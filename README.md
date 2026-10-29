# Sinchana B G | Developer Portfolio

A responsive personal portfolio website for Sinchana B G, a Computer Science and Engineering student and aspiring web developer. Built with plain HTML, CSS and JavaScript, with no frameworks, libraries or build tools.

## Features

- Premium dark theme with a blue accent and a working light/dark toggle (choice is remembered in the browser)
- Responsive navbar with an accessible hamburger menu (`aria-expanded`, `aria-controls`, Escape to close)
- Hero, About (education), Skills, Projects, and Contact sections
- Project cards with technology badges and honest "not published yet" labels where no live link exists
- Smooth scrolling, scroll-reveal animations, and active-section highlighting in the navbar
- Visible focus states, skip link, keyboard-friendly controls, semantic HTML
- `prefers-reduced-motion` support
- Footer with an automatic copyright year and a back-to-top link
- Mobile-first layout designed for 375px, 768px and 1280px+ screens

## Technologies

- HTML5
- CSS3 (custom properties, Grid, Flexbox)
- Vanilla JavaScript (ES5-compatible syntax)

## Folder Structure

```
portfolio/
├── index.html
├── style.css
├── script.js
└── README.md
```

## Run Locally

1. Download or clone the project folder.
2. Make sure all four files are in the same folder.
3. Double-click `index.html` to open it in your browser.

Optional: if you use VS Code, the "Live Server" extension can serve the folder with auto-reload.

## Personalize

Open `index.html` and look for text in square brackets such as `[Start year – Expected graduation year]` and for `EDIT:` comments. Replace them with your real details. Update the project cards as you publish demos or add new projects.

## Upload to a Public GitHub Repository

1. Sign in at https://github.com and click **New repository**.
2. Name it (for example `portfolio`) and set visibility to **Public**.
3. Create the repository, then click **uploading an existing file**.
4. Drag in `index.html`, `style.css`, `script.js` and `README.md`, then commit.

Using Git from the terminal instead:

```bash
git init
git add .
git commit -m "Add portfolio website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
git push -u origin main
```

## Deploy with GitHub Pages

1. Open your repository on GitHub and go to **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Choose branch **main** and folder **/ (root)**, then click **Save**.
4. Wait a minute or two. GitHub shows your site URL at the top of the Pages settings.
5. Open that URL to confirm the site works, then add it to the Portfolio project card in `index.html` and to your repository's **About** section.

## License

Personal portfolio. Add a license of your choice if you want others to reuse the code.
