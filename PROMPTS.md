# Reusable Prompts

## Cheat Card Prompt

Use this cheat card as a quick reference for the TRIAD-GATE → TASK-GATE protocol:

```
## 🤠 TRIAD-GATE → TASK-GATE — One-Screen Cheat Card

### 🚦 Golden Rule
**Nothing executes without governance.**

---

### 🔐 Phase 1 — Governance
Start every new session with:
```
TRIAD-GATE:START
```

You then define:
- Tasks
- Order
- Permissions (P1–P5)
- Risks (legal, safety, UI limits)

Governance responds with:
```
TRIAD-GATE:LOCKED
...
Handoff:
TRIAD-GATE:EXECUTE
```

Until you see this, **nothing runs**.

---

### ⚙️ Phase 2 — Execution
Begin execution only with:
```
TASK-GATE:START
```

TASK-GATE:
- Executes **only approved tasks**
- Obeys permission limits
- Fails closed on uncertainty
- Returns finished artifacts (not plans)

Continue with:
```
TASK-GATE:CONTINUE
```

---

### 🔑 Permissions
- **P1** Draft / Organize  
- **P2** Web Research  
- **P3** Connected Files / Sources  
- **P4** UI Co-Pilot (GitHub UI, etc.)  
- **P5** Automation / Monitoring  

---

### 🧑‍💻 GitHub Browser Execution (GBE)
If GitHub is involved:
- UI only (no git, no APIs)
- **One repo, one file, one change**
- Fully visible & reversible
- Stop immediately if a button or access is missing

---

### 🦾 Output Contract
Every execution returns:
A) Completed Deliverables  
B) Hybrid Handoffs  
C) Blockers / Permissions Needed  
D) Next Executable Queue

---

**If in doubt: stop.  
If not locked: don’t run.**
```

## Repo Badge Snippet

Use this badge snippet in your README:

```
![TRIAD-GATE Governed](https://img.shields.io/badge/Governance-TRIAD--GATE-blueviolet)
![TASK-GATE Enabled](https://img.shields.io/badge/Execution-TASK--GATE-success)
```

## Contributing Guidelines Prompt

This prompt outlines the contributing guidelines for repositories governed by TRIAD-GATE and TASK-GATE:

```
# Contributing Guidelines

This repository operates under a **governance-first execution model** using  
**TRIAD-GATE v4 → TASK-GATE v2.2**.

No work executes without explicit authorization.

## 🧑‍💻 How Work Happens Here

### Phase 1 — Governance (Required)
All contributions begin with:
```
TRIAD-GATE:START
```

Governance defines:
- Approved tasks
- Execution order
- Risk constraints
- Permission levels (P1–P5)

Until governance is locked, **nothing executes**.

### Phase 2 — Execution
Execution begins only after governance emits:
```
TRIAD-GATE:LOCKED
...
Handoff:
TRIAD-GATE:EXECUTE
```
and is followed by:
```
TASK-GATE:START
```

## 🔑 Permission Levels
- **P1** Drafting, formatting, organizing
- **P2** Web research (citations required)
- **P3** Connected files or sources
- **P4** UI interaction (GitHub Browser Execution)
- **P5** Automation or monitoring

Permissions are explicit.  
If not granted, the system **fails closed**.

## 🧑‍💻 GitHub Browser Execution (GBE)
All GitHub work must:
- Use GitHub.com UI only
- Modify **one file per task**
- Be visible and reversible
- Stop immediately if access is missing

No local git. No APIs. No batch edits.

## ✅ Example: Correct Flow
```
TRIAD-GATE:START

Tasks:
1. Update README governance section

Order:
Sequential

Permissions:
P1, P4

Risks:
Documentation accuracy
GBE enforced
```
→ Governance locks  
→ Execution begins  
→ One file edited  
→ Clear commit message

## ❌ Anti-Patterns
- Editing files before governance
- Executing without permission
- Bundling multiple files in one task
- Guessing UI paths when blocked

## 🔁 Continuing Work
To proceed with approved tasks:
```
TASK-GATE:CONTINUE
```

To add new work:
→ Return to **TRIAD-GATE**

This process ensures safety, clarity, and auditability.
```
