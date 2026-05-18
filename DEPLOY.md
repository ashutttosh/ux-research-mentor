# Deploy guide

Two commands. Two minutes.

## Option 1 — Deploy to Vercel only (fastest)

```bash
cd ux-research-mentor          # the folder this README lives in
npx vercel deploy --prod
```

On first run, the Vercel CLI will:
1. Open a browser to log in (use your existing `ashutttosh's projects` account).
2. Ask which scope/project to use — pick `ashutttoshs-projects`.
3. Ask if you want to link to an existing project — say **N** to create a new one.
4. Suggest a project name — accept default (`ux-research-mentor`) or change.
5. Deploy and print a URL like `https://ux-research-mentor-xxx.vercel.app`.

Subsequent deploys just need `npx vercel deploy --prod` from the same folder.

## Option 2 — Publish on GitHub + Vercel (full open-source)

### Step 1: Create the GitHub repo

If you have the GitHub CLI installed:

```bash
cd ux-research-mentor
git init
git add -A
git commit -m "Initial commit: UX Research Mentor plugin v1.0"
git branch -M main
gh repo create ux-research-mentor --public --source=. --remote=origin --push
```

Or without `gh`, create the repo on github.com first, then:

```bash
cd ux-research-mentor
git init
git add -A
git commit -m "Initial commit: UX Research Mentor plugin v1.0"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/ux-research-mentor.git
git push -u origin main
```

### Step 2: Connect Vercel to the repo

1. Go to https://vercel.com/new
2. Import the GitHub repo `ux-research-mentor`.
3. Framework preset: **Other** (or leave on auto-detect — it'll be a static site).
4. Root directory: `./` (default).
5. Click **Deploy**.

Future pushes to `main` will auto-deploy.

## After deploy

Once you have the URL:

1. Edit `README.md` and replace `[INSERT YOUR VERCEL URL HERE AFTER DEPLOY]` with the actual URL.
2. `git commit -am "Add live URL to README" && git push` — Vercel auto-deploys.
3. Share the URL.

## Custom domain (optional)

In your Vercel project settings → Domains → Add. If you don't own one yet:

```bash
npx vercel domains buy uxresearchmentor.com  # or similar
```

Then add it as the production domain.
