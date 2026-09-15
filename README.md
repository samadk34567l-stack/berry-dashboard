# Berry Dashboard

Ek React aur Vite par bana hua admin dashboard, jismein Material UI (MUI) components, Recharts se charts, aur React Router se multi-page navigation use hota hai.

## Features

- **Dashboard & Analytics** — earnings, income, aur total growth charts
- **CRM Module** — contact list, contact cards
- **Customer Management** — create, edit, view aur list customers
- **Order Management** — create, edit, view aur list orders
- **Blog, Statistics, Invoice** pages
- **User Management** — user list aur profile
- **Authentication pages** — login aur signup
- Responsive layout with Navbar aur Sidebar

## Tech Stack

- [React 18](https://react.dev/)
- [Vite 5](https://vitejs.dev/)
- [Material UI (MUI) 5](https://mui.com/)
- [Recharts](https://recharts.org/)
- [React Router DOM](https://reactrouter.com/)
- [Notistack](https://notistack.com/) (notifications)

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 ya usse zyada recommended)
- npm

### Installation

```bash
# Dependencies install karein
npm install
```

### Development

```bash
# Development server chalayein
npm run dev
```

App `http://localhost:5173` par khul jayega (default Vite port).

### Build

```bash
# Production build banayein
npm run build
```

### Preview

```bash
# Production build ko locally preview karein
npm run preview
```

## Project Structure

```
berry-dashboard-main/
├── index.html
├── package.json
├── vite.config.js
└── src/
    ├── App.jsx
    ├── main.jsx
    ├── theme.js
    ├── components/      # Reusable UI components (cards, charts, etc.)
    ├── data/             # Static/mock data
    ├── layout/           # MainLayout, Navbar, Sidebar
    └── pages/            # Route-level pages (Dashboard, CRM, Orders, etc.)
```

## License

Is project ka license specify nahi kiya gaya hai. Zaroorat ke hisaab se apna license add karein.
