<<<<<<< HEAD
<h1 align="center">🦷 DentCare – Dental Platform with AI Voice Agent 🦷</h1>
=======
<h1 align="center">🦷 DentCare: AI-Powered Dental Consultation Platform with Voice Agent 🦷</h1>
>>>>>>> 829dc8771a9ed1ac477bdb75e7b5ed105f9e8988

<p align="center">
  <b>AI meets Dentistry.</b> DentCare lets users chat with an AI Dentist or book virtual appointments with certified dental professionals — all from the comfort of their home.
</p>

<p align="center">
<img width="1822" height="939" alt="Screenshot (202)" src="https://github.com/user-attachments/assets/8f0d9035-3136-4a8a-9a45-193e7344abe1" />

---

## 💡 Inspiration

DentCare was inspired by my first painful experience with a toothache and the difficulty of getting timely dental consultation. The goal is to make professional dental guidance accessible anytime through AI-powered interaction and virtual appointments.

---

## 🚀 Features

- 🏠 **Modern Landing Page** – Beautiful gradients, responsive design, and clean UI.
- 🔐 **User Authentication** – Secure sign-in via Clerk (Google, GitHub, Email & Password).
- 🔑 **Email Verification** – 6-digit code verification for added security.
- 📅 **Appointment Booking System** – Smooth 3-step flow: *Dentist → Service & Time → Confirm*.
- 📩 **Email Notifications** – Automated booking confirmations using **Resend**.
- 📊 **Admin Dashboard** – Manage dentists, appointments, and users efficiently.
- 🗣️ **AI Dentist Voice Agent** – Chat or talk with an AI-powered dentist (via **Vapi**).
- 💳 **Subscription Payments** – Free + Paid plans with Clerk billing integration.
- 🧾 **Auto Invoicing** – Receipts and invoices sent automatically via email.
- 💸 **Smart Plan Upgrades** – Pay only the difference when upgrading.
- 🧠 **PostgreSQL Database** – Robust and scalable data persistence.
- 🎨 **Tailwind CSS + Shadcn** – Elegant styling with responsive design.
- ⚡ **TanStack Query** – Optimized server-state management and fetching.

---

---

## 🧠 Tech Stack

**Frontend:** Next.js 14, TypeScript, Tailwind CSS, Shadcn/UI  
**Backend:** PostgreSQL, Vapi, Resend API, Clerk Auth  
**Tools:** Git, GitHub, CodeRabbit, TanStack Query, Sevalla  
**AI Integration:** Vapi AI Voice Agent  

---

## 🧪 .env Setup

```bash
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

DATABASE_URL=your_postgres_database_url

NEXT_PUBLIC_VAPI_ASSISTANT_ID=your_vapi_assistant_id
NEXT_PUBLIC_VAPI_API_KEY=your_vapi_api_key

ADMIN_EMAIL=your_admin_email

RESEND_API_KEY=your_resend_api_key

NEXT_PUBLIC_APP_URL=your_app_url

```

## Run the app

```bash
1- npm install
2- npm run dev
```

##📜 License

This project is licensed under the MIT License — free to use and modify.

<p align="center"> 💙 Built with passion to make dental care smarter, faster, and more accessible. </p>

