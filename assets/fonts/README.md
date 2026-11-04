# Embedded fonts

| File | Source | License |
|---|---|---|
| `GeistSerif-Regular.ttf` | Geist Serif 1.001 (vercel/geist-font release v1.9.0, `GeistSerif/ttf/`) | SIL OFL 1.1, `OFL-GeistSerif.txt` |
| `JetBrainsMono-Regular.ttf` | JetBrains Mono 2.304 (release zip, `fonts/ttf/`) | SIL OFL 1.1, `OFL-JetBrainsMono.txt` |
| `MythicMonoAlt-Regular.ttf` | IBM Plex Mono 2.005 (IBM/plex release `@ibm/plex-mono@2.5.0`, `fonts/complete/ttf/`) | SIL OFL 1.1, `OFL-IBMPlexMono.txt` |

These are modified versions (subset, unhinted, GSUB/GPOS/GDEF removed, Geist Serif's GPOS
kerning flattened into a legacy `kern` table). IBM Plex Mono declares the Reserved Font Name
"Plex", so the modified copy is renamed "Mythic Mono Alt" (OFL section 3). Geist Serif and
JetBrains Mono declare none and keep their names. Geist Serif ships one weight, so there is no
medium or semibold. Rebuild with `build_fonts.py` (see its header). The OFL texts must be
distributed alongside any binary that embeds these fonts (e.g. in the library's LICENSE/NOTICE).
