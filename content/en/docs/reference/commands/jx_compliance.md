---
date: 2020-09-02T10:36:03-04:00
title: "jx compliance"
slug: jx_compliance
url: /commands/jx_compliance/
description: list of jx commands
---
## jx compliance

Run compliance tests against Kubernetes cluster

### Synopsis

Run compliance tests against Kubernetes cluster

```
jx compliance ACTION [flags]
```

### Options

```
  -h, --help   help for compliance
```

### Options inherited from parent commands

```
  -b, --batch-mode   Runs in batch mode without prompting for user input
      --verbose      Enables verbose output. The environment variable JX_LOG_LEVEL has precedence over this flag and allows setting the logging level to any value of: panic, fatal, error, warn, info, debug, trace
```

### SEE ALSO

* [jx](/commands/jx/)	 - jx is a command line tool for working with Jenkins X
* [jx compliance delete](/commands/jx_compliance_delete/)	 - Deletes the Kubernetes resources allocated by the compliance tests
* [jx compliance logs](/commands/jx_compliance_logs/)	 - Prints the logs of compliance tests
* [jx compliance results](/commands/jx_compliance_results/)	 - Shows the results of compliance tests
* [jx compliance run](/commands/jx_compliance_run/)	 - Runs the compliance tests
* [jx compliance status](/commands/jx_compliance_status/)	 - Retrieves the status of compliance tests

###### Auto generated by spf13/cobra on 2-Sep-2020
