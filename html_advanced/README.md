# HTML, advanced: SmileSchool

![SmileSchool logo](images/logo.png)

This project turns a designer's Figma file into a webpage for **SmileSchool**, a fictional online school with short video tutorials on how to smile. It focuses on the **HTML structure only**: pure semantic markup, no CSS and no styling. Styling comes in the next project.

## Learning objectives

- What HTML is and how to build a page from a wireframe
- What a markup language is
- What the DOM is
- What elements, tags and attributes are
- The purpose of each semantic HTML tag (`header`, `main`, `section`, `footer`, `blockquote`, …)

## Page structure

| Part | Tag | Content |
|------|-----|---------|
| Header | `<header>` | Clickable logo and 3 navigation links |
| Banner | `<section>` | `h1` title, text and button, then an `h2` with 4 feature blocks (image, `h3`, text) |
| Quote | `<section>` | Portrait, `blockquote`, author and job title |
| Videos | `<section>` | `h1` and 4 video cards: thumbnail, title, text, author, 5-star rating and duration |
| Membership | `<section>` | `h1`, 4 benefit items (image, `h2`, text) and a button |
| FAQ | `<section>` | `h1` and 2 rows of 2 questions (`h2`, `p`) |
| Footer | `<footer>` | Logo, social media links and copyright text |

```
body
├── header
├── main
│   ├── section  (banner)
│   ├── section  (quote)
│   ├── section  (videos)
│   ├── section  (membership)
│   └── section  (faq)
└── footer
```

## Files

| File | Description |
|------|-------------|
| `index.html` | The SmileSchool page |
| `images/` | Logo, icons, thumbnails, avatars, rating stars and social icons |

## Requirements

- Ubuntu 20.04 LTS, any modern browser
- W3C compliant: validated with the [W3C Validator](https://validator.w3.org/)
- No external libraries

## Author

Regan Ayiecho, [github.com/rayiecho](https://github.com/rayiecho)
