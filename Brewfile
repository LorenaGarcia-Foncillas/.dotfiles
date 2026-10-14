# Core Shell & Package / Runtime Managers
brew "starship"     # Cross-shell prompt
brew "antidote"     # Fast Zsh plugin manager
# uv comes from its own installer (no Homebrew bottle for this macOS
# version meant building the full LLVM+Rust toolchain from source)
brew "fnm"          # Fast Node version manager (replaces nvm)

# Modern CLI Productivity Tools
brew "bat"          # Cat clone with syntax highlighting
brew "eza"          # Modern ls replacement with git status & icons
brew "fd"           # User-friendly, fast find replacement
brew "fzf"          # Command-line fuzzy finder
# No delta pager for git diff — plain git diff is fine
brew "ripgrep"      # Blazing fast regex search (rg)
brew "zoxide"       # Smarter cd command that learns your habits
# dust comes from its own release binary (no usable bottle here, falls
# back to building llvm+rust from source)

# General Development Tools
# git itself comes from Apple's Command Line Tools (newer than Homebrew's here)
# git-lfs comes from its own release binary (also forced a Rust-from-
# source build via Homebrew on this macOS version)
# gh comes from its own release binary (no bottle for this macOS version)
brew "gitleaks"     # Secret scanner for git repos
brew "osv-scanner"  # Dependency vulnerability scanner
brew "cmake"
brew "ninja"        # Fast build system
brew "jq"           # JSON processor
brew "wget"         # Internet file retriever
brew "ffmpeg"       # Image/video handling
brew "openjdk@25"   # Java LTS runtime
brew "automake"
brew "pkgconf"
brew "texinfo"
brew "smartmontools" # Disk health (smartctl)
brew "mole"          # Disk cleanup (mo clean, mo purge)
brew "mas"          # Mac App Store CLI (installs mas entries below)

# Cloud, Backend & Database Tools
brew "awscli"

# Document & Media Utilities
brew "imagemagick"
# tectonic comes from its own release binary (Rust tool, no usable
# bottle here, falls back to building llvm+rust from source)
# yt-dlp comes from `uv tool install yt-dlp` (its rust-based build deps
# forced a full Rust-from-source build via Homebrew on this macOS version)
brew "rclone"       # Cloud storage sync tool
brew "poppler"      # PDF utilities
brew "potrace"      # Bitmap to vector tracing

# Personal extras — installed on this Mac, not part of upstream's curated set.
# Neuroimaging (FreeSurfer / ITK-SNAP / Slicer workflow)
brew "dcm2niix"     # DICOM to NIfTI converter
brew "eigen"        # Linear algebra library used by neuroimaging tools
# Dev tools in daily use here
# black comes from `uv tool install black` (same Rust-build issue)
brew "croc"         # Peer-to-peer file transfer
brew "ghostscript"  # PostScript/PDF interpreter
# hf comes from `uv tool install huggingface-hub` (same Rust-build issue)
brew "libsndfile"   # Audio file library
brew "llvm@18"      # Pinned LLVM toolchain
brew "pulumi"       # Infrastructure as code
brew "tmux"         # Terminal multiplexer
brew "tree"         # Directory listing

# Applications (Casks)
cask "google-chrome"
cask "visual-studio-code"
cask "zoom"
cask "microsoft-teams"
cask "tailscale-app"
cask "docker-desktop"

# Personal extras (casks)
cask "slack"
cask "spotify"
cask "chromium"
cask "github"       # GitHub Desktop
cask "basictex"     # LaTeX distribution
cask "inkscape"     # Vector graphics editor

# Mac App Store
mas "Xcode", id: 497799835
mas "TestFlight", id: 899247664
mas "Pages", id: 409201541
mas "Keynote", id: 409183694
mas "Numbers", id: 409203825
mas "AdBlock Pro", id: 1018301773
