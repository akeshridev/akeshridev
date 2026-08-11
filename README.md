# Hi, I'm Ashish Prasad Keshri 👋

Android Engineer (15y) exploring On-Device AI

15 years building consumer mobile platforms at scale, and — more recently — the
production-grade AI agent systems that help engineering teams ship faster. I've spent my
career at the intersection of native Android architecture and applied AI, most recently
leading the AI-native engineering transformation for a 100+ engineer mobile org at OKX.

📧 [akeshridev@gmail.com](mailto:akeshridev@gmail.com)

---

### 🔭 What I'm building right now

**[Vault Mind](https://github.com/akeshridev/on-device-rag-android)** — a fully offline,
privacy-first "chat with your documents" Android app. Add a PDF, ask questions, get answers
grounded in and cited to the actual pages — with **zero data ever leaving the device**.

- Gemma 3 1B for generation, via Google's LiteRT-LM
- MediaPipe Text Embedder + ObjectBox's HNSW vector index for on-device retrieval
- Hybrid vector + keyword search, built after live testing exposed real gaps in pure
  embedding-based retrieval — not theory, actual wrong-answer debugging against real PDFs
- Kotlin, Jetpack Compose, Room, PdfBox-Android

### ⚡ Selected impact

- **OKX** — Designed and shipped an autonomous AI release-testing agent (MCP server + LLMs
  + UIAutomator) that cut 20+ manual engineer-hours per release cycle. Led platform-wide
  adoption of LLM-assisted development (Claude, Cursor) across 100+ mobile engineers,
  cutting PR cycle times by 30%. Built an LLM-powered PR review suite catching memory leaks,
  main-thread blocks, and ANR risks, plus a Logcat PII scanner that caught 3 critical
  pre-production data leaks.
- **DoorDash** — Built a customer self-service Chatbot SDK from scratch on Sendbird
  infrastructure, leading a 6-engineer squad to ship 2 weeks ahead of schedule and deliver
  multi-million dollar operational savings.
- **Groupon** — Decomposed a legacy transactional checkout monolith into modular
  Kotlin/MVI components, cutting build times by 35%.
- **CSG Ascendon** — Architected an enterprise white-label Android media SDK (ExoPlayer,
  Chromecast V3, adaptive DASH streaming) deployed across DisneyLife, Redbox, and Paramount.

### 🧰 Core expertise

**AI & LLM Architecture**
Agentic workflows (Think-Act-Observe) · MCP (Model Context Protocol) · Claude API · Prompt
engineering · Autonomous testing agents · On-device AI

**Android & Mobile**
Kotlin · Jetpack Compose · Coroutines/Flow · Kotlin Multiplatform (KMP) · Clean Architecture ·
MVVM/MVI · UDF

**Platform & Delivery**
CI/CD (GitHub Actions, Fastlane) · Strategic modularization · SDK development · Payments &
fintech systems (Google Pay, PayPal, crypto wallets) · Distributed global team leadership

---

<p align="left">
  <img src="https://skillicons.dev/icons?i=kotlin,androidstudio,compose,java,git,github,githubactions,gradle,py" alt="Skills" />
</p>

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=akeshridev&show_icons=true&theme=default&hide_title=false" alt="GitHub stats" height="165" />
</p>
