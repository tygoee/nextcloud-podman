# Quadlets

Collection with some of my Quadlet configuration files, or modifications of configurations found on the internet. 

Feel free to contribute if you wrote a better implementation, some things like podman secrets may not have been added yet.

## List of containers

- Nextcloud (Apache) [View ↗](./nextcloud-apache)
- Nextcloud (Caddy) [View ↗](./nextcloud-caddy)
- Technitium [View ↗](./technitium-dns)

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

You are free to use any of these configurations, as long as you agree that THESE FILES ARE PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THESE FILES OR THE USE OR OTHER DEALINGS WITH THESE FILES.