# Supplier Saver

Mobile-first supplier purchasing web app built with vanilla JavaScript and Supabase.

## Features
- Email/password authentication with per-user Row Level Security
- Supplier CRUD with delivery days, cut-offs, minimum orders, fees and purchasing preferences
- Master product catalogue with favourites
- Supplier catalogue (many-to-many supplier/product pricing)
- Automatic price history capture in Postgres
- Shopping lists and validation-ready optimisation action
- Order history
- Business and optimisation settings
- CSV/XLSX Import Centre with official blank/sample Excel templates
- Demo data loader/reset that keeps user data separate
- Mobile-first fixed-width responsive UI with no horizontal scrolling

## Backend
Dedicated Supabase project: `Supplier Saver` (`dipyagaxuoqttskrnnnh`).

Schema migration is in `supabase/migrations/20260825073003_initial_supplier_saver_schema.sql`.

## Hosting
This repository is static and GitHub Pages compatible. Serve `index.html` from the repository root.

## Current milestone
Matches the Lovable prototype stage as closely as practical, while leaving these later-phase features scaffolded rather than fully implemented:
- optimisation strategy engine (lowest cost / fewer suppliers / preferred suppliers)
- purchase order generation
- AI PDF/invoice extraction
- full template editor and create-from-template selector
