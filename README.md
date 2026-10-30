# Savor Kitchen MKE
Static HTML + Tailwind CSS 4 + vanilla JavaScript, matching the other TwinBros Solutions client projects.

## Develop in WSL
npm install
npm run build
npm run serve

Open http://localhost:9001. Run npm run watch in another terminal while editing CSS.

## Before launch
Replace sample dishes, prices, and Unsplash stock photos with owner-approved content.
Ordering is delivery-only. DoorDash, Grubhub, and Uber Eats buttons are disabled placeholders. Replace them with the actual kitchen storefront URLs before launch. There is no pickup form, checkout, or payment processing on this site.
Confirm contact details, pickup/delivery, ordering schedule, ingredient/allergen information and policies with the owner.
Remove the noindex meta and robots.txt block only after approving final content and domain. Add canonical, social metadata and sitemap for the real domain.
No real contact details, certifications, reviews, or operating hours have been invented.

## Cloudflare Pages
Build: npm run build
Publish directory: project root
No secrets required. Do not publish node_modules.

Toolchain: Node.js 20+ is recommended by Tailwind. If npm omits the WSL native binding, run npm install --no-save @tailwindcss/oxide-linux-x64-gnu@4.2.2 and rebuild.
