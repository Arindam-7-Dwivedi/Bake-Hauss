# 🍰 Bake Hauss

## 📖 Introduction
Bake Hauss is a strategic digital transformation project designed to transition a premium, home-based artisanal bakery into a scalable digital brand. Historically, the business relied on fragmented phone-based coordination and word-of-mouth. This project bridges that gap by engineering a bespoke full-stack ecosystem to make the business "accessible" while preserving its "home-baked" essence.

---

## 🎯 Project Objectives
The core mission of this transition includes:
* **Digital Presence**: Establishing a professional online footprint.
* **Visual Gallery**: Showcasing past cake designs to inspire customers.
* **Streamlined Workflow**: Simplifying inquiries and orders through a structured digital platform.
* **Storytelling**: Using a blog to improve customer engagement and brand narrative.

---

## 💻 Tech Stack
This project is built using a modern **PERN** stack, optimized for performance and a smooth developer experience:

* **Frontend:** React.js (scaffolded with Vite for speed)
* **Backend:** Node.js & Express.js (Vanilla JavaScript)
* **Database:** PostgreSQL (Relational database for structured e-commerce data)
* **ORM:** Prisma (For seamless database migrations and query building)

---

## 🔄 Website Workflow & Architecture

The application is divided into two primary experiences:

### 1. Customer Flow
* **Discovery:** Users browse the digital menu (Products) categorized by cake type, occasion, or dietary preference.
* **Cart & Customization:** Users can select quantities, add custom messages (e.g., "Happy Birthday!"), and specify fulfillment dates.
* **Checkout:** Upon checkout, the system locks in the *Price at Purchase* to protect against future menu price changes, generating an `Order` and associated `OrderItems` in the database.

### 2. Admin (Bakery Owner) Flow
* **Dashboard Access:** Secure login for the business owner.
* **Menu Management:** Create, update, or hide products without deleting them from historical records (`isAvailable` toggle).
* **Order Tracking:** View incoming orders, track fulfillment dates, and update statuses from `Pending` to `Baking` to `Delivered`.

---

## 🎨 Design & UI Mockups
All user interface designs, wireframes, and prototyping for Bake Hauss are maintained in Figma. 

* [🔗 View the Figma Design File Here](https://www.figma.com/make/V40KSdbdrs6jokY2OkuzgY/BAKEHAUSS-Homepage-Design?p=f&t=RPyaFMs9UBusKGTk-0&fullscreen=1) 
*(Note for developers: Please reference Figma for all exact hex codes, typography, and spacing)*

---
