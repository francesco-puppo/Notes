---
layout: default
title: macOS
parent: Apple
has_children: true
---

# macOS

## The Mac as a place, not a thing

> To me the Macintosh has always felt more like a place than a thing. Not a place I go physically, but a place my mind goes intellectually. <mark>When I’m working or playing and in the flow, it has always felt like MacOS is where I am.</mark> I’m in the Mac. Interruptions — say, the doorbell or my phone ringing — are momentarily disorienting when I’m in the flow on the Mac, because I’m pulled out of that world and into the physical one.\
> – [John Gruber (Daring Fireball)](https://daringfireball.net/2023/06/first_impressions_of_vision_pro_and_visionos)


## Problem solving

### If Apple Mail takes forever to open…

Delete `~/Library/Containers/com.apple.mail` which contains the mail preferences.

After that you have to set up a few things again but nothing major.

In particular, it might be this file causing the issue: 

```
~/Library/Containers/com.apple.mail/Data/DataVaults/MailBundles/Library/Mail/Bundles/Properties.plist
```

