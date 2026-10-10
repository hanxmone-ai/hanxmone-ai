### Hi, I'm Han (Yihan Qiu) 👋

**AI full-stack engineer · 12 years shipping products · Xiamen, China · open to remote work**

🌐 Portfolio: [hanxmone-ai.github.io](https://hanxmone-ai.github.io/) · [中文](https://hanxmone-ai.github.io/zh/)

I build products end to end: LLM backends, Flutter and Android apps, and the hardware they
talk to (POS printers, barcode scanners, NFC readers, BLE devices). I have taken several of them
from zero to App Store / Google Play and into real stores and schools.

#### What I work on

- **LLM applications**: multi-model routing (Claude, OpenAI, DeepSeek, Ollama) with retries and fallback, structured JSON output, conversation memory and summaries, token cost tracking, SSE / WebSocket streaming
- **Mobile**: Flutter and native Android (Kotlin). Large refactors, offline-first storage, in-app subscriptions, i18n, store releases
- **Hardware integration**: Sunmi / POS receipt printers, scanners, customer displays, RFID / NFC, face-recognition terminals, BLE
- **Backend & delivery**: Python (FastAPI, asyncio), REST / WebSocket API design, Docker, CI/CD

#### Open source

| Project | What it is |
|---|---|
| [sunmi-webview-bridge](https://github.com/hanxmone-ai/sunmi-webview-bridge) | Android app that lets any web page use a Sunmi terminal's scanner and printer through a documented JavaScript API |
| [escpos-kit](https://github.com/hanxmone-ai/escpos-kit) | Pure Dart ESC/POS library for Flutter and servers: Chinese (GBK), aligned item/price rows, barcodes, QR codes, images, network and Bluetooth printing |
| [flutter-ble-kit](https://github.com/hanxmone-ai/flutter-ble-kit) | Flutter Bluetooth LE app and toolkit: scanning, GATT browser, live heart rate, auto-reconnect and receipt printing over BLE, with a demo mode that runs without hardware |
| [streaming-chat-demo](https://github.com/hanxmone-ai/streaming-chat-demo) ([live demo](https://hanxmone-ai.github.io/streaming-chat-demo/)) | Streaming LLM chat without frameworks: a Node server relays any OpenAI-compatible API as server-sent events, cancels the model call on Stop, and a 15 KB TypeScript client renders Markdown as it arrives |
| [voice-assistant-demo](https://github.com/hanxmone-ai/voice-assistant-demo) | Hands-free voice assistant in the browser: voice activity detection, answers spoken sentence by sentence while the model streams, and barge-in that stops the model and the audio the moment you talk |
| llm-router-lite *(coming soon)* | Self-hosted LLM gateway: one OpenAI-style API, routing across providers, retries, fallback and token accounting |

#### Selected work (closed source, described only)

- **AI voice companion app for overseas markets** (Flutter): real-time voice chat with cloud + on-device speech recognition, streaming TTS, long-term memory, App Store / Google Play subscriptions
- **Flutter rewrite of a large native Android app**: 147 screens and 180+ APIs moved to one cross-platform codebase, plus a multi-model chat service with token accounting
- **Restaurant POS and queue system** (Flutter + Kotlin): cashier pads, kitchen tickets, call-number screens, thermal printers, scanners and RFID
- **Smart-campus terminals** (Android + Vue): face recognition and NFC attendance, deployed in dozens of schools in Fujian

#### Contact

📫 hanxmone@gmail.com: available for remote full-time roles and freelance projects.

<sub>中文：12 年全栈工程师，专注 AI 应用、Flutter / Android 与硬件集成，可远程合作。</sub>
