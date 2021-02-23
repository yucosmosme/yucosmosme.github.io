---
title: "[error]dns_probe_finished_nxdomain,ERR_NAME_NOT_RESOLVED "
categories:
  - Dev
tags:
  - domain
  - nginx
  - dns error
  - a record
date: 2021-02-23 17:31
comments: true 
---

I had to change my domain hosting from AWS route53 to other domain hosting service. and I got this error : `dns_probe_finished_nxdomain` from chrome.

- ![Image Alt error](/assets/images/posts/err1.png)
*error: dns_probe_finished_nxdomain*
 
And `ERR_NAME_NOT_RESOLVED` from MS edge.

- ![Image Alt error](/assets/images/posts/err2.png)
*error: ERR_NAME_NOT_RESOLVED*

That simply refers that domain is not connected to IP address. There could be several reasons for that. Main reason is server's DNS service is set wrong. In my case I didn't put A record on the hosting. Two hours after A record had been filled, the error was gone. It was that simple!

If it still doesn't work, there are other ways to look into:

- flush dns cache
- check if web server softwear such as nginx setting is written correctly.
- clean cookies and caches.
