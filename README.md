# i-Coder Website

A multi-page front-end website for **i-Coder**, a coding and tech learning platform for students and beginners. It is built with **HTML, CSS and Bootstrap 5** and has four pages: Home, About, Sign-in and Contact Us.

## Pages

| Page | File | What it contains |
|------|------|------------------|
| Home | `index.html` | Navbar, fade carousel with captions, four featured article cards, footer |
| About | `about.html` | Three skill highlights (Web Development, Programming Skills, Career Growth) and alternating sections: Motive, About, What We Offer, Our Mission |
| Sign-in | `Sign-in.html` | Account form with full name, username, email, password, coding interest dropdown, terms checkbox and remember-me option |
| Contact Us | `contact-us.html` | Contact form with name, username, email, address, country, state and pin code |

## Features

- Responsive layout built with the Bootstrap grid, so it works on mobile, tablet and desktop
- Collapsible navbar with page links and a search bar
- Image carousel with fade transition and call-to-action buttons
- Article cards for Trending Tech, Web Development, Projects and Career Growth
- Floating-label form inputs on the Sign-in page
- Contact form with country and state dropdowns (including all Indian states and union territories)
- Consistent Poppins typography across all pages

> The forms are front-end only. They are not connected to a backend yet, so nothing is saved or submitted.

## Tech Stack

- HTML5
- CSS3
- [Bootstrap 5.3](https://getbootstrap.com/) (grid, navbar, carousel, forms, utilities)
- Google Fonts (Poppins)

## Project Structure

```
i-Coder/
├── index.html
├── about.html
├── Sign-in.html
├── contact-us.html
├── images (PWB-*, Ab-*, Website_logo_3.png, ...)
└── README.md
```

## How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   ```
2. Open the folder
   ```bash
   cd YOUR_REPO_NAME
   ```
3. Open `index.html` in your browser (or use the **Live Server** extension in VS Code)

No installation or build step is needed. Bootstrap and fonts load from a CDN, so an internet connection is required.

## Screenshots

_Add screenshots of the pages here._

```markdown
![Home Page](screenshots/home.png)
![About Page](screenshots/about.png)
```

## What I Learned

- Building a responsive multi-page site with the Bootstrap grid
- Creating a collapsible navbar and a carousel with captions
- Designing forms with floating labels, selects and checkboxes
- Using the featurette layout for alternating image and text sections
- Linking multiple pages into one website

## Future Improvements

- Add the navbar and footer to every page for consistent navigation
- Add JavaScript form validation for the Sign-in and Contact forms
- Connect the forms to a backend (Node.js, Express and MongoDB)
- Add a working search, a courses page and a blog section
- Add dark mode

## Author

**Abhinav Tomar**
GitHub: [@abhinavtomar856-droid](https://github.com/abhinavtomar856-droid)
