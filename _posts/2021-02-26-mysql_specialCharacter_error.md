---
title: "[error] mysql - select - special character error"
categories:
  - Dev
tags:
  - mysql
  - node-mysql
  - regular expression
date: 2021-02-26 18:30
comments: true 
---

> On search function (SELECT, SELECT LIKE in mysql), there occured error when single quotation mark was searched.

If search contents were normal text, it would apear as below.
- ![Image Alt error](/assets/images/posts/20210226_155918.png)

But if there is single quotation mark inside search content, error occurs. This was because there was already quotation mark set in the query, so single quotation mark in the search content was considered as part of sql query.
- ![Image Alt error](/assets/images/posts/20210226_155919.png)
 
Solution is to add another single quotation mark `'` or back slash `\` infront of single quotation mark as below images.
- ![Image Alt error](/assets/images/posts/20210226_155920.png)
- ![Image Alt error](/assets/images/posts/20210226_155921.png)

To do so, I simply added one line on my backend code (node.js) using regular expression.

```js
search = search.replace(/(['])/g, '\\$1')
```

When replacing in regular expression, patter `/()` will be replaced by `$1`.  
If there is two patterns like `/() ()`, first pattern will be replaced by `$1` and second one by `$2`.

`g` is for global search. Without `g`, it will only search first ones.

`[]` means character set. in the `[]` all the characters are just characters, so special characters don't need to be escaped.
You can assign character range using `-` inside `[]`.

e.g. [a-c] is same as [abc]

Backslash before special character means 'any characters after backslash is considered only as normal characters.'.  
So to add one back slash in the character set, another backslash should be added.




