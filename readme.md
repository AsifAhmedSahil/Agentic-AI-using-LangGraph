# Agentic AI

> A complete guide to understanding Agentic AI — perfect for interview preparation.

---

## What is Agentic AI?

Agentic AI refers to AI systems that can **act on their own** to achieve goals. Unlike simple AI that just responds to inputs, Agentic AI can make decisions, use tools, plan ahead, and learn from feedback.

---

## Key Characteristics

### 1. Autonomous

The agent can make decisions and take actions on its own. It is **proactive** (doesn't wait for instructions).

**How autonomy is controlled:**
- Permission scope (what it is allowed to do)
- Human in the loop (HITL) — a human approves important actions
- Override controls (a human can stop or change its action)
- Guardrails (rules it cannot break)

### 2. Goal Oriented

The agent continuously works toward a specific goal.

**Key points:**
- Goals are stored in **core memory**
- Goals can be changed later if needed
- The agent works independently to achieve the goal within given limits

### 3. Planning

Breaking a big goal into smaller steps or subgoals.

**Three steps of planning:**
1. **Generate** multiple candidate plans
2. **Evaluate** each plan based on — efficiency, tool availability, cost, risk, and alignment with rules
3. **Select** the best plan (often with human in the loop)

### 4. Reasoning

The thinking process where the agent understands information, draws conclusions, and makes decisions.

**Reasoning during planning:**
- Breaking the goal into smaller pieces
- Choosing which tool to use
- Estimating resources needed

**Reasoning during execution:**
- Making real-time decisions
- Handling human in the loop requests
- Handling errors

### 5. Adaptability

The agent can change its plans or actions when something unexpected happens, while still staying aligned with the goal.

**When adaptability is needed:**
- When a step **fails**
- When the agent gets **external feedback**
- When the **goal changes**

### 6. Context Awareness

The agent makes better decisions by understanding the full situation across multiple steps.

**Types of context:**
- The original goal
- Progress made so far
- The current environment state
- Tool responses
- User preferences
- Policies or guardrails

**Context is managed through:**
- **Short term memory** — remembers recent steps
- **Long term memory** — remembers past experiences and learnings

---

## Components of Agentic AI

### 1. Brain

The core thinking part of the agent. It handles:
- Understanding the goal
- Planning
- Reasoning
- Choosing the right tool
- Communicating with users and other systems

### 2. Orchestrator

The manager that controls the flow of work. It handles:
- Deciding the order of tasks
- Routing to different paths based on conditions
- Retrying failed steps
- Looping and repeating steps when needed
- Delegating work to other agents or systems

### 3. Tools

Ways for the agent to interact with the outside world:
- **External actions** — like sending an email, calling an API, or updating a database
- **Knowledge base access** — searching documents or databases for information

### 4. Memory

How the agent stores and recalls information:
- **Short term memory** — current session or task info
- **Long term memory** — past learnings and experiences
- **State tracking** — keeping track of where it is in the current task

### 5. Supervisor

The safety and control layer. It handles:
- Asking for human approval (Human in the Loop)
- Enforcing guardrails and rules
- Escalating edge cases to a human when the agent is stuck

---

## Summary Table

| Component | What it does |
|-----------|-------------|
| **Brain** | Thinks, plans, reasons, selects tools |
| **Orchestrator** | Manages task flow, retries, routing |
| **Tools** | Connects to external systems and data |
| **Memory** | Stores short-term and long-term info |
| **Supervisor** | Enforces safety, asks humans for help |

---

## Interview Tips

- **Autonomy vs Safety** — Be ready to explain how autonomy is balanced with guardrails and human oversight.
- **Planning vs Execution** — Understand the difference: planning is before action, reasoning happens during both.
- **Memory types** — Short term = like a notebook for current task. Long term = like a diary of past experiences.
- **Real-world example** — Think of an AI customer support bot: it plans how to solve your issue (planning), checks your order history (tool), remembers what you said earlier (memory), and asks a human if it cannot help (supervisor).
