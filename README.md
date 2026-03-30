# context-compress

Claude Code plugin that intercepts Read/Grep/Glob tool outputs and compresses them to save context window tokens.

## Install

```bash
claude plugin marketplace add jhollander/context-compress
claude plugin install context-compress@context-compress
```

## Status

Currently in canary/testing mode — hooks log to `/tmp/context-compress.log` to verify they fire on built-in tools.
