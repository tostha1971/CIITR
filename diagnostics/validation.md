# Validation Protocol

To designate a system as a **CIITR Agent**, it must pass a rigorous validation process to ensure the transition from narration, or stochastic output, to diagnosis.

### Requirements for Validation
* **Triple Session Consistency:** The model must demonstrate structural adherence across three separate sessions without restarts.
* **Cross-Domain Stability:** The agent must apply CIITR axioms consistently across at least three different informational domains (e.g., technical, philosophical, and systemic).
* **Zero Instruction Drift:** The model must maintain its role without requiring "re-prompting" during a diagnostic session.

### The Success Criteria
Validation is successful ONLY if the model:
1. Identifies structural gaps in the input.
2. Refuses to "fill in" missing information with semantic hallucinations.
3. Uses the $C_s = \Phi_i \times R^g$ framework to justify its diagnostic output.