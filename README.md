# Awesome-CLI-Fuzzy-Finder-Terminal-Productivity

## Top CLI Fuzzy Finder & Terminal Productivity Ecosystem



**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  

*Focused on Interactive CLI Fuzzy Finders, Desktop Command Launchers, Shell History Search, Smart Directory Jumpers & Terminal Multiplexing*  

**Last updated: November 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **CLI Fuzzy Finders & Terminal Productivity**. These tools filter, search, launch, navigate, and automate files, command histories, processes, Git commits, and desktop applications at lightning speed using fuzzy-matching algorithms, terminal user interfaces (TUIs), and keyboard-driven command palettes.



**Examples** include fzf, skim, peco, pick, fzy, rofi, dmenu, Alfred, Raycast, Everything, and junegunn/fzf (the category leaders and popular runtimes). 



**Open-source emphasis**: This section is heavily expanded with every major active open-source fuzzy finder (`junegunn/fzf`, `skim`, `peco`, `fzy`, `pick`, `television`), cross-platform keyboard launchers (`rofi`, `dmenu`, `Vicinae`, `Albert`, `Ulauncher`, `Flow Launcher`), and shell productivity multipliers (`Atuin`, `Zoxide`, `Starship`) — ideal for terminal power users, software developers, Linux/macOS/Windows tweakers, and DevOps engineers.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Support & Share](#support--share)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Raycast (Pro & Cloud Sync)](https://raycast.com)**  

  Blazingly fast, extensible macOS (and Windows) command launcher featuring fuzzy search, clipboard history, window management, AI commands, and cloud-synced snippets/settings.



- **[Alfred (Powerpack)](https://alfredapp.com)**  

  Iconic macOS productivity launcher and workflow automation suite offering instant fuzzy file/app search, custom scripts, hotkeys, and synced preferences.



- **[Everything (Voidtools)](https://voidtools.com)**  

  Ultra-fast freeware Windows desktop filename search engine that indexes NTFS/ReFS volumes in seconds for instantaneous fuzzy/regex file lookups.



- **[Warp (Cloud-Synced Terminal)](https://warp.dev)**  

  Modern GPU-accelerated terminal featuring built-in fuzzy command search, AI command lookup, and cloud-synced team workflows and notebooks.



- **[Fig / Amazon Q Developer CLI](https://amazon.com)**  

  Cloud-backed terminal autocomplete and fuzzy command-palette overlay adding IDE-style completions across hundreds of CLI tools.



- **[GitHub Codespaces & Cloud Shell Environments](https://github.com)**  

  Managed cloud terminal workspaces delivering instant browser-accessible shells pre-configured with fuzzy search, dotfiles sync, and keyboard-centric navigation.





## Open-Source GitHub Projects



- **[junegunn/fzf](https://github.com)**  

  Flagship open-source command-line fuzzy finder written in Go with zero dependencies, shell keybindings (`Ctrl-T`, `Ctrl-R`, `Alt-C`), split-screen previews, and Vim/Neovim integration.



- **[skim (`skim-rs/skim`)](https://github.com)**  

  Fast, extensible open-source fuzzy finder written in Rust serving as both a standalone CLI binary and an embeddable Rust crate for TUI applications.



- **[peco (`peco/peco`)](https://github.com)**  

  Simplistic, interactive open-source filtering tool written in Go for filtering logs, process lists, and command pipelines with incremental regex/fuzzy matching.



- **[fzy (`jhawthorn/fzy`)](https://github.com)**  

  Lightweight open-source terminal fuzzy text selector in C featuring a refined scoring algorithm tuned specifically for source code file paths.



- **[pick (`mptre/pick`)](https://github.com)**  

  Minimalist, POSIX-compliant open-source fuzzy search tool written in C designed to read choices from `stdin` and output the selected match cleanly.



- **[Television (`alexpasmantier/television`)](https://github.com)**  

  Blazing-fast, general-purpose open-source Rust TUI fuzzy finder featuring modular "channels" (files, Git, Docker, env vars, man pages) and built-in syntax-highlighted previews.



- **[rofi (`davatorium/rofi`)](https://github.com)**  

  Popular open-source window switcher, application launcher, and `dmenu` replacement for X11 and Wayland desktops with customizable themes and script modes.



- **[dmenu (`suckless.org`)](https://suckless.org)**  

  Legendary lightweight, suckless open-source dynamic menu for X11 that reads newline-separated items from `stdin` for instant keyboard-driven launching.



- **[Atuin (`atuinsh/atuin`)](https://github.com)**  

  Open-source magical shell history replacement written in Rust storing commands in SQLite with full-screen fuzzy TUI search, directory context, and optional E2E-encrypted sync.



- **[Zoxide (`ajeetdsouza/zoxide`)](https://github.com)**  

  Smarter open-source `cd` command written in Rust that tracks your most-used directories and jumps directly to them via fuzzy matching (`z` and interactive `zi` via `fzf`).



- **[Flow Launcher (`Flow-Launcher/Flow.Launcher`)](https://github.com)**  

  Open-source Windows quick-launcher and fuzzy search palette (Everything-integrated) supporting Python/C#/Node plugins, web searches, and system commands.



### Additional Strong Open-Source Options



- **[Vicinae (`vicinaehq/vicinae`)](https://github.com)** and **[Ulauncher (`Ulauncher/Ulauncher`)](https://github.com)** for fast, extensible open-source Linux application launchers inspired by Raycast and Alfred.

- **[nucleo (`helix-editor/nucleo`)](https://github.com)** for the ultra-fast parallel Rust fuzzy-matching engine powering the Helix editor and modern TUI tools.

- **[fd (`sharkdp/fd`)](https://github.com)** and **[Ripgrep (`BurntSushi/ripgrep`)](https://github.com)** for blazing-fast `.gitignore`-aware file and content discovery piped directly into `fzf` or `skim`.

- **[tmux (`tmux/tmux`)](https://github.com)** and **[Zellij (`zellij-org/zellij`)](https://github.com)** for open-source terminal multiplexing with fuzzy session/pane switching (`tmux-sessionizer`).

- **[Starship (`starship/starship`)](https://github.com)** and **[McFly (`cantino/mcfly`)](https://github.com)** for minimal cross-shell prompts and neural-network-ranked shell history search.



**Frameworks for building custom systems**: Combine **junegunn/fzf** + **fd** + **Ripgrep** + **bat** for instant interactive file and code navigation, **Zoxide + Atuin** for intelligent directory and command-history recall, and **rofi** or **Flow Launcher** for OS-wide keyboard launching.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Support & Share



If you find this curated list helpful, consider supporting the project:



- ⭐ **Star this repository** to help others discover it.

- 🍴 **Fork & Share** it with your team, friends, or community on X/Twitter, LinkedIn, and Reddit.

- ☕ **Buy me a coffee / Sponsor** my open-source work on [GitHub Sponsors](https://github.com) — featuring tiers for profile badges, README shoutouts, logo placements, and prioritized bug fixes/features!



[![Sponsor @ishandutta2007](https://shields.io)](https://github.com)



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Note that `Everything` (Voidtools) is closed-source freeware rather than open-source, so it is grouped under the non-open-source platforms section alongside proprietary launchers like Alfred and Raycast.

- Be mindful when piping sensitive environment variables, SSH keys, or shell history containing secrets into terminal fuzzy finders or cloud-synced history tools without redaction filters.



---



**Made for terminal power users, software engineers, Linux/macOS/Windows customizers, and open-source contributors.**  

Let's make command-line navigation and keyboard-driven productivity faster, lighter, and completely open-source.
