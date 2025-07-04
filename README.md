# LLM-Instruction-Following-Research

This independent research project aims to systematically investigate the faithfulness and robustness of large language models (LLMs), particularly in their ability to adhere to complex, multi-constraint instructions. The core of this research is to identify, quantify, and analyze patterns of "instruction neglect" or "constraint drift," where a model may fail to follow all parts of a given prompt. The ultimate goal is to develop and share a set of best practices and prompt engineering techniques to improve model reliability.

As a heavy user of advanced LLMs like Claude for complex professional tasks, I've frequently observed a fascinating phenomenon: when given a prompt with multiple layers of constraints (e.g., "summarize this text, use a bulleted list, adopt a formal tone, and strictly avoid mentioning financial figures"), the model's performance can be inconsistent. Sometimes it executes flawlessly; other times, it may "forget" one or two of the constraints.

These anecdotal observations suggest a rich area for systematic research. This project moves beyond individual trial-and-error to create a structured methodology for understanding and mitigating these inconsistencies, contributing to the broader goal of building more reliable and steerable AI systems.

The primary objectives of this project are:

1.To quantify instruction-following failure by developing a benchmark corpus of complex prompts to measure how often models fail to adhere to all given constraints.
2.To identify failure patterns by analyzing the results. For example, are formatting instructions forgotten more often than content-based restrictions? Does the order of instructions matter?
3.To develop mitigation strategies by formulating and testing a set of actionable prompt engineering guidelines based on the findings.

This project is licensed under the MIT License. 
