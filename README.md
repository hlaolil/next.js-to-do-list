# WDD 430 — React to-do list and Next.js dashboard

Two learning projects from WDD 430 (Web Full-Stack Development) at BYU–Pathway Worldwide.

**Live dashboard:** https://wdd430-cyan.vercel.app

## `to-do-list/`: React to-do list

A first React app, built with Vite. You add items, tick them off and delete them, all handled with `useState` in a single `App.jsx`. Items are kept in memory and clear when the page reloads.

```bash
cd to-do-list
npm install
npm run dev        # http://localhost:5173
```

## `nextjs-dashboard/`: Acme invoices dashboard

The dashboard app from the official [Next.js App Router course](https://nextjs.org/learn), worked through chapter by chapter:

- App Router layouts, nested routes, and loading and error pages with streaming skeletons
- A dashboard with revenue chart, summary cards and latest invoices
- Invoices: search (debounced, kept in the URL), pagination, and create, edit and delete with Server Actions and Zod validation
- Customers table
- Login with NextAuth (credentials and bcrypt) protecting `/dashboard`
- Data from Postgres (`app/lib/data.ts`)

```bash
cd nextjs-dashboard
npm install
npm run dev        # http://localhost:3000
```

Set `POSTGRES_URL` (plus `AUTH_SECRET` and `AUTH_URL` for NextAuth) in `nextjs-dashboard/.env`.

## Related

- [Handcrafted Haven](https://github.com/hlaolil/team_13): the WDD 430 team project
