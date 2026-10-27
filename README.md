<p align="center">
  <img src="assets/header.svg" width="100%" alt="Lev Iva — Software Engineer, full-stack: production web platforms, single sign-on and AI integrations">
</p>

I'm a software engineer (full-stack), working mostly in **Python** and **TypeScript**. My day job is building and running the internal platforms of an energy-tech company: the service desk, company-wide sign-in, document workflows and production dashboards. On top of that I build the AI layer: **MCP connectors** that let Claude work with these systems on behalf of each employee.

After hours I go lower in the stack: Linux, developer tooling and desktop apps.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/stats-dark.svg">
  <img src="assets/stats-light.svg" width="100%" alt="1,600+ commits to production code in 2026 · 10+ services built or co-owned · 100+ MCP tools in production · from spec to production, end to end">
</picture>

## 💼 Work

Private repositories, so here is what I build instead of links.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/work-dark.svg">
  <img src="assets/work-light.svg" width="100%" alt="Service desk with a RAG assistant; company-wide SSO (OAuth 2.0 / OpenID Connect); documents and org chart; production dashboard; HR portal; marketing analytics. Every service ships with Docker and GitHub Actions to AWS or Azure, with backups and monitoring.">
</picture>

## 🤖 AI integrations

I build **MCP servers** that connect company systems to Claude: over **100 tools** in production, each one acting with the signed-in employee's own permissions.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/ai-dark.svg">
  <img src="assets/ai-light.svg" width="100%" alt="An employee asks in Claude. The MCP connector signs them in through company SSO, acts with their own rights, asks before any write and treats untrusted text as data. It reaches the service desk, project management, Microsoft Teams, CRM and ERP.">
</picture>

<details>
<summary><b>More on how it's built</b></summary>
<br>

- **Built for real-world APIs.** A Postgres mirror with webhooks and incremental sync to live under a 1 request/second limit, OAuth 2.0 with refresh-token rotation, Prometheus metrics, backups.
- **AI-first workflow.** Claude Code as a pair programmer and parallel agent sessions in separate git worktrees. Every change still goes through review, tests and CI.

</details>

## 🛠️ Side projects

<p align="center">
  <picture><source media="(prefers-color-scheme: dark)" srcset="assets/project-nya-os-dark.svg"><img src="assets/project-nya-os-light.svg" width="49%" alt="Nya OS: a Debian 13 based Linux distribution with its own Wayland desktop, apps, installer, fingerprint login and a signed apt repository"></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="assets/project-kitsu-code-dark.svg"><img src="assets/project-kitsu-code-light.svg" width="49%" alt="Kitsu Code: my own VS Code distribution without telemetry or Microsoft services, with extension signature checks and its own branding"></picture>
</p>
<p align="center">
  <picture><source media="(prefers-color-scheme: dark)" srcset="assets/project-nya-browser-dark.svg"><img src="assets/project-nya-browser-light.svg" width="49%" alt="Nya Browser: a fast, private desktop browser with network-level ad blocking, vertical tabs, reading mode, 65 languages and auto-updates"></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="assets/project-deb-installer-dark.svg"><img src="assets/project-deb-installer-light.svg" width="49%" alt="Deb Installer: a GTK 4 app that installs .deb packages safely with dependency, conflict and maintainer-script checks"></picture>
</p>

## 🧰 Stack

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=python%2Cts%2Cjs%2Cbash%2Cfastapi%2Cnestjs%2Cnodejs%2Cprisma%2Creact%2Cnextjs%2Cvite%2Ctailwind%2Celectron%2Cpostgres%2Credis%2Cdocker%2Cgithubactions%2Cnginx%2Cterraform%2Caws%2Cazure%2Clinux%2Cdebian%2Cqt%2Cgit&perline=13&theme=dark">
  <img src="https://skillicons.dev/icons?i=python%2Cts%2Cjs%2Cbash%2Cfastapi%2Cnestjs%2Cnodejs%2Cprisma%2Creact%2Cnextjs%2Cvite%2Ctailwind%2Celectron%2Cpostgres%2Credis%2Cdocker%2Cgithubactions%2Cnginx%2Cterraform%2Caws%2Cazure%2Clinux%2Cdebian%2Cqt%2Cgit&perline=13&theme=light" alt="Python, TypeScript, JavaScript, Bash, FastAPI, NestJS, Node.js, Prisma, React, Next.js, Vite, Tailwind CSS, Electron, PostgreSQL, Redis, Docker, GitHub Actions, Nginx, Terraform, AWS, Azure, Linux, Debian, Qt/QML, Git">
</picture>

<img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white" alt="Claude"> <img src="https://img.shields.io/badge/MCP-7C3AED?style=flat-square&logo=modelcontextprotocol&logoColor=white" alt="MCP"> <img src="https://img.shields.io/badge/RAG_·_Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white" alt="RAG with Qdrant"> <img src="https://img.shields.io/badge/Microsoft_Graph-0078D4?style=flat-square" alt="Microsoft Graph"> <img src="https://img.shields.io/badge/OAuth_2.0_·_OIDC-F78C40?style=flat-square&logo=openid&logoColor=white" alt="OAuth 2.0 and OpenID Connect">
