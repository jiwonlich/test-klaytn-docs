---
description: >-
Cautions when using `eth` namespace apis in Klaytn.
---

# Namespace caution <a id="namespace-caution"></a>

Klaytn supports `eth` namespace APIs, so Developers who using Ethereum based SDKs or tools now can easily migrate their
existing projects to Klaytn.
(e.g. just replacing endpoint url to Klaytn node in the source code using Ethereum SDKs should work enough.)

But due to the fundamental design differences existing between Klaytn and Ethereum,
there are some APIs that are difficult to fully supported. (e.g. some fields have always zero value, etc...)

This document describes the limitations of those APIs.