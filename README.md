# Nitin Patel | Portfolio Website

A responsive, fully static personal portfolio built with plain HTML, CSS and JavaScript. It has no frameworks, no build step and no dependencies, so it works by opening `index.html` in a browser.

**Live site:** https://nitinpatel-dev.vercel.app/

---

## About

I'm Nitin Patel, a B.Tech Computer Science and Engineering student at Lakshmi Narain College of Technology (LNCT), Indore. I build database-driven Python applications, practise problem-solving on LeetCode (200+ problems solved) and am training in Python, MySQL and AI fundamentals at InfoBeans Foundation.

This website presents my skills, projects, training, education and contact details in one place.

## Features

- Dark and light themes with a toggle button. The site follows the visitor's system theme by default and remembers their choice.
- Responsive layout for mobile, tablet and desktop, with a mobile menu.
- Hero section with a circular profile photo and a rotating role line.
- Resume download from the navigation bar.
- Sections for About, Skills, Projects, Training and Education, LeetCode, and Contact.
- Contact form that opens the visitor's email app with the message filled in (no server required).
- Accessible by design: semantic HTML, keyboard focus styles, and reduced-motion support.

## Sections

| Section | What it shows |
| --- | --- |
| Hero | Introduction, social links and profile photo |
| About | Short bio and focus areas |
| Skills | Python, MySQL, HTML/CSS/Bootstrap, Git and GitHub |
| Projects | LocalFix, Typing Speed Tester, Snakes and Ladders |
| Training and Education | InfoBeans Foundation, LNCT B.Tech, school education |
| LeetCode | Problem-solving progress with a link to my profile |
| Contact | Email, LinkedIn, GitHub and a contact form |

## Projects featured

- **LocalFix:** a service booking system connecting customers with service providers (Python, MySQL, OOP).
- **Typing Speed Tester:** measures typing speed in WPM and CPM with accuracy tracking (Python).
- **Snakes and Ladders:** a turn-based board game (Python).

## Tech stack

- HTML5
- CSS3 (custom properties for theming, Grid, Flexbox)
- Vanilla JavaScript
- Google Fonts (Sora and Nunito Sans)

## Project structure

```
Portfolio/
├── index.html                 # Page structure and JavaScript (entry point)
├── nitin.css                  # All styles, including dark and light themes
├── photo.jpg                  # Profile photo
├── Nitin_Patel_Resume.pdf     # Resume, downloaded from the navigation bar
└── README.md
```

## Run locally

1. Clone the repository:
   ```bash
   git clone https://github.com/nitinrudaydiya/Portfolio
   cd Portfolio
   ```
2. Open `index.html` in your browser.

To use a local server instead, run `python -m http.server 8000` and visit `http://localhost:8000`.

## Customize

- **Photo:** replace `photo.jpg` with your own square image, or change the file name in the `<img>` tag.
- **Resume:** replace `Nitin_Patel_Resume.pdf`, or update the `href` of the two Resume links in the navigation bar.
- **Colors and themes:** edit the CSS variables at the top of `nitin.css` (`:root` for light, `[data-theme="dark"]` for dark).
- **Project links:** replace the GitHub profile links on the project cards with the link to each repository.
- **Contact email:** search for `nitinanilpatel@gmail.com` and replace it with your address.

## Deploy

### GitHub Pages

1. Push the files to a GitHub repository.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select the `main` branch and the `/ (root)` folder, then save.
4. Your site will be live at `https://<your-username>.github.io/<repository-name>/` after a minute or two.

### Vercel

1. Import the repository in Vercel.
2. Set **Framework Preset** to **Other** and leave the build command and output directory empty.
3. Deploy. The entry file must be named `index.html` and sit at the root of the repository.

### Netlify

Drag the project folder onto [Netlify Drop](https://app.netlify.com/drop) to publish it instantly.

## Contact

- Email: nitinanilpatel@gmail.com
- LinkedIn: https://www.linkedin.com/in/nitinrudaydiya/
- GitHub: https://github.com/nitinrudaydiya
- LeetCode: https://leetcode.com/u/nitinrudaydiya/

---

© 2026 Nitin Patel. Feel free to take inspiration from this layout. Please replace the personal content, photo and resume with your own.
