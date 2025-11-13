# **Day 1 – From Prompts to Agents: Building Intelligent Systems with Google’s Agent Development Kit (ADK)**  

## **Introduction: The New Frontier of Agentic AI**  
Artificial intelligence has entered a transformative phase — one that goes beyond static responses and ventures into autonomous reasoning, orchestration, and collaboration. The rise of *agentic AI* represents a paradigm shift: from simple question-answer systems to dynamic entities capable of perception, decision, and action.  

On Day 1 of Google’s **Agentic AI 5-Day Training**, I explored this frontier through the **Agent Development Kit (ADK)** — Google’s framework for creating intelligent, action-driven systems powered by the **Gemini 2.5 Flash Lite** model. The day’s focus was to understand what it truly means to build an *agent* — not merely a chatbot, but a reasoning engine that can interpret intent, invoke tools, and execute complex workflows autonomously.  

---

## **The Problem: When LLMs Aren’t Enough**  
Modern large language models (LLMs) are remarkably capable, yet they remain limited when isolated. They can converse, summarize, and generate ideas, but they cannot *act* — they don’t fetch live data, run operations, or coordinate multiple specialized subtasks.  

This limitation gives rise to what Day 1 calls the **“Do-It-All Agent Problem.”** As tasks grow more complex, the monolithic-prompt approach quickly becomes unwieldy. Asking one model to research, analyze, write, edit, and fact-check simultaneously leads to bloated instructions, unpredictable results, and opaque debugging processes.  

The challenge, therefore, was clear: **how do we design intelligent systems that can reason modularly, act autonomously, and collaborate seamlessly?**  

---

## **The Breakthrough: From LLMs to True Agents**  
Google’s ADK redefines the workflow by introducing the concept of the *agent as an orchestrator of actions*. Rather than relying solely on prompt engineering, ADK empowers developers to construct agents that:  

- Understand their environment and toolset.  
- Make decisions about *when* and *how* to act.  
- Retrieve real-time information via integrated tools (e.g., Google Search).  
- Maintain conversational context and state across workflows.  

In my first experiment, I built a foundational **“Helpful Assistant” Agent** — a simple yet profound example of how ADK transforms interaction into *agency*. When prompted with questions, this agent could autonomously decide to perform a Google Search, retrieve relevant information, and compose an informed, real-time response.  

This small step represented a massive conceptual leap: **the LLM was no longer responding — it was reasoning and acting.**  

---

## **Key Insights: Thinking in Systems, Not Prompts**  
Day 1 emphasized a critical mindset shift — from crafting better prompts to **architecting better systems**. An agentic workflow isn’t about wording; it’s about orchestration.  

Through ADK’s modular design, each agent becomes a *specialist* within a broader ecosystem. Rather than one model attempting everything, multiple agents can collaborate, each with a clear, focused purpose.  

This modularity mirrors real-world team dynamics. A “Research Agent” might gather insights, a “Summarizer Agent” might synthesize them, and a “Coordinator Agent” might manage the overall flow. The benefit is clarity: tasks are easier to debug, extend, and improve independently — a foundational principle in software engineering now applied to intelligent systems.  

---

## **Multi-Agent Collaboration: The Power of Specialization**  
The highlight of Day 1 was constructing a **multi-agent system**, a miniature example of collaborative intelligence.  

I designed a workflow with two agents:  
1. **Research Agent** – dedicated solely to discovering and compiling information.  
2. **Summarizer Agent** – focused on distilling that information into concise, actionable insights.  

A **Coordinator Agent** served as the orchestrator, delegating responsibilities and consolidating outputs.  

This design demonstrated the beauty of *division of cognitive labor*. Instead of overwhelming one model with a multifaceted task, each agent performed a well-defined function. The result was not just efficiency, but explainability — it was now possible to trace which step produced which output, and why.  

In that moment, “agentic AI” stopped being an abstract buzzword and became an operational design principle.  

---

## **Workflow Patterns: The Language of Intelligent Orchestration**  
As the day progressed, the course introduced three core workflow archetypes — **Sequential**, **Parallel**, and **Loop Patterns** — the building blocks for any scalable agentic system.  

### **1. Sequential Workflows – The Assembly Line of Thought**  
Sequential workflows ensure deterministic execution: tasks occur in a fixed order, where each agent’s output becomes the input for the next. This approach mirrors an assembly line — ideal for structured processes like blog generation, where an outline, draft, and final edit must occur in order.  

The takeaway was simple yet powerful: *use sequential systems when order and dependency matter.*  

### **2. Parallel Workflows – Speed Through Independence**  
Not all tasks depend on each other. Researching AI, healthcare, and finance trends, for example, can happen concurrently. The **Parallel Agent** model eliminates unnecessary bottlenecks by allowing multiple agents to operate simultaneously and then merge their results through an aggregator step.  

This pattern reflects how modern organizations function — specialized teams work in parallel toward a shared objective, dramatically improving efficiency.  

### **3. Loop Workflows – Intelligence Through Iteration**  
Perhaps the most fascinating workflow was the **Loop Pattern**, which introduced iterative self-improvement. Instead of producing a one-shot result, a looped agent system refines its work based on feedback.  

A writing-and-critique loop, for instance, allows one agent to create a story while another critiques it. The system then revises iteratively until quality criteria are met. This iterative refinement mirrors human creative cycles — write, review, improve — embodying true *machine self-critique.*  

---

## **Architecture as Intelligence**  
The real insight of Day 1 was realizing that *intelligence emerges from architecture, not from raw model power.*  

Each workflow pattern — sequential, parallel, or looped — represents a different **cognitive archetype**. Sequential workflows think like planners, parallel workflows think like collaborators, and loop workflows think like perfectionists.  

By combining these patterns, developers can construct sophisticated systems that exhibit human-like reasoning, prioritization, and adaptability. ADK, in this sense, is less a framework for running models and more a **platform for composing intelligence.**  

---

## **Reflections: Learning to Orchestrate, Not Just Query**  
Day 1 transformed the way I think about building with AI. The exercise wasn’t about writing better prompts; it was about engineering *autonomous reasoning systems.*  

I learned to:  
- Define clear agent roles and responsibilities.  
- Design modular, explainable workflows.  
- Integrate real-time tools for live information retrieval.  
- Architect reliable pipelines that balance autonomy with control.  

Beyond the technical skills, the philosophical lesson was profound: the future of AI lies in **delegation and orchestration**, not micromanagement. The goal isn’t to make one giant model smarter — it’s to make a network of simpler agents *work together intelligently.*  

---

## **Key Takeaways**  
- **Agents are not just LLMs** — they are decision-makers that act within defined toolsets.  
- **Multi-agent systems mirror human teamwork**, dividing complex challenges into manageable, cooperative units.  
- **Workflow patterns** are the grammar of intelligent orchestration — each brings predictability, speed, or refinement.  
- **ADK bridges reasoning and action**, turning generative models into operational systems.  
- **Agentic AI marks a new development paradigm** where design thinking and system architecture become as important as model performance.  

---

## **Conclusion: From Experimentation to Orchestration**  
By the end of Day 1, I had not only built my first AI agent but had glimpsed the blueprint of a new kind of software development — one where systems think, decide, and evolve.  

The training underscored that *agency is the next abstraction layer of AI.* Just as functions abstracted machine code and APIs abstracted services, **agents now abstract reasoning itself.** Developers no longer program step-by-step logic — we define goals, tools, and constraints, and let agents discover how to achieve them.  

Day 1 closed with a clear realization: this isn’t just about learning ADK; it’s about learning to **engineer intelligence as a system.** And with this foundation, the path to Days 2–5 — exploring custom tools, long-running processes, and complex orchestration — becomes not only possible but inevitable.  

---

### **Skills Strengthened**
- Agent architecture design  
- AI workflow orchestration  
- Modular system thinking  
- Problem decomposition and specialization  
- Iterative refinement strategies  
- Real-time AI reasoning and decision systems  

---

### **Looking Ahead**
With the fundamentals in place, the next challenge lies in extending these principles — enabling agents to handle real-world integrations, custom functions, and long-running operations.  
Day 1 laid the groundwork: from here, the journey continues toward building *autonomous, collaborative, and adaptive* intelligent ecosystems.  

# Day 2 – Orchestrating Long-Running Agent Workflows with Human-in-the-Loop Approvals

## Introduction: Addressing the Challenge of Stateful, Long-Running Tasks

While Day 1 introduced the foundations of agentic AI and multi-agent orchestration, Day 2 tackled a critical problem: **how to enable agents to perform long-running, stateful workflows that require human oversight, external tool integration, and dynamic decision-making**. Modern AI agents can reason and act autonomously, but real-world processes often involve delays, approvals, or complex operations that cannot be completed in a single synchronous interaction.  

This day focused on **extending the ADK framework** to handle these scenarios using **resumable workflows, human-in-the-loop approvals, and external MCP (Managed Connector Platform) services**. The goal was to bridge the gap between autonomous AI reasoning and operational realities in enterprise workflows.

---

## Stateful Workflows: Maintaining Context Over Time

One of the key challenges in long-running operations is maintaining **workflow state**. Unlike short-lived interactions, long processes may require pausing, waiting for external events, or resuming with updated inputs. Using ADK, agents can now run asynchronous workflows that store state across pauses.  

The demonstration centered on a **shipping workflow** (`run_shipping_workflow()`) that handles both small and large orders. Small orders are auto-approved and completed immediately, while large orders simulate a **human approval process**, requiring the agent to pause until explicit confirmation is received.  

Highlights from this section include:

- **Invocation IDs**: Each workflow run has a unique `invocation_id`, enabling precise resume and audit.  
- **Pause and Resume**: Agents can suspend execution, wait for approvals or external triggers, and continue seamlessly.  
- **Event Detection**: The agent continuously monitors workflow events, such as `approval_requested` or `approval_granted`.  

This approach models real-world operational scenarios, such as enterprise approvals, ticket routing, or compliance checks, demonstrating how AI can orchestrate complex tasks over time rather than in a single burst.

---

## Human-in-the-Loop Approvals: Integrating Human Judgment

Even the most intelligent agent cannot replace human oversight in critical operations. Day 2 emphasized **human-in-the-loop workflows**, where agents pause to request explicit confirmation.  

In practice, the workflow includes:

1. **Sending a request** to the agent using `run_async()`.  
2. **Detecting approval events** with `check_for_approval()` or similar monitoring functions.  
3. **Pausing the workflow** until the human provides input.  
4. **Resuming execution** using the same `invocation_id` after approval or rejection.  

For example, a large shipping order triggers an approval request. The agent stops, waits for the manager to review the order, and then either continues processing or aborts based on the human decision. This illustrates **stateful interaction between AI and humans**, a critical requirement for enterprise-grade automation.

Highlights include:

- **Seamless pause/resume** ensures workflows are resilient to delays.  
- **Auditable approvals** provide traceability for compliance.  
- **Flexible logic** supports auto-approval for low-risk tasks while enforcing human review for critical operations.

---

## MCP Integration: Extending Agent Capabilities

A central theme of Day 2 was using **MCP services** to extend agent functionality. MCP acts as a bridge, allowing agents to invoke external tools, APIs, and services without requiring custom low-level integrations.  

In the shipping workflow example:

- The agent can **query shipping rates, inventory levels, or logistics APIs** via MCP.  
- Tool calls are handled automatically, maintaining conversational context.  
- Paused workflows preserve the integration context, so external calls can resume reliably.  

By leveraging MCP, agents become **modular, extensible, and connected to real-world systems**, enabling enterprise-grade intelligence without rebuilding every integration from scratch.

---

## Workflow Patterns for Long-Running Processes

Building on Day 1’s sequential, parallel, and looped patterns, Day 2 introduced **extended workflow patterns** for asynchronous, long-running tasks:

### Sequential Long-Running Workflows

Tasks execute in a defined order but may include **pauses for approvals or external input**. This ensures deterministic behavior while accommodating real-world delays.

### Parallel Async Workflows

Independent operations, such as querying multiple tools or services simultaneously, can run concurrently. The results are aggregated once all tasks complete, improving efficiency.

### Looped Iterative Workflows

Agents can refine outputs iteratively while waiting for human feedback or external events. For example, a draft shipping report might loop through a human review and automated analysis until quality criteria are met.

These patterns reinforce that **architecture dictates intelligence**, allowing developers to build robust, resumable, and explainable agentic systems.

---

## Execution Timeline: Demonstrating Resumable Workflows

The demo shipping workflow highlighted the **timeline of events**:

1. User submits request → agent triggers workflow asynchronously.  
2. Small orders are processed automatically.  
3. Large orders trigger **approval events**, causing the agent to pause.  
4. Human approval is provided → workflow resumes using the same `invocation_id`.  
5. Agent completes the task, including any MCP tool calls.

This step-by-step execution showcases **state preservation, human oversight, and external integration**, all managed seamlessly by ADK.

---

## Highlights

- **Problem Addressed**: Enabling agents to handle long-running, stateful, and real-world workflows with human oversight.  
- **Human-in-the-Loop**: Approval requests and resumption demonstrate controlled agent autonomy.  
- **MCP Integration**: External services and tools extend agent capabilities without extra code.  
- **Workflow Resilience**: Pause/resume functionality ensures reliability and auditability.  
- **Scalable Patterns**: Sequential, parallel, and looped workflows support complex orchestration scenarios.

---

## Key Takeaways

- **Agents can now manage long-running processes**, maintaining state and context across pauses.  
- **Human-in-the-loop workflows** ensure critical decisions involve human judgment.  
- **MCP integration** provides seamless access to external tools and APIs.  
- **Workflow patterns** extend beyond simple tasks, supporting async operations, concurrency, and iterative refinement.  
- **ADK architecture** allows developers to build robust, scalable, and enterprise-ready agentic systems, bridging reasoning, action, and real-world constraints.

---

By the end of Day 2, it became clear that agentic AI is not just about reasoning in a single interaction — it is about orchestrating **sophisticated, resumable workflows that interact with humans and external systems**, transforming agents from conversational models into **enterprise operational engines**.

