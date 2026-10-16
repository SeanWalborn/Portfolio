# Sean Walborn — Personal Portfolio

A responsive portfolio for Sean Walborn, a Computer Science student at California State Polytechnic University, Pomona. Built with plain HTML, CSS, and minimal JavaScript. Includes an introduction, objective, About section, three Coming Soon project cards, contact links, and a PDF resume.

## Files

- `index.html` — page content, navigation, and project card templates
- `styles.css` — theme, component styles, and responsive layouts
- `script.js` — updates the copyright year
- `assets/headshot.jpg` — profile photo
- `assets/Sean-Walborn-Resume.pdf` — current resume

## Run locally

Open `index.html` in your browser. No dependencies or build step are required.

Alternatively, from the project folder, run:

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000` in your browser. Stop the server with Ctrl+C.

## Replace the headshot

Replace `assets/headshot.jpg` with your new JPG using the same filename. If its dimensions change, update the image's `width` and `height` attributes in `index.html` to match. Keep the alt text descriptive. CSS handles proportional cropping and responsive sizing; it does not change the original file.

## Replace the resume

Replace `assets/Sean-Walborn-Resume.pdf` with the updated PDF using the same filename. The Resume button opens this file in a new tab. If you change the filename, update the Resume link in `index.html` too. Keep filenames simple and match capitalization exactly.

## Add future projects

1. In `index.html`, find the Projects section and duplicate a complete `<article class="project-card">` block.
2. Replace the Coming Soon title, description, placeholder label, and technology list. Use one `<li>` per technology.
3. Uncomment the `project-links` block and replace `YOUR_GITHUB_REPOSITORY_URL` with the real repository URL. Remove the `project-status` paragraph.
4. Set the optional live demo URL, or remove that link if there is no demo.
5. For an optional image, add a screenshot to `assets/` and replace the decorative `project-preview` div with the commented `project-image` example. Update its relative path, alt text, width, and height.

Keep links and image examples commented out until real destinations and files are available. The grid adapts automatically to additional cards.

## Deploy with GitHub Pages

After reviewing, committing, and pushing the files to the `main` branch of `SeanWalborn/landingPage`:

1. Open the repository on GitHub and go to **Settings → Pages**.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Choose **main** and **/ (root)**, then click **Save**.
4. Wait for the Pages deployment to finish. GitHub will show the published URL in the Pages settings.

The expected address is `https://seanwalborn.github.io/landingPage/`. Local asset paths are relative, so they work under the repository's `/landingPage/` path. No build command or framework configuration is needed.
