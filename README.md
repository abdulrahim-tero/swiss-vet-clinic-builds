# App builds

Static download page for prototype builds of the client app. Deployed to Vercel; the APK is
served with `Content-Disposition: attachment`. `/latest.apk` always points at the newest build
(see `vercel.json`).

Builds are debug-signed prototypes with demo data. Not for the Play Store.
