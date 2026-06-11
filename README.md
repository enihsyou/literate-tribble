# literate-tribble

Experimental repository for testing GitHub App commit workflows.

## Commit Convention

This repository uses the **Arapacati** GitHub App for automated commits.

### Author Attribution Rules

| Scenario | Author | Co-Authored-By |
|----------|--------|----------------|
| Code entirely written by AI | `Hermes Agent <292837902+arapacati[bot]@users.noreply.github.com>` | `九条涼果 <enihsyou@gmail.com>` |
| Code entirely written by Claude Code | `Claude Code <292837902+arapacati[bot]@users.noreply.github.com>` | `九条涼果 <enihsyou@gmail.com>` |
| Code entirely written by other AI Agent | `<Agent Name> <292837902+arapacati[bot]@users.noreply.github.com>` | `九条涼果 <enihsyou@gmail.com>` |
| Code partially written by human | `九条涼果 <enihsyou@gmail.com>` | `Hermes Agent <292837902+arapacati[bot]@users.noreply.github.com>` |

### Notes

- All commits are signed by the GitHub App `arapacati`
- The `Co-Authored-By` trailer properly attributes contributions
- GitHub links co-authored commits to both the app and the human contributor
