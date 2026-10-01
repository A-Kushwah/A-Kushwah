<div align="center">

<img src="./assets/hero.svg" alt="Ayush Kushwah — full-stack developer, distributed systems" width="100%" />

<br/>

<a href="https://www.linkedin.com/in/a-kushwah"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white&labelColor=0b1020" /></a>
<a href="https://github.com/A-Kushwah"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white&labelColor=0b1020" /></a>
<a href="mailto:ayushkushwah131@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white&labelColor=0b1020" /></a>
<img src="https://komarev.com/ghpvc/?username=A-Kushwah&style=flat-square&color=22d3ee&label=views" />

</div>

<img src="./assets/divider.svg" width="100%" height="3" />

## `~/about`

Full-stack developer who keeps pulling on the systems thread — Redis, queues, what actually happens under load. CSE undergrad at Vellore Institute of Technology, Bhopal (2023–2027).

```
→ ran 5 rate-limiting algorithms head-to-head against real traffic, not just read about them
→ built CareFlow: double-booking prevention enforced at the database level, not app code
→ co-authored an IEEE paper (AIST 2025) on carbon footprint estimation
→ went down a cybersecurity rabbit hole via Goldman Sachs' sim — ended up cracking weak
  hashes with Hashcat for fun
→ currently deep in placement prep + building llmctl, a multi-provider LLM config CLI
```

<img src="./assets/divider.svg" width="100%" height="3" />

## `~/stack`

<table>
<tr><td valign="top" width="33%">

**Languages**
```
Java
JavaScript
TypeScript
HTML5 / CSS3
```

</td><td valign="top" width="33%">

**Frameworks**
```
Next.js · React
Node.js · Express
Prisma ORM
Tailwind CSS
```

</td><td valign="top" width="33%">

**Data**
```
PostgreSQL · MySQL
MongoDB · SQLite
Redis
```

</td></tr>
<tr><td valign="top" width="33%">

**Infra & Tools**
```
AWS (EC2/S3/Lambda/RDS)
Docker · Linux
Git · Postman
Playwright
```

</td><td valign="top" width="33%">

**Core Concepts**
```
REST APIs · WebSockets
JWT · OAuth 2.0
System Design · RAG
```

</td><td valign="top" width="33%">

**AI-assisted dev**
```
Claude · Claude Code
ChatGPT / Codex
GitHub Copilot · Ollama
```

</td></tr>
</table>

<img src="./assets/divider.svg" width="100%" height="3" />

## `~/projects --featured`

### 🏥 CareFlow — Healthcare Appointment Platform
`Next.js` `TypeScript` `Prisma` `PostgreSQL`

Double-booking isn't an edge case in scheduling software — it's the thing that breaks trust fastest. Most apps catch it with application-side checks, which race under real concurrent load. This one doesn't:

- Prevents double-booking with a **PostgreSQL GiST exclusion constraint** at the database level, not just app-side checks
- **Transactional outbox** with exponential backoff + dead-letter queue for reliable notification delivery
- Google Calendar OAuth 2.0 sync, role-based access (Patients / Doctors / Admins)
- **65 passing integration tests**

[`→ live demo`](https://a-kushwah-care-flow.vercel.app/) · [`→ source`](https://github.com/A-Kushwah/CareFlow)

---

### ⚡ Distributed API Rate Limiter
`Node.js` `Redis` `Lua` `Docker`

Five rate-limiting algorithms, benchmarked head-to-head against real traffic instead of staying theoretical:

- Token bucket, sliding window, sliding log, fixed window, leaky bucket — all as **atomic Redis Lua scripts**
- **500 req/s sustained, p99 latency 12ms**; blocked 4,990 of 5,000 over-quota requests exactly
- Live WebSocket dashboard to watch algorithm behavior under load in real time

[`→ live demo`](https://rate-limiter-j4km.onrender.com) · [`→ source`](https://github.com/A-Kushwah/Rate-Limiter)

---

<table>
<tr><td valign="top" width="50%">

**🔗 Stub — URL Shortener**
`Next.js` `TypeScript` `SQLite`

JWT sessions + bcrypt hashing, click-analytics across 4 dimensions, QR codes, zero-dependency SQLite backend.

[`→ demo`](https://stub-url-shortner.vercel.app/) · [`→ source`](https://github.com/A-Kushwah/URL-Shortner)

</td><td valign="top" width="50%">

**📄 DocQ — Document Q&A (RAG)**
`React` `Vite`

Fully client-side RAG pipeline — chunking, cosine-similarity retrieval — zero server round trips, documents never leave the browser.

[`→ demo`](https://docq-gamma.vercel.app/) · [`→ source`](https://github.com/A-Kushwah/RAG-Document-Q-A)

</td></tr>
</table>

<details>
<summary><code>$ ls more-projects/</code></summary>
<br/>

| Project | Stack | Notes |
|---|---|---|
| [Carbon Footprint Estimator](https://github.com/A-Kushwah/carbon_foorprint) | LightGBM, TabGNN, TabPFN, Streamlit | Individual & industrial emissions estimation; basis for [IEEE AIST 2025 paper](https://ieeexplore.ieee.org/abstract/document/11441523), built as Data Scientist on a 4-person team |
| [Multiple Disease Detection](https://github.com/A-Kushwah/Multiple-Disease-Detection) | Streamlit, scikit-learn | Diabetes / heart disease / breast cancer prediction with confidence scores |
| [Currency Converter](https://github.com/A-Kushwah/Currency_Converter) | HTML, CSS, JS | Real-time exchange rates, responsive UI |

</details>

<img src="./assets/divider.svg" width="100%" height="3" />

## `~/certifications`

| Cert | Issuer |
|---|---|
| Software Engineering Virtual Experience (cracked outdated hashes w/ Hashcat) | Goldman Sachs · Forage |
| Intro to Machine Learning | NPTEL |
| Bits and Bytes of Computer Networking | Coursera (Google) |
| Google IT Support Certificate | Google Career Certificates |
| AI/ML Internship Certificate | MPOnline Limited |

<img src="./assets/divider.svg" width="100%" height="3" />

## `~/stats`

<div align="center">
<img height="165" src="https://github-stats-extended.vercel.app/api?username=A-Kushwah&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0b1020&title_color=22d3ee&icon_color=a78bfa&text_color=c4b5fd"/>
<img height="165" src="https://github-stats-extended.vercel.app/api/top-langs/?username=A-Kushwah&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0b1020&title_color=22d3ee&text_color=c4b5fd"/>
</div>

<img src="./assets/divider.svg" width="100%" height="3" />

<div align="center">

### `$ echo "let's build something"`

<a href="https://www.linkedin.com/in/a-kushwah"><img src="https://img.shields.io/badge/Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:ayushkushwah131@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>

</div>
