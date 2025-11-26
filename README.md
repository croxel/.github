# Croxel Organization GitHub Configurations

This repository contains organization-wide GitHub configurations and workflow templates for Croxel.

## Workflow Templates

### Claude Code Action

AI-powered code assistant that integrates Claude into your PRs and issues.

**Features:**
- Code reviews triggered by `@claude review this PR`
- Feature implementation from issue descriptions
- Bug fixes with context-aware solutions
- Answer architecture and code questions

**How to add to your repo:**

1. Go to your repository on GitHub
2. Click **Actions** tab
3. Click **New workflow**
4. Find "Claude Code Action" under "By Croxel"
5. Click **Configure**
6. Commit the workflow file

**Usage:**

Once installed, mention `@claude` in any PR or issue comment:

```
@claude Please review this PR
@claude What does this function do?
@claude Can you add error handling to this?
@claude Implement the feature described in this issue
```

**Security:**
- Only runs on non-fork repositories (SDK forks like zephyr, msdk, hal_adi are excluded)
- Requires write access to trigger
- Uses organization-level API key

## Questions?

Contact Albert Garvett or see the [Claude Code Action documentation](https://github.com/anthropics/claude-code-action).
