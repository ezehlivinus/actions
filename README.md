# GitHub Actions Examples

Compact set of focused GitHub Actions samples. Each folder covers one topic: triggers, job flow, artifacts, custom actions, secrets, containers, or security.

## Purpose
Show practical patterns without long explanations.

## Project List

1. [Basic Workflow](https://github.com/ezehlivinus/basic-workflow) – first simple workflow and manual trigger
2. [Job Dependencies](https://github.com/ezehlivinus/job-dependencies) – jobs that wait on others and pass data
3. [Issue Events](https://github.com/ezehlivinus/issue-events) – reacting to issue open / label events
4. [Event Triggers](https://github.com/ezehlivinus/event-triggers) – multiple events, path filters, manual dispatch
5. [Advanced Execution Patterns](https://github.com/ezehlivinus/advanced-execution-patterns) – matrix builds, reusable workflow, continue-on-error
6. [Custom Actions](https://github.com/ezehlivinus/custom-actions) – local composite / JS / Docker action examples
7. [Artifacts and Outputs](https://github.com/ezehlivinus/artifacts-and-outputs) – share build files and small values between jobs
8. [Environment Variables & Secrets](https://github.com/ezehlivinus/env-variables-and-secrets) – safe use of env vars and secrets
9. [Docker Workflows](https://github.com/ezehlivinus/docker-workflows) – run jobs in a container + service (e.g. MongoDB)
10. [Security](https://github.com/ezehlivinus/security) – least‑permission tokens, simple script injection guard


## Highlights
- Triggers (push, PR, manual, issues)
- Job relationships (`needs`, matrix)
- Outputs & artifacts
- Custom local actions
- Secrets vs plain env vars
- Container + service usage
- Minimal permission security pattern

## Notes
- Short on purpose
- No invented metrics
- Mix and reuse components freely

## Order Suggestion
basic-workflow → job-dependencies → issue-events → event-triggers → advanced-execution-patterns → custom-actions → artifacts-and-outputs → env-variables-and-secrets → docker-workflows → security

Feel free to adapt any snippet.