# Everything Homebrew installs. Run from the repo root:  brew bundle --file Brewfile
# Check what's missing without installing:               brew bundle check --file Brewfile
# Entry lines must stay `kind "name"` with no trailing comment.

# --- Command-line tools
brew "git"
brew "gh"
brew "node"
brew "pnpm"
brew "mas"

# --- SDKs and runtimes
# Deliberately NOT brew "powershell": the formula pulls in its own .NET, which
# shadows the SDK on PATH. Install PowerShell as a dotnet global tool instead.
cask "dotnet-sdk"
cask "microsoft-openjdk@21"

# --- Apps: now
cask "visual-studio-code"
cask "ghostty"
cask "iterm2"
cask "claude"

# --- Apps: later (uncomment, then re-run brew bundle)
# cask "obsidian"
# cask "vlc"
# cask "rectangle"
# brew "scrcpy"
# brew "zoxide"
# brew "fzf"

# --- VS Code extensions
vscode "bierner.markdown-mermaid"
vscode "mermaidchart.vscode-mermaid-chart"
vscode "ms-vscode.powershell"
vscode "zainchen.json"
