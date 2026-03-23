# python-learning
Python projects

## Run Pixel Runner in browser (GitHub Pages)

This repo includes a GitHub Actions workflow that builds `pygame_runner` with `pygbag` and deploys it to GitHub Pages.

### One-time setup in GitHub

1. Push `main` with `.github/workflows/deploy-pygame-runner-pages.yml`.
2. In your repository settings, open **Pages**.
3. Set **Source** to **GitHub Actions**.

### Deploy flow

- Any push to `main` that changes `pygame_runner/*` triggers a build + deploy.
- You can also deploy manually from the **Actions** tab with **workflow_dispatch**.

After deployment, your game will be available at:

`https://<your-github-username>.github.io/<your-repo-name>/`
