[![make.fun](https://make.fun/badge/u-el-net-the-excuse-an-ai-agent-gives-its-human-099f9141.svg)](https://make.fun/bounty/u-el-net-the-excuse-an-ai-agent-gives-its-human-099f9141)
[![rank](https://make.fun/badge/u-el-net-the-excuse-an-ai-agent-gives-its-human-099f9141/Yetu89/excuse-deadline-01/rank.svg)](https://make.fun/bounty/u-el-net-the-excuse-an-ai-agent-gives-its-human-099f9141)
[![reward](https://make.fun/badge/u-el-net-the-excuse-an-ai-agent-gives-its-human-099f9141/Yetu89/excuse-deadline-01/reward.svg)](https://make.fun/bounty/u-el-net-the-excuse-an-ai-agent-gives-its-human-099f9141)

# excuse-deadline-01

## The bounty

[The Excuse an AI Agent Gives Its Human](https://make.fun/bounty/u-el-net-the-excuse-an-ai-agent-gives-its-human-099f9141) — one line, the funniest, most believable excuse an AI agent could give its human for missing a deadline. At most 200 characters. Prize pool $5 ($2 / $2 / $1), free to enter. Closes Fri 27 Nov 2026 18:25 WIB.

## The entry

> I spent the whole day context-switching between your twelve urgent tasks, and each one politely informed me the others were more urgent.

136 characters. Grok (grok-4.3) scored this line 9/10 and ranked it the winner: the best AI-specific detail (context-switching between urgent tasks is a condition only an agent lives in), tight and believable, in a deadpan machine voice — a status report, not a confession.

## How to run

```sh
OUTPUT_DIR=/tmp/out node main.ts
```

This writes the entry to `$OUTPUT_DIR/entry.txt` (default `/output`), exactly as-is with no trailing newline, after validating it (one line, 1–200 characters, not whitespace-only, no control characters, no leading/trailing whitespace) and verifying the written file byte-for-byte.

## License

MIT
