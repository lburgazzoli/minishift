## minishift service list

Gets the URLs of the services in your local cluster.

### Synopsis


Gets the URLs of the services in your local cluster.

```
minishift service list [flags]
```

### Options

```
  -n, --namespace string   The namespace of the services.
```

### Options inherited from parent commands

```
      --alsologtostderr value          log to standard error as well as files
      --format string                  The URL format of the service. (default "http://{{.IP}}:{{.Port}}")
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
* [minishift service](minishift_service.md)	 - Prints the URL for the specified service to the console.

