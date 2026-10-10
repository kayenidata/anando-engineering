ANANDO ENGINEERING WEBSITE
==========================

This folder is the complete website: index.html plus the images folder.
No build step, no framework. Upload the whole folder as it is.

BEFORE GOING LIVE
- Confirm the Metcem project (2015-2016) status. It currently shows no "Completed" badge.
- Confirm the road lengths (9.376 km Molege-Ute, 24 km Ilaro-Owode) and the "33 km" figure.
- WhatsApp buttons use +234 708 873 7387. To change it, search index.html for 2347088737387.
- Optional: export the company profile PDF, name it  anando-company-profile.pdf  and put it
  in this folder next to index.html. A "Download company profile" button appears automatically
  once the file is there.

DEPLOY (pick one)

A) Netlify (free, commercial use allowed, easiest)
   1. Go to app.netlify.com/drop and sign up.
   2. Drag this whole folder onto the page. The site is live in seconds.
   3. Site settings > Domain management to rename it or add a custom domain.

B) Cloudflare Pages (free, commercial use allowed)
   1. dash.cloudflare.com > Workers & Pages > Create > Pages > Upload assets.
   2. Upload this folder.

C) Vercel (free Hobby plan is for non-commercial use; a business site should use Pro)
   1. Install Node.js, then in a terminal inside this folder run:
        npx vercel
   2. Follow the prompts (no build command, output directory = ".").
   3. Run  npx vercel --prod  to publish.

AFTER IT'S LIVE
- Replace the og:image line in index.html with the full address, for example
  https://anandoengineering.com/images/og-image.jpg, so WhatsApp and LinkedIn link previews show the photo.
- Add the website link to his Google Business Profile and WhatsApp Business profile.
