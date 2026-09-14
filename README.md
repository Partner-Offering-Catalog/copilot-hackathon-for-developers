# Copilot Hackathon for Developers

This repository is a safe starting point for exploring GitHub Copilot custom
agents, skills, prompts, hooks, and repository guidance. It intentionally
contains no application code and does not create issues or projects on this
template repository.

## Participant walkthrough

1. Install [GitHub Copilot for Desktop](https://github.com/features/copilot)
   and sign in with the GitHub account supplied for the training.
2. In Copilot for Desktop, choose **Open repository** (or **Clone repository**)
   and clone your own repository created from this template. Do not run the
   exercises against this template repository.
3. Open the cloned folder in Visual Studio Code. Install the GitHub Copilot
   and GitHub Copilot Chat extensions when prompted, then sign in with the
   same account.
4. In Copilot Chat, select **Agent** mode. The custom agents in
   `.github/agents/` and prompts in `.github/prompts/` are available after the
   repository is trusted and opened.
5. Begin with the `plan-feature` prompt. The Backlog Analyst will ask
   clarifying questions, then creates a plan in *your* exercise repository.
   Continue through design, implementation, testing, operations, and
   documentation prompts.

## Suggested exercise

Ask the Backlog Analyst to plan a small application such as a team task list.
Answer its questions, review the created backlog, then use the Designer and
Developer agents to deliver one feature at a time. Let the DevOps Engineer
propose automation only after there is application code to automate.

## Repository map

| Location | Purpose |
| --- | --- |
| `.github/agents/` | Custom agent definitions |
| `.github/skills/` | Reusable skills for canvas, private gists, and knowledge bases |
| `.github/prompts/` | Starting prompts for each SDLC phase |
| `.github/hooks/` | Optional VS Code agent-hook examples |
| `.github/ISSUE_TEMPLATE/` | Bug and feature issue forms |
| `.vscode/mcp.json` | Microsoft Learn MCP server configuration |
| `docs/` | Application knowledge base content |

## Working safely

- Create issues, projects, milestones, branches, pull requests, gists, and
  deployments only in the repository you created from this template.
- Review every Copilot-proposed command and change before accepting it.
- Keep secrets out of prompts, commits, gists, and documentation.
- Custom agent definitions are maintained by repository owners. Agents must
  not modify `.github/` except GitHub Actions workflows when explicitly asked.

## Maintaining the template

Repository owners can adapt the agent instructions and prompts to suit their
organization. Keep `docs/` current as the application evolves, and update the
knowledge-base skill if the documentation platform or ownership changes.