# Full Stack AI Fianace Platform with Next JS, Supabase, Tailwind, Prisma, Inngest, ArcJet, Shadcn UI Tutorial 🔥🔥


<img width="1470" alt="Screenshot 2024-12-10 at 9 45 45 AM" src="https://github.com/user-attachments/assets/1bc50b85-b421-4122-8ba4-ae68b2b61432">

A powerful, secure, and beautiful AI-powered finance tracking platform built using modern full stack technologies. 🔥

Live Link 👉 [welthaifinance.vercel.app](https://welthaifinance.vercel.app/)

## 🚀 Tech Stack

- **Frontend**: Next.js 14, Tailwind CSS, Shadcn UI
- **Backend**: Supabase (PostgreSQL), Prisma ORM
- **Auth**: Clerk
- **AI**: Gemini API
- **Email**: Resend
- **Queue / Jobs**: Inngest
- **Security**: ArcJet
- **Deployment**: Vercel

---

## 🛠️ Features

- ✨ AI-powered financial assistant
- 📈 Budget and expense tracking
- 🔐 Secure authentication with Clerk
- 📬 Email notifications via Resend
- 📊 Realtime data with Supabase
- 🧠 GPT-like responses using Gemini
- ⚙️ Background jobs and automation with Inngest
- 🛡 Runtime protection via ArcJet

---

## 🔐 Environment Variables

Create a `.env` file in the root and add the following:

```env
DATABASE_URL=
DIRECT_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=

RESEND_API_KEY=

ARCJET_KEY=
