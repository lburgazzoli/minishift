## minishift stop

Stops the running local OpenShift cluster.

### Synopsis


Stops the running local OpenShift cluster. This command stops the Minishift
VM but does not delete any associated files. To start the cluster again, use the 'minishift start' command.

```
minishift stop
```

### Options inherited from parent commands

```
      --alsologtostderr value          log to standard error as well as files
      --log-flush-frequency duration   Maximum number of seconds between log flushes (default 5s)
      --log_backtrace_at value         when logging hits line file:N, emit a stack trace (default :0)
      --log_dir value                  If non-empty, write log files in this directory
      --logtostderr value              log to standard error instead of files
      --password string                Password for the virtual machine.
      --show-libmachine-logs           Show logs from libmachine.
      --stderrthreshold value          logs at or above this threshold go to stderr (default 2)
      --username string                User name for the virtual machine.
  -v, --v value                        log level for V logs
      --vmodule value                  comma-separated list of pattern=N settings for file-filtered logging
```

### SEE ALSO
* [minishift](minishift.md)	 - Minishift is a tool for application development in local OpenShift clusters.

