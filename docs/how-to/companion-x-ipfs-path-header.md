---
title: Using x-ipfs-path
description: The x-ipfs-path header is a legacy way to detect IPFS content over HTTP.
meta:
  - name: robots
    content: noindex, follow
---

# Support for `x-ipfs-path` headers in IPFS Companion

::: danger

## `x-ipfs-path` support is deprecated

The `x-ipfs-path` HTTP header is a legacy way to detect IPFS content over HTTP. [Gateway URL conventions](https://specs.ipfs.tech/http-gateways/) and [DNSLink](../concepts/dnslink.md) have superseded it. This page is provided for reference only; see the [`x-ipfs-path` glossary entry](../concepts/glossary.md#x-ipfs-path).

:::

`x-ipfs-path` is an HTTP response header that some IPFS gateways add to name the IPFS path of the content they return. IPFS Companion can still detect it, but the option is off by default. You can turn it on under the extension's _Preferences_ screen.
