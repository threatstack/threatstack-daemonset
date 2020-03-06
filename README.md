# Threat Stack Kubernetes Deployment Yamls

These files are templates for deploying the Threat Stack agent on Kubernetes. This is meant as a base to build customer-specific orchestration of the Threat Stack agent. Users may wish to change the namespace, the resource limits, etc.

The `TSGKEDaemonSet.yaml` has some small modifications for the template to work more seamlessly with GKE kubernetes clusters.

## Questions?

Please contact Threat Stack support. We are not monitoring issues or pull requests through github.

## Usage

```
# with $DEPLOY_KEY set to your organization's deploy key
sed -i "s/<REPLACE_WITH_VALID_DEPLOY_KEY>/$DEPLOY_KEY/g" TSKubernetesDaemonSet.yaml
kubectl apply -f TSKubernetesDaemonSet.yaml
```
