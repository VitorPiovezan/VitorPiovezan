<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:1d6b5c,100:2fbf71&height=210&section=header&text=Vitor%20Piovezan&fontSize=58&fontColor=ffffff&fontAlignY=36&desc=Product%20Engineer%20%C2%B7%20%C3%81rvore%20Educa%C3%A7%C3%A3o&descSize=18&descAlignY=58&animation=fadeIn" alt="Vitor Piovezan" />
</p>

<p align="center">
  <a href="https://vitorpiovezan.com.br">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=900&color=2FBF71&center=true&vCenter=true&width=720&lines=Product+Engineer+who+ships+end-to-end+%F0%9F%9A%80;From+idea+to+schema%2C+API%2C+web%2C+app+and+deploy;Building+AI-native+tools+for+engineering+teams+%F0%9F%A4%96;7%2C000%2B+commits+across+30%2B+repos+at+%C3%81rvore+%F0%9F%8C%B3;Contributor+to+Hive+%E2%80%94+open+source+agent+fleet+%F0%9F%90%9D" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://vitorpiovezan.com.br"><img src="https://img.shields.io/badge/vitorpiovezan.com.br-0f2027?style=for-the-badge&logo=googlechrome&logoColor=2FBF71" alt="Website" /></a>
  <a href="https://www.linkedin.com/in/vitor-piovezan-6a65351aa"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="http://instagram.com/vitor_piovezan"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" /></a>
  <a href="mailto:vitor.piovezan7@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" /></a>
  <img src="https://komarev.com/ghpvc/?username=VitorPiovezan&style=for-the-badge&color=2fbf71&label=PROFILE+VIEWS" alt="Profile views" />
</p>

---

## 🌳 Who I am

<img align="right" width="340" src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" alt="coding" />

I'm a **Product Engineer** at **[Árvore Educação](https://www.arvore.com.br)**, the Brazilian edtech that puts reading and writing in the hands of millions of students in Brazil and the US.

I started in 2021 as a front-end developer. Five years and **7,000+ commits** later, I own features **end to end**: I talk to the people who use the product, shape the problem, design the data model, write the migration, the API, the web screen, the mobile screen, and watch it in production.

- 🧭 **Product first.** I start from the user problem, not from the ticket.
- 🧱 **Full stack by default.** Next.js, NestJS, Elixir, React Native, Python, MySQL, Postgres.
- 🤖 **AI-native.** I work with a fleet of coding agents every day and build the tools that make that possible.
- 📍 Monte Alto, São Paulo, Brazil

<br clear="right" />

---

## 🚀 What I build today

<table>
<tr>
<td width="50%" valign="top">

### ✍️ Super Autor / Super Author
Our writing product, where every student publishes a **real printed book**. I led its migration into the Árvore platform and its launch in the **US market**:

- Teacher, student, guardian and principal journeys
- Print-ready PDF pipeline (interior + cover, bleed, embedded fonts)
- Guardian store with Stripe checkout and shipping by deadline
- **Clever** rostering for US school districts
- An internal back office to run schools, networks and projects

</td>
<td width="50%" valign="top">

### 📄 Sheet Scan (computer vision)
Students write and draw on paper. A Python service reads the scanned sheets back:

- **OpenCV** page detection, perspective fix and QR orientation
- Crops each illustration and handwriting slot automatically
- **AI-based crop validation** and handwriting OCR through a queue
- Cut processing time by ~76% after profiling the hot path

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📱 Mobile apps
The Árvore and BibliON reading apps on the App Store and Google Play:

- **React Native + Expo**, OTA updates behind a CDN
- Offline bundle of the web app inside the native shell
- Crash hunting on Android (WebView renderer, R8, native services)
- Reading position sync and the e-reader experience

</td>
<td width="50%" valign="top">

### 📚 Reading platform
The core product used by schools every day:

- **Next.js** front end and **NestJS** API, plus the **Elixir/Phoenix** legacy
- Session and auth hardening across three token systems
- Multi-brand white-label (BibliON) by host
- Gamification ("Floresta"), events, certificates and reading fluency

</td>
</tr>
</table>

---

## 🐝 Open source

<table>
<tr>
<td width="50%" valign="top">

### [Hive](https://github.com/arvoreeducacao/hive)
**Run a fleet of coding agents side by side** and watch them all at once: Claude Code, Codex, OpenCode, Kimi, Kiro or Cursor, on your machine or on a server you own.

My contributions:
- 🎙️ **Meetings**: record a call, get the transcript and AI notes, plus a Chrome extension that captures Google Meet captions
- 📱 **Android device driver**: an agent drives a real emulator through `device_*` tools (adb, live screen pane, taps)
- 🐣 **"Mini você"**: a tamagotchi with your profile face that reacts when an agent needs you
- 🧩 Request queue, Slack hand-off and pod health fixes

</td>
<td width="50%" valign="top">

### [arvore-mcp-servers](https://github.com/arvoreeducacao/arvore-mcp-servers)
A collection of **Model Context Protocol** servers that plug real company tools into AI assistants.

My contributions:
- 📊 **Metabase MCP**: query dashboards and questions from the chat
- 🤖 **Play Console MCP**: Android vitals, crash clusters and reviews
- 👀 **Visual Review MCP**: screenshot-based UI review

### [Canopy](https://github.com/arvoreeducacao/canopy)
Watch and drive your real browser with AI agents (MCP + CDP daemon, live cockpit, visible AI cursor).

</td>
</tr>
</table>

---

## 🛠️ Internal tools I created

| | Tool | What it does |
|---|---|---|
| 🦜 | **Parrot** | The company's own Discord: text, voice, screen share and camera. Electron desktop app, LiveKit, Fastify, Google SSO |
| 🌾 | **Aveia** | Meeting notebook: records via Meet captions or mic, AI notes, sharing, plus an MCP so agents can read decisions |
| 📈 | **Data Analyst Chat** | An agent that answers data questions by cross-checking Metabase, ClickHouse and MySQL with real queries |
| ⚙️ | **Arvore ETL** | A lightweight Airflow alternative to schedule and run ETL jobs |
| 🧠 | **IA para todos** | Onboarding site that teaches the whole company to work with AI |
| 🏆 | **[campeao-bot](https://github.com/VitorPiovezan/campeao-bot)** | A Discord bot with voice, audio and Whisper transcription |

---

## 🧰 Tech stack

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,tailwind,nodejs,nestjs,elixir,python,electron&perline=10" />
  </a>
  <br/>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=mysql,postgres,redis,graphql,prisma,docker,kubernetes,aws,cloudflare,vercel&perline=10" />
  </a>
  <br/>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=opencv,firebase,githubactions,git,linux,vitest,jest,figma,androidstudio,vscode&perline=10" />
  </a>
</p>

| Area | Tools |
|---|---|
| 🎨 **Front end** | Next.js (App Router), React 19, TypeScript, Tailwind, shadcn/ui, our Bonsai design system |
| 📱 **Mobile** | React Native, Expo, EAS, OTA updates, Android native debugging |
| 🧩 **Back end** | NestJS, Elixir/Phoenix, GraphQL, REST, Python (FastAPI, OpenCV) |
| 🗄️ **Data** | MySQL, PostgreSQL, ClickHouse, Metabase, Knex migrations |
| ☁️ **Infra** | AWS (EKS, S3, CloudFront, SQS), Kubernetes, Docker, Cloudflare, Dokploy, GitHub Actions |
| 🔭 **Observability** | SigNoz / OpenTelemetry, Sentry, PostHog, LaunchDarkly |
| 🤖 **AI** | Claude Code, Codex, MCP servers, Vercel AI SDK + AI Gateway, OpenAI, Whisper |
| 💳 **Integrations** | Stripe, Clever, HubSpot, Slack, Google Meet |

---

## 📊 Five years at Árvore in numbers

<div align="center">

| 🌳 Since | 💾 Commits | 📦 Repos touched | 🔀 Top repos |
|:---:|:---:|:---:|:---:|
| **2021** | **7,000+** | **30+** | frontend-nextjs · api · arvore (Elixir) · mobile |

</div>

```text
2021  ▏                                   first commits in the Elixir legacy
2022  ██                                  React, design system, reader web
2023  █████                               full stack: Next.js + NestJS
2024  ███                                 mobile app and platform
2025  ███████                             Super Autor migration begins
2026  ████████████████████████████████    AI-native: agents ship with me every day
```

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=VitorPiovezan&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=VitorPiovezan&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=VitorPiovezan&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=VitorPiovezan&theme=tokyo-night&hide_border=true&area=true" width="100%" />
</p>

---

## 🎮 Side projects

- 🐱 **[vitudoro-cat](https://github.com/VitorPiovezan/vitudoro-cat)**: a pixel-art cat that walks on your Linux desktop and runs your pomodoro
- 💰 **[my-finance](https://github.com/VitorPiovezan/my-finance)**: local personal finance app with SQLite in the browser and AI categorization
- 🔔 **[gnome-extension-gh-prs](https://github.com/VitorPiovezan/gnome-extension-gh-prs)**: your open PRs and pending reviews in the GNOME top bar
- 💡 **[tuya-control](https://github.com/VitorPiovezan/tuya-control)**: control smart lights over the local network

---

<p align="center">
  <img src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg" alt="snake" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2fbf71,50:1d6b5c,100:0f2027&height=120&section=footer" />
</p>
