# 🧾 Extraction Prompts

## Prompt 1: Entity Extraction
Extract the following details from the text:
- Person names
- Locations
- Dates

Return in JSON format with keys: "names", "locations", "dates".
**Text:** "Steve Jobs founded Apple in Cupertino in 1976."

---

## Prompt 2: Keyword Extraction
Identify the top 5 keywords that capture the main ideas of the text.  
Return them as a comma-separated list.  
**Text:** "Artificial intelligence is transforming healthcare, finance, and education."

---

## Prompt 3: Structured Data Extraction
Extract product details from the text and return in JSON format:
```json
{
  "product_name": "",
  "price": "",
  "category": ""
}
