# GitHub Actions Examples

Plain collection of small focused projects that show different GitHub Actions features. Each folder highlights one idea: triggers, job flow, outputs, custom actions, secrets, containers, or security basics. Wording is kept simple on purpose.

## Projects

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

## What You Can Learn Here

- How to wire basic through to moderately advanced workflows
- Ways to structure jobs that depend on each other
- Passing values (outputs) and files (artifacts)
- Writing and using your own actions
- Handling secrets and environment specific settings
- Running steps inside containers and with service containers
- Adding basic safety checks to workflows

## Quick Tour

Pick a folder, open its README (or the `.github/workflows` files if present) and scan the YAML. They are short and commented. Move in the order above if you are new; later folders build on earlier ideas.

## Simple Skill Map

- Triggers & events
- Job coordination (`needs`, matrix)
- Caching, artifacts, outputs
- Custom actions (composite / JS / Docker)
- Secrets & environment config
- Containers & services
- Basic security & permissions

## Notes

- No marketing claims or fake numbers included
- Names are descriptive, not fancy
- Focus is on clear, readable examples

Use anything here as a starting point for your own workflows.