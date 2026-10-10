# EcoScience Learning: GitHub Pages draft

Static HTML/CSS/JS prototype rebuilt using homepage copy and selected images from the provided Local by Flywheel WordPress backup. This is not a pixel-perfect export of Astra/WordPress.

## Preview
Open `index.html` in a browser, or use `python3 -m http.server 8000` from this folder and visit `http://localhost:8000`.

## Before publishing
- Replace `CONTACT_EMAIL_HERE` in `index.html` with the correct contact email, or remove the Email button until ready.
- Review all site copy, branding, and the description of the initiative as a demo.
- Check desktop and phone layout.
- Do not upload any WordPress database, PHP config files, or WordPress ZIP backup to GitHub.

## Publish
Create a new public GitHub repository, upload only this folder's contents, then in Settings > Pages choose `Deploy from a branch`, `main`, `/(root)`. The site should become available at `https://alanmeireles.github.io/ecoscience/` if the repository is named `ecoscience` and Pages is enabled.

## Contact form (version 4)
The Contact form posts to FormSubmit (`https://formsubmit.co/manuelameireles35@gmail.com`). Required fields: full name, email address, message. Optional: phone, organization, topic. The submit button is enabled. FormSubmit handles submission and bot checks; visitors leave the site for the provider's confirmation page.

**To activate delivery**: publish on an HTTP(S) website, submit a test using non-sensitive dummy information, open `manuelameireles35@gmail.com`, follow the FormSubmit activation link, and submit another test to check delivery. This cannot be verified from an offline ZIP. Review the site's privacy notice before collecting real inquiries. For anti-spam protection, do not disable the provider's default CAPTCHA.

All submissions go through a third party. Never upload WordPress private files or the original WordPress ZIP to a public repo.
