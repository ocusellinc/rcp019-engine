# Conventions for Claude Code

## Commit messages

All commits MUST use [Conventional Commits](https://www.conventionalcommits.org) format:

```
<type>: <description>
```

| Type | Use for | Version bump |
|------|---------|--------------|
| `feat` | New functionality | Minor |
| `fix` | Bug fixes | Patch |
| `chore` | Maintenance, deps, config | None |
| `docs` | Documentation only | None |
| `refactor` | Code change, no behaviour change | None |
| `test` | Adding or updating tests | None |

For breaking changes, add `BREAKING CHANGE:` in the commit body.

Never use a generic message like "update files" or "fix bug". Always use the conventional format.

## Repository

This is `ocusellinc/rcp019-engine`, formerly a fork of `zenlist/rets_expression`. It is maintained
independently and is no longer in that fork network. **Never** open pull requests or issues, push,
or comment on `zenlist/rets_expression`; all work stays in this repository. Keep the attribution in
`LICENSE.md`.

The main consumer is `ocusellinc/rulesetta`, which pins this crate by git tag. A fix reaches it
only after it is released here (release-please tag) and rulesetta's tag pin is bumped.
