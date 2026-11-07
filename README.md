# Perfect Electronics website

Responsive static website with a guided phone enquiry flow.

## Deploy / update on Vercel
1. Replace the files in your GitHub repository with the contents of this folder (keep the image files and favicon in the repository root, as the current GitHub upload is flat).
2. Commit the changes to the main branch. Vercel should redeploy automatically.
3. No build command or output directory is required; choose Other as the framework preset.

## Guided enquiry flow
Choose a brand → Buy new / Get repaired / Buy second hand → series → model → (repair only) multi-select issue list → Call or WhatsApp. WhatsApp opens a pre-filled message containing the customer's choices.

## Catalogue maintenance
Edit `catalogue` in `script.js` to add brands, series or model names. The list is a starter catalogue, not a complete or live inventory. Confirm model availability and names before advertising. Product cards currently use a remote generic phone image URL; replace with official product image URLs only when you have permission and verified stable image links.

## Important
- The website does not claim real-time stock or guaranteed repair pricing.
- WhatsApp enquiries go to 9717189697; the second contact number is also shown on the site.
- Shop images are referenced from the repository root: `storefront.jpg`, `store-interior.jpg`, `favicon.svg`.
