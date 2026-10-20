# DataCrate360 Homebrew tap

```sh
brew trust --formula datacrate360/tap/agent-countercheck   # once: Homebrew 7 asks before loading a third-party tap's formula
brew install datacrate360/tap/agent-countercheck
```

| Formula | Command | What it is |
|---|---|---|
| `agent-countercheck` | `countercheck` | Proof that AI agents' work really happened: re-runs your checks in a clean copy the agent can't edit, and writes a sealed receipt. [Source](https://github.com/datacrate360/agent-countercheck) |

`countercheck` was the formula's name up to v0.3.1; `formula_renames.json` moves existing installs to
`agent-countercheck` on the next `brew upgrade`.
