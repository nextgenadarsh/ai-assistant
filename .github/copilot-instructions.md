# Repository Copilot Customizations

Keep customizations required for this repository in version-controlled workspace files so they are available to anyone who clones it. Do not rely on personal Copilot instructions, agents, skills, or files stored outside the repository.

## Locations

- Always-on repository guidance: `.github/copilot-instructions.md`
- Custom agents: `.github/agents/<agent-name>.agent.md`
- Skills: `.github/skills/<skill-name>/SKILL.md`; keep any required skill assets in that skill's directory.
- File-specific instructions: `.github/instructions/<name>.instructions.md`
- Reusable prompts: `.github/prompts/<name>.prompt.md`
- Agent support files: `.github/agent-support/<agent-name>/`, outside `.github/agents/` so they are not discovered as separate agents. Keep all agents' support assets under this shared root.

Use descriptive names and the required file formats/frontmatter so VS Code can discover each customization.

For every new or updated custom agent, keep its discoverable definition at `.github/agents/<agent-name>.agent.md` and put all companion files under `.github/agent-support/<agent-name>/`. Do not put supporting files in `.github/agents/` or create agent-specific support folders elsewhere. Reference companion files using repository-relative paths. Create a support directory only when the agent needs supporting files.

## Portability and Privacy

- Use repository-relative paths. Never reference a developer's home directory, user profile customization folder, untracked local file, or machine-specific setup as a required dependency.
- Keep shared agents and skills usable when optional, user-specific information is absent. Ask focused questions instead of assuming it is available.
- Do not put credentials, account details, or personal financial profiles in shared files. Keep user-specific data in a local ignored file or use a sanitized template; ensure the agent can proceed when that local file is absent.
- Document any required extension, tool, or external dependency in the relevant customization.

When adding or changing a repository customization, put the source file in the appropriate path above and include all non-sensitive assets needed by other contributors in the same repository.
