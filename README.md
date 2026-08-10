# Hi, I'm Rafael Infante 👋

### Senior Full-Stack Java Engineer · Payments & Fintech · Platform Engineering · Legacy Modernisation

20+ years building and modernizing secure, cloud-deployed production platforms. Payments is my deepest specialty — but my range is broad: end-to-end full-stack delivery (Java/Spring + Angular), mobility & smart-city platforms, the CI/CD and engineering toolchain I build from scratch, legacy-to-modern migrations, and mentoring distributed teams.

🌍 Remote from São Paulo, Brazil (UTC−3) &nbsp;·&nbsp; 🗣️ Fluent English (C1) &nbsp;·&nbsp; 💼 Open to remote contract, full-time, or fractional roles
🎓 Oracle Certified Professional, Java Programmer

🔗 **[rafaelinfante.net](https://rafaelinfante.net)** &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/infanterafael) &nbsp;·&nbsp; matos.rafael@gmail.com

---

### 🛠️ Tech

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat&logo=stripe&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat&logo=mqtt&logoColor=white)

- **Backend:** Java (8/11/17) · Spring Boot (3.x) · Spring MVC · Spring Security · Spring Data JPA · Hibernate · Flyway · Spring Integration (MQTT)
- **Frontend:** Angular (17–20) · TypeScript · RxJS · JavaScript · HTML5 · CSS3
- **Payments & Security:** 13 gateways (Stripe, PayPal, Worldpay, ACI, Authipay, Checkout.com, Windcave, …) · gateway-hosted payment pages (reduced PCI scope) · idempotency & duplicate-payment prevention · signed webhooks · OAuth2 / JWT / OIDC
- **Cloud & DevOps:** Docker · Jenkins (CI/CD) · Maven · SonarQube · Wazuh · Uptime Kuma · AI-assisted development
- **Portfolio / currently learning:** Kafka · RabbitMQ · Kubernetes · Spring AI — see the featured projects below

---

### 🚀 Production platforms I build

- **PayBrix** — insurance collections-automation platform (recurring payments, automated dunning, omnichannel SMS/email/click-to-pay), publicly reporting **€150M+ collected** → [paybrix.com](https://paybrix.com)
- **Parking Management Solution** — multi-tenant parking platform on a modern greenfield stack (Java 17, Spring Boot 3.5, Angular 20, Maven multi-module, MQTT, multi-gateway card payments)
- **TrafficFlow** — cloud HGV traffic management for the Port of Dakar (ANPR-based entry/exit + integrated payments) → [telclic.net/trafficflow](https://telclic.net/trafficflow)
- **TFI Bikes** — Ireland's national public bike-share, backed by the National Transport Authority → [bikeshare.ie](https://bikeshare.ie)

---

### ⭐ Featured open-source projects

Each repo backs a claim on my CV — documented, tested, CI-green, and runnable with one command. *(This is where I explore beyond the day job: Kafka, Kubernetes, AI engineering.)*

| Repo | What it shows |
|---|---|
| [`payment-gateway-service`](https://github.com/rafaelinfante/payment-gateway-service) | **Payments & PCI** — one REST API over Stripe, Adyen & PayPal + a mock legacy gateway; three PCI flows (`HOSTED` / `TOKEN` / `CARD`), signed webhooks, idempotency, Testcontainers. `docker compose up` → running API, no keys needed |
| [`subscription-manager`](https://github.com/rafaelinfante/subscription-manager) | **Full-stack delivery** — subscription billing with Spring Boot 3 + Angular, social login, RS256 JWT with rotating refresh tokens, automated dunning engine |
| [`legacy-to-modern-refactor`](https://github.com/rafaelinfante/legacy-to-modern-refactor) | **Legacy modernisation** — the same app built twice: AngularJS 1.8 + Spring MVC (javax) vs Angular 20 + Spring Boot 3.5 (jakarta), with a shared contract suite proving parity + a transactional outbox |
| [`event-streaming-kafka`](https://github.com/rafaelinfante/event-streaming-kafka) | **Event streaming** — Kafka Streams: windowed revenue, KStream–KTable joins, infrastructure-vs-business error handling |
| [`kubernetes-deploy`](https://github.com/rafaelinfante/kubernetes-deploy) | **Cloud-native ops** — production-shaped K8s: HPA, zero-downtime rollouts, probes, NetworkPolicy + PDB, kustomize, Argo CD GitOps; runs on kind |
| [`model-mux`](https://github.com/rafaelinfante/model-mux) | **AI engineering** — Spring AI gateway with cost/compare routing, Resilience4j as the single retry authority, PR summarizer |
| [`fleet-telemetry-platform`](https://github.com/rafaelinfante/fleet-telemetry-platform) | **Real-time & MQTT** — MQTT → RabbitMQ (quorum queues, backpressure) → WebSocket/STOMP live map; Angular 20 + Leaflet dashboard |
| [`observability-stack`](https://github.com/rafaelinfante/observability-stack) | **Observability / SRE** — golden-signal monitoring wrapped *non-invasively* around `payment-gateway-service` (git submodule): Prometheus, Grafana, alerting |

---

### 📈 Selected impact

- ⚡ Raised payment authorization success **~38% → ~85%** by designing and building two gateway integrations from scratch — **Stripe (~95%)** and **Fiserv/Authipay (~90%)** — and migrating merchant traffic onto them
- 🛡️ **Zero confirmed double-charges across 313,000+ card transactions** · **99.997% merchant webhook delivery** (238k+ callbacks)
- 💰 **300k+ card transactions** processed · **180,000+ policyholder records** · **1M+ automated reminders** in the payment systems I personally maintain
- 💳 Integrated **13 payment gateways** behind unified, PCI-aware APIs
- 🏗️ Built CI/CD from scratch — **26 Jenkins pipelines**, cutting deploys from a manual 15-min-to-1-hour process to **~1 min** (median 45s)
- 🔧 Solo **Java 11→17 + Spring 4.3→5.8** platform upgrade in ~1 week (~20 libraries)
- 📊 Greenfield parking platform grew **payment volume ~188%** and **transactions ~228%** in its first year
- 🧩 **2,300+ PRs reviewed (900+ approved)** · **500+ merged PRs authored** · **2,100+ commits** as a hands-on tech lead

---

### 📫 Let's connect

[![Website](https://img.shields.io/badge/Website-rafaelinfante.net-4F46E5?style=flat&logo=googlechrome&logoColor=white)](https://rafaelinfante.net)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rafael%20Infante-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/infanterafael)
[![Email](https://img.shields.io/badge/Email-matos.rafael@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:matos.rafael@gmail.com)
