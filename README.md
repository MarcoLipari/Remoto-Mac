# Remoto-Mac

A macOS screen streaming system that captures video via AVFoundation, FFmpeg encodes with hardware-accelerated H.264, serves HLS streams through MediaMTX, and exposes them via Cloudflare Tunnels. Built as a developoper tool for zero-configuration remote screen access without NAT traversal or server infrastructure or as a lightweight screen broadcasting solution.

Part of the Remoto Ecosystem. Initially built as a dependency for remoto (https://github.com/muhammadbalawal/remoto). You can use it independently or as part of the full Remoto application.

# Quick Start

Download and run MacQuick install or (preferred) use hombrew tap:

`brew install marcolipari/remoto/marcolipari-remoto`

Or `brew tap marcolipari/remoto` and then `brew install marcolipari-remoto`.

Or, in a `brew bundle` `Brewfile`:

```ruby
tap "marcolipari/remoto"
brew "marcolipari-remoto"
```

## Documentation
See https://github.com/MarcoLipari/homebrew-remoto

# Roadmap

## In Progress
- [ ] Configuration options
  - [ ] Support other available devices
- [ ] Fix bug: remoto-log not working

# Acknowledgements

MediaMTX - RTSP/HLS server
FFmpeg - Video encoding
Cloudflare - Tunnel service
