# CLiOS

Public resources for CLiOS -- the native iOS command center for OpenClaw.

## Install Skill

```bash
openclaw skills install --from github:verkh-agents/clios/skills/clios
```

Or manually:
```bash
git clone https://github.com/verkh-agents/clios.git /tmp/clios && cp -r /tmp/clios/skills/clios ~/.openclaw/workspace/skills/ && rm -rf /tmp/clios
```

## What's Inside

- `skills/clios/` -- Agent skill for card-based output (GitHub PRs, email drafts, TODO, digest, etc.)
- `docs/CONNECTION-PROTOCOL.md` -- Full WebSocket connection protocol with ed25519 device auth
- `docs/CARD-PROTOCOL.md` -- Card format specification and capability negotiation

## Links

- [CLiOS App](https://github.com/lolkalol9112/openclaw-ios) (private)
- [OpenClaw](https://openclaw.ai)
