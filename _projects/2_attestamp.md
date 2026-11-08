---
layout: page
title: Attestamp
description: Remote attestation that makes the hash of code running in a TEE trustworthy
logo: /assets/img/projects/attestamp.svg
importance: 2
category: work
github: https://github.com/spicslab-kr/tee-blockchain
---

**[SPICS Lab](https://spicslab.kr/), Kyung Hee University × [Datarmor](https://datarmor.ai/) · 2026 · Go, AWS Nitro Enclaves, Ethereum/Solidity**

Software runs inside a TEE. An independent auditor rebuilds it, confirms the enclave runs exactly those bytes, and registers the measurement on an Ethereum-compatible chain.
Anyone can then ask the enclave to attest itself and compare against the on-chain value — no trusted key required.

- Reproducible builds: pinned Go toolchain, `-trimpath`, identical measurements across vendor and auditor machines

[GitHub](https://github.com/spicslab-kr/tee-blockchain)
