# Richard Ewing

**Architect of [Exogram.ai](https://exogram.ai)** · **Founder & CEO at [CareerWin.ai](https://careerwin.ai)** · **Author of [The AI Economist](https://theaieconomist.beehiiv.com)**

[![Exogram Live Workspace](https://img.shields.io/badge/Exogram_AI-Personal_Neural_Network_%26_Living_Tiles-4C2B4B?style=for-the-badge)](https://exogram.ai/dashboard/chat)
[![Exogram Open-Core SDK](https://img.shields.io/badge/Python_%26_TS_SDK-exogram--sdk-2563eb?style=for-the-badge)](https://github.com/Richard-Ewing/exogram-sdk)
[![Exogram Protocol RFC](https://img.shields.io/badge/Specification-exogram--protocol--rfc-059669?style=for-the-badge)](https://github.com/Richard-Ewing/exogram-protocol-rfc)
[![CareerWin AI](https://img.shields.io/badge/CareerWin.ai-ATS_Intelligence-201B20?style=for-the-badge)](https://careerwin.ai)

---

### 1. Flagship Architecture: [Exogram.ai](https://exogram.ai) — The Personal Neural Network & Governed AI Workspace

Standard conversational AI assistants wake up with total amnesia on every new chat, dump walls of static Markdown instead of executing real work, and lack cryptographic isolation between private personal context and public tool calls.

**[Exogram](https://exogram.ai)** (Master Plan v5) is a personal intelligence and work-execution operating system powered by an **Infinite-Hop Personal Neural Network (`Work · People · Life`)**, a **Two-Tier Privacy Gateway**, **A2UI Composable Living Tiles**, and **0.07ms Instinct Action Governance**:

```text
┌──────────────────────────────────────────────────────────────────────────────────────┐
│ 1. INFINITE-HOP PERSONAL NEURAL NETWORK (Work · People · Life Spheres)               │
│    • Infinite-Hop Associative Spreading Activation (decay=0.72, 1/√deg hub damping)  │
│    • HippoRAG 2 Spectral Personalized PageRank (D⁻¹/² A D⁻¹/²) + 4-Way RRF (k=60)    │
│    • 3-Horizon Episodic Memory (36h TTL · RRULE:FREQ=YEARLY · durable_trait) + Undo  │
└──────────────────────────────────────────┬───────────────────────────────────────────┘
                                           │ Laya <15ms Deterministic Fast-Path
                                           ▼
┌──────────────────────────────────────────────────────────────────────────────────────┐
│ 2. TWO-TIER INFERENCE GATEWAY & 6 HONEST FIRST-PARTY KERNELS                         │
│    • PERSONAL -> Paid Gemini 3.8 Flash / 2.5 Pro (Zero Data Retention)               │
│    • PUBLIC_ONLY -> stripVaultAndPiiFromPublicSubtask + Multi-Lab Free Pool          │
│    • 6 Honest Kernels: Neural Graph · Generative UI · Live Web & Places Scout        │
│      Action & Draft · Analytical Synthesis · Grounded Citation (Complete · Cited)    │
└──────────────────────────────────────────┬───────────────────────────────────────────┘
                                           │ 8-12 Semantic Tools + AG-UI JSON Patching
                                           ▼
┌──────────────────────────────────────────────────────────────────────────────────────┐
│ 3. A2UI COMPOSABLE LIVING TILES & 0.07ms INSTINCT ACTION GOVERNANCE                  │
│    • Living Tiles: Editorial SVG Diagrams · HyperFrames 30fps Video · Instinct       │
│      Operator · action_draft · checklist · decision_matrix · curated_places · Undo   │
│    • Instinct Pre-Mutation Gate + [Approve Step] / [Take Over] + SHA-256 C_tok       │
└──────────────────────────────────────────┴───────────────────────────────────────────┘
```

#### Core Engineering Pillars
* **Infinite-Hop Personal Neural Network + HippoRAG 2 PPR**: Traverses multi-hop connections across `Work`, `People`, and `Life` using associative spreading activation ($\text{decay}=0.72$, $1/\sqrt{\text{deg}}$ hub damping), spectral Personalized PageRank ($D^{-1/2} A D^{-1/2}$), 3-Horizon Episodic Memory TTLs, Read-Time Scalar Conflict Supersession, and 1-click rollback via `/api/memory/undo`.
* **Two-Tier Inference Gateway (`PERSONAL` vs. `PUBLIC_ONLY`) & Laya `<15ms` Preflight**: Resolves vault entities and sphere affinity in `<15ms` in-memory (`<= 1.6s` P50 TTFT). Routes `PERSONAL` subtasks exclusively to zero-retention Paid Gemini 3.8 Flash / 2.5 Pro while sanitizing `PUBLIC_ONLY` subtasks via `stripVaultAndPiiFromPublicSubtask`.
* **6 Honest First-Party Kernels & 8–12 Semantic Tool Selector**: Dispatches `Neural Graph Kernel`, `Generative UI Kernel`, `Live Web & Places Scout`, `Action & Draft Kernel`, `Analytical Synthesis Kernel`, and `Grounded Citation Kernel` over `<= 12` semantically matched tools wrapped in `provenance.untrusted_content`, verifying every citation post-synthesis (`verifyAgentContributionsAgainstTurnOutput`).
* **A2UI Composable Living Tiles & Instinct Operator (`0.07ms`)**: Renders schema-validated Living Tiles—including **Editorial Plum Mineral SVG Diagrams** (`branded_diagram_tile`), **HyperFrames 30fps Video Briefings** (`hyperframes_video_tile`), and the **Instinct Autonomous Operator** (`instinct_computer_tile`)—governed by `evaluateInstinctPreMutationGate`, `Household` vs. `Work` A2A boundaries, `[Approve Step]` / `[Take Over]` sentinel controls, and SHA-256 state-hash tokens ($C_{tok}$).

🚀 **Try it now:**
* **Live AI Workspace:** **[exogram.ai/dashboard/chat](https://exogram.ai/dashboard/chat)**
* **Python/TS SDK & FastMCP Server (`pip install exogram` / `uvx mcp-server-exogram --local`):** **[Richard-Ewing/exogram-sdk](https://github.com/Richard-Ewing/exogram-sdk)**
* **Open Architecture Specification (`RFC-0001`):** **[Richard-Ewing/exogram-protocol-rfc](https://github.com/Richard-Ewing/exogram-protocol-rfc)**

---

### 2. [CareerWin.ai](https://careerwin.ai) — Authentic Career Intelligence & ATS Engine

I build software that closes the gap between raw human capability and algorithmic gatekeepers. **[CareerWin.ai](https://careerwin.ai)** anchors candidate applications to a verified Master Work Record, strips out synthetic AI resume clichés, and automates enterprise ATS portals (Workday, Greenhouse, Lever, iCIMS, Taleo) in 380ms.

* 🛠️ **[Real-Time ATS Resume Scanner](https://careerwin.ai/tools/ats-resume-scanner)** — Audit resumes against real enterprise parser benchmarks.
* 🚫 **[47 Banned AI Resume Words](https://careerwin.ai/no-ai-buzzwords)** — The exact vocabulary that flags applications as automated spam.
* 📐 **[Product Manager Altitude Scorer](https://careerwin.ai/tools/pm-altitude-scorer)** — Measure whether your portfolio reflects tactical execution or executive strategy.
* 🧩 **[CareerWin Chrome Extension](https://chromewebstore.google.com/detail/careerwin-ai-job-applicat/hndikjplphkgdhlkhhflflmfeefkgeaa)** — 1-click tailored application pack generator and DOM autofill.

---

### 3. Open Specifications, SDKs & Research

| Repository / Publication | Focus Area | Link |
| :--- | :--- | :--- |
| **`exogram-sdk`** | Official Python SDK (`pip install exogram`), TypeScript SDK & FastMCP Server (`uvx mcp-server-exogram --local` SQLite WAL + Cloud). | [GitHub Repo](https://github.com/Richard-Ewing/exogram-sdk) |
| **`exogram-protocol-rfc`** | `RFC-0001`: Open specification for Infinite-Hop Personal Neural Networks, Two-Tier Privacy Routing, A2UI Living Tiles, and Instinct Action Governance. | [GitHub Repo](https://github.com/Richard-Ewing/exogram-protocol-rfc) |
| **The Negative Carry Code Crisis** | Economic teardown of how unverified AI code generation accelerates enterprise technical debt. | [Read Paper](https://exogram.ai/blog/negative-carry-code-crisis) |
| **The Verification Penalty** | Why probabilistic LLM-as-a-Judge guardrails fail in production and how deterministic state-hash gates solve it. | [Read Paper](https://exogram.ai/blog/the-verification-penalty) |
| **The AI Economist** | Weekly analysis on agent systems, compute economics, and software incentives. | [Substack / Beehiiv](https://theaieconomist.beehiiv.com) |

---

### Connect

* **Exogram Workspace**: [exogram.ai](https://exogram.ai)
* **Personal Site**: [richardewing.io](https://www.richardewing.io)
* **LinkedIn**: [linkedin.com/in/richard-ewing-mba](https://www.linkedin.com/in/richard-ewing-mba)
* **Columns**: [BuiltIn Contributor](https://builtin.com/authors/richard-ewing) · [CIO.com Author](https://www.cio.com/author/richard-ewing/)
* **X / Twitter**: [@CareerWinAI](https://x.com/CareerWinAI)
