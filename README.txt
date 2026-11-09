Research Paper Agent — Assignment 1

Purpose
A few-shot prompt specification for Papertrail, a research paper agent. It helps refine a research question, plan a literature search, evaluate provided papers, compare evidence, and draft a cautious synthesis.

Files
- research-paper-agent.json: system instructions and three few-shot examples for evidence-grounded academic assistance.
- README.txt: project overview and build notes.

App
Papertrail was generated in Google AI Studio Build as a responsive research workspace. Its preview is available in the creator's AI Studio account. It includes a research protocol, source library, evidence matrix, literature review draft, and JSON/Markdown export. The agent is instructed not to invent citations or claim it searched unless a search tool actually ran.

Build notes
1. Open https://aistudio.google.com/ and sign in with your Google account.
2. Open Build to create or remix a web app.
3. Use research-paper-agent.json as the agent's core behavior.
4. Keep API credentials in server-side secrets. Never commit private API keys.
5. Verify source claims against the original papers before relying on generated summaries.

Submission
Submit this public repository URL in the assignment's Google Form.
