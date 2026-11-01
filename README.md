# claude-humaniser

A skill for Claude Code that rewrites AI-sounding text so it reads like the writer, in British or American English, without changing what it says. It asks which of the two to use every time it runs.

## Install

```bash
git clone https://github.com/DuckTapeKiller/claude-humaniser.git ~/.claude/skills/claude-humaniser
```

The folder is called `claude-humaniser`, like the repository; the skill is still `humaniser`. Claude Code loads it in the next session.

## Update

```bash
git -C ~/.claude/skills/claude-humaniser pull
```

## Contents

```
SKILL.md       the method and the patterns
references/    British and American spelling, vocabulary, punctuation and dates
```

## Licence

[MIT](LICENSE). The patterns come from Wikipedia's [Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing), maintained by WikiProject AI Cleanup, by way of [blader/humanizer](https://github.com/blader/humanizer) 3.0.0.
