# Setup Instructions — GitHub Profile README

## 1. Create (or open) the special profile repo

The repo name must match your username **exactly**:

```
https://github.com/georgengugi-04/georgengugi-04
```

If it doesn't exist yet, create a new public repo named `georgengugi-04` and check
"Add a README file" when prompted.

## 2. Add the README

- Open the repo → click on `README.md` → **Edit** (pencil icon).
- Delete everything, paste in the contents of `README.md` from this pack.
- Scroll down → **Commit changes**.

Your profile page (`github.com/georgengugi-04`) will update immediately.

## 3. Add the snake animation

- In the repo, click **Add file → Create new file**.
- For the filename, type: `.github/workflows/snake.yml` (GitHub will auto-create the folders).
- Paste in the contents of `.github/workflows/snake.yml` from this pack.
- Commit directly to the `main` branch.

> Already set this up before? Just replace the file's contents with the new version —
> it now generates the snake in GitHub's own dark-green palette instead of the default
> colors, to match the terminal theme. Re-run the workflow (step 5) after updating it.

## 4. Turn on GitHub Pages for the `output` branch

- Go to the repo's **Settings → Pages**.
- Under "Build and deployment":
  - Source: **Deploy from a branch**
  - Branch: **output** (this branch is created automatically the first time the workflow runs — if you don't see it yet, wait a minute and refresh)
  - Folder: **/ (root)**
- Save.

## 5. Run the workflow once manually (don't wait for the schedule)

- Go to the **Actions** tab in the repo.
- Click **Generate Snake** in the sidebar.
- Click **Run workflow → Run workflow**.
- Wait ~1–2 minutes, refresh, and the snake SVG will appear in your README.

It's scheduled to regenerate automatically every 12 hours after that, so it always reflects your latest contributions.

## 6. Before you're done — replace the placeholders

Open `README.md` and swap out:

- `REPLACE_WITH_YOUR_LINKEDIN_URL` → your real LinkedIn profile URL
- `REPLACE_WITH_YOUR_EMAIL` → your real email address

Everything else (stats, streak, trophies, activity graph) pulls live from your
GitHub username automatically — nothing else to configure.
