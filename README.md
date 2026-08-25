# .github

Default community health files for the Consortio IT organisation.

GitHub applies everything here to any repository in the organisation that does not have its own copy of the same file. A repository overrides a default simply by defining the file itself.

## Contents

| Path | Applies to |
| --- | --- |
| `.github/pull_request_template.md` | The pull request body, prefilled |
| `.github/ISSUE_TEMPLATE/*.yml` | The issue type chooser |
| `.github/ISSUE_TEMPLATE/config.yml` | Whether blank issues are allowed |
| `CONTRIBUTING.md` | Linked from new issues and pull requests |

## This repository is public, and has to be

GitHub does not source default community health files from a private repository. There is no way around this on the Team plan, since internal visibility requires Enterprise.

**Nothing here should reference a customer, an internal hostname, a project codename, or anything else you would not put on the company website.** The templates are deliberately generic for that reason.

## Gotchas

- Issue templates are all-or-nothing. If a repository has *any* file in its own `.github/ISSUE_TEMPLATE/` folder, including just a `config.yml`, none of the defaults here are used for that repository.
- `CODEOWNERS`, `LICENSE`, and `dependabot.yml` do **not** work as organisation defaults. They have to be added per repository.
- These files are not included when someone clones a repository. They exist only here.
