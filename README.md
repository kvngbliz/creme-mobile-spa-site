# Crémé Dé Lá Crémé – The Mobile Spa

A responsive one-page website for Crémé Dé Lá Crémé. It uses plain HTML, CSS and JavaScript, so there is no paid theme or framework requirement.

## Preview
Unzip the package and open `index.html` in a browser. Keep the `assets` folder beside `index.html` so the logo displays.

## Publish free on Vercel
1. Create/sign in to GitHub: https://github.com/
2. Create a repository named `creme-mobile-spa-site`.
3. Upload `index.html`, `README.md`, and the entire `assets` folder (including `creme-logo.jpg`).
4. Create/sign in to Vercel: https://vercel.com/ and connect GitHub.
5. Choose **Add New → Project**, import the repository, and deploy. For this plain HTML site, no build command is needed; use **Other** if asked for a framework.
6. Vercel will provide a free `*.vercel.app` address. Project name availability determines the exact address.
7. To update the website later, edit files in GitHub and commit the changes. Vercel automatically redeploys.

## Manage the website
- **Logo:** Replace `assets/creme-logo.jpg` with your new logo image, keeping the same filename. For best results, use a clear PNG with a transparent or white background.
- **Prices:** In `index.html`, find `id="pricing"` and edit treatment names and naira amounts.
- **Services:** Find `id="services"` and edit the service-card headings/descriptions.
- **WhatsApp/phone:** Search for `2348107670550` and `2348100288256`. WhatsApp URLs use country code 234 and omit the leading zero.
- **Social accounts:** Search for `creme_de_la_creme45` to update Instagram/TikTok links.
- **Gallery:** Replace the three image URLs in the `id="gallery"` section with images you own or have permission to use. The current photos are generic illustrative stock images, not images of your actual team or clients.
- **Copy:** Search for the wording you want to change and edit it.

## Before launch
Verify all prices, phone numbers, social handles, service descriptions and booking terms. The gallery is clearly described as illustrative. No customer reviews, ratings, therapist credentials, or deposit policy are fabricated. WhatsApp buttons open an enquiry; the site does not collect payments or store customer information.

## Technical notes
- Static website: no database or backend needed.
- Responsive on mobile and desktop.
- Generic illustrative images are loaded from Unsplash and require an internet connection.
- Free Vercel hosting is subject to Vercel's current plan limits and terms.
