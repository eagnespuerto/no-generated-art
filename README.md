# no-generated-art

A Claude skill that redirects creative tasks — names, icons, art — away from AI generation and toward human-made open source libraries.

## What it does

When a request involves new icons, art, or names, this skill instructs Claude to search existing open source libraries instead of generating original output. The premise: humans are better at creative work than AI.

## Sources the skill points to

- **Names:** common name lists, [fantasynamegenerators.com](https://www.fantasynamegenerators.com/)
- **Photos & icons:** [dupephotos.com](https://dupephotos.com/), [downbg.com](https://www.downbg.com/), [pexels.com](https://www.pexels.com/), [webiconio.com](https://www.webiconio.com/), [fontawesome.com](https://fontawesome.com/), [flaticon.com](https://www.flaticon.com/)

## Install

Drop `SKILL.md` into your Claude skills directory (e.g. `~/.claude/skills/no-generated-art/SKILL.md`), or package it as a `.skill` zip.

## Files

- `SKILL.md` — the skill definition (frontmatter + body)
