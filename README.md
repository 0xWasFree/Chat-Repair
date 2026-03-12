# Chat Repair

> Fork of [op7418/Claude-to-IM-skill](https://github.com/op7418/Claude-to-IM-skill) — enhanced with auto-approve, full session display, and more.

Bridge Claude Code / Codex to IM platforms — chat with AI coding agents from Telegram, Discord, Feishu/Lark, or QQ.

## What's different from upstream?

| Feature | Upstream | Chat Repair |
|---------|----------|-------------|
| Tool permission | Manual approve each time | Auto-approve by default |
| Session ID display | Truncated (8 chars) | Full ID |
| Pre-built bundle | No | Yes, ready to run |

## Quick Install

```bash
git clone https://github.com/0xWasFree/Chat-Repair.git ~/.claude/skills/claude-to-im
cd ~/.claude/skills/claude-to-im && npm install
```

Then in Claude Code:
```
/claude-to-im setup
/claude-to-im start
```

## Roadmap

- [ ] Telegram message chunking improvements for long responses
- [ ] Better session context carry-over on `/new`
- [ ] 1Password secrets integration
- [ ] Multi-model session support

## Credits

This project is a fork of [Claude-to-IM-skill](https://github.com/op7418/Claude-to-IM-skill) by [@op7418](https://github.com/op7418), licensed under MIT.

## License

MIT — see [LICENSE](LICENSE) for details.
