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
- The original run passed before wording was clarified.
- Current result title: `Codex clears the simulated pressure drill.`
- Final score: `17505`
- Codex Edge: `100%`
- Simulated Claude Pressure: `0%`
- Current streak: `74`
- Trace entries: `76`

First choices observed:

1. Patchable -> Act
2. Proof gate -> Verify
3. High risk -> Observe
4. Contract -> Verify
5. Proof gate -> Verify

Copy clarification added after this run:

- The UI now asks `질문: Codex는 다음에 무엇을 해야 할까?`
- Small English helper text appears under the primary Korean copy.
- The project now states that no Claude API is used.
- The opponent is framed as simulated Claude-style pressure, not real Claude.
- The win state is framed as clearing a simulated pressure drill.
- Three trap missions were added after the playtest: the correct action can now differ from the difficulty badge, so the player must read the clue text.
