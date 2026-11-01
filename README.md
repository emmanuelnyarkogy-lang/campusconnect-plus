# CampusConnect Plus

A responsive campus marketplace website starter using the supplied CampusConnect Plus logo and its navy-blue/gold brand palette.

## Current features
- Responsive landing page
- Campus service categories: food, printing, stationery, errands/delivery, laundry/personal care and other services
- Customer order/enquiry form
- WhatsApp handoff structure
- Vendor directory placeholder (ready for real vendor profiles)
- Basic Progressive Web App manifest and offline cache

## Before launch
1. Open `app.js` and add the official team WhatsApp number to `CONFIG.teamWhatsApp` in international digits-only format.
2. Confirm the launch campus/campuses and service categories.
3. Add vendor profiles, product/service listings, prices, service areas and vendor WhatsApp numbers when vendors are onboarded.
4. Test the order form and WhatsApp handoff on a phone.
5. Check the site on desktop and mobile.

## Publish on GitHub Pages
1. Create a GitHub repository called `campusconnect-plus`.
2. Upload the contents of this folder to the repository root (including the `assets` folder).
3. Open repository Settings → Pages.
4. Select Deploy from a branch, choose `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish the site and open the generated address.

## Important functionality note
This is the first static website version. GitHub Pages can host the frontend, but does not store orders or provide private vendor/admin accounts. The current form is designed to hand the request to the team's WhatsApp once the team number is configured. For vendor logins, inventory, order tracking and a secure admin dashboard, connect a backend such as Supabase or Firebase in a later development stage.

## App installation
The project includes a basic PWA setup. A compatible browser can offer an install option once the site is hosted over HTTPS. A Google Play Store release needs Android packaging, testing and Play Console setup separately.
