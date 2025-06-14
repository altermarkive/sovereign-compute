# Sovereign Compute

* [Sovereign Compute](sovereign-compute)

# Other Tools

* AWS CLI - [`amazon/aws-cli`](https://hub.docker.com/r/amazon/aws-cli)
* Azure CLI - [`mcr.microsoft.com/azure-cli`](https://hub.docker.com/_/microsoft-azure-cli)
* Expose Docker host ports on Docker networks - [`qoomon/docker-host`](https://github.com/qoomon/docker-host)
* Powerful tunneling software - [`socat`](https://www.redhat.com/sysadmin/getting-started-socat)
* Forward a service on a local port to an SSH jump server - [`autossh`](https://www.harding.motd.ca/autossh/)

# To Do

- Rework Kubernetes example into a local cluster with [kind](https://kind.sigs.k8s.io/docs/user/quick-start#installing-from-release-binaries)
- Replate Tailscale ingress with local-only WireGuard
- Add [Kueue](https://github.com/kubernetes-sigs/kueue) controller to the local cluster
- If necessery to govern the queue with a git repo then consider [Argo](https://github.com/argoproj)
