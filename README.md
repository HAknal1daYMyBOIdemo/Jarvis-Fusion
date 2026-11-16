# Jarvis Fusion — Windows preview

[**Download the app ZIP**](https://github.com/HAknal1daYMyBOIdemo/Jarvis-Fusion/raw/refs/heads/main/Jarvis-Fusion-Windows-Preview.zip)

The ZIP contains the complete application source, pinned upstream source modules and licenses, tests, and the Windows launcher. No API keys, personal memories, recordings, model binaries, or virtual environments are included.

## Run on Windows

1. Download the app ZIP above. Right-click it and choose **Extract All**.
2. Install **Python 3.12**, including its Python launcher, from https://www.python.org/downloads/windows/.
3. Install and start **Ollama for Windows** from https://ollama.com/download/windows for local models.
4. Open the extracted **Jarvis-Fusion** folder and double-click **Start-Fusion.cmd**. Keep the terminal open. First launch installs dependencies.
5. Open **http://127.0.0.1:8765** in Chrome or Edge.
6. In **Models**, download a model that fits your computer, then select **Use this model**. Test text chat first.
7. For voice, open **Voice settings → Install local speech** (about 1 GB), choose a device-local Windows voice, test it, then **Enable open mic**.

You can use the OpenAI API instead of Ollama. Enter your API key in **Connect**, choose OpenAI and a model available to your account, then enable cloud context. API billing is separate from a ChatGPT subscription.

## Included

- Animated Jarvis home screen and turn-taking voice controls.
- Visual linked-note memory graph and explicit memory editing.
- Shared memory and conversation across Ollama/OpenAI model switches.
- Javis OS's real memory index, note-link parser, 21-entry Ollama catalog, downloader and offline speech module.
- OpenJarvis's real inference adapters.

This is an integration preview, not the complete upstream agent runtimes. Automatic memory extraction and full agent/tool execution are not enabled. Eleven backend checks and browser-flow checks passed in Linux. Native Windows, real Whisper recognition, real device voice playback and live model generation still need verification. See READ-ME-FIRST.md and VALIDATION.md inside the app for details.

## Package integrity

SHA-256 of `Jarvis-Fusion-Windows-Preview.zip`:

```
cfbb6daee7bde5ddeee67cebac3c0bc689390da5f1dee4c638730eeea7457bc8
```

Original upstream licenses are preserved inside `vendor/` in the package.
