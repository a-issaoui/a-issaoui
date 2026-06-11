# Hi, I'm Abdelhamid Issaoui 👋

**Software Engineer — AI Infrastructure & Backend Systems**

I build across the stack — from AI retrieval engines and local LLM infrastructure to
high-performance Go systems, HA database clusters, and production web platforms. I like
owning a system end to end: the retrieval algorithm *and* the inference server *and* the
database cluster it runs on. 8+ years of software engineering across backend
systems, SaaS platforms, and infrastructure tools — now focused on AI systems and backend
infrastructure.

📍 Tunisia · Open to Remote (US / Global) · 📧 a.issaoui@aol.co.uk

---

### 🧠 AI Systems

**[coderag](https://github.com/a-issaoui/coderag)** — *scry* · Python
Local-first, multi-language code retrieval. Fuses dense embeddings + BM25 + a structural
code graph via Reciprocal Rank Fusion; framework-aware across 6 languages; MCP-native.

**[llm-inference-server](https://github.com/a-issaoui/llm-inference-server)** — Python · FastAPI
OpenAI-compatible local LLM server for GGUF models: dynamic VRAM management, GPU-first
loading with a serialized request queue, persistent sessions, tool calling, Prometheus metrics.

### ⚙️ Systems / Go

**[tcp-phantom](https://github.com/a-issaoui/tcp-phantom)** — Go
Userspace TCP/IP stack from scratch — handshake state machine, retransmission, options,
checksums — with TLS + HTTP layers and per-OS fingerprint personas.

**[goscrub](https://github.com/a-issaoui/goscrub)** — Go
Low-allocation PII/secret scrubbing: Aho-Corasick prefiltering, pooling, 214 patterns;
allocation-free clean path (~150 ns/op, 0 allocs in benchmarks). Full tests + CI.

**[herolog](https://github.com/a-issaoui/herolog)** — Go
Zero-allocation structured logging for CloudWeGo Hertz — drop-in `hlog` replacement with
Aho-Corasick scrubbing, diode buffering, rotation, Prometheus metrics.

### 🛠️ Infrastructure / DevOps

**[postgres-ha](https://github.com/a-issaoui/postgres-ha)** — Docker / Infra
Self-hosted HA PostgreSQL cluster: `repmgr` streaming replication + auto-failover, `pgpool`
load balancing, `pgbouncer` pooling, per-node Prometheus exporters.

### 🎨 Rendering / Frontend

**[universal-msdf-generator](https://github.com/a-issaoui/universal-msdf-generator)** — TypeScript · WASM · *npm*
MSDF font-asset generator for GPU text rendering — msdfgen→WASM, PixiJS output, Arabic/HarfBuzz shaping.

**[carthage-template](https://github.com/a-issaoui/carthage-template)** — Next.js 16 · React 19 · Tailwind v4
Production-grade marketing-site template: block-based architecture, typed content layer,
first-class SEO (JSON-LD/sitemap/robots). Build-verified.

**[pretext-rendering-stack](https://github.com/a-issaoui/pretext-rendering-stack)** — TypeScript · WebGL
5-layer GPU rendering engine on PixiJS with a React-like Fiber reconciler and Flutter-style layout.

---

### 💼 Client & Product Work

Production platforms delivered through **M3Soft** (architecture · backend · frontend · deployment):

- **Carthage Catering** — catering platform for a Los Angeles client · *Next.js 16 · React 19 · Three.js · GSAP · Supabase*
- **M3Soft** — agency site with 3D hero + full SEO engine · *Next.js 16 · React 19 · Three.js · Framer Motion · Prisma* — [m3soft.tn](https://www.m3soft.tn)
- **Sabra FM** — site + CMS for Tunisia's 3rd-largest radio station · *Nuxt · Laravel* — [radiosabrafm.net](https://www.radiosabrafm.net)
- **IFMS (GTSP)** — fleet-management system for a transport company · *Vue · Laravel* — [ifms.gtsp.tn](https://www.ifms.gtsp.tn)
- **Educasoft** — school-management platform (primary & high school) · *CodeIgniter* — [ennour.madrasa.tn](https://www.ennour.madrasa.tn)
- **Railconcept** (France, via Studio Gazoline) · **PFE.tn** · **BookingRose** (Qatar) — additional Jekyll / Laravel platforms

---

### 🧰 Tech

**Languages:** `Go` · `Python` · `TypeScript` · `JavaScript` · `SQL` · `PHP`
**AI/Systems:** RAG (vector + BM25 + graph) · MCP · embeddings · llama.cpp / GGUF serving · multi-agent
**Backend:** REST · microservices · low-allocation Go · Node.js (Express/Fastify) · Laravel
**Frontend:** Next.js · React 19 · Tailwind · Vue/Nuxt · WebGL (PixiJS/Three.js) · WASM
**Data/Infra:** PostgreSQL (HA: repmgr/pgpool/pgbouncer) · MySQL · MongoDB · Docker · Prometheus/Grafana · Linux

---

### 📫 Reach me

- 📧 **a.issaoui@aol.co.uk**
- 💼 [linkedin.com/in/abdel-issaoui](https://www.linkedin.com/in/abdel-issaoui)
- 🔗 [github.com/a-issaoui](https://github.com/a-issaoui)
