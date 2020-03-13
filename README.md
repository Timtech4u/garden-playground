# Garden Playground

> Garden is a developer tool that automates your workflows and makes developing, testing and deploying Kubernetes applications faster and easier than ever.

- Develop and iterate as quickly with remote clusters as you do locally, and share development clusters with your team. With remote clusters you can even run Garden without Kubernetes or Docker installed on your machine!
- Hot reload lets you near-instantaneously update code and static files in containers as they run, for services that support in-place reloading.
- The built-in web dashboard gives you a full overview of your stack.
- Build, test and deploy Docker containers, Helm charts, OpenFaaS functions and more.
- Garden can be used to make your CI faster and easier to work with. 

**Garden does NOT yet supports gradual rollouts, canary deployments.**


## Next steps
- Connect to your Kubernetes cluster
- Setup your Garden project `garden create project` / edit configs.
- Initialize using `garden plugins kubernetes cluster-init` and run `garden dev` or `garden deploy`

## Garden Modules ( & Services)

- [Helm Chart Module](./docker/garden.yml)
- [Docker Container Module](./helm/garden.yml)
- [Kubernetes Manifests Module](./kubernetes/garden.yml)
- [Remote Git Module](./remote/garden.yml)