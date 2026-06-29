# AI WhatsApp Message Priority Classifier

## Project Status
Prototype / Proof of Concept

This project is currently tested using a WhatsApp test number and is not yet deployed for mass production.

## Project Overview
This project is an AI automation workflow built using n8n, OpenAI, WhatsApp Trigger, Structured Output Parser, IF condition, Wait node, and Gmail.

The workflow receives incoming WhatsApp messages, analyzes the message content using an AI Agent, classifies the message as High Priority or Low Priority, and sends an automated Gmail notification.

## Tools Used
- n8n
- OpenAI
- WhatsApp Trigger
- Structured Output Parser
- IF Node
- Wait Node
- Gmail

## Workflow Logic
1. WhatsApp Trigger receives an incoming message.
2. AI Agent analyzes the message content.
3. Structured Output Parser formats the output.
4. IF Node checks whether the message is High Priority or Low Priority.
5. High Priority messages are sent immediately to Gmail.
6. Low Priority messages are delayed before email notification.

## Skills Demonstrated
- AI workflow automation
- n8n workflow design
- WhatsApp message automation
- OpenAI integration
- Structured output parsing
- Conditional routing
- Gmail automation
- Basic API/webhook understanding
- Automation testing and documentation

## Current Limitations
- Tested using a WhatsApp test number only.
- Not yet deployed for mass production.
- No database or message history log yet.
- No retry or error handling mechanism yet.

## Future Improvements
- Add Google Sheets logging.
- Add status tracking: Pending, Replied, Closed.
- Add error handling and retry logic.
- Improve AI prompt rules to reduce false classification.
