# Startup Analyzer
https://excalidraw.com/#json=DYEjXDkOLU8NjVi_SV7X-,81GStAy_wDwOlchGgAMH_A
[Uploading Startup Analyzer Design.excalidraw…]()
<img width="1197" alt="Startup Analyzer Design" src="https://github.com/user-attachments/assets/5ed63a01-f5e0-4d52-8cac-667d25abfa79" />


A practical tool that helps evaluate startup ideas by gathering insights from different business perspectives.

## What it Does

This tool breaks down startup idea analysis into three clear steps:

1. Expert Reviews
   - Market research: Size, trends, and competition
   - Tech review: Development needs and timeline
   - Financial check: Costs, revenue, and projections
   - Legal review: Regulations and compliance needs

2. Combined Analysis
   - Experts review each other's findings
   - Identify overlapping concerns
   - Spot potential issues early
   - Refine recommendations

3. Final Report
   - Clear yes/no recommendation
   - Confidence rating
   - Key points to consider
   - Next steps to take

## Setup

1. Open in Google Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]()

2. Add your API keys in Colab:
   - Gemini API key
   - OpenAI API key

3. Run the notebook

## How to Use

1. Fill in your startup details:
```python
idea_details = {
    "name": "Your Startup Name",
    "description": "What your startup does",
    "target_market": "Who you're selling to",
    "initial_investment": 500000,  # Amount needed
    "timeline": "12 months",  # Development time
    "revenue_model": "How you'll make money"
}
```

2. Run the analysis

3. Get your results:
   - Market opportunities and risks
   - Technical requirements
   - Financial projections
   - Legal considerations
   - Clear next steps

## Requirements

You'll need these packages (installed automatically):
- pydantic-ai
- pydantic
- nest_asyncio

# NOTE:
You can use any model you prefer by simply changing the `llm` setting. For more information, please refer to the [Pydantic-AI documentation](https://example-link-to-docs).

## License

MIT License

