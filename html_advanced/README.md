# HTML - Advanced

## Description
This project builds the HTML structure of **Techium**, a fictional digital-agency website, one step at a time. It starts from an empty document and progressively adds the document skeleton, semantic landmarks, headings, content, navigation, links, images, and finally a complete **styleguide** page showcasing every common HTML element.

Most numbered files are **cumulative snapshots**: each `N-index.html` extends the previous one with a new feature. The un-numbered files (`index.html`, `about.html`, `contact.html`, `latest_news.html`, `article.html`, `styleguide.html`) are the final pages.

## 📝 Learning Objectives
* Write a valid HTML5 document (`<!DOCTYPE html>`, `lang`, `dir`, `<head>` metadata, favicons, viewport).
* Structure a page with semantic elements: `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`.
* Use the heading hierarchy (`h1` to `h6`), paragraphs, lists, `blockquote`/`cite`, `address`, `small`, `hr`.
* Create internal and external links, anchors, and navigation menus.
* Embed images with explicit dimensions and alternative text.
* Embed media and interactive elements: `table`, `details`/`summary`, `video`, `audio`, `iframe`.
* Document code with `<!-- comments -->` and keep the markup free of presentational attributes.

## 🛠️ Requirements & Engineering Constraints
* **Markup only:** These pages contain structure and content; no stylesheet is linked (styling is handled in the [`CSS_advanced`](../CSS_advanced/) project).
* **Validation:** Pages are meant to be valid HTML5 (checkable with the W3C validator).
* **Files:** All files end with a new line.

## 📁 File List & Tasks Directory

### Homepage (`index` chain)

| File | Task Title | Description |
| :--- | :--- | :--- |
| `0-index.html` | Empty document | Bare `<!DOCTYPE html>` and `<html>` tag with `lang="en"` and `dir="rtl"`. |
| `1-index.html` | Head and body | Adds empty `<head>` and `<body>` elements. |
| `2-index.html` | Metadata | Adds charset, viewport, `<title>`, description and favicons. |
| `3-index.html` | Page landmarks | Adds `<header>`, `<main>` and `<footer>`. |
| `5-index.html` | Page sections | Splits `<main>` into the hero, services, works, about, latest news, testimonials and contact sections. |
| `6-index.html` | Articles | Adds three `<article>` elements to the works, latest news and testimonials sections. |
| `7-index.html` | Navigation | Adds an empty `<nav>` inside the header. |
| `8-index.html` | Main title | Adds the `<h1>` page title. |
| `9-index.html` | Section titles | Adds an `<h2>` to every section. |
| `10-index.html` | Sub-titles | Adds `<h3>` titles to services, works, news and testimonials items. |
| `12-index.html` | Paragraphs | Fills the sections with `<p>` content. |
| `14-index.html` | Brand name | Adds the "Techium" `<span>` in the header. |
| `15-index.html` | Content wrappers | Wraps content blocks in `<div>` elements. |
| `16-index.html` | Article structure | Adds `<header>` and `<div>` inside each article. |
| `17-index.html` | Comments | Documents each part of the page with HTML comments. |
| `18-index.html` | Logo link | Wraps the brand name in a link to the homepage. |
| `20-index.html` | Navigation links | Adds the menu links (Home, Services, Works, About, Latest news, Testimonials, Contact). |
| `21-index.html` | Social links | Adds Facebook, Twitter and Instagram links to the footer. |
| `22-index.html` | Calls to action | Adds the "Get Started", "Learn more about us" and "Get in touch" links. |
| `23-index.html` | Service links | Turns service and work titles into links. |
| `24-index.html` | Navigation list | Rewrites the menu as a `<ul>` / `<li>` list. |
| `25-index.html` | Legal links | Adds the Terms of Use, Privacy Policy and Cookie Policy list to the footer. |
| `27-index.html` | Copyright | Adds an `<hr>` and the copyright line. |
| `29-index.html` | Testimonials | Marks up testimonials with `<blockquote>` and `<cite>`. |
| `31-index.html` | Authors and address | Adds `<small>` article authors and an `<address>` block. |
| `35-index.html` | Logo image | Replaces the text logo with the `logo-black.png` image. |
| `36-index.html` | Content images | Adds the work, about and blog pictures. |
| `index.html` | Final homepage | Complete Techium homepage. |

### Styleguide (`styleguide` chain)

| File | Task Title | Description |
| :--- | :--- | :--- |
| `11-styleguide.html` | Headings | Styleguide skeleton with the `h1` to `h6` heading levels. |
| `13-styleguide.html` | Paragraph | Adds a heading with a subtitle and a paragraph. |
| `26-styleguide.html` | Lists | Adds unordered, ordered and definition lists. |
| `28-styleguide.html` | Horizontal rule | Adds the `<hr>` section. |
| `30-styleguide.html` | Blockquotes | Adds inline quote (`<q>`) and `<blockquote>` examples. |
| `32-styleguide.html` | Typography | Adds `address`, `pre`/`code`, `mark` and `cite` examples. |
| `33-styleguide.html` | Table | Adds a table with caption, header and body (Star Wars trilogy data). |
| `34-styleguide.html` | Details | Adds default and open `<details>` / `<summary>` examples. |
| `38-styleguide.html` | Video | Adds an HTML5 `<video>` player with fallback text. |
| `39-styleguide.html` | Audio | Adds an HTML5 `<audio>` player with fallback text. |
| `styleguide.html` | Final styleguide | Complete styleguide, ending with an `<iframe>` YouTube embed. |

### Other pages and assets

| File | Description |
| :--- | :--- |
| `about.html`, `contact.html`, `latest_news.html` | Secondary pages sharing the homepage layout, each with its own `<h1>`. |
| `article.html` | Article page skeleton with an `<aside>`. |
| `images/` | Pictures used by the pages (work, blog, person and about images). |
| `logo-black.png`, `favicon.*`, `apple-touch-icon.png` | Logo and icons referenced from the pages. |

---

## 🚀 Viewing the Pages

Open any file directly in a browser:

```bash
xdg-open index.html
```

Or serve the folder locally:

```bash
python3 -m http.server 8000
```

---

## 👤 Author
* **Student:** [RebornLPB](https://github.com/RebornLPB)
* **GitHub:** [https://github.com/RebornLPB](https://github.com/RebornLPB)
* **School:** [Holberton School](https://www.holbertonschool.com/)
