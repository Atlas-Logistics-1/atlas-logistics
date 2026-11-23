# Atlas Logistics — US TMS Demo

A responsive, browser-based transportation management dashboard prototype for US domestic freight operations.

## Features
- English / Russian interface toggle
- US-focused units and conventions: USD, miles, pounds, states, domestic lanes
- Overview KPIs and shipment status dashboard
- Shipment management (create, edit, search, filter)
- Dispatch board and driver assignment
- Driver, carrier, customer and invoice records
- Demo freight rate estimator
- CSV export for records
- Document selection UI
- Local browser persistence with `localStorage`
- Responsive desktop and mobile layout

## Run locally
Open `index.html` in a modern browser. No build step is required.

## Publish with GitHub Pages
1. Create a new **public** repository on GitHub, for example `atlas-logistics-us`.
2. Upload `index.html`, `README.md`, and `.nojekyll` from this folder to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main**, folder **/(root)**, then click **Save**.
6. Wait for GitHub Pages to publish. The public address will appear in the Pages section.

## Important limitations
This is a front-end demo, not a production TMS. Records are stored only in the current browser. It does not connect to real GPS/ELD, FMCSA, carrier APIs, EDI, payment gateways, email/SMS, cloud file storage, or live rate databases. Quote estimates and sample records are illustrative. A production deployment needs a secure backend, authentication, database, role permissions, audit logs, and vetted third-party integrations.
