<!-- Header Banner -->
<div align="center">
  <img src="https://res.cloudinary.com/delqnymxb/image/upload/v1778237120/Gemini_Generated_Image_671l5671l5671l56_dpn2ul.png" alt="GZMart Logo" width="120" height="120" style="border-radius: 20px;" />
  <h1>🛒 GZMart</h1>
  <p><strong>B2C E-Commerce Platform & Mini-ERP System for Cross-Border Fashion Retail</strong></p>
  <p><em>Capstone Project · SEP490 · FPT University</em></p>

  <!-- Badges -->
  <p>
    <img src="https://img.shields.io/badge/React-18.3-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React"/>
    <img src="https://img.shields.io/badge/Node.js-18%2B-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js"/>
    <img src="https://img.shields.io/badge/MongoDB-Atlas-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>
    <img src="https://img.shields.io/badge/Redis-ioredis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"/>
    <img src="https://img.shields.io/badge/Socket.io-4.x-010101?style=for-the-badge&logo=socket.io&logoColor=white" alt="Socket.io"/>
  </p>
  <p>
    <img src="https://img.shields.io/badge/Google_Gemini_AI-Powered-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Gemini AI"/>
    <img src="https://img.shields.io/badge/LiveKit-Streaming-FF6B6B?style=for-the-badge&logo=webrtc&logoColor=white" alt="LiveKit"/>
    <img src="https://img.shields.io/badge/PayOS-Payment-00C9FF?style=for-the-badge&logo=stripe&logoColor=white" alt="PayOS"/>
    <img src="https://img.shields.io/badge/License-Private-red?style=for-the-badge" alt="License"/>
  </p>
</div>

---

## 📖 About

**GZMart** is a full-stack web platform built for **cross-border fashion retail** in Vietnam. It integrates a powerful **B2C e-commerce storefront** with a **Mini-ERP back-office** for sellers, giving every stakeholder — buyers, sellers, and admins — a tailored, feature-rich experience.

> 🎓 Built as a graduation capstone project (SEP490) at FPT University by a team of 5 developers.

---

## 🗺️ Platform Overview

```
┌─────────────────────────────────────────────────────────────────┐
│                         GZMart Platform                         │
├───────────────┬──────────────────────────┬──────────────────────┤
│     BUYER     │      SELLER (ERP)        │        ADMIN         │
├───────────────┼──────────────────────────┼──────────────────────┤
│ AI Image Srch │ Purchase Order Mgmt      │ User Management      │
│ AI Chatbot    │ Inventory Tracking       │ Flash Sale Oversight │
│ Flash Sales   │ Landed Cost Calculator   │ Banner / Ads Mgmt    │
│ Live Shopping │ Campaign & Vouchers      │ Platform Settings    │
│ Cart/Checkout │ Finance & Revenue Rpt    │ System Dashboard     │
│ GHN Shipping  │ Live Streaming Studio    │ Exchange Rate Mgmt   │
│ PayOS Payment │ Shop Decoration          │ Subscription Tiers   │
│ Loyalty Coins │ Bulk Product Upload      │ Dispute Resolution   │
│ Reviews/RMA   │ Order Management         │ Seller Applications  │
└───────────────┴──────────────────────────┴──────────────────────┘
```

---

## ✨ Key Features

### 🛍️ Buyer Experience

| Feature | Description |
|:--------|:------------|
| 🔍 **AI Image Search** | Upload any photo → instantly find visually similar products using vector embeddings |
| 🤖 **AI Chatbot** | Gemini-powered assistant to discover products and answer queries in natural language |
| ⚡ **Flash Sales** | Time-limited deals with real-time countdown, live stock tracking, and smart queuing |
| 📡 **Live Shopping** | Watch seller livestreams via LiveKit and purchase products in real time |
| 🎟️ **Vouchers & Promotions** | System/seller vouchers, combo deals, add-on deals, and campaign-based discounts |
| 🪙 **Loyalty Coins** | Daily check-in rewards + earn coins on purchases, redeem for discounts |
| 🚚 **GHN Shipping** | Real-time shipping fee calculation, order creation, and live tracking |
| 💳 **PayOS Payment** | Seamless integrated online payment gateway |
| ⭐ **Reviews & Ratings** | Photo/video reviews with seller response support |
| 🔄 **RMA / Dispute** | Full return, refund, and dispute resolution workflow |

### 🏪 Seller — Mini-ERP Dashboard

| Feature | Description |
|:--------|:------------|
| 📋 **Purchase Orders** | Full PO lifecycle: create → approve → receive → track from overseas suppliers |
| 📦 **Inventory Management** | Real-time stock levels, movement logs, and low-stock alerts |
| 🧮 **Landed Cost Calculator** | Compute total import cost including freight, duties, VAT, and other fees |
| 📊 **Finance & Reports** | Revenue charts, commission tracking, payout requests with Recharts visualizations |
| 📢 **Campaign Management** | Create and manage flash sale campaigns with product enrollment |
| 🎫 **Voucher Campaigns** | Schedule automated voucher distribution to targeted buyers |
| 🎨 **Shop Decoration** | Custom storefront banner layouts and branding |
| 📺 **Livestream Studio** | Host live shopping events with real-time product showcase |
| 📁 **Bulk Upload** | CSV/Excel mass product import with variant support |
| 🎁 **Deals & Combos** | Configure add-on product deals and bundle combo pricing |

### 🛡️ Admin Panel

| Feature | Description |
|:--------|:------------|
| 👥 **User & Seller Management** | Approve seller applications, suspend accounts, manage platform users |
| ⚡ **Flash Sale Oversight** | Monitor live sales, pause/stop events, issue policy violation warnings |
| 🖼️ **Banner Management** | Control homepage banners and sponsored advertisement placements |
| ⚙️ **Platform Settings** | Configure commission rates, fees, and system-wide policies |
| 📈 **System Dashboard** | Revenue analytics, user growth, and order volume statistics |
| 💱 **Exchange Rate Management** | Set real-time currency conversion rates for cross-border pricing |

---

## 🔧 Tech Stack

<table>
<tr>
<td valign="top" width="50%">

### 🖥️ Frontend

![React](https://img.shields.io/badge/React_18-61DAFB?style=flat&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![Redux](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=flat&logo=redux&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router_v6-CA4245?style=flat&logo=react-router&logoColor=white)
![Ant Design](https://img.shields.io/badge/Ant_Design-0170FE?style=flat&logo=ant-design&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap_5-7952B3?style=flat&logo=bootstrap&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat&logo=socket.io&logoColor=white)
![i18next](https://img.shields.io/badge/i18next-26A69A?style=flat&logo=i18next&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat&logo=framer&logoColor=white)
![Recharts](https://img.shields.io/badge/Recharts-22B5BF?style=flat)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=flat&logo=leaflet&logoColor=white)

</td>
<td valign="top" width="50%">

### ⚙️ Backend

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=flat&logo=google&logoColor=white)
![Groq](https://img.shields.io/badge/Groq_SDK-FF6B35?style=flat)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat&logo=cloudinary&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat&logo=json-web-tokens&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat&logo=swagger&logoColor=black)
![Puppeteer](https://img.shields.io/badge/Puppeteer-40B5A4?style=flat&logo=puppeteer&logoColor=white)
![Winston](https://img.shields.io/badge/Winston_Logger-231F20?style=flat)

</td>
</tr>
</table>

---

## 📦 Repositories

<table>
<tr>
<td align="center" width="50%">
<h3>🖥️ Frontend</h3>
<a href="https://github.com/GZMart/GZMart_FE">
<img src="https://img.shields.io/badge/GZMart__FE-View_Repo-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="Frontend Repo"/>
</a>
<p>React 18 · Vite · Redux Toolkit · Ant Design · Socket.io</p>
</td>
<td align="center" width="50%">
<h3>⚙️ Backend</h3>
<a href="https://github.com/GZMart/GZMart_BE">
<img src="https://img.shields.io/badge/GZMart__BE-View_Repo-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Backend Repo"/>
</a>
<p>Node.js · Express · MongoDB · Redis · Gemini AI</p>
</td>
</tr>
</table>

---

## 🚀 Quick Start

<details>
<summary><b>⚙️ Backend Setup</b></summary>

```bash
# 1. Clone the repository
git clone <backend-repo-url>
cd GZMart_BE

# 2. Install dependencies
npm install

# 3. Configure environment
cp .env.example .env
# → Fill in: MongoDB URI, JWT secrets, Cloudinary, GHN, PayOS, Gemini AI keys...

# 4. Run development server
npm run dev
# ✅ API running at http://localhost:3000
# 📚 Swagger docs at http://localhost:3000/api-docs
```

</details>

<details>
<summary><b>🖥️ Frontend Setup</b></summary>

```bash
# 1. Clone the repository
git clone <frontend-repo-url>
cd GZMart_FE

# 2. Install dependencies
npm install

# 3. Configure environment
cp .env.example .env
# → Fill in: VITE_API_URL, Goong Maps key, LiveKit URL...

# 4. Run development server
npm run dev
# ✅ App running at http://localhost:5173
```

</details>

> **Prerequisites:** Node.js ≥ 18.0.0 · npm ≥ 9.0.0 · MongoDB Atlas · Redis

---

## 👥 Contributors

<table align="center">
  <tr>
    <td align="center">
      <a href="https://github.com/Nomsociuu">
        <img src="https://github.com/Nomsociuu.png" width="80" height="80" style="border-radius:50%" alt="Huynh Dinh Thien"/><br/>
        <b>Huynh Dinh Thien</b><br/>
        <sub><code>@Nomsociuu</code></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/hofang42">
        <img src="https://github.com/hofang42.png" width="80" height="80" style="border-radius:50%" alt="Phan Le Thanh Hoang"/><br/>
        <b>Phan Le Thanh Hoang</b><br/>
        <sub><code>@hofang42</code></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/BaoAnNguyen1903">
        <img src="https://github.com/BaoAnNguyen1903.png" width="80" height="80" style="border-radius:50%" alt="Nguyen Dinh Bao An"/><br/>
        <b>Nguyen Dinh Bao An</b><br/>
        <sub><code>@BaoAnNguyen1903</code></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/justduck25">
        <img src="https://github.com/justduck25.png" width="80" height="80" style="border-radius:50%" alt="Nguyen Doan Trong Duc"/><br/>
        <b>Nguyen Doan Trong Duc</b><br/>
        <sub><code>@justduck25</code></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/dikay2104">
        <img src="https://github.com/dikay2104.png" width="80" height="80" style="border-radius:50%" alt="Pham Duy Khanh"/><br/>
        <b>Pham Duy Khanh</b><br/>
        <sub><code>@dikay2104</code></sub>
      </a>
    </td>
  </tr>
</table>

---

<div align="center">
  <sub>🎓 <strong>GZMart</strong> · SEP490 Capstone Project · FPT University · 2025</sub><br/>
  <sub>Built with ❤️ by the GZMart Team</sub>
</div>