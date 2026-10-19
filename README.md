# Richard Ewing

**Architect of [Exogram.ai](https://exogram.ai)** · **Founder & CEO at [CareerWin.ai](https://careerwin.ai)** · **Author of [The AI Economist](https://theaieconomist.beehiiv.com)**

[![Exogram Live Workspace](https://img.shields.io/badge/Exogram_AI-Personal_Neural_Network_%26_Living_Tiles-4C2B4B?style=for-the-badge)](https://exogram.ai/dashboard/chat)
[![Exogram Open-Core SDK](https://img.shields.io/badge/Python_%26_TS_SDK-exogram--sdk-2563eb?style=for-the-badge)](https://github.com/Richard-Ewing/exogram-sdk)
[![CareerWin AI](https://img.shields.io/badge/CareerWin.ai-Open_World_Career_%26_ATS_Engine-0f172a?style=for-the-badge)](https://careerwin.ai)
[![Shadow ATS Piercer](https://img.shields.io/badge/NPM-shadow--ats--piercer-10b981?style=for-the-badge)](https://github.com/Richard-Ewing/shadow-ats-piercer)
[![Adversarial Council](https://img.shields.io/badge/Multi--Agent-adversarial--council-ea580c?style=for-the-badge)](https://github.com/Richard-Ewing/adversarial-council)
[![CareerWin MCP](https://img.shields.io/badge/MCP-careerwin--mcp-4f46e5?style=for-the-badge)](https://github.com/Richard-Ewing/careerwin-mcp)

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

### 2. Flagship Architecture: [CareerWin.ai](https://careerwin.ai) — Open-World Career Compiler, 4-Seat Adversarial Hiring Committee & 380ms ATS Piercer

Generic AI resume tools wrap a single prompt around a candidate's file, invent unverified metrics, default every non-tech worker to SaaS buzzwords, and fail silently when browser scripts try to autofill React 18 or Workday Shadow-DOM forms.

**[CareerWin.ai](https://careerwin.ai)** (`v0.2.243` Web | `v5.1.83` Extension) is an evidence-grounded career compilation and ATS execution engine covering all **23 major O\*NET 31.0 and ESCO v1.2.1 occupational families**:

```text
┌──────────────────────────────────────────────────────────────────────────────────────┐
│ 1. OPEN-WORLD 7-PRIMITIVE OCCUPATION ENGINE & 5D EPISTEMIC GRAPH (O*NET 31 / ESCO)   │
│    • 7 Work Primitives: Activities · Decisions · Tools · Constraints · Scope         │
│      Outcomes · Non-Substitutable Statutory Gates (RN, CPA, Red Seal, PE, TS/SCI)    │
│    • 5D Epistemic Schema + Expected Information Value (EIV) Smart Interview Ranker   │
└──────────────────────────────────────────┬───────────────────────────────────────────┘
                                           │ Pre-LLM AST Claim-to-Slot Allocation
                                           ▼
┌──────────────────────────────────────────────────────────────────────────────────────┐
│ 2. SECS HALLUCINATION FIREWALL & 4-SEAT ADVERSARIAL HIRING COMMITTEE (2ms Gate)      │
│    • SECS Grounding Validator (0% Unverified Employer/Credential/Metric Fabrication) │
│    • 4-Seat Blind Committee: Recruiter · Hiring Manager · Bar Raiser · Comp Chair    │
│    • <60% Jaccard Echo-Chamber Gate + [ANCHORED] Tags + FLIP Falsifiability Triggers │
└──────────────────────────────────────────┬───────────────────────────────────────────┘
                                           │ 4-Gatekeeper Deterministic Verification
                                           ▼
┌──────────────────────────────────────────────────────────────────────────────────────┐
│ 3. 5-SURFACE OPPORTUNITY KITS & 380ms SHADOW-DOM / REACT 18 FIBER ATS PIERCER        │
│    • 5-Surface Kit: Vector PDF · True OOXML .docx · Cover Letter · Outreach · Q&A    │
│    • Pierces 4-Level Workday ShadowRoots + Resets React 18 Fiber _valueTracker       │
│    • 5-Point Bedrock Employment Anchor Gate (Zero False-Positive Page Injection)     │
└──────────────────────────────────────────┴───────────────────────────────────────────┘
```

#### Core Engineering Pillars
* **Open-World 23-SOC Occupational Engine (`ONET_31_0_ESCO_1_2_1`)**: Decomposes any role—from Trauma ICU Registered Nurses and Commercial Master Electricians to Staff Distributed Systems Engineers and Public Accounting CPAs—into 7 work primitives with `0.0%` Product Management fallback bias (`45/45` benchmark checks passed).
* **Behind-Closed-Doors 4-Seat Adversarial Hiring Committee (`ADR-0025`)**: Evaluates candidates across 4 independent seats (`Recruiter Gatekeeper`, `Hiring Manager`, `Bar Raiser`, `Compensation Chair`) enforced by a `2ms` zero-token Jaccard anti-sycophancy audit, `[ANCHORED]` epistemic tags, `FLIP:` falsifiability conditions, and a 3-Form Ruling (`APPLY_NOW`, `APPLY_ONLY_IF`, `DO_NOT_APPLY`).
* **Pre-LLM AST Compiler & SECS Grounding Firewall (`ADR-0024`)**: Routes all 4 platform surfaces through `CanonicalResumeSchema` and the 4-tier Gemini cascade router (`2.5-flash` -> `2.5-pro` -> `2.5-flash-lite` -> `2.0-flash`), generating single-column vector PDFs and authentic OOXML `.docx` (`PK\x03\x04`) files.
* **Universal Shadow-DOM & React 18 Fiber ATS Piercer (`v5.1.83`)**: Recursively traverses nested `ShadowRoot` trees across Workday, Greenhouse, Lever, Ashby, iCIMS, and SmartRecruiters, invokes native `HTMLInputElement.prototype.value` setters, and resets React's internal `_valueTracker` so synthetic inputs never wipe on form submission.

🚀 **Explore CareerWin & Open-Source Packages:**
* **Live Platform & 10-Stage Interactive Tour:** **[careerwin.ai](https://careerwin.ai)** · **[careerwin.ai/how-it-works](https://careerwin.ai/how-it-works)**
* **Architecture & Visual Showcase Repo:** **[Richard-Ewing/careerwin](https://github.com/Richard-Ewing/careerwin)**
* **Shadow-DOM & React 18 Fiber ATS Piercer (`npx shadow-ats-piercer`):** **[Richard-Ewing/shadow-ats-piercer](https://github.com/Richard-Ewing/shadow-ats-piercer)**
* **Zero-Token Multi-Agent Anti-Sycophancy Auditor (`npx adversarial-council`):** **[Richard-Ewing/adversarial-council](https://github.com/Richard-Ewing/adversarial-council)**
* **Model Context Protocol Server (`npx careerwin-mcp`):** **[Richard-Ewing/careerwin-mcp](https://github.com/Richard-Ewing/careerwin-mcp)**

---

### 3. Open Specifications, SDKs & Research

| Repository / Publication | Focus Area | Link |
| :--- | :--- | :--- |
| **`careerwin`** | Architecture showcase, 10-stage product visual walkthrough, O\*NET 31.0 / ESCO v1.2.1 7-Primitive Career Engine & 4-Gatekeeper benchmarks. | [GitHub Repo](https://github.com/Richard-Ewing/careerwin) |
| **`shadow-ats-piercer`** | Zero-dependency Shadow-DOM traversal, React 18/19 Fiber `_valueTracker` bypass, and 5-Point ATS Employment Anchor detector (`npx shadow-ats-piercer`). | [GitHub Repo](https://github.com/Richard-Ewing/shadow-ats-piercer) |
| **`adversarial-council`** | `2ms` zero-token anti-sycophancy deliberation protocol for multi-agent LLM swarms (`<60%` Jaccard gate, `FLIP:` triggers, 3-Form Rulings). | [GitHub Repo](https://github.com/Richard-Ewing/adversarial-council) |
| **`careerwin-mcp`** | Model Context Protocol (MCP) server for Claude Desktop, Cursor, and Antigravity (`resolve_occupation_primitives`, `audit_ats_gatekeepers`, `simulate_hiring_committee`). | [GitHub Repo](https://github.com/Richard-Ewing/careerwin-mcp) |
| **`exogram-sdk`** | Official Python SDK (`pip install exogram`), TypeScript SDK & FastMCP Server (`uvx mcp-server-exogram --local` SQLite WAL + Cloud). | [GitHub Repo](https://github.com/Richard-Ewing/exogram-sdk) |
| **`exogram-protocol-rfc`** | `RFC-0001`: Open specification for Infinite-Hop Personal Neural Networks, Two-Tier Privacy Routing, A2UI Living Tiles, and Instinct Action Governance. | [GitHub Repo](https://github.com/Richard-Ewing/exogram-protocol-rfc) |
| **The Negative Carry Code Crisis** | Economic teardown of how unverified AI code generation accelerates enterprise technical debt. | [Read Paper](https://exogram.ai/blog/negative-carry-code-crisis) |
| **The Verification Penalty** | Why probabilistic LLM-as-a-Judge guardrails fail in production and how deterministic state-hash gates solve it. | [Read Paper](https://exogram.ai/blog/the-verification-penalty) |
| **The AI Economist** | Weekly analysis on agent systems, compute economics, and software incentives. | [Substack / Beehiiv](https://theaieconomist.beehiiv.com) |

---

### Connect

* **CareerWin Platform**: [careerwin.ai](https://careerwin.ai)
* **Exogram Workspace**: [exogram.ai](https://exogram.ai)
* **Personal Site**: [richardewing.io](https://www.richardewing.io)
* **LinkedIn**: [linkedin.com/in/richard-ewing-mba](https://www.linkedin.com/in/richard-ewing-mba)
* **Columns**: [BuiltIn Contributor](https://builtin.com/authors/richard-ewing) · [CIO.com Author](https://www.cio.com/author/richard-ewing/)
* **X / Twitter**: [@CareerWinAI](https://x.com/CareerWinAI)
