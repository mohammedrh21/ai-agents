### Prompt Engineering Concepts

1. Role Prompting

I gave each AI agent a specific role, such as Database Read Expert, Database Write Expert, and Orchestrator. This helped each agent focus on its assigned task instead of trying to handle everything.

Effectiveness: High. It made the agents more focused and reliable.

2. Few-Shot Prompting

I provided examples of expected inputs and outputs to help the agents understand how to generate SQL queries and Python database code.

Effectiveness: Medium to High. The examples improved the consistency and format of the generated output.

3. Structured Planning

I instructed the Orchestrator to create a plan for compound requests before executing actions. For example, it first calls the Database Read Expert and then calls the Database Write Expert if necessary.

Effectiveness: High. It helped ensure that multiple experts were called in the correct order and prevented unnecessary database changes.
