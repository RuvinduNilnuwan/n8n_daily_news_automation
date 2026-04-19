# n8n_daily_news_automation
This project is an automated news aggregation and summarization system built using n8n and OpenAI.
 **Features**

* Fetches news from multiple RSS feeds (BBC, TechCrunch, IGN)
* Cleans and processes data
* Uses OpenAI to generate a summarized daily briefing
* Sends email automatically via SMTP (Brevo)
* Runs daily using Cron trigger

## Tech Stack

* n8n (workflow automation)
* OpenAI API (AI summarization)
* Brevo SMTP (email delivery)
* RSS feeds (data source)

## Workflow

screenshot attached

##  How it works

1. Cron triggers daily at 7 AM
2. RSS feeds fetch latest news
3. Data is merged and cleaned
4. AI generates a summarized report
5. Email is sent automatically

## Setup

1. Import `workflow.json` into n8n
2. Add your OpenAI API key
3. Configure SMTP credentials
4. Activate the workflow

Credentials are not included. Please configure your own OpenAI and SMTP credentials


