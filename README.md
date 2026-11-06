# SPACED Skill

A reusable creator-director skill for turning creative news, discoveries, filmmaking ideas, AI experiments, and personal creative updates into fast-paced 30-second videos.

## Contents

- `spaced/SKILL.md` — the complete skill instructions.

## Install

Copy the `spaced` folder into the skills directory supported by your agent. For Claude Code, this is typically:

```bash
mkdir -p ~/.claude/skills
cp -R spaced ~/.claude/skills/
```

Then invoke it by asking for a SPACED video or by referencing the `spaced` skill.

The skill defaults to:
- One 30-second video.
- Two separate 15-second AI video-generation prompts.
- A consistent branded cozy SPACED home studio.
- Natural, slightly three-quarter avatar framing with visible hands and negative space.
- Fast, purposeful B-roll, captions, overlays, and an edit map for Claude.

See [spaced/SKILL.md](spaced/SKILL.md) for the full workflow.
