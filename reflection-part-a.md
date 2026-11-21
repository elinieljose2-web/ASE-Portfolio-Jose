# Reflection from Part A: Concept Analysis

**Course:** CPELX230-330 | **Activity:** Week 02-04, Exploring Agentic Software Engineering and Responsible AI

---

## 1. What is Agentic Software Engineering?

Agentic Software Engineering is the practice of designing, building, testing, and maintaining software that uses AI agents, or is built with their help. These agents pursue goals by planning, making decisions, using tools, and acting with limited human direction.

It matters in modern development because agents can automate coding, testing, and operations, letting engineers focus on design and judgment. An example is a coding agent that writes a function, runs tests, and fixes failures.

---

## 2. How does an AI agent differ from a traditional software application?

Traditional software follows fixed, predefined rules: the same input produces the same output, and every behavior is explicitly programmed.

An AI agent perceives its environment, reasons about goals, and chooses actions on its own, often using machine learning or language models. As Russell and Norvig describe, an agent maps percepts to actions. Because of this, agents can adapt to new situations but are less predictable, harder to test, and may behave differently each time.

---

## 3. Why are Agile methods appropriate for developing agentic systems?

Agentic systems have uncertain behavior and evolving requirements, so they need experimentation and feedback. Agile methods such as Scrum deliver work in short sprints, producing working increments that can be tested early.

Sprint reviews let stakeholders examine agent behavior, while retrospectives help the team improve. This empirical approach, based on transparency, inspection, and adaptation, lets teams adjust prompts, tools, and safeguards quickly instead of discovering problems late.

---

## 4. What risks should developers consider when deploying autonomous AI agents?

Developers should consider several risks:

- **Safety:** agents may take unintended or irreversible actions, such as deleting data.
- **Privacy:** agents may expose or misuse personal information.
- **Security:** attacks like prompt injection or misuse of connected tools can hijack an agent.
- **Reliability and bias:** agents can hallucinate or produce unfair outcomes from biased data.
- **Accountability:** it can be unclear who is responsible when an agent causes harm.

The NIST AI Risk Management Framework recommends identifying and managing these risks throughout the system lifecycle.

---

## 5. Why is human oversight important in AI-enabled applications?

Human oversight keeps AI systems accountable and safe. People can catch errors, hallucinations, and bias that an agent cannot recognize in itself, and can handle unusual situations outside its training.

Humans also provide ethical judgment and legal responsibility, which machines cannot hold. Approaches such as human-in-the-loop approval for high-impact actions build user trust. The NIST Govern function stresses clear roles, policies, and accountability so that humans remain in control of AI decisions.
