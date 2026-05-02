# Static Engineering Portfolio

This repository is a simple static one-page portfolio for GitHub Pages. There is no Jekyll, Ruby, Docker, package manager, or build step.

## Files

- `index.html`: all page content and placeholders.
- `styles.css`: all site styling.
- `.nojekyll`: tells GitHub Pages to serve the static files directly without Jekyll processing.
- `assets/resume.pdf`: replace this placeholder with your final one-page resume.
- `assets/justification-memo.pdf`: replace this placeholder with your final justification memo.

## How to edit content

Open `index.html` and replace bracketed placeholder text like `[Your Name]`, `[Project Title 1]`, and `[Write the main project description here...]` with your final content.

For project images, add image files to `assets/` and replace each `<div class="media-placeholder">Add image or media</div>` with an image tag, for example:

```html
<img class="project-image" src="assets/project-1.jpg" alt="Short description of project image" />
```

The `.project-image` rule is already included in `styles.css`.

## Resume and memo PDFs

When you have the real PDFs:

1. Upload your resume to `assets/resume.pdf`, replacing the placeholder.
2. Upload your justification memo to `assets/justification-memo.pdf`, replacing the placeholder.
3. Keep those exact filenames so the buttons on the website continue to work.

## GitHub Pages deployment

1. Push `index.html`, `styles.css`, `.nojekyll`, `README.md`, and the `assets/` folder to GitHub.
2. In GitHub, open the repository.
3. Go to `Settings` > `Pages`.
4. Under `Build and deployment`, set the source to deploy from a branch.
5. Choose the `main` branch and the repository root folder.
6. Save the settings.
7. Wait for GitHub Pages to publish the site.
8. Open the published URL and test the navigation, Resume button, and Memo button.

Because this is plain static HTML and CSS, GitHub Pages should serve it directly from the repository root.
