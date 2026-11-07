# Perfect Electronics website

Responsive static website for Perfect Electronics with a guided phone enquiry flow, repair booking enquiries, sell/exchange enquiries, a Google review link and English/Hindi language switching.

## Deploy / update on Vercel
1. Replace the files in your GitHub repository with the contents of this folder (keep the image files and favicon in the repository root, as the current GitHub upload is flat).
2. Commit the changes to the main branch. Vercel should redeploy automatically.
3. No build command or output directory is required; choose Other as the framework preset.

## New customer features
- **Repair booking:** The form collects customer contact details, brand/model, issue and preferred visit date/time, then opens WhatsApp with the enquiry pre-filled. The shop must reply to confirm the visit; this is not an online appointment calendar.
- **Sell / exchange old phones:** Collects device details, condition, storage, expected price and accessories, then opens WhatsApp. Customers must attach phone photos manually in the WhatsApp chat; the static site does not upload or store photos.
- **Google reviews:** The review section links to the supplied Google Business listing so visitors can view the listing and leave feedback. No fabricated testimonials or ratings are shown. A live Google reviews feed would require a supported Google API/widget and configuration.
- **Hindi / English:** The language switch translates key website copy, navigation, forms and the interactive phone-selection flow. Brand and model names remain in their official form.

## Guided enquiry flow
Choose a brand → Buy new / Get repaired / Buy second hand → series → model → (repair only) multi-select issue list → Call or WhatsApp. WhatsApp opens a pre-filled message containing the customer's choices.

## Catalogue maintenance
Edit `catalogue` in `script.js` to add brands, series or model names. The list is a starter catalogue, not a complete or live inventory. Confirm model availability and names before advertising. Product cards currently use a remote generic phone image URL; replace with official product image URLs only when you have permission and verified stable image links.

## Privacy and operational notes
- This is a static website. Forms do not save customer data to a database; they open WhatsApp with the submitted details.
- Do not advertise a repair appointment as confirmed until the shop replies.
- Sell/exchange estimates are indicative enquiries only. Final offers require in-person inspection.
- The Google link currently opens the supplied business listing, not a live embedded reviews feed.

## Important
- The website does not claim real-time stock or guaranteed repair pricing.
- WhatsApp enquiries go to 9717189697; the second contact number is also shown on the site.
- Shop images are referenced from the repository root: `storefront.jpg`, `store-interior.jpg`, `favicon.svg`.
