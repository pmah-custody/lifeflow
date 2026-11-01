# LifeFlow AI

Mobile-first Arabic personal organizer: https://lifeflow23.github.io/

GitHub Pages: main branch, root folder. Default build base is /.
Editable source: lifeflow-source.zip. Run pnpm install --frozen-lockfile then pnpm build.

Records stay in this browser's IndexedDB. No desktop or local network required. Cross-device sync is not enabled. Export backups from Settings. Data from the previous origin must be exported there and imported at the new URL; it does not migrate automatically.

Smart Capture can use Gemini 3.5 Flash-Lite through a password-protected Cloudflare Worker. Sign in from Settings to enable it. Financial, unknown, and mixed sensitive input remains local. The Worker key and login password are managed secrets and are never included in this repository, website bundle, or source archive. Gemini does not send email or write records directly; the app validates proposals and saves them locally.

272 baseline checks and 62 AI checks passed. Live Gemini interpretation and isolated IndexedDB persistence were verified on November 1, 2026. Physical iPhone installation, keyboard, popup sign-in, and offline checks remain pending.

No user records or credentials are included. See ASSET-LICENSES.md.
