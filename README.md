# The Stability Initiative — Website v1.0

A responsive, multi-page static website for The Stability Initiative.

## Pages
- Home
- My Story
- The Goals
- Give Support
- Community Board
- Services & Collaboration
- Updates
- Connect

## Deploy to Netlify (free tier)
1. Create/sign in to GitHub and create a **public** repository named `the-stability-initiative`.
2. Upload the contents of this folder to the repository root (the HTML files should be at the top level; keep the `assets` folder).
3. In Netlify, choose **Add new site → Import an existing project**.
4. Connect GitHub and select `the-stability-initiative`.
5. For a plain static site, leave Build command blank and Publish directory as `.` (or the repository root).
6. Deploy.
7. After deployment, open the deployed site and submit each form once as a test. Netlify Forms should detect forms with `data-netlify="true"` after deployment. If they are not detected, check Netlify's Forms settings and redeploy.
8. Configure form notification recipients in Netlify before sharing the website widely. Do not assume form notifications are configured automatically.

## Important launch limitations
- This version includes all eight planned pages and Netlify-compatible forms.
- Forms are configured for Netlify Forms and require deployment plus dashboard configuration and testing.
- No payment processor is connected. The Give Support page clearly says payment is not yet enabled.
- No public searchable directory, member accounts, private messaging system, or review system is active yet.
- Community submissions are private inquiries for review; they are not automatically published.
- Do not put passwords, API keys, private personal records, donor lists, bank details, or sensitive information in this repository.
- The initiative is individual-led and is not represented as a registered charity. Contributions are not represented as tax-deductible.
- The $12,000 target and allocations are provisional and should be validated before treating them as final.

## Editing
- Each page is a separate `.html` file.
- Shared styling is in `assets/style.css`.
- Navigation and footer are repeated in each page for simplicity in this first version.
