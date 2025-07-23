# Anarix_Assignment
```
# E-commerce AI Agent

## Features
- Ask any question about your e-commerce data via API.
- LLM-powered translation of questions to SQL.
- Visualizations for suitable queries.
- Modular, local-first design.

## Setup
1. Place your CSVs in data/.
2. Run python db/init_db.py to create the database.
3. Start the API: uvicorn api.main:app --reload
4. POST questions to /ask.
