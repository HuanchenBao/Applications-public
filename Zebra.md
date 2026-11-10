# Zebra

Zebra is a macOS PDF reader and LaTeX workspace with document-aware dictation and GPT assistance.

[Download Zebra 1.13.0](https://github.com/HuanchenBao/Applications-public/releases/tag/zebra-v1.13.0)

**Developer ID signed and Apple notarized.**

Requires an Apple silicon Mac (M1 or newer) running macOS 13.5 or later. Download the DMG, open it, and drag Zebra to Applications.

## Get started

1. Sign in with your own ChatGPT account for GPT features.
2. Choose **Download default speech model** for local dictation. Whisper Turbo Q5 is approximately 574 MB; no speech model is bundled.
3. Drop a PDF to read and ask questions, or a TeX file to edit in its existing folder.
4. Select a passage, press **E**, speak after the chime, then press **E** again. Review your instruction and press **Enter**. Use **Shift+Enter** for a new line.

PDF reading and typed input can be used without a speech-model download. The first LaTeX compilation downloads its verified compiler and required packages.

## Updates

Open **About → Updates** to check for and download newer versions. Zebra verifies the signed release information and the installer’s exact size and SHA-256 checksum. Updates are installed manually by replacing the app; documents, models and settings remain separate.

## Privacy and source

The installer contains no developer login, API keys, private keys, documents, recordings or speech weights. Audio is transcribed locally. GPT questions and optional transcript cleanup send your transcript and relevant document context through your own account.

Zebra is proprietary software. This repository hosts public downloads and release information only; application development source and source archives remain private. Required web runtime assets and third-party libraries are inspectable, and third-party license notices are included.

Dolphin speech integration is optional. Zebra works independently and does not install or modify Dolphin.

Developed by [Huanchen Bao](https://blog.nus.edu.sg/huanchen/). © 2026 Huanchen Bao. All rights reserved.

[Contact & Feedback](mailto:bao.huanchen@gmail.com)
