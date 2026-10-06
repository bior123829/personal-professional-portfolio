# Personal Professional Portfolio Website

A modern, responsive portfolio website built with HTML, CSS and JavaScript for Internship Task 1.

## Features

- Responsive desktop/tablet/mobile layout
- Home, About, Skills, Projects, Resume and Contact sections
- Mobile navigation menu
- Smooth scrolling
- Active navigation highlighting
- Scroll reveal animations
- Contact form validation
- Mailto-based contact submission
- SEO-friendly semantic HTML
- Back-to-top button

## Folder Structure

```text
personal-portfolio/
├── index.html
├── style.css
├── script.js
├── README.md
└── images/
    └── profile-placeholder.svg
```

## Run in VS Code

1. Extract/open this folder in VS Code.
2. Open `index.html`.
3. Install the **Live Server** extension if you want a local development server.
4. Right-click `index.html` → **Open with Live Server**.
5. The website opens in your browser.

You can also double-click `index.html` to open it directly.

## Personalize Before Submission

Search and replace:

- `Your Name`
- `your.email@example.com`
- `Your City, India`
- `Your College Name`
- GitHub URL
- LinkedIn URL
- Phone number

Replace `images/profile-placeholder.svg` with your professional photo if desired.

If you have a PDF resume, place it in the root folder as:

```text
resume.pdf
```

Then the Download Resume button will work.

## Contact Form

The current version uses `mailto:` so it works without a backend. Replace the email address in `script.js`.

For true server-side email notifications, connect the form to an email/form service or a Node.js backend before final deployment.

## Deployment

The project can be hosted on GitHub Pages, Netlify or Vercel. Upload the complete project folder to a GitHub repository and deploy it using the hosting provider's standard static-site workflow.
