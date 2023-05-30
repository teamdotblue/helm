## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

`helm repo add teamdotblue https://teamdotblue.github.io/helm`

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo teamdotblue`
to see the charts.

To install the <chart-name> chart:

```console
helm install my-<chart-name> teamdotblue/<chart-name>
```

To uninstall the chart:

```console
helm delete my-<chart-name>
```

## Charts available

- [Repman](https://github.com/repman-io/repman) - [Chart source available](https://github.com/teamdotblue/helm/tree/main/charts/repman)