# Unofficial Helm chart for self-hosted AFFINE

Helm chart to easily deploy [AFFINE](https://github.com/toeverything/AFFiNE).

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add affine-chart https://chandr-andr.github.io/affine-chart

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
affine-chart` to see the charts.