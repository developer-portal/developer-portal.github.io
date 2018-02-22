---
section: doc
page_menu_hl: markdown-hints
layout: documentation
---

# Markdown hints
Learn more about markdown in this [Mastering Markdown guide](https://guides.github.com/features/mastering-markdown/).

## Tables

You can use different formatting for your markdown tables by prepending them with one, or a combination of, these properties:

* `.bordered` - The table will have borders.
* `.centered` - Text will be centered in the cells.
* `.striped` - Every other row will have different background color.
* `.highlight` - Hovering over the table will highlight rows.

Example:

```
{: .centered .striped .highlight}
| This is centered and striped table. | It has heading. |
|---|---|
| Two columns | Two rows |
| No borders | And it highlights rows! |
```
