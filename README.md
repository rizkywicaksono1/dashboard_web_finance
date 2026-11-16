# SP-ER Finance Dashboard (Frontend)

A React-based frontend for a labor-union information and finance dashboard. The single-page interface is written in HTML with JSX and uses React, Tailwind CSS, Babel Standalone, and ExcelJS from CDNs.

## Included

- Finance dashboard and transaction views
- Member and agenda navigation
- Meeting-results and member-suggestion interfaces
- Excel export for suggestions
- API-based login and data operations

## Backend and data

This repository contains **frontend code only**. The Node.js backend, database, credentials, and production environment files are intentionally not included. The interface expects an API server for authentication and persisted data; it is not a standalone demo with working sample accounts.

Before deploying, configure `API_BASE` in `index.html` to the API URL you control. Do not put passwords, API tokens, database credentials, or other secrets in this frontend. Keep them in your server's environment configuration.

## Run / deploy

Serve `index.html` from a web server and configure the API URL first. The app loads its frontend libraries from public CDNs, so an internet connection is needed. For production, use a secured backend with authenticated routes, HTTPS, and appropriate database access controls.

## Portfolio note

This repository demonstrates the dashboard frontend and its user flows. It does not include a production-ready backend or sample user credentials.
