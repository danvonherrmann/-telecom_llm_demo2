
# Telecom LLM Demo

This Streamlit app is an AI-powered assistant for telecom marketing and sales teams. It analyzes prospects, visualizes CRM data, generates campaigns using CampaignsGPT logic, and integrates with Salesforce and contact enrichment sources.

## Features
- Generate tailored sales pitches
- Analyze prospect signals
- Visualize KPIs from Salesforce/Monday.com
- Automate campaigns using CampaignsGPT (E0–E3)
- Monitor churn/upgrade signals
- Optimize route builds

## Setup

1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Set your OpenAI key:
   ```bash
   export OPENAI_API_KEY=your_key_here  # or set in Streamlit Cloud secrets
   ```
4. Run the app:
   ```bash
   streamlit run telecom_llm_demo.py
   ```

## Deployment

Deploy to [Streamlit Cloud](https://streamlit.io/cloud) and configure `OPENAI_API_KEY` in the app’s secret settings.
