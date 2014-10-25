---
layout: post
title: "launchpad is not saving in yosemite"
date: 2014-10-25 12:47:44 +0800
comments: true
categories: OSX, Yosemite
---
When you updated your Mac to Yosemite, the launchpad always reset when you restart your mac, you can follow these steps to fix.

1. ```$ rm -rf /Library/Application Support/Dock```

2. ```$ killall Dock```

3. Put your application icons back where they were.

Restart!
