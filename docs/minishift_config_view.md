## minishift config view

Display the properties and values of the Minishift configuration file.

### Synopsis


Display the properties and values of the Minishift configuration file. You can set the output format from one of the available Go templates.

```
minishift config view
```

### Options

```
      --format string   Go template format to apply to the configuration file. For more information about Go templates, see: https://golang.org/pkg/text/template/
		For the list of configurable variables for the template, see the struct values section of ConfigViewTemplate at: https://godoc.org/github.com/minishift/minishift/cmd/minikube/cmd/config#ConfigViewTemplate (default "- {{.ConfigKey}}: {{.ConfigValue}}\n")
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
* [minishift config](minishift_config.md)	 - Modifies Minishift configuration properties.

