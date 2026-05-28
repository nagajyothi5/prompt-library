# 📄 Summarization Prompts

## Prompt 1: General Summary
Summarize the following article in 3 bullet points.  
Focus on the main arguments and conclusions.  
Do not exceed 100 words.

---

## Prompt 2: Targeted Summary (Directional Stimulus)
Summarize the text in 2–3 sentences based on the hint:  
**Hint:** where the nisse lives.

---

## Prompt 3: Chain-of-Density Summary
Generate a concise summary of the text.  
Identify missing entities and rewrite the summary to include them.  
Repeat this process 3 times.  
Return all summaries in JSON format with keys: "missing_entities" and "denser_summary".
