---
layout: post
title: "custom subdomain in Octopress with Github page"
date: 2014-09-17 20:24:57 +0800
comments: true
categories: git
---
Follow these step after you deploy your octopress to github page.

First, you need to create a file named ``` CNAME ``` in your blog's source:
```
echo 'subdomain.your-domain.com' >> source/CNAME
```
commit this file and deploy your changes.

Second, you must use an ```A``` record pointing to ```192.30.252.153``` or ```192.30.252.154```, and use an ```ALIAS``` record put ```subdomain.your-domain.com``` point to ```username.github.io```.

All done!
