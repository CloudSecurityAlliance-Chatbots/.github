# CloudSecurityAlliance-Chatbots

Chatbot configurations, datasets, and supporting files for CSA conversational interfaces.

## CCSK Orb

The **CCSK Orb** chatbot ([ccsk-orb.cloudsecurityalliance.org](https://ccsk-orb.cloudsecurityalliance.org)) helps users study for the CCSKv5 (Certificate of Cloud Security Knowledge v5) certification. It uses a customized LibreChat instance backed by OpenAI with RAG over the CCSK v5 curriculum.

| Repo | Purpose | Public? |
|------|---------|---------|
| [chatbot-ccsk-orb-librechat](https://github.com/CloudSecurityAlliance-Chatbots/chatbot-ccsk-orb-librechat) | LibreChat fork — React frontend, Node.js API, Docker deployment | Yes |
| [chatbot-ccsk-orb-data](https://github.com/CloudSecurityAlliance-Chatbots/chatbot-ccsk-orb-data) | CCSK v5 curriculum content (markdown), system prompts, data pipeline | Yes |
| chatbot-ccsk-orb-librechat-config | Production config, secrets, branding, server ops scripts, operations runbook | Private |

## Other Repos

| Repo | Purpose |
|------|---------|
| [chatbot-CCSKv5-data](https://github.com/CloudSecurityAlliance-Chatbots/chatbot-CCSKv5-data) | Alternate/legacy CCSK v5 data pipeline with PDF conversion scripts |
| [chatbot-internal-iso-qms](https://github.com/CloudSecurityAlliance-Chatbots/chatbot-internal-iso-qms) | Internal ISO QMS chatbot |
