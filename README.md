# AI Workflow Automation Agent using n8n

## Project Overview

This project demonstrates an AI-powered workflow automation agent built using n8n and OpenAI.

The workflow is designed to receive chat messages, generate AI responses, maintain conversation context using memory, and support email automation through Gmail.

## Objectives

- Build a visual AI workflow using n8n.
- Integrate an OpenAI Chat Model with an AI Agent.
- Explore conversation memory.
- Configure Gmail integration for email automation.
- Document workflow setup, testing, and reuse.

## Technology Stack

- n8n — workflow automation
- OpenAI API — AI-generated responses
- AI Agent — tool-based workflow interaction
- Simple Memory — conversation context
- Gmail — email integration

## Workflow Architecture

Chat Trigger → AI Agent

AI Agent connections:
- OpenAI Chat Model
- Simple Memory
- Gmail Tool

## Repository Structure

- `workflows/` — exported n8n workflow JSON
- `screenshots/` — workflow and test screenshots
- `README.md` — project documentation

## Setup Instructions

1. Start your n8n instance.
2. Import the workflow JSON from the `workflows/` directory.
3. Configure your own OpenAI credentials.
4. Configure Gmail OAuth2 credentials if using Gmail.
5. Review node settings and connections.
6. Test the workflow using sample messages.
7. Verify the workflow execution results before using it.

## Security

Do not commit API keys, passwords, OAuth secrets, access tokens, or private email data.

Configure credentials securely in your own n8n instance.

## Testing

Document the test cases you actually performed, including AI responses, memory behavior, Gmail execution, and error handling where applicable.

## Limitations

The workflow requires a running n8n instance and valid credentials. AI responses may be inaccurate and should be reviewed.



