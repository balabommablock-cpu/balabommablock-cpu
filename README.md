# Hi, I'm Rishabh 👋

I make AI tools simpler.

<sub>Takes toys seriously. Takes seriousness as a toy.</sub>

I'm a product manager (VP Product). Most of my job is noticing where people get stuck and taking that step away. On GitHub I do the same thing for open-source AI agents: small fixes, plain error messages, and the odd "we could just delete this".

## What I work on
- **Personal AI agents** that run on their own computer and talk to you in chat: OpenMausBot, rakazo, airi, nanobot.
- **Agent memory**: claude-mem, gbrain, hindsight.
- **The boring bits that decide whether people trust an agent**: does it say why it failed, does it stop asking the same question, does it do what the button says.

## A few merged fixes I like
- [rakazo #1468](https://github.com/elie222/rakazo/pull/1468): warn when a model can't see images, before you send one to it.
- [rakazo #1461](https://github.com/elie222/rakazo/pull/1461): keep a paragraph break between turns, so replies stop running into each other.
- [OpenMausBot #3026](https://github.com/milind-soni/OpenMausBot/pull/3026): name the HTTP status when an MCP server says no, instead of a vague error.
- [claude-mem #4855](https://github.com/thedotmack/claude-mem/pull/4855): switch back to the main model once it recovers.
- [airi #3013](https://github.com/moeru-ai/airi/pull/3013): make the speech cards open the settings they point to.
- [unifi-mcp #883](https://github.com/sirkirby/unifi-mcp/pull/883): don't report a saved setting as failed when only the check failed.

I also write product notes on issues. Some of them ended up on [hindsight](https://github.com/vectorize-io/hindsight)'s plan, which made my week.

## How I work
1. Find the step where people get stuck.
2. Make the smallest change that removes it.
3. Write the PR so anyone can review it in two minutes.

## Something I built
- [**stuckcheck**](https://github.com/balabommablock-cpu/stuckcheck): reads an AI agent's chat log and points at where it went in circles. No LLM needed.

<sub>Rule of thumb: if it needs a long README, it probably needs a shorter product.</sub>
