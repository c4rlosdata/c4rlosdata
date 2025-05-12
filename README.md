# Hello! 👋 Welcome to my GitHub Profile!

I'm a specialist in **back-end** and **automation** applied to business, focusing on integrating and optimizing processes to enhance efficiency and customer experience. As the Founder and BackEnd Developer at **Nexus Solutions**, I help companies transform complex routines into automated solutions that add real value to their daily operations.

---

## 🔧 Skills and Technologies

- **Programming Languages:** Python, PHP, JavaScript, Node.js
- **Automation & System Integration:** Diverses APIs, Meta API, Web scraping
- **Web Development:** HTML, CSS, and backend frameworks
- **Databases:** MySQL, Postgress, data handling, and high-scale record management
- **Machine Learning & Business AI:** Practical AI applications for business process analysis and automation
- **DevOps & Hosting:** Experience with VPS and cloud services for production applications

---

## 📈 Featured Private Projects

Here are some of the most impactful projects I’ve developed:

### 💬 WhatsApp Virtual Assistant & CRM Automation

Built an end-to-end virtual assistant that lets DI Brownie’s customers place and track orders entirely through WhatsApp while keeping the MERCOS CRM in perfect sync.  
**Key points**

- **Problem solved** – customers who hadn’t bought for 15 days were slipping away and the sales team lost hours re-typing orders into the CRM.  
- **Features**  
  - Conversational flow that greets, shows last order, takes a ❶ *repeat order* or ❷ *talk to human* path.  
  - Automatic creation of new customers/orders in MERCOS, PDF receipt generation, and instant WhatsApp delivery.  
  - Reactivation daemon runs daily, fetches “Days-Since-Last-Purchase” report, and triggers personalised reminders.  
- **Stack**  
  - Node.js + TypeScript webhook server (routing, validation, retry queues)  
  - Python micro-services (PDF renderer, business rules)  
  - PostgreSQL for orders, logs and chat history  
  - WhatsApp Business Cloud API + MERCOS Open API  
  - Multistage Docker, CI/CD on Railway, full-stack tracing with OpenTelemetry  
- **Impact**  
  - ⏱ 60 hours/month saved in manual data entry  
  - ⚡ Purchase cycle cut from **4 m 10 s → 25 s**  
  - 🔄 **+228 %** inactive clients reactivated, **72 %** of orders close without a sales rep  
- **Next steps** – GPT-powered flavour recommendations and real-time delivery tracking inside WhatsApp.


### 💹 Real-Time Crypto Arbitrage Alert System on Telegram

Built for **Arbinvest**, this end-to-end platform scans **13 crypto exchanges** and pushes instant arbitrage alerts to Telegram, replacing slow manual monitoring.  
**Problem solved** – profitable spreads disappeared before traders could react; we needed bid/ask comparison across many markets in parallel.

**Features**  
- Parallel REST + WebSocket connections to all 13 exchanges.  
- Ultra-fast engine calculates price spreads and filters only profitable opportunities.  
- Telegram bot delivers pair, exchanges, spread %, and volume in real time.  
- Dockerized, CI/CD on Railway for high availability and worry-free ops.

**Stack**  
Python · REST/WebSocket · Telegram Bot API · Docker · Railway · Agile Dev.

**Impact**  
- Alert latency slashed, boosting capture rate and P&L.  
- New SaaS offering grew Arbinvest’s subscriber base and market reputation.  
- 24/7 monitoring sets the firm apart in a crowded landscape.

**Next steps** – automatic order execution and multi-exchange risk analytics.

### 📑 Content Automation Orchestrator

One-click pipeline that scouts crypto topics on Reddit, writes & refines an illustrated article with Google Gemini, publishes it to Ghost, and auto-tweets the link — while listening for Ghost webhooks to keep X in sync.

**Highlights**  
- **Config-first**: clone, drop a YAML + .env, and spin up new agents; zero code edits.  
- Dual **schedulers**: independent loops for Reddit harvesting and article generation.  
- **AI agents**: Gemini Flash turns posts into polished HTML; image agent adds custom art.  
- **Flask + APScheduler** orchestrator; Ghost→X webhook fires social posts in < 1 s.  
- Slim **Docker** image (~160 MB) and two-command deploy on Railway.  

**Stack**  
Python · Flask · APScheduler · PRAW · Google Gemini API · Ghost Admin API · Twitter API · PostgreSQL · Docker · Railway · OpenTelemetry  

**Impact**  
- Slashes end-to-end content production from hours to minutes.  
- Ensures consistent SEO tags, feature images, and cross-platform publishing.  
- Multi-instance by design — already powering 3+ crypto news blogs.  

**Next steps** – multi-channel fan-out (LinkedIn, Telegram) and real-time analytics dashboards.


---

## 🚀 What Drives Me

I believe time is our most valuable asset. At Nexus Solutions, our mission is to create solutions that "give purpose to time." I have a strong interest in projects that simplify operational routines, eliminate rework, and enable companies to focus on what really matters: their purpose and growth.

---

## 📫 Let’s Connect!

Feel free to explore my repositories and projects here, and don't hesitate to reach out!

- **LinkedIn:** [My Profile](https://www.linkedin.com/in/carlos-augusto-nascimento-desenvolvedor-python/)
- **Email:** carlos.a.r.n@hotmail.com

---

🔎 **Explore. Automate. Transform.**

[Nexus Site](https://www.nexus-solutions.tech/)
