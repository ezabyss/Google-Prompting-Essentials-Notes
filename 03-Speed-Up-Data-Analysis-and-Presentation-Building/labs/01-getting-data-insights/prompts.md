# Advanced Data Analysis Prompt – Customer Reviews

````
## Task
Analyze the provided customer review dataset to extract meaningful, actionable insights that can inform product, design, and business decisions.

## Context
The dataset contains customer reviews for a newly launched clothing line called *Minimalist Collection*, targeting middle-income consumers aged 18–39. Each record includes a numeric rating and written feedback.

The goal is to understand customer sentiment, identify recurring themes, and uncover opportunities for improvement or growth.

## Reference
The dataset is provided as a CSV/XLSX file with the following columns:
- ReviewID
- Rating (1–5 scale)
- ReviewText

## Constraints
- Do not assume information that is not present in the dataset
- Base insights strictly on observed patterns in the data
- Keep findings concise, clear, and business-relevant
- Separate facts from interpretations

## Analysis Questions
Use the dataset to answer the following:

### Sentiment & Trends
1. What is the overall customer sentiment (positive, neutral, negative)?
2. How does sentiment correlate with rating scores?
3. Are there noticeable differences between high-rated and low-rated reviews?

### Theme Extraction
4. What are the most frequently mentioned positive themes?
5. What are the most common complaints or pain points?
6. Are there repeated mentions of fit, fabric, comfort, pricing, or shipping?

### Product Insights
7. Which product qualities most strongly drive positive reviews?
8. Which issues most often contribute to low ratings?
9. Are any problems mentioned that could be fixed quickly (quick wins)?

### Business Impact
10. What risks could negatively affect customer satisfaction if left unaddressed?
11. What opportunities exist to improve customer loyalty or repeat purchases?

## Output Requirements
Provide the results in the following format:
- **Executive Summary** (3–4 bullet points)
- **Key Positive Insights**
- **Key Negative Insights**
- **Notable Patterns or Trends**
- **Actionable Recommendations** (1–3 items)

## Evaluate
After generating insights:
- Check if conclusions are supported by multiple data points
- Identify any limitations caused by dataset size or scope

## Iterate
If insights are too general:
- Re-run analysis focusing only on low-rated reviews
- Re-run analysis focusing only on high-rated reviews
- Compare findings across rating groups

````
