# Academic Markdown

![GitHub](https://img.shields.io/github/license/mashape/apistatus.svg)

![Snippets in action](./academic-md.gif)

_A set of atom snippets for writing academic materials with markdown._

## Install

```sh
  apm install academic-markdown
```

## Pandoc metadata

Pandoc metadata are always placed at the begining of markdown files.

### Article metadata _(article)_

```md
---
author:
title:
date:
documentclass: article
---


```

### Book metadata _(book)_

```md
---
author:
title:
date:
documentclass: book
---


```
### Memoir metadata _(memoir)_

```md
---
author:
title:
date:
documentclass: memoir
---


```

### Presentation metadata _(presentation)_

```
---
author:
title:
date:
transition: convex #cube
theme: black
---

```

### Report metadata _(report)_

```md
---
author:
title:
date:
documentclass: report
---


```

## Reveal.js snippets

### Speaker notes _(notes)_

```md
:::notes

:::

```

### A slide with a custom image background _(background)_

```
# [slide title] {.slide: data-background="[path/to/background/img]"}


```

## Bibliography

### Cite all bibliography entries including uncited items _(bibliography)_

```md
---
nocite: '@*'
...

```

### Cite a reference _(cite)_

```md
[@[reference_key], [pages]]
```
