# BridgeAAC

Communication is a fundamental human right, not a luxury feature.

BridgeAAC is an open-source, offline-first Augmentative and Alternative Communication (AAC) organization built to ensure no one is locked out of speaking due to arbitrary paywalls, expensive subscriptions, or hardware limitations. We build 100% free software that runs locally on the devices people already own.

**Our Core Philosophy**

* **Zero Cost:** No upfront app fees, no recurring subscriptions, and no hidden in-app purchases.
* **100% Local Privacy:** Your voice, your vocabulary, and your data stay completely on your device. No cloud accounts or tracking required.
* **Universal Access:** Designed to run seamlessly across iOS, Android, Windows, macOS, Linux, ChromeOS, and the open web.
* **Format Interoperability:** Native support for Open Board Format (`.obf`, `.obz`), custom BridgeAAC (`.bridge`) packages, and standard archive-based SQLite vocabulary exports—ensuring users and speech-language pathologists retain full ownership and portability of their custom communication boards.

**Our Tech Stack**

We rely on modern, offline-first web technologies to deliver zero-latency speech and broad cross-platform compatibility without sacrificing performance:

* **Architecture:** TypeScript, Vite, Progressive Web App (PWA) standards, and lightweight native wrappers.
* **Speech Engine:** A multi-tier local synthesis system utilizing OS Native Speech, downloadable Piper VITS Neural Offline Models (ONNX via OPFS), and zero-megabyte Web Audio fallbacks.
* **Local Storage:** Origin Private File System (OPFS), IndexedDB caching, and in-browser WebAssembly SQLite (`sql.js`).

**Get Involved**

BridgeAAC is built by independent developers, educators, and the open-source community. Whether you write code, test accessibility features, or design AAC symbol boards, your contributions keep this project alive and free.

* **Launch the App:** [bridgeaac.org](https://bridgeaac.org)
* **Contribute Code:** Check out the `core` repository below to submit pull requests, optimize our local speech engine, or expand our open board parser.
* **Report Issues:** Open a ticket in our issue tracker for bug reports, device testing feedback, or accessibility requests.

**Legal & Licensing**

BridgeAAC is an independent open-source project released under the **MIT License** and is not affiliated with, endorsed by, or sponsored by any commercial AAC hardware or software vendor. File format importers are provided strictly for user data portability and interoperability.
