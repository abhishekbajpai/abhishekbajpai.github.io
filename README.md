# Agentic AI Design Patterns


Agentic AI is a type of AI that can operate independently, making decisions and taking actions. Agentic AI systems used LLM to analyze data, identify patterns, and take actions to achieve specific goals. Key Charactersitcs agents have is there ability to dynamically plan and execute task by using external tools. 

But question is how to build a robuts and effective agentic system. Let's look into some common design patterns used for building Agentic AI applications. Let's deep dive each one of them: 


- **Reflection Pattern**: Agent generates a draft solution, and then evaluate it's own output uses that feedback to revive its response iteratively until it produces the final response. This pattern is also know as Self-Critique or Evaluator-Optimizer as it used self reflection. Evaluation can be done either by same LLM or second LLM, this cycle can repeat until the evaluator confirms the requirements are met or a satisfing output is achieved.

  **Use Cases:**

  - Code Generation: An AI writes code and then debugs it, iteratively fixing errors until it's functional.
  - Data Analysis: The AI generates a report from data and then reviews its own conclusions to ensure logical consistency and accuracy.
  - Creative Writing: An AI drafts a story or article and then refines it for grammar, tone, and overall flow.

