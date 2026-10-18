# davesmods

A Claude Code plugin marketplace for function-hooks mods. Each mod lives in its own repository.

| Mod | What it does |
|---|---|
| [brief-template](https://github.com/davethedev3/brief-template) | Expands an `Agent` prompt that names a markdown brief template and `{{variable}}` values into the finished brief before the agent spawns. |
| [idle-dedupe](https://github.com/davethedev3/idle-dedupe) | Shortens a subagent's `idle_notification` when that agent already delivered its report by `SendMessage` or an earlier idle result. |

## Install

```sh
claude plugin marketplace add davethedev3/davesmods
claude plugin install brief-template@davesmods
claude plugin install idle-dedupe@davesmods
```

Inside a session, `/plugin marketplace add davethedev3/davesmods` and `/plugin install <mod>@davesmods` do the same. Function hooks are an early-access Claude Code feature; these mods were written against 2.1.302.
