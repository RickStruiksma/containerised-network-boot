# containerised-network-boot
A collection of K8s containers to enable installing virtual guests over the network

This project aims to create a number of containers that provide a netbooting service on the network, specifically to facilitate the install process for new virtual machines by being able to point to a ready-made image.

Contents (notional):
- Ansible bootstrap script to create a Kubernetes cluster
- Docker private registry to store images for K8s containers
- TFTP server container
- DHCP/BootP container
- Content server container
- K8s services/ingress
- Ancillary K8s objects as needed

29-12-2022
