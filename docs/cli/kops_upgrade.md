## kops upgrade

Upgrade a kubernetes cluster.

### Synopsis


Automates checking for and applying Kubernetes updates. This upgrades a cluster to the latest recommended production ready k8s version. After this command is run usekops update cluder, and kops rollingupdate cluster to finish a cluster upgrade.

### Examples

```
  # Upgrade a cluster's Kubernetes version.
  kops upgrade cluster kubernetes-cluster.example.com --yes --state=s3://kops-state-1234
```

### Options inherited from parent commands

```
      --alsologtostderr                  log to standard error as well as files
      --config string                    config file (default is $HOME/.kops.yaml)
      --log_backtrace_at traceLocation   when logging hits line file:N, emit a stack trace (default :0)
      --log_dir string                   If non-empty, write log files in this directory
      --logtostderr                      log to standard error instead of files (default false)
      --name string                      Name of cluster
      --state string                     Location of state storage
      --stderrthreshold severity         logs at or above this threshold go to stderr (default 2)
  -v, --v Level                          log level for V logs
      --vmodule moduleSpec               comma-separated list of pattern=N settings for file-filtered logging
```

### SEE ALSO
* [kops](kops.md)	 - kops is Kubernetes ops.
* [kops upgrade cluster](kops_upgrade_cluster.md)	 - Upgrade a kubernetes cluster.

