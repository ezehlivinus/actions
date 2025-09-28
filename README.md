# GitHub Actions Examples

Compact set of focused GitHub Actions samples. Each folder covers one topic: triggers, job flow, artifacts, custom actions, secrets, containers, or security.

## Purpose
Show practical patterns without long explanations.

## Project List
1. Basic Workflow – minimal manual workflow
2. Job Dependencies – gated multi‑job pipeline
3. Issue Events – issue trigger + push pipeline
4. Event Triggers – mixed event filtering
5. Advanced Execution Patterns – matrix / reusable / chaining
6. Custom Actions – composite, JS, Docker examples
7. Artifacts and Outputs – pass files & values
8. Environment Variables & Secrets – config & secret scopes
9. Docker Workflows – container + service job
10. Security – unsafe vs safer pattern

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