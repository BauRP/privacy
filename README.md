# Wave Notes — Privacy Policy

This branch contains the **independent RU/EN privacy-policy website** for Wave Notes by Tengrize studio.

- `index.html` — self-contained page with no third-party scripts, fonts, trackers, or cookies.
- App source audited: [BauRP/exact-screenshot-match](https://github.com/BauRP/exact-screenshot-match/tree/chatgpt/super-notes-stability-20261025).
- Covered features: local notes, PDF, audio, offline OCR with Google ML Kit, camera/microphone, AdMob and Google UMP, optional feedback to Telegram, Google Fonts, export and backups, biometric/PIN limitations.
- Effective date: 2026-10-26.

## How to publish independently

Create a **new public repository** named `wave-notes-privacy` under `BauRP` and copy this branch's `index.html` into its root. Add `.nojekyll`. Configure **Settings → Pages → Deploy from a branch → main → / (root)**. Once GitHub confirms deployment, verify the actual public URL in a browser; its expected format is `https://baurp.github.io/wave-notes-privacy/`.

Do not use the repository code URL as the privacy-policy website URL. Do not change the existing Trivo Chat privacy website on `main`.

The checked app identifies developer as **Tengrize studio**. For public contact, the policy currently links to GitHub Issues; a dedicated private support email is preferable before final publication.

The site is a best-effort statement of the audited implementation, not a certification of legal compliance. Update after any app data-handling changes.
