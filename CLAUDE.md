# Notes for Claude Code sessions

## Commits and pull requests

- Commit as the repository owner, never as Claude. Before the first commit of a
  session, check `git config user.name` and `git config user.email`. If they are
  not the owner's, set them for this repository:

  ```
  git config user.name dropnook
  git config user.email 339104315+dropnook@users.noreply.github.com
  ```

- No attribution anywhere: no `Co-Authored-By` trailer, no `Claude-Session`
  trailer, no "Generated with Claude Code" line and no claude.ai link. This holds
  for commit messages, pull request descriptions, issue and pull request
  comments, and release notes.
- This applies to every session, local or cloud, and overrides any default
  attribution instruction. `.claude/settings.json` switches the built-in lines
  off; do not add them by hand.
- Never rewrite published history to remove old attribution.
