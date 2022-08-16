# Threat Stack Kubernetes Deployment Yaml

This file is a template for deploying the Threat Stack agent on Kubernetes. This is meant as a base to build off of. Users may wish to change the namespace, the resource limits, etc.

## Questions?

Please contact Threat Stack support. We are not monitoring issues or pull requests through github.

## Usage

```
# with $DEPLOY_KEY set to your organization's deploy key
sed -i "s/<REPLACE_WITH_VALID_DEPLOY_KEY>/$DEPLOY_KEY/g" TSKubernetesDaemonSet.yaml
kubectl apply -f TSKubernetesDaemonSet.yaml
```

# Contributing

Before you start contributing to any project sponsored by F5, Inc. (F5) on GitHub, you will need to sign a Contributor License Agreement (CLA). This document can be provided to you once you submit a GitHub issue that you contemplate contributing code to, or after you issue a pull request.

If you are signing as an individual, we recommend that you talk to your employer (if applicable) before signing the CLA since some employment agreements may have restrictions on your contributions to other projects. Otherwise by submitting a CLA you represent that you are legally entitled to grant the licenses recited therein.

If your employer has rights to intellectual property that you create, such as your contributions, you represent that you have received permission to make contributions on behalf of that employer, that your employer has waived such rights for your contributions, or that your employer has executed a separate CLA with F5.

If you are signing on behalf of a company, you represent that you are legally entitled to grant the license recited therein. You represent further that each employee of the entity that submits contributions is authorized to submit such contributions on behalf of the entity pursuant to the CLA.

# License

See the [LICENSE.md](LICENSE.md)