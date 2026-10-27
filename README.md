<div align="center">

# Hossein Abdollahi
### Full-Stack Developer · TypeScript · NestJS · React · AI Integration

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohammadhossein-abdollahi-155a79224/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/mha13)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:mohammadhosseinabdollahi1376@gmail.com)
![Location](https://img.shields.io/badge/📍_Torino_·_Milano,_Italy-grey?style=flat-square)

</div>

---

## 👋 About Me

Full-stack developer based in **Italy** with 4+ years of experience building production platforms across Iran, Spain and Italy.

Today I build **backend integrations and portals in TypeScript**: NestJS APIs, PostgreSQL data models, multi-tenant security, CRM integrations and React frontends, all shipped with Docker.

I also have a background in **law**, with a focus on AI regulation (EU AI Act), so I care about privacy, security and responsible AI in the software I build.

What I do best:
- ⚙️ **Backend engineering** — NestJS, Node.js, REST APIs, PostgreSQL / MySQL, TypeORM migrations, queues (Redis + BullMQ)
- 🔗 **Integrations** — CRM REST APIs (vTiger), sync with retry, document upload, idempotency
- 🔐 **Secure by design** — JWT in httpOnly cookies, tenant isolation, one-time tokens, rate limiting, GDPR-aware logging
- 🎨 **Frontend** — React, TypeScript, Vite, TanStack Query, react-hook-form + zod, Tailwind, shadcn/ui
- 🤖 **AI integration** — OpenAI API, chatbots with human escalation, Firebase real-time systems
- 🧩 **WordPress & e-commerce** — custom PHP/JS plugins, WooCommerce, Shopify

---

## 🚀 Featured Work

### Colloquia Connector — Customer Portal & CRM Integration *(private · work project)*

> Multi-tenant platform that lets companies and hospitals request **translation, face-to-face and video interpreting** services. Requests and documents are synced into the company's **vTiger CRM**.

```
React portal (Vite SPA) ──HTTPS + cookie──▶ NestJS API ──REST──▶ vTiger CRM
                                             │       │
                                        PostgreSQL  Local / object storage
```

**Stack:** `TypeScript` `NestJS` `PostgreSQL` `TypeORM` `React` `Vite` `TanStack Query` `Docker` `Caddy` `Jest` `Vitest`

- ✅ **Plugin architecture** — one common request engine; each service type plugs in as a handler
- ✅ **"Database first, CRM second"** sync — no request is lost if the CRM is slow or down; safe admin retry without duplicates
- ✅ **Tenant isolation** — tenant always taken from the session, never from the request body
- ✅ **Portal accounts** activated from CRM contacts — hashed one-time tokens, httpOnly cookie session, CSRF origin check
- ✅ **Documents** pushed to the CRM with neutral file names; picklists read live from the CRM (never hardcoded)
- ✅ Unit + integration tests on real PostgreSQL, CI checks, Docker Compose deployment

### [hi-chat-assistenza](https://github.com/mha13/hi-chat-assistenza) — AI WordPress Chatbot Plugin

> Production WordPress plugin that uses **OpenAI GPT** for first-level support, with live **human-operator escalation**.

```
OpenAI API  ──►  WordPress Plugin  ──►  Firebase Realtime DB
                      │                       │
                 Admin Dashboard  ◄────  Operator Chat UI
```

**Stack:** `PHP` `JavaScript` `OpenAI API` `Firebase` `MySQL` `WordPress`

- ✅ Real-time messaging with Firebase Realtime Database
- ✅ Secure authentication with Firebase Auth
- ✅ Admin dashboard to monitor, intervene and configure
- ✅ Modular architecture, easy to extend

---

## 🛠️ Tech Stack

### Backend
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwind-css&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)

### Databases & Messaging
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

### DevOps & Testing
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Caddy](https://img.shields.io/badge/Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

### Platforms & Tools
![WordPress](https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white)
![WooCommerce](https://img.shields.io/badge/WooCommerce-96588A?style=flat-square&logo=woocommerce&logoColor=white)
![Shopify](https://img.shields.io/badge/Shopify-96BF48?style=flat-square&logo=shopify&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)

### Currently Learning 🔥
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Cybersecurity](https://img.shields.io/badge/Cybersecurity-222222?style=flat-square&logo=letsencrypt&logoColor=white)

---

## 📂 Other Projects

| Project | Description | Stack |
|---|---|---|
| **Camar** | Dynamic PDF generation & merging system with admin dashboard | PHP · TCPDF · ACF · MySQL · WordPress |
| **M2Smart** | IoT remote device control platform — reduced operational waste by 20% | React · REST API · Bootstrap |
| **Nashrenow** | Redesign for a major Iranian book publisher — 30% faster load times | WordPress · PHP · CSS |
| **CISO Online** | ISO 27001 cybersecurity platform UX — bounce rate reduced by 10% | Shopify · UI/UX |
| **Hampanah** | Medical appointment booking plugin & WordPress theme | PHP · WordPress · JS |
| **Babel Book Review** | Literary criticism platform migrated from Laravel to WordPress | Laravel · WordPress · PHP |

---

## 💼 Experience

```
🟠 Vox Gentium · Full-Stack Developer (Stage)   Sep 2026 – Present    · Milano, Italy (Hybrid)
🟢 Hidoly · Web Developer                       Mar 2026 – Present    · Torino, Italy
🔵 Proceedit Trading · Web Designer             Aug 2025 – Mar 2026   · Barcelona, Spain (Remote)
🟣 Avaat · Web Developer                        Oct 2021 – Oct 2023   · Isfahan, Iran
```

---

## 🎓 Education & Certifications

- 🎓 **LLB International / Global Studies** — Università degli Studi di Torino · thesis on AI discrimination and the EU AI Act
- 🎓 **B.Sc. Computer Engineering** — Iran
- 🌍 **Erasmus** — West University of Timișoara (2024–2025)
- 📜 **Advanced React** — Meta (2024)
- 📜 **Principles of UX/UI Design** — Meta (2024)
- 📜 **Version Control** — Meta (2024)
- 📜 **AI & Human Rights** — Council of Europe (2025)

---

## 🌍 Languages

`Persian — Native` &nbsp; `English — C1` &nbsp; `Italian — B1 → B2`

---

<div align="center">

*Open to full-stack / backend roles in Italy or remote — especially teams working with TypeScript, NestJS, React, integrations or AI.*

**📩 [mohammadhosseinabdollahi1376@gmail.com](mailto:mohammadhosseinabdollahi1376@gmail.com)**

</div>
