# Fork Customizations

> Upstream: [RamiAwar/dataline](https://github.com/RamiAwar/dataline)
> Fork maintained by: @ashsolei
> Last reviewed: 2026-04-08
> Fork type: **active-dev**
> Sync cadence: **monthly**

## Purpose of Fork

Chat-with-your-data tool customized for iAiFy analytics workflows and governance integration.

## Upstream Source

| Property | Value |
|---|---|
| Upstream | [RamiAwar/dataline](https://github.com/RamiAwar/dataline) |
| Fork org | AiFeatures |
| Fork type | active-dev |
| Sync cadence | monthly |
| Owner | @ashsolei |

## Carried Patches

Local commits ahead of `upstream/main` at last review:

- `b9b26d0 build(deps): bump qs and express in /frontend (#15)`
- `694d727 build(deps-dev): bump storybook from 8.2.2 to 8.6.18 in /frontend (#14)`
- `a8f6059 build(deps): bump requests from 2.32.3 to 2.33.0 in /backend (#2)`
- `72db43b build(deps): bump pygments from 2.18.0 to 2.20.0 in /backend (#5)`
- `2de5915 build(deps): bump aiohttp from 3.10.10 to 3.13.4 in /backend (#6)`
- `0068147 build(deps): bump lodash from 4.17.21 to 4.18.1 in /frontend (#12)`
- `b14ff30 build(deps-dev): bump vite from 5.4.14 to 6.4.2 in /frontend (#13)`
- `87a0803 build(deps-dev): bump flatted from 3.3.1 to 3.4.2 in /frontend (#1)`
- `c4f7776 build(deps): bump yaml from 2.4.5 to 2.8.3 in /frontend (#3)`
- `6a6deb0 build(deps-dev): bump brace-expansion from 1.1.11 to 1.1.13 in /frontend (#4)`
- `361f10c build(deps): bump lodash-es from 4.17.21 to 4.18.1 in /frontend (#7)`
- `88b063f build(deps): bump defu from 6.1.4 to 6.1.6 in /frontend (#8)`
- `8eedaf5 build(deps): bump tornado from 6.4.1 to 6.5.5 in /backend (#9)`
- `22a58b9 build(deps): bump picomatch from 2.3.1 to 2.3.2 in /frontend (#10)`
- `10372b5 chore: sync CLAUDE.md and copilot-instructions docs`
- `dda41ad ci: add github-actions ecosystem to dependabot`
- `440e5c5 docs: update FORK-CUSTOMIZATIONS.md with upstream source`
- `a0c381f docs: add FORK-CUSTOMIZATIONS.md per enterprise fork governance`
- `9834810 ci: add copilot-setup-steps.yml for Copilot Workspace`
- `9f01377 chore: add AGENTS.md`
- `60cb954 chore: add CLAUDE.md`
- `f742598 chore: add copilot-instructions.md`
- `fa90a47 chore: add Copilot Coding Agent setup steps`
- `acef54a chore: remove misplaced agent files from .github/copilot/agents/`
- `d2c1634 chore: deploy core custom agents from AgentHub`
- ... (8 more commits ahead of `upstream/main`)

## Supported Components

- Root governance files (`.github/`, `CLAUDE.md`, `AGENTS.md`, `FORK-CUSTOMIZATIONS.md`)
- Enterprise CI/CD workflows imported from `Ai-road-4-You/enterprise-ci-cd`

## Out of Support

- All upstream source directories are tracked as upstream-of-record; local edits to core source are discouraged.

## Breaking-Change Policy

1. On upstream sync, classify per `governance/docs/fork-governance.md`.
2. Breaking API/license/security changes auto-classify as `manual-review-required`.
3. Owner triages within 5 business days; conflicts are logged to the `fork-sync-failure` issue label.
4. Revert local customizations only after stakeholder sign-off.

## Sync Strategy

This fork follows the [Fork Governance Policy](https://github.com/Ai-road-4-You/governance/blob/main/docs/fork-governance.md)
and the [Fork Upstream Merge Runbook](https://github.com/Ai-road-4-You/governance/blob/main/docs/runbooks/fork-upstream-merge.md).

- **Sync frequency**: monthly
- **Conflict resolution**: Prefer upstream; reapply iAiFy customizations on a sync branch
- **Automation**: [`Ai-road-4-You/fork-sync`](https://github.com/Ai-road-4-You/fork-sync) workflows
- **Failure handling**: Sync failures create issues tagged `fork-sync-failure`

## Decision: Continue, Rebase, Refresh, or Replace

| Option | Current Assessment |
|---|---|
| Continue maintaining fork | yes - active iAiFy product scope |
| Full rebase onto upstream | feasible on request |
| Fresh fork (discard local changes) | not acceptable without owner review |
| Replace with upstream directly | not possible (local product value) |

## Maintenance

- **Owner**: @ashsolei
- **Last reviewed**: 2026-04-08
- **Reference runbook**: `ai-road-4-you/governance/docs/runbooks/fork-upstream-merge.md`
