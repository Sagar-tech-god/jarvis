J.A.R.V.I.S. — no backend, no credits, hosts free anywhere
==========================================================

This version talks to Gemini directly from your phone. Your API key is
typed into the app once and saved ON YOUR DEVICE only — it is never in
these files and never uploaded. So there is no server, no functions, and
nothing that burns credits.

DEPLOY (easiest path — Vercel, free, accepts a zip like Netlify did):

1. Go to  vercel.com/signup  and make a free account (no card needed).
2. Go to  vercel.com/new  ->  choose the option to upload / drag files,
   or use  vercel.com/import  and drop this ZIP.
   (Any static host works too: Cloudflare Pages, GitHub Pages, etc.)
3. Deploy. You'll get a URL like  your-jarvis.vercel.app

FIRST RUN:

4. Open the URL in Chrome.
5. Tap the gear (top right) and paste your Gemini key. It saves on the device.
6. Type or tap the reactor to talk. Done.
7. Chrome menu -> "Add to Home screen" to install it as an app.

Notes:
- Get a free Gemini key at  aistudio.google.com  (Get API key).
- The key lives only in this browser. New device/browser = paste it once there.
- Change the model or voice anytime in the gear menu.
- To change Jarvis's personality: edit SYSTEM_PROMPT near the top of the
  <script> in index.html.
