# abcd-agentic-training-vnr-nyshada

## My Training Assignments

### Assignment 1: AI-Powered Email Workflow

#### Workflow Description
In this assignment, I developed an automated workflow using the **n8n framework**. The workflow performs the following tasks:

1. **Receive Emails**  
   - The workflow listens for incoming emails using a **Gmail Trigger** in n8n.  
   - Gmail access is established through a **Google OAuth 2.0 client**, which securely connects n8n to Gmail.  

2. **Send Email Content to AI Agent**  
   - The body of each email is sent as a **prompt to Google’s Gemini AI**.  
   - The AI agent requires three inputs: **Chat Model (mandatory)**, **Memory**, and **Tools**.  

3. **Send AI Response via Gmail**  
   - The AI-generated response is then sent to a specified email address using the **Gmail API**, completing the automated email interaction.  

#### Implementation Details
- **n8n Framework**: Orchestrates the workflow and triggers actions based on email events.  
- **Google Cloud**: Provides OAuth 2.0 credentials to authorize secure access to Gmail.  
- **Google AI Studio**: Supplies the API key and configuration for the AI agent.  
- **Automation Logic**:  
  - Gmail Trigger → Send prompt to AI → Receive AI response → Send reply email.  

This workflow demonstrates **integration of AI with automated email processing**, showcasing skills in cloud services, workflow automation, and AI API usage.
