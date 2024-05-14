# cincodebio-helm-chart


```fallback
## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add scce https://colm-brandon-ul.github.io/cincodebio-helm-chart/

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
scce` to see the charts.

To install the cinco-de-bio chart:

    helm install my-cinco-de-bio scce/cinco-de-bio

To uninstall the chart:

    helm delete my-<chart-name>
```
