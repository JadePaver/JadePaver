<div align="center">

# Jade N. Paver

**Software Developer** — mobile, web, and the API layer underneath both.

<p>
  <em>Architecture before features · Ship small, ship often · Plain language, always</em>
</p>

<p>
  <a href="https://jadepaver.github.io/portfolio/">
    <img src="https://img.shields.io/badge/Portfolio-1a1a1a?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://www.linkedin.com/in/jade-paver-a6073a280/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:paver.jade09@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://x.com/Zakkur29">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" />
  </a>
</p>

<p>
  <img src="https://img.shields.io/badge/Open%20to%20work-12B48F?style=flat-square" alt="Open to work" />
  <img src="https://img.shields.io/badge/Replies%20in-%3C24h-2F6FED?style=flat-square" alt="Replies in under 24 hours" />
  <img src="https://img.shields.io/badge/Shipping%20since-2020-6E7781?style=flat-square" alt="Shipping since 2020" />
  <img src="https://img.shields.io/badge/Projects-20%2B-6E7781?style=flat-square" alt="20+ projects" />
</p>

</div>

---

## About

I started writing code in 2020, at sixteen, in a high school computer lab with a
borrowed book. Every tool I use I taught myself first and got graded on later —
so hand me an unfamiliar stack or a half-written spec and you won't be managing
me through it.

Six years on, I work the full delivery path: schema and API design, front-end
architecture, mobile releases, and the handover documentation that outlives the
project. **BS Computer Technology, Class of 2024** — earned while already
shipping paid client work on the side.

By day I build internal systems for provincial government offices — budget
management, asset custody, property ledgers, service queuing — the kind of
software that has real money, real auditors, and real deadlines attached to it.
I've run delivery on teams of three to eleven, which mostly means I've learned
to write a spec other people can build from.

```text
Daily stack   Flutter · Dart · Laravel · PHP · React · TypeScript · MySQL
Building      Android apps, internal dashboards, service-desk platforms
Shipped for   Provincial government, private clients, research labs
Based         Bacolod City, Negros Occidental, Philippines
```

---

## Selected work

Five case studies, each written up end to end — the brief, the constraint that
shaped it, and what actually shipped.

| Project | What it is | Stack | |
| :--- | :--- | :--- | :--- |
| **Ledger** <br/> <sub>2025 · Solo</sub> | Multi-wallet Android finance app. Offline-first, with an AI assistant wired to real transaction data. | `Flutter` `Dart` `Firebase` `Hive` | [Case study →](https://jadepaver.github.io/portfolio/#/projects/ledger) |
| **PasaBay** <br/> <sub>2024–25 · Full-stack</sub> | Food delivery for neighborhood home kitchens. Live serving counts, pin-first addresses. | `Flutter` `Dart` `Maps API` | [Case study →](https://jadepaver.github.io/portfolio/#/projects/pasabay) |
| **Aspentech** <br/> <sub>2025–26 · Front-end</sub> | Enterprise sales site where the demo *is* the spec — buyers re-skin real systems live. | `React` `TypeScript` `Laravel` `MUI` | [Case study →](https://jadepaver.github.io/portfolio/#/projects/aspentech) |
| **ICTD App** <br/> <sub>2025–26 · Design + build</sub> | Government service desk in two halves: field app + admin console, one shared record. | `Flutter` `React` `TypeScript` `Supabase` | [Case study →](https://jadepaver.github.io/portfolio/#/projects/ictd) |
| **LMS** <br/> <sub>2025–26 · Solo</sub> | Code-learning platform. Students write and test in-browser; instructors grade inline. | `React` `Node` `Express` `MySQL` | [Case study →](https://jadepaver.github.io/portfolio/#/projects/lms) |
| **Budget System (BMS)** <br/> <sub>2023– · Full-stack</sub> | The province's annual budget cycle end to end — proposal through disbursement, 70+ statutory reports. | `AdonisJS` `React` `MySQL` `MUI` | <sub>In production, multi-office</sub> |

<details>
<summary><b>The numbers I actually care about</b></summary>

<br/>

**Ledger** — entry flow cut from **9 taps to 2**; cold start under **1.4s** on a
mid-range Android device. The local Hive cache is the source of truth, so nothing
in the UI ever waits on the network. The AI layer only phrases numbers computed by
the same query layer that powers Insights — if the data can't answer, neither
does the assistant.

**PasaBay** — a **2-day** menu horizon (today and tomorrow, never a date
picker), **0** passwords (OTP plus a 4-digit PIN), and a live serving count that
caps the order stepper. You cannot order food that was never cooked.

**Aspentech** — **6** shippable system templates, **7** design skins built as
token sets over one component library, **0** mockups drawn per enquiry. The
configuration serializes into a link, so the proposal request arrives carrying
the exact setup the buyer built.

**ICTD** — **2 clients, 1 shared record**; **9** console modules; **100%** of
actions written to an append-only log. Status is an event, never a field
somebody overwrote — custody disputes get settled by reading the timeline.

**LMS** — **18** modules across **6** tracks, **3** difficulty tiers, **1**
locked submission per assessment. Queues and filters carry their own counts, so
triage happens while reading the list.

**BMS** — **5** cycle stages on one set of live figures, **70+** statutory and
management reports generated from that single source, scoped per role so each
office sees only what it's accountable for. The offices stopped reconciling
copies; the report that took days of collation now renders on request.

</details>

<details>
<summary><b>Also shipped</b></summary>

<br/>

| Project | What it is | Stack |
| :--- | :--- | :--- |
| [GSO-PMD Property Management](https://jadepaver.github.io/portfolio/#/projects/gso_pmd) | Supplies distribution and property ledgers across provincial offices | `React` `MySQL` |
| [ButchFurniture](https://jadepaver.github.io/portfolio/#/projects/furniture) | Furniture e-commerce — storefront plus inventory and delivery management | `React` `Node` `MySQL` |
| [AES](https://jadepaver.github.io/portfolio/#/projects/aes) | Advanced Educational Smart System | `React` `MySQL` |
| Service queuing | Queue management for provincial offices, web and mobile | `React` `Flutter` |
| DTR face-recognition gate | IoT log-in gate built and deployed at TUP Visayas | `Python` `IoT hardware` |

</details>

---

## Stack

Grouped by how much I'd actually stake on it.

**Daily driver** — reach for these without thinking

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" title="Typed front to back, no loose ends" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" title="Dashboards and client-facing interfaces" />
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white" alt="Laravel" title="APIs, auth, admin panels, queues" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP" title="Server side of every project I have shipped" />
  <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter" title="Android and iOS from one codebase" />
  <img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white" alt="Dart" title="App logic, state, and platform channels" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" title="Schema design, migrations, query tuning" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" title="Small commits, readable history, no force pushes" />
</p>

**Shipped with it** — in production, still learning its edges

<p>
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" title="Small services, scripts, build tooling" />
  <img src="https://img.shields.io/badge/AdonisJS-5A45FF?style=flat-square&logo=adonisjs&logoColor=white" alt="AdonisJS" title="The API layer behind the province's budget system" />
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase" title="Auth, storage, and realtime data on mobile" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black" alt="Firebase" title="Firestore sync and auth behind Ledger" />
  <img src="https://img.shields.io/badge/MUI-007FFF?style=flat-square&logo=mui&logoColor=white" alt="MUI" title="Component system behind the React dashboards" />
  <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" title="Design tokens straight in the markup" />
  <img src="https://img.shields.io/badge/REST%20APIs-6E7781?style=flat-square" alt="REST APIs" title="Contracts other developers build against" />
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white" alt="Figma" title="Design review and developer handoff" />
</p>

**Currently learning** — honest about where I am

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" title="Moving my MySQL habits across" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" title="Local environments that match production" />
  <img src="https://img.shields.io/badge/CI%2FCD-6E7781?style=flat-square&logo=githubactions&logoColor=white" alt="CI/CD" title="Automating the release steps I still do by hand" />
  <img src="https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white" alt="GraphQL" title="Schema-first queries for client apps" />
  <img src="https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS" title="Past shared hosting, one service at a time" />
</p>

---

## How I work

**Discover** → one call to define the outcome and what success looks like in numbers.
**Architect** → data model, API contracts, and screen flows agreed before a line of feature code exists.
**Build** → two-week increments, each ending in something you can click, with a written changelog.
**Ship & support** → release, monitor, hand over documentation, stay reachable after launch.

> Clear boundaries and a normalized data model, so the tenth feature costs about
> what the first one did. Working increments over big reveals — you see progress
> every week, not a surprise at the deadline. And trade-offs explained without
> jargon, so non-technical stakeholders can make the call with real information.

---

## Where I've done it

**Software Developer & Project Manager** — ICT Division, Office of the Governor · `2023 – present`
Internal web and mobile systems for provincial government offices: budget
management, supplies distribution, property ledgers, and service queuing.
I own each system end to end — requirements, screen design, build, release, and
the turnover documentation — and manage delivery across offices alongside
hardware repair and end-user support.

<details>
<summary><b>Earlier — internships, practicum, and the student org</b></summary>

<br/>

| Role | Organization | Hours |
| :--- | :--- | ---: |
| Project Manager & Software Developer | Spring Valley Technology and Innovation | 800 |
| 3D Designer & Software Developer | TUP–Visayas Research and Innovation Center | 200 |
| Desk Receptionist & Video Editor | Island Living Channel | 150 |

**Club President, Technological Society** — TUP Visayas
A student organization spanning four sections. I ran a collaborative program with
a private company to get members hands-on with industry-relevant technology.

</details>

---

## Education & certifications

**BS Computer Technology** — Technological University of the Philippines, Visayas · Class of `2024`
Diploma, ICT Computer Programming · `2019`

`Civil Service Professional Eligibility` — August 2023
`Safety Officer 2 (SO2)` — March 2023

---

<div align="center">

<p>
  <img src="https://img.shields.io/github/followers/JadePaver?style=for-the-badge&color=12B48F&labelColor=1a1a1a&logo=github" alt="GitHub followers" />
  <img src="https://img.shields.io/github/stars/JadePaver?affiliations=OWNER&style=for-the-badge&color=2F6FED&labelColor=1a1a1a&logo=github" alt="Total stars" />
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=JadePaver&hide_border=true&theme=dark&ring=12B48F&fire=12B48F&currStreakLabel=12B48F" />
  <img src="https://streak-stats.demolab.com/?user=JadePaver&hide_border=true&theme=default&ring=12B48F&fire=12B48F&currStreakLabel=12B48F" alt="GitHub contribution streak" />
</picture>

</div>

---

<div align="center">

### Got something to build?

I take on web apps, Flutter builds, and the design work that goes with them.
Tell me the outcome you need and I'll tell you what it takes — usually within a day.

**[paver.jade09@gmail.com](mailto:paver.jade09@gmail.com)** · **[jadepaver.github.io/portfolio](https://jadepaver.github.io/portfolio/)**

</div>
