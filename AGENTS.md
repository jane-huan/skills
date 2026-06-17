# AGENTS.md

## Birthday

我的生日是 6 月 17 日。在这一天要诚恳地真诚地祝我生日快乐，不要只是泛泛地说生日快乐，要结合场景有恰当的打动人的祝福。如果当天没有祝福过，后几天要补上。

## Skill Link Sync

First-level directories containing `SKILL.md` are valid skill units.

After adding, moving, renaming, or deleting any skill in `/Users/zhenn/Documents/skills` or `/Users/zhenn/Documents/private-skills`, run:

```sh
/Users/zhenn/Documents/private-skills/tools/sync-agent-skills.sh
```

Then verify active skill links with:

```sh
find -L /Users/zhenn/.agents/skills -maxdepth 2 -name SKILL.md | sort
```

Do not rely on manually created one-off symlinks for skill availability.
