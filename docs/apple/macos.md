---
layout: default
title: macOS
parent: Apple
---

# macOS

## Problem solving

### If Apple Mail takes forever to open…

Delete `~/Library/Containers/com.apple.mail` which contains the mail preferences.

After that you have to set up a few things again but nothing major.

In particular, it might be this file causing the issue: 

```
~/Library/Containers/com.apple.mail/Data/DataVaults/MailBundles/Library/Mail/Bundles/Properties.plist
```

