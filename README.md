# After Hours Bar POS

Static Netlify frontend for After Hours Bar POS v5.8.

## Deploy

This repository contains the **website files at the repository root**. Connect this repository's `main` branch to your **existing** Netlify site with:
- Base directory: *(leave empty)*
- Build command: *(leave empty)*
- Publish directory: `.`

The POS uses a Supabase publishable client key; **never commit service-role keys, private authentication tokens, passwords, or environment secrets**.

**Deployment note:** Linking Netlify's Git deployment to the existing site is a separate step from uploading files to GitHub. Until linked, pushes here will not change the website. Verify cashier onboarding, checkout, stock updates, tabs, and reports on staging before relying on it for live trading.
