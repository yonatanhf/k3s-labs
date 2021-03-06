# K3s Tutorials

<img src="k3s_logo.png" alt="k3s_logo"  />

This repository has been designed to guide you through basic steps of Kubernetes and Docker. The environment which these tutorials are designed for is [Rancher K3s](https://k3s.io/) running on a 4 node Raspberry Pi 4 cluster. All docker images have been created in multi-arch for AMD64 and ARM64.

To get the most out of these tutorials please follow the below labs in order.

### Setup Up Lab Environment

​	[Download Lab VM](https://github.com/chrisjen83/k3s-labs-vm)

​	[Kubectl Config File](https://github.com/chrisjen83/k3s-labs/tree/master/admin-namespace)

​	Once you have your lab VM running clone via git this repo into the VM.  We will be using these files for all 	of the tutorials.

```
# mkdir -p ~/git/
# cd ~/git
# git clone https://github.com/chrisjen83/k3s-labs.git
```

### Docker Labs

​	[Deploy a Docker Image](https://github.com/chrisjen83/k3s-labs/tree/master/Docker)

​	[Understand Docker Networking](https://github.com/chrisjen83/k3s-labs/blob/master/Docker/Docker-Networking.md)

### Setup Kubernetes

1. [Deploy a K3s Load Balancer](https://github.com/chrisjen83/k3s-labs/tree/master/deploy-metallb)
2. [Deploy MongoDB ARM64](https://github.com/chrisjen83/k3s-labs/tree/master/deploy-mongo)

   #### Dell EMC ECS Metadata Search GUI

   1. [Deploy ECS Metadata Search](https://github.com/chrisjen83/k3s-labs/tree/master/ecs_meta_search)

   #### Photo Album Application

   1. [Deploy Photo Album Web Page](https://github.com/chrisjen83/k3s-labs/tree/master/deploy-photo-album)
   2. https://github.com/chrisjen83/k3s-labs/tree/master/ecs_meta_search)

#### Handy Links

When working with YAML spaces are a critical part of the language.  One wrong space and the YAML is unusable.  I have found a very good YAML formatter which helps you resolve strange syntax and formatting errors in your YAML.  If during the course you have a YAML format or syntax error give this website a go.

[Kubernetes YAML Linter](https://kubeyaml.com/)
