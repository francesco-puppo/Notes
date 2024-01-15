---
layout: default
title: Research
has_children: true
has_toc: true
---

# {{ page.title }}

I use Omnivore to save research-related articles and read them later.

It's nice because it's free and open-source, it has highlights, and it syncs with [Obsidian](/docs/apps/note-taking/obsidian).
  
<details>
<summary>
My setup
</summary>

I use the [Omnivore plugin for Obisidian](https://github.com/omnivore-app/obsidian-omnivore) to sync only the highlights of the articles I read, plus a link to the original source, one to Omnivore, and a few other details.

To do this, I filtered the plugin to **only fetch articles that have been highlighted**, and I tweaked the **article template** to collect only what I'm interested in:

```
# {{{title}}}

{{note}}

{{#highlights.length}}
## Highlights

{{#highlights}}
> {{{text}}}
{{#note}}

{{{note}}}
{{/note}}

{{/highlights}}
{{/highlights.length}}

---

- [Source]({{{originalUrl}}})
- [Read on Omnivore]({{{omnivoreUrl}}})

<div class="omni-footer>
<p>Saved on: {{dateArchived}}</p>
</div>
```

And I changed the **Front Matter template** to fit into Jekyll's template

```
id: {{{id}}}
layout: default
title: {{{title}}}
parent: Research
```

</details>
