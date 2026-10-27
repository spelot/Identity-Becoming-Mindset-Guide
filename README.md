# The Becoming Interview

An AI interviewer that asks you one hard question at a time, digs for real stories, and writes who you're becoming into a living file called `becoming.md`. Your AI tools can use that file to know what you stand for and push back when you drift.

Built for business leaders, owners, and coaches who serve clients. It runs in a Claude Project, a ChatGPT Project or Custom GPT, or Grok.

**Prompt v0.4.** Early. Run it on yourself first, then tell me what broke.

## The idea

We're all becoming. Everyone has a core, the person they're meant to be, but it gets buried under ego, wounds, baggage, and old stories. The interview helps you dig out what's already there, name what's in the way, and choose to live it. You make the calls about who you are. The AI asks the questions and keeps you honest.

It isn't therapy. It invites honesty about what gets in your way, but you set the depth.

## Start here

1. Open [SETUP-GUIDE.md](SETUP-GUIDE.md). It walks you through building the Claude Project in about 10 minutes.
2. Pick your instructions file: project-only memory for a clean first run, or shared memory if you want an interviewer that already knows you.
3. Upload the two context files and type "start."

## What's in here

| Path | What it is |
| --- | --- |
| `SETUP-GUIDE.md` | Step-by-step setup with every copy block included |
| `instructions/instructions-project-only.md` | The interviewer's instructions, for Use account memory **off** |
| `instructions/instructions-shared-memory.md` | Same instructions plus one section that stops the interviewer from skipping questions it thinks it knows the answers to |
| `context/becoming-template.md` | The structure of `becoming.md`. Upload to the project's Context |
| `context/getting-started-guide.md` | What the interviewer reads when you ask "how does this work?" Upload to Context |
| `LICENSE` | MIT license for this project |
| `NOTICE.md` | Third-party attribution |

## The nine phases

The core interview is Phases 1-8, about 30-45 minutes in one sitting or spread over as many sessions as you want. Phase 9 is its own session.

1. **The Last Word:** what you want said about you when you're gone
2. **What Shaped Me:** the stories behind who you are
3. **Core Values:** three, ranked, and how you slip from them
4. **Lines I Won't Cross**
5. **Future Me:** a normal workday three to five years out, in detail
6. **Mission**
7. **Who I'm Becoming:** statements with proof so far and a next rep
8. **Review and Confirm**
9. **Where This Shows Up:** how your core plays out at work, at home, and everywhere else

After that, come back in about 90 days for a Re-Grill: the interviewer checks what you said you're becoming against what you've actually done.

## How the file travels

`becoming.md` is the source of truth, not the chat. Say "update" to get the latest version, swap it into the project's Context, and say "continue" in a new chat. A Claude Project can't write back to its own files yet, so that last step is manual for now.

## Credits

Interview method adapted from "Grill Me" by Matt Pocock (MIT). See [NOTICE.md](NOTICE.md). Other influences are credited in the instructions. All questions and wording are original.

Built by Sage Pelot. My own work here is MIT licensed (see [LICENSE](LICENSE)).
