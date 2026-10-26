DAVID MACHARIA — PORTFOLIO SITE
================================

WHAT THIS IS
No build step. No npm. No Lovable credits needed. Just index.html + manifest.json + icons.
Open index.html in any browser and it works immediately.

HOW TO DEPLOY (choose one — both are free, ~2 minutes)

OPTION A — Netlify (easiest)
1. Go to https://app.netlify.com/drop
2. Drag the whole "site" folder onto the page
3. Netlify gives you a live URL immediately (e.g. yourname.netlify.app)
4. Optional: claim a free subdomain or connect your own domain in Site Settings

OPTION B — Vercel
1. Go to https://vercel.com/new
2. Sign in, choose "Deploy without Git" / drag-and-drop upload
3. Upload the "site" folder
4. Get your live URL

AFTER YOU HAVE A LIVE URL
Go back to PWABuilder.com, paste your new live URL, and it will now detect
manifest.json automatically (no more red "Missing Manifest" error) — then
"Package For Stores" → Android will be clickable, and you can generate your APK.

FILES
- index.html      → the entire site (all pages, all logic, all styling)
- manifest.json   → PWA manifest, already linked and pre-filled
- icons/          → app icons (192, 512, maskable) — replace with your own
                     photo/logo anytime by re-generating the same 3 filenames

CUSTOMIZING
- Phone/email/WhatsApp: edit the PHONE, PHONE_INTL, EMAIL constants near the
  top of the <script> tag in index.html
- Services content: edit the `services` array
- Estimate calculator pricing: edit `projectTypes`, `featureList`, `timelineOpts`
- Colors: edit the CSS variables at the top of <style> (--ink, --signal, --amber)
