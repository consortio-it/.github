# Contributing

These defaults apply to every repository in the organisation that does not define its own `CONTRIBUTING.md`.

## Branching and merging

- Work on a branch. Direct pushes to the default branch are blocked by an organisation ruleset.
- Every change reaches the default branch through a pull request, including your own. Approval is not required by default, but the pull request is.
- Merges are **squash only**. Merge commits and rebase merges are disabled.
- The squash commit takes its title from the pull request title, so write the pull request title as the commit message you want in `git log`.
- Head branches are deleted automatically on merge. The individual commits remain visible on the pull request's Commits tab afterwards.

## Pull requests

- Keep them small enough to review in one sitting, even if nobody else will review them.
- Resolve every conversation thread before merging. The ruleset enforces this.
- Use auto-merge rather than waiting on CI manually.

## History

The default branch keeps a linear history. Force pushes and branch deletion are blocked there.

## A note on smaller projects

Many projects here are staffed by one person. The pull request requirement is not ceremony: it is what produces the reviewable diff, the commit history on the pull request, and the record of why a change was made. Write the description for whoever picks the project up next, which is often you, eighteen months later.
