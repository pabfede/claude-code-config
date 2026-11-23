# Claude Code Configuration

My personal Claude Code settings and configuration. Use this as reference or customize for your own setup.

## Contents

- **settings.json** – Main configuration file with:
  - Model preferences (Haiku for cost optimization)
  - Permission allowlist for common commands
  - Enabled plugins and skill marketplaces
  - Hook configurations
  - Theme and update settings

## Setup

To use this configuration:

```bash
# Option 1: Copy to your Claude Code config directory
cp settings.json ~/.claude/settings.json

# Option 2: Merge with existing settings
# (manually merge the JSON, being careful with hooks)
```

### Installed Plugins

- **expo** – Expo and EAS CLI integration
- **firecrawl** – Web scraping and research
- **superpowers** – Advanced development workflows
- **ponytail** – Lazy code generation
- **skill-creator** – Custom skill development
- **code-simplifier** – Code quality improvements
- **playwright** – Browser automation
- **context7** – Library documentation
- **skillspector** – Skill validation
- **task-observer** – Task tracking

### Skill Marketplaces

- **skillspector** – TronJuan/skillspector-claude-skill
- **ponytail** – DietrichGebert/ponytail
- **task-observer** – rebelytics/one-skill-to-rule-them-all
- **lemo-opuscar** – lemomo-ai/lemo-opuscar

## Notes

- Uses Haiku model by default for cost efficiency
- Includes pre-approved bash commands for common tools
- Hooks to `~/.pixel-agents/hooks/` for extended integrations
- Dark theme preferred

---

Customize permissions, model choice, and enabled plugins based on your needs!
