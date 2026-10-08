# CSS, basic

Styling the two-page website from `html_basic` with plain CSS.

| File | Description |
|------|-------------|
| base.css | Base styles: fonts, spacing, header navigation, `.logo` class and the `works_on_smartphone` responsive rules |
| styles.css | Flexbox page layout (header / main with article + aside / footer) and custom colours |
| index.html | Homepage, linked to both stylesheets, with a viewport meta tag and the `works_on_smartphone` class |
| tweets.html | Tweets page with the same structure and stylesheets |

## Layout

- `body` is a flex column: `header`, `main`, `footer`
- `main` is a flex row: `article` (2/3 width) and `aside` (1/3 width), both scrollable
- Below 768px wide, `article` and `aside` stack vertically
