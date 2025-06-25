# DevFlow – Agile Project Management App

DevFlow is a modern, full-stack agile project management tool for developers and teams to track, organize, and collaborate on tasks using a Scrum-style board. It features a clean UI, drag-and-drop task flow, and robust user management.

---

## ✨ Features

- 👤 User Authentication (Clerk)
- 📁 Create and manage projects
- 🧩 Add, update, and delete tasks
- 🟩 Kanban-style board with drag-and-drop
- 🔎 Task filtering and status updates
- 🏢 Organization and team management
- 📱 Responsive design for all devices

---

## ⚙️ Tech Stack

- Next.js (React)
- Tailwind CSS
- Prisma ORM
- PostgreSQL (or your configured database)
- Clerk (authentication & user management)
- Radix UI, Embla Carousel, Zod, Sonner

---

## 🧪 Getting Started Locally

### Prerequisites

- Node.js, npm
- PostgreSQL (or your configured database)
- Clerk account (for authentication)

### 1. Clone the Repository

```sh
git clone <your-repo-url>
cd <your-project-folder>
```

### 2. Install Dependencies

```sh
npm install
```

### 3. Set Up Environment Variables

Create a `.env` file in the root with the following:

```
DATABASE_URL=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding
```

### 4. Run Prisma Migrations

```sh
npx prisma migrate dev
```

### 5. Start the Development Server

```sh
npm run dev
```

---

## License

MIT
