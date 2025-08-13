# Knowledge Base Updater (n8n Workflow)

This is an n8n workflow that:
1. Scrapes articles from given URLs
2. Summarizes them using OpenAI GPT
3. Updates table on Airtable

## Components Used
- HTTP Request
- HTML Extract
- OpenAI API
- Airtable token

## How It Works
- The workflow takes a list of article URLs
- Scrapes each article’s content
- Sends it to OpenAI to summarize

- Updates to table in Airtable
