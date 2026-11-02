# GHOST Secure Text Mesh — Evaluation Demo v1.0

**Free, runnable Rust technical evaluation for secure and
resilient text communications.**

GHOST Demo v1.0 is a limited, non-production technical
preview of selected GHOST Secure Text Mesh capabilities.

This repository contains real evaluation source code,
tests, technical instructions and applicable license
materials. It does not contain the private Production Core.

## Download the demo

**Linux and Windows x86-64 packages:**

[GitHub Releases](https://github.com/s7nHan/GHOST-Demo-v1/releases)

The release assets will include Linux and Windows ZIP
packages and a SHA-256 verification manifest.

## Technical capabilities

The evaluation demonstrates:

- ML-KEM post-quantum key encapsulation
- ML-DSA post-quantum digital signatures
- AES-256-GCM authenticated encryption
- Shamir Secret Sharing
- Local QUIC-based mesh communication
- Delay-Tolerant Networking (DTN)
- Disconnect, reconnect and delivery scenarios
- Signed acknowledgments
- Replay and security-behavior checks
- Bounded in-memory queueing
- Three-node and isolated-process evaluation scenarios

## Source code and instructions

- [Demo overview and usage](evaluation-demo/README.md)
- [Runtime evaluation instructions](evaluation-demo/public-runtime/EVALUATION-README.md)
- [Cryptographic evaluation source](evaluation-demo/public-crypto/)
- [Network runtime and tests](evaluation-demo/public-runtime/)

Follow the instructions in the linked documents to
build and run the supported evaluation scenarios.

## Scope and limitations

This project is a scripted technical evaluation,
not a production messaging application.

The demonstrated scenarios are local evaluation
scenarios, not a validated multi-host field deployment.

No independent security certification is claimed.

The private GHOST Production Core and commercial
integration rights are not included.

## Licensing

- [GHOST Evaluation License](evaluation-demo/LICENSE-EVALUATION.md)
- [Third-Party Notices](evaluation-demo/THIRD-PARTY-NOTICES.md)

GHOST-owned evaluation materials are subject to the
evaluation license. Third-party materials remain
subject to their respective licenses.

## Main project

[GHOST Secure Text Mesh — Main Repository](https://github.com/s7nHan/Ghost-securetextmesh)

## Technical feedback

Technical review and reproducible feedback are welcome
through GitHub Discussions in the main project.

---

**GHOST Secure Text Mesh**

*Built for resilience. Designed for security.*
