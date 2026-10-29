# golden-gate-exit
information and tools for easing transition from Apple iOS and macOS to Linux (GrapheneOS, Debian)

tools, guides, and ongoing notes on leaving Apple's ecosystem — macOS and iOS — following the removal of Apple Intelligence opt-out in macOS 27 and iOS 27.

companion to [Golden Gate, exit from Apple](https://www.jimmont.com/golden-gate-exit)

---

## Tools

| Tool | Platform | What it does |
|---|---|---|
| [RemoveMacAI](https://github.com/omlahore/RemoveMacAI) | macOS 27, Apple Silicon | Disables Apple Intelligence, removes models, blocks re-download. Reversible. |
| [Lulu](https://objective-see.org/tools) | macOS | Per-process outbound firewall. Free, open source. |
| [Cloudflare WARP](https://one.one.one.one) | macOS, iOS | DNS. Simple upgrade over the default. |
| [Tinycast](https://tinycast.dev) | macOS | Spotlight replacement. Fast, no telemetry. |
| [UTM](https://mac.getutm.app) | macOS | VM host. Runs Debian (and others) on Apple Silicon. |
| [GrapheneOS](https://grapheneos.org) | Pixel 9a, Pixel 10a | Privacy-hardened Android. Production-supported through 2032–2033. |

---

## Status

Tool compatibility against current OS versions. PRs welcome.

| Tool | Last tested | macOS | iOS | Status |
|---|---|---|---|---|
| RemoveMacAI | 2026-10-28 | 27.2 | — | ✅ |
| Lulu | 2026-10-28 | 27.2 | — | ✅ |
| Cloudflare WARP | 2026-10-28 | 27.2 | 27.2 | ✅ |
| Tinycast | 2026-10-28 | 27.2 | — | ✅ |
| UTM + Debian | 2026-10-28 | 27.2 | — | ✅ |
| GrapheneOS | 2026-10-28 | — | — | ✅ |

---

planning to add grapheneos suggestions, VM for use

issues and discussion available

