Student Management System — installable web app (PWA)

Files:
- index.html: your original app with PWA support added
- manifest.json: app name, appearance, and install settings
- service-worker.js: basic offline caching
- icon.svg: app icon

Important:
1. Upload ALL four files to the ROOT of a static hosting site that serves HTTPS.
2. Open the published website in Chrome on Android.
3. Tap the three-dot menu, then choose "Install app" or "Add to Home screen".
4. Confirm the installation.

This is a beginner/demo app. Student records are stored in browser local storage on that device and are not synced to other phones or users. Use sample data only, not sensitive real student information.
