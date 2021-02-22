# Canonical Candid - Python package

[![Publish](https://github.com/canonical-web-and-design/canonicalwebteam.candid/workflows/Publish/badge.svg)](https://github.com/canonical-web-and-design/canonicalwebteam.store-api/actions?query=workflow%3APublish)

canonicalwebteam.candid provides authentication with Candid, a macaroon-based
authentication service.


See: https://github.com/canonical/candid


This client only support the browser-redirect login protocol that
provides a mechanism for a user to authenticate with candid, and
subsequently discharge macaroons, by redirecting a web browser via
the candid login pages.

## How to install

To install this extension as a requirement in your project, you can use PIP:

```bash
pip install canonicalwebteam.candid
```

See also the documentation for [pip install](https://pip.pypa.io/en/stable/reference/pip_install/).

## Development

The package leverages [poetry](https://poetry.eustace.io/) for dependency management.
