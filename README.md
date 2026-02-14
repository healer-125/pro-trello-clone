# Pro Trello Clone

A production-ready, full-stack project management application inspired by Trello. Built with **Next.js 15**, **TypeScript**, **Supabase**, and **Clerk**—featuring real-time collaboration, drag-and-drop Kanban boards, and subscription-based access control.

---

## Demo

**Live Preview:** [https://trello-clone-by-shan.vercel.app](https://trello-clone-by-shan.vercel.app)

---

## Skills Demonstrated

### TypeScript & JavaScript
- **TypeScript** — Full type safety, interfaces, generics, and strict mode
- **Modern ES6+** — Async/await, destructuring, spread operators, modules
- **Type-safe API design** — End-to-end type consistency across frontend and backend
- **Type inference & utility types** — Efficient type composition and inference

### AI & Intelligent Features
- **AI-ready architecture** — Modular, extensible design for future ML/AI integrations
- **Structured data models** — Clean schemas suitable for AI-powered analytics and suggestions
- **Context-aware filtering** — Smart task filtering by priority, assignee, and due dates
- **Search & discoverability** — Fast, queryable data layer for AI-assisted search

### UI & Frontend Frameworks
- **React 19** — Latest React with Server Components and concurrent features
- **Next.js 15** — App Router, Server-Side Rendering, route handlers
- **Component-based architecture** — Reusable, composable UI with clear separation of concerns
- **Experience with:** Tailwind CSS, Shadcn/UI, Radix UI, and utility-first CSS

---

## Features

### Core Functionality
- **Kanban Board Management** — Create, edit, and organize boards with customizable colors and titles
- **Drag & Drop Interface** — Smooth task reordering with @dnd-kit
- **Column Management** — Create, edit, and delete columns to structure workflows
- **Task Management** — Tasks with titles, descriptions, assignees, priorities, and due dates
- **Real-time Updates** — Live sync of board changes across sessions via Supabase

### Security & Data Protection
- **Row Level Security (RLS)** — Database-level security so users only access their own data
- **User Isolation** — Complete data separation between accounts

### User Experience
- **Modern Authentication** — Secure sign-in/sign-up with Clerk
- **Responsive Design** — UI built with Tailwind CSS and Shadcn UI
- **Dashboard Overview** — Centralized view of boards with statistics
- **Advanced Filtering** — Filter tasks by priority, assignee, and due dates
- **Search** — Search across boards and tasks

### Subscription Model
- **Free Tier** — Limited to 1 board for free users
- **Premium Plans** — Unlimited boards and advanced features via Clerk pricing
- **Upgrade Prompts** — Seamless upgrade flow for free users

### Technical Highlights
- **Full TypeScript** — Type safety across the app
- **Server-Side Rendering** — Next.js 15 for performance
- **Supabase** — Real-time database and authentication
- **Feature-based architecture** — Modular, maintainable codebase

---

## Screenshots

| Home | Sign Up | Dashboard |
|------|---------|-----------|
| ![Home](https://i.ibb.co/b5HDBpvn/trello-clone-home.png) | ![Sign Up](https://i.ibb.co/HTGNY3gj/trello-clone-signup.png) | ![Dashboard](https://i.ibb.co/d03BSbpJ/trello-clone-dashboard.png) |

*Modern landing page • User registration with Clerk • Board overview and statistics*

| Filters | Board | Pricing |
|---------|-------|---------|
| ![Filters](https://i.ibb.co/5gk56gKV/trello-clone-dropdown.png) | ![Board](https://i.ibb.co/sJK02cFR/trello-clone-edit-board.png) | ![Pricing](https://i.ibb.co/ZpRsPFRL/trello-clone-pricing.png) |

*Filter dropdown • Interactive Kanban board • Subscription plans*

---

## Tech Stack

| Category | Technologies |
|----------|--------------|
| **Framework** | Next.js 15, React 19 |
| **Language** | TypeScript 5 |
| **Styling** | Tailwind CSS 4, Shadcn UI, Radix UI |
| **Database** | Supabase (PostgreSQL) |
| **Auth** | Clerk |
| **Drag & Drop** | @dnd-kit |
| **Icons** | Lucide React |
| **Tooling** | ESLint, PostCSS, Turbopack |

---

## Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/healer-125/pro-trello-clone.git
cd pro-trello-clone
```

### 2. Install dependencies

```bash
npm install
```

### 3. Environment variables

Create a `.env` file in the project root:

```env
# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

# Supabase
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
```

### 4. Start the dev server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## Project Structure

```
pro-trello-clone/
├── app/                    # Next.js App Router
├── components/             # Shared UI components
├── features/               # Feature modules (auth, boards, dashboard, pricing)
├── lib/                    # Utilities, Supabase client, services
└── providers/              # React context providers
```

---

## Deployment

Deployed on **Vercel** with automatic builds from the main branch.

---

## Author

**healer-125**

- GitHub: [@healer-125](https://github.com/healer-125)
- Project: [pro-trello-clone](https://github.com/healer-125/pro-trello-clone)

---

## License

This project is available for portfolio and educational use. For questions or feedback, please open an issue on GitHub.
