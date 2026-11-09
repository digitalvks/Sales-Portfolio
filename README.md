# Vinayak Soma portfolio (vinayaksoma.com)

Plain static site: no build step, no npm. Upload the files to the root of your GitHub Pages repository.

## What changed
- Hero, About, Experience, Skills, Contact and the metrics strip rewritten for Customer Success, Account Support and Sales Operations. Design, colours, fonts, animations and mobile layout are unchanged.
- All old sales figures ($1.2M+ pipeline, 120%+ quota, $500K+ HP, 35% market share, 95% satisfaction, 30% fewer repeat visits, and similar) are removed everywhere, including metadata and the preview image.
- Metrics strip now shows only the four activity figures from your resumes (40+ contacts, 20+ customers weekly, 100+ CRM accounts, 12+ representatives coordinated), described as activity, not as achievements.
- New About section (and an About link in the desktop menu).
- Skills regrouped into four categories. Education unchanged apart from wording to match your resumes. Google and HubSpot certifications kept, as you confirmed them.
- One resume on the site: `Vinayak_Soma_Customer_Success_Resume.pdf` (unaltered), linked from the nav, hero and contact buttons as "Resume" / "Download Resume". The old `Vinayak-Resume.pdf` link is gone.
- Mobile and desktop layouts were polished separately (hero fit and headline on laptops, tidier hero tags and button sizing on phones). Tablet rendering is unchanged.
- Email is now a real `mailto:` link. The old copy-to-clipboard popup was removed.
- Title, description, Open Graph, Twitter/X tags and alt text updated. A small structured-data (schema.org Person) block was added. `og-image.jpg` regenerated from your headshot in the same style, with no figures. Your phone number is not on the site.

## Resumes
The website offers only the Customer Success resume, to keep things simple for visitors. Keep `Vinayak_Soma_Sales_Operations_Resume.pdf` on your computer and attach it directly when applying for Sales Support, Sales Coordinator, Sales Operations, CRM Coordinator and Business Operations roles. To change which resume the site offers, replace the PDF's contents under the same filename (or tell me and I will update the links).

## Upload to GitHub
1. Extract the ZIP. The files are at the top level, with no extra folder.
2. In your repository, choose Add file > Upload files and drag in everything, replacing existing files with the same names.
3. Delete the old `Vinayak-Resume.pdf` from the repository (it is no longer linked).
4. Commit to the branch GitHub Pages publishes from.

## Custom domain
This ZIP does not contain a `CNAME` file, and your original ZIP did not either. Uploading does not delete files already in the repository, so your existing `CNAME` (and `.nojekyll`, if you have one) stays as is. Do not delete them. Check Settings > Pages afterwards and confirm `vinayaksoma.com` is still shown.

## Confirm it is live
Wait a minute or two, then open https://vinayaksoma.com in a private window (or hard refresh). Check the new headline, click the resume buttons, and click the email link. To refresh the social preview, paste the URL into LinkedIn Post Inspector; platforms cache the old image for a while.

## Please check before publishing
- The resume PDF opens correctly after upload. It contains your phone number.
- Footer says "Canadian permanent resident." This line was already on your site; keep or remove it as you prefer.
- Dates and titles match your resumes (HP Feb 2026 to Sep 2026, confirmed by you).
- The "Assistant Sales Manager" title at Reliance Jio is shown as it appears on your resumes.
