# Lesson 01 specification

## STUDIO-001 · Launch a tested calculator on an existing server

**Status:** Instructor simulation; real technical evidence with synthetic learner replies.
**Next step:** Confirm your clone with the coach, then follow [Lesson 01](studio/lesson-01.md).
**Instructor implementation:** [issue #9](https://github.com/kaw393939/373_hosting/issues/9).
Create your own issue from the [lesson template](.github/ISSUE_TEMPLATE/studio-calculator.md).

## Agreed result

Launch the supplied published calculator image through your existing Traefik
network and a nonconflicting HTTPS hostname. Preserve unrelated services and
host access. Do not add another proxy/updater or build a substitute image.
The [release selection](studio/calculator-release.json) supplies the expected
commit and multi-platform digest independently of the running website.
An explicitly agreed adoption of a matching existing deployment is recorded
as adoption, not a fresh launch. This bounded lesson does not certify the whole
server baseline or a vulnerability-free image.

- **Public hostname:** https://studio-calc.mywebclass.org (temporary trial).
- **New launch or adopted deployment, and reason:** New isolated calculator launch; unused route and no owned studio container at preflight. See [new-launch evidence](studio/launch-evidence.json).
- **Own issue / feature branch:** [issue #1](https://github.com/kaw393939/is373-studio-retry-1027/issues/1), `studio/001-calculator`.
- **Agreed scope or actual access/configuration gap:** Supplied image on existing proxy network only; normal private terminal sudo. No proxy, host, OS or app-source changes.

Private SSH targets and configuration stay in ignored local state. Share only
reviewed, selected evidence; never commit credentials or raw server output.

## Evidence to keep

| Evidence | Actual result / link |
|---|---|
| Prepared Black/Pylint/pytest and real-image browser checks | Passed locally: Black, Pylint, 91 non-E2E and two real Docker/Chromium checks |
| Hosted image/commit, trusted HTTPS, valid and rejected API cases | Passed; [dated repeat verification](studio/evidence.json) |
| Preservation of unrelated services | 15 selected container identities/states/ports unchanged at launch and repeat verify |
| Own prediction, check interpretation, browser observation and keep/revise reason | [LEARNING.md](LEARNING.md), explicitly synthetic role-play; no real learner evidence |
| Accuracy review before publishing learner excerpts | AI/operator reviewed synthetic labels and real-evidence links; no actual student excerpts |
| Actual PR, latest CI, merge and issue closure | See actual issue/PR links; final `status` reads their current GitHub state |

Link the exported `studio/evidence.json`, actual CI and issue/PR when available.
CI does not deploy this server. A fixture, green check, timestamp, closed issue
or AI assertion alone does not establish the full result. `status` reports
recorded evidence and readiness for instructor review; it does not grade,
certify authorship or establish understanding.

## Optional instructor history

The records below are background, not steps to repeat. Their original anchors
remain here so earlier links continue to work.

## HOST-001 · Keep the Traefik dashboard private

[Historical requirement and evidence](book/changes/hosting-spec-history.md#host-001--keep-the-traefik-dashboard-private).

## HOST-002 · Controlled host maintenance

[Historical requirement and evidence](book/changes/hosting-spec-history.md#host-002--controlled-host-maintenance).

## HOST-003 · Companion image security maintenance

[Historical requirement and evidence](book/changes/hosting-spec-history.md#host-003--companion-image-security-maintenance).
