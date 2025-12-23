# Guvohnoma Verification Portal

Hujjatlarni tekshirish portali - repository.gov.uz ga o'xshash.

## Features

- PIN-kod orqali hujjatni himoyalash
- To'g'ri PIN kiritilganda PDF avtomatik yuklanadi
- Ko'rinish repository.gov.uz ga mos

## PIN-kod

Hujjatni ochish uchun PIN-kod: **8362**

## Local Development

```bash
npm install
npm start
```

Server `http://localhost:3000` da ochiladi.

## Deploy to Render

1. GitHub ga push qiling
2. [Render Dashboard](https://dashboard.render.com/) ga kiring
3. "New" -> "Web Service" tanlang
4. GitHub repo ni ulang
5. Render avtomatik `render.yaml` ni o'qib, deploy qiladi

## Files

- `index.html` - Asosiy PIN verification sahifa
- `guvohnoma.html` - Asl guvohnoma hujjati
- `server.js` - Express server
- `render.yaml` - Render deploy config

## Tech Stack

- HTML5, CSS3, JavaScript
- Express.js (server)
- html2pdf.js (PDF generation)
