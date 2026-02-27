# CodeReach Releases

Public download page and release assets for the CodeReach daemon installer.

Site: [unboundcoder.com](https://unboundcoder.com)

## What is CodeReach?

CodeReach is a remote terminal system: a lightweight Go daemon runs on each target machine managing tmux sessions, and a native iOS app provides full terminal access from your iPhone. Supports LAN direct connections and gateway tunnels for remote access to machines behind NAT or WSL2.

## Downloads

Visit [unboundcoder.com](https://unboundcoder.com) or check the [Releases](https://github.com/wwallace04-projects/codereach-releases/releases) page.

## Installation

### Linux (RPM)
```bash
sudo dnf install ./codereach-daemon-*.rpm
```

### macOS (.pkg)
```bash
sudo installer -pkg ./codereach-daemon-*.pkg -target /
```

The installer handles everything: daemon binary, frpc tunnel client, service configuration, token generation, and automatic startup.
