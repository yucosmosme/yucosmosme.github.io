---
title: "[error] mysql - select - special character error"
categories:
  - Dev
tags:
  - mysql
  - node-mysql
  - regular expression
  - single quotation mark error
  - special character error
date: 2021-02-26 18:30
comments: true 
---

> On search function (SELECT, SELECT LIKE in mysql), there occured error when single quotation mark was searched.

To show the difference, on mysql workbench, if search contents were normal text, it would apear as below.

![Image Alt error](/assets/images/posts/20210226_155918.png)

But if there is single quotation mark inside search content, error occurs. This happens when there is already quotation mark set in the query. considering single quotation mark in the search content as part of the query.

![Image Alt error](/assets/images/posts/20210226_155946.png)
 
Solution is to add another single quotation mark `'` or back slash `\` infront of single quotation mark as below images.

![Image Alt error](/assets/images/posts/20210226_160001.png)

![Image Alt error](/assets/images/posts/20210226_160016.png)

To do so, I simply added one line on my backend code (node.js) using regular expression.

```js
search = search.replace(/(['])/g, '\\$1')
```

- When replacing in regular expression, pattern `/()` will be replaced by `$1`.  
If there are two patterns like `/() ()`, first pattern will be replaced by `$1` and second one by `$2`.

- `g` is for global search. Without `g`, it will only search first pattern.

- `[]` means character set. in the `[]` all the characters are just characters, so special characters don't need to be escaped.
You can assign character range using `-` inside `[]`.  
e.g. [a-c] is same as [abc]

- Backslash before special character means 'any character after backslash will be considered only as normal characters'.    
So to add one back slash in the character set, another backslash should be added to escape.




