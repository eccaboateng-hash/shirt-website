# A&C Clothing — static storefront

Ready for GitHub Pages or Netlify. No npm install or build command is needed.

## Before publishing
1. Put your original photos and logo in `images/`, using the exact filenames in `images/IMAGE-FILENAMES.txt`. Images were not supplied with the HTML and are not included here. Filenames are case-sensitive on Netlify.
2. Check the `BRAND` object in `index.html` for your business name, phone, WhatsApp, Mobile Money number and account holder.
3. Check the product list, prices and all wording.
4. Open `index.html` locally to preview, then test on the deployed site, including WhatsApp checkout.

## GitHub and Netlify
1. Create a new GitHub repository. Upload `index.html`, `netlify.toml`, `README.md`, and the `images` folder (with your real image files). Commit changes.
2. In Netlify choose **Add new project > Import an existing project > GitHub**, authorize GitHub and select the repository.
3. Build command: leave blank. Publish directory: `.` (repository root). Deploy.
4. Future commits to the connected branch automatically trigger a new deploy.

## Notes
- The cart is stored in each visitor's browser; there is no database or automatic payment gateway. Checkout opens WhatsApp with a prepared order; MoMo payment is confirmed manually.
- A missing image shows a built-in shirt illustration until the corresponding original file is uploaded.
- Keep the file named `index.html` in the repository root, not `.md` or `.txt`.
