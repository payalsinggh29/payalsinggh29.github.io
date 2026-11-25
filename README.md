# Payal Singh | Business Analyst Portfolio

A personal portfolio website showcasing my experience in business analysis, data analysis, process improvement and workflow automation.

**Live site:** https://payalsinggh29.github.io

## Profile 

I’m a Business Analyst with 2 years of experience delivering HR and Payroll system improvement initiatives for the City of Onkaparinga and Infosys. I hold a Master of Business Analytics from the University of Adelaide and work with Microsoft Dynamics CRM, SAP, Advanced Excel, Power BI and SQL.

## Features

- Responsive design that works on desktop, tablet and mobile
- Dark theme with a purple accent
- Sticky navigation bar with a mobile menu
- Typewriter effect in the hero section
- Scroll animations
- Sections: Home, About, Skills, Expertise, Experience, Key Work, Education, Certifications and Contact
- Working contact form (via Formspree)
- Downloadable CV button

## Built With

- HTML5
- [Tailwind CSS](https://tailwindcss.com/) (loaded from a CDN)
- [AOS](https://michalsnik.github.io/aos/) for scroll animations
- [Feather Icons](https://feathericons.com/)
- [Formspree](https://formspree.io/) for the contact form
- Hosted on [GitHub Pages](https://pages.github.com/)

No installation, build step or package manager is needed. The whole site is a single `index.html` file.

## Project Structure

```
payalsinggh29.github.io/
├── index.html                  # The entire website
├── README.md                   # This file
└── assets/
    ├── profile.png             # Profile photo (optional)
    ├── hero-wallpaper.jpg      # Background for Hero and About (optional)
    ├── footer.jpg              # Background for Contact (optional)
    └── Payal_Singh_Resume.pdf  # CV used by the Download CV button
```

Image files are optional. If one is missing, the site falls back to a dark gradient (or the "PS" initials in place of the photo).

## Run Locally

1. Download or clone this repository.
2. Double-click `index.html` to open it in your browser.

An internet connection is needed so the Tailwind, AOS and icon files can load.

## Deploy on GitHub Pages

1. Create a **public** repository named `payalsinggh29.github.io`.
2. Upload `index.html`, `README.md` and the `assets` folder.
3. Go to **Settings → Pages**.
4. Under **Branch**, select `main` and `/ (root)`, then click **Save**.
5. After 1–2 minutes, your site is live at `https://payalsinggh29.github.io`.

## Customise

| What to change | Where to find it in `index.html` |
|---|---|
| Colours | Search for `--accent` near the top of the file |
| Typewriter sentence | Search for `const text =` |
| Experience, skills and education text | Edit the matching section (`id="experience"`, `id="skills"`, and so on) |
| Add a skill | Copy a `<div class="skill"` line and change the icon and label |
| Add a project | Copy the commented project card in the Key Work section and remove the comment markers |
| Icons | Pick names from [feathericons.com](https://feathericons.com/) |

## Set Up the Contact Form

1. Create a free account at [formspree.io](https://formspree.io/).
2. Click **New Form** and enter your email address.
3. Copy your form link, for example `https://formspree.io/f/abcd1234`.
4. In `index.html`, search for `YOUR_FORM_ID` and replace it with the code at the end of your link (`abcd1234`).
5. Save and commit the file. Submissions will arrive in your inbox.

## Contact

- Email: payalsingh.ps29@yahoo.com
- LinkedIn: [linkedin.com/in/payalsinggh](https://www.linkedin.com/in/payalsinggh)
- Location: Adelaide, South Australia

## License

© Payal Singh. All rights reserved. Please don’t copy the personal content (text, photos or CV) from this site. The layout is yours to learn from.
