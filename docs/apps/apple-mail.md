---
layout: default
title: Apple Mail
parent: Apps
last_modified: 2024-01-15 15:32
---

# {{ page.title }}

I manage both my work and personal emails using only Apple Mail.\
Some find it limited, I love it exactly because of that.

## How I use it

### Folder structure

```
┏  📬 Inbox
┃
┣  📁 Actions
┃
┣  📁 Updates
┃
┣  📁 On hold
┃
┗ 🗄️ Archive
  ┃
  ┣ 📁 Reference
  ┃
  ┗ 📁 Newsletters
```

- Anything that is needed in the short term (i.e. 1 week) goes in the `Actions` folder.
- If it's a notification from another app (i.e. Figma or DevOps) it goes in the `Updates` folder
- If I receive something that I know I'll need soon enough, it goes in `On hold`.
- Anything else goes in the `Archive`. If it's useful information I'll toss it in the reference `Folder` and if it's a newsletter it'll automatically go in `Newseletters`.

### Flags

I try to use flags / labels sparingly:

- **🔴 Urgent:** For anything that has top priority
- **🔵 Updates:** For notifications from various apps and automated using rules
- **🟢 Newsletters:** Automated using rules
- **🟡 External addresses:** Used only on my work and automated using rules


### Rules

I have a bunch of rules to help me clean up the inbox automatically and flag things for me to notice.

#### Newsletters - Unsubscribe

This rule checks if the email has been sent to my personal[^personal] account and if the message contains the word "Unsubscribe". If so, it'll move it to the `Newsletters` folder and flag it with a green marker [^marker].
![](/assets/images/2024-01-15_mail-filters-01.png)

[^personal]: If you use a separate email address just for newsletters it's even better
[^marker]: This step is actually not needed but I do it anyway