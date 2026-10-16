# Personalize your portfolio

- The hero photo uses `assets/headshot.jpg` with alt text `Headshot of Sean Walborn`. Place the original photo at this path; CSS crops it proportionally without modifying the file.
- The current resume is `assets/Sean-Walborn-Resume.pdf`. The Resume button opens it in a new tab. Replace this file with an updated PDF using the same filename to keep the link working.
- Review the draft introduction, objective, and About copy so they reflect your goals.
- To add a project, duplicate one complete `<article class="project-card">` in `index.html`.
- Replace its `Coming Soon` heading and short description. List technologies in the `project-technologies` list, one `<li>` per technology.
- Uncomment the `project-links` block, replace `YOUR_GITHUB_REPOSITORY_URL` with the real repository URL, and remove the `project-status` paragraph. Replace `YOUR_LIVE_DEMO_URL` with a real demo URL or remove that anchor if there is no demo.
- Optionally add a screenshot to `assets/` and replace the decorative `project-preview` div with the commented `project-image` example. Set its path, meaningful alt text, and original image dimensions. Leave the preview div in place if you do not want a screenshot.

No build step or packages are required. Open `index.html` directly, or serve the repository with `python3 -m http.server 8000`.

