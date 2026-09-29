# 0bull plugins for Claude

Plugins that connect Claude to [0bull](https://0bull.net), real iPhones rented by the month.

| Plugin | What it does |
| --- | --- |
| [`0bull`](plugins/0bull) | See and operate your rented iPhones: screenshots, on-screen text, taps, swipes, typing, device commands, recorded macros and the on-phone agent. |

## Install in Claude Code

```
/plugin marketplace add 0bull/claude-plugin
/plugin install 0bull@0bull
```

Then run `/mcp`, choose `0bull` and sign in with your 0bull account.

## Develop

```
claude plugin validate ./plugins/0bull --strict
claude plugin validate . --strict
```
