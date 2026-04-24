# 🍎 Mac Tools voor homelab, dev & productiviteit

Een opinionated curated lijst met tools die echt nuttig zijn op macOS, gericht op:

- **Homelab** beheerders (Home Assistant, Docker, self-hosted)
- **Developers** (fullstack, scripting, automation)
- **Creators** die houden van strakke workflows
- **Security-aware** gebruikers

Niets is hier voor "omdat het mooi is" — alles is een tool die ik zelf gebruik of sterk aanbeveel.

---

## 🗂️ Inhoud

- [Essentials](#-essentials-must-have)
- [Window Management](#-window-management)
- [Terminal & Shell](#-terminal--shell)
- [Development](#-development)
- [Docker & Containers](#-docker--containers)
- [Productivity](#-productivity)
- [System Tools](#-system-tools)
- [Network & Homelab](#-network--homelab)
- [Security & Privacy](#-security--privacy)
- [AI & Local LLMs](#-ai--local-llms)
- [Quick Setup Script](#-quick-setup-script)

---

## 🌟 Essentials (must-have)

| Tool | Wat | Prijs | Link |
|---|---|---|---|
| **Homebrew** | Package manager voor macOS — alle CLI tools via `brew install` | Free | [brew.sh](https://brew.sh) |
| **BetterDisplay** | HiDPI scaling, custom resoluties, fix wazige tekst op externe monitoren | Free / Pro €20 | [betterdisplay.pro](https://betterdisplay.pro) |
| **Raycast** | Spotlight op steroïden — clipboard history, snippets, window management, AI, script commands | Free / Pro $8/mnd | [raycast.com](https://raycast.com) |
| **Rectangle** | Snap windows met keyboard shortcuts — essentieel voor ultrawide | Free | [rectangleapp.com](https://rectangleapp.com) |
| **1Password** | Password manager — zowel voor personen als SSH keys/tokens | $3/mnd | [1password.com](https://1password.com) |
| **Stats** | Systeem-monitoring in de menubar (CPU, RAM, netwerk, temperatuur) | Free | [github.com/exelban/stats](https://github.com/exelban/stats) |

---

## 🪟 Window Management

| Tool | Wat | Prijs |
|---|---|---|
| **Rectangle** | Keyboard shortcuts voor snappen — `⌃⌥← / →` voor halve schermen | Free ([download](https://rectangleapp.com)) |
| **BetterTouchTool** | Gesture + shortcut-beheer op epische schaal | €10 ([folivora.ai](https://folivora.ai/btt)) |
| **AltTab** | Windows-stijl ⌘-Tab met preview van vensters | Free ([github.com/lwouis/alt-tab-macos](https://github.com/lwouis/alt-tab-macos)) |
| **HazeOver** | Dimt alle vensters behalve actieve — superfocus | €5 ([hazeover.com](https://hazeover.com)) |
| **Hidden Bar** | Verbergt drukke menu-bar icons | Free ([github.com/dwarvesf/hidden](https://github.com/dwarvesf/hidden)) |

---

## 🖥️ Terminal & Shell

| Tool | Wat | Prijs |
|---|---|---|
| **Warp** | Modern terminal met AI, workflows, blocks | Free / Pro | [warp.dev](https://www.warp.dev) |
| **iTerm2** | Klassieker. Splits, profiles, zeer configureerbaar | Free | [iterm2.com](https://iterm2.com) |
| **Ghostty** | Snelste terminal op Mac (GPU-accelerated). Door Mitchell Hashimoto | Free | [ghostty.org](https://ghostty.org) |
| **Starship** | Universele shell-prompt, supersnel, reactief | Free | [starship.rs](https://starship.rs) |
| **fish** / **zsh + zinit** | Shells met autocompletion en history-search | Free | [fishshell.com](https://fishshell.com) |
| **tmux** | Terminal multiplexer — sessies die blijven draaien | Free | `brew install tmux` |
| **lsd** | `ls` met iconen en kleuren | Free | `brew install lsd` |
| **bat** | `cat` met syntax-highlighting | Free | `brew install bat` |
| **fzf** | Fuzzy finder voor bestanden, history, git branches | Free | `brew install fzf` |
| **ripgrep (rg)** | Snellere `grep` | Free | `brew install ripgrep` |
| **fd** | Snellere `find` | Free | `brew install fd` |
| **htop** / **btop** | Mooiere process monitors | Free | `brew install btop` |

---

## 💻 Development

### Editors & IDEs

| Tool | Wat | Prijs |
|---|---|---|
| **Cursor** | VS Code fork met AI-first, Claude + GPT als coder | Free / Pro $20/mnd | [cursor.com](https://cursor.com) |
| **VS Code** | Classic, 10K+ extensies | Free | [code.visualstudio.com](https://code.visualstudio.com) |
| **Zed** | Snel IDE van de Atom-makers, multiplayer-coding | Free | [zed.dev](https://zed.dev) |
| **Xcode** | Voor iOS/macOS native apps | Free | App Store |
| **JetBrains Toolbox** | WebStorm, PyCharm, IntelliJ, etc. | Varies | [jetbrains.com](https://jetbrains.com) |

### Database & API

| Tool | Wat | Prijs |
|---|---|---|
| **TablePlus** | Database client (SQLite, PostgreSQL, MySQL, Redis, ...) | $59 eenmalig | [tableplus.com](https://tableplus.com) |
| **DBeaver** | Free alternatief, ietsje lelijker | Free | [dbeaver.io](https://dbeaver.io) |
| **Proxyman** | HTTP inspector (Charles-alternatief) | $49 | [proxyman.io](https://proxyman.io) |
| **Bruno** | Open-source Postman alternative, Git-friendly | Free | [usebruno.com](https://usebruno.com) |
| **Insomnia** | REST/GraphQL client | Free / paid | [insomnia.rest](https://insomnia.rest) |

### Git

| Tool | Wat | Prijs |
|---|---|---|
| **lazygit** | Terminal Git-UI — razendsnel, keyboard-driven | Free | `brew install lazygit` |
| **Tower** | GUI Git-client, premium | $70/jaar | [git-tower.com](https://www.git-tower.com) |
| **Fork** | Alternatief GUI voor Git | $50 eenmalig | [git-fork.com](https://git-fork.com) |
| **delta** | Mooiere `git diff` output | Free | `brew install git-delta` |

---

## 🐳 Docker & Containers

| Tool | Wat | Prijs |
|---|---|---|
| **OrbStack** | **Lichtgewicht Docker + Linux VMs voor Mac** — veel sneller dan Docker Desktop | Free personal / $8/mnd work | [orbstack.dev](https://orbstack.dev) |
| **Docker Desktop** | De standaard, iets zwaarder | Free personal | [docker.com](https://docker.com) |
| **Lima** | CLI Linux VMs | Free | `brew install lima` |
| **Colima** | Docker zonder Desktop, Pro-gratis optie | Free | `brew install colima` |

> **Aanbeveling**: OrbStack. Halveert opstarttijd, gebruikt minder RAM, werkt gewoon.

---

## ⚡ Productivity

| Tool | Wat | Prijs |
|---|---|---|
| **Raycast** | Launcher + clipboard + snippets + 1000+ extensions | Free | [raycast.com](https://raycast.com) |
| **Obsidian** | Notities in Markdown, local-first, extensible | Free | [obsidian.md](https://obsidian.md) |
| **Things 3** | Todo-app, prachtig ontwerp | $50 eenmalig | [culturedcode.com](https://culturedcode.com/things/) |
| **Todoist** | Cross-platform todo | Free / paid | [todoist.com](https://todoist.com) |
| **Shottr** | Screenshots + scrolling screenshots + OCR | Free | [shottr.cc](https://shottr.cc) |
| **CleanShot X** | Premium screenshot tool, annotation, cloud | $30 / Setapp | [cleanshot.com](https://cleanshot.com) |
| **TextExpander** / **Espanso** | Text snippets met variabelen | Paid / Free | [espanso.org](https://espanso.org) |
| **Bartender** | Menubar-organisator (opvolger Hidden Bar) | $16 | [bartender.net](https://bartender.net) |

---

## 🔧 System Tools

| Tool | Wat | Prijs |
|---|---|---|
| **AppCleaner** | Complete uninstalls (ook launch-agents, preferences) | Free | [freemacsoft.net](https://freemacsoft.net/appcleaner/) |
| **The Unarchiver** | ZIP/RAR/7z en exotische archieven | Free | App Store |
| **Keka** | Archief-maker (7z, zip, tar) | Free / App Store $5 | [keka.io](https://keka.io) |
| **OnyX** | System maintenance + cleaning | Free | [titanium-software.fr](https://www.titanium-software.fr/en/onyx.html) |
| **DaisyDisk** | Disk space visualizer — prachtig | $10 eenmalig | [daisydiskapp.com](https://daisydiskapp.com) |
| **GrandPerspective** | Gratis alternatief voor DaisyDisk | Free | [grandperspectiv.sourceforge.net](http://grandperspectiv.sourceforge.net) |
| **iStat Menus** | Uitgebreide menubar stats (temp, fans, power, network) | $12 eenmalig | [bjango.com](https://bjango.com/mac/istatmenus/) |
| **Stats** | Open-source alternatief voor iStat Menus | Free | [github.com/exelban/stats](https://github.com/exelban/stats) |
| **Macs Fan Control** | Handmatige fan-snelheid (bij oudere Macs) | Free | [crystalidea.com](https://crystalidea.com/macs-fan-control) |

---

## 🌐 Network & Homelab

| Tool | Wat | Prijs |
|---|---|---|
| **Tailscale** | WireGuard-gebaseerde VPN — zero-config toegang tot homelab van anywhere | Free (tot 100 devices) | [tailscale.com](https://tailscale.com) |
| **Wireshark** | Netwerk-analyse, packet capture | Free | [wireshark.org](https://wireshark.org) |
| **Transmit** | FTP / SFTP / S3 client — prachtig | $45 | [panic.com/transmit](https://panic.com/transmit/) |
| **ForkLift** | FTP / SMB / WebDAV / dual-pane file manager | $29 | [binarynights.com](https://binarynights.com) |
| **Wi-Fi Explorer** | Wi-Fi signal analyzer, channel scan | $20 | App Store |
| **iNet Network Scanner** | LAN scanner, ping, port check | Free / Pro $20 | App Store |
| **LanScan** | Snelle LAN device discovery | Free | App Store |
| **Home Assistant Companion** | HA-app op Mac menubar/dashboard | Free | [home-assistant.io](https://www.home-assistant.io/docs/frontend/mobile/) |
| **Royal TSX** | SSH / RDP / VNC session manager | Free | [royalapps.com](https://royalapps.com) |
| **Termius** | SSH client met sync over devices | Free / Pro | [termius.com](https://termius.com) |
| **Mosh** | SSH-alternatief met roaming + lagere latency | Free | `brew install mosh` |
| **yt-dlp** | YouTube / video downloader CLI | Free | `brew install yt-dlp` |

---

## 🔒 Security & Privacy

| Tool | Wat | Prijs |
|---|---|---|
| **Little Snitch** | Application firewall — zie welke app naar buiten belt | €45 | [obdev.at/littlesnitch](https://obdev.at/products/littlesnitch) |
| **LuLu** | Gratis firewall-alternatief van Objective-See | Free | [objective-see.org/products/lulu.html](https://objective-see.org/products/lulu.html) |
| **KnockKnock** | Scan persistently-installed malware | Free | [objective-see.org/products/knockknock.html](https://objective-see.org/products/knockknock.html) |
| **BlockBlock** | Alert bij nieuwe persistente installaties | Free | [objective-see.org/products/blockblock.html](https://objective-see.org/products/blockblock.html) |
| **DoNotDisturb** | Alert bij lid-openen (anti-evil-maid) | Free | [objective-see.org](https://objective-see.org) |
| **1Password** | Passwords + SSH keys + 2FA | $3/mnd | [1password.com](https://1password.com) |
| **Bitwarden** | Open-source password manager | Free / $10/jr | [bitwarden.com](https://bitwarden.com) |
| **Mullvad VPN** | Privacy-first VPN, anoniem | €5/mnd | [mullvad.net](https://mullvad.net) |

---

## 🤖 AI & Local LLMs

| Tool | Wat | Prijs |
|---|---|---|
| **Ollama** | Run local LLMs (Llama, Mistral, Qwen) | Free | [ollama.com](https://ollama.com) |
| **LM Studio** | GUI voor lokale LLMs | Free | [lmstudio.ai](https://lmstudio.ai) |
| **Enchanted** | Native Mac app voor Ollama | Free | [App Store](https://apps.apple.com/app/enchanted/id6499880259) |
| **Claude** | Anthropic's chat + API | Free / Pro $20/mnd | [claude.ai](https://claude.ai) |
| **Claude Code** | CLI coding agent (die dit schrijft!) | Free met Claude Pro | [claude.com/product/claude-code](https://claude.com/product/claude-code) |
| **Cursor** | AI-first IDE | Free / Pro | [cursor.com](https://cursor.com) |
| **Raycast AI** | Quick AI in launcher | Pro $8/mnd | [raycast.com](https://raycast.com) |

---

## 🎨 Creative

| Tool | Wat | Prijs |
|---|---|---|
| **Figma** | UI/UX design, web-based | Free / paid | [figma.com](https://figma.com) |
| **Sketch** | Mac-native UI design | $10/mnd | [sketch.com](https://sketch.com) |
| **Affinity Suite** | Photoshop/Illustrator/InDesign alternative | €180 eenmalig | [affinity.serif.com](https://affinity.serif.com) |
| **Pixelmator Pro** | Lichte photo-editor | $50 | [pixelmator.com/pro](https://www.pixelmator.com/pro/) |
| **Blender** | 3D modeling, animation, sculpting | Free | [blender.org](https://www.blender.org) |
| **Inkscape** | Vector illustrator, open-source | Free | [inkscape.org](https://inkscape.org) |
| **DaVinci Resolve** | Pro video editor, gratis versie erg compleet | Free / $300 | [blackmagicdesign.com](https://www.blackmagicdesign.com/products/davinciresolve) |
| **Handbrake** | Video transcoder | Free | [handbrake.fr](https://handbrake.fr) |
| **Excalidraw** | Snelle sketches & diagrams (web + Raycast extensie) | Free | [excalidraw.com](https://excalidraw.com) |

---

## 🚀 Quick Setup Script

Kopieer het onderstaande in Terminal voor een basis-Mac setup:

```bash
# Installeer Homebrew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# CLI essentials
brew install git htop btop lsd bat fzf ripgrep fd tmux mosh yt-dlp starship lazygit jq gh

# GUI essentials (casks)
brew install --cask \
  raycast rectangle betterdisplay stats \
  warp iterm2 ghostty \
  visual-studio-code cursor \
  orbstack tableplus \
  1password tailscale \
  obsidian shottr \
  appcleaner the-unarchiver keka \
  little-snitch

# Homelab / dev extras
brew install --cask wireshark transmit royal-tsx ollama

# Clean up
brew cleanup

echo "✅ Alles geïnstalleerd. Start Raycast, logical windowSize in Rectangle, en zet BetterDisplay op voor je externe monitor."
```

---

## 📝 Bijdragen

Tool ontbreekt? Open een Pull Request of [issue](../../issues). Lege regels over hypes en tools die niemand echt gebruikt; focus is op tools die productief maken.

## 📜 Licentie

[MIT](LICENSE) — doe ermee wat je wil.

---

**Gemaakt door Hans** — homelab-liefhebber, Mac-gebruiker, altijd nieuwsgierig naar betere tools. Check ook [zero0f4.dev](https://zero0f4.dev) voor mijn sci-fi hobby.
