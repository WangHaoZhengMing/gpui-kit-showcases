# Diffy

Diffy is a native Git diff viewer built in Rust with GPUI Kit. It helps developers keep up with changes across projects and coding-agent workspaces.

## Review changes as they happen

Read live staged, unstaged, and untracked changes in split or unified views. Syntax highlighting, inline changes, expandable context, source copying, and remembered reading positions make it easier to follow a review. Stage or unstage whole files from the viewer.

## Keep worktrees together

Git worktrees share one project entry, with separate checkout tabs. Each checkout keeps its own selected file, scope, and reading position. Keyboard navigation and a searchable command palette help move between projects, worktrees, and changed files.

## Read GitHub pull requests

Review open and draft GitHub.com pull request diffs using an existing GitHub CLI login, without checking out a branch. Pull request review is read-only; comments, approvals, and merging stay on GitHub.

## Find your agent projects

Discover local Git projects from Herdr, Codex, and Claude Code, then choose which ones to import. Discovery reads local project metadata without running agents or reading their conversations.

## Platforms

Diffy supports macOS, Windows, and Linux. macOS is in beta; Windows and Linux are early alphas with limited hardware testing. All platforms require Git.

Diffy is published by hitSlop and is open source under the MIT license.

[Official website](https://diffy.run) · [Source code](https://github.com/hitSlop/Diffy)
