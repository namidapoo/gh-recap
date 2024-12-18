This repository is a fork of https://github.com/matsubara0507/gh-wrap.
Below are the modifications made:
- Added Reviewed PRs count
- Added Spinner for data fetching

# gh-recap

![画面収録 2024-12-18 20 59 20](https://github.com/user-attachments/assets/1a1b49ba-01fb-47a9-bdb2-6a0de2874f79)

```
$ gh wrap -h
Collect your yearly GitHub all stats
 - Commits : yearly commits count in all private/public repositories
 - PullRequests : yearly opened pull requests count in all private/public repositories
 - Issues : yearly opened issues count in all private/public repositories
 - NewRepos : yearly created repositories count without fork

USAGE
  gh recap [<year>] [flags]

FLAGS

INHERITED FLAGS
  -h, --help                     Show help for command

ACKNOWLEDGMENTS
  This gh extension is inspired by https://lowcode.land/ghwrap/

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
