# 📊 [Data Analyst AI Agent]

An AI data analysis agent that lets you ask questions about CSV and Excel files in plain English. It is powered by Google Gemini, built with the Agno agent framework, and uses DuckDB to run the queries.

## What it does

- Upload a CSV or Excel file and the schema is detected automatically
- Ask questions in natural language, with no SQL needed
- The agent turns your question into a SQL query and runs it on DuckDB
- Results are shown in a Streamlit interface
- [Add anything else you built, e.g. charts, query history]

## Tech stack

- Python
- Agno (agent framework)
- Google Gemini 
- DuckDB
- Streamlit

## Getting started

1. Clone the repo
   ```bash
   git clone https://github.com/YOUR-USERNAME/YOUR-REPO.git
   cd YOUR-REPO
   ```
2. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```
3. Get a Gemini API key from [Google AI Studio](https://aistudio.google.com/apikey)
4. Run the app
   ```bash
   streamlit run [your_main_file].py
   ```
5. Paste your Gemini API key in the sidebar, upload a file, and start asking questions

## Example questions

- "What are the top 5 products by revenue?"
- "Show the average [column] grouped by [column]"
- [Add examples that fit your own sample data]