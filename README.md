# Fan Guys Exam Pro

NASCLA electrical exam study app (single React app).

## Put it online (no command line needed)
1. Create a new repository on GitHub (Public or Private is fine).
2. Click "Add file" > "Upload files" and drag in EVERYTHING in this folder,
   including the `src` folder. Commit.
3. Go to vercel.com, sign in with GitHub, "Add New… > Project", pick this repo.
4. Vercel auto-detects Vite. Leave the defaults and click "Deploy".
5. You get a live link (like fan-guys-exam-pro.vercel.app) to share with the crew.

## File map
- index.html ........ the page shell
- src/main.jsx ...... boots the app
- src/App.jsx ....... the whole app (the file Claude built)
- package.json ...... lists React + Vite so the host can build it
- vite.config.js .... build settings
