# Academic Markdown

![GitHub](https://img.shields.io/github/license/mashape/apistatus.svg)

![Snippets in action](./academic-md.gif)

_A set of atom snippets that helps you to write academic materials with markdown._

## Suggest a snippet

Open an issue [issue](https://github.com/Eonm/academic-md/issues/new?assignees=Eonm&labels=Snippet+submition&template=submit-a-snippet.md&title=%5BAdd+snippet%5D) on github.

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
classoption: twoside #oneside
---


```

### Book metadata _(book)_

```md
---
author:
title:
date:
documentclass: book
classoption: twoside #oneside
---


```
### Memoir metadata _(memoir)_

```md
---
author:
title:
date:
documentclass: memoir
classoption: twoside #oneside
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
classoption: twoside #oneside
---


```

### Bibliorapy metadata _(bibliography)_

```md
bibliography:
csl:
```

### Papersize _(a4)_

```md
papersize: a4
```

### Papersize _(letter)_

```md
papersize: a4
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

### Cite all bibliography entries including uncited items _(bibliography-no-cite)_

```md
---
nocite: '@*'
...

```

### Cite a reference _(cite)_

```md
[@[reference_key], [pages]]
```
