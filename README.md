# Kubernetes in Azure (AKS)

This repo lists my demo definition files, which you can use as a template to deploy your own containerised apps in Azure Container Services (AKS) with Kubernetes.
There are effectively 3 files:
- Pod one: to create smallest container unit in AKS;
- Deployment: this is now more robust deployment, with a number of desired pods, so that AKS do its magic with self-healing;
- Service: that is the way to enable access to your solution from the public network. It would automatically deploy Azure LoadBalancer for you as a part of the setup

Any questions, feel free to reach out to me to discuss or create a new pull requests, if you want to extend anything here further.
