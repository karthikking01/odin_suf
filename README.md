# Odin Sign-Up Form

A responsive sign-up / registration page built as part of [The Odin Project](https://www.theodinproject.com/) curriculum.

## Preview

The page is split into two columns:

- **Left panel** – a full-height background photograph with the Odin logo overlaid.
- **Right panel** – a sign-up form that collects user details and enforces client-side validation.

## Features

- Clean two-column layout using CSS Flexbox
- Input fields for First Name, Last Name, Email Address, Phone Number, Password, and Confirm Password
- Client-side HTML5 validation:
  - Email must match a standard `user@domain.com` format
  - Phone number must follow the international format `+CCCXXXXXXXXXX`
  - Password must be at least 8 characters and contain at least one uppercase letter, one lowercase letter, and one digit
- Visual feedback – invalid inputs are highlighted in red; focused inputs show a blue outline
- Custom *Norse Bold* typeface for the logo heading

## Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Page structure and form validation |
| CSS3 | Styling, Flexbox layout, custom font |

## Getting Started

No build step required – just open `index.html` in any modern browser.

```bash
# Clone the repository
git clone https://github.com/karthikking01/odin_suf.git

# Open in your browser
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows
```

## Credits

- Background photograph by [Jisca Lucia](https://unsplash.com/@wanderlandjournal) on [Unsplash](https://unsplash.com/)
- Project brief from [The Odin Project](https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-sign-up-form)

## License

This project is licensed under the [GNU General Public License v3.0](LICENSE).
