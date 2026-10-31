# CRPF Smart Mess Manager

A GitHub Pages-ready multi-page starter based on the supplied CRPF Smart Mess Manager dashboard design.

## Pages included
- Dashboard
- Members (member photo upload only)
- Mess Staff
- Ration Store
- Recipes
- Meals & Ration
- Accounts
- Reports (expense entry has no bill-photo upload)
- Handover (replaces Settlement)
- Backup & Restore
- Settings

## Run locally
Open `index.html` in a modern browser. For a better local development experience, use VS Code Live Server.

## Publish on GitHub Pages
1. Create a repository and upload all files from this folder to the repository root.
2. In repository **Settings → Pages**, choose deploy from branch, select `main` and `/ (root)`.
3. Save and wait for GitHub Pages to publish.

## Data and calculation notes
- This starter uses browser localStorage. Data does not automatically sync across different devices or commanders.
- Member photos are saved in the current browser with the member record. No bill photos are requested or stored.
- Export regular JSON backups. Photos can increase backup size.
- Member meal charges are split evenly across members selected for each meal.
- Stock value is quantity × rate; this starter does not automatically deduct ingredients from stock quantities.
- Handover figures are calculated from the entries recorded in this browser. Verify original bills, physical cash/bank balance, and official accounting requirements before signing.
- For production deployment, add authentication, a shared database, permissions, secure image storage, audit logs, and automated backups. Avoid storing real personnel/financial data in a public GitHub repository.
