<div align="center">

# 🎙️ WisprOwn

**Hold a key. Speak. Release. Your words appear where your cursor is.**

Private, multilingual push-to-talk dictation for macOS. It runs entirely on your Mac:
no cloud, no subscription, and your audio never leaves your computer.

**[⬇ Download the latest version](https://github.com/diebrudie/wisprown/releases/latest/download/WisprOwn.zip)**

Current version: [0.9.0](https://github.com/diebrudie/wisprown/releases/tag/v0.9.0), released 23 October 2026

</div>

---

## What it does

- **Push to talk:** hold Left Option, speak, let go. The text is pasted wherever your cursor is.
- **On-device speech recognition:** Whisper runs locally on Apple Silicon, about one second from release to text.
- **English, German, Spanish and more:** the language is detected automatically.
- **Your own dictionary:** add names and terms, and it learns from the corrections you make.
- **Optional AI clean-up:** bring your own API key to remove filler words. Off by default.
- **Insights:** words per day, words per minute, streaks and time saved compared to typing. Count from today whenever you want a fresh start.
- **Notetaker:** transcribe a call or interview while it runs, with your lines as "Me" and the other side as "Them". Add the people's names afterwards and every line shows who spoke. With your own API key it writes a summary with key points and a fitting title. Copy it, or download it as a PDF or Markdown file. A small floating widget shows the time and a Stop button, and WisprOwn can notice when a call starts or a calendar meeting is due. Tell the people on the call first.

## Requirements

- Apple Silicon Mac (M1 or newer)
- macOS 14.2 (Sonoma) or newer
- About 4 GB free disk space (the speech models download on first launch)
- 16 GB RAM recommended

## Install

1. [Download **WisprOwn.zip**](https://github.com/diebrudie/wisprown/releases/latest/download/WisprOwn.zip), double-click it, and drag **WisprOwn** into your **Applications** folder.
2. Open it. macOS warns that it can't verify the developer, because the app is self-signed rather than notarized by Apple.
   - **macOS 15 or newer:** click **Done**, open *System Settings → Privacy & Security*, scroll down and click **Open Anyway** next to WisprOwn.
   - **macOS 14:** right-click the app, choose **Open**, then **Open** again.
3. Allow **Microphone**, then switch WisprOwn on under *System Settings → Privacy & Security → Accessibility*. This lets it hear your hotkey and paste for you.
4. Wait for the one-time model download (about 2.8 GB) and about a minute of setup. When the menu bar icon becomes a plain microphone, click into any text field, **hold Left Option**, speak and release.

**Updating:** quit WisprOwn, replace the app in Applications with the new version and open it. Your settings, history and dictionary are kept.

## Privacy

Everything runs on-device. The only network activity is the one-time model download from Hugging Face. If you add your own AI provider key, transcripts (text only, never audio) are sent to that provider to be cleaned up. Leave it empty and nothing leaves your Mac. Meeting transcripts are stored on your Mac only, and no audio is ever kept. A meeting summary is made only when you ask for one, and then the transcript text goes to your provider.

## License

Free for personal use. Selling, redistributing or modifying the app is not permitted. See [LICENSE](LICENSE).

Made by [diebrudie](https://github.com/diebrudie).
