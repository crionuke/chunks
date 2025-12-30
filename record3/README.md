Record #3, multi agents on github actions

Failed to run a couple of Claude Code agents communicating with each other via GitHub comments or issues using the
default tooling provided by Anthropic’s claude-code-action.

Mostly because:

- the Claude Code action works with and updates only a single GitHub comment
- GitHub Actions do not trigger sub-workflow executions

Switched back to implementing the idea on my own infrastructure, with my own rules.

#records #claude #agents #github