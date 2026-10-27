# CSS - Advanced

## Description
This project styles the **Techium** homepage (`index.html`) from scratch, one concern at a time. The `styles/` folder contains 32 **cumulative** stylesheets: each `N-style.css` contains everything from the previous one plus one new feature, going from smooth scrolling and colors to a CSS-variable design system, a float-based grid, components (buttons, cards, navigation) and transitions.

`index.html` currently links `styles/27-style.css` (the hero section step); change the `<link>` to try another step.

## 📝 Learning Objectives
* Use CSS custom properties (`:root`, `var(--name)`) to build a maintainable design system.
* Control typography: `font-family`, `rem`-based sizing (`62.5%` root trick), `font-weight`, `line-height`, `text-transform`.
* Style link states with `:link`, `:visited`, `:hover` and `:active`.
* Reset browser defaults with `normalize.css` and `box-sizing: border-box`.
* Build layouts with a fixed-width `.container` and a float-based grid (`.row`, `.col-*`, clearfix).
* Theme sections with attribute selectors (`[data-section-theme="dark"]`).
* Create reusable components: buttons, cards, navbar, header logo, hero.
* Position elements (`relative`/`absolute`), use pseudo-elements (`::before`) and `object-fit`.
* Animate state changes with `transition` and `transform`.

## 🛠️ Requirements & Engineering Constraints
* **Fonts:** [Open Sans](https://fonts.google.com/specimen/Open+Sans) and [Raleway](https://fonts.google.com/specimen/Raleway) (loaded from Google Fonts in `index.html`).
* **Reset:** `normalize.css` 8.0.1 imported from cdnjs (from `14-style.css`).
* **Design tokens:** colors (`--color-primary: #d73953`, black, white, greys), font sizes, weights and line heights are declared as variables on `:root`.
* **Files:** All files end with a new line.

## 📁 File List & Tasks Directory

| File | Task Title | Description |
| :--- | :--- | :--- |
| `index.html` | Techium homepage | HTML page styled by the stylesheets below. |
| `images/` | Assets | Pictures, logos and favicon used by the page (see [images/README.md](images/README.md)). |
| `styles/1-style.css` | Smooth scroll | Enables `scroll-behavior: smooth` on `html`. |
| `styles/2-style.css` | Colors | Sets text and link color, hides `.visually-hidden`, colors the card category and section tagline. |
| `styles/3-style.css` | Color variables | Moves the colors to custom properties declared on `:root`. |
| `styles/4-style.css` | Font family | Adds base and title font-family variables, applied to the body and headings. |
| `styles/5-style.css` | Font sizes | Sets `html` font-size to `62.5%` and adds a `rem` font-size scale. |
| `styles/6-style.css` | Font weights | Adds regular/bold weight variables. |
| `styles/7-style.css` | Web fonts | Switches to Open Sans (base) and Raleway (titles). |
| `styles/8-style.css` | Line heights | Adds small/base/big line-height variables. |
| `styles/9-style.css` | Link decoration | Removes the underline from links. |
| `styles/10-style.css` | Section header | Centers `.section-header` through a variable. |
| `styles/11-style.css` | Section tagline | Styles `.section-tagline` / `.card-category` (title font, uppercase, bold). |
| `styles/12-style.css` | Section title | Styles `.section-title` (size, weight, margin, color). |
| `styles/13-style.css` | Link states | Styles `:link`, `:visited`, `:hover` and `:active`. |
| `styles/14-style.css` | Normalize | Imports `normalize.css` 8.0.1. |
| `styles/15-style.css` | Box sizing | Applies `box-sizing: border-box` to every element. |
| `styles/16-style.css` | Container | Adds a centered 960px `.container`. |
| `styles/17-style.css` | Section spacing | Adds padding variables for `.section`, header, body and footer. |
| `styles/18-style.css` | Navigation | Styles `.navbar-menu` (floated right) and the `.nav` items, links and hover color. |
| `styles/19-style.css` | Grid | Adds `ul.row` reset and the `.col-1-3` / `.col-1-2` float columns. |
| `styles/20-style.css` | Clearfix | Adds `.row::after` to clear floats. |
| `styles/21-style.css` | Grid refinement | Reworks the column rules (`.col-1-3` width). |
| `styles/22-style.css` | Dark theme | Adds `[data-section-theme="dark"]` (white text on black background). |
| `styles/23-style.css` | Stylesheet organization | Reorganizes the file into numbered sections (variables, base, layout, components, navigation, footer, utilities). |
| `styles/24-style.css` | Service cards | Styles `.card-services` links (padding, grey background, primary color on hover). |
| `styles/25-style.css` | Buttons | Adds the `.button` component with variables and hover state. |
| `styles/26-style.css` | Testimonial cards | Centers testimonials, round avatar (`border-radius: 50%`) and colored `cite`. |
| `styles/27-style.css` | Hero section | Styles `.section-hero` (background size, title margin, inner padding). |
| `styles/28-style.css` | Header and logo | Adds header padding and the absolutely positioned logo link. |
| `styles/29-style.css` | Navigation underline | Adds the animated-underline `::before` on `.nav-link` and the hover colors. |
| `styles/30-style.css` | Work cards | Styles `.card-work` (overflow hidden, `object-fit: cover` images, overlay). |
| `styles/31-style.css` | Quote mark | Adds the large decorative quotation mark (`::before`) on testimonials. |
| `styles/32-style.css` | Transitions | Adds `transition` variables, scale-on-hover for work cards and smooth color transitions. |

---

## 🚀 Viewing the Page

Open the page in a browser (it links the stylesheet currently set in `index.html`):

```bash
xdg-open index.html
```

To preview another step, edit the `<link rel='stylesheet' href='styles/27-style.css'>` line in `index.html`.

---

## 👤 Author
* **Student:** [RebornLPB](https://github.com/RebornLPB)
* **GitHub:** [https://github.com/RebornLPB](https://github.com/RebornLPB)
* **School:** [Holberton School](https://www.holbertonschool.com/)
