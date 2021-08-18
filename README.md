# helm-prometheus-spring
Prometheus helm chart which is able to scrape spring boot apps.


## Helm Chart Repo Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

helm repo add helm-prometheus-spring https://jwindhaber.github.io/helm-prometheus-spring

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages. You can then run `helm search repo helm-prometheus-spring` to see the charts.

To install the efk chart:

    helm install my-prometheus-spring helm-prometheus-spring/prometheus-spring

To uninstall the chart:

    helm delete helm-prometheus-spring
