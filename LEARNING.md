# STUDIO-001 · Instructor simulation

**Synthetic learner replies, not a real student submission.** This is a scripted
coaching evaluation. Technical commands and browser observations were actually
performed by the AI/operator; the learner responses below are AI role-play.
They do not establish human authorship, review or understanding. The public
record contains no actual learner conversation or credentials.

## Prediction

Simulated learner, before the second launch plan: “I think DNS finds my server,
and Traefik uses the hostname to pick the calculator. I don't know what Docker
network does.” The coach explained that the existing Docker network connects
Traefik privately to the container without adding another public port.

## Check interpretation

Simulated learner: “It means the API rejected dividing by zero instead of
returning a number. I still need to see whether the webpage shows a helpful
error and clears the last result.” Stimulus was the actual `6 ÷ 0` API check:
expected 400, received 400. This does not establish every browser behavior.

## Browser observation

Simulated learner response based on the AI/operator's actual CUA browser check:
“6 times 7 shows 42 in both result areas and Results match. With divide by zero
both results become dashes and it says Cannot divide by zero.” This is not a
human observation; the role-play cannot substitute for a real student's turn.

## Keep decision

Simulated learner: “Keep it because the website and API agree on 42 and bad
input shows an error rather than keeping an old answer. The CMS title is
confusing, but I understand this lesson is hosting the supplied calculator,
not changing app code.” No application code was changed in this trial.

## Review

The AI/operator reviewed this synthetic summary for its labels, scope and
agreement with the actual command/browser evidence before publication. There
was no real learner excerpt or learner approval. CLI readiness checks only
record presence, publication and technical evidence; it is not an assessment.

## AI work and next step

The AI/operator created a separate template copy and fresh SSH clone, recovered
from GitHub template-generation timing by pulling after files appeared, created
a new virtual environment, and ran the prepared checks: Black/Pylint, 91
non-E2E tests and two Docker/Chromium journeys passed. A real new hosted launch
and subsequent verify passed the selected release identity, trusted HTTPS,
positive/negative API cases and preservation of 15 other containers.

See [scope](SPEC.md), [actual new-launch evidence](studio/launch-evidence.json),
[repeat verification](studio/evidence.json) and [trial issue](https://github.com/kaw393939/is373-studio-retry-1027/issues/1).
The [actual PR #2](https://github.com/kaw393939/is373-studio-retry-1027/pull/2)
evaluates the technical GitHub workflow separately. Retire the disposable
trial and remove only its resources after evidence is preserved.
