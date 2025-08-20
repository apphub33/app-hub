# App Hub — Quick Edit Guide (Emergency App)

Open `index.html` and edit:

1) Version: search `v1.0.0` and update when you release.
2) APK link: search `https://RapidNow.com/RapidNow.apk` and replace with your actual URL.
3) Email: search `apphub@yahoo.com` if you change contact info.
4) Screenshots: replace `assets/rapidnow-1.png` and `assets/rapidnow-2.png` with your real images (or change the <img src=...> paths).
5) Privacy date: edit the "Last updated" date in the Privacy section when policy changes.
6) Text: You can modify any wording in the Rapid Now "Overview", "Permissions", and "FAQ" to match your exact behavior.

## Update manifest (optional)
Edit `update-manifests/rapid-now.json` if your app checks for updates from the website.

## Deploy
Upload the folder to Netlify / GitHub Pages / Cloudflare Pages / your server. Entry file is `index.html`.
