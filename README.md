# Software Engineering Portfolio

A responsive, accessible, static portfolio with dark/light theme switching, five featured projects, category filters, project detail dialogs, technical skills, education, and contact links. **No installation, backend, API keys, or build step required.**

## Start locally

Open `index.html` in a browser. All project data is in `config.js`.

## Personalize before publishing (important)

Open `config.js` in VS Code or Notepad and edit:

- `name`, `initials`, `role`, `headline`, `introduction`, `location`
- `university`, `degree`, `graduation`, `availability`
- `email`, `github`, `linkedin`
- `resume` (leave empty until you add your CV, e.g. `assets/resume.pdf`)
- `skills` (only claim skills you can discuss)
- Each project's `github`, `demo`, `status`, features, and stack. **Do not mark prototypes as production apps.**

Missing links are intentionally hidden. All project cards have working details dialogs even when a live demo is unavailable.

## Publish with GitHub Pages (browser method)

1. Go to https://github.com/new and create a **Public** repository named `software-engineering-portfolio`.
2. Do not initialize with a README (this package already contains one).
3. Click **uploading an existing file** and upload `index.html`, `styles.css`, `app.js`, `config.js`, `README.md`, `.gitignore` and the `assets` folder if you added files to it. Keep `index.html` at repository root.
4. Commit your files to `main`.
5. Go to **Settings → Pages → Build and deployment**.
6. Choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
7. Wait for the Pages deployment. Your URL will usually be `https://YOUR-USERNAME.github.io/software-engineering-portfolio/`.
8. Open it in a private/incognito window, test theme toggle, navigation, project filters, project details and links on phone and desktop.
9. Add the live URL to the repository **About → Website** field.

## Update later

Edit `config.js` in GitHub (pencil icon), commit the change, and GitHub Pages redeploys. Or edit locally and upload again.

## Security and accuracy

- Do not publish phone numbers, personal addresses, passwords, private data, or API keys.
- Do not add claims of employment, certifications, awards, or production readiness unless verified.
- The GitHub Pages site is public; it contains no server-side contact form. Email links open the visitor's mail app.
- All project details are editable in `config.js`.

## Structure

```
index.html      # page structure and semantic sections
styles.css      # responsive layout, dark and light themes
app.js          # theme, filtering, dialogs, rendering
config.js       # all editable profile/project data
README.md       # publishing instructions
assets/         # optional resume or images
```

## License

No license is supplied by default. Choose a license only if you want to grant reuse rights.
