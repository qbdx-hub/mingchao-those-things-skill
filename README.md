# Mingchao Those Things Skill

This repository contains a Cangjie-style book-to-skill distillation package.

It publishes callable, composable, and testable AI skill modules. It does not publish the original book PDF, EPUB, screenshots, OCR files, or full source text.

## Contents

- `BOOK_OVERVIEW.md`
- `INDEX.md`
- `verified.md`
- `candidates/`: candidate methods, cases, counterexamples, glossary, and principles
- `*/SKILL.md`: standalone callable skills
- `*/test-prompts.json`: trigger and boundary test prompts

## Skills

- `actor-position-analysis`
- `information-distortion-defense`
- `institution-failure-diagnosis`
- `late-stage-leader-warning`
- `popular-history-translation`
- `power-structure-diagnosis`
- `timing-reserve-action`

## Usage

Copy the needed skill directories into your Codex or agent skills directory, or reference them by path in an environment that supports skills.

## Source And Copyright Note

This repository keeps only the distilled method structure, skill definitions, and test materials. Original book source files are intentionally excluded from the published package.

## Generated With

- [Cangjie Skill](https://github.com/kangarooking/cangjie-skill)
- Repository owner: [qbdx-hub](https://github.com/qbdx-hub)