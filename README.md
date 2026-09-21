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

The players table is stored in the cloud ([KVdb](https://kvdb.io)), not in GitHub Pages files.

**One-time activation:** open [https://kvdb.io/login](https://kvdb.io/login) and verify `dilda777@bk.ru` (check spam). Until then the UI shows «нужна активация».

Config: `leaderboard-config.js`
