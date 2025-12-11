# myJERAT Admin Dashboard

A modern, open-source admin dashboard template built with Astro, TailwindCSS, and Alpine.js. Inspired by Flowbite Admin Dashboard, designed with a clean and minimal approach.

## Tech Stack

- [Astro](https://astro.build) - Static site generator
- [TailwindCSS](https://tailwindcss.com) - Utility-first CSS framework
- [Alpine.js](https://alpinejs.dev) - Lightweight JavaScript framework
- [Lucide Icons](https://lucide.dev) - Icon library

## Features

- Responsive sidebar navigation with collapsible menus
- Dashboard with statistics cards and data tables
- CRUD pages (Users, Products)
- Authentication pages (Login, Register, Forgot Password, Reset Password)
- Profile and Settings pages
- Error pages (404, 500)
- Table page
- Dark overlay for mobile sidebar
- Breadcrumb navigation

## Getting Started

### Prerequisites

- Node.js 18+
- npm or pnpm

### Installation

```bash
# Clone the repository
git clone https://github.com/jeratpapua/myjerat-admin-dashboard.git

# Navigate to the project directory
cd myjerat-admin-dashboard

# Install dependencies
pnpm install

# Start the development server
pnpm run dev
```

The application will be available at `http://localhost:4321`.

### Build

```bash
# Build for production
pnpm run build

# Preview the production build
pnpm run preview
```

## Project Structure

```
src/
├── components/
│   ├── BaseHead.astro
│   ├── Breadcrumbs.astro
│   ├── Footer.astro
│   ├── Navbar.astro
│   └── Sidebar.astro
├── layouts/
│   ├── BaseLayout.astro
│   └── MainLayout.astro
├── pages/
│   ├── auth/
│   │   ├── forgot-password.astro
│   │   ├── login.astro
│   │   ├── register.astro
│   │   └── reset-password.astro
│   ├── crud/
│   │   ├── products/
│   │   │   └── index.astro
│   │   └── users/
│   │       └── index.astro
│   ├── pages/
│   │   ├── 404.astro
│   │   ├── 500.astro
│   │   ├── profile.astro
│   │   └── settings.astro
│   └── index.astro
└── styles/
    └── global.css
```

## About JERAT Papua

JERAT Papua (Jaringan Kerja Rakyat Papua) is a non-governmental organization founded in 2008, based in Jayapura City, Papua, Indonesia. The organization focuses on advocacy for indigenous knowledge and public policy that supports ecological justice and recognition of collective rights of Papuan indigenous peoples.

Learn more at [jeratpapua.org](https://jeratpapua.org)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.