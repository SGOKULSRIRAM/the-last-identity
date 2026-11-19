# THE LAST IDENTITY — Deployment-ready prototype

## What's included
- `index.html`: responsive emerald cyber-intelligence demo
- `manifest.webmanifest`: installable web-app metadata
- `service-worker.js`: caches the app shell for offline reopening after first successful load
- `icon.svg`: app icon

## Local preview
For the simplest preview, open `index.html` in Chrome or Edge. PWA install/offline features require serving over HTTPS or localhost.

## Publish with GitHub Pages
1. Create/sign in to a GitHub account.
2. Create a **Public** repository named `the-last-identity`.
3. Upload the four files in this folder to the repository root (not the containing folder).
4. Open repository Settings → Pages.
5. Under Build and deployment, choose **Deploy from a branch**.
6. Choose branch `main`, folder `/(root)`, then Save.
7. Wait for GitHub Pages to publish. The URL appears in Settings → Pages and usually has the form `https://YOUR-USERNAME.github.io/the-last-identity/`.

The URL is stable while the GitHub account, repository and Pages service remain active and in good standing. No hosting provider can promise that a free URL will never be removed or that a service will exist forever.

## Demo login
Role: Police Officer / Forensic Expert / System Administrator
Demo code: `IDENTITY2026`

## Critical limitations
This remains a front-end educational demo. It uses browser localStorage, so records are not shared across devices or users. The demo access code is not real authentication. It has no cloud database, secure server-side access control, biometric processing, government/police integration, or official identity verification.

Do not enter real personal, police, medical, or biometric information. Use fictional training records only. Match scores are illustrative metadata-only examples and are not proof of identity.

## To make it a real multi-user hosted application
A backend must be configured with a cloud database, real authentication, server-side authorization, audit logging, encryption, retention controls, backups, and legal/security review. This requires an account and project credentials owned by the deploying organization. Never put service-role or private keys in browser code or upload `.env` files to a public repository.


INTERFACE UPDATE
The dashboard has been refreshed with a full-width emerald cyber command-centre layout inspired by the supplied reference: status strip, horizontal navigation, centered title/mission hero, ethical demo notice, action links and synthetic metric tiles. Existing case modules and local demo interactions are retained.
