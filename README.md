<div align="center">
  <h1 align="center">Rio Ardian Pratama</h1>
  <p align="center">
    <strong>Systems Architect & Backend Engineer • Distributed FinTech & PPOB Infrastructure</strong><br/>
    <em>Engineering high-throughput transactional backends, low-latency gateways, and zero-compromise ACID systems.</em>
  </p>

  <!-- Mobile-Responsive Terminal Typing Animation (width <= 440) -->
  <a href="https://github.com/riiardian">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=16&duration=2500&pause=800&color=38BDF8&center=true&vCenter=true&width=440&lines=Backend+%26+Distributed+Systems;High-Concurrency+FinTech+Engines;Go+(Golang)+%E2%80%A2+Rust+%E2%80%A2+TypeScript;Zero-Compromise+System+Reliability" alt="Typing SVG" />
  </a>

  <br/><br/>

  <!-- Clean, Reliable Flat Badges -->
  <p align="center">
    <a href="https://github.com/riiardian">
      <img src="https://img.shields.io/badge/GitHub-riiardian-181717?style=flat-square&logo=github" alt="GitHub" />
    </a>
    <a href="mailto:ardianrio990@gmail.com">
      <img src="https://img.shields.io/badge/Email-ardianrio990%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
    </a>
    <a href="https://linkedin.com/in/riiardian">
      <img src="https://img.shields.io/badge/LinkedIn-Rio%20Ardian-0A66C2?style=flat-square&logo=linkedin" alt="LinkedIn" />
    </a>
    <img src="https://img.shields.io/badge/Location-Indonesia-0052CC?style=flat-square" alt="Location" />
  </p>
</div>

---

### 👨‍💻 About Me

* 🏢 **Founder & Principal Systems Architect:** Creator and lead engineer of [**AeroFlazz**](https://aeroflazz.com) (High-Throughput Digital Products & PPOB Distribution) and [**PaySaku**](https://paysaku.site) (Next-Gen FinTech Payment Gateway & Mutation Engine).
* ⚙️ **High-Concurrency Systems & Backend:** Specializing in lock-contention mitigation, distributed state management, idempotent financial transaction processing, and sub-millisecond data caching layers in **Go** and **Rust**.
* 🛡️ **Production Reliability & Security:** Hardening live multi-tenant architectures against race conditions, OWASP WSTG threat vectors, WAF bypasses, and unauthorized ledger mutations using strict cryptographic HMAC verification and atomic primitives.
* 🎓 **Academic Background:** Informatics Engineering student at **Telkom University** (Class of 2026), dedicated to systems programming, network security, and distributed computing.

---

### 🌟 Featured Production Projects

#### ⚡ [AeroFlazz](https://aeroflazz.com) — High-Throughput Digital Products & PPOB Infrastructure
* **Ownership & Architecture:** Designed and built full-stack production platform from scratch. High-performance asynchronous backend in **Go (Fiber)** coupled with **PostgreSQL** under strict ACID transaction boundaries.
* **Concurrency & Ledger Integrity:** Employs pessimistic row-level locking (`GORM v2` / `SELECT FOR UPDATE`) and atomic Redis mutexes to eliminate race conditions and balance discrepancies during intense checkout spikes.
* **Frontend & Edge Delivery:** Low-latency **Next.js (Turbopack)** web client with tiered edge caching, Cloudflare CDN integration, and real-time transaction state synchronizers.
* **Security & Orchestration:** Hardened via custom internal WAF rules, sliding-window rate limiting, and zero-downtime process management (**Supervisor** & **PM2** on Linux VPS).
* **Tech Stack:** `Go (Golang)` • `PostgreSQL` • `Redis` • `Next.js` • `TypeScript` • `Supervisor` • `Nginx`
* **Links:** [🌐 Live Platform](https://aeroflazz.com) • [🏢 Official Owner Profile](https://aeroflazz.com/tentang-kami)

---

#### 💳 [PaySaku v2](https://paysaku.site) — Real-Time Payment Gateway & E-Wallet Mutation Platform
* **Ownership & Architecture:** High-throughput financial automation gateway built in native **Rust (Tokio / Axum)** for sub-millisecond transaction routing, concurrent webhook dispatching, and zero-overhead memory footprint.
* **Dual-Engine Auto Sync:** Native asynchronous scrapers for **GoBiz (GoPay Merchant)** and **ShopeePay** delivering automatic mutation reconciliation directly to client callbacks without manual intervention.
* **Cryptographic Verification:** HMAC-SHA256 signature enforcement on all inbound/outbound callbacks, idempotent payment intake, and replay-attack mitigation.
* **Tech Stack:** `Rust` • `Tokio` • `React` • `TypeScript` • `PostgreSQL` • `HMAC-SHA256` • `Nginx`
* **Links:** [🌐 Live Platform](https://paysaku.site) • [📚 Developer API Docs](https://paysaku.site/docs)

---

#### 🌾 [Kertanusa](https://github.com/riiardian/kertanusa) — Precision Agriculture & IoT Decision Support System
* **Architecture & Telemetry:** Full-stack decision support system integrating global agro-meteorological models (**ECMWF**, **NOAA**) calibrated against national weather stations (**BMKG**) to calculate soil water balance (**FAO-56**).
* **Vision AI Pipeline:** Real-time multimodal computer vision inference for automated plant pathology diagnosis with sub-2s latency.
* **Tech Stack:** `Next.js 15` • `TypeScript` • `Tailwind CSS` • `Multimodal Vision AI` • `Leaflet GIS` • `Nginx`
* **Links:** [💻 Open Source Repository](https://github.com/riiardian/kertanusa)

<div align="center" style="margin-top: 15px;">
  <a href="https://github.com/riiardian/kertanusa">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=riiardian&repo=kertanusa&theme=github_dark&hide_border=false" alt="Kertanusa Repository Card" />
  </a>
</div>

---

### 💻 Tech Arsenal

<div align="center">
  <img src="https://skillicons.dev/icons?i=go,rust,ts,js,nextjs,react,tailwind,postgres,mysql,redis,docker,linux,nginx,git,github,postman&theme=dark&perline=8" alt="Tech Stack" />
</div>

<br/>

| Domain | Technologies & Standards |
| :--- | :--- |
| **Languages** | Go (Golang), Rust, TypeScript, JavaScript, SQL, Python |
| **Backend & Architecture** | Distributed Systems, RESTful APIs, Tokio Async, Fiber, Event-Driven Queues, HMAC-SHA256 |
| **Frontend & UI** | Next.js (App Router, Turbopack), React, Tailwind CSS |
| **Databases & Caching** | PostgreSQL (ACID, Row Locking), MySQL, Redis (Distributed Mutex, Atomic Counters), SQLite |
| **DevOps & Cloud** | Linux (Debian/Ubuntu), Nginx Reverse Proxy, PM2, Supervisor, Cloudflare Edge, Docker |
| **Security & Standards** | OWASP Hardening (HSTS, CSP), Anti-Race Condition, Input Sanitization, Rate Limiting |

---

### 🐍 Contribution Activity

<div align="center">
  <img src="https://raw.githubusercontent.com/riiardian/riiardian/output/github-contribution-grid-snake-dark.svg" alt="GitHub Contribution Snake" width="100%" />
</div>

---

### 📊 GitHub Activity & Metrics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=riiardian&show_icons=true&theme=github_dark&hide_border=false&count_private=true" width="48%" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=riiardian&layout=compact&theme=github_dark&hide_border=false" width="48%" alt="Top Languages" />
</div>

<div align="center" style="margin-top: 10px;">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=riiardian&theme=github_dark&hide_border=false" width="97%" alt="GitHub Streak" />
</div>

---

<div align="center">
  <sub>Engineered with clean architecture and strict security standards. © 2026 Rio Ardian Pratama</sub>
</div>
