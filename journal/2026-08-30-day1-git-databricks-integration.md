# 📓 Journal - 2026-08-30 - Day 1: Git & Databricks Integration

## 💡 What I learned
1. Can't push to a repo I don't own.
   - How: Used "Use this template" to make my own copy instead of cloning.
2. Can edit/commit files in-browser with github.dev.
   - How: Pressed the period key on the repo page.
3. Databricks "Git folder" ≠ GitHub repo: _repo lives on GitHub, each person clones it into their own Databricks Git folder_.
   - How: Watched a YouTube guide on Databricks + GitHub integration.
4. Teammates never push/pull directly into each other's Git folders: _everyone syncs through the shared GitHub repo_.
5. Teams can pair individual git folders with one shared "final pipeline" folder that only pulls from main.
6. Creating a branch in a Databricks Git folder creates it on GitHub too.
   - How: Saw my "virna" branch appear live on Nella's repo.🥰
7. Fine-grained tokens scope access to specific repos/permissions, unlike broader classic tokens.

## 🌿 How I created my branch (Databricks → GitHub)
Nella's repo → copied URL → Databricks: Create → Git folder → pasted URL → cloned → clicked "Branch: main" → Create Branch → named "virna" → Create → checked out on my branch → confirmed live on GitHub 🎉

## 🤔 What confused me
1. Why I couldn't push to the original repo.
   - Clarified: only owner/collaborators can push. ([video](https://www.youtube.com/watch?v=fiDc6RgOhjU))
2. Mixed up cloning, forking, and templates.
   - Clarified: Sir Myk's README pointed to "Use this template"; confirmed via video since I'm a visual learner. ([video](https://www.youtube.com/watch?v=pGLwb5TJphM))
3. Being added to a workspace ≠ seeing a shared folder.
   - Clarified: asked an AI in simpler terms and watched videos last night; Sara also shared a helpful video. ([video](https://www.youtube.com/watch?v=uljYTx7nzy8))
   - Turns out the workspace only had a catalog so far.
4. Wasn't sure if I needed Nella's Git credential to collaborate.
   - Clarified using AI: everyone links their own GitHub account, _never someone else's_.
5. Wasn't sure how to keep a "final" pipeline version safe from edits.
   - Clarified: a Git folder can just stay on main and get pulled periodically.

## 🎯 One small next step
- [ ] Start making my first actual changes/commits on my "virna" branch

## ✅ Git checkpoint
- [x] Created my own copy of the repo using "Use this template"
- [x] Created journal/2026-08-30-day1.md
- [x] Joined the shared Databricks workspace
- [x] Linked my own GitHub account to Databricks
- [x] Mapped out the full team Git workflow
- [x] Cloned Nella's repo into my own Databricks Git folder
- [x] Created my own branch (virna), confirmed on GitHub
- [ ] Committed my changes
- [ ] Pushed my changes to GitHub
