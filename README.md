# Gentoo Overlay
This overlay contains some stuff what I like

## Usage
Just add following lines to /etc/portage/repos.conf/exodev.conf

```
[exodev]
location = /var/db/repos/exodev
sync-type = git
sync-uri = https://github.com/exodev/gentoo-overlay.git
auto-sync = true
```
