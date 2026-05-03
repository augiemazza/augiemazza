### Augie Mazza

Founder of [VARRD](https://varrd.com). Building tools to find statistically real trading edges with AI.

**Stuff I've built since I was a kid**

- **Before 12** — Couldn't play sports for medical reasons, so I learned to fly small prop planes instead. Landed one about 25 times before turning 13. Eventually got a procedure done, went back to sports — didn't love flying enough to stick with it. Just always been a doer.
- **12** — Started an ice cream truck because that's what I'd told everyone I wanted to be when I grew up. First "company," half a joke.
- **13** — Bought a 3D printer. Was one of the first 10 on Thingiverse to grab the fidget spinner model and started printing them along with Pokémon Go gear, sold to kids at my school and a few others. Mom kept the printer fed with filament while I was at school in 6th grade.
- **14** — Saved up for a laser engraver. Cut and engraved wood and granite for paying customers — first real online business.
- **2017** — Stuck Helium (HNT) routers in buildings where I had electricity access, paid owners small amounts for the watt usage. Bought a few Bitcoin miners around the same time. Mostly to learn the rigs, but they made some money too.
- Bought and flipped domain names (`iamlearninghowtogolf` among them, minor success). To drive traffic, ran Twitter bots that posted something useful instead of spam — pulled live gas prices via geo scripts and posted nationwide daily averages.
- Got into DeFi early, mostly to learn the mechanics rather than make money on it.
- Building with tensor models since they came out in 2017.
- A dozen other intellectually-curious paths I went down along the way — small ventures, weekend builds — not worth listing individually.

**The other side of those years**

Worked through my teens as a janitor at a private jet airport, in retail, at a fast food chain, and on a landfill. Hated all of it. Only now do I appreciate why my parents made me do those — they're the reason I'm not letting anything coast.

**Career**

Traded futures derivatives at one of Chicago's biggest futures firms from 18 to 22. Loved that the job was just you, your data, and your own code — the market eventually told you whether you were right. Still profitable, still trading.

**College**

Mostly stopped doing the curriculum — the teachers thought I was ahead of what we were covering, so the school let me work on my own ventures instead. They had me run Q&A sessions for the faculty and staff on AI and crypto, and I review their AI and BIS curriculum each year before classes start. Still come back a few times a year to talk to classes.

**About this GitHub**

VARRD has been built for years on our own servers — most of the work doesn't show up in this commit graph. What's here is the public surface (CLI, MCP, SDK).

**VARRD — how we got here**

Started this with Ben (Princeton math, buddy from Chicago). Four phases:

1. **Tools for ourselves.** Built research tools for ourselves and the Chicago futures firm we were trading at. Just trying to find edges faster.

2. **The engine.** Turned the tools into a system that takes a plain-English idea and turns it into a quantitative formula that gets tested under the strictest reasonable statistical settings. Took a couple years to build the DSL and the surrounding system. We were convinced this would change how traders work, and the bet has held up — the goal is everyone being able to trade on statistically valid signals. Test settings are kept strict on purpose, with the rule that **transparency, legitimacy, and honesty about what's actually being tested** comes before any individual result. Most ideas get killed. The ones that survive are real.

3. **Autonomous mode.** Realized that fully driving the engine took more bandwidth than most traders had time for. Built a mode where you point VARRD in a direction and it goes off and tests, discovers, and surfaces edges on its own — same context management, same test rules.

4. **Edges as a service.** People don't want a drill, they want a hole in the wall. Years of testing — by us, our pilot users, and now hundreds of researchers — built up a real library of edges, and we have meaningful compute through NVIDIA Inception. Privacy was a transparent paid option, taken by users who wanted it; everything else aggregates into a live feed. Now you can pay a few cents per query to see which VARRD-validated edges are firing right now, about to trigger on a pending bar close, or already in an open trade. Across the last 70 days the feed's edges have made money with small drawdowns. Edge discovery stopped being the bottleneck a while ago — properly attained edges, portfolio execution, and risk management are. So we cut out the first one.

The thesis: Terence Tao said idea generation is no longer the bottleneck — we'd already been building like that was true. The bottleneck moves to honest hypothesis testing, and that's a context-management and knowledge-graph problem more than a model problem.

With the agent economy ramping up, the natural interface is your AI talking to ours — paying small fees to query the research engine, autonomous mode, or the live edge feed. That's where we've leaned in.

200+ users. 100,000+ hypotheses tested. MCP server shipping now: `pip install varrd`.

**It's been a ride and we're nowhere near done.** What VARRD is today is a fraction of what it'll be. The early signs of the impact we set out for are already showing up.

**Where this is now**

- NVIDIA Inception partner
- Built alongside Wedbush's business development team
- Direct conversations with C-suite leadership across 10+ major financial firms — clearing brokers, prop trading shops, brokerage tech
- Pilot programs with 20+ brokerages, including most of the major US clearing firms
- Used by major hedge funds and prop trading firms
- Context-engineering work has caught unsolicited interest from major Silicon Valley AI labs — stayed focused on VARRD
- Multiple acquisition discussions active — holding out for terms that match where we believe this is going
- Bootstrapped — multiple funding offers fielded, the system funds itself, no equity given up

**Reach**

[@VarrdInc](https://twitter.com/VarrdInc) · [varrd.com](https://varrd.com)
