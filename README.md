## Usage

kruise helm chart for special CRDs for kubernetes.
Based on https://github.com/openkruise/kruise
Is needed for docker-garbage-collector -> AdvancedCronJob

How to install:

```shell
    export CHART_NAME=kruise
    export CHART_REPO_NAME=kruise-chart
    helm repo add $CHART_REPO_NAME https://iits-consulting.github.io/$CHART_REPO_NAME/
    helm search repo $CHART_NAME
    helm install $CHART_NAME $CHART_REPO_NAME/$CHART_NAME
```