---
name: featured-project-evidence
description: Use when changing any project bullet, repository link, repository slug, displayed stack or language label, or "Other projects" entry in this profile README. Covers repository identity, stack/language metadata, and description truthfulness.
---

# Featured project evidence

Trigger: changes to any project bullet, repository link, repository slug, displayed stack or language label, or "Other projects" entry.

## In scope

Public repository existence, repository slug casing, displayed stack/language metadata, description truthfulness against source docs and README files, and contact/blog link accuracy.

## Out of scope

README layout, punctuation, or tone. Those belong to `profile-readme-authoring`, not this skill.

## Core rules

- Read the source repository before changing a featured project description. The PR #2 correction exists because Synapse and Time Beam descriptions were assumed rather than verified.
- Do not attribute functionality that source docs do not support, especially LLM-powered or self-hosted behavior.
- Verify every repository exists through GitHub metadata before merging.
- Preserve historical but valid slugs such as `andorid-app`; do not change external repository identities without captain approval.
- Featured projects receive one-sentence factual descriptions; secondary projects stay in the compact inline list.
- When a description cannot be verified, remove or defer it rather than guessing.
- Any contact or blog link changed in the README must be checked live.

## Boundaries

- Do not generalize these rules to other repositories; they are specific to this profile README.
- Fact verification stays in this skill; layout and tone stay out.