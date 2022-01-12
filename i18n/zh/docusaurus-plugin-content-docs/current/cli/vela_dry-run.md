---
title: vela dry-run
---

Dry Run an application, and output the K8s resources as result to stdout

### Synopsis

Dry-run application locally, render the Kubernetes resources as result to stdout.

```
vela dry-run
```

### Examples

```
vela dry-run
```

### Options

```
  -d, --definition string   specify a definition file or directory, it will only be used in dry-run rather than applied to K8s cluster
  -e, --env string          specify environment name for application
  -f, --file string         application file name (default "./app.yaml")
  -h, --help                help for dry-run
  -n, --namespace string    specify the Kubernetes namespace to use
```

### SEE ALSO



#### Go Back to [CLI Commands](vela) Homepage.


###### Auto generated by spf13/cobra on 10-Jan-2022, refer to [script in KubeVela](https://github.com/oam-dev/kubevela/tree/master/hack/docgen).