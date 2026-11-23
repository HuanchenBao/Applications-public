# Dolphin — Your visual notebook for the AI era

[Download Dolphin 1.31.27](https://github.com/HuanchenBao/Applications-public/releases/download/dolphin-v1.31.27/Dolphin-1.31.27-macOS-AppleSilicon.dmg) · [Release notes and checksums](https://github.com/HuanchenBao/Applications-public/releases/tag/dolphin-v1.31.27)

Developer ID signed and Apple notarized. Apple silicon; macOS 14 or later. Apple notarization verifies distribution security requirements; it is not a guarantee of transcription accuracy or AI answers.

## Quick start

1. Download the DMG and drag Dolphin to Applications. Open the installed copy.
2. Add notes or import Markdown, then explore your notebook blueprint. Click a card to preview; double-click to open a note. Zoom, fit and drag cards to arrange your view. Saved connections show their explanations and supporting notes.
3. Open Settings to download a recognizer. Cohere Transcribe Q4 is the new English default. Select a multilingual Whisper/Qwen model for other languages or meetings. Existing supported model choices are preserved on upgrade.
4. For voice input grant microphone access. For insertion into other supported apps, grant Accessibility access and set the Globe/Fn key’s macOS action to Do Nothing if needed. Fn starts and stops dictation; Fn+Shift opens Assistant with voice input. The toolbar D opens chat without recording.
5. Connect your own GPT account for assistant requests and choose the available model/reasoning/speed and approval options. Local dictation does not require a GPT connection. Stopping voice capture leaves an unsent draft.
6. Browse original Markdown or a layered Overview. Ask the assistant to summarize, update or organize notes. Review and undo changes as appropriate to the selected approval mode.

## Source records and meetings

Settings includes dictation source retention and a source inspector. When enabled, it keeps original audio and separate raw, cleanup, formatted and revision stages. Play the original, export one stage or the full bundle, or save a stage into a note with a source link. Disabled/skipped stages are labeled rather than invented. Existing retained audio remains until you delete it. Source deletion does not purge the separate append-only training archive.

Meeting recording can retain microphone and selected-app audio. Use a prepared agenda note and ask the assistant to combine it with the transcript. Meeting recordings remain separate from ordinary dictation. Calendar operations require your authorization to access Calendar.

## Privacy and storage

Notes and media live in the local Dolphin profile; audio and attachments are separate from note JSON. This is not a cloud backup. Back up important data. Dropbox and Mac–iPhone synchronization are not configured or verified in this release. This download is the Mac app, not an iOS installer.

Speech and formatting weights download separately. Supported local models run on your Mac after download. Explicit GPT requests transmit relevant content to your selected GPT provider; provider terms, availability and billing apply. OS permissions are requested only for the features using them.

Public packages exclude developer account sessions, credentials, signing private keys, personal notes, recordings, training records and model weights. Signing certificates and the updater verification public key are public verification material, not secrets.

## Updates

Check for Updates in Dolphin offers signed, checksum-verified release information and downloads for manual installation. Download the new installer and replace the app in Applications; keep your local profile. Never delete your profile merely to update the app.

## What changed

Read the [full 1.31.27 release notes](https://github.com/HuanchenBao/Applications-public/releases/tag/dolphin-v1.31.27) for the transition from dictation utility to visual notebook. Earlier public 1.12.0 downloads remain historical releases. Dolphin and Zebra are independent; shared speech integration from earlier versions is no longer supported.
