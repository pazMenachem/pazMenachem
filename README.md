# Paz Menachem

**IT & Security Engineer at Copyleaks** — the sole IT and security engineer for an 80-person SaaS company, reporting to the CISO.

I came into security from writing code, and I did not stop writing it. Two internal platforms I built end to end are in daily production use, one of them across the whole company, and both were in scope for the company's SOC 2 audit. Before this I spent two years at Magshimim teaching C++ and computer networks to 10th and 11th graders, preparing them for elite IDF cyber units.

Outside work I build things end to end: a home internet filter that blocks domains from inside the Linux kernel, a multiplayer trivia game with its own C++ server and wire protocol, and a scheduler that reads job listings with an LLM and messages the matches to Telegram.

**Works on:** backend services, DevSecOps and platform tooling, cloud security. Based in Israel.

---

### Projects

**[JobHunter](https://github.com/pazMenachem/JobHunter)** — a scheduler that reads job listings with an LLM and messages the matches to Telegram or email. Runs unattended in Docker for weeks. The LLM and the notification channel sit behind factories, so swapping Gemini for a local model is a new class and a config string.

**[My_Internet](https://github.com/pazMenachem/My_Internet)** — a home internet filter that blocks domains from inside the Linux kernel. A netfilter hook rewrites blocked DNS lookups into NXDOMAIN before they leave the machine; the blocklist is RCU-protected because it is read on every packet. Python management server and desktop client on top.

**[Trivia_Game](https://github.com/pazMenachem/Trivia_Game)** — a multiplayer trivia game with its own C++ server and wire protocol. Thread per client, a request-handler state machine that swaps behaviour as a player moves between menu and game, and binary-framed JSON over raw sockets. C# desktop client.

---

### Working with

`Python` `TypeScript` `C` `C++` `C#` `Bash` — Next.js, Fastify, Node.js, Django, Firestore, PostgreSQL, SQLite
`GCP` `Oracle Cloud` `Docker` `Terraform` `Cloud Run` `Linux` — IAM, CI/CD, firewall and network policy
`Elastic SIEM` `CrowdStrike EDR` `Keycloak` — OIDC, SAML, SSO, MFA, least-privilege access design, SOC 2 Type II
`Claude Agent SDK` `MCP` `n8n` — agent tooling and workflow automation

---

[Portfolio](https://pazmenachem.github.io/WebFolio/) · [LinkedIn](https://linkedin.com/in/paz-menachem) · paz.menach@gmail.com
