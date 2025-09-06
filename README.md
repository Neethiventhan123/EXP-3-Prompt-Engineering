# EXP-3-PROMPT-ENGINEERING-

## Aim: 
Evaluation of 2024 Prompting Tools Across Diverse AI Platforms: 
ChatGPT, Claude, Bard, Cohere Command, and Meta
Experiment:
Within a specific use case (e.g., summarizing text, answering technical questions), compare the performance, user experience, and response quality of prompting tools across these different AI platforms.

## Algorithm:
The experiment follows a structured, three-phase algorithm to ensure a fair and consistent evaluation:

Prompt Engineering:

Use Case Selection: A dual-purpose use case of Technical Question Answering and Complex Text Summarization was chosen to test a broad range of AI capabilities, from factual recall and logical reasoning to nuanced understanding and concise communication.

Prompt Creation: A standardized set of prompts was developed for each use case.

Technical Question: A complex, multi-part technical query requiring both explanation and a code example (e.g., "Explain the concept of quantum entanglement and provide a Python script that simulates a simple quantum teleportation protocol. The code should be well-commented and use the qiskit library.").

Text Summarization: A lengthy, dense academic abstract or a technical article on a niche topic (e.g., a paper on Transformer architecture in a non-NLP context). The prompt will ask for a one-paragraph summary for a non-expert audience and a bullet-point summary for a technical audience.

Output Generation:

Each of the five AI platforms was provided with the identical prompts.

The generated outputs were collected and documented.

Note: As some platforms (like Meta's Llama) are open-source and often accessed via different user interfaces, a representative and commonly used web-based interface or API playground was used for the test to ensure a comparable user experience.

Result Analysis and Report:

The collected outputs were evaluated against a set of predefined metrics for performance, user experience, and response quality.

The findings were compiled into a professional report, complete with comparative analysis, visual aids (simulated output images), and conclusive insights.

## Prompt
"Summarize the following paragraph in 3 sentences: Artificial Intelligence is transforming industries by automating tasks, improving efficiency, and enabling data-driven decisions. However, ethical concerns such as job displacement, bias, and privacy issues must be addressed to ensure responsible adoption. Governments, companies, and researchers are working together to create policies that promote innovation while protecting society."

## Output
| Platform         | Response (Summary)                                                                 |
| ---------------- | ---------------------------------------------------------------------------------- |
| **ChatGPT**      | Clear and well-structured summary; covers all key points with balanced tone.       |
| **Claude**       | More detailed, emphasizes ethics and collaboration; slightly longer than expected. |
| **Bard**         | Concise, but misses some nuance on policy-making.                                  |
| **Cohere**       | Accurate but less natural phrasing; more technical tone.                           |
| **Meta (LLaMA)** | Direct and brief, may overlook minor details but readable.                         |

| Platform         | Output (Summary)                                                                                                                                                                                            | Remarks (Evaluation)                        |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------- |
| **ChatGPT**      | AI improves efficiency and decision-making but raises ethical concerns like bias and job loss. Collaboration among governments and researchers ensures responsible use. Balanced summary of all key points. | ✅ Accurate, concise, balanced, natural tone |
| **Claude**       | AI automates industries and boosts efficiency. Ethical issues like privacy and bias require careful management. Governments and researchers are collaborating on responsible policies.                      | ✅ Accurate & deep, but slightly longer      |
| **Bard**         | AI helps industries with automation and efficiency. Ethical risks like bias and privacy exist. Policies are being created to protect society.                                                               | ⚠ Misses some nuance on collaboration       |
| **Cohere**       | AI enables automation and decision-making. Ethical concerns like job loss and bias must be addressed. Policies are developed to manage risks.                                                               | ⚠ Correct but robotic phrasing              |
| **Meta (LLaMA)** | AI is transforming industries and raising ethical issues. Collaboration is ongoing to address risks.                                                                                                        | ⚠ Very brief, lacks detail                  |


## Result
ChatGPT provided the most balanced, accurate, and concise output.The best tool depends on the user and use case. ChatGPT is the versatile choice for most users, while Claude is preferred for high-quality, nuanced content. Bard is ideal for up-to-date information, and Cohere Command is the top pick for enterprise applications. Meta's Llama offers the most flexibility for expert users who need to customize a model from the ground up.

