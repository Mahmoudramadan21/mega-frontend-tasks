# Professional Creative Agency Website - HTML5 Mastery Challenge (Part 2)

## Challenge Overview
This is the **second and final** HTML mastery challenge, covering **Lessons #19 to #37** from the legendary series **"Learn HTML in Arabic 2021"** by Elzero Web School.

You are required to build a complete, production-ready **single-page website for a creative digital agency** using **pure HTML5 only** (no CSS or JavaScript allowed except where explicitly permitted).

The goal is to prove **complete mastery** of:
- Modern Semantic HTML5
- Advanced forms & input types
- Media embedding (audio/video)
- Accessibility (a11y) & ARIA
- Internationalization (Arabic + English bidirectional text)

## Project Name
**PixelPulse Agency – One-Page Professional Website**

## Requirements Summary

| Category                  | Must Include                                                                                  |
|---------------------------|------------------------------------------------------------------------------------------------|
| Validity                  | 100% valid HTML5 – passes W3C Validator with **0 errors & 0 warnings**                        |
| Semantic Structure        | Correct use of `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`, `<figure>`, etc. |
| Accessibility             | Full ARIA landmarks, labels, roles, and screen-reader optimization – passes WAVE / axe with 0 errors |
| Forms                     | One fully-featured contact form using **every** HTML form concept from lessons #24–#32         |
| Media                     | `<audio>` + `<video>` with controls, tracks, and fallback content                             |
| Embedding                 | At least one `<iframe>` (e.g., Google Maps or YouTube video)                                   |
| Internationalization      | Bilingual content (Arabic + English) with proper `dir="rtl"` / `dir="ltr"` and `<bdi>` usage   |
| All New Elements          | Must use **every** element introduced in lessons #19–#37 at least once                         |

## Mandatory Page Sections (in order)

1. **Header & Navigation** (`<header>`, `<nav>`)
2. **Hero Section** with background `<video>` or prominent `<video>`
3. **About Us** (`<section>`, `<blockquote>`, `<q>`, `<wbr>`, `<bdi>`)
4. **Services** using semantic `<dl>` (definition list)
5. **Portfolio Gallery** using `<figure>` + `<figcaption>`
6. **Testimonials** with `<blockquote>` and bidirectional names
7. **Contact Form** – the heart of the challenge (see detailed form specs below)
8. **Location Map** using `<iframe>`
9. **Footer** with copyright, social links, `<pre><code>`, `<time>`, etc.

## Contact Form – Must Contain All of These

- `<form action="" method="POST" target="_blank" novalidate>`
- Grouped with `<fieldset>` + `<legend>`
- Every input type:
  - `text`, `email`, `tel`, `url`, `search`
  - `number`, `range`, `color`
  - `date`, `time`, `datetime-local`
  - `file` (with `multiple`)
  - `radio`, `checkbox`
  - `<select>` with `<optgroup>`
  - `<textarea>`
  - `<datalist>`
  - `hidden`
- Attributes: `required`, `placeholder`, `autofocus`, `disabled`, `readonly`, `min`, `max`, `step`, etc.
- Proper `<label for="id">` connection
- `<button type="submit">` and `<button type="reset">`
- Bonus elements: `<output>`, `<meter>`, `<progress>` (e.g., for form completion indicator)

## Must Use These Elements At Least Once

| Element          | Required Usage Example                          |
|------------------|-------------------------------------------------|
| `<main>`         | Wrap primary content                            |
| `<article>`      | For testimonials or portfolio items             |
| `<aside>`        | Sidebar or additional info                      |
| `<details>` / `<summary>` | FAQ or extra info                         |
| `<mark>`         | Highlight important text                        |
| `<time datetime="">` | Dates in footer or events                    |
| `<bdi>`          | Names mixing Arabic & English                   |
| `<wbr>`          | In very long words or URLs                      |
| `<pre><code>`    | Show a small HTML snippet in footer             |
| `<output>`       | Display calculated value (even if static)       |
| `<meter>` / `<progress>` | Visual indicators (can be static)            |

## Accessibility Requirements

- All ARIA landmarks (`role="banner"`, `navigation`, `main`, `contentinfo`, etc.)
- `aria-labelledby`, `aria-label`, `aria-hidden` where needed
- Proper heading hierarchy (h1 → h2 → h3…)
- Meaningful `alt` attributes on every `<img>`
- `<video>` and `<audio>` must have `<track kind="captions">` (even if src is empty)

## Project Structure

```
pixelpulse-agency/
├── index.html
├── README.md
└── assets/
    ├── images/
    ├── audio/
    └── video/
```

## Submission Checklist

- [ ] Single `index.html` file
- [ ] All assets in `assets/` folder with correct relative paths
- [ ] W3C Validator result: **0 errors, 0 warnings** (include screenshot or link)
- [ ] WAVE or axe Accessibility Test: **0 errors**
- [ ] Bilingual content (Arabic + English) with correct text direction
- [ ] Every concept from lessons #19–#37 is used and highlighted in comments
- [ ] README.md includes:
  - Live demo link (GitHub Pages / CodePen / etc.)
  - Validator & accessibility report links/screenshots
  - Short explanation of where each new concept was applied

## Bonus (Legendary Status)

- Add a hidden Easter egg using `<details><summary>`
- Make the form look organized even without CSS (using `<table>` or proper spacing with ` ` and `<br>`)
- Include a downloadable PDF brochure using `<a download>`

## Who Completes This Challenge?
You are officially an **HTML5 Grandmaster** and ready to dominate CSS, JavaScript, and modern front-end frameworks without ever looking back.

Ready?  
Reply with **"I'm in!"** and I’ll send you a clean starter template if you want.

Good luck, future web legends! 🚀
