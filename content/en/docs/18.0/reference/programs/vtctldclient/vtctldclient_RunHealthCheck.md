---
title: RunHealthCheck
series: vtctldclient
commit: 9a6f5262f7707ff80ce85c111d2ff686d85d29cc
---
## vtctldclient RunHealthCheck

Runs a healthcheck on the remote tablet.

```
vtctldclient RunHealthCheck <tablet_alias>
```

### Options

```
  -h, --help   help for RunHealthCheck
```

### Options inherited from parent commands

```
      --action_timeout duration   timeout to use for the command (default 1h0m0s)
      --compact                   use compact format for otherwise verbose outputs
      --server string             server to use for the connection (required)
```

### SEE ALSO

* [vtctldclient](../)	 - Executes a cluster management command on the remote vtctld server.

