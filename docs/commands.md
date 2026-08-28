# Commands

The primary command is `/backpack`. Established aliases are `/vbp` and `/bp`.
Use the primary form in server documentation and scripts where possible.

## Player Commands

| Command | Description | Permission |
|---|---|---|
| `/backpack help` | Show available commands | None |
| `/backpack info` | View plugin information | `vackstudio.vacks.command.info` |
| `/backpack update` | Check for updates asynchronously | `vackstudio.vacks.command.update` |
| `/backpack give <player> <tier>` | Give a backpack | `vackstudio.vacks.command.give` |

## Admin Commands

| Command | Description | Permission |
|---|---|---|
| `/backpack admin inspect [player]` | Open the read-only Backpack Inspector | `vbackpack.admin.inspect` |
| `/backpack inspect [held\|<player>\|uuid <backpack-uuid>]` | Inspect backpack state | `vackstudio.vacks.admin.inspect` |
| `/backpack artifact list` | List registered Artifacts | `vackstudio.vacks.admin.artifact.list` |
| `/backpack artifact give <player> <artifact> [level]` | Give an Artifact | `vackstudio.vacks.admin.artifact.give` |
| `/backpack artifact inspect` | Inspect a held Artifact | `vackstudio.vacks.admin.inspect` |
| `/backpack admin diagnostics` | Show a compact support summary | `vackstudio.vacks.admin.diagnostics` |
| `/backpack admin player <player>` | Show a read-only player summary | `vackstudio.vacks.admin.player` |
| `/backpack admin storage status` | View storage status | `vackstudio.vacks.admin.diagnostics` |
| `/backpack admin storage inspect <uuid>` | Inspect one backpack's storage | `vackstudio.vacks.admin.storage.inspect` |
| `/backpack admin achievements <player>` | Inspect Achievement counts | `vackstudio.vacks.admin.achievements.inspect` |

Some advanced diagnostic and recovery subcommands have separate permissions;
see [Permissions](permissions.md). Secret Achievement criteria are not exposed
by the documentation or inspection summary.

[← Documentation Home](index.md) · [Next: Permissions →](permissions.md)
