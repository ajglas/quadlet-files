# Podman Quadlets 

Systemd quadlets used with Podman and GVisor on Fedora CoreOS.
This repository contains most of my self-hosted services.

## Assumptions
- Podman (rootful)
- Systemd managed quadlets
- SELinux enforcing
- gVisor as runtime (some containers do not work with it, those containers have PodmanArgs=--runtime=runc)
- Container data directory is /srv/
- .container files are in /etc/containers/systemd/ (default rootful containers directory)

