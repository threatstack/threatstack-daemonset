# Threat Stack Kubernetes Deployment Yaml

This file is a template for deploying the Threat Stack agent on Kubernetes. This is meant as a base to build off of. Users may wish to change the namespace, the resource limits, etc.

## Questions?

Please contact Threat Stack support. We are not monitoring issues or pull requests through github.

## Usage

```
# with $DEPLOY_KEY set to your organization's deploy key
sed -i 's/<REPLACE_WITH_VALID_DEPLOY_KEY>/$DEPLOY_KEY/g' TSKubernetesDaemonSet.yaml
kubectl apply -f TSKubernetesDaemonSet.yaml
```
