## helm inspect values

shows inspect values

### Synopsis



This command inspects a chart (directory, file, or URL) and displays the contents
of the values.yaml file


```
helm inspect values [CHART]
```

### Options

```
      --keyring string   path to the keyring containing public verification keys (default "/Users/mattbutcher/.gnupg/pubring.gpg")
      --verify           verify the provenance data for this chart
      --version string   version of the chart. By default, the newest chart is shown
```

### Options inherited from parent commands

```
      --debug                 enable verbose output
      --home string           location of your Helm config. Overrides $HELM_HOME (default "/Users/mattbutcher/Code/helm_home")
      --host string           address of tiller. Overrides $HELM_HOST
      --kube-context string   name of the kubeconfig context to use
```

### SEE ALSO
* [helm inspect](helm_inspect.md)	 - inspect a chart

###### Auto generated by spf13/cobra on 1-Nov-2016
