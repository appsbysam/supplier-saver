# Supplier Saver

Mobile-first supplier purchasing web app built with vanilla JavaScript and Supabase.

## Features
- Email/password authentication with per-user Row Level Security
- Supplier CRUD with delivery days, cut-offs, minimum orders, fees and purchasing preferences
- Master product catalogue with favourites
- Supplier catalogue (many-to-many supplier/product pricing)
- Automatic price history capture in Postgres
- Shopping lists with product validation and an optimisation-ready action
- Reusable shopping-list templates: create, edit, duplicate, add products and create lists from templates
- Order history
- Business and optimisation settings
- CSV/XLSX Import Centre with official blank/sample Excel templates, including template imports
- Demo data loader/reset that keeps user data separate
- Mobile-first fixed-width responsive UI with no horizontal scrolling

## Backend
Dedicated Supabase project: `Supplier Saver` (`dipyagaxuoqttskrnnnh`).

The production database is completely separate from the Timesheet and B5 projects. Row Level Security is enabled and Supabase's security advisor currently reports no findings.

## Hosting
GitHub Pages is enabled. The production web app is served from the repository root.

## Current milestone
The app now covers the functionality built during the Lovable prototype phase, including the shopping-list template workflow.

Later-phase features intentionally not implemented yet:
- full optimisation strategy engine (lowest cost / fewer suppliers / preferred suppliers)
- purchase order generation and approval workflow
- AI PDF/invoice extraction
- advanced import column-mapping/preview wizard
