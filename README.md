#  EscrowAgent AI

An autonomous, no-code financial coordinator engineered to seamlessly parse unstructured, natural language freelance agreements and organize them into standardized, transactional parameter layouts.

##  How It Works
1. **Natural Language Input:** A freelancer details an agreement in plain English (e.g., specifying project scope, financial value, target currency, and client email credentials).
2. **Agentic Parsing:** The core logic utilizes an advanced open-weights reasoning model hosted via GroqCloud to analyze the conversation string, strip away casual noise, and isolate strict variables in 0.0 seconds.
3. **Structured Compilation:** The output is mapped into a clean, validated data payload designed to interface directly with payment sandbox environments.

##  Architecture Overview
* **Visual AI Orchestrator:** Dify Cloud
* **Language Model Brain:** gpt-oss-120b (Inference via Groq Cloud)
* **Integration Framework:** Target API schema mapping for payment sandbox automation

##  How to Import This Workflow
To run this workflow inside your own environment:
1. Create a free account on [Dify.ai](https://dify.ai).
2. Navigate to your Studio dashboard and click **Create from Blank** -> **Import DSL file**.
3. Upload the configuration file included in this repository.
4. Bind your custom API configurations to the LLM node and hit Publish!
