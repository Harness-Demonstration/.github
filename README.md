# .github

Organisation defaults for Harness-Demonstration. GitHub uses the files here for every repository that has no file of its own at the same path.

- `.github/ISSUE_TEMPLATE/`: Agent task, Agent task (strong model) and Human task. The labels they set (`agent-ready`, `model:strong`, `needs-human`) must exist in each repository; `scripts/onboard-repo.sh` in the harness repository creates them.

How the labels drive the agent loop: https://github.com/Harness-Demonstration/harness/blob/main/docs/agent-loop.md
