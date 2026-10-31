# Moonlit Tools for Claude

Ask Claude about your website's saved Moonlit results: what to work on next, why a recommendation matters, and which findings support it.

## Use It

1. Add this plugin, then open its Connectors tab and connect Moonlit.
2. Sign in to Moonlit with an emailed link or your email and password, then approve read-only access.
3. Ask something like "What should I work on next on my website, and what evidence supports it?"

Claude names the website and scan date, gives your Quick Wins and saved recommendations, and explains the linked evidence. If a scan or data source is missing, it says so.

## What It Can Do

The connector has eight read-only tools: the selected website, the latest saved scan, saved recommendations, the evidence for one recommendation, Moonlit's Quick Wins, what changed since the previous comparable scan (new, resolved, improved and worsened findings, plus score movement), a fix packet for one recommendation (a developer handoff with steps and how to tell it's done), and the outcomes of your completed tasks. It can't start scans, connect data sources, change tasks or edit your account. You can disconnect it anytime in Moonlit Settings, under AI Assistants.

## Plans

Every Moonlit plan can connect. On the Free plan Claude sees your Website Health score and up to 3 Quick Wins with their evidence. Launch and higher plans include every recommendation and fix packets. Task outcomes are available on every plan.

## Data

Claude reads your workspace and website names, saved scans, recommendations, Quick Wins, their evidence and the tasks you marked complete through `mcp.moonlit.tools`, using your own Moonlit sign-in. The connector stores none of it, and Moonlit doesn't store what you ask Claude.

## Help and Privacy

- Setup help: https://www.moonlit.tools/ai-assistants
- Privacy policy: https://www.moonlit.tools/privacy
- Support: hello@moonlit.tools

## License

MIT. See `LICENSE`.
