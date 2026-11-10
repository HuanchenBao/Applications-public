# Dolphin

Standalone dictation for Apple silicon Macs running macOS 14 or later.

**Current release: Dolphin 1.12.0 (build 28), Apple notarized.**

[Download the Mac installer](https://github.com/HuanchenBao/Applications-public/releases/download/dolphin-v1.12.0/Dolphin-1.12.0-macOS-AppleSilicon.dmg) · [Release notes](https://github.com/HuanchenBao/Applications-public/releases/tag/dolphin-v1.12.0) · [SHA-256 checksum](https://github.com/HuanchenBao/Applications-public/releases/download/dolphin-v1.12.0/SHA256SUMS.txt)

## Getting started

1. Open the disk image and drag Dolphin into Applications.
2. Launch Dolphin and download the default **Whisper Large v3 Turbo (Q5)** model, or choose another speech model. The installer contains **no speech or formatting model weights**.
3. Connect **your own ChatGPT account**. The default formatter is **GPT-6-Luna, Low reasoning**. Optional local Qwen formatting and **None** are available.
4. Follow the first-use Accessibility instructions for inserting text into other apps. **Fn** starts and finishes dictation; **Esc** cancels.

Mode-specific references, optional LaTeX instructions, correction memory, and local training archives are available. Dolphin supports Zebra’s shared-speech protocol.

## Updates

Dolphin checks its dedicated GitHub update feed automatically, at most once per day. You can also use **Settings → Updates** to check manually. When a newer compatible release is available, Dolphin offers a notification and a download button. It verifies the signed release metadata and installer checksum before offering to open the download. Drag the new app into Applications to complete installation.

The updater uses `dolphin-updates.json`; releases for other applications do not trigger Dolphin updates.

## Privacy and source availability

The installer contains no developer login credentials, personal dictation history, recordings, references, private signing keys, or model downloads. Each user connects their own account and downloads their own models. Online formatting sends the transcript and applicable formatting context to the selected service. History and training archives are not automatically uploaded to the developer.

Dolphin’s original application source is private. This repository distributes the compiled app, update information, and documentation. GitHub’s automatically generated “Source code” archives contain this public catalog, not the application source. Included third-party components retain their own license terms and notices.

Developed by [Huanchen Bao](https://blog.nus.edu.sg/huanchen/). © 2026 Huanchen Bao. All rights reserved.

[Contact & Feedback](mailto:bao.huanchen@gmail.com)
