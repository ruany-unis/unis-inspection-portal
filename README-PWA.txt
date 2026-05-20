# UNIS Inspection Portal PWA

Upload these files to the root of the GitHub repository:
- index.html
- manifest.json
- service-worker.js
- icons/icon-192.png
- icons/icon-512.png

Live URL:
https://ruany-unis.github.io/unis-inspection-portal/

Notes:
- Installs on Android from Chrome using Add to Home screen / Install app.
- Offline mode works after the first successful online visit.
- Records currently use browser localStorage. For true multi-user record sync across phones/tablets, connect Firebase Firestore or Supabase.
- To generate an APK, use PWABuilder or Bubblewrap / Trusted Web Activity.
