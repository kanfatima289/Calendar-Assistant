Calendar Assistant (n8n Workflow)

An automated n8n workflow that emails you a daily briefing on the two most important events on your calendar.

How it works

Schedule Trigger: Runs automatically every day at 6:00 AM.
AI Agent: Powered by OpenAI's gpt-5-mini. It reads the day's events and picks the top two most important ones, based on each event's title, description, and attendees. It then writes a short explanation of why each one matters.
Google Calendar tool: The agent uses it to fetch the day's events from the connected calendar.
Gmail tool: The agent uses it to send the summary email to the configured address.
Tools and integrations
n8n (AI Agent, Schedule Trigger)
OpenAI (gpt-5-mini)
Google Calendar (OAuth2)
Gmail (OAuth2)

Setup

Import Calendar Assistant.json into n8n.
Connect your own credentials for OpenAI, Google Calendar, and Gmail.
Update the calendar and the recipient email address in the AI Agent prompt.
Activate the workflow.
