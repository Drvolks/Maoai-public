# Maoai Privacy Policy

**Last updated: March 23, 2026**

## Overview

Maoai is designed with your privacy in mind. We do not collect, store, or have access to any of your personal data.

## Data Collection

Maoai does **not** collect any personal data. Specifically:

- We do not collect analytics or usage data
- We do not use tracking or advertising frameworks
- We do not collect crash reports
- We do not collect device identifiers

## Data Shared with Third-Party AI Service

When you send a message or request an image, Maoai transmits the following data directly from your device to **MiniMax** (`api.minimax.io`), a third-party AI service:

- **Text prompts** — the messages you type in a conversation
- **Conversation context** — prior messages in the current conversation, sent so the AI can provide contextual responses
- **Image generation prompts** — text descriptions you provide when requesting an image
- **API token** — your personal MiniMax API token, used to authenticate requests

**No data is sent to MiniMax until you explicitly choose to send a message or generate an image.** The app requests your consent before any data is transmitted by requiring you to enter your own API token and acknowledge this data sharing on the welcome screen. No background or automatic data transmission occurs.

We do not operate any intermediary servers. All communication happens directly between your device and MiniMax's servers. We have no ability to intercept, read, or store your conversations or prompts.

Your interactions with MiniMax are subject to [MiniMax's privacy policy](https://platform.minimax.io) and [terms of service](https://platform.minimax.io).

## Data Storage

- **Conversations** are stored locally on your device using Apple's SwiftData framework.
- **iCloud Sync** is optional. When enabled, conversations sync via your personal iCloud account using Apple's CloudKit. We do not have access to your iCloud data.
- **Generated images** are stored locally on your device's file system.
- **API token** is stored securely in the device Keychain, managed by the operating system.

## Third-Party Services

Maoai integrates with the following third-party services:

| Service | Purpose | Data Shared |
|---------|---------|-------------|
| MiniMax API | AI responses and image generation | Your prompts and conversation history (sent directly from your device) |
| Apple iCloud (optional) | Conversation sync | Conversation data (via your personal iCloud account) |
| Apple StoreKit | In-app subscriptions | Purchase transactions (managed entirely by Apple) |

## Children's Privacy

Maoai is not directed at children under 13. We do not knowingly collect any information from children.

## Changes to This Policy

We may update this privacy policy from time to time. Any changes will be reflected in the "Last updated" date above.

## Contact

If you have questions about this privacy policy, please open an issue on our [GitHub repository](https://github.com/jfdufour/Maoai-public).
