<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,30:0a0e1a,60:0f1a35,100:2AA9FF&height=220&section=header&text=Sabin%20Pant&fontSize=72&fontColor=ffffff&fontAlignY=40&desc=Backend%20Engineer%20%E2%80%94%20I%20design%20systems%20before%20I%20write%20code&descAlignY=60&descSize=17&animation=fadeIn" />

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=3000&pause=800&color=2AA9FF&center=true&vCenter=true&multiline=false&repeat=true&width=600&lines=Backend+Architecture+%7C+Distributed+Systems;Java+%2F+NestJS+%2F+Node.js+%2F+PostgreSQL;5%C3%97+AWS+Certified+%7C+Cloud+Infrastructure;Building+things+that+don%27t+break+in+production)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sabinpant/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:sabinpant100@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-2AA9FF?style=flat-square&logo=vercel&logoColor=white)](https://sabin-portfolio-hazel.vercel.app/)

</div>

---

## `whoami`

```typescript
const sabin: Developer = {
  location:      "Kathmandu, Nepal 🇳🇵",
  education:     "BHons Computing — Islington College × London Metropolitan University",
  certifications: ["AWS Cloud Foundations", "AWS Data Engineering", "AWS ML Foundations",
                   "AWS ML for NLP", "AWS Generative AI Foundations"],
  currentlyBuilding: "Nebula — Virtual NEPSE Stock Trading & Learning Platform",
  philosophy:    "System design first. Code second. Ship something that lasts.",
  interests:     ["Backend Architecture", "Distributed Systems", "B2B Product Design"],
};
```

> It started with a game. I wanted to build one so right out of high school, I dove into C and C++, data structures, and algorithms. That foundation pulled me deeper: from low-level primitives to Java enterprise architecture to cloud infrastructure. Every layer I pulled back revealed something more interesting underneath.
>
> Today, I hold myself to a production standard: software that behaves the same on `localhost` as it does in prod, doesn't silently corrupt data under concurrent load, and can be maintained by someone who wasn't in the room when it was built.

---

## 📊 GitHub at a Glance

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=Sabinpabt23&show_icons=true&theme=github_dark&bg_color=0d1117&border_color=2AA9FF&icon_color=2AA9FF&title_color=2AA9FF&text_color=c9d1d9&ring_color=2AA9FF&hide_border=false" />
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sabinpabt23&theme=github_dark&bg_color=0d1117&border_color=2AA9FF&title_color=2AA9FF&text_color=c9d1d9&langs_count=8&layout=compact" />

</div>

<div align="center">

<img width="70%" src="https://streak-stats.demolab.com/?user=Sabinpabt23&theme=dark&background=0d1117&border=2AA9FF&stroke=2AA9FF&ring=2AA9FF&fire=ff6b6b&currStreakNum=ffffff&sideNums=ffffff&currStreakLabel=2AA9FF&sideLabels=2AA9FF&dates=888888" />

</div>

<br/>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Sabinpabt23&bg_color=0d1117&color=2AA9FF&line=2AA9FF&point=ffffff&area=true&area_color=2AA9FF&hide_border=false&border_color=2AA9FF&theme=github-compact" width="95%" />

</div>

---

## 🛠️ Tech Stack

<div align="center">

### Languages & Backend Runtime
<img src="https://skillicons.dev/icons?i=java,nodejs,python,cpp,typescript,javascript&theme=dark" />

### Frameworks & Architecture
<img src="https://skillicons.dev/icons?i=spring,nestjs,express,react,nextjs,tailwind&theme=dark" />

### Databases, Caching & Queues
<img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,oracle,prisma&theme=dark" />

### Cloud, Infra & Tooling
<img src="https://skillicons.dev/icons?i=aws,docker,vercel,git,github,vscode&theme=dark" />

### Design & Workflow
<img src="https://skillicons.dev/icons?i=figma,postman,linux&theme=dark" />

</div>

---

## 🚀 Latest Project

### 💬 Nebula Chat &nbsp;·&nbsp; <a href="https://nebula-chat-seven.vercel.app">Live Demo</a> &nbsp;·&nbsp; <a href="https://github.com/Sabinpabt23/nebula-chat">GitHub</a>

> Production-grade real-time chat with passwordless OTP login, Google OAuth, one-to-one & group messaging, typing indicators, and online presence — built with strict clean architecture.

<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
<img src="https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>

```
Client (React/Vite/TS)
       │
       ▼
Express API  ◄──  JWT Auth + Google OAuth + OTP
       │                    │
       ▼                    ▼
  PostgreSQL          Socket.IO ── Redis Pub/Sub
  (TypeORM)           Real-time delivery, presence, typing
```

| What | How |
|:-----|:----|
| Auth | Passwordless OTP · Google OAuth 2.0 · JWT rotation (15 min access + 7-day httpOnly refresh) |
| Messaging | DMs · Group chat · Unread badges · Typing indicators · Online presence |
| Architecture | Strict 3-layer: Controller → Service → Repository. No cross-layer leakage. |
| Deployed on | Vercel · Render · Neon · Upstash |

---

## 🏗️ How I Build

> I don't start projects. I design systems.

Before a single line is committed on any serious build, I work through:

```
┌─────────────────────────────────────────────────────────────┐
│  PHASE 1 — DESIGN                                           │
│                                                             │
│  01  Actor Definition      Who uses it, what they can do,  │
│                            what they absolutely cannot      │
│                                                             │
│  02  Schema Design         Tables, relations, indexes,      │
│                            constraints — decided upfront    │
│                                                             │
│  03  Edge Case Analysis    Concurrency, race conditions,    │
│                            failure states, data integrity   │
│                                                             │
│  04  Architecture          Layer separation, shared utils,  │
│                            error handling, security model   │
├─────────────────────────────────────────────────────────────┤
│  PHASE 2 — BUILD                                            │
│                                                             │
│  05  Production Readiness  Env parity, graceful shutdown,  │
│                            health checks, deploy pipeline  │
└─────────────────────────────────────────────────────────────┘
```

---

## 📜 Certifications

<div align="center">

| Certification | Issued By | Domain |
|:-------------|:----------|:------:|
| AWS Academy Graduate — Cloud Foundations | Amazon Web Services | ☁️ Cloud |
| AWS Academy Graduate — Data Engineering | Amazon Web Services | 📊 Data |
| AWS Academy Graduate — Machine Learning Foundations | Amazon Web Services | 🤖 ML |
| AWS Academy Graduate — Machine Learning for NLP | Amazon Web Services | 🗣️ NLP |
| AWS Academy Graduate — Generative AI Foundations | Amazon Web Services | ✨ GenAI |
| UI/UX with Figma — Web Design & Prototyping | Islington College | 🎨 Design |

</div>

---

## 📈 Contribution Summary

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Sabinpabt23&theme=github_dark" width="95%"/>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Sabinpabt23&theme=github_dark" width="46%"/>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Sabinpabt23&theme=github_dark" width="46%"/>

</div>

---

## 📫 Connect

<div align="center">

<a href="https://www.linkedin.com/in/sabinpant/">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
&nbsp;&nbsp;
<a href="mailto:sabinpant100@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-Message-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<br/><br/>

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark&quote=Design%20first.%20Build%20second.%20Ship%20something%20that%20lasts.&author=Sabin%20Pant" />

</div>

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2AA9FF,50:0f1a35,100:0d1117&height=120&section=footer&animation=fadeIn" />

<sub>Designed with intention · Built for production · Maintained with care</sub>

</div>
