# Heeler for Mac

Mac builds (Mac Catalyst, Apple silicon) of [Heeler](https://github.com/ZingerLittleBee/Heeler),
the agent console for herdr and tmux over SSH.

This repository holds only release files: signed and notarized app archives on
[Releases](https://github.com/rockiestar-com/heeler-mac/releases) and the Sparkle
update feed `appcast.xml`. The app checks this feed and updates itself.

- **Requires:** macOS 15 or later on Apple silicon.
- **Install:** download the newest `Heeler-<version>.zip` from Releases, unzip it,
  and move `Heeler.app` to `/Applications`.
- **Not in the Mac build:** Remote Desktop, overlay networks (Tailscale, ZeroTier,
  EasyTier), Live Activities and widgets.

This is an unofficial community build. Heeler is made by
[ZingerLittleBee](https://github.com/ZingerLittleBee) and is licensed under the
Apache License 2.0 ([LICENSE](LICENSE)). Report Mac build problems here; report
app problems upstream.
