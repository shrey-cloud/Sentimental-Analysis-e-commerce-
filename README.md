# Spam Filter — Review Moderation Dashboard (frontend scaffold)

A React frontend scaffold for a product-review moderation dashboard: admin login,
product/review browsing, and filtered/deleted review queues, backed by local
mock data.

## How it works

- `src/App.jsx` wires up routing with a Mantine theme provider and navbar.
- `src/routes.jsx` defines the routes: Home, Login, Products, Reviews,
  Filtered, Deleted, About, plus a 404 page.
- `src/components/login` renders an admin login form. Validation is local only;
  submitting logs the values to the console — there is no real authentication.
- `src/components/navbar` renders the top navigation bar.
- `public/mock-api/` holds placeholder JSON: 100 mock products with stub
  reviews and 4 mock user accounts.
- The Products, Reviews, Filtered, Deleted, and About pages are title
  placeholders — no listing, filtering, or deletion logic is implemented.

## How to run

```bash
npm install
npm start
```

Opens http://localhost:3000 in the browser.

## Built with

React 17, Mantine v4 (UI components), react-router-dom v6.

## Known limitations

- Frontend only: no backend, no database, no real authentication.
- All data is mock/placeholder; the review-filtering logic does not exist yet.
- The login form accepts any input that meets the length rule.

## What was difficult

[Shreya to write — not obvious from the code.]
