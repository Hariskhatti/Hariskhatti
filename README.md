<!-- ═══════════════ HEADER ═══════════════ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=230&section=header&text=Haris%20Khatti&fontSize=64&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Java%20Backend%20Developer%20%7C%20Spring%20Boot%20%7C%20AI%20%2B%20Cloud%20%7C%20CI%2FCD&descAlignY=58&descSize=18" width="100%"/>
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=38BDF8&center=true&vCenter=true&width=720&lines=Building+secure+%26+scalable+REST+APIs;Spring+Boot+%7C+PostgreSQL+%7C+Docker+%7C+JWT;AI-powered+backends+with+Groq+LLMs;Shipping+with+GitHub+Actions+CI%2FCD;Open+to+backend+developer+roles+%F0%9F%9A%80" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=haris-khatti&label=Profile%20Views&color=0e75b6&style=flat-square" />
  <img src="https://img.shields.io/badge/Status-Open%20to%20Work-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/Location-Pakistan%20🇵🇰-01411C?style=flat-square" />
</p>

<p align="center">
  <a href="mailto:hariskhatti.dev@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/haris-khatti-a97526208/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://hariskhatti.netlify.app/"><img src="https://img.shields.io/badge/Portfolio-0f172a?style=for-the-badge&logo=netlify&logoColor=00C7B7"/></a>
</p>

---

## 🧭 About Me

I'm a **Java Backend Developer** who builds **secure, scalable, production-style backend systems** with **Java 21, Spring Boot and PostgreSQL**.

I don't stop at CRUD. I care about the parts that make a backend real:

- 🔐 **Authentication & authorization** — JWT, role-based access, email-based 2FA, token rotation
- 🏗️ **Clean layered architecture** — controllers → services → repositories, centralized exception handling
- 🗄️ **Database design & migrations** — PostgreSQL, Flyway versioned migrations, constraints & uniqueness rules
- 🤖 **AI integration** — LLM-powered features using **Groq** (`gpt-oss-120b`) behind secure backend APIs
- 🐳 **Containerization** — Docker & Docker Compose for backend + admin panel + database
- ⚙️ **CI/CD** — automated build, test and Docker image pipelines with **GitHub Actions**
- 🧪 **Testing** — JUnit 5 + Mockito

> 💡 I like understanding *why* something is built a certain way, not just *how*.

---

## 💼 Experience

<table>
<tr>
<td width="50%" valign="top">

### 🏥 Junior Java Backend Developer
**Softsincs** · `05 Jul 2026 – 02 Nov 2026`

Built the backend of **MediMentor** — an AI-powered clinical decision support platform for doctors in Pakistan — plus its **React admin panel** and a **React Native mobile app** (built with AI-assisted tooling).

</td>
<td width="50%" valign="top">

### 🚛 Backend Intern
**Novasinc** · `01 May 2026 – 02 Jun 2026`

Worked on **TruckFlow Pro**, a logistics & fleet management platform for Saudi Arabia, and introduced **Flyway database migrations** for versioned, repeatable schema changes.

</td>
</tr>
</table>

---

## 🚀 Featured Projects

### 🏥 MediMentor — AI-Powered Clinical Decision Support *(Softsincs)*

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-4.0.6-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Java](https://img.shields.io/badge/Java-21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-17-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![JWT](https://img.shields.io/badge/Auth-JWT-000000?style=flat-square&logo=jsonwebtokens)
![Groq](https://img.shields.io/badge/AI-Groq%20gpt--oss--120b-F55036?style=flat-square)
![React](https://img.shields.io/badge/Admin-React%2018%20%2B%20Vite-61DAFB?style=flat-square&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/Mobile-React%20Native%20%2B%20Expo-000020?style=flat-square&logo=expo&logoColor=white)
![Tests](https://img.shields.io/badge/Tests-JUnit%205%20%2B%20Mockito-25A162?style=flat-square&logo=junit5&logoColor=white)

A three-part system: **Spring Boot backend API**, **React admin dashboard**, and a **React Native mobile app**.

**Backend highlights**
- 🔐 JWT auth with **admin email 2FA** (6-digit code, 60-second resend cooldown) and forced password change for temporary-password admins
- 🩺 **Doctor verification flow** — PM&DC number checks, duplicate-claim detection, approve / reject (with reason codes) / revoke
- 💬 **Patient & AI chat flow** powered by Groq LLM
- 📄 **Private patient document handling** with secure access
- 🩸 **Blood donor** and ⚡ **Quick Check** modules
- 📞 Phone-number uniqueness rules + centralized, consistent **exception handling** and response format
- 📧 Email features (2FA codes, notifications)
- 🧾 **Audit trail** of admin actions, exportable as CSV
- 🧪 Unit tests with **JUnit 5 + Mockito**

**Admin panel** — React 18 · Vite · React Router · Axios · lucide-react: dashboard stats, verification queue, doctor directory, user suspend/reactivate, admin management, audit logs.

**Mobile app** — Expo SDK 57 · React Native 0.86 · React 19 · TypeScript · React Navigation 7 · Zustand 5 *(built with AI tools)*.

```mermaid
flowchart LR
    A[📱 React Native App] -->|REST + JWT| C
    B[🖥️ React Admin Panel] -->|REST + JWT + 2FA| C
    C[☕ Spring Boot API] --> D[(🐘 PostgreSQL 17)]
    C -->|LLM calls| E[🤖 Groq gpt-oss-120b]
    C --> F[📧 Email Service]
    G[🐳 Docker Compose] -.->|runs| C
    G -.-> D
    G -.-> B
```

> 🔒 *MediMentor is a private company project (Softsincs), so the source code isn't public.*

---

### 🚛 TruckFlow Pro — Logistics & Fleet Management *(Novasinc)*

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-Migrations-CC0200?style=flat-square&logo=flyway&logoColor=white)
![Database](https://img.shields.io/badge/Relational-Database-336791?style=flat-square&logo=postgresql&logoColor=white)

A logistics and fleet management platform for the **Saudi Arabian** market. I added **Flyway-based database migrations** so schema changes are versioned, repeatable and safe across environments.

---

### 🧩 More on my profile

- 🔐 **Role-Based Authentication & Authorization** — JWT-secured REST APIs
- 🔄 **Token Rotation & Refresh Token Handling** — production-style session management
- ☁️ **Cloudinary Media Management** — image/file upload and cloud storage
- 🤖 **AI Integration** — LLM-enhanced backend services
- 🐳 **Dockerized Spring Boot apps** with PostgreSQL / MongoDB

👉 *Explore my repositories for more implementations.*

---

## 🛠️ Tech Stack

### ☕ Backend
![Java](https://img.shields.io/badge/-Java%2021-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/-Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![Hibernate](https://img.shields.io/badge/-Hibernate%20%2F%20JPA-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![JWT](https://img.shields.io/badge/-JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![REST](https://img.shields.io/badge/-REST%20APIs-0ea5e9?style=for-the-badge)
![Servlets](https://img.shields.io/badge/-Servlets%20%26%20JSP-f97316?style=for-the-badge)
![JDBC](https://img.shields.io/badge/-JDBC-dc2626?style=for-the-badge)

### 🗄️ Databases & Migrations
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Flyway](https://img.shields.io/badge/-Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white)

### 🤖 AI / LLM
![Groq](https://img.shields.io/badge/-Groq-F55036?style=for-the-badge)
![gpt-oss](https://img.shields.io/badge/-gpt--oss--120b-7c3aed?style=for-the-badge)
![Prompt Engineering](https://img.shields.io/badge/-LLM%20Integration-0ea5e9?style=for-the-badge)

### ⚙️ DevOps & CI/CD
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/-Docker%20Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/-Git%20%26%20GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

### 🧪 Testing & Tools
![JUnit](https://img.shields.io/badge/-JUnit%205-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/-Mockito-78A641?style=for-the-badge)
![Postman](https://img.shields.io/badge/-Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![IntelliJ](https://img.shields.io/badge/-IntelliJ%20IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white)

### 🎨 Frontend & Mobile
![React](https://img.shields.io/badge/-React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/-Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![React Native](https://img.shields.io/badge/-React%20Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/-Expo-000020?style=for-the-badge&logo=expo&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Zustand](https://img.shields.io/badge/-Zustand-433e38?style=for-the-badge)
![Axios](https://img.shields.io/badge/-Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Thymeleaf](https://img.shields.io/badge/-Thymeleaf-005F0F?style=for-the-badge&logo=thymeleaf&logoColor=white)

---

## ⚙️ CI/CD Pipeline I Use

```mermaid
flowchart LR
    A[💻 Push / Pull Request] --> B[🔨 Build<br/>Maven + Java 21]
    B --> C[🧪 Test<br/>JUnit 5 + Mockito]
    C --> D[🐳 Build Docker Image]
    D --> E[📦 Push to Registry]
    E --> F[🚀 Deploy<br/>Docker Compose]
```

<details>
<summary>📄 Example GitHub Actions workflow (Spring Boot)</summary>

```yaml
name: CI

on:
  push:
    branches: [main]
  pull_request:

jobs:
  build-and-test:
    runs-on: ubuntu-latest
    services:
      postgres:
        image: postgres:17
        env:
          POSTGRES_DB: testdb
          POSTGRES_USER: test
          POSTGRES_PASSWORD: test
        ports: ["5432:5432"]
    steps:
      - uses: actions/checkout@v4
      - uses: actions/setup-java@v4
        with:
          distribution: temurin
          java-version: 21
          cache: maven
      - name: Build & test
        run: mvn -B verify
      - name: Build Docker image
        run: docker build -t app:${{ github.sha }} .
```

</details>

---

## 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=haris-khatti&show_icons=true&theme=radical&hide_border=true&count_private=true" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=haris-khatti&layout=compact&theme=radical&hide_border=true" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=haris-khatti&theme=radical&hide_border=true" height="170"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=haris-khatti&theme=react-dark&hide_border=true&area=true" width="95%"/>
</p>

---

## 🎯 Currently

- 🔭 Deepening **CI/CD** with GitHub Actions (build → test → Docker → deploy)
- 🤖 Building more **LLM-powered backend features** (Groq, prompt design, safe AI responses)
- ☁️ Cloud media management & secure token handling
- 📐 Studying **system design** — scalability, caching, and API security

---

<p align="center">
  ⭐ <b>Open to Java Backend Developer roles</b> where I can learn, contribute and grow.<br/>
  📫 Let's connect — <a href="mailto:hariskhatti.dev@gmail.com">hariskhatti.dev@gmail.com</a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,100:0f2027&height=120&section=footer" width="100%"/>
</p>
