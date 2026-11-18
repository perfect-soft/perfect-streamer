# Changelog

The full version history is in the documentation:

- **Perfect Streamer Meshwork (2.x):** [What's new](https://doc2.pstreamer.tv/en/manual/whats_new/index.html)
- **Version 1.x and the free demo:** [What's new](https://doc.pstreamer.tv/en/manual/whats_new.html)

## 2.1.2.656 — Beta 3 (update) (2026-11-18)

An update of Beta 3 in the beta channel `pstreamer2-beta` (package 2.1.2.656-1). The stable version stays 2.0.2.423. Full
list: [What's new, 2.1.2 — Beta 3](https://doc2.pstreamer.tv/en/manual/whats_new/index.html#whats-new-2-1-2-656).

- Login page: the short tagline «Management and monitoring».
- Topology and Transport Links: an SRT or PS1 connection without autologin to a domain node's listener is drawn once, as
  the member link with its telemetry, not also as an external source.
- Stream editor: out-of-range OTT and DVR values are refused at the field, and saving stays blocked until they are fixed.
- Russian console and help: the term «автологин» throughout.

## 2.1.2.653 — Beta 3 (2026-11-16)

Public beta of Perfect Streamer Meshwork 2.1, beta channel `pstreamer2-beta` (package 2.1.2.653-1). The stable version stays
2.0.2.423. Full list: [What's new, 2.1.2 — Beta 3](https://doc2.pstreamer.tv/en/manual/whats_new/index.html#whats-new-2-1-2-653).

- RTMP and RTMPS publishing from encoders to the node's own RTMP server.
- Archive: export of a fragment to an MPEG-TS or MP4 file; the real broadcast time in archive playback.
- Console player for streams and adaptive bundles.
- Adaptive bundles: a player compatibility check, the variant order, viewer failover to a backup node.
- Meshwork domain library and Topology: external sources, a new stream from a library entry, folding in large domains.
- Meshwork reserve: the multicast reserve switches on a key frame.
- Security: PSE2 encryption for Pro-MPEG and PS1.
- Alerts to team messengers over a webhook; new alerts for a stalled processing thread and A/V drift.
- Installation: a test instance next to a production node; a clear message when resources run short.

Demo builds published on this page: see [Releases](https://github.com/perfect-soft/perfect-streamer/releases).
