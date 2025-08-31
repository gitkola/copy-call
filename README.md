# copy-call

## Description

Copy Call is a serverless, copy-paste WebRTC application for video calls.
It works as a static site and does not require any backend, no signaling server, no authentication no database, no nothing.

## User flow

1. Initiator when opens the page, it generates offer link and it is available to copy.
2. Initiator shares copied offer link with the recipient through any third-party service like email, sms, etc.
3. When recipient opens the link in their browser it generates answer code and it needs to be sent back to initiator.
4. Initiator pastes answer code and hits "Connect" button.
5. After that the peer connection is established and video call starts.

## Tech stack

- [Bun](https://bun.sh) - Fast all-in-one JavaScript runtime for hot reload during development.
- [WebRTC](https://webrtc.org) - WebRTC is a free, open project that provides web browsers and mobile applications with real-time communication via simple APIs.

## Installation

To install dependencies:

```bash
bun install
```

To run:

```bash
bun run index.html
```

This project was created using `bun init` in bun v1.2.17.
