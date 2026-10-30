# BridgeAAC

Communication is a fundamental human right, not a luxury feature.

BridgeAAC is an open-source, offline-first Augmentative and Alternative Communication (AAC) organization built to ensure no one is locked out of speaking due to arbitrary paywalls, expensive subscriptions, or hardware limitations. We build 100% free software that runs locally on the devices people already own.

**Our Core Philosophy**

* **Zero Cost:** No $300 upfront app fees, no recurring subscriptions, and no hidden in-app purchases.
* **100% Local Privacy:** Your voice, your vocabulary, and your data stay completely on your device. No cloud accounts required.
* **Universal Access:** Designed to run seamlessly across iOS, Android, Windows, Linux, and the open web.
* **Format Freedom:** Native support for loading existing TouchChat (`.ce`, `.c4v`), Open Board Format (`.obf`), and custom BridgeAAC (`.bridge`) vocabulary files directly.

**Our Tech Stack**


We rely on offline-first web technologies to deliver zero-latency speech and broad cross-platform compatibility without sacrificing performance:

* **Architecture:** TypeScript, Vite, PWA, and Electron/WebAPK wrappers.
* **Speech Engine:** A 5-tier local system utilizing OS Native Speech, downloadable Piper VITS Neural Offline Models (ONNX via OPFS), and zero-megabyte Web Audio fallbacks.
* **Local Storage:** Origin Private File System (OPFS), IndexedDB caching, and in-browser WebAssembly SQLite (`sql.js`).

**Get Involved**


BridgeAAC is built by independent developers and the FOSS community. Whether you write code, test accessibility features, or design AAC pictograms, your contributions keep this project alive and free.

* **Use the App:** [bridgeaac.org](https://bridgeaac.org)
* **Contribute Code:** Check out the main `core` repository below to submit pull requests, optimize our local speech engine, or expand our `.ce` file parsing.
* **Report Issues:** Open a ticket in our issue tracker for bug reports, hardware testing feedback, or feature requests.
