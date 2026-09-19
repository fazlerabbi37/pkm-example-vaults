# Study: OpenWrt storage docs — 2026-08-24

| CUES (recall prompts)     | NOTES                                      |
|---------------------------|--------------------------------------------|
| What bounds package size? | overlay partition, ~2MB free on 8MB flash  |
| What does extroot do?     | mounts USB as overlay, removes ceiling     |
| Extroot failure mode?     | boot falls back if USB absent              |

**Summary:** Flash overlay, not RAM, is the constraint; extroot
trades the ceiling for a USB boot dependency.
