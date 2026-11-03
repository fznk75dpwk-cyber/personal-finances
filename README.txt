MY FINANCE — DEPLOYABLE V2

This version has no npm/build step.

Deploy to Render / Netlify / Cloudflare Pages / GitHub Pages as a static site.
Publish directory: the folder containing index.html.
Build command: none.

IMPORTANT: Opening index.html by double-clicking is not the intended deployment method because the app imports the Supabase browser SDK from a CDN and browser file:// restrictions vary. Serve/deploy it over http/https.

Supabase backend is already configured in app.js using a publishable browser key. Never replace it with a service-role/secret key.
