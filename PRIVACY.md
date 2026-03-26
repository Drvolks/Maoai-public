# Maoai Privacy Policy

**Last updated: March 26, 2026**

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

**No data is sent to MiniMax until you explicitly choose to send a message or generate an image.** No background or automatic data transmission occurs.

We do not operate any intermediary servers. All communication happens directly between your device and MiniMax's servers. We have no ability to intercept, read, or store your conversations or prompts.

Your interactions with MiniMax are subject to [MiniMax's privacy policy](https://platform.minimax.io/protocol/privacy-policy) and [terms of service](https://platform.minimax.io/protocol/terms-of-service). MiniMax is required to protect your data in accordance with their privacy policy.

## How We Collect and Use Data

Maoai collects data **only through direct user action** — specifically, when you type a message and tap send, or when you submit an image generation prompt. The app does not collect data passively, in the background, or without your knowledge.

All data listed above is used **solely** to provide AI-powered responses and image generation through the MiniMax API. It is not used for any other purpose such as advertising, analytics, profiling, or resale.

## User Consent

Before any data is shared with MiniMax, the app presents a mandatory consent screen that:

1. **Discloses what data will be sent** — text prompts, conversation context, image prompts, and your API token
2. **Identifies who the data is sent to** — MiniMax, a third-party AI service at api.minimax.io
3. **Requires explicit consent** — you must tap "I Consent to Share My Data with MiniMax" before any data transmission can occur

You may revoke this consent at any time in the app's Settings under "Privacy & Data." Revoking consent immediately prevents any further data transmission to MiniMax until consent is granted again.

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
