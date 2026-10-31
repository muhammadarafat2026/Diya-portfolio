# Diya Chander — B.Pharm Portfolio

A responsive static portfolio built with HTML, CSS and vanilla JavaScript.

## Run locally
1. Extract the ZIP file.
2. Open the `diya-portfolio` folder.
3. Double-click `index.html` to open it in a browser.
4. For a local development server, open a terminal in this folder and run `python -m http.server 8000`, then visit `http://localhost:8000`.

## Publish on Render (static site)
1. Upload this project to a GitHub repository (keep `index.html`, `styles.css`, `script.js` and the `assets` folder together).
2. In Render, choose **New + → Static Site** and connect the repository.
3. Set **Build Command** to blank (or `echo "Static site"` if the dashboard requires a command).
4. Set **Publish Directory** to `.` and deploy.
5. Render will provide a public URL.

## Personalise the portfolio
- Open `index.html` in a code editor.
- Replace `[Add institution name]`, `[Add city, country]` and `[Add profile when available]`.
- Update the academic year and progress percentage as your semesters advance.
- Edit the subject, skill, interest and roadmap text as needed.
- Replace the profile image at `assets/diya-profile.jpg` with another image using the same filename, or change the image path in the hero section.
- Update the email and LinkedIn URL if they change.

## Add certificates
In the `credentials` section of `index.html`, replace the empty-record message with a certificate card. Store certificate files in a new folder such as `assets/certificates/` and link to them with a relative path. Only list credentials actually earned.

## Add projects
Duplicate one `.work-card` button in the `work` section. Update its title, category, short description and `data-desc` attribute. The detail dialog will display the `data-desc` content. Add only completed work and accurate learning outcomes.

## CV
A CV has not been supplied, so the site does not claim to provide a downloadable CV. Add your PDF later and place a link to it in the hero actions.

## Contact form
The contact form validates required fields and opens the visitor's default email application using a `mailto:` link. It does not send messages directly or store submissions. A hosted form service or backend is needed for direct website submissions.

## Notes
- Google Fonts require an internet connection; system sans-serif fallbacks are included.
- No certificate, award, internship, research experience or professional qualification is fabricated.
