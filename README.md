# APLIKASI UPDATE — SEND TO TELEGRAM

Frontend preview for the multi-Pool Furniture / COMSER update application.

## Deploy to Cloudflare Pages using GitHub

1. Create a new GitHub repository named `aplikasi-update-send-to-telegram`.
2. Upload `index.html` and this `README.md` to the repository root.
3. In Cloudflare Dashboard, open **Workers & Pages** → **Create** → **Pages** → **Connect to Git**.
4. Select the GitHub repository.
5. Configure:
   - Framework preset: **None**
   - Build command: leave blank
   - Build output directory: `.` (repository root)
6. Deploy. Cloudflare will assign a `*.pages.dev` address.

## Important

This package is the current frontend preview only. It still uses demo data and local browser storage. It is not yet connected to live Google Sheets, Apps Script, Telegram bots, or a production photo-storage service. Do not enter real operational credentials or bot tokens in this frontend.
