# HTML Unit I – Notes & Question Bank

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

## 2. Question Bank

### Part A – 2 Marks
1. Define HTML and list its advantages.  
2. What is the use of `<title>` tag?  
3. List attributes of `<meta>` tag with example.  
4. Differentiate `<br>` and `<hr>`.  
5. Write syntax for creating a hyperlink.  
6. Write difference between `<b>` and `<strong>`.  
7. Give an example of `<sub>` and `<sup>`.  

### Part B – 5 Marks
1. Explain different types of heading tags with examples.  
2. Write a short note on `<body>` tag and its attributes.  
3. Discuss the uses and limitations of `<img>` tag.  
4. Describe `<a>` tag with attributes and examples.  
5. Explain metadata tags and their importance.  
6. Compare text formatting tags `<b>`, `<i>`, `<u>`, `<em>`.  

### Part C – 10 Marks
1. With examples, explain the structure of an HTML document.  
2. Discuss all text formatting tags in HTML with examples.  
3. Compare and contrast block-level and inline elements with examples.  
4. Write an HTML code to design a webpage that includes heading, paragraph, image, and a hyperlink.  
5. Explain the importance of SEO-related tags (`<title>`, `<meta>`) with examples.  
6. Design a sample webpage that demonstrates **bold, italic, underline, highlight, subscript, and superscript** text.  
