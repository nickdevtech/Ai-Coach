# 🧑‍💼 ElevateAI



An AI-powered full-stack career coach that helps you **build resumes, generate cover letters, and prepare for interviews**.  
Built with **React 19 + Next.js 15**, styled with **Tailwind CSS + Shadcn UI**, and powered by **Gemini AI**.

## 📘 Live Demo
👉 [AI Career Coach](https://ai-coach-gu85-git-main-nicks-projects-12f88e89.vercel.app)  

---

## 🚀 Features
- 📄 **Resume Builder** – Create professional resumes in minutes
- 📝 **Cover Letter Generator** – AI Tailored cover letters from job descriptions
- 🎯 **Interview Preparation** – AI-generated practice questions & performance tracking
- 🔐 **Authentication** – Secure login with Clerk
- ⚡ **Background Workflows** – Async tasks powered by Inngest
- 🤖 **AI Integration** – Gemini API for insights & text generation
- 🎨 **Modern UI** – Shadcn UI + TailwindCSS components

---

## 🛠 Tech Stack
- **Frontend:** React 19, Next.js 15
- **UI & Styling:** TailwindCSS, Shadcn UI
- **Database:** NeonDB (Postgres) with Prisma ORM
- **Auth:** Clerk
- **Workflows:** Inngest
- **AI API:** Gemini API
- **Deployment:** Vercel

---

## 📂 Project Structure
```
app/           # Next.js app routes
components/    # Reusable UI components
data/          # Static or seed data
hooks/         # Custom React hooks
lib/           # Utilities & helpers
prisma/        # Prisma schema & migrations
public/        # Static assets
```

---

## ⚡ Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/nickdevtech/ai-career-coach.git
cd ai-career-coach
```

### 2. Install dependencies
```bash
pnpm install
# or
npm install
```

### 3. Configure environment variables
Create a `.env.local` file in the project root:

```bash
DATABASE_URL="your-neondb-url"
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY="your-clerk-publishable-key"
CLERK_SECRET_KEY="your-clerk-secret"
GEMINI_API_KEY="your-gemini-api-key"
```

### 4. Run database migrations
```bash
npx prisma migrate dev
```

### 5. Start the dev server
```bash
pnpm dev
# or
npm run dev
```

The app will be running at 👉 `http://localhost:3000`

---

Run database migrations in production:
```bash
npx prisma migrate deploy
```

---

## 🤝 Contributing
Contributions are welcome! Fork the repo, make changes, and submit a pull request.

---

## 📄 License
This project is licensed under the **MIT License**.

---

## 👤 Author
**nickdevtech**  
🔗 [GitHub](https://github.com/nickdevtech)
