# How to use your study partner

**What this is.** Two files that turn an AI assistant of your choice into a practice partner for this module – one that asks before it answers, refuses to do your exercises for you, and knows where AI models typically get this field wrong. Using it is **voluntary**. It contains nothing that is not also in the course script, so nobody who works without it is at a disadvantage.

**Setting it up** (pick the tool you already use):

- **Tools that read SKILL.md** (Claude, several CLI/IDE assistants): place the folder `mxup-study-partner/` with both files where your tool loads skills, or attach the folder to your project.
- **Custom assistants with an instruction field** (custom GPTs, Gems and similar): paste the *body* of `SKILL.md` (everything below the second `---`) into the instruction field – it fits the usual limit – and upload `referenz.md` as a knowledge file.
- **Plain chat, any provider:** attach both files at the start of a conversation and write: "Act according to SKILL.md; referenz.md contains the module's definitions."

**What to expect.** The partner will ask what you already have before explaining, will point at errors instead of fixing them, and will refuse finished solutions for exercise sheets and exam questions – by design. If that annoys you at 23:40 before a deadline: that is the annoyance working as intended.

**Two honest notes.** First: no setup guarantees compliance – if the assistant slips into answer-machine mode, remind it of its role or restart. Second: whatever it says, the course script is the binding source; where they disagree, the script wins.

**Keep it current.** Version and date are in the SKILL.md header (v1.0, 2026-08-21). Updates appear in the learning platform; around week 6 *you* will extend the pitfalls section yourselves – that is part of the course.
