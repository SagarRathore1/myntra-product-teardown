# 🛍️ Myntra Product Teardown & UX Optimization | Vistaar Ventures

> **Problem Statement:** How might we convert browse-and-wishlist users into first-time buyers by reducing checkout friction?

---

## 📌 Executive Summary
This project analyzes **Myntra's product experience** with a focused deep dive into **cart/wishlist abandonment**, **checkout friction**, and **pricing trust issues**. Based on primary research ($n=50$) and extensive secondary research (Reddit, App Store reviews), we proposed actionable feature additions (**24-Hour Price Lock** & **Transparent Pricing**) and validated their prospective impact on North Star Metrics.

* **Team:** Vistaar Ventures (Sagar, Sourav, Priya)
* **Deck Link:** https://drive.google.com/file/d/1n3d3EnekNRF3nysQCz5icgO5-KM_emIK/view?usp=sharing
* **Live Demo Prototype (Web):** https://attached-assets--sourav23248.replit.app/
* **App PRD & Prototype:** Accessible via Expo Go / Replit

---

## 🎯 Key Findings & User Insights
* **Primary Cause of Wishlisting:** **48%** of users wishlist items strictly as a price-watch tool, while **52%** of hesitations stem from unexpected price hikes or stock anxiety.
* **Checkout Drop-Off:** The #1 reason for cart abandonment is **surprise/hidden platform & convenience fees** (₹20–₹200) added at the final step.
* **Return Fear:** Users avoid initial orders due to high-return penalties and non-refundable convenience fees.

---

## 🚀 Key Proposed Solutions

| Solution | Concept | Core Benefit |
| :--- | :--- | :--- |
| **24-Hour Price Lock** | Freezes wishlist discounts for 24 hours with a countdown timer | Eliminates price hike anxiety & creates immediate purchase urgency. |
| **Transparent Pricing** | Displays all fees (platform + delivery) upfront on the Product Detail Page (PDP) | Prevents last-minute price shock at the checkout screen. |
| **Risk-Aware Returns** | Waives penalties for size mismatches; defaults refunds to original payment method | Rebuilds trust for first-time buyers. |

---

## 📊 Key Metrics & Impact (Guesstimate)

* **North Star Metric (NSM):** **Gross Merchandise Value (GMV) per Active User**
* **First-Purchase Activation Rate:** Projected growth from **5.0% ➔ 7.0%** (+2.0% Absolute Delta)
* **Wishlist-to-Cart Graduation Rate:** Projected growth from **12.0% ➔ 15.0%** (+3.0% Absolute Delta)
* **Net GMV per Active User:** Projected increase from **₹58.46 ➔ ₹74.59** (+₹16.13/user)

---

## 🛠️ MVP Prototype Tech Stack
* **Framework:** React + Vite
* **Styling:** Tailwind CSS (Responsive, Desktop-first)
* **Icons:** Lucide React Icons
* **State Management:** React Native State (`useState`, `useEffect`)

---

## 📁 Repository Structure

```text
├── docs/
│   ├── Myntra_Product_Teardown_Vistaar_Ventures.pdf
│   ├── PRD_App_Version.md
│   └── PRD_Web_Version.md
├── src/
│   ├── components/       # Header, PriceCard, Countdown, Tooltip
│   ├── pages/            # ProductPage, WishlistPage, CheckoutPage
│   ├── data/             # Mock Product Data
│   └── utils/            # Timer & logic utilities
├── README.md
└── package.json
