# OpenWolf + Git/GitHub Workflow

@.wolf/OPENWOLF.md

This project uses OpenWolf for context management. Read and follow .wolf/OPENWOLF.md every session. Check .wolf/cerebrum.md before generating code. Check .wolf/anatomy.md before reading files.

## Git & GitHub Workflow

**Repository:** https://github.com/BenTheWin/ClaudeOKCPools

**Mandatory commit practices:**
- After every significant code change, test completion, or bug fix, commit locally with a clean, descriptive message
- Commit message format: `[type] subject` where type is: fix, feat, refactor, docs, test
  - Examples: `fix: resolve null pointer in API endpoint`, `feat: add user authentication`, `docs: update deployment guide`
- Push to GitHub regularly (at least daily or after major changes) to maintain backup and version history
- Never push broken code; ensure tests pass and code is stable before pushing
- Use atomic commits — each commit should represent one logical change

**Workflow:**
1. Make code changes
2. Test locally to ensure stability
3. Run `git add <files>` to stage changes
4. Run `git commit -m "message"` with clear, descriptive message
5. Run `git push origin main` to push to GitHub
6. If reverting is needed, use git history or GitHub to restore previous versions

**Reason:** This ensures we always have a backed-up version of the project, can easily revert changes if needed, and maintain a clear history of all work done.
