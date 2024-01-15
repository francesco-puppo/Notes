---
layout: default
title: Obsidian + Omnivore
parent: Obsidian
---

# {{ page.title }}

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