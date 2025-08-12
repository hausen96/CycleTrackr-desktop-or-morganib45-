<img width="914" height="748" alt="Screenshot 2025-08-12 at 14 27 51" src="https://github.com/user-attachments/assets/bc5a6228-d9b0-4afd-bb47-2be9fe41de65" /># CycleTrackr-desktop-or-morganib45-
CycleTrackr is a Java/Swing desktop app that lets athletes sign in with Strava (OAuth 2.0) and read their activities to generate goals and simple analytics (distance, time, pace, power/HR when available). It is read-only, no activity uploads or posts. Tokens and cached data are stored locally on the user’s machine.

#  CycleTrackr (desktop)
Java/Swing desktop app that connects to a Strava account (OAuth 2.0) to read activities
and show weekly/monthly goals and basic analytics. Read-only; no uploads or posts.

Tech: Java 22, Swing, OkHttp, Jackson, SQLite.

## How it works
1) Click “Login with Strava” (OAuth in browser).
2) App receives a code on http://127.0.0.1:53817/callback and exchanges it for tokens.
3) Tokens are stored locally in a SQLite DB (`goals.db`); data never leaves the device.

## Privacy
See [PRIVACY.md](./PRIVACY.md).

## Screenshots
<img width="914" height="748" alt="Screenshot 2025-08-12 at 14 27 51" src="https://github.com/user-attachments/assets/d36c26c6-79bf-40fc-9152-d6d6f00bcee2" />
<img width="388" height="327" alt="Screenshot 2025-08-12 at 14 27 45" src="https://github.com/user-attachments/assets/583b9c4f-7ee1-441c-9529-219ff8b45251" />
