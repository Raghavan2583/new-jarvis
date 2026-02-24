# new-Tarviz

# Tarviz-Orchestrator
> **The Engineering Governance & Acceleration Layer for AI-Driven Development**

Tarviz-Orchestrator is a "Meta-Agent" reasoning layer designed to sit between developers and Agentic AI tools (like Claude Code). It ensures that AI-driven development remains disciplined, cost-effective, and 100% aligned with approved architectural designs.

## 🚀 The Mission
To move from "chat-based" trial-and-error coding to **Deterministic AI Engineering.** Tarviz automates the "plumbing" of development so engineers can spend their creative energy on high-level innovation.

## 🛠️ How It Works (The 4-Pillar Model)

### 1. Architectural Fidelity (The "Source of Truth")
Tarviz audits the project’s `final.md` design against **40 Senior Heuristics**. It ensures the AI never ignores, dilutes, or "hallucinates" away from the approved technical roadmap.

### 2. Operational Standardization
Tarviz enforces consistent, professional patterns (security protocols, naming conventions, library choices) across the entire team. 
* **For Juniors:** It acts as a 24/7 Senior Mentor.
* **For Seniors:** It eliminates the need to catch "basic mistakes" in code reviews.

### 3. Context & Cost Optimization
By intelligently partitioning project knowledge into a `.claude/` directory, Tarviz reduces "Context Bloat." This results in **60-80% lower token costs** and significantly faster AI response times.

### 4. The Innovation Escape Hatch
Tarviz is a **Baseline, not a Ceiling.** While it enforces project standards for routine implementation, it includes an "Experiment Mode" where engineers can override rules to prototype new, creative patterns.

## 🔄 The Aligned Workflow

```mermaid
graph TD
    Design[Approved Design .md] --> Tarviz{Tarviz ENGINE}
    Tarviz -->|Audit & Optimize| Context[CLAUDE.md / .claude folder]
    
    User((Developer)) -->|Naive Intent| Tarviz
    Tarviz -->|Expert Prompt + Checklist| User
    
    User -->|Paste & Run| ClaudeCode[Claude Code AI]
    ClaudeCode -->|Writes Code| Draft[New Code]
    Draft -->|Run Tests & Verification| InternalTest{Checklist & Tests Pass?}
 ```

    InternalTest -->|YES| Success[Proceed to Next Task]
    InternalTest -->|NO / Gap| Feedback[Knowledge Loop: Update Tarviz]
    Feedback --> Tarviz
