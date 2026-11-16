# Anna Play — Free-to-play demo

A responsive, Vercel-compatible static prototype inspired by the supplied screenshots.

## Included
- `index.html`: responsive game dashboard and user interface
- `admin.html`: local demo controls
- `assets/style.css`: responsive styling
- `assets/app.js`: demo game logic and browser storage
- `vercel.json`: static deployment configuration

## Run locally
Open `index.html` in a browser, or run a static server from this folder.

## Deploy to Vercel
1. Create a GitHub or GitLab repository and upload the contents of this folder.
2. In Vercel, choose **Add New → Project** and import that repository.
3. Framework preset: **Other**.
4. Build command: leave empty.
5. Output directory: `.` (root).
6. Deploy.

## Important prototype limitations
This is a free entertainment demo only. It has no deposits, payment gateway, cash prizes, withdrawals, transferable credits, official lottery feed, or real-money wagering. Virtual points are stored in `localStorage` on one browser/device. The demo admin page is not authenticated and is not secure. It is not a multi-user backend.

For a production multi-user version, add a secure backend/database (for example Supabase), server-side authentication, role-based admin access, audit logs, rate limits, and security review. Keep any future feature set within applicable laws and platform policies. Do not use this prototype to sell tickets or handle money.
