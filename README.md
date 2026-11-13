# Applications

**Zebra:** [Latest download](https://github.com/HuanchenBao/Applications-public/releases/download/zebra-v1.20.4/Zebra-1.20.4-macOS-AppleSilicon.dmg) · [Release notes](https://github.com/HuanchenBao/Applications-public/releases/tag/zebra-v1.20.4)  
**Dolphin:** [Download and release notes](https://github.com/HuanchenBao/Applications-public/releases/tag/dolphin-v1.12.0)

## Dolphin — AI-assisted dictation tool for latex input

**Dolphin 1.12.0 — Apple notarized** · Apple silicon · macOS 14 or later

[Download the Mac installer](https://github.com/HuanchenBao/Applications-public/releases/download/dolphin-v1.12.0/Dolphin-1.12.0-macOS-AppleSilicon.dmg) · [Release notes](https://github.com/HuanchenBao/Applications-public/releases/tag/dolphin-v1.12.0) · [Setup, updates and privacy](Dolphin.md)

A standalone dictation app with local speech recognition, optional GPT or local formatting, mode-specific references, and LaTeX support. No speech or formatting models are bundled. On first use, download Whisper Large v3 Turbo (Q5) and connect your own ChatGPT account. The default formatter is GPT-6-Luna with Low reasoning.

Dolphin’s application source remains private. This public repository contains the compiled installer, release information and signed update feed. The installer excludes developer credentials and personal dictation data.

## Zebra — AI-assisted LaTeX Editor and PDF Reader

**Zebra 1.20.4 — Apple notarized** · Apple silicon · macOS 13.5 or later

[Download the Mac installer](https://github.com/HuanchenBao/Applications-public/releases/download/zebra-v1.20.4/Zebra-1.20.4-macOS-AppleSilicon.dmg) · **[Read the release notes](https://github.com/HuanchenBao/Applications-public/releases/tag/zebra-v1.20.4)** · [Setup, updates and privacy](Zebra.md)

A simpler PDF-first workspace with a fully capable GPT assistant and direct Overleaf project browsing. Connect to Overleaf in Zebra, choose your TeX file, and collect passage-specific instructions for **Apply all**. Editing and compilation run locally, with verified synchronization to Overleaf in the background; external changes pause uploads for review.

The compact interface keeps the PDF central, with a left icon rail and GPT chat on demand. Select a passage and press **Option+E** to type an instruction. Zebra is text-only: no speech model, microphone permission or dictation-app integration. Sign in with your own ChatGPT account. An independent dictation app can insert text normally.

The full GPT assistant supports model/reasoning choices, research, linked references, images, notes, version history and publication approvals. Updates under **About** provide signed, checksum-verified downloads for manual installation.

Zebra’s development source and source archives remain private. Public downloads contain compiled installers, minimized interface assets, third-party licenses and checksums. Package audits found no developer credentials, personal documents, signing keys or model weights.

## A Note on AI Use and Source Code

Dolphin and Zebra are closed source and were developed primarily using AI-generated code. I don’t have a coding background, so I’m unable to independently review and verify the source code. To reduce the risk of accidentally exposing personal or confidential information, I’ve chosen to keep the source private and share only the packaged apps.

I’m happy to discuss how the apps were built, answer questions about the development process, and share my experience creating them with AI.
