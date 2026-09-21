# Online leaderboard (Firebase)

KVdb emails failed — use Firebase instead (Google login, no confirm mail).

## Setup (≈2 minutes)

1. Open https://console.firebase.google.com/ (login with Gmail)
2. **Create a project** → name e.g. `portfolio-lab` → continue (Analytics off is fine)
3. Left menu: **Build → Realtime Database → Create Database**
4. Location: `europe-west1` (or any) → **Start in test mode** → Enable
5. Copy the database URL, looks like:
   `https://portfolio-lab-xxxxx-default-rtdb.europe-west1.firebasedatabase.app`
6. Paste it into `leaderboard-config.js` as `url: '...'`
7. **Rules** tab → paste contents of `firebase-database.rules.json` → Publish
8. Commit/push, or send the URL here and I’ll plug it in

After that the Players tab shows `онлайн · N`.
