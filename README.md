## Hi, I'm Abhishek 👋

Backend developer and infrastructure tinkerer. I build things end-to-end — from API design to Docker deployment on my own Linux server.

### 🚀 What I've Shipped

- **[PersonalS3](https://personals3.tech)** ([source](https://github.com/personals3)) — Self-hosted S3-compatible object storage with built-in media transcoding. Sign in, drag-drop a video → an FFmpeg worker (VA-API hardware accel) transcodes it to an adaptive HLS ladder in the background, exposes signed share URLs, and streams globally via Cloudflare Tunnel. Ships a cross-platform [`ps3` CLI](https://github.com/personals3/cli), S3 SDK compatibility (boto3 / aws-cli / rclone), self-serve onboarding with 2FA + trusted devices, and [user docs](https://developers.personals3.tech)
- **[gitDeploy](https://gitdeploy.online)** ([source](https://github.com/abhishekabck/git_deploy)) — A self-hosted PaaS built from scratch. Push a GitHub repo URL → it clones, builds a Docker image, allocates a port, configures Nginx, and serves your app at a public subdomain in under 60 seconds. JWT auth, OTP email verification, encrypted per-app secrets sidecar
- **[Portfolio](https://abhishek.gitdeploy.online)** ([source](https://github.com/abhishekabck/PortFolio---GUI)) — Dual-mode portfolio: a real terminal emulator with custom CLI commands + a GUI mode with interactive architecture diagrams. Backed by a FastAPI + SQLite API — deployed on gitDeploy, naturally
- **AI Tender Intelligence** *(FYP)* — NLP pipeline that scrapes government tender portals, extracts structured fields via custom spaCy NER, scores company eligibility, and generates summaries using a local Llama3 model

### 🔧 Stack

`Go` `Python` `FastAPI` `Django` `Next.js` `React` `TypeScript` `PostgreSQL` `Valkey` `Docker` `Nginx` `Cloudflare Tunnel` `FFmpeg` `Linux` `spaCy` `LangChain`

### 📫 Connect

- 🌐 [abhishek.gitdeploy.online](https://abhishek.gitdeploy.online)
- 💼 [linkedin.com/in/abhishekabck](https://linkedin.com/in/abhishekabck)
