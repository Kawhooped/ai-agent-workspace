# VOIDD Manager Hub

Single-file GitHub Pages workspace. Talk to a manager, list repo files through the GitHub API, open a file, commit it back.

Live (after Pages is on):
https://kawhooped.github.io/ai-agent-workspace/

## First open
1. Settings → Pages → Deploy from GitHub Actions (this repo has `.github/workflows/pages.yml`).
2. Open the Pages URL on your phone.
3. Config:
   - Gemini key (stays in localStorage)
   - Repo like `Kawhooped/arcade`
   - Branch `dd-main`
   - Fine-grained PAT with Contents: Read and Write on that repo
4. Fetch. Open a file. Edit. Commit.

## What this is not
- Keys are never committed.
- The paste you were given only listed the root and never wrote. This one reads the tree and commits.
- Do not paste a classic PAT with repo scope on a public page if you can use a fine-grained token instead.
