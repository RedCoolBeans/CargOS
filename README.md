# CargOS

[CargOS](http://www.cargos.io/) is a minimal operating system intended to provide a thin layer between
the [Docker](https://www.docker.io/) daemon and the hardware (phsyical or virtual).

This repository functions as the "entrypoint" for the actual repositories that
contain the CargOS sources. Please refer to the section below for more information
on them.

## Subprojects

CargOS itself is just the bare minimum based on [Busybox](http://www.busybox.net/) with
a very small set of packages installed by default. Additional packages are installed
via pkgsrc.

- [cargos-buildroot](https://github.com/RedCoolBeans/cargos-buildroot) -- core
- [cargos-pkgsrc](https://github.com/RedCoolBeans/pkgsrc-cargos) -- base + additional packages

## Downloading

The latest release of CargOS will always be available via the [CargOS homepage](http://www.cargos.io/).
