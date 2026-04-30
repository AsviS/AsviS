<div align="center">

<a href="https://github.com/AsviS">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=2800&pause=900&color=00C2FF&center=true&vCenter=true&width=620&lines=Hi+there%2C+I'm+Ihor+%F0%9F%91%8B;Backend+Developer+;Node.js+%2F+TypeScript+%2F+PHP;Building+backend+systems" alt="Typing SVG" />
</a>

### Backend Developer · Node.js / TypeScript / PHP

🌍 Ukraine · 💻 Open for Remote Work

![Profile views](https://komarev.com/ghpvc/?username=AsviS&color=00C2FF&style=flat-square&label=Profile+views)

</div>

---

## 👨‍💻 About Me

I’m a backend developer with hands-on experience in designing, building, and maintaining backend systems, RESTful APIs, and third-party integrations.

- 🛠 Specialize in backend development using **Node.js** and **TypeScript**, building **API**s with **Express.js** and **Strapi**, and working with **PHP**-based systems.
- 💳 Hands-on with **payment gateway integrations** — Stripe, Primer.io, OPPWA, CatalystPay, eMerchantPay
- 🗄 Experienced with **PostgreSQL, MySQL,** and **MongoDB**; designed and optimized data models and queries. Worked with **TypeORM** for data access layer. Implemented background processing using **Redis** and **BullMQ** queues.
- 🚀 Building production-grade open-source pet projects on **NestJS + TypeScript** in my spare time
- 🌱 Currently exploring **NestJS**, Docker, **Kubernetes**, microservices architecture, **Laravel** and OOP patterns

---

## 🛠 Tech Stack

#### Languages
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PHP](https://img.shields.io/badge/-PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

#### Backend Frameworks & Runtimes
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express&logoColor=white)
![NestJS](https://img.shields.io/badge/-NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Strapi](https://img.shields.io/badge/-Strapi-4945FF?style=flat-square&logo=strapi&logoColor=white)
![Laravel](https://img.shields.io/badge/-Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)

#### Databases & ORM
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![TypeORM](https://img.shields.io/badge/-TypeORM-FE0902?style=flat-square&logo=typeorm&logoColor=white)

#### Queues, Caching & DevOps
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![BullMQ](https://img.shields.io/badge/-BullMQ-FF6B35?style=flat-square)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Nginx](https://img.shields.io/badge/-Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![PM2](https://img.shields.io/badge/-PM2-2B037A?style=flat-square&logo=pm2&logoColor=white)
![Cloudflare](https://img.shields.io/badge/-Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)

#### Integrations & Tools
![Stripe](https://img.shields.io/badge/-Stripe-008CDD?style=flat-square&logo=stripe&logoColor=white)
![REST API](https://img.shields.io/badge/-REST%20API-009688?style=flat-square)
![Postmark](https://img.shields.io/badge/-Postmark-FFCC00?style=flat-square&logo=postmark&logoColor=black)
![Telegram Bot](https://img.shields.io/badge/-Telegram%20Bot%20API-26A5E4?style=flat-square&logo=telegram&logoColor=white)
![Puppeteer](https://img.shields.io/badge/-Puppeteer-40B5A4?style=flat-square&logo=puppeteer&logoColor=white)
![Jest](https://img.shields.io/badge/-Jest-C21325?style=flat-square&logo=jest&logoColor=white)

---

## 🚀 Featured Projects

### 🔍 [XP Metal Detectors Firmware Bot](https://github.com/AsviS/xpmetaldetectors-tg-bot)

> A **production-ready Telegram bot** built for the XP Metal Detectors community to deliver real-time firmware update notifications.

**Stack:** `NestJS 11` · `TypeScript` · `grammY` · `PostgreSQL + TypeORM` · `Redis + BullMQ` · `Docker` · `Pino` · `Jest`

- Modular NestJS architecture (bot · database · xp-api · queue · scheduler · common)
- Async notification pipeline on **BullMQ + Redis** with dedicated processors
- Cron-scheduled firmware checks via `@nestjs/schedule` integrated with the official XP API
- Multilingual support for **8 languages** (`@grammyjs/i18n` + Fluent)
- RBAC via NestJS guards · admin broadcasts · API account management
- Security: API token rotation, encrypted credentials, graceful error handling

---

### 🤖 [Theresanaiforthat Scraper](https://github.com/AsviS/theresanaiforthat-scraper)

> A **multi-phase web scraper** that collects structured data on AI tools from theresanaiforthat.com.

**Stack:** `Node.js` · `Puppeteer` · `Puppeteer Extra (Stealth Plugin)` · `Winston` · `Dotenv`

- Three-phase pipeline: link collection → tool detail extraction → category tree
- Anti-detection: User-Agent rotation, randomized delays, viewport randomization, stealth plugin
- Recursive category-tree traversal with both flat-list and hierarchical JSON output
- Centralized Winston logging with environment-driven configuration
- Detailed JSON schema (features, pricing, modalities, releases, FAQ, pros/cons)

---

### ⚽ Sports Data Parser & Prediction System

> A real-time scraper that collects football match data and delivers automated predictions to a Telegram channel.

**Stack:** `Node.js` · `Puppeteer` · `MySQL` · `Telegraf.js`

- Real-time data collection from soccerstand.com / flashscore.ua
- Automated football match prediction pipeline with Telegram delivery
- MySQL schema for historical match data and prediction results

---

## 🤝 Let's Connect

<div align="center">

[![Telegram](https://img.shields.io/badge/-Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/asv1s)
[![Email](https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:xenkokk@gmail.com)
[![X / Twitter](https://img.shields.io/badge/-X%20(Twitter)-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/IhorDziuba)

</div>

---

<div align="center">
  😉
</div>
