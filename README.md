# AI Automation Chatbot for Grocery Inventory

## Project Overview
This project uses AI-powered automation to manage a grocery inventory system. It allows users to interact with a chatbot to view or update inventory, powered by OpenAI GPT and Google Sheets. The workflow is built using the n8n automation platform and deployed on the cloud.

## Tech Stack
- Automation Workflow: n8n
- AI Chat Model: OpenAI ChatGPT
- Memory Management: Simple Memory (n8n)
- Database: Google Sheets
- Frontend: n8n Hosted Chat
- Hosting: n8n Cloud

## How it Works
1. Trigger: Workflow starts when a user sends a message in the hosted chat.
2. AI Agent: Message is passed to an AI Agent using OpenAI’s ChatGPT model.
3. Intent Handling: The AI decides whether the user wants to search or update inventory.
4. Search Inventory: Reads item quantity from Google Sheets.
5. Update Inventory: Modifies item quantity in Google Sheets.

## Example Interactions
- Search:
  User: “Do we have apples?”
  Bot: “Yes, we currently have 50 apples in stock.”
- Update:
  User: “Add 10 oranges to the stock.”
  Bot: “Updated! Oranges now have a total of 18 in stock.”

## Google Sheet Structure
| Item Name | Quantity in Stock |
|-----------|-------------------|
| Apples    | 50                |
| Bananas   | 10                |
| ...       | ...               |

## Advantages
- 24/7 virtual store assistant
- Real-time inventory updates
- Easy integration with Google Workspace
- AI with memory allows personalized conversations


