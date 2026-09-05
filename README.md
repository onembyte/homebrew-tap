# Kolkrabbi Homebrew tap

Homebrew formula for **[Kolkrabbi](https://github.com/onembyte/kolkrabbi)** (`kolk`) — an
open-source, model-agnostic AI coding agent for the terminal. A Claude Code and Codex CLI
alternative that runs any OpenRouter model, your own Claude or ChatGPT subscription, or a local
model on Ollama or vLLM.

```bash
brew install onembyte/tap/kolk
kolk
```

macOS and Linux, Apple Silicon and Intel, arm64 and amd64.

## What this repository is

One generated file. `Formula/kolk.rb` is produced by
[`scripts/update-homebrew-tap.sh`](https://github.com/onembyte/kolkrabbi/blob/main/scripts/update-homebrew-tap.sh)
in the main repository, which reads the release's own `checksums.txt` and pins each SHA-256 from it.
Do not edit the formula by hand — regenerate it.

Every Kolkrabbi release ships four archives and a `checksums.txt` signed with keyless Cosign. The
digests in this formula come from that manifest, so `brew` verifies the same bytes the release
signed.

## Other ways to install

```bash
curl -fsSL https://kolkrabbi.francomichetti.com/install.sh | sh   # verifies SHA-256 itself
go install github.com/onembyte/kolkrabbi/cmd/kolk@latest
```

- Website: <https://kolkrabbi.francomichetti.com>
- Source and issues: <https://github.com/onembyte/kolkrabbi>
- License: Apache-2.0
