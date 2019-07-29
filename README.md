# ansible-podman-examples

This is to share some of ansible examples for running stuff in podman
containers.

I use these containers at home, hopefully they are useful for you too. They
depend on ansible role [podman_container_systemd](https://galaxy.ansible.com/ikke_t/podman_container_systemd) which uses systemd to make sure containers state.

List of containers:

* [Grafana](./run_container-grafana-podman.yml)
* [Gogs Git server](./run_container-gogs-podman.yml)
* [Nextcloud](./run_container-nextcloud-podman.yml)
* [Node-Red](./run_container-nodered-podman.yml)
* [OpenHAB](./run_container-openhab-podman.yml)
* [Pi-Hole](./run_container-pihole-podman.yml)
* [Unifi Controller](./run_container-unifi-controller-podman.yml)
