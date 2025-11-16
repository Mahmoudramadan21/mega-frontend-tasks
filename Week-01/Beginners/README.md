```markdown
# HTML Mastery Challenge - MEGA TEAM

## Description
This challenge tests your **complete mastery** of **"Learn HTML in Arabic 2021"** lessons **#01 to #18**.

You will build a **fully semantic, accessible, responsive "Personal Portfolio Page"** using **only HTML** (no CSS/JS yet). The page must:
- Be **valid HTML5**
- Use **semantic elements** correctly
- Be **accessible** (ARIA, alt text, etc.)
- Include **all concepts** from the 18 lessons
- Validate with **W3C Markup Validator**
- Follow **best practices** (SEO, performance, readability)

---

## Concepts Covered
- **Intro & Setup (#01–#06)**
  - What is HTML? Elements, tags, browser rendering
  - First page, `<!DOCTYPE html>`, quirks vs standards mode
  - `<head>`, nested elements, comments

- **Text & Structure (#07–#11)**
  - Headings (`<h1>`–`<h6>`)
  - `<p>`, formatting (`<strong>`, `<em>`, `<mark>`, etc.)
  - Attributes (`id`, `class`, `title`, `lang`)

- **Links & Media (#12–#13)**
  - `<a href>`, target, download
  - `<img src>`, `alt`, paths (relative/absolute)

- **Lists & Tables (#14–#15)**
  - `<ul>`, `<ol>`, `<dl>`
  - `<table>`, `<thead>`, `<tbody>`, `<caption>`

- **Layout & Entities (#16–#18)**
  - `<span>`, `<br>`, `<hr>`
  - `<div>` for grouping
  - HTML entities (`&copy;`, `&rarr;`, `&nbsp;`)

---

## Project Structure
```
/HTML-Mastery-Challenge
│
├─ index.html             # Your full HTML page
├─ assets/
│   ├─ images/
│   │   └─ profile.jpg    # Your photo (300x300px)
│   └─ resume.pdf         # Sample PDF
├─ README.md              # Answers + validator screenshot
└─ .gitignore             # (optional)
```

---

## Task Instructions

### 1. **Setup (#01–#06)**
- Create folder + files
- Open in **VS Code**
- Add `<!DOCTYPE html>` at top
- Set `<html lang="en">`
- Add comment: `<!-- This page follows HTML5 standards -->`

---

### 2. **Complete `index.html` with TODOs**

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <!-- TODO #1: Add charset, viewport, title -->
  <!-- TODO #2: Add meta description, author -->
</head>
<body>
  <!-- TODO #3: Use <header> with <h1> and <nav> -->
  <!-- TODO #4: Add <main> with sections -->
  <!-- TODO #5: Hero section: <h2>, <p>, <img> with alt -->
  <!-- TODO #6: About: <p> with <strong>, <em>, <mark> -->
  <!-- TODO #7: Skills: <ul> or <dl> -->
  <!-- TODO #8: Experience: <ol> with nested <li> -->
  <!-- TODO #9: Projects: <table> with thead/tbody -->
  <!-- TODO #10: Contact: <a href="mailto:">, <a href="tel:"> -->
  <!-- TODO #11: Download resume: <a href="assets/resume.pdf" download> -->
  <!-- TODO #12: Use <hr> between sections -->
  <!-- TODO #13: Use <span> for inline styling hints -->
  <!-- TODO #14: Add <footer> with &copy; entity -->
  <!-- TODO #15: Use <br> only if necessary -->
</body>
</html>
```

---

### 4. **Best Practices Checklist**
| Requirement | How to Achieve |
|-----------|----------------|
| **Semantic HTML** | Use `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>` |
| **Accessibility** | `alt` on images, `lang`, proper heading order, ARIA if needed |
| **SEO** | `<title>`, `<meta description>`, semantic tags |
| **Performance** | Small image, no inline CSS/JS |
| **Validation** | Pass [W3C Validator](https://validator.w3.org/) |
| **Entities** | Use `&amp;`, `&lt;`, `&copy;`, `&nbsp;` where needed |

---

### 5. **README.md Updates**
Add:
- 1–2 sentences: **"What is HTML?"** (your words)
- Screenshot of **W3C Validator = 0 errors**
- List of **10 HTML entities** you used
- Explain **why you used `<dl>` instead of `<ul>`**

---

## Evaluation (100 Points)

| %   | Criteria |
|-----|--------|
| 15% | Valid `<!DOCTYPE>`, `<head>`, `lang`, charset |
| 15% | Semantic structure (`<header>`, `<main>`, etc.) |
| 15% | Correct use of text elements (`<h1>–<h6>`, `<p>`, formatting) |
| 15% | Links + images with proper paths/alt |
| 15% | Lists + table with semantic markup |
| 15% | `<div>`/`<span>` only when needed, entities |
| 10% | Accessibility + SEO meta tags |
| +Bonus | Creative layout, extra entities, validator screenshot |

---

## Author
- MEGA TEAM Frontend Mentor: **Mahmoud Ramadan**

---

## License
For **educational use only** within MEGA TEAM.
```