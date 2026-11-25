# SpendWise — Student Budget Tracker

A React app for recording expenses, setting a monthly budget, tracking recurring fees, and viewing spending insights.

## Run locally

1. Install Node.js.
2. Run `npm install`.
3. Run `npm run dev` and open the local address shown in the terminal.

The app starts in demo mode with sample transactions and stores changes in the current browser. To connect a Supabase project, copy `.env.example` to `.env`, add its URL and anon key, and run the SQL in `Omar_Hassan_Ebayah/schema.sql` in the Supabase SQL editor.

## Deploy

The included GitHub Actions workflow builds the site and publishes it to GitHub Pages whenever changes are pushed to the `main` branch. The repository's Pages setting must use **GitHub Actions** as its build and deployment source.

The supplied SQL schema includes open demo policies for classroom prototyping. Replace them with per-user access policies before using real or private financial data.
