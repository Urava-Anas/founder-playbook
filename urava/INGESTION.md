# Knowledge Ingestion Contract

Use this pipeline when adding books, standards, playbooks, repos, case studies or Urava execution evidence.

## Source classes

- **A — Urava locked/internal authority:** governance, architecture, approved policies.
- **B — Official/primary external authority:** standards, official documentation, original books where lawfully available.
- **C — High-quality distilled commentary:** Founder Playbook skills, notes, expert syntheses.
- **D — Real-world reference:** case studies, examples, community material.
- **E — Urava evidence:** measured outcomes from our own execution. E does not override safety/governance, but it should dominate context-specific practical recommendations over time.

## Pipeline

1. Register source metadata and provenance.
2. Extract principles, decision rules, anti-patterns and explicit limitations.
3. Separate source claims from Urava interpretation.
4. Map each item to one or more Developer House skills.
5. Check conflicts against `AUTHORITY.md` and existing intelligence.
6. Convert useful items into compact artifacts: router rule, checklist, rubric, test, tool, template or evidence hypothesis.
7. Do not load whole sources at runtime when a compact validated artifact exists.
8. Apply in real work and update `EVIDENCE.md` records.
9. Promote/downgrade/retire rules based on evidence and source changes.

## Current source notes

- The upstream Founder Playbook is a Class C MIT-licensed commentary source, not a substitute for its underlying books.
- The current Mom Test module can be used as Class C operational guidance until a lawful primary copy is available for verification.
- Uploaded technical books should be registered individually with exact edition/version; do not silently assume a newer edition than the actual file.

## Copyright and provenance

Store derived rules, commentary, citations, and short necessary excerpts. Do not turn the Urava overlay into a redistribution archive of copyrighted books. Preserve source attribution and license requirements for reusable code/docs.
