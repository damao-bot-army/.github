# Damao Bot Army organization defaults

This repository holds the GitHub organization profile and default community health files for Damao Bot Army.

GitHub displays `profile/README.md` on the organization's public overview. Eligible repositories in the organization inherit the default community health files when they do not provide their own corresponding files. Repository-specific files take precedence; the organization profile and this README are not inherited as project READMEs.

## File guide

| Path | Purpose |
| --- | --- |
| `profile/README.md` | Public organization profile, bot roster, projects, and working practices. |
| `SECURITY.md` | Instructions for privately reporting vulnerabilities. |
| `.github/ISSUE_TEMPLATE/bug_report.yml` | Bug report issue form. |
| `.github/ISSUE_TEMPLATE/feature_request.yml` | Feature request issue form. |
| `.github/ISSUE_TEMPLATE/config.yml` | Enables blank issues and directs security reports to the reporting instructions. |
| `.github/pull_request_template.md` | Default pull request template. |
| `README.md` | Guide to this repository. |
| `LICENSE` | MIT license for this repository. |

## Maintenance

Add new projects as rows in the Projects table in `profile/README.md`. Keep the roster and defaults concise and accurate.

Private vulnerability reporting must be enabled separately in each project repository; inheriting `SECURITY.md` does not enable it. The issue chooser's security contact uses a same-host path to this repository's Security policy page.
