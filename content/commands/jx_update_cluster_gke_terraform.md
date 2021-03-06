---
date: 2018-08-11T09:36:54Z
title: "jx update cluster gke terraform"
slug: jx_update_cluster_gke_terraform
url: /commands/jx_update_cluster_gke_terraform/
---
## jx update cluster gke terraform

Updates an existing kubernetes cluster on GKE using Terraform: Runs on Google Cloud

### Synopsis

Command re-applies the terraform plan in ~/.jx/clusters/ <cluster>/terraform against the specified cluster

```
jx update cluster gke terraform [flags]
```

### Examples

```
  jx update cluster gke terraform
```

### Options

```
  -b, --batch-mode               In batch mode the command never prompts for user input
  -n, --cluster-name string      The name of this cluster
      --headless                 Enable headless operation if using browser automation
  -h, --help                     help for terraform
      --install-dependencies     Should any required dependencies be installed automatically
      --no-brew                  Disables the use of brew on MacOS to install or upgrade command line dependencies
      --service-account string   Use a service account to login to GCE
      --skip-login               Skip Google auth if already logged in via gloud auth
      --verbose                  Enable verbose logging
```

### SEE ALSO

* [jx update cluster gke](/commands/jx_update_cluster_gke/)	 - Updates an existing kubernetes cluster on GKE: Runs on Google Cloud

###### Auto generated by spf13/cobra on 11-Aug-2018
