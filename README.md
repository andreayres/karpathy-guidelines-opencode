# karpathy-guidelines for OpenCode

Andrej Karpathy-inspired coding guidelines for OpenCode. Reduces common LLM coding mistakes through four core principles.

## The Problem

From Andrej Karpathy's observations:

> "The models make wrong assumptions on your behalf and just run along with them without checking. They don't manage their confusion, don't seek clarifications, don't surface inconsistencies, don't present tradeoffs, don't push back when they should."

> "They really like to overcomplicate code and APIs, bloat abstractions, don't clean up dead code..."

## The Solution

Four principles that directly address these issues:

1. **Think Before Coding** - Don't assume. Surface tradeoffs. Ask when unclear.
2. **Simplicity First** - Minimum code that solves the problem. Nothing speculative.
3. **Surgical Changes** - Touch only what you must. Clean up only your own mess.
4. **Goal-Driven Execution** - Define success criteria. Loop until verified.

## Installation

Install via OpenCode plugin manager:

```bash
opencode plugin https://github.com/YOUR_USERNAME/karpathy-guidelines-opencode.git
```

## Usage

Once installed, the skill `karpathy-guidelines` will be available globally. OpenCode will automatically load these guidelines in every session.

## Key Insight

> "LLMs are exceptionally good at looping until they meet specific goals... Don't tell it what to do, give it success criteria and watch it go."

## License

MIT

## Credits

- Original concept by [Andrej Karpathy](https://x.com/karpathy)
- Claude Code adaptation by [forrestchang](https://github.com/forrestchang/andrej-karpathy-skills)
- OpenCode plugin by YOUR_NAME
