---
title: Origin
---

This is your index page. You can edit its contents at `docs/01-index.hbs`

## Markdown Helper

[Markdown helper](https://github.com/helpers/helper-markdown) using [remarkable](https://github.com/jonschlinkert/remarkable) with [typographer](https://github.com/jonschlinkert/remarkable#typographer) option.

```
\{{ markdown text }}
```
```
\{{ markdown "paragraph" }}
```

or block helper:

```
\{{# markdown }}
\{{ text }}
\{{/ markdown }}
```
```
\{{# markdown }}
paragraph
\{{/ markdown }}
```
