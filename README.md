# CargOS

[CargOS](http://www.cargos.io/) is a minimal operating system intended to provide a thin layer between
the [Docker](https://www.docker.io/) daemon and the hardware (phsyical or virtual).

It's a no-nonsense operating system intended for one purpose, and one purpose only: to run Docker. It's kept minimal and simple without any tools or services that get in your way like Systemd.

This repository functions as the "entrypoint" for the actual repositories that
contain the CargOS sources. Please refer to the section below for more information
on them.

## Documentation

Documentation on how to install and use CargOS can be found in [the wiki](https://github.com/RedCoolBeans/CargOS/wiki).

## Subprojects

CargOS itself is just the bare minimum based on [Busybox](http://www.busybox.net/) with
a very small set of packages installed by default. Additional packages are installed
via pkgsrc.

- [cargos-buildroot](https://github.com/RedCoolBeans/cargos-buildroot) -- core
- [cargos-pkgsrc](https://github.com/RedCoolBeans/pkgsrc-cargos) -- base + additional packages

## Downloading

The latest release of CargOS will always be available via the [CargOS homepage](http://www.cargos.io/).
