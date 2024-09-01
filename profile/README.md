# SPEEM app- Serverless Peer-to-peer & End-to-end Encrypted Messaging 

## :warning: :construction: Under Active Development :construction: :warning:

The SPEEM project is still in early stages and very much a work in progress. More features will be added,
docs may be missing or outdated and api/config may change.

## About SPEEM

SPEEM is a truly serverless, privacy-focused messaging app. SPEEM uses peer-to-peer networking and solid cryptography and encryption to establish secure communications. Messages and app metadata are securely stored on the device, with no relay servers involved.

---

## Features

- **Serverless:** SPEEM doesn't rely on relay servers. Data is kept secure on each device, and conversations are shared only with trusted peers.
- **Peer-to-peer:** SPEEM uses solid and efficient peer-to-peer networking for user pairing and discovery, as well as for data reconciliation between trusted peers.
- **Secure local storage:** All messages and metadata are encrypted before being stored in the device's local storage. No remote storage is used.
- **Native apps:** The mobile apps for iOS and Android are native for better user experience and optimal performance.

---

## Sub-projects

- **The core built with Rust:** This is the [core shared library](https://github.com/speemapp/core) built with Rust, offering maximum performance and security.
- **The iOS app:** The native [iOS app](https://github.com/speemapp/ios-app).
- **The Android app:** The native [Android app](https://github.com/speemapp/android-app).

---

## Development Roadmap

### Proof of Concept (PoC)

The PoC aims to demonstrate the feasibility of a serverless, privacy-focused messaging app. It should include the core functionalities needed to establish secure communication between users without relying on central servers.

- User registration and key generation.
- User pairing and discovery.
- Peer-to-peer messaging.
- End-to-end encrypted messages.
- Store keys and messages securely on the device.

### Version 1

- Enhanced messaging: message delivery confirmation, support for multimedia messages.
- User status and presence notification.
- User discovery enhancements.
- Ensure data synchronization across multiple devices of the same user.
- Enhanced privacy: provide options for users to manage their own privacy settings.
- (Maybe) Implement federated learning for predictive text and spam detection without compromising privacy.

---

## About the Developer

SPEEM is a project developed by [Wassim Mansouri](https://wassimans.com), in the open. To learn more about the project, visit our [GitHub repository](https://github.com/speemapp).

---

© 2024 SPEEM app. All rights reserved.
