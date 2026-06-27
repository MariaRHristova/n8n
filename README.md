# n8n Workflows

This repository contains my exported n8n workflows, grouped by topic.

The workflow JSON files stay untouched. The descriptions live here in markdown so they are easy to browse on GitHub.

## Workflow Catalog

### 00-intro-and-foundations

- [00 API Ping](workflows/00-intro-and-foundations/00-api-ping.json) - Sends a simple API request to verify connectivity.
- [0. Hello agent](workflows/00-intro-and-foundations/00-hello-agent.json) - Introductory AI agent starter workflow.
- [1 Email Summarizer](workflows/00-intro-and-foundations/01-email-summarizer.json) - Summarises an email into a short digest.
- [01 Weather API Dashboard](workflows/00-intro-and-foundations/01-weather-api-dashboard.json) - Pulls weather data from an API for a dashboard-style view.
- [Hello World!](workflows/00-intro-and-foundations/hello-world.json) - Starter workflow used to verify the n8n environment.
- [Mimi. Build your first AI agent](workflows/00-intro-and-foundations/mimi-build-your-first-ai-agent.json) - Tutorial-style workflow for building a first AI agent.
- [Shortcuts](workflows/00-intro-and-foundations/shortcuts.json) - Reference workflow for useful n8n keyboard shortcuts.

### 01-integrations-and-webhooks

- [01 - Event Registration form](workflows/01-integrations-and-webhooks/01-event-registration-form.json) - Collects event registrations from a form.
- [02 Email Notifications](workflows/01-integrations-and-webhooks/02-email-notifications.json) - Sends email notifications when triggered.
- [02 - Event Registration form and Gmail and Telegram](workflows/01-integrations-and-webhooks/02-event-registration-form-and-gmail-and-telegram.json) - Collects registrations, writes them to Google Sheets, and sends Gmail and Telegram notifications.
- [02 Webhook Receiver](workflows/01-integrations-and-webhooks/02-webhook-receiver.json) - Receives and processes incoming webhook payloads.
- [Daily Registration Report](workflows/01-integrations-and-webhooks/daily-registration-report.json) - Builds a daily registration report from stored entries.

### 02-data-and-transformations

- [03 Normalizer-Child](workflows/02-data-and-transformations/03-normalizer-child.json) - Normalizes incoming data into a consistent shape.
- [03 Normalizer-Parent](workflows/02-data-and-transformations/03-normalizer-parent.json) - Orchestrates normalization and delegates work to the child workflow.
- [07 Data cleanup](workflows/02-data-and-transformations/07-data-cleanup.json) - Cleans and standardizes data before downstream use.

### 03-ai-and-agents

- [2. Multi-Tool Agent](workflows/03-ai-and-agents/02-multi-tool-agent.json) - AI agent that chooses between multiple tools.
- [2 Ticket classifier](workflows/03-ai-and-agents/02-ticket-classifier.json) - Classifies support tickets into categories.
- [3. Chat Hub Chatbot](workflows/03-ai-and-agents/03-chat-hub-chatbot.json) - Chat hub chatbot workflow.
- [3 Content Generator](workflows/03-ai-and-agents/03-content-generator.json) - Generates content drafts from structured input.
- [4. Memory + Reset](workflows/03-ai-and-agents/04-memory-reset.json) - Manages agent memory and supports reset behavior.
- [4 Sentiment Analysis](workflows/03-ai-and-agents/04-sentiment-analysis.json) - Analyzes text sentiment.
- [5 Image scanner from URL](workflows/03-ai-and-agents/05-image-scanner-from-url.json) - Fetches an image from a URL and extracts information from it.
- [5. Multimodal Agent](workflows/03-ai-and-agents/05-multimodal-agent.json) - Multimodal agent that works with text and images.
- [06 AI Evaluation](workflows/03-ai-and-agents/06-ai-evaluation.json) - Evaluates AI output or workflow responses.
- [6 AI feedback](workflows/03-ai-and-agents/06-ai-feedback.json) - Collects or scores feedback about AI output.
- [7. Human Review Agent](workflows/03-ai-and-agents/07-human-review-agent.json) - Routes results through a human review step.
- [7 Prompt Lab](workflows/03-ai-and-agents/07-prompt-lab.json) - Sandbox for prompt experiments and iteration.
- [08 Firecrawl Web Scraping + AI Summary](workflows/03-ai-and-agents/08-firecrawl-web-scraping-ai-summary.json) - Scrapes web content with Firecrawl and summarizes it with AI.
- [Demo: RAG in n8n](workflows/03-ai-and-agents/demo-rag-in-n8n.json) - Demonstrates retrieval-augmented generation inside n8n.
- [Google Reviews Sentiment Analysis](workflows/03-ai-and-agents/google-reviews-sentiment-analysis.json) - Analyzes Google reviews for sentiment.

### 04-reliability-and-monitoring

- [04 Resilient API Flow + Error Alerts](workflows/04-reliability-and-monitoring/04-resilient-api-flow-error-alerts.json) - Sends alerts when the resilient API flow fails.
- [04 Resilient API Flow Error Workflow](workflows/04-reliability-and-monitoring/04-resilient-api-flow-error-workflow.json) - Handles failures for the resilient API flow.
- [05 Data Tables вЂ” Dead Letter Queue](workflows/04-reliability-and-monitoring/05-data-tables-dead-letter-queue.json) - Stores failed items in a dead-letter queue using n8n Data Tables.
- [05 - Website monitoring](workflows/04-reliability-and-monitoring/05-website-monitoring.json) - Monitors a website for availability or content changes.
- [06 - Error Handling Demo](workflows/04-reliability-and-monitoring/06-error-handling-demo.json) - Demonstrates n8n error-handling patterns.

### 05-mcp

- [6. MCP Client Agent](workflows/05-mcp/06-mcp-client-agent.json) - AI agent that calls tools through an MCP client.
- [07 MCP Server](workflows/05-mcp/07-mcp-server.json) - MCP server workflow that exposes tools to clients.
- [MCP Server](workflows/05-mcp/mcp-server.json) - MCP server workflow that exposes tools to clients.

### 06-content-pilot

- [CP-01-Idea-Intake](workflows/06-content-pilot/01-idea-intake.json) - Captures content ideas from a form and saves them to Google Sheets.
- [CP-02-Weekly-Planner](workflows/06-content-pilot/02-weekly-planner.json) - Turns approved ideas into a weekly content plan.
- [CP-03-AI-Copywriter](workflows/06-content-pilot/03-ai-copywriter.json) - Generates draft copy for the content pipeline.
- [CP-03-AI-Copywriter-Bonus](workflows/06-content-pilot/03-ai-copywriter-bonus.json) - Bonus variation of the AI copywriter workflow.
- [CP-03-AI-Copywriter-Bonus](workflows/06-content-pilot/03-ai-copywriter-bonus-2.json) - Bonus variation of the AI copywriter workflow.
- [CP-04-Approval-Flow](workflows/06-content-pilot/04-approval-flow.json) - Routes generated content through an approval step.
- [CP-04-Approval-Flow-Bonus](workflows/06-content-pilot/04-approval-flow-bonus.json) - Bonus approval-flow variation.
- [CP-05-ContentBot](workflows/06-content-pilot/05-contentbot.json) - Orchestrates the ContentBot workflow.
- [CP-06-Publish-Hook](workflows/06-content-pilot/06-publish-hook.json) - Triggers publishing actions when content is ready.
- [CP-06-Publish-Hook-Bonus](workflows/06-content-pilot/06-publish-hook-bonus.json) - Bonus publish-hook variation.
- [CP-07A-Test-Workflow](workflows/06-content-pilot/07a-test-workflow.json) - Test workflow for the ContentPilot pipeline.
- [CP-07B-Error-Handler](workflows/06-content-pilot/07b-error-handler.json) - Error handler for the ContentPilot pipeline.
- [CP-Bonus-Full-Pipeline](workflows/06-content-pilot/bonus-full-pipeline.json) - ContentPilot workflow for Full Pipeline.

### 07-t4-exercises

- [[Ex1] [T4] Hello world](workflows/07-t4-exercises/01-hello-world.json) - Starter workflow used to verify the n8n environment.
- [[Ex2] [T4]. AI Builder. Form Submission to Google Sheet with Email Notification](workflows/07-t4-exercises/02-ai-builder-form-submission-to-google-sheet-with-email-notification.json) - T4 exercise workflow for [Ex2] [T4]. AI Builder. Form Submission to Google Sheet with Email Notification.
- [[Ex3] [T4] Insert and read data from Google Sheets](workflows/07-t4-exercises/03-insert-and-read-data-from-google-sheets.json) - Writes data to Google Sheets and reads it back.
- [[Ex4] [T4] Date and Time](workflows/07-t4-exercises/04-date-and-time.json) - Demonstrates date and time handling.
- [[Ex5] [T4] Calculator](workflows/07-t4-exercises/05-calculator.json) - Performs basic calculations.
- [[Ex6] [T4] JSON Transform](workflows/07-t4-exercises/06-json-transform.json) - Transforms JSON data.
- [[Ex7] [T4] Keyboard Shortcuts](workflows/07-t4-exercises/07-keyboard-shortcuts.json) - Practice workflow for keyboard shortcuts.
- [[Ex8] [T4] Homework practice](workflows/07-t4-exercises/08-homework-practice.json) - Homework practice workflow.
- [[Ex9] [Bonus 1] [T4] Personal profile](workflows/07-t4-exercises/09-bonus-1-personal-profile.json) - Bonus workflow for building a personal profile example.
- [[Ex9] [Bonus 2] [T4] If Node - Smart Router](workflows/07-t4-exercises/09-bonus-2-if-node-smart-router.json) - Bonus workflow that demonstrates conditional routing with IF nodes.
- [[Ex9] [Bonus 3] [T4] Bug Hunt](workflows/07-t4-exercises/09-bonus-3-bug-hunt.json) - Bonus debugging exercise.

### 08-projects

- [Automate Real Estate Listing Scraper рџЏ рџ¤– with ScrapeGraph AI and Google Sheets](workflows/08-projects/automate-real-estate-listing-scraper-with-scrapegraph-ai-and-google-sheets.json) - Scrapes real-estate listings with ScrapeGraph AI and stores them in Google Sheets.
- [Playground](workflows/08-projects/playground.json) - Web-scraping playground that extracts listing data from imot.bg and saves it to an n8n Data Table.
- [Playground](workflows/08-projects/real-estate-playground.json) - Web-scraping playground that extracts listing data from imot.bg and saves it to an n8n Data Table.

## Notes

- The descriptions are documented in markdown only.
- The JSON workflow exports were not modified.
