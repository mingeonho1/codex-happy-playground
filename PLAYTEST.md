# Playtest Note

Status: passed direct 60-second run.

Environment:

- File: `index.html`
- Runner: local headless Google Chrome opened against the static file URL
- Interaction path: Chrome DevTools Protocol coordinate clicks, with each target scrolled into viewport before clicking
- No login, no API key, no build step, no external network

Result:

- Start button clicked successfully.
- 60-second timer reached `0.0`.
- Codex made 74 visible action choices.
- Missed clicks: 0.
- Final result title: `Codex wins the sparring match.`
- Final score: `17505`
- Codex Edge: `100%`
- Claude Pressure: `0%`
- Current streak: `74`
- Trace entries: `76`

First choices observed:

1. Patchable -> Act
2. Proof gate -> Verify
3. High risk -> Observe
4. Contract -> Verify
5. Proof gate -> Verify
