# Changelog

The full version history is in the documentation:

- **Perfect Streamer Meshwork (2.x):** [What's new](https://doc2.pstreamer.tv/en/manual/whats_new/index.html)
- **Version 1.x and the free demo:** [What's new](https://doc.pstreamer.tv/en/manual/whats_new.html)

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
