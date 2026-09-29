# 4. Where Everything Goes

## Folder Structure

```
CLAUDE.md                           your AI project context (you write it)
README.md                           start here
SUCCESS.md                          what you are scored against
SUBMISSION.md                       your submission form
LEARNING_LOG.md                     skills learned, with confidence scores
project.yaml                        project settings, read by the platform (do not edit)
guide/                              these instructions
.claude/skills/                     teach-me and troubleshoot
context/scenario-N-name/spec.md     the spec you gave the agent
docs/scenario-N-name/compilation.md the seven-section document
docs/ai-pipeline.md                 your AI pipeline (you create it)
docs/reflection.md                  your cross-engagement reflection
src/scenario-N-name/mockup.html     the mockup
proof/scenario-N-name/              screenshots
examples/worked-example-loandesk/   the finished reference engagement
```

Scenario names: `scenario-1-labline`, `scenario-2-clausetrack`, `scenario-3-claimgate`, `scenario-4-coldchain`, `scenario-5-payrun`.

## Standards

- **Real numbers, no placeholders.** Every cost has a figure and the reasoning behind it.
- **Diagrams live inside the documents** as Mermaid, so they render on GitHub.
- **No server, no account, no build step.** A library loaded from a CDN is fine if the file still opens from disk.
- **Fixture data only.** Invent names and figures. Never real personal, medical, or financial data.
- **No secrets anywhere**, ever.
- **Spec before build.** Commit each `spec.md` before its mockup.
- **Commit as you go.** At least one commit per engagement with clear messages. One big commit at the end is flagged.
- **AI use is expected and visible.** Your agent direction logs and AI pipeline show how you directed it.
- **Presentable cold in under five minutes.** Anyone opening a `compilation.md` should find the ship-readiness note in ten seconds.
