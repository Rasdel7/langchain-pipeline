# LangChain Pipeline Builder 🔗

Visual multi-step AI pipeline builder
using Gemini — chain prompts, add memory
and visualize LLM workflows.

## Live Demo
[Click here](YOUR_STREAMLIT_URL)

## Features
- Visual pipeline builder (drag-style)
- 7 step types: LLM Call, Template, Router etc
- Pipeline flow diagram visualization
- 4 pre-built templates (Blog, Code Review etc)
- Variable interpolation {{variable}}
- Execution trace with timing
- Memory buffer (conversation history)
- Memory-augmented chat demo
- Output length analytics
- LangChain ecosystem reference

## Tools Used
- Python, Streamlit, Google Gemini API,
  Plotly, Pandas

## How to Run Locally
pip install streamlit google-generativeai pandas numpy plotly
streamlit run app.py
