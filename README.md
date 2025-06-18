# 📸 ImageKit Full Stack Project (Next.js + ImageKit + NextAuth)

This project is a **full-stack web application** built using **Next.js** that integrates **ImageKit** for advanced image handling and **NextAuth** for secure authentication. The goal of this project is to understand how to build scalable, secure, and media-efficient applications using modern full-stack technologies.

> ⚡ This project was built as part of a learning course and has significantly enhanced my understanding of full-stack development, authentication, and media optimization. It has added strong value to my development profile.

---

## 🚀 Features

- 🌐 **Next.js App Structure** with API routes and modern folder setup
- 🧠 **Model Design** for handling user data and media metadata
- 🔗 **Database Integration** (using modern ORM/tools for DB connection)
- 🔒 **NextAuth** for authentication and session management
- 🖼️ **ImageKit Integration** for high-performance image delivery
- ✨ **AI-Powered Image URLs** (transformation, resizing, etc.)
- 🧾 **Frontend for Register/Login**
- 🔐 **Middleware-Based Routing** for protected pages
- 🎯 **Frontend ImageKit Integration** for upload/view

---

## 🧱 Project Structure
```
Imagekit/
├── app/ # App-level pages and components
├── lib/ # Helper functions and modules
├── models/ # Data models (User, Video etc.)
├── public/ # Static assets
├── .gitignore # Files/folders to ignore in Git
├── env.sample # Sample environment config
├── eslint.config.js # Linting rules
├── middleware.ts # Route protection middleware
├── next.config.js # Next.js configuration
├── next-auth.d.ts # Type definitions for NextAuth
├── package.json # Dependencies and scripts
├── postcss.config.js # PostCSS setup
├── tsconfig.json # TypeScript configuration
├── types.d.ts # Global custom types
```
---

## 🛠️ What I Learned

- **Designing Models in Next.js:** Creating modular, scalable models for users and image data storage.
- **Database Connectivity in Next.js:** Establishing secure and efficient DB connections using environment configurations.
- **Mastering NextAuth:** Implementing secure user authentication, sessions, and route protection using middleware.
- **Handling ImageKit:** Using URL-based image transformations powered by ImageKit’s AI capabilities.
- **Frontend Design:** Implementing clean login/register pages, input validations, and responsive design.
- **Frontend ImageKit Integration:** Uploading and managing images from the frontend securely and efficiently.

---

## 📦 How to Use

This is a Next.js project bootstrapped with `create-next-app`.

### 🔧 Installation & Setup

- 1.Clone the repository:
```bash
git clone https://github.com/your-username/Imagekit.git
cd Imagekit
```
- 2.Install dependencies:
```bash 
npm install
# or
yarn
# or
pnpm install
# or
bun install
```
- 3.Set up environment variables:
Copy .env.sample to .env
Add your ImageKit keys, database URI, and NextAuth secrets in the .env file.

- 4.Start the development server:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```
- 5.Open your browser at:
```bash
http://localhost:3000
```
