# 🚀 Elevate AI

**Elevate AI** is an AI-powered career development platform designed to help students and professionals prepare for their careers. It leverages **Google Gemini AI** to provide personalized career guidance, technical quizzes, mock interviews, resume assistance, and skill assessments—all in one modern web application.

## ✨ Features

- 🤖 AI-powered Career Coach
- 💼 AI Mock Interview Preparation
- 📝 Technical Quiz Generator
- 📄 AI Resume & Cover Letter Assistance
- 📊 Personalized Career Dashboard
- 🎯 Skill Assessment & Feedback
- 📈 Career Progress Tracking
- 🔐 Secure Authentication with Clerk
- ⚡ Responsive and Modern UI

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Next.js 15 | Full-stack React Framework |
| React 19 | Frontend UI |
| Prisma ORM | Database ORM |
| PostgreSQL (Supabase) | Database |
| Clerk | Authentication |
| Google Gemini AI | AI Features |
| Tailwind CSS | Styling |
| Shadcn UI | UI Components |
| Inngest | Background Jobs |
| Zod | Validation |

---

## 📂 Project Structure

```text
app/
actions/
components/
hooks/
lib/
prisma/
public/
```

---

## ⚙️ Environment Variables

Create a `.env` file in the project root.

```env
DATABASE_URL=
DIRECT_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

GEMINI_API_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
```

---

## 🚀 Getting Started

Clone the repository

```bash
git clone https://github.com/nickdevtech/Ai-Coach.git
```

Navigate to the project

```bash
cd Ai-Coach
```

Install dependencies

```bash
pnpm install
```

Generate Prisma Client

```bash
pnpm prisma generate
```

Push Database Schema

```bash
pnpm prisma db push
```

Start the development server

```bash
pnpm dev
```

Open **http://localhost:3000** in your browser.

---

## 🏗️ Production

Build the project

```bash
pnpm build
```

Run production server

```bash
pnpm start
```

---

## 🌟 AI Modules

- **AI Career Coach** – Personalized career guidance based on your profile.
- **AI Quiz Generator** – Generates technical quizzes for your chosen skills.
- **AI Mock Interview** – Practice with AI-generated interview questions.
- **Skill Assessment** – Analyze your performance and receive improvement suggestions.

---

## 🔐 Authentication

User authentication is handled securely using **Clerk**, including:

- Sign Up
- Sign In
- Session Management
- Protected Routes

---

## 🌐 Live Demo

👉 **https://ai-coach-gu85-t6dnnqs6j-nicks-projects-12f88e89.vercel.app/**

---

## 👨‍💻 Author

**Nick DevTech**

- GitHub: https://github.com/nickdevtech/Ai-Coach

---

## ⭐ Support

If you found this project useful, consider giving it a **⭐ Star** on GitHub. It helps support the project and motivates future improvements!