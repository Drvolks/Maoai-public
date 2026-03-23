# MiniChat Privacy Policy

**Last updated: March 23, 2026**

## Overview

MiniChat is designed with your privacy in mind. We do not collect, store, or have access to any of your personal data.

## Data Collection

MiniChat does **not** collect any personal data. Specifically:

- We do not collect analytics or usage data
- We do not use tracking or advertising frameworks
- We do not collect crash reports
- We do not collect device identifiers

## API Communication

MiniChat communicates directly with the MiniMax API (`api.minimax.io`) using your personal API token. All API requests are made directly from your device to MiniMax's servers. We do not operate any intermediary servers and have no ability to intercept, read, or store your conversations.

Your interactions with the MiniMax API are subject to [MiniMax's privacy policy](https://platform.minimax.io).

## Data Storage

- **Conversations** are stored locally on your device using Apple's SwiftData framework.
- **iCloud Sync** is optional. When enabled, conversations sync via your personal iCloud account using Apple's CloudKit. We do not have access to your iCloud data.
- **Generated images** are stored locally on your device's file system.
- **API token** is stored securely in the device Keychain, managed by the operating system.

## Third-Party Services

MiniChat integrates with the following third-party services:

| Service | Purpose | Data Shared |
|---------|---------|-------------|
| MiniMax API | AI responses and image generation | Your prompts and conversation history (sent directly from your device) |
| Apple iCloud (optional) | Conversation sync | Conversation data (via your personal iCloud account) |
| Apple StoreKit | In-app subscriptions | Purchase transactions (managed entirely by Apple) |

## Children's Privacy

MiniChat is not directed at children under 13. We do not knowingly collect any information from children.

## Changes to This Policy

We may update this privacy policy from time to time. Any changes will be reflected in the "Last updated" date above.

## Contact

If you have questions about this privacy policy, please open an issue on our [GitHub repository](https://github.com/jfdufour/MiniChat-public).
