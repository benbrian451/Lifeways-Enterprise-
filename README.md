# Lifeways Enterprise Ltd. — Netlify Front-End

A responsive, static front-end for Lifeways Enterprise Ltd. using the supplied logo and project photographs.

## Files
- `index.html` — main company website
- `styles.css` — responsive styling and brand colors
- `script.js` — mobile navigation and current year
- `assets/logo.png` — supplied logo artwork
- `assets/projects/` — project gallery images
- `thank-you.html` — enquiry success page

## Deploy to Netlify
1. Extract this ZIP.
2. Sign in to Netlify and choose **Add new site → Deploy manually** (or connect a Git repository).
3. Drag the extracted folder's contents into the manual deploy area, or upload the folder according to Netlify's current deploy interface.
4. After deployment, open **Forms** in your Netlify site dashboard and confirm form detection is enabled. If the form is not detected automatically, redeploy after enabling form detection in the site's form settings.
5. Submit a test enquiry and confirm it appears in Netlify Forms. Configure form notifications to your company email.
6. Add your custom domain in Netlify's domain settings and follow its DNS/HTTPS prompts.

## Contact information used
- Phone: 0704 446 7746
- Email: teamlifeways@gmail.com
- Location: Nairobi, Kenya
- Tagline: Where Quality Meets Class

## Important scope notes
This is the **front-end only**. It has no PHP backend, admin dashboard, staff login system, or custom database. Netlify Forms can receive website enquiries after deployment and configuration, but it is not a replacement for the former PHP staff-management dashboard. For multiple staff accounts and role-based access, add a separate backend/authentication service (or host the PHP version on PHP-compatible hosting).

The enquiry form uses Netlify Forms markup. Form submissions and notifications must be tested in the deployed Netlify site; they do not submit to a database when previewed as local files.

The project image filenames are retained from the supplied package. Google Fonts are loaded from an external service; system fonts remain fallback options if it is unavailable.
