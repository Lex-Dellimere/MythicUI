# Embedded fonts

| File | Source | License |
|---|---|---|
| `Inter-Regular.ttf`, `Inter-Medium.ttf`, `Inter-SemiBold.ttf` | Inter 4.1 (rsms/inter release zip, `extras/ttf/`) | SIL OFL 1.1 — `OFL-Inter.txt` |
| `JetBrainsMono-Regular.ttf` | JetBrains Mono 2.304 (release zip, `fonts/ttf/`) | SIL OFL 1.1 — `OFL-JetBrainsMono.txt` |

These are modified versions (subset, unhinted, GPOS kerning flattened into a legacy `kern`
table, GSUB/GPOS/GDEF removed). Neither font declares a Reserved Font Name, so the original
family names are kept. Rebuild with `build_fonts.py` (see its header). The OFL texts must be
distributed alongside any binary that embeds these fonts (e.g. in the library's LICENSE/NOTICE).
Design usage and metrics: `.apex/DESIGN-SYSTEM.md` §3.
