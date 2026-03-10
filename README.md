[README.md](https://github.com/user-attachments/files/25865603/README.md)
# Kailo.KZ — GLP-1 Patches Landing Page

> Official landing page for **Kailo.KZ** — premium GLP-1 weight management patches available across Kazakhstan.

---

## 🌐 Live Website

👉 [View Website](https://kailokz93-maker.github.io/Kailo-Kz/)

---

## 📋 About

Kailo.KZ is a wellness brand offering GLP-1 transdermal patches developed in partnership with **Kraein Netura™**. This landing page is designed to inform customers and collect orders directly, with instant delivery to a Google Sheet and WhatsApp follow-up.

---

## ✨ Features

- Fully responsive design (mobile + desktop)
- Order form connected to Google Sheets (real-time submissions)
- WhatsApp direct contact button
- Smooth scroll animations
- Product showcase & customer testimonials
- Delivery available across all of Kazakhstan

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 / CSS3 | Structure & styling |
| Vanilla JavaScript | Form handling & animations |
| Google Apps Script | Form → Google Sheets integration |
| GitHub Pages | Free hosting |

---

## 📦 Order Form Fields

When a customer submits the form, the following data is sent to Google Sheets:

- Timestamp
- First Name
- Last Name
- Phone Number
- City / Delivery Address
- Quantity selected
- Source (Kailo.KZ Landing Page)

---

## 🔧 Setup & Configuration

### 1. Google Sheets Integration
The form submits data to Google Sheets via a Google Apps Script Web App.
To configure your own:
1. Create a Google Sheet with headers: `Timestamp, First Name, Last Name, Phone, Address, Quantity, Source`
2. Go to **Extensions → Apps Script** and deploy as a **Web App**
3. Replace the `SHEET_URL` in the HTML file with your script URL

### 2. WhatsApp Number
The WhatsApp contact button links to `+7 771 193 6931`. Update the `wa.me` links in the HTML to change it.

---

## 📁 File Structure

```
kailo-kz/
│
├── index.html        # Main landing page (all-in-one)
└── README.md         # This file
```

---

## 📬 Contact

For business inquiries or support:

- 💬 WhatsApp: [+7 771 193 6931](https://wa.me/77711936931)

---

© 2026 Kailo.KZ — Kazakhstan. All rights reserved.
