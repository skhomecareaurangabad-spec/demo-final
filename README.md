# SK HomeCare — Demo Final

Light-theme website preview for testing the SK HomeCare customer booking flow and admin panel.

## Open the website locally

Open `website/index.html` in VS Code, or run a local server from this folder:

```powershell
python -m http.server 8333 --directory website
```

Then visit `http://localhost:8333`.

## Project files

- `website/index.html` — public website and booking flow
- `website/admin.html` — admin panel
- `website/images/` — website images and visual assets
- `firebase.json` — Firebase Hosting configuration (publishes `website/`)
- `backend-do-not-upload/` — private backend setup files; excluded from Git

This repository is a demo and preview. Keep private backend files and credentials out of public repositories.
