# Cecil plugins for Claude Code

[Claude Code](https://code.claude.com) plugin marketplace for [Cecil](https://cecil.app), the static site generator.

## Plugins

| Plugin  | Description                                                                                                                                                                        |
| ------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `cecil` | The Cecil [agent skills](https://cecil.app/documentation/ai/agent-skills/): `cecil` (create, configure, build and deploy a site) and `cecil-theme` (create and package a theme). |

The skills are maintained in the [Cecil repository](https://github.com/Cecilapp/Cecil/tree/main/skills): the plugin fetches only that directory.

## Install

In Claude Code:

```text
/plugin marketplace add Cecilapp/claude-plugins
/plugin install cecil@cecil
```

Or from your shell:

```bash
claude plugin marketplace add Cecilapp/claude-plugins
claude plugin install cecil@cecil
```

Then ask Claude to create, build, configure or deploy a Cecil site, or to create a theme: it uses the matching skill automatically. You can also invoke them directly with `/cecil:cecil` and `/cecil:cecil-theme`.

## License

Released under the [EUPL-1.2](LICENSE) license.
