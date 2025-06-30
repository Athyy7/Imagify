# 🧠 Imagify – AI-Powered Text-to-Image Generator

**Imagify** is a full-stack SaaS application that transforms natural language prompts into vivid, AI-generated images in seconds. Designed for accessibility and performance, Imagify blends cutting-edge AI capabilities with a smooth user experience — all powered by a secure and scalable MERN architecture.

> 🖼️ Generate. 💬 Describe. ⚡ Visualize. All in under 5 seconds.

---

## 🚀 Overview

Imagify is more than just a text-to-image converter — it's a productivity tool for creators, designers, marketers, and developers. The application enables users to securely register/login, input creative prompts, and receive high-quality image output instantly, all while managing usage via a credit-based system and seamless Razorpay integration.

### 🔧 Key Highlights

- 🧩 **MERN Stack**: MongoDB, Express.js, React.js, Node.js
- 🔐 **Authentication**: JWT-based secure login/signup
- 💳 **Razorpay Integration**: Real-time credit top-up system
- 🌐 **RESTful API**: Backend endpoints built to scale and secure
- ⚡ **Framer Motion**: Clean UI/UX with smooth animation transitions
- 🖌️ **Tailwind CSS**: Modern, responsive and utility-first styling
- 📦 **MongoDB Atlas**: Cloud-hosted NoSQL database with schema validation

---

## 📊 Functional Stats

- ⏱️ **Avg Image Generation Time**: ~3–4 seconds per prompt
- 🛡️ **Authentication**: 100% protected routes with token middleware
- 📁 **Folder Architecture**: Organized for feature scaling & modularity
- 🎯 **Conversion Accuracy**: Optimized with text-to-image REST APIs
- 🧾 **Transactions**: Logged via MongoDB transactions schema for auditing

---

## 🧠 Why Imagify?

The problem with most AI image tools:
- ❌ Complex interfaces not friendly for beginners
- ❌ High costs for simple use cases
- ❌ Poor authentication and credit misuse
- ❌ Inflexible deployment and API dependencies

**Imagify solves this with:**
- ✅ Beginner-friendly UI built in React with intelligent state management via context API
- ✅ On-demand, pay-per-use Razorpay integration to avoid lock-ins
- ✅ Server-side validation with custom middleware and controller logic
- ✅ Scalable backend with REST endpoints and MongoDB Atlas
- ✅ Deployment-ready and modular for future enhancements (e.g., social sharing, image history, download tracking)

---

## 🛠️ Built With

| Tech               | Description                                      |
|--------------------|--------------------------------------------------|
| React.js           | Frontend library for building UI                 |
| Tailwind CSS       | Utility-first styling for responsiveness         |
| Framer Motion      | Animations and transitions for interactivity     |
| Node.js + Express  | REST API and backend logic                       |
| MongoDB Atlas      | NoSQL database for user and transaction data     |
| JWT                | Authentication and secure route protection       |
| Razorpay API       | Integrated payment gateway for credit purchase   |
| REST APIs          | Used for AI-based image generation               |

---


---

## 🔒 Security & Auth

- Environment variables secured using `.env` files
- Tokens stored securely in local storage
- Custom Express middleware (`auth.js`) for protected routes
- MongoDB indexes set for unique user entries (email)

---

> 👨‍💻 Made with passion and precision by [Atharav Shivhare](https://github.com/Athyy7)

