### Hi, I'm Aaron 👋

Senior full stack engineer in Tacoma, WA. I build production web apps in **Java/Spring Boot**, **Angular**, and **TypeScript/Node**, and I run them on **AWS** and **Google Cloud**. I'm open to remote senior engineering roles.

Most recently I was a Senior Software Engineer at Buyers Edge Platform on **Back Office**, a restaurant operations and accounting SaaS used by 4,000+ restaurants. There I designed the data model that turns POS data from about 25 systems into accounting views operators can trust.

#### What I'm building

- **[Studio Manager](https://github.com/AaronFilson/studiomanager)** (in development): an open-source platform for running pottery studios, from pieces and kiln queues to firing fees, scheduling, supplies, and consignment payouts.
  - **Backend:** Spring Boot 4.1 on Java 25, a Spring Modulith modular monolith with test-verified module boundaries, and an OpenAPI-first contract that fails the build on drift.
  - **Data:** PostgreSQL 18 with row-level security for tenant isolation, and a double-entry ledger the database keeps balanced.
  - **Clients:** a React 19 web app and an Expo mobile app on one generated TypeScript client, with Microsoft Entra External ID sign-in.
  - **Infrastructure:** Terraform for Azure Container Apps, passwordless database access through managed identity, keyless OIDC deploys, and Testcontainers integration tests.
- **[Glazecalc](https://glazecalcapp.com)** ([repo](https://github.com/AaronFilson/glazecalc)): a free glaze chemistry calculator for potters. I revived a 2017 AngularJS app as a maintained product:
  - **Stack:** Angular 22, a TypeScript Node 24/Express 5 API, and MongoDB.
  - **Languages:** translated into 39 languages: an official language for every EU country, plus 15 across Asia and the Middle East, including right-to-left Arabic and Urdu.
  - **AI assistants:** an [MCP server](https://glazecalcapp.com/mcp), listed in the [MCP Registry](https://registry.modelcontextprotocol.io/v0/servers?search=com.glazecalcapp/glazecalc) as `com.glazecalcapp/glazecalc`, so Claude, Copilot, Cursor, and Gemini can run the chemistry. Your own recipes are reachable only with read-only personal access tokens you can revoke.
  - **Security:** Google and GitHub sign-in (OAuth 2.0/OIDC with PKCE), plus optional two-step sign-in with passkeys, authenticator apps, and recovery codes.
  - **Quality:** 1,800+ automated tests, Lighthouse 99/100, and a 204-entry materials library sourced from manufacturers' data sheets.
  - **Deploys:** keyless, approval-gated deploys to EC2, with staging and automatic rollback, for about $13 a month.
  - **Docs:** read the [case study](https://github.com/AaronFilson/glazecalc/blob/master/docs/case-study.md) and the [decision records](https://github.com/AaronFilson/glazecalc/tree/master/docs/adr).
- **[Updraft Pottery Studio](https://updraftpotterystudio.com)** ([repo](https://github.com/AaronFilson/updraftwebsite)): a live shop for a Tacoma ceramics studio that takes real Square payments.
  - **Front end:** a fast static site with its own image pipeline.
  - **Shop:** serverless Lambda APIs with stock-aware checkout. In a load test, 12 simultaneous buyers tried for one piece and exactly one was charged.
  - **Infrastructure:** S3 and CloudFront defined as code, with staging and production stages.
- **[Glaze Vault](https://github.com/AaronFilson/glaze-vault)** (early development): an encrypted desktop app for studios with proprietary glaze recipes, with teams and roles, built with Tauri 2, a Rust core (SQLCipher, Argon2id), and React 19. It's now adding a LAN host with offline replicas, signed revisions, and an audit log.
- **[Omnifilter](https://omnifilter-3uthre4zva-uc.a.run.app)** ([repo](https://github.com/ocgears/omnifilter)): a 2016 team project I revived as a GPU photo-filter app, live on Google Cloud Run. It has OpenCL kernels in a C++ Node addon, plus WebGPU and WebGL2 engines for live in-browser previews, even on the camera.
- **[Kilndesigner](https://github.com/AaronFilson/kilndesigner)** (early development): describe a kiln and get its heat loss, element or burner sizing, a 3D model, and buildable plans, with the working and sources for every number. Python (FastAPI, SciPy, Cantera, build123d) with a React Three Fiber viewer.

#### How I work with AI

I use Claude Code every day as a directed coding agent, with guardrails:

- Plans and decision records come before code.
- Security-sensitive work gets an adversarial review.
- Every change runs through tests and CI gates (CodeQL, axe, Lighthouse) before an approved deploy.

I've also built AI agents at company hackathons.

#### Tools I use

Java · Spring Boot · Spring Modulith · Hibernate · Angular · React · TypeScript · Node.js · Python · FastAPI · Rust · MySQL · PostgreSQL · MongoDB · Redis · AWS (EC2, S3, Lambda, CloudFront, CloudFormation/SAM) · Google Cloud Run · Azure Container Apps · Terraform · Docker · GitHub Actions · Playwright · JUnit · Testcontainers · MCP

#### Off the keyboard

I'm a potter, which is why so much of my side work involves glazes and kilns. I also run, kayak, and camp.

📫 [LinkedIn](https://www.linkedin.com/in/aaronfilson/)
