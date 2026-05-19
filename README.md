# Gluetun servers

This repository contains the servers data available in [Gluetun](https://github.com/qdm12/gluetun).

Each update of the servers data corresponds to a new release of gluetun-servers.

Gluetun imports the servers data from this repository as a Go module, using the `go.mod` file to specify the version of the module to use, also known as the "servers version".

Every month, all the servers data is updated by a Github Action workflow using the latest gluetun program version (credits to @shwoop)
