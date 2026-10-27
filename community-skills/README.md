# DUYTRUYENTHONG skill library

Made by [DUYTRUYENTHONG](https://github.com/DUYTRUYENTHONG), freely shared with the
community. This directory is a curated index. The surrounding repository remains
a fork of OpenAI Codex; its runtime code and upstream notices are preserved.
This directory does not install or replace Codex, activate hooks, or change the
agent currently running it.

## One source for each capability

| Layer | Canonical location | Use |
|---|---|---|
| Career workflow | [Vietnam Career Agent Kit](https://github.com/DUYTRUYENTHONG/vietnam-career-agent-kit) | Ten project skills and their tested local contracts |
| Personal library index | This directory's `catalog.json` | Pinned discovery links, hashes and adoption status |
| External collections | Pinned source reviews linked by the catalog | Candidates and examples, loaded only when relevant |
| Host tools/plugins | Your selected agent's supported integrations | Actual execution; a catalog cannot supply credentials or browser sessions |

Do not copy every source collection into an active skills directory. Select an
existing owner, read its skill, then load only references needed for the task.
Install or configure separately only when your chosen host supports it and you
intend to use it. A referenced collection is not a verified native integration.

## Career skills

All ten are maintained in Career Agent Kit, not duplicated in this Codex fork:

| Skill | Responsibility |
|---|---|
| `onboarding` | Workspace and capability setup |
| `candidate-evidence` | Supported facts and contradictions |
| `vietnam-job-discovery` | Relevant public vacancies |
| `job-normalization` | Vacancy identity, location and duplicates |
| `fit-assessment` | Requirements versus evidence |
| `application-tailoring` | CV and email wording |
| `document-review` | Rendered document content and layout |
| `campaign-approval` | Exact finite or standing scope |
| `browser-application` | Supported UI actions and handoffs |
| `application-tracking` | Receipts, counts and continuation |

`catalog.json` records immutable source URLs and Git-blob hashes for those ten
entrypoints. Follow their relevant policy and supporting references in the same
checkout. Downloading a single SKILL.md does not provide its dependencies.

## Use from a fresh checkout

1. Read `catalog.json` and select a capability. Its revision is the reviewed
   baseline; newer source revisions need their own review.
2. Clone the canonical repository separately and check out the recorded revision.
   Follow that repository's setup guide and fictional demo before using accounts.
3. Verify project discovery and actual tools in your host. Codex/Claude wrappers
   and generic handoff guidance have different compatibility scopes.
4. Keep candidate facts, credentials, receipts and screenshots in the selected
   external private workspace. Keep one canonical ledger and one existing owner.
5. Run deterministic checks with tools. Add parallel agents only for independent
   work when permitted; a shared authenticated browser has one action stream.

The catalog is intentionally inert JSON. It does not switch models, dispatch
agents, grant application authority, fetch updates or execute remote content.
No model cost, throughput or native-host integration is inferred from it.

## Add or update another skill family

Identify the gap and current owner first. Record the canonical repository,
immutable revision, exact path, SHA-256 of Git blob bytes, applicable license,
dependencies, decision and observed acceptance evidence. Reuse overlapping
capabilities; do not publish personal settings or copy third-party text without
its applicable notices. Upstream changes are new candidates, not automatic
promotions. Expand the catalog through focused reviewed commits.

Original documentation and catalog data in this directory are offered under the
repository's Apache-2.0 license. Career Agent Kit remains MIT; linked collections
retain their own licenses and source-specific caveats. This index does not
relicense them or claim authorship of OpenAI Codex or external work.
