<div align="center">
  <br />
    <a href="https://github.com/samarth-kamble" target="_blank">
      <img src="./public/thumbnail.png" alt="Project Banner">
    </a>
  <br />

  <div>
    <img src="https://img.shields.io/badge/-Typescript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="typescript" />
    <img src="https://img.shields.io/badge/-PostgreSQL-black?style=for-the-badge&logoColor=white&logo=postgresql&color=4169E1" alt="postgresql" />
    <img src="https://img.shields.io/badge/-Next_._JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="nextdotjs" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" alt="nodejs" />
    <img src="https://img.shields.io/badge/-Stripe-black?style=for-the-badge&logoColor=white&logo=stripe&color=008CDD" alt="stripe" />
  </div>
  <h3 align="center">CaseCaobra: Custom iPhone Case</h3>
</div>

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)

## <a name="introduction">🤖 Introduction</a>

    A cutting-edge Custom Case App that enables users to create, discover, and enjoy mobile custom case, with their custom image.

Case cobra is website to design the mobile case with your photo. Basically this a mobile case store. Here, you put your image on the case. This ecommerce with the admin dashboard. Admin Dashboard access only for the one email which the admin.

## <a name="tech-stack">⚙️ Tech Stack</a>

- Next.js
- TypeScript
- PostgreSQL
- Redis
- Kinde
- ShadCN
- Tailwind CSS

## <a name="features">🔋 Features</a>

- 🛠️ Complete shop built from scratch in Next.js 14
- 💻 Beautiful landing page included
- 🎨 Custom artworks made by a professional illustrator
- 💳 Secret admin dashboard to manage orders
- 🖥️ Drag-and-drop file uploads
- 🛍️ Customers can purchase directly from you
- 🌟 Clean, modern UI on top of shadcn-ui
- 🛒 Completely custom phone case configurator
- 🔑 Authentication using Kinde
- ✉️ Beautiful thank-you email after purchase
- ✅ Apple-inspired configuration design
- ⌨️ 100% written in TypeScript
- 🎁 ...much more

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)
- [bun](https://bun.sh/) (Bun Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/samarth-kamble/Case-Ecommerce.git
cd Case-Ecommerce
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

or

```bash
bun install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
#PostgreSQL URL (NEON.TEch)
DATABASE_URL=

#  Kinde Auth
KINDE_SITE_URL=
KINDE_POST_LOGIN_REDIRECT_URL=
KINDE_POST_LOGOUT_REDIRECT_URL=
KINDE_CLIENT_ID=
KINDE_CLIENT_SECRET=
KINDE_ISSUER_URL=

# Web URL
NEXT_PUBLIC_SERVER_URL=

# Admin Email
ADMIN_EMAIL=

# UploadThing Crendntial
UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

# Stripe Crendential
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=

# Resend Crendential
RESEND_API_KEY=

```

**Running the Project**

```bash
npm run dev
```

or

```bash
bun run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.
