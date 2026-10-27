# Contributing

Start with the repository's own contribution guide, README, and applicable
AGENTS.md instructions. Repository-specific contribution restrictions, review
requirements, and security or release gates take precedence over these defaults.

Report security vulnerabilities through the repository's security policy.
Do not put sensitive reports, credentials, or private review material in public
issues or pull requests.

## Review before submitting

Running autoreview before opening a pull request is highly encouraged. Local
ClawSweeper is an optional, more extensive alternative. Review the final changes,
check actionable findings, and include the relevant testing and review outcome
in the pull request.

Use the [released shared autoreview installation guide](https://github.com/openclaw/agent-skills/blob/v0.6.0/docs/RELEASING.md#installing-a-pinned-source)
or the [local ClawSweeper guide](https://github.com/openclaw/clawsweeper/blob/main/docs/local-clawsweeper-skill.md).
Follow the selected tool's supported setup and repository requirements.

If automated review is unavailable, explain the limitation and the manual
review and testing completed. Do not purchase model access solely to satisfy
this guidance. A maintainer can decide the appropriate exception and next step.

## Maintainer review route

For this policy, a maintainer has effective maintain or admin permission on the
target repository, or is an organization owner.

Maintainers must complete local ClawSweeper on the final eligible changes.
When it is unavailable, complete autoreview and request one hosted ClawSweeper
review after the changes and validation are ready. Do not routinely run all
three review paths. Repository-specific exceptions and independent gates still
apply.

## Share useful results

Summarize the reviewed source, outcome, remaining findings, and limitations.
Generated preflight summaries are advisory: they do not prove trusted execution
or replace required tests, human review, or repository checks. Never describe an
incomplete or unavailable review as clean.

Batch related fixes before requesting another review. Check for an existing
queued or running review and do not repeat the request while it is pending.
Follow the target repository's published admission rules; this document does
not establish an automatic rejection, label, or fixed review allowance.

## Forks and exclusions

Follow upstream contribution guidance when working in a fork. These defaults
do not require changing fork workflows or settings, or authorize review bots
to write labels, comments, checks, assignments, branches, or other repository
state in a fork. Keep review results local or use an explicitly supported
read-only service route.

A pull request from a fork into an upstream repository follows the upstream
target's policy without changes to the source fork.

Temporary security-advisory repositories are excluded from this organization
review rollout.
