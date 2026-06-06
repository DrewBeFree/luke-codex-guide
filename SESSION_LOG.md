## 2026-06-06 (Luke Codex guide site)

**What we did:**
- Read Drew/Luke transcript context and extracted Luke's setup pain points around Codex, GitHub, local folders, permissions, branches, and avoiding manual copy/paste loops.
- Created a beginner-friendly Codex + GitHub setup guide as static HTML and a printable PDF.
- Created and published `DrewBeFree/luke-codex-guide` for GitHub Pages with `CNAME` set to `luke.drewbefree.com`.
- Fixed unreadable command/code blocks by separating inline code styling from block code styling and regenerated the PDF.

**Where we stopped:**
- GitHub Pages is built from `main` and reports `cname: luke.drewbefree.com`.
- GitHub Pages HTTPS certificate state is `new`, so HTTPS enforcement is not enabled yet.
- Local repo is at `C:\Users\drewb\Documents\GitHub\sites\luke-codex-guide` on `dev`, with `main`, `origin/main`, and `origin/dev` all at `e78e162` before this log entry.

**Next up:**
- Wait for GitHub Pages certificate provisioning, then enable/verify HTTPS for `https://luke.drewbefree.com`.
- Review the guide in-browser after DNS/HTTPS settles and adjust wording/design if Luke needs a shorter version.

## 2026-06-06 (GUI-first Luke guide revision)

**What we did:**
- Revised the Luke Codex guide so the normal workflow is GUI-first after initial setup.
- Changed setup steps to use installers, Codex app, GitHub connection screens, VS Code, and optional GitHub Desktop.
- Moved terminal commands into an "Only If the GUI Gets Stuck" fallback section.
- Regenerated and pushed the matching PDF.

**Where we stopped:**
- `DrewBeFree/luke-codex-guide` has the GUI-first HTML and PDF on `main` and `dev`.
- Local repo is `C:\Users\drewb\Documents\GitHub\sites\luke-codex-guide` on `dev`.

**Next up:**
- Re-check `luke.drewbefree.com` after GitHub Pages finishes rebuilding and HTTPS certificate provisioning settles.
