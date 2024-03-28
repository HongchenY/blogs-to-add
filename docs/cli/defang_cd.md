---
title: defang_cd
---
## defang cd

Manually run a command with the CD task

### Options

```
  -h, --help   help for cd
```

### Options inherited from parent commands

```
  -s, --cluster string      Defang cluster to connect to (default "fabric-prod1.defang.dev")
      --color color-mode    Colorize output; "auto", "always" or "never" (default auto)
  -C, --cwd string          Change directory before running the command
      --debug               Debug logging for troubleshooting the CLI
      --dry-run             Dry run (don't actually change anything)
  -f, --file string         Compose file path (default "*compose.y*ml")
  -T, --non-interactive     Disable interactive prompts / no TTY
  -P, --provider provider   Cloud provider to use; use "aws" for bring-your-own-cloud (default auto)
  -v, --verbose             Verbose logging
```

### SEE ALSO

* [defang](defang.md)	 - Defang CLI manages services on the Defang cluster
* [defang cd cancel](defang_cd_cancel.md)	 - Cancel the current CD operation
* [defang cd destroy](defang_cd_destroy.md)	 - Destroy the service stack
* [defang cd down](defang_cd_down.md)	 - Refresh and then destroy the service stack
* [defang cd ls](defang_cd_ls.md)	 - List all the projects and stacks in the CD cluster
* [defang cd refresh](defang_cd_refresh.md)	 - Refresh the service stack
* [defang cd teardown](defang_cd_teardown.md)	 - Destroy the CD cluster without destroying the services

###### Auto generated by spf13/cobra on 27-Mar-2024