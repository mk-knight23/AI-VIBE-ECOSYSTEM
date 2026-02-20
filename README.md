# 🌐 AI-VIBE-ECOSYSTEM

<p align="center">
  <img src="https://img.shields.io/badge/AI--VIBE-MASTER--HUB-black?style=for-the-badge&logo=github&logoColor=white" alt="AI Vibe Ecosystem">
  <br>
  <b>The definitive collection of autonomous agents, modern chat interfaces, and intelligent automation tools.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Projects-10-blueviolet" alt="10 Projects">
  <img src="https://img.shields.io/badge/LLMs-30+-ff69b4" alt="30+ LLMs Supported">
  <img src="https://img.shields.io/badge/Frameworks-Nuxt--Next--Svelte--Python-orange" alt="Frameworks">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License: MIT">
</p>

---

## 🗺️ Ecosystem Navigation

- [🤖 AI Automation](#-ai-automation-agents)
- [💬 AI Chat Interfaces](#-ai-chat-interfaces)
- [💻 AI CLI Tools](#-ai-cli-tools)
- [🏗️ AI Website & App Builders](#%EF%B8%8F-ai-website--app-builders)
- [🚀 Quick Start](#-global-quick-start)

---

## 🤖 AI Automation Agents

Automating workflows with multi-agent orchestration and drag-and-drop simplicity.

### 1. [Agentify (V1)](../AI-VIBE-AUTOMATION-V1)
**Tagline:** Modern AI workflow automation platform with drag-and-drop simplicity.
**Tech:** `Next.js 15` • `Inngest` • `React Flow` • `Prisma`

<details>
<summary>Technical Deep Dive</summary>

- **Features**: Visual Flow Builder, Multi-Provider AI (OpenAI, Anthropic, Gemini), Background Jobs, Arcjet Security.
- **Project Structure**: App Router based, Server Actions for workflows.
- **Node Types**: Start, AI, API, If/Else, Loop, Code, Delay.
</details>

### 2. [n8n-Clone (V2)](../AI-VIBE-AUTOMATION-V2)
**Tagline:** Scalable, type-safe workflow automation engine inspired by n8n.
**Tech:** `Next.js 15` • `tRPC` • `React 19` • `Prisma`

<details>
<summary>Technical Deep Dive</summary>

- **Features**: Type-safe API layer, Radix UI, Workflow Engine with JSON connections.
- **Architecture**: Unified API layer via tRPC, persistent session management via Better Auth.
- **Optimizations**: React Query caching, static generation for dashboard.
</details>

---

## 💬 AI Chat Interfaces

A diverse range of chat experiences from high-performance frameworks to unique AI personalities.

### 3. [Nuxt-3 Chat (V1)](../AI-VIBE-CHAT-V1)
**Tagline:** Feature-rich AI chat built with Nuxt 3 and Naive UI.
**Tech:** `Nuxt 3.11` • `Vue 3.4` • `Pinia` • `Naive UI`

<details>
<summary>Technical Deep Dive</summary>

- **Features**: AES-GCM Encryption, Glassmorphism UI, Server-side API Proxy.
- **Stabilization**: Fully stabilized Nuxt 3 stack with PERSISTED encrypted stores.
- **Security**: Hidden API keys on server-side Nitro routes.
</details>

### 4. [Svelte-5 Chat (V2)](../AI-VIBE-CHAT-V2)
**Tagline:** High-performance AI chat interface inspired by ChatGPT.
**Tech:** `SvelteKit 5` • `Tailwind CSS 4` • `TypeScript`

<details>
<summary>Technical Deep Dive</summary>

- **Architecture**: Minimal, high-performance Svelte 5 implementation.
- **Focus**: UI/UX speed and developer experience with the latest Svelte and Tailwind versions.
</details>

### 5. [Funny-Formal AI (V3)](../AI-VIBE-CHAT-V3)
**Tagline:** Where Bureaucracy Meets Comedy! A delightfully formal AI.
**Tech:** `Next.js 15` • `React 19` • `Groq` • `Tailwind 4`

<details>
<summary>Technical Deep Dive</summary>

- **Experience**: 16 unique personalities, 30+ AI models (Groq, OpenRouter, Routeway).
- **Security**: Zod validation, rate limiting, secure local storage history.
- **Magic**: Lightning-fast inference via Groq, streaming responses.
</details>

### 6. [AI Provider Dashboard (V4)](../AI-VIBE-CHAT-V4)
**Tagline:** AI API Provider showcase and benchmarking dashboard.
**Tech:** `Next.js 15` • `Recharts` • `Zustand` • `Tailwind`

<details>
<summary>Technical Deep Dive</summary>

- **Tools**: Pricing Calculator, Benchmarks Dashboard, API Playground (Mocked).
- **Data**: Detailed info for 30+ providers (Anthropic, DeepSeek, Google, etc.).
- **Security**: CSP headers, environment variable validation, no client-side API keys.
</details>

---

## 💻 AI CLI Tools

Powerful terminal assistants for autonomous development and system management.

### 7. [Friday CLI (Python)](../AI-VIBE-CLI-PYTHON)
**Tagline:** Enterprise-grade autonomous AI coding assistant.
**Tech:** `Python 3.10+` • `OpenAI` • `Docker` • `PostgreSQL`

<details>
<summary>Technical Deep Dive</summary>

- **Features**: 16+ Built-in Tools, .claude/ folder integration, Autonomous Mode.
- **Security**: Secret Scrubbing, Approval Policies, Dangerous Command Detection.
- **Resilience**: Circuit Breakers, structured audit logging.
</details>

### 8. [VIBE CLI (TypeScript)](../AI-VIBE-CLI-TypeScript)
**Tagline:** Opinionated AI development tool using an 8-primitives architecture.
**Tech:** `TypeScript` • `Node.js 20` • `MCP` • `SQLite`

<details>
<summary>Technical Deep Dive</summary>

- **Primitives**: Planning, Completion, Execution, MultiEdit, Approval, Memory, Search, Orchestration.
- **MCP**: Built on Model Context Protocol for extensible context integration.
- **Plugins**: Community-driven plugin system for scaffold, test, and fix.
</details>

---

## 🏗️ AI Website & App Builders

Generating production-ready code from natural language prompts.

### 9. [Website Builder V1](../AI-VIBE-WEBSITE-BUILDER-V1)
**Tagline:** Build stunning websites with AI in seconds using real-time streaming.
**Tech:** `Next.js 15` • `Prisma` • `Clerk` • `tRPC`

<details>
<summary>Technical Deep Dive</summary>

- **Magic**: Multi-provider streaming (OpenRouter, Routeway, MegaLLM).
- **Sandbox**: E2B Code Interpreter integration for safe execution.
- **Workflow**: Auto-generator hook for real-time live preview.
</details>

### 10. [VibeDesign V2](../AI-VIBE-WEBSITE-BUILDER-V2)
**Tagline:** AI-powered platform to design and prototype mobile apps.
**Tech:** `Next.js 16` • `XYFlow` • `Minimax AI` • `Clerk`

<details>
<summary>Technical Deep Dive</summary>

- **Features**: Draggable Flow Canvas, Realistic Device Mockups, PNG Export.
- **AI**: Prompt-to-UI generation using Minimax AI + Vercel AI SDK.
- **Architecture**: Infinite workspace powered by XYFlow (React Flow).
</details>

---

## 🚀 Global Quick Start

The VIBE ecosystem is designed for rapid deployment and experimentation.

### 1. General Setup
Most projects follow the standard Next.js sequence:
```bash
git clone https://github.com/mk-knight23/AI-VIBE-ECOSYSTEM.git
# Navigate to a specific project directory
cd AI-VIBE-CHAT-V3
npm install
cp .env.example .env.local
npm run dev
```

### 2. API Configuration
Common environment variables required across the ecosystem:
- `ANTHROPIC_API_KEY`
- `OPENAI_API_KEY`
- `GROQ_API_KEY`
- `DATABASE_URL` (PostgreSQL)

---

<p align="center">
  <b>Managed by AI-VIBE-ECOSYSTEM</b><br>
  <i>Built with ❤️ to push the boundaries of AI-driven development.</i>
</p>
