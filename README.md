# Quadlets

Collection with some of my Quadlet configuration files, or modifications of configurations found on the internet.

Feel free to contribute if you wrote a better implementation, some things like podman secrets may not have been added yet.

## List of containers

- Nextcloud (Apache) [View ↗](./nextcloud-apache)
- Nextcloud (Caddy) [View ↗](./nextcloud-caddy)
- Technitium [View ↗](./technitium-dns)
- Crafty [View ↗](./crafty)

## Container directory

The default quadlet container directory for a rootless system is `~/.config/containers/systemd/`. For all system-wide directories, you should take a look at [the documentation](https://docs.podman.io/en/latest/markdown/podman-systemd.unit.5.html#podman-rootful-unit-search-path).

## Fixing Quadlet errors

When quadlets aren't showing up in systemd, it's possible to show the errors by doing a dry run:

```sh
/usr/libexec/podman/quadlet -dryrun -user
```

Omit `-user` when parsing rootful services

## Quadlet documentation

[podman-systemd.unit - systemd units using Podman Quadlet](https://docs.podman.io/en/latest/markdown/podman-systemd.unit.5.html#podman-rootful-unit-search-path)

[Make systemd better for Podman with Quadlet - Red Hat](https://www.redhat.com/en/blog/quadlet-podman)

---

You're free to use any of these configurations however you like
