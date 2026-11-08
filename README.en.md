# OHS Field Portal (demo)

*Türkçe: [README.md](README.md)*

At companies that provide occupational health and safety (OHS) services, the work goes like this: a specialist goes to the site and writes down findings; a manager plans who goes where; and the client company wants to see its own status. Usually all of this is scattered across Excel files, WhatsApp groups and paper. This portal brings the three roles together on one screen.

> This repo is a **demo version**. All company names, people and amounts are sample data.

## What it has
- **Screens by role:** the OHS specialist, the field manager and the client company each see their own view.
- **Company tracking:** visit plan, progress percentage, account balance.
- **Field report:** finding, risk level, action to take and deadline; a report with one click.
- **Task flow:** work orders from manager to specialist, with status tracking.
- **Bulletins:** safety announcements for the field.
- **Bulk import:** upload and preview a company list from CSV.
- **Live sync:** with Supabase Realtime everyone sees the same data instantly (off in the demo; data is kept in the browser).

## Tech
HTML · Tailwind CSS · plain JavaScript · Supabase (Postgres + Realtime) · Vercel

## Running it
Just open `index.html` in a browser. For live sync, enter your own Supabase project's details in `supabaseUrl` and `supabaseAnonKey`.

---
Built by **Emirhan Karaca**
