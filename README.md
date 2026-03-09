# Great Product Skills

A collection of Cursor agent skills for a full-cycle product development workflow — from ideation to interactive prototype.

## Overview

**`product-team`** is the orchestrator skill that acts as an AI Team Lead (codename: Seven / 阿七), driving a product from fuzzy idea to polished demo through four phases:

```
Phase 1: Product Discussion  →  Phase 2: Write Spec  →  Phase 3: Build Demo  →  Phase 4: UX Walkthrough
       [pm-debate]              [spec-generate]        [frontend-design]        [ux-walkthrough]
                                                       [web-artifacts-builder]
```

## Skills

| Skill | Purpose |
|-------|---------|
| **product-team** | Orchestrator — full-cycle product development workflow with project management |
| **pm-debate** | High-quality product discussion as a senior PM sparring partner |
| **spec-generate** | Structured PRD generation with step-by-step workflow |
| **frontend-design** | Production-grade frontend UI implementation |
| **web-artifacts-builder** | Multi-component React artifacts with shadcn/ui |
| **ux-walkthrough** | Systematic UX expert review and issue reporting |
| **doc-coauthoring** | Collaborative documentation writing workflow |

## Installation

Copy the skill directories into your project's `.cursor/skills/` folder:

```bash
cp -r skills/* /path/to/your-project/.cursor/skills/
```

## Usage

Trigger the product-team skill in Cursor with keywords like:

- "产研团队" / "team lead" / "阿七" / "seven"
- "从想法到 demo" / "全流程" / "帮我推进"

Or enter any phase directly:

| Say | Starts at |
|-----|-----------|
| "聊聊这个方向" | Phase 1 — Product Discussion |
| "帮我写个 spec" | Phase 2 — Write Spec |
| "做个 demo 看看" | Phase 3 — Build Demo |
| "走查一下这个" | Phase 4 — UX Walkthrough |

## License

Individual skills may contain their own LICENSE files. See each skill directory for details.
