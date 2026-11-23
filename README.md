# Module 02: Prompt Engineering & AI Productivity

Hands-on project built with **Google Colab**, **`google-genai`** (`gemini-3.5-flash-lite`), **Pydantic**, and **Pandas** covering prompt design, structured outputs, AI debugging/evaluation, and a reusable productivity toolkit.

## Key Deliverables & Workflows
1. **Zero-Shot & Few-Shot Prompting:** Role-based, context-rich prompts with strict output constraints and multi-class ticket classification.
2. **Structured JSON Output:** Schema-enforced extraction (`TicketAnalysis` via Pydantic) parsed cleanly into JSON.
3. **AI-Assisted Debugging & Evaluation:** Automated Python bug detection/fixes paired with a structured prompt evaluation table (`pandas.DataFrame`).
4. **AI Productivity Toolkit (`AIProductivityToolkit`):** Reusable Python methods for executive summarization, professional emails, ATS-friendly resume bullets, and coding/research breakdowns.

## How to Run
1. Open `Module_02_Prompt_Engineering_AI_Productivity.ipynb` in **Google Colab**.
2. Add your Google AI Studio key under **Colab Secrets** as `GEMINI_API_KEY` with **Notebook access** enabled.
3. Run all cells sequentially (`Runtime -> Run all`).
