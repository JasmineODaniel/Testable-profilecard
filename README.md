# Testable Profile Card

A semantic, accessible, and responsive profile card built with HTML, CSS, and vanilla JavaScript.



## Project Structure

```
├── index.html
├── style.css
├── app.js
└── README.md
```

## Features

- Semantic HTML5 with proper use of `article`, `figure`, `nav`, `section`, and `header`
- Live epoch time in milliseconds updated every second
- Fully keyboard navigable social links
- Responsive layout — stacks vertically on mobile, side-by-side on desktop
- WCAG AA color contrast compliant
- `aria-live` on the time element for screen reader support
- All elements have `data-testid` attributes for automated testing

## Data Testids

| Element | data-testid |
|---|---|
| Profile card root | `test-profile-card` |
| Name | `test-user-name` |
| Bio | `test-user-bio` |
| Time (ms) | `test-user-time` |
| Avatar | `test-user-avatar` |
| Social links list | `test-user-social-links` |
| Twitter link | `test-user-social-twitter` |
| GitHub link | `test-user-social-github` |
| LinkedIn link | `test-user-social-linkedin` |
| Email link | `test-user-social-email` |
| Hobbies list | `test-user-hobbies` |
| Dislikes list | `test-user-dislikes` |

## How to Run Locally

```bash
git clone https://github.com/JasmineODaniel/Testable-profilecard.git
cd Testable-profilecard
```

Then open `index.html` in your browser. No build step needed.

## Built With

- HTML5
- CSS3 (Flexbox)
- Vanilla JavaScript
- Google Fonts — Michroma & DM Sans
