# Building Systems With ChatGPT

## Course Overview
[Building Systems with ChatGPT](https://www.deeplearning.ai/short-courses/building-systems-with-chatgpt/) teaches you how to automate complex workflows using the ChatGPT API by chaining multiple prompts and integrating Python code with LLM responses. You'll learn how to build structured pipelines to enhance accuracy, safety, and relevance in AI applications.

### Key Topics:
- **Multi-stage prompting** – Splitting complex tasks into sequential steps.
- **LLM-driven automation** – Using prompt chaining to build dynamic systems.
- **Evaluation techniques** – Ensuring safe and accurate model outputs.
- **Practical applications** – Building a customer service chatbot and query classification system.

By the end of this course, you will be able to create robust AI-powered workflows for real-world use cases. 🚀


## Course Contents

### 1. [Language Models, Chat Format, and Tokens](https://github.com/michaWorku/Building-Systems-With-ChatGPT/blob/main/L1_Language_Models.ipynb)
- Understand LLM text generation processes.
- Differences between **Base LLMs** and **Instruction-Tuned LLMs**.
- Reinforcement Learning from Human Feedback (**RLHF**).
- API setup and prompt structuring.
- Understanding tokens and message roles (**System, User, Assistant**).

### 2. [Classification](https://github.com/michaWorku/Building-Systems-With-ChatGPT/blob/main/L2_classification.ipynb)
- Implement input evaluation and query classification.
- Use prompt engineering to handle different cases effectively.

### 3. [Moderation](https://github.com/michaWorku/Building-Systems-With-ChatGPT/blob/main/L3_moderation.ipynb)
- Evaluate inputs using OpenAI’s Moderation API.
- Detect harmful content in text and images.
- Prevent prompt injections using delimiters, system messages, and few-shot learning.

### 4. [Chain of Thought Reasoning](https://github.com/michaWorku/Building-Systems-With-ChatGPT/blob/main/L4_chain_of_thought_reasoning.ipynb)
- Implement multi-step reasoning processes.
- **Inner Monologue:** Hiding intermediate reasoning steps while serving final responses.

### 5. [Chaining Prompts](https://github.com/michaWorku/Building-Systems-With-ChatGPT/blob/main/L5_chaining_prompts.ipynb)
- Process inputs through sequential prompts.
- Manage context limitations and optimize token usage.
- Reduce costs by skipping unnecessary processing steps.
- Track external states and integrate external tools (e.g., databases, web search).
- Implement multi-prompt workflows for **product information retrieval**.

### 6. [Checking Outputs](https://github.com/michaWorku/Building-Systems-With-ChatGPT/blob/main/L6_check_output.ipynb)
- Evaluate LLM responses for accuracy and safety.
- Use OpenAI Moderation API for output filtering.
- Ensure factual correctness using structured system messages.

### 7. [End-to-End System Development](https://github.com/michaWorku/Building-Systems-With-ChatGPT/blob/main/L7_evalution.ipynb)
- Build a complete pipeline:
  1. Moderate user inputs.
  2. Extract relevant product names.
  3. Retrieve product details.
  4. Generate user responses.
  5. Moderate final outputs.
  6. Evaluate responses for quality.
  7. Implement human fallback mechanisms when needed.
- Maintain conversation history in chatbot interactions.

### 8. [Evaluation – Part I](https://github.com/michaWorku/Building-Systems-With-ChatGPT/blob/main/L8_evaluation_part_I.ipynb)
- Evaluate responses when there is a **single correct answer**.
- Tune prompts based on test cases and edge scenarios.
- Perform **regression testing** and automated evaluation.
- Measure correctness using development and test sets.

### 9. [Evaluation – Part II](https://github.com/michaWorku/Building-Systems-With-ChatGPT/blob/main/L9_evaluation_part_II.ipynb)
- Evaluate responses when multiple correct answers exist.
- Compare LLM outputs against expert responses using:
  - OpenAI evals.
  - BLEU score for text similarity.
- Implement automated evaluation rubrics.


## Notebooks List
1. [**Language Models**]((https://github.com/michaWorku/Building-Systems-With-ChatGPT/blob/main/L1_Language_Models.ipynb)) – Introduction to LLMs, tokens, and message roles.
2. [**Classification**](https://github.com/michaWorku/Building-Systems-With-ChatGPT/blob/main/L2_classification.ipynb) – Query classification using LLM prompts.
3. [**Moderation**](https://github.com/michaWorku/Building-Systems-With-ChatGPT/blob/main/L3_moderation.ipynb) – Identifying and filtering harmful content.
4. [**Chain of Thought Reasoning**](https://github.com/michaWorku/Building-Systems-With-ChatGPT/blob/main/L4_chain_of_thought_reasoning.ipynb) – Step-by-step logical processing.
5. [**Chaining Prompts**](https://github.com/michaWorku/Building-Systems-With-ChatGPT/blob/main/L5_chaining_prompts.ipynb) – Creating efficient multi-step workflows.
6. [**Check Outputs**](https://github.com/michaWorku/Building-Systems-With-ChatGPT/blob/main/L6_check_output.ipynb) – Ensuring factual correctness and safety.
7. [**Evaluation**](https://github.com/michaWorku/Building-Systems-With-ChatGPT/blob/main/L7_evalution.ipynb) – Building structured evaluation processes.
8. [**Evaluation Part I**](https://github.com/michaWorku/Building-Systems-With-ChatGPT/blob/main/L8_evaluation_part_I.ipynb) – Automated testing for single-answer tasks.
9. [**Evaluation Part II**](https://github.com/michaWorku/Building-Systems-With-ChatGPT/blob/main/L9_evaluation_part_II.ipynb) – Evaluating subjective responses with scoring methods.


## Getting Started
1. Install required Python libraries.
2. Set up an API key for OpenAI access.
3. Run the provided Jupyter notebooks interactively.

## References
- [Course Link](https://www.deeplearning.ai/short-courses/building-systems-with-chatgpt/)

This course provides essential skills for building **AI-powered automation workflows**, ensuring safety, accuracy, and efficiency in LLM-based applications. 🚀

