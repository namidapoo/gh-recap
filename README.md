This repository is a fork of https://github.com/matsubara0507/gh-wrap.

Below are the modifications made:
- Change the issue count logic
  - `before`: Count the issues you have opened
  - `after`: Count the issues you have been assigned to and closed
- Added Reviewed PRs count
- Added Spinner for data fetching

# gh-recap

![画面収録 2024-12-18 21 17 45](https://github.com/user-attachments/assets/eab8ed56-16b0-4c22-b718-4d72e7b6fd53)

```
$ gh recap -h
Collect your yearly GitHub all stats
 - Commits : yearly commits count in all private/public repositories
 - PullRequests : yearly opened pull requests count in all private/public repositories
 - Issues : yearly opened issues count in all private/public repositories
 - NewRepos : yearly created repositories count without fork
 - ReviewedPRs : yearly reviewed pull requests count in all private/public repositories

USAGE
  gh recap [<year>] [flags]

FLAGS

INHERITED FLAGS
  -h, --help                     Show help for command

ACKNOWLEDGMENTS
  This gh extension is inspired by https://lowcode.land/ghwrap/ and https://github.com/matsubara0507/gh-wrap

$ gh recap
GitHub CLI Recap 🚀: namidapoo's 2024 GitHub ALL Stats
+----------------------+----------------------+
| Commits              |                 2174 |
+----------------------+----------------------+
| PullRequests         |                  347 |
+----------------------+----------------------+
| Issues               |                  127 |
+----------------------+----------------------+
| NewRepos             |                   60 |
+----------------------+----------------------+
| ReviewedPRs          |                  129 |
+----------------------+----------------------+
```
