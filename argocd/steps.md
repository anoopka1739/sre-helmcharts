Our actual workflow
We'll perform these operations manually first, so you understand each step:
1. Identify the trusted upstream Argo CD chart source.
2. Select and pin a chart version.
3. Create your GitHub repository.
4. Define the upstream chart as a dependency.
5. Download and lock the dependency.
6. Customize values.yaml for your EKS cluster.
7. Validate the rendered Kubernetes manifests.
8. Install Argo CD using Helm.
9. Verify that all Argo CD components are healthy.
Later, we can automate this with CI/CD and GitOps.