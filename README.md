# 🚀 Node.js & Express.js — 6 LPA Master Engineering Handbook
### (0 SE HERO — Complete 16 Chapters + Capstone Project + Request Tracing)

A comprehensive, zero-to-hero visual engineering handbook and revision guide for **Node.js, Express.js, MongoDB, Mongoose, Authentication, and Modern Backend Architecture**. Designed specifically for cracking high-bar software engineering and backend developer interviews.

---

## 🌟 What's Inside?

### 📚 16 Master Chapters:
- **Ch 01:** Core JavaScript Essentials, Scopes (TDZ), Parallel Promises (`Promise.all`, `Promise.allSettled`, `Promise.race`), Async/Await, Rest/Spread vs `arguments`
- **Ch 02:** Node.js Architecture, Libuv Internals, Event Loop 6 Phases, Module System & Multi-core CPU Scaling (`cluster` module, `worker_threads`)
- **Ch 03:** File System (`fs.promises`), Buffers, Streams Pipeline, Flowing vs Paused Mode & Backpressure
- **Ch 04:** Raw Node.js HTTP Server, TCP Streams, Methods & Status Codes
- **Ch 05:** Express.js Fundamentals, Routing, Auto-headers & Request Data Extraction
- **Ch 06:** Middleware Architecture, The `(req, res, next)` Pipeline & Execution Ordering
- **Ch 07:** Payload Data Ingestion (`params` vs `query` vs `body` vs `headers`)
- **Ch 08:** REST API Architecture, Dynamic Routing, JWT Authentication (Bearer Tokens) & Auth Bridge
- **Ch 09:** MVC Architecture Pattern, `express.Router()`, Separation of Concerns & Real Mongoose Model Layer
- **Ch 10:** Server-Side Rendering (SSR), EJS Templating Engine, `method-override` for PUT/DELETE & Layouts
- **Ch 11:** Production-Ready Node.js (CORS Preflight Mechanics, Helmet 11 Security Headers, Centralized Error Handler, Rate Limiting, PM2 & Gzip Compression)
- **Ch 12:** Database Layer — MongoDB & Mongoose (In-Memory Array Failure, NoSQL vs SQL, Atlas Setup, Schemas & Models, CRUD & `.populate()` 2-Query Join Mechanics)
- **Ch 13:** Real Authentication — bcrypt + Sessions vs JWT (One-Way Hashing, Pre-Save Password Hooks, Signup/Login Anti-Enumeration & Stateful vs Stateless Comparison)
- **Ch 14:** File Uploads — Multer Mastery (Binary Streams vs `express.json()`, `multipart/form-data`, `diskStorage`, MIME Filters & 5MB Limits)
- **Ch 15:** Input Validation — `express-validator` (Client vs Server-Side Validation, Schema Sanitization Chains & `validationResult(req)`)
- **Ch 16:** Production Deployment (Pre-Flight Hardening Checklist, Dynamic `process.env.PORT` & Render Cloud Zero-Downtime Deployment)

---

### 🏆 Capstone Project: "TechJobs Portal"
- Complete Production MVC Architecture
- Role-based & ownership authorization (`isJobOwner.js` middleware guard)
- Step-by-step 11-step build matrix
- 6 LPA Production Checklist

---

### 🔬 End-to-End Request Tracing (Step-by-Step Execution Lifecycle)
1. **Flow A:** `POST /api/jobs` (Protected creation with Auth, Validation, Pre-save hooks & DB persistence)
2. **Flow B:** `GET /api/jobs/:id` (Deep `.populate('postedBy')` 2-query relational resolution)
3. **Flow C:** Global Error Pipeline (`try/catch` ➡️ `next(err)` ➡️ Centralized Error Middleware)

---

### 💼 30+ Curated Technical Interview Masterclass Questions
Interactive interview prep cards with category filters, Indian relatable analogies, and concise English technical answers.

---

### 📄 Printable PDF Booklet
Includes pre-configured print stylesheet (`NodeJS_Express_Master_Revision.pdf`).

---

## 💻 How to View & Run Locally

1. **Option 1: Direct File Open**
   Simply open `index.html` in any web browser.

2. **Option 2: Live Local Server**
   ```bash
   npx serve .
   # or
   python3 -m http.server 5500
   ```

---

## 🌐 Live Web App
This handbook is deployed and hosted on GitHub Pages:
👉 **[https://omsawant13.github.io/Node-js-Notes/](https://omsawant13.github.io/Node-js-Notes/)**

---
*Created by [Om Sawant](https://github.com/OmSawant13) for 6 LPA Backend Engineering Preparation.*
