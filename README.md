# 👨‍💻 Nick (Yiming) Zheng

**Tech Leader · Full-Stack TypeScript Developer · DevOps / Platform Engineering**

- 📧 **Email:** nickzhengyiming@gmail.com  
- 📱 **Phone:** +86 189 189 60666  

---

## 🚀 Summary

- **12+ years** of hands-on experience in **Full-Stack JavaScript** development and **DevOps / Platform Engineering**.
- Deep expertise in modern JS stack: **React / Next.js / Node.js (NestJS)**, delivering **Web Apps**, **WeChat Mini Programs**, and production-grade services.
- Strong focus on **reliability & delivery efficiency**: **CI/CD**, Git workflow, Kubernetes orchestration, and automated quality gates.
- Solid testing practices across frontend & backend: **unit / integration / e2e**, ensuring high quality and stable releases.
- **6 years** of people management experience (**8–15 engineers**): hiring, team structuring, task allocation, mentoring, and performance coaching.

---

## 🎓 Education

- **Master of Computing and IT**, Northumbria University (UK) — *2012.01 – 2013.06*  
- **Bachelor of Communication Engineering**, Shanghai Dianji University (China) — *2007.09 – 2011.06*

---

## 🧰 Tech Stack

### 🖥️ Frontend (React Ecosystem)

- **React** (since 2015): `createClass` → ES6 Class Components / Pure Components → Functional Components / Hooks  
- **State management**: Redux (Saga/Thunk) → Context + custom hooks → **Redux Toolkit / DVA / Zustand / React Query / ahooks**
- **Framework**: **Next.js**
- **UI & Forms**: **Ant Design / Ant Design Pro / React Hook Form**
- Legacy: Angular 1.x

### ⚙️ Backend (Node.js)

- **Frameworks**: Express → Koa → Ali Egg.js → **NestJS** (AOP & DI)
- **API**: **RESTful**, **Swagger / OpenAPI**
- **ORM**: **TypeORM**
- **Storage**: PostgreSQL / Redis

### ☁️ DevOps / Cloud / Platform

- **Cloud**: AWS / Alibaba Cloud / Azure
- **CI/CD**: GitHub Actions / GitLab Pipelines / Jenkins (pre-2018)
- **Deployment**
  - Frontend: **S3 + CDN**, **Cloudflare Pages**
  - Backend: **Kubernetes (Helm)** / ECS Fargate / **Serverless** (Lambda / Alibaba Cloud Function)
- **Observability**: Sentry (Errors / Tracing / APM / Logs / Metrics)
- **RUM**: Alibaba Cloud Real User Monitoring (Frontend)

### 🧪 Tooling & Testing

- **Code quality**: ESLint / Prettier → **Biome**
- **Git hooks**: Husky + lint-staged (pre-commit / pre-push)
- **Frontend testing**: React Testing Library / Jest / Cypress
- **Backend testing**: Supertest / @nestjs/testing
- Legacy (2013–2015): Jasmine / Karma / Protractor / Grunt / Gulp / RequireJS

---

## 💼 Experience & Selected Projects

### 🎵 ACE Studio AI (ongoing)

- 🌐 **Web:** https://web-dev.acemusic.ai

---

### 🎓 CampusGPT (since 2023)

- 🌐 **Chatbox:** https://chat.campus-gpt.com/

**Tech Stack**
- Frontend: React + Zustand + Tailwind + Ant Design  
- Backend: NestJS + TypeORM  
- Infrastructure: AWS → Alibaba Cloud, ECS (Fargate) → Alibaba Cloud Function (Serverless)  
- Gateway: Cloudflare AI Gateway  

---

### 🧩 Yara

**Tech & Highlights**
- Built WeChat Mini Program using **Taro (React)** with standardized UI component patterns and delivery workflow
- Backend services built with **NestJS** **TypeORM**
- Established an **OpenAPI-based client generation** workflow to produce TypeScript Axios clients + typings
- Operated on **Alibaba Cloud ACK (Kubernetes)** and implemented Kubernetes-based deployment automation
- Enabled faster iteration with **Review Apps** (GitLab Review Apps) across environments

---

### 🏢 EY (Ernst & Young)

#### React Hooks Enablement & Frontend Engineering Practices
- Drove team-wide React Hooks best practices: patterns, review checklist, and shared examples
- Extracted shared logic into reusable **custom hooks** to reduce duplication and improve readability
- EImproved data-flow clarity by reducing ad-hoc `useEffect` usage and enforcing predictable abstractions
- Reduced scattered `useEffect` usage with clearer abstractions and predictable data flow

#### EY Blockchain China Hosting & Compliance
- Azure (Azure CN) China hosting
- Introduced Helm to template and standardize deployments
- Moved region- and customer-specific differences into Helm values files
- Designed CI/CD workflows to meet China region constraints and compliance requirements

```chat
┌──────────────────────────┐
│   Environment US/China │  ← values-cn.yaml / values-us.yaml
└────────────▲─────────────┘
             │
┌────────────┴─────────────┐
│     Helm Values Layer    │  ← image, resources, ingress, replicas
└────────────▲─────────────┘
             │
┌────────────┴─────────────┐
│     Helm Templates       │  ← deployment / service / ingress
└────────────▲─────────────┘
             │
┌────────────┴─────────────┐
│       Kubernetes         │
└──────────────────────────┘

```

- Replaced **Auth0** with **Authing** for authentication and user management
- Localization implemented via **Git flow**

#### Express → NestJS Migration
- Led services migration from **pure Express**  to **NestJS**
- Standardized **authentication**, **validation**, **logging**, and **error handling** in **NextJS**
- Set up **OpenAPI-driven TypeScript client generation** to align FE/BE contracts

#### Blockchain On-chain Public Service
- Built a reusable on-chain public service layer to unify blockchain write/read operations
- Consolidated repeated **ethers.js** integration logic into a standardized shared micro-service

---

## 🌱 Early Career

### University (Self-taught)
- Ruby on Rails
- PHP (Yii Framework)

### HSBC
- Adobe Flex / ActionScript → HTML5 / Angular 1.x
- RequireJS / Grunt / Karma / Jasmine
- TeamCity / Jira Agile

### React & Tooling (2015)
- JSX, component model, Flux / Reflux
- Webpack, Babel

### Node.js & Infra
- Express / Koa / Egg.js
- Docker / Kubernetes
