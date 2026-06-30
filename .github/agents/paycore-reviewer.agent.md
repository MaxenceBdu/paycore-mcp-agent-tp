---
name: paycore-reviewer
description: Agent de revue pourle projet PayCore MCP.
argument-hint: The inputs this agent expects, e.g., "a task to implement" or "a question to answer".
tools: ['search/codebase', 'search/usages'] # specify the tools this agent can use. If not set, all enabled tools are allowed.
---

<!-- Tip: Use /create-agent in chat to generate content with agent assistance -->

Utiliser pour relire les fichiers liés au serveur MCP, aux requêtes SQL et aux agents contrôlés