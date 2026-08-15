# Edge Case Mapper

Reviews product goal documents to map end-to-end user flows, proactively flagging missing state transitions, edge cases, and error states. Use when the user wants journey maps, edge-case analysis, state-transition gaps, error-state inventories, flow completeness reviews, "what can go wrong in this flow," or QA-minded product walkthroughs from PRDs/goals. Typical triggers include pre-build flow reviews, missing empty/error states, and onboarding/checkout/auth path audits.

**Type:** Custom Grok agent  
**Compatible with:** Grok Build (native). Also usable as a subagent prompt in Claude Code and similar tools.

## Install

### Grok Build
Copy `agents/user-journey-edge-case-mapper.md` to `~/.grok/agents/` then reload agents (`/agents` or a new session).

### Other coding agents
Treat `agents/user-journey-edge-case-mapper.md` as a custom subagent prompt. Drop it into the agent folder your tool uses (for example `.claude/agents/` or a plugin `agents/` directory).

## Files

- `agents/user-journey-edge-case-mapper.md` — agent prompt (YAML frontmatter + instructions)

## License

MIT © Miranda Komorny
