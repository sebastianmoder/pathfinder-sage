# Content Remediation Backlog

Reviewed: 13 September 2026

This file tracks editorial TODOs that remain in published content. Incomplete
pages are kept in `drafts/` and are intentionally excluded from the public
content tree.

## Completed in the September 2026 review

- Published an EU-oriented responsible-use guide covering privacy, AI Act
  escalation, oversight, transparency, copyright, accessibility, and tool
  selection.
- Replaced the former chain-of-thought page with outcome-first, checkable
  prompting guidance.
- Rewrote the task-level "When to use AI" guidance and corrected the consent and
  copyright framing.
- Published the feedback page with a privacy gate, rubric-grounded workflow,
  copyable prompt, and human-review checklist.
- Completed the lecture-slide section of the course-materials page.
- Moved incomplete standalone pages out of `content/` so they are not routed,
  searched, or included in the sitemap.

## Remaining published-content work

| Priority | File | Required change |
| --- | --- | --- |
| High | `content/genai/ai_detection.mdx` | Refresh time-sensitive detector evidence and add links to assessment alternatives, process evidence, and oral follow-up guidance. |
| High | `content/prompting/assign_job.mdx` | Replace placeholder role-prompt outputs with concrete education examples and explain when roles add little value. |
| High | `content/prompting/give_examples.mdx` | Add an education-specific few-shot example and publish the commented guidance on structure, format, and style. |
| Medium | `content/prompting/use_delimiters.mdx` | Add one substantial education prompt with clearly separated context, evidence, constraints, and output sections. |
| Medium | `content/teaching/lesson_planning.mdx` | Add an explicit outcomes–activities–assessment alignment check. |
| Medium | `content/teaching/curriculum_design.mdx` | Add a worked example for planning interactive learning. |

## Publication checks

Before marking an item complete:

1. remove its inline `TODO` comment;
2. verify time-sensitive claims with current primary sources;
3. confirm examples do not encourage disclosure of student data;
4. check internal links and references;
5. run `pnpm build`; and
6. inspect the affected routes, sidebar, sitemap, and search results.
