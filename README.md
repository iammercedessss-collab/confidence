# Confidence — The Idea Fortifier

> *"Action breeds confidence and courage."* — Dale Carnegie

Confidence is an architectural AI staging ground for your ideas. It doesn't just applaud your concepts; it stress-tests them, secures their weak points, and builds an execution-ready framework around them. It transforms raw inspiration into resilient, production-ready blueprints.

---

## How it works

Bring any app concept, business hypothesis, system architecture, or strategic plan to Confidence. The AI processes your proposal through three calculated architectural phases every single turn:

- **Fortify** — Reinforces your idea with structural context you might have missed: scalable patterns, deployment strategies, market precedents, or technical considerations.
- **Stress-Test** — Acts as the ultimate devil's advocate, identifying potential choke points, edge cases, hidden technical debt, or market vulnerabilities.
- **Calibrate** — Delivers an actionable optimization step and a sharp structural pivot to advance the design.

A live **Structural Integrity** indicator in the header tracks the robustness of your project (0–100%), dynamically updated by the model's self-assessed confidence score of your current framework.

## Features

- **Dynamic Stress-Testing** — Optimized for technical frameworks, product roadmaps, and business logic.
- **8 Blueprint Starters** — Instant suggestion chips to kickstart project breakdowns across different domains.
- **Tri-Phase Architecture** — Structured Fortify → Stress-Test → Calibrate output pipeline, cleanly parsed and visually separated.
- **Live Integrity Bar** — Active metrics tracking with diagnostic status notes (e.g., *"Analyzing Edge Cases"*, *"Architectural Lock"*).
- **Persistent Memory Core** — Complete multi-turn context tracking across deep system designs.
- **Modular Refactoring** — Instantly shift project directions or spin up new modules without session loss.

## Stack

| Layer | Technology |
|---|---|
| Frontend | Vanilla HTML/CSS/JS, no framework |
| Backend | Node.js + Express |
| AI | Gemini 2.5 Flash via `@google/genai` |
| Build | Vite + TypeScript |
| Styling | Tailwind CSS v4 + custom CSS variables |
| Animation | Motion library |

The API key is securely isolated server-side via `.env` — never exposed to the client.

## Running locally

```bash
# 1. Clone the repo
git clone [https://github.com/yourusername/confidence.git](https://github.com/yourusername/confidence.git)
cd confidence

# 2. Install dependencies
npm install

# 3. Secure your environment
cp .env.example .env
# Edit .env and inject your key: GEMINI_API_KEY=your_key_here

# 4. Fire up the development engine
npm run dev