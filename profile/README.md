# QuillCrypt 🛡️

Secure, end-to-end encrypted messaging platform for developers. Native performance meets maximum privacy.

## 🚀 The Vision

QuillCrypt provides a developer-centric communication tool where security is not an afterthought. By combining modern cryptographic standards with a high-performance stack, we ensure that your conversations remain yours.

## 🏗️ Architecture & Ecosystem

Our system is split into three primary components:

- **[app](https://github.com/QuillCrypt/app)**: Cross-platform desktop/mobile client built with **Tauri**, **React**, and **TypeScript**. Handles all encryption/decryption locally.
- **[backend](https://github.com/QuillCrypt/backend)**: High-performance **Go** service using **Hexagonal Architecture**. Manages secure message routing and real-time delivery via WebSockets.
- **[proto](https://github.com/QuillCrypt/proto)**: Shared **Protocol Buffers** definitions for consistent, type-safe communication between client and server.

## 🛠️ Tech Stack

- **Languages**: Go, Rust, TypeScript.
- **Frontend**: React 19, Tailwind CSS, Material 3.
- **Backend**: PostgreSQL, Redis, Uber-Go Zap.
- **Infrastructure**: Docker & Docker Compose.

## 🔐 Security First

- **Local-First Encryption**: Keys never leave your device.
- **Modern Standards**: Leveraging Tauri's Stronghold and audited crypto libraries.
- **Transparency**: Fully open-source under the **AGPL-3.0** license.

## 🚦 Status

**Under Active Development.** Features are being implemented rapidly. Not recommended for production use until versioned releases begin.

---
"Lock your thoughts, keep the quill."
