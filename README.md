# claude-code-mods

The `egonleitner` marketplace for [Claude Code](https://code.claude.com): a catalog of mods,
each developed in its own repository.

## Add the marketplace

```bash
claude plugin marketplace add EgonLeitner/claude-code-mods
```

Then install a mod by its name, for example:

```bash
claude plugin install dashband@egonleitner
```

## Mods

| Mod | What it does |
|---|---|
| [dashband](https://github.com/EgonLeitner/dashband) | Prompt cache, context and plan limits at a glance, in the prompt footer and above the prompt |

Mods need Claude Code 2.1.287 or later and draw in the terminal and in the Code tab of the
Claude Desktop app. A mod runs with your permissions; read its README before installing.

## License

[MIT](LICENSE)
