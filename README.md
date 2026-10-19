### Hi, I'm Aaron 👋

Senior full stack engineer in Tacoma, WA. I build production web apps in **Java/Spring Boot**, **Angular**, and **TypeScript/Node**, and I run them on **AWS** and **Google Cloud**. I'm open to remote senior engineering roles.

Most recently I was a Senior Software Engineer at Buyers Edge Platform on **Back Office**, a restaurant operations and accounting SaaS used by 4,000+ restaurants. There I designed the data model that turns POS data from about 25 systems into accounting views operators can trust.

#### What I'm building

- **[Glazecalc](https://glazecalcapp.com)** ([repo](https://github.com/AaronFilson/glazecalc)): a free glaze chemistry calculator for potters. I revived a 2017 AngularJS app as a maintained product:
  - **Stack:** Angular 22, a TypeScript Node 24/Express 5 API, and MongoDB.
  - **Languages:** translated into 32 languages: an official language for every EU country, plus Japanese, Korean, Chinese, Thai, Vietnamese, Indonesian, and Turkish.
  - **AI assistants:** an [MCP server](https://glazecalcapp.com/mcp), listed in the [MCP Registry](https://registry.modelcontextprotocol.io/v0/servers?search=com.glazecalcapp/glazecalc) as `com.glazecalcapp/glazecalc`, so Claude, Copilot, Cursor, and Gemini can run the chemistry. Your own recipes are reachable only with read-only personal access tokens you can revoke.
  - **Security:** Google and GitHub sign-in (OAuth 2.0/OIDC with PKCE), plus optional two-step sign-in with passkeys, authenticator apps, and recovery codes.
  - **Quality:** 1,800+ automated tests, Lighthouse 99/100, and a 204-entry materials library sourced from manufacturers' data sheets.
  - **Deploys:** keyless, approval-gated deploys to EC2, with staging and automatic rollback, for about $13 a month.
  - **Docs:** read the [case study](https://github.com/AaronFilson/glazecalc/blob/master/docs/case-study.md) and the [decision records](https://github.com/AaronFilson/glazecalc/tree/master/docs/adr).
- **[Updraft Pottery Studio](https://updraftpotterystudio.com)** ([repo](https://github.com/AaronFilson/updraftwebsite)): a live shop for a Tacoma ceramics studio that takes real Square payments.
  - **Front end:** a fast static site with its own image pipeline.
  - **Shop:** serverless Lambda APIs with stock-aware checkout. In a load test, 12 simultaneous buyers tried for one piece and exactly one was charged.
  - **Infrastructure:** S3 and CloudFront defined as code, with staging and production stages.
- **[Glaze Vault](https://github.com/AaronFilson/glaze-vault)** (early development): an encrypted desktop app for studios with proprietary glaze recipes, with teams and roles, built with Tauri 2, a Rust core (SQLCipher, Argon2id), and React 19.
- **[Omnifilter](https://omnifilter-3uthre4zva-uc.a.run.app)** ([repo](https://github.com/AaronFilson/omnifilter)): a 2016 team project I revived as a GPU photo-filter app, live on Google Cloud Run. It has OpenCL kernels in a C++ Node addon, a WebGPU backend, and live in-browser previews, even on the camera.

#### How I work with AI

I use Claude Code every day as a directed coding agent, with guardrails:

- Plans and decision records come before code.
- Security-sensitive work gets an adversarial review.
- Every change runs through tests and CI gates (CodeQL, axe, Lighthouse) before an approved deploy.

I've also built AI agents at company hackathons.

#### Tools I use

Java · Spring Boot · Hibernate · Angular · React · TypeScript · Node.js · Rust · MySQL · PostgreSQL · MongoDB · Redis · AWS (EC2, S3, Lambda, CloudFront, CloudFormation/SAM) · Google Cloud Run · Docker · GitHub Actions · Playwright · JUnit · MCP

#### Off the keyboard

I'm a potter, which is why so much of my side work involves glazes and kilns. I also run, kayak, and camp.

📫 [LinkedIn](https://www.linkedin.com/in/aaronfilson/)
