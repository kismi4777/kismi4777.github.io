# Nikita Bychkov — Portfolio

Personal site for Unity / Tech Art / 3D work: production highlights, an interactive lab demo, and two web tools.

## Open locally

```bash
python -m http.server 5500
```

Then open [http://127.0.0.1:5500](http://127.0.0.1:5500).

## Structure

| Path | Description |
|------|-------------|
| `index.html` | Main portfolio + compact lab clicker |
| `tools/html-code-studio.html` | HTML/CSS/JS editor with live preview |
| `tools/ramp-studio.html` | Gradient / LUT generator |
| `tools/gameplay-lab-demo.html` | Extended gameplay lab |

## Online leaderboard

Stored in **Firebase Realtime Database** (survives redeploys).

Setup: see [LEADERBOARD_SETUP.md](LEADERBOARD_SETUP.md) — create a free Firebase project with Google, paste the DB URL into `leaderboard-config.js`.
