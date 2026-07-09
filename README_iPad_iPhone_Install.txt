Posey Purposeful Rounding PWA - iPad/iPhone Demo Install

What this package contains:
- index.html: the Safari web app
- manifest.json: app name, launch settings, icons
- service-worker.js: offline cache support after first load
- icons/: Home Screen icons

How to demo on iPad/iPhone:
1. Host this folder on an HTTPS web location. Good demo options: SharePoint web hosting, Azure Static Web Apps, Netlify, Vercel, GitHub Pages, or an internal TIDI web server.
2. Open the hosted index.html link in Safari on the iPad or iPhone.
3. Tap Share.
4. Tap Add to Home Screen.
5. Open Posey Rounding from the Home Screen.

Important notes:
- Opening index.html directly from Files usually will not behave like a full web app because Safari treats local files differently and service workers require a hosted HTTPS origin.
- The current demo saves data in the device browser's local storage. That is fine for demos, but production should use a secure backend/database so roundings sync across reps, devices, CRM, and leadership dashboards.
- Offline mode works after the hosted app has been opened once and the service worker has cached the files.
