---
title: Using x-ipfs-path
description: The x-ipfs-path header is a legacy way to detect IPFS content over HTTP.
meta:
  - name: robots
    content: noindex, follow
---

# Support for `x-ipfs-path` headers in IPFS Companion

::: callout
**Deprecated.** The `x-ipfs-path` header is a legacy way to detect IPFS content over HTTP. Use [gateway URL conventions](https://specs.ipfs.tech/http-gateways/) and [DNSLink](../concepts/dnslink.md) instead. See the [`x-ipfs-path` glossary entry](../concepts/glossary.md#x-ipfs-path).
:::

`x-ipfs-path` is a legacy HTTP response header. [Gateway URL conventions](https://specs.ipfs.tech/http-gateways/) and [DNSLink](../concepts/dnslink.md) have superseded it as the way to detect and address IPFS content over HTTP.

IPFS Companion can still detect this header, but the option is off by default. You can turn it on under the extension's _Preferences_ screen.
