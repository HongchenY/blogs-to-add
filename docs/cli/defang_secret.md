---
title: defang_secret
---
## defang secret

Add, update, or delete service secrets

### Options

```
  -h, --help   help for secret
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
* [defang secret create](defang_secret_create.md)	 - Adds or updates a secret
* [defang secret ls](defang_secret_ls.md)	 - List secrets
* [defang secret rm](defang_secret_rm.md)	 - Deletes one or more secrets

###### Auto generated by spf13/cobra on 27-Mar-2024
