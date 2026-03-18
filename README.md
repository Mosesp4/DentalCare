# 🦷 DentCare – AI-Powered Dental Consultation Platform

> **AI meets Dentistry.** Chat with an AI dentist or book virtual appointments with certified dental professionals — all from the comfort of your home.

[

![Live Demo](https://img.shields.io/badge/Live%20Demo-dental--care--theta.vercel.app-blue?style=for-the-badge)

](https://dental-care-theta.vercel.app)
[

![GitHub](https://img.shields.io/badge/GitHub-Mosesp4%2FDentalCare-black?style=for-the-badge&logo=github)

](https://github.com/Mosesp4/DentalCare)
[

![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

](LICENSE)

---

## 💡 Inspiration

My first painful toothache taught me how hard it is to get timely dental advice. Long waiting times, expensive consultations, and zero access after hours — DentCare was built to change that. The goal: make professional dental guidance accessible to anyone, anytime, through AI-powered interaction and virtual appointments.

---

## 🚀 Features

| Feature | Description |
|---|---|
| 🏠 **Landing Page** | Modern, responsive design with clean UI and beautiful gradients |
| 🔐 **Authentication** | Secure sign-in via Clerk (Google, GitHub, Email & Password) |
| ✉️ **Email Verification** | 6-digit code verification for added account security |
| 📅 **Appointment Booking** | Smooth 3-step flow: Pick Dentist → Choose Service & Time → Confirm |
| 📩 **Email Notifications** | Automated booking confirmations and reminders via Resend |
| 📊 **Admin Dashboard** | Manage dentists, appointments, and users efficiently |
| 🗣️ **AI Voice Agent** | Chat or speak with an AI-powered dentist via Vapi — anytime |
| 💳 **Subscription Billing** | Free + Paid plans with Clerk billing integration |
| 🧾 **Auto Invoicing** | Receipts and invoices sent automatically after bookings |
| 💸 **Smart Plan Upgrades** | Users pay only the difference when upgrading plans |
| 🧠 **PostgreSQL Database** | Robust and scalable data persistence |
| ⚡ **Optimized Fetching** | TanStack Query for efficient server-state management |

---

## 🧠 Tech Stack

**Frontend**
- [Next.js 14](https://nextjs.org/) + TypeScript
- [Tailwind CSS](https://tailwindcss.com/) + [Shadcn/UI](https://ui.shadcn.com/)
- [TanStack Query](https://tanstack.com/query)

**Backend & Infrastructure**
- [PostgreSQL](https://www.postgresql.org/) via Prisma ORM
- [Clerk](https://clerk.com/) – Authentication & Billing
- [Vapi](https://vapi.ai/) – AI Voice Agent
- [Resend](https://resend.com/) – Transactional Emails
- [Sevalla](https://sevalla.com/) – Deployment

**Tooling**
- Git & GitHub
- [Biome](https://biomejs.dev/) – Linting & Formatting
- [CodeRabbit](https://coderabbit.ai/) – AI Code Review

---

## 📸 Screenshots

> _Coming soon — screenshots of the landing page, booking flow, admin dashboard, and AI voice agent._

---

## ⚙️ Getting Started

### Prerequisites

- Node.js 18+
- PostgreSQL database
- Accounts on: [Clerk](https://clerk.com), [Vapi](https://vapi.ai), [Resend](https://resend.com)

### 1. Clone the repository

```bash
git clone https://github.com/Mosesp4/DentalCare.git
cd DentalCare
2. Install dependencies
npm install
3. Set up environment variables
Create a .env file in the root directory:
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

DATABASE_URL=your_postgres_database_url

NEXT_PUBLIC_VAPI_ASSISTANT_ID=your_vapi_assistant_id
NEXT_PUBLIC_VAPI_API_KEY=your_vapi_api_key

ADMIN_EMAIL=your_admin_email

RESEND_API_KEY=your_resend_api_key

NEXT_PUBLIC_APP_URL=your_app_url
4. Run database migrations
npx prisma migrate dev
5. Start the development server
npm run dev
Open http://localhost:3000 to view the app.
🗂️ Project Structure
DentalCare/
├── prisma/          # Database schema & migrations
├── public/          # Static assets
├── src/
│   ├── app/         # Next.js app router pages
│   ├── components/  # Reusable UI components
│   └── lib/         # Utility functions & config
├── .env             # Environment variables (not committed)
└── README.md
🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to open an issue or submit a pull request.
📜 License
This project is licensed under the MIT License — free to use and modify.
�
💙 Built with passion to make dental care smarter, faster, and more accessible. 

Moses Echela · @Mosesp4 

```
