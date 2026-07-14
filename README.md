# 📰 Roz-Nama (روز نامہ)

Roz-Nama is a dynamic, fully responsive serverless web application that brings live global news right to your fingertips. Built using Python's **Flask** framework, styled natively with **Sass**, and powered structurally by **Bootstrap 5**, Roz-Nama delivers real-time news articles quickly, cleanly, and securely.

🔗 **Live Demo:** [https://roz-nama.vercel.app/](https://roz-nama.vercel.app/)

---

## 🚀 Key Features

* **Real-time Global News:** Powered by the NewsAPI integration to pull the latest breaking headlines instantly.
* **Dynamic Search Filtering:** Quickly search for news topics (e.g., tech, sports, business) directly from the navigation bar.
* **Automatic Quality Filter:** Built-in Python backend filtering to automatically strip out broken or "removed" placeholders from the news feed.
* **Serverless Deployment:** Optimized to run entirely within Vercel's Serverless Function architecture for fast global delivery.
* **Security-First Architecture:** Utilizes strict environment variable routing to keep confidential API credentials safely hidden from public source code.

---

## 🛠️ The Tech Stack

### 🐍 Flask (The Engine)
Flask acts as the backbone serverless controller for Roz-Nama. It handles the dynamic URL routing, captures incoming user search queries, dispatches asynchronous HTTP requests to the News API via the `requests` library, and sanitizes incoming data payloads before dynamically passing clean contexts to Jinja2 HTML templates.

### 🎨 Sass (The Custom Identity)
Instead of relying on boilerplate styles, Roz-Nama utilizes Sass (Syntactically Awesome Style Sheets) to build a unique visual identity. By leveraging nesting, variables, and clean component modules, our custom stylesheet controls typographic rhythm, card layouts, and subtle micro-interactions across the news grid.

### ⚡ Bootstrap 5 (The Structural Transformation)
Integrating Bootstrap directly into the Flask environment entirely transformed how Roz-Nama operates. 

---

## 💎 The Bootstrap Transformation: Before vs. After

Integrating Bootstrap didn't just add style; it fundamentally altered the development speed, responsiveness, and structural layout of the application. 

| Feature | Without Bootstrap | With Bootstrap Integration |
| :--- | :--- | :--- |
| **Grid Layout** | Messy custom CSS floats or fragile flexbox math trying to map multiple news cards evenly. | Seamless use of the `.row` and `.col-md-4` fluid flex grid, snapping cards cleanly into place across all viewports. |
| **Mobile Responsiveness** | Complex media queries written manually to prevent text overlapping on small screens. | **Native mobile-first responsiveness.** Breakpoints handle layouts natively so the layout flows effortlessly from mobile to 4K displays. |
| **Components** | Days spent writing custom CSS for buttons, search fields, cards, and navigation bars. | Utilizes polished Bootstrap `.card`, `.navbar`, and form layouts, allowing immediate focus on core application logic. |
| **UI Polish** | Static, dry layouts lacking consistent spacing, padding, and UI depth. | **Utility-driven perfection.** Easy utility classes (`g-4`, `p-3`, `shadow-sm`) added instant, professional depth and modern padding. |

---
