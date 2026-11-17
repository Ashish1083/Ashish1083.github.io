# Ashish Kumar — Research Portfolio

A responsive academic portfolio built with React, Vite, and Tailwind CSS, designed for GitHub Pages.

## Local development

Install Node.js 20+ and run:

```bash
npm install --no-audit --no-fund
npm run dev
```

Open the local URL printed by Vite (usually http://localhost:5173).

## Publish on GitHub Pages

1. Create a **public** GitHub repository named **Ashish1083.github.io** under the **Ashish1083** account.
2. Copy these files into the repository root (including `.github/workflows/deploy.yml`).
3. Commit and push to the `main` branch.
4. Open **Settings → Pages → Build and deployment → Source**, and choose **GitHub Actions**.
5. Open the **Actions** tab to follow the deployment. Your site will appear at **https://Ashish1083.github.io/** after the workflow completes.

From a terminal inside this project directory, for a *new empty* repository:

```bash
git init
git branch -M main
git add .
git commit -m "Launch research portfolio"
git remote add origin https://github.com/Ashish1083/Ashish1083.github.io.git
git push -u origin main
```

GitHub may require authentication (GitHub CLI, credential manager, or personal access token) for HTTPS pushes.

## Update content

- **`src/main.jsx`**: Change the introduction, research areas, project descriptions, publications, experience, and contact details.
- **`src/index.css`** and **`tailwind.config.js`**: Adjust colors and typography.
- **`index.html`**: Change the page title and metadata.
- **`public/`**: Put your own permitted figures, headshot, and CV here, then link them in the React page.

## Important before publishing

- Project cards use *illustrative vector artwork* and currently link to your GitHub repositories list, not specific code projects.
- Confirm publication status and author information; replace manuscript placeholders with final citations/DOIs when available.
- Confirm the contact email is the address you want public.
- Do not upload confidential internship code, restricted datasets, or copyrighted figures without permission.

## Production build

```bash
npm run build
npm run preview
```
