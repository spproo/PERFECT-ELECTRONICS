# Perfect Electronics website

A responsive, static website for Perfect Electronics. It is ready to deploy on Vercel.

## Deploy on Vercel
1. Extract `perfect-electronics-website.zip`.
2. Sign in to https://vercel.com/ and choose **Add New → Project**.
3. Import the folder from a GitHub repository, or use Vercel CLI from this folder:
   - Install Node.js if needed.
   - Run `npm i -g vercel`
   - Run `vercel` and follow the prompts.
4. For this plain HTML/CSS/JS site, use the project root as the root directory. No build command or output directory is required; if Vercel asks for a framework, choose **Other**.
5. After deployment, Vercel gives you a live `.vercel.app` URL. You can connect a custom domain from the project's **Settings → Domains**.

## Edit before publishing
- Confirm both phone numbers, address, Facebook link and Google business link.
- Confirm which repairs/accessories are currently offered and the current second-hand phone stock.
- The site intentionally does **not** invent customer testimonials or ratings. Add genuine customer reviews only with permission.
- The displayed service descriptions are general descriptions; repair feasibility, parts, prices and stock should be confirmed with the shop.
- Replace the two images in `assets/` if you want newer photographs.

## Files
- `index.html` — website content
- `styles.css` — responsive styling
- `script.js` — mobile navigation and current year
- `assets/` — supplied shop photographs and favicon
