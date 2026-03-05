# Congress Design — Research Intelligence

Static app for congress abstracts and research intelligence (dark/light theme, responsive).

## Run locally

```bash
npm install
npm start
```

Open [http://localhost:3000](http://localhost:3000).

## Deploy to GitHub and GitHub Pages

The project is already set up to push to **garimadasila4/congress-medical**. If your GitHub username is not `garimadasila4`, run:

```bash
git remote set-url origin https://github.com/YOUR_USERNAME/congress-medical.git
```

### 1. Create the GitHub repository

- Go to [github.com/new](https://github.com/new).
- **Repository name:** `congress-medical`
- Do **not** add a README, .gitignore, or license (this repo already has them).
- Click **Create repository**.

### 2. Push this project to GitHub

From the project root:

```bash
git push -u origin main
```

If prompted for credentials, use a [Personal Access Token](https://github.com/settings/tokens) (GitHub no longer accepts account passwords).

### 3. Enable GitHub Pages

- In the repo on GitHub: **Settings → Pages**.
- Under **Build and deployment**:
  - **Source:** Deploy from a branch
  - **Branch:** `main` — **/ (root)**
- Save.

The site will be available at:

**https://garimadasila4.github.io/congress-medical/**

Future pushes to `main` will trigger a new deployment automatically.
