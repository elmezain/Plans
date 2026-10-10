# Program Tree — Taibah University, College of Computer Science & Engineering (Yanbu)

A single-page site for browsing the college's academic programs and study plans, with an admin panel for managing user accounts.

## Contents

- `index.html` — the website itself. Upload this to any static web host (or your faculty server) to run the site.
- `firestore.rules` — security rules for the Firebase project that powers login/accounts. Paste these into the **Rules** tab of your Firestore database.
- `SETUP.md` — step-by-step setup guide (in Arabic) for connecting the site to a free Firebase project, including creating the first administrator account.

## Why Firebase?

The original version stored user accounts only in each visitor's browser (`localStorage`), so an account created by the admin never reached other devices. This version uses Firebase Authentication + Firestore instead, so accounts and passwords are stored centrally and work from any device or browser.

See `SETUP.md` for the full one-time setup (about 10 minutes).

## License

Internal project for Taibah University, College of Computer Science & Engineering (Yanbu).
