<h1 align="center"> Splitr 💸 – AI-Powered Expense Manager & Smart Settlements </h1>
<div align="center">

![Splitr Banner](./banner.png)

Splitr is a sleek, AI-driven web app that helps you manage personal and group expenses effortlessly. Inspired by Splitwise, Splitr lets you track expenses, settle debts smartly, analyze spending with real-time dashboards, and receive AI-powered insights and reminders. Built with modern tools like **Next.js**, **Convex**, **Gemini AI**, and **ShadCN UI**, it offers blazing-fast performance and a clean, responsive design.

</div>

---

## 🌟 Features

* **🧾 Add & Split Expenses**: Split equally, by percentage, or custom amounts.
* **🤝 Group & Individual Tracking**: Track who owes whom in real time.
* **⚡ Smart Debt Simplification**: Reduce unnecessary transactions automatically.
* **📊 Expense Analytics Dashboard**: Monthly trends, net balances & detailed views.
* **🧠 AI-Powered Insights**: Personalized spending analysis & smart reminders (Gemini AI).
* **🔔 Email Reminders**: Stay on top of dues with AI-generated emails (via RESEND).
* **👥 Contact & Group Management**: Create/join groups, manage members & payments.
* **📲 Fully Responsive UI**: Optimized for mobile, tablet, and desktop.

---

## 🛠️ Tech Stack

| Tech                                                                                                 | Description                               |
| ---------------------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![Next.js](https://img.shields.io/badge/Next.js-000?logo=nextdotjs\&logoColor=white)                 | React Framework for frontend              |
| ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css\&logoColor=white) | Utility-first CSS framework               |
| ![ShadCN UI](https://img.shields.io/badge/ShadCN_UI-000000?logo=vercel\&logoColor=white)             | Beautiful pre-built UI components         |
| ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript\&logoColor=white)       | Static typing for better dev experience   |
| ![Convex](https://img.shields.io/badge/Convex_DB-000000?logo=vercel\&logoColor=white)                | Real-time backend & database              |
| ![Gemini AI](https://img.shields.io/badge/Gemini_AI-4285F4?logo=google\&logoColor=white)             | AI for insights and reminders             |
| ![Resend](https://img.shields.io/badge/Resend_Email-F02E65?logo=resend\&logoColor=white)             | Transactional email service for reminders |
| ![Inngest](https://img.shields.io/badge/Inngest_Server-000000?logo=inngest\&logoColor=white)         | Event-driven serverless workflows         |
| ![Vercel](https://img.shields.io/badge/Vercel-000?logo=vercel\&logoColor=white)                      | Hosting & deployment                      |

---

## 🧭 How It Works

1. **Create or Join a Group**: Invite friends and manage shared expenses.
2. **Add Expenses**: Split equally, by percentage, or custom.
3. **Track Debts**: Real-time updates on what’s owed.
4. **View Dashboard**: Visual charts of your spending trends.
5. **AI Insights**: Receive smart analysis and reminders.
6. **Settle Up**: Use smart settlement suggestions to minimize transactions.

---

## 📸 UI Preview

<div align="center">

![Splitr UI Preview](./image.png)

> It's a fresh launch, so the dashboard is looking a bit empty—no expenses yet, haha! 🎉

</div>

---

## 🧪 Local Development

Clone the repository and set up your environment:

```bash
# Clone the repo
git clone https://github.com/codewmanas/splitr-ai.git

# Navigate to the project folder
cd splitr

# Install dependencies
npm install

# Run the development server
npm run dev
```

### 🔐 Environment Variables

Create a `.env` file in the root directory and add the following variables:

```env
# Deployment used by `npx convex dev`
CONVEX_DEPLOYMENT=

NEXT_PUBLIC_CONVEX_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

CLERK_JWT_ISSUER_DOMAIN=

RESEND_API_KEY=

GEMINI_API_KEY=
```

---

## 📬 Contact & Support

Want to contribute or suggest a feature? Open an issue or pull request! For other queries:

<p>
📧 Email: <a href="mailto:manas.kolaskar@somaiya.edu">My Mail</a><br>
</p>

---

<p>
Made with ❤️ by Manas and the Splitr team.
</p>
