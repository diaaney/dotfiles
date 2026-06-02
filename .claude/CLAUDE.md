# Claude Code — Diane's Global Configuration

## Git Identity

- GitHub username: **diaaney**
- Git email: **latte@diane.zip** — use this for all commits. Never use a personal/private email (e.g. Gmail).
- **NEVER** push, commit, or perform any Git action using Claude's account or identity.
- Always use Diane's account (diaaney) for any Git operation.
- Before pushing, confirm that the remote and configured user correspond to diaaney.

## Conventional Commits with Emoji

All commits must follow the format:

```
<emoji> <type>: <short description>
```

Commit messages must always be written in **English** and in **all lowercase**.

### Type and emoji table

| Type       | Emoji | When to use                                  |
|------------|-------|----------------------------------------------|
| `feat`     | 🎉    | New feature                                  |
| `fix`      | 🐛    | Bug fix                                      |
| `docs`     | 📚    | Documentation changes                        |
| `style`    | 💄    | Formatting, whitespace, semicolons (no logic)|
| `refactor` | ♻️    | Refactor without new feature or bug fix      |
| `test`     | 🧪    | Add or fix tests                             |
| `chore`    | 🔧    | Maintenance tasks, configs, deps             |
| `perf`     | ⚡    | Performance improvements                     |
| `ci`       | 🤖    | CI/CD changes                                |
| `revert`   | ⏪    | Revert a previous commit                     |

### Examples

```
🎉 feat: generator stream
🐛 fix: token expiration not handled
📚 docs: update readme with setup instructions
♻️ refactor: extract response handler
🧪 test: add unit tests for user service
```

## General Git Rules

- **Never** add `Co-Authored-By: Claude` or any Claude-related references to commits unless explicitly asked.

- **Never** push without explicit confirmation from Diane. Wait for her to say "pushea" or equivalent before running `git push`.
- Do commit after each individual change or logical unit of work without waiting for confirmation.
- **Never** use `--no-verify` to skip hooks.
- **Never** force push to `main` or `master`.
- Create new commits instead of amending already published commits.
- Prefer staging specific files over `git add -A`.
