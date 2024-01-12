---
layout: default
title: Meta
last_updated: 2024-01-12T15:45:00
has_children: true
has_toc: true
---

# Meta

This website runs on [Jekyll](https://jekyllrb.com/), which means it’s basically a collection of markdown files, and is hosted on [GitHub](https://pages.github.com/). 

The template I used is called [Just the Docs](https://just-the-docs.com/), which I modified a bit. 

I tried to set it up in a way that is easy for me to edit and maintain. [^happy]

## Setup

Everything is hosted on GitHub (in [this repository](https://github.com/francesco-puppo/Notes)) and, locally, I store the project in a folder synced with iCloud.

To edit these files I mainly use Nova or VS Code (see [Text Editors / Code](/docs/apps/text-editors.html#code)), unless I have to write some form of long-text content, in which case I use iA Writer (see [Text Editors / Markdown](/apps/text-editors#markdown)).

## Structure

The structure of the files follow the instructions from Just the Docs and it looks like this:

```
┣ ⚙️ _config.yml
┃
┣ 📁 _includes
┃ ┃
┃ ┗ 📄 (custom layouts)
┃ 
┣ 📁 _saas
┃ ┃
┃ ┗ 📄 (custom styling)
┃ 
┣ 📁 assets
┃ ┃
┃ ┗ 📄 (photos, favicon, etc.)
┃
┣ 📁 docs (all notes are stored in here)
┃ ┃
┃ ┣ 📁 topic 1
┃ ┃ ┃
┃ ┃ ┣ 📄 index.md
┃ ┃ ┃
┃ ┃ ┗ 📄 page.md
┃ ┃
┃ ┗ 📁 topic 1
┃   ┃
┃   ┣ 📄 index.md
┃   ┃
┃   ┗ 📄 page.md
┃  
┣ 💎 Gemfile
┃
┣ 📄 index.md (the homepage)
┃
┗ Other varius pages
```

The folder `docs` store all the actual pages in Markdown format. 

I also added it to iA Writer and Obsidian so I am able to edit them from there as well, without the need to navigate through the Finder or open VS Code.

[^happy]: Even if I'm quite happy with the result, I know it could be improved. Unfortunately, I lack the technical skills.