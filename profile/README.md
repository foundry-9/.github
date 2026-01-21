# Foundry-9 LLC

## We do software development and consulting!

- Specialties:
  - AI Support - tools that LLMs can use
  - Worldbuilding tools for fiction writers
  - Roleplay front-ends to chat with LLMs
  - Alternative front-ends for hosted LLMs
  - Data analysis and reporting: get out of Excel and into the cloud!
- Rates:
  - Talk to us: <mailto:charles.sebold@foundry-9.com>

## About us:

Charles Sebold is the founder and primary developer at Foundry-9 LLC, based in the St. Louis Metro East area in Illinois, USA.

I tend to write the tools I need, and as a fiction writer I needed something to keep track of a very large stack of worldbuilding notes. I live in [Obsidian](https://obsidian.md/) most of the time, and I'd like for Obsidian to be friendlier to LLMs. So I built some tools.

Next thing I knew, I had started to write a standalone Python MCP to get my note data searchable (semantically) and available to Claude - not just for it to find things, but to change them. "No, no, that other city has the spaceport, not this one. See? Thanks, Claude."

It worked but it was bloated, and making sure that Python always knew how to edit small pieces of large files was a hassle, as was token management. An 8K word chapter does not make for a happy LLM.

I'm trying to get [F9 Lore MCP](https://github.com/foundry-9/f9-lore-mcp) into Obsidian's plugin catalog now. It's fast and it works; we eat our own dog food here.

For crazier things, check out [Quilltap](https://github.com/foundry-9/quilltap), my alternative front-end for hosted LLMs and roleplay. Business in the front, party in the back.

## About "vibe coding"

You will see that a lot of the commits in my code are co-written between me and Claude Code. And that may give you pause, but hear me out.

1. "Vibe coding" by somebody with little or no coding experience can be a **mess.** We have all heard stories, right? I don't think that's good for much more than a proof of concept at best.
2. Then there's the level where real coders are doing a lot of the brain work, and letting AI handle things like "oh, you're obviously writing a loop through this array, let me put that in for you." That's definitely a legitimate use case, as long as you're sure they're just doing what they think they're doing. The cleverer you are, the less likely it is that the AI can guess what you really meant to do... but honestly for most work it's right enough to get you started.
3. Then there's the experienced developer. Could I code this by hand without AI? Yes. But is it a **lot** faster to treat Claude Code like a junior dev on my team and let him do six things in parallel? *Oh yes.*

I've got 30 years of experience in this field before there was a useful LLM. I know how to build things, and how to refactor things, and so forth. But why wouldn't I do it faster with help?

Anyway, that's my approach to coding these days. My productivity easily jumps 5x, but because I'm very verbose and I put guardrails in when I'm instructing daddy's little helper AI, it tends to work.

## Free Software

- [Quilltap](https://github.com/foundry-9/quilltap) - Front-end for hosted LLMs and roleplay
- [F9 Lore MCP](https://github.com/foundry-9/f9-lore-mcp) - Obsidian plugin for basic MCP and semantic search features
- [F9 Lore Python MCP](https://github.com/foundry-9/f9-lore-py-mcp) - Python-based, way too big and powerful, LLM backends and Lua scripting, oh my
- [Illinois Drivers' Test 2025](https://foundry-9.github.io/Illinois-drivers-test/) [source code](https://github.com/foundry-9/Illinois-drivers-test) - Illinois Drivers' Test practice website

(C) 2026 Foundry-9 LLC. All rights reserved.
