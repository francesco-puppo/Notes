---
layout: default
title: CSS
parent: Coding
---

# CSS

## Snippets

### Media queries

```css
/*** Affects mobile ***/
@media screen and (max-width: 800px) {
}
```

### Dark theme

```css
@media (prefers-color-scheme: dark) {
  :root {
    --theme: #070b11;
    --content: #cbd5e1;
    --primary: #00bfff;
    --secondary: #0f3f68;
    --markdown: #2b486f;
    --code-text: #508ec5;
    --code-bg: #041d36;
  }
}
```


### Default fonts

```css
body {
	font-family: system-ui, -apple-system, blinkmacsystemfont, "Segoe UI", roboto, "Helvetica Neue", arial, sans-serif, "Segoe UI Emoji";
}
```

## Resources

- [Beautiful CSS shadows](https://getcssscan.com/css-box-shadow-examples)