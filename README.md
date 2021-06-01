# goftp-tlsconfig

A fork of [goftp/server](https://gitea.com/goftp/server) with support for
using a custom `tls.Config`.

## Installation

The library can be installed with

```sh
go get github.com/marco/goftp-tlsconfig
```

## Usage

Usage is identical to [goftp/server](https://gitea.com/goftp/server).
`ServerOpts` now supports an additional `TLSConfig` field, which can be set
to nil for an automatic configuration or explicitly set to a `*tls.Config` value.
