<div align="center">

# Hi, I'm Omar Mahmoud 👋

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=2F81F7&center=true&vCenter=true&width=640&lines=Backend+Software+Engineer;Node.js+%7C+TypeScript+%7C+NestJS+%7C+Laravel;AWS+Certified+Solutions+Architect+%E2%80%93+Associate;Payments+%E2%80%A2+Multi-tenant+SaaS+%E2%80%A2+Cloud+Media" alt="Typing SVG" /></a>

**I build and own production backends end to end — data model, REST APIs, auth, payments, infrastructure and deployment.**

📍 Muscat, Oman (GMT+4) · 🌍 Open to remote & relocation · 🗣️ Arabic · English · Turkish

<a href="https://www.linkedin.com/in/omarmahmoud00"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:omar.a.abuyoussef@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://leetcode.com/u/omarmahmoud00"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
<a href="https://aws.amazon.com/verification"><img src="https://img.shields.io/badge/AWS_Certified-Solutions_Architect_Associate-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS Certified Solutions Architect – Associate"/></a>

</div>

---

## 🧑‍💻 About me

Backend engineer with **2+ years** shipping production systems in **Node.js / TypeScript (NestJS, Prisma, PostgreSQL)** and **PHP / Laravel (MySQL, MongoDB)**.
I've built the multi-tenant core of a fintech donations SaaS, a cloud media archive serving **500,000 photos** and thousands of videos, and a search service with **50% lower latency**.

What I'm good at:

- 🔌 **API design** — clean REST contracts, consistent errors, versioning, validation
- 💳 **Payments** — Stripe & PayPal subscriptions, refunds, **idempotent, signature-verified webhooks**
- 🏢 **Multi-tenant SaaS** — row-level isolation, host-based routing, zero cross-tenant leakage
- 🔐 **Security hardening** — JWT/refresh tokens, 2FA/OTP, RBAC, PII encryption, audit trails, locked-down servers
- ☁️ **Cloud & ops** — AWS (S3, CloudFront, Rekognition, IAM), Azure Blob, Docker, CI/CD, Linux/Nginx

---

## 📈 Impact in numbers

<div align="center">

| 💰 **$800K+** | 👥 **50,000+** | 🖼️ **500,000** | ⚡ **−50%** | 📦 **5.5 TB** |
|:---:|:---:|:---:|:---:|:---:|
| donations processed on a platform I built | donors served | photos delivered worldwide via S3 + CloudFront | search query latency | media migrated to S3 |

</div>

---

## 💼 Experience

**Software Engineer — Sortera LLC** · *Mar 2025 – Present*
Arabic historical video & photo archive — two Laravel services (MySQL transactional + MongoDB search microservice)
- Cut search latency **50%** with a read-optimized MongoDB search service that keeps heavy reads off the write path
- Serve **500K photos** and thousands of videos via multi-region **S3 + CloudFront**; leading the migration to **Azure Blob Storage**
- Built face-based photo filtering across the full library with **AWS Rekognition** and background jobs
- Queued **FFmpeg** pipeline for transcoding, clipping and thumbnails, plus resumable chunked uploads
- Sanctum auth, **2FA**, RBAC and audit logging; semantic search over clips via an AI chatbot with transcript indexing; CI/CD with automated tests

**Backend Developer — FlowX** · *Oct 2025 – May 2026*
Multi-tenant fundraising fintech SaaS — **NestJS · TypeScript · Prisma · PostgreSQL**
- Built the **multi-tenant core**: row-level isolation per organization with host-based routing
- Shipped refunds, subscription billing and a WooCommerce checkout; standardized API response & error contracts
- Fixed critical security defects (leaked API keys, non-expiring JWTs) and hardened the production Docker deployment

**Backend Developer — FrameUp** · *Jun 2024 – Aug 2025*
Charity & donations platform — **Laravel · MySQL**
- Launched a platform that processed **$800K+ from 50,000+ donors** and doubled daily donation volume
- Shipped a campaign-recommendation feature that lifted donations **20%**
- **Stripe & PayPal** one-time + recurring giving with idempotent webhooks — provider retries never create duplicates
- PII encryption at rest, scoped RBAC, single-active-session rule, full audit trail, hardened VPS
- Moved CSV exports and bulk email to queued jobs processing ~1,000-row chunks

---

## 🛠️ Tech stack

**Languages**

<img src="https://skillicons.dev/icons?i=ts,js,nodejs,php,java,c,cs,html,css" alt="Languages" />

**Frameworks & ORMs** — NestJS · Express · Laravel · Prisma · Eloquent

<img src="https://skillicons.dev/icons?i=nestjs,express,laravel,prisma" alt="Frameworks" />

**Data**

<img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis" alt="Databases" />

**Cloud & DevOps**

<img src="https://skillicons.dev/icons?i=aws,azure,docker,githubactions,linux,nginx,git,github" alt="Cloud and DevOps" />

---

## 🧠 Skills

| Area | Skills |
|---|---|
| 💻 **Languages** | TypeScript · JavaScript (Node.js) · PHP · SQL · Java · C · C# · HTML · CSS |
| 🧱 **Frameworks & ORMs** | NestJS · Express · Laravel · Prisma · Eloquent |
| 🗄️ **Data** | PostgreSQL · MySQL · MongoDB · Redis · schema design · indexing · migrations · read-optimized search services |
| 🔌 **APIs** | REST API design · JSON · standardized response & error contracts · rate limiting · input validation · pagination & filtering |
| 🔐 **Auth & Security** | JWT / refresh tokens · OAuth · Laravel Sanctum · 2FA (Google Authenticator) / email OTP · session management · RBAC · PII encryption at rest · audit logging · server & firewall hardening |
| 💳 **Payments** | Stripe · PayPal · WooCommerce · Mailgun · subscriptions & recurring billing · refunds · signature-verified, idempotent webhooks · fraud scoring |
| ☁️ **Cloud** | **AWS** — S3 (CLI, Transfer Acceleration), CloudFront, Rekognition, IAM, Lambda, API Gateway, DynamoDB, Cognito, WAF · **Azure** — Blob Storage, Cosmos DB |
| ⚙️ **Infrastructure & DevOps** | Docker · CI/CD · Git · Linux · Nginx · DNS · VPS & server management · queues & background jobs · FFmpeg media pipelines |
| 🏗️ **Architecture & Practices** | Multi-tenant SaaS (row-level isolation, host-based routing) · microservices · automated testing · code review · OOP / OOD · AI-assisted development (Claude & coding agents) |
| 🗣️ **Spoken languages** | Arabic (native) · English (full professional) · Turkish (limited working) |

---

## 🚀 Featured projects

| Project | What it is | Stack |
|---|---|---|
| [**serverless-rest-api-cognito-waf**](https://github.com/omarmahmoud00/serverless-rest-api-cognito-waf) | Secure, globally delivered serverless REST API reference architecture — Cognito OAuth2 + PKCE, scoped authorizers, WAF at edge & region, single-table DynamoDB, X-Ray tracing, cost model | AWS · Lambda · API Gateway · DynamoDB · CloudFront · SAM |
| [**laravel-paymentGateways**](https://github.com/omarmahmoud00/laravel-paymentGateways) | One API to initiate and confirm payments across 6 gateways (Stripe, PayPal, Mollie, Paystack, Instamojo, SSLCommerz) | Laravel · PHP |
| [**senior-project-**](https://github.com/omarmahmoud00/senior-project-) | Multi-industry booking engine exposed as RESTful APIs (transport, hospitality, events, services) | Laravel · MySQL · Tailwind |
| [**Restful-Api-php**](https://github.com/omarmahmoud00/Restful-Api-php) | RESTful API built in plain PHP | PHP · MySQL |
| [**gallery-management-system**](https://github.com/omarmahmoud00/gallery-management-system) | Gallery admin with accounts, uploads, threaded comments, tags and a follow system | PHP · MySQL · JS |
| [**School-Management-System**](https://github.com/omarmahmoud00/School-Management-System) | File-based system for students, staff and managers — GPA and salary tracking | Java |
| [**DSA-Problem-Solving**](https://github.com/omarmahmoud00/DSA-Problem-Solving) | My LeetCode & Codeforces solutions | PHP · Java · JS |

---

## 🎓 Education & certification

- 🏅 **AWS Certified Solutions Architect – Associate** — Amazon Web Services (2026 – 2029) · validation no. `4a7cf178f52c44538841ed54388f46dd` · [verify](https://aws.amazon.com/verification)
- 🎓 **B.Sc. Computer Engineering** — Karabük University, Türkiye

---

## 📊 GitHub activity

<div align="center">

<img src="https://streak-stats.demolab.com?user=omarmahmoud00&theme=transparent&hide_border=true" alt="GitHub streak" />

</div>

---

<div align="center">

### 🤝 Let's work together

I'm open to **backend / software engineering roles** — remote or relocation.
The fastest way to reach me is [**email**](mailto:omar.a.abuyoussef@gmail.com) or [**LinkedIn**](https://www.linkedin.com/in/omarmahmoud00).

</div>
