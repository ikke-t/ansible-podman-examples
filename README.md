# ansible-podman-examples

This is to share some of ansible examples for running stuff in podman
containers.

I use these containers at home, hopefully they are useful for you too. They
depend on ansible role [podman_container_systemd](https://galaxy.ansible.com/ikke_t/podman_container_systemd) which uses systemd to make sure containers state.

List of containers:

* [Gogs Git server](https://raw.githubusercontent.com/ikke-t/ansible-podman-examples/master/run-container-gogs-podman.yml)
* [Grafana](https://raw.githubusercontent.com/ikke-t/ansible-podman-examples/master/run-container-grafana-podman.yml)
* [Nextcloud](https://raw.githubusercontent.com/ikke-t/ansible-podman-examples/master/run-container-nextcloud-podman.yml)
* [Node-Red](https://raw.githubusercontent.com/ikke-t/ansible-podman-examples/master/run-container-nodered-podman.yml)
* [OpenHAB](https://raw.githubusercontent.com/ikke-t/ansible-podman-examples/master/run-container-openhab-podman.yml)
* [Pi-Hole](https://raw.githubusercontent.com/ikke-t/ansible-podman-examples/master/run-container-pihole-podman.yml)
* [Unifi Controller](https://raw.githubusercontent.com/ikke-t/ansible-podman-examples/master/run-container-unifi-controller-podman.yml)
