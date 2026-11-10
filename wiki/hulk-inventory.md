# Hulk inventory

Compiled from the 2026-11-08 AppLens Linux inventory scan. Host and user names stay redacted in the raw JSON.

## Source

- Raw: [`../raw/AppLens_Results_hulk_2026-11-08T175336Z.json`](../raw/AppLens_Results_hulk_2026-11-08T175336Z.json)
- Schema 3.0, Mode `Inventory`, Platform `Linux`
- GeneratedAt `2026-11-08T17:53:36.748569+00:00`
- Duration 0.138 s, `IsPartial` false

## Machine

| Field | Value |
| --- | --- |
| OS | Ubuntu 24.04.5 LTS, x86_64 |
| CPU | AMD Ryzen 5 5600X 6-Core Processor |
| GPU | PCI `0x10de:0x21c4` (NVIDIA present; NVIDIA X Server Settings installed) |
| RAM | 31.2 GiB total, 25.7% in use at capture |
| Uptime | ~24.8 h |

### Disks (non-virtual)

| Volume | FS | Total | Free | Used |
| --- | --- | --- | --- | --- |
| Mount 1 | ext4 | 456.3 GiB | 290.2 GiB | 36.4% |
| Mount 34 | vfat | 1.0 GiB | 1.0 GiB | 0.6% |

Thirty-two squashfs mounts were flagged low-space. Those are full read-only Snap images, not the main disk.

## Software counts

| Bucket | Count |
| --- | --- |
| Desktop applications | 44 |
| Packages | 2351 (2334 dpkg, 17 Snap) |
| Runtimes and frameworks | 73 |

### CLI tools present

Git, Python 3, Node.js, npm, Docker, Ollama, Cursor, Java

### CLI tools not on PATH

PowerShell, Homebrew, VS Code (`code`), uv, pipx, conda, Go, Rust, dotnet

### Desktop applications

Additional Drivers, Advanced Network Configuration, App Center, Calculator, Characters, ChatGPT, Clocks, CPU-X, Cursor, Discord, Disk Usage Analyzer, Disks, Document Viewer, Files, Firmware Updater, Fonts, GNOME System Monitor, Google Chrome, Help, IBus Preferences, Image Viewer, Input Method, Language Support, LibreOffice, LibreOffice Math, LibreOffice Writer, Local Models, Logs, NVIDIA X Server Settings, OpenCode, OpenCode Desktop, OpenJDK Java 8 Policy Tool, Passwords and Keys, Power Statistics, Settings, Slack, Software & Updates, Software Updater, Startup Applications, System Monitor, Terminal, Text Editor, Vim, VLC media player

## Probe notes

Succeeded: OS, CPU, memory, uptime, graphics, mounts, XDG desktop apps, dpkg, Snap.

Unavailable on this Ubuntu host (expected): rpm, pacman, apk, xbps, Flatpak, Homebrew formula/cask.
