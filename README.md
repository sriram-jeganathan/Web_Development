# HTML

## 1. Notes on HTML Tags

| Tag             | Definition                          | Attributes                          | Uses                             | Pros/Cons                                             | Example |
|-----------------|-------------------------------------|-------------------------------------|----------------------------------|------------------------------------------------------|---------|
| `<html>`        | Root element of HTML document       | `lang`                              | Defines language of the page     | Adv: Standard starting point <br> Disadv: must close | `<!DOCTYPE html><html lang="en">...</html>` |
| `<head>`        | Container for metadata              | `title`, `meta`, `link`, `style`    | Holds metadata, resources        | Adv: Stores info <br> Disadv: No visible output       | `<head><title>My Page</title></head>` |
| `<title>`       | Sets browser tab title              | None                                | SEO + tab name                   | Adv: Helps SEO <br> Disadv: Only text                 | `<title>My Website</title>` |
| `<meta>`        | Provides metadata                   | `charset`, `name`, `content`        | SEO, responsiveness              | Adv: SEO boost <br> Disadv: No visible output         | `<meta charset="UTF-8">` |
| `<body>`        | Visible page content                | `bgcolor`, `text`                   | Main container                   | Adv: Holds content <br> Disadv: Heavy use = slow      | `<body><h1>Hello</h1></body>` |
| `<h1>`–`<h6>`   | Headings (largest → smallest)       | `align`                             | Structure + SEO                  | Adv: Semantic <br> Disadv: Overuse confuses SEO       | `<h1>Main Title</h1>` |
| `<p>`           | Defines paragraph                   | `align`                             | Text blocks                      | Adv: Readability <br> Disadv: Limited formatting      | `<p>This is a paragraph.</p>` |
| `<a>`           | Defines hyperlink                   | `href`, `target`, `rel`             | Navigation                       | Adv: Connects docs <br> Disadv: Broken links bad UX   | `<a href="https://example.com" target="_blank">Visit</a>` |
| `<img>`         | Embeds image                        | `src`, `alt`, `width`, `height`     | Visuals                          | Adv: Engages users <br> Disadv: Slow if big           | `<img src="pic.jpg" alt="Example">` |
| `<br>`          | Line break                          | None                                | Break line                       | Adv: Simple <br> Disadv: Overuse = messy layout       | `Line1<br>Line2` |
| `<hr>`          | Horizontal line                     | `size`, `width`, `color`            | Thematic break                   | Adv: Clear separation <br> Disadv: Not semantic       | `<hr>` |

---

## 1.1 Text Formatting Tags

| Tag       | Definition               | Example | Output |
|-----------|--------------------------|---------|--------|
| `<b>`     | Bold text (non-semantic) | `<b>Bold</b>` | **Bold** |
| `<strong>`| Important text (semantic)| `<strong>Important</strong>` | **Important** |
| `<i>`     | Italic text (non-semantic)| `<i>Italic</i>` | *Italic* |
| `<em>`    | Emphasized text (semantic)| `<em>Emphasized</em>` | *Emphasized* |
| `<u>`     | Underlined text          | `<u>Underlined</u>` | <u>Underlined</u> |
| `<mark>`  | Highlighted text         | `<mark>Highlight</mark>` | <mark>Highlight</mark> |
| `<sub>`   | Subscript (below text)   | `H<sub>2</sub>O` | H₂O |
| `<sup>`   | Superscript (above text) | `x<sup>2</sup>` | x² |
| `<del>`   | Deleted/strikethrough    | `<del>Old</del>` | ~~Old~~ |

**Key Point:**  
- `<b>` vs `<strong>` → both look bold, but `<strong>` adds semantic meaning (screen readers read it as “important”).  
- `<i>` vs `<em>` → same style, but `<em>` adds emphasis meaning.  
- `<u>`, `<mark>` are purely presentational.  
- `<sub>` and `<sup>` often appear in science/maths.  

---

# CSS [ Cascading Style Sheet ]

## Types of CSS

### External CSS

An HTML file is styled using an external CSS file, which is connected using the line: 

`<link rel="stylesheet" href="style.css">`

### Internal CSS

An HTML file can be styled using the <style> element, which is typically placed inside the document's <head> section.
```
<style>
  tag {
    // Attributes
  }
</style>
```

### Inline CSS
A HTML tag can be styled indivually by using the style attribute.
`<tag style=""></tag>`
