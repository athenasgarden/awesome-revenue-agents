# Awesome Revenue Agents [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of **local-first agents, playbooks, and tools** for builders who already shipped — and now need to get paid.

This is not another AI course dump.

[owainlewis/awesome-artificial-intelligence](https://github.com/owainlewis/awesome-artificial-intelligence) is the right list if you want foundations, papers, and AI engineering depth. This list is the next room: you can build. The gap is distribution, offers, and a stack that does not rent your margin to a credit meter.

**Audience:** solopreneurs, indie hackers, and small studios running agents on their own machines.

**Quality bar:** an entry has to help you find a customer, make an offer, take money, or keep the work running without a SaaS treadmill. Short categories beat padded ones.

## Contents

- [Why this list](#why-this-list)
- [Start here](#start-here)
- [Talk to customers](#talk-to-customers)
- [Offers and pricing](#offers-and-pricing)
- [Get paid](#get-paid)
- [Distribution without ads](#distribution-without-ads)
- [Local-first runtimes](#local-first-runtimes)
- [Agents you can actually run](#agents-you-can-actually-run)
- [Agent skills for revenue work](#agent-skills-for-revenue-work)
- [Copy, SEO, and listings](#copy-seo-and-listings)
- [Boring niches that print](#boring-niches-that-print)
- [Related lists](#related-lists)
- [Contribute](#contribute)

## Why this list

Most AI lists optimize for *learning the stack*. Builders who already shipped do not need another Transformer explainer. They need:

1. A way to hear a real problem without leading the witness.
2. An offer a stranger will pay for this week.
3. Rails that take the money.
4. Agents that do the repetitive parts (research, listings, replies, pages) on hardware they own.

If an item is only a model card, a framework hello-world, or a landing page with no working loop, it stays off this list.

## Start here

- [The Mom Test](https://www.momtestbook.com/) — How to talk to customers when everyone is lying to be nice. Two hours. Read it before you prompt an agent to "validate" anything.
- [Shape Up](https://basecamp.com/shapeup) — Fixed-time, shaped bets. Useful when an agent can generate infinite scope and you cannot.
- [Building Effective Agents (Anthropic)](https://www.anthropic.com/research/building-effective-agents) — Patterns that actually hold: workflows first, autonomy second.
- [Chip Huyen — AI Engineering](https://huyenchip.com/books/) — If you still need the product-engineering frame for foundation models, start here instead of a 400-link course list.

## Talk to customers

- [The Mom Test](https://www.momtestbook.com/) — Behavioral evidence over compliments.
- [Jobs to Be Done interview resources](https://jobs-to-be-done.com/) — Demand lives in the job, not in your feature list.
- [Indie Hackers Interviews](https://www.indiehackers.com/interviews) — Revenue numbers attached to boring products. Use as pattern library, not as a personality cult.
- [TinySeed](https://www.tinyseed.com/) — Bootstrapped operators talking about getting to $10k months without a growth team.

## Offers and pricing

- [$100M Offers — Hormozi](https://acquisition.com/books/offers) — Grandiose title, usable offer math: dream outcome, time delay, effort, risk.
- [SaaS pricing strategy guide](https://www.chargebee.com/resources/guides/saas-pricing-strategy-guide/) — Practical structures when you are past "I guess $9."
- [Patrick McKenzie on pricing](https://www.kalzumeus.com/2009/04/05/pricing-experiments/) — Old, still the cleanest public writing on charging more than feels polite.
- [kalzumeus.com](https://www.kalzumeus.com/) — Sell to businesses. Invoice. Stop undercharging because the model was free to you.

## Get paid

Prefer rails that let a one-person shop sell globally without inventing tax software.

- [Stripe](https://stripe.com/) — Default card rail. You own the customer object.
- [Polar](https://polar.sh/) — Open-source billing aimed at developers: digital products, subscriptions, GitHub access. Merchant of record option. [Source](https://github.com/polarsource/polar).
- [Lemon Squeezy](https://www.lemonsqueezy.com/) — Merchant of record for digital goods. Fine when tax compliance is the bottleneck.
- [Gumroad](https://gumroad.com/) — Fastest path for a file or a course. Ugly on purpose. Ships.
- [Paddle](https://www.paddle.com/) — MoR for software when you outgrow the first checkout.
- [AgentaOS](https://agentaos.ai/) — Merchant of record that sells for you in its own name and pays out to 85+ countries, including many where Stripe is not available; its MCP server lets an agent create products and checkout links.
- [Teachers Pay Teachers](https://www.teacherspayteachers.com/) — Existing marketplace. Worse margins, real buyers already standing there.
- [Kindle Direct Publishing](https://kdp.amazon.com/) — Same idea for short books and series.

Skip anything that only meters *your* inference credits and calls that a business model.

## Distribution without ads

- [Google Search Central](https://developers.google.com/search/docs) — One useful page that answers a query still beats ten agent-generated posts.
- [AlternativeTo](https://alternativeto.net/) — Directory that actual humans use when they hate the incumbent.
- [Zola](https://www.getzola.org/) — Static site generator. A directory should be a folder of HTML, not a Next.js bill.
- [Astro](https://astro.build/) — Same idea: ship pages, not a framework essay.
- [Eleventy](https://www.11ty.dev/) — Another good default for a one-person site that just needs to exist.
- [Pinterest business docs](https://business.pinterest.com/) — Organic discovery for visual products (printables, lesson packs, covers). Pins are pages with a URL.

## Local-first runtimes

Run the model where the files already are.

- [Ollama](https://ollama.com/) — Local model runner with a boring CLI and an OpenAI-compatible port.
- [llama.cpp](https://github.com/ggml-org/llama.cpp) — The actual engine a lot of the pretty UIs wrap.
- [LM Studio](https://lmstudio.ai/) — Desktop runner when you want a GUI and local OpenAI-compatible server.
- [Jan](https://jan.ai/) — Open-source desktop app, local-first, can point at remote providers when you choose.
- [vLLM](https://github.com/vllm-project/vllm) — When one box is serving several agents and Ollama is the bottleneck.
- [Open WebUI](https://github.com/open-webui/open-webui) — Self-hosted chat UI in front of local or remote models.

## Agents you can actually run

Not a census of every "agent framework." Things a person has been known to leave running.

- [OpenClaw topic](https://github.com/topics/openclaw) — Local-ish personal agent pattern: channels, memory, skills, always-on. Implementations fork weekly; start at the topic, not a random clone.
- [Goose](https://github.com/block/goose) — Block's open-source engineering agent with an extensible toolkit.
- [Aider](https://github.com/Aider-AI/aider) — Terminal coding agent that works against a git repo and leaves real commits.
- [Cline](https://github.com/cline/cline) — VS Code agent with MCP, browser, and terminal. Useful; watch what it sends off-box.
- [OpenHands](https://github.com/All-Hands-AI/OpenHands) — Open autonomous coding agent you can self-host.
- [n8n](https://github.com/n8n-io/n8n) — Self-hosted workflows when the job is glue, not a novel.

## Agent skills for revenue work

Skills are `SKILL.md` folders an agent loads on demand. Prefer small, inspectable skills over 8,000-file dumps.

- [anthropics/skills](https://github.com/anthropics/skills) — Official format, document skills, and skill-creator. Read this before you invent a schema.
- [obra/superpowers](https://github.com/obra/superpowers) — Methodology plus composable engineering skills. Heavy; steal structure, do not swallow whole.
- [royalpinto007/awesome-agent-skills](https://github.com/royalpinto007/awesome-agent-skills) — Small, security-aware directory. Skills are code the agent trusts.

**Skill ideas that belong on a revenue desk (write your own):**

- Draft directory listings from a product URL + constraints (no send).
- Turn a job-to-be-done interview into an offer page outline.
- Ship one static city / niche page per night and refuse thin pages.
- Reply desk: help first, pitch last or never.

## Copy, SEO, and listings

- [Google's SEO starter guide](https://developers.google.com/search/docs/fundamentals/seo-starter-guide) — Still the non-snake-oil version.
- [Copyhackers](https://copyhackers.com/) — Direct-response copy without the guru costume.
- [Screaming Frog](https://www.screamingfrog.co.uk/seo-spider/) — See what you actually published.
- [Google Search Console](https://search.google.com/search-console) — First measurement tool. Paid suites later.

## Boring niches that print

Agents are good at pages, matching, and reminders. Humans still buy sleep, compliance, and school-night sanity.

- After-hours services (notary, locksmith, towing) — intent + geography + phone number.
- Teacher / homeschool printables — existing marketplaces, visual discovery.
- Short fiction / KU catalogs — volume plus positioning, not "one viral novel."
- Local professional directories — one useful page beats a 200-city doorway farm.
- Resume / hiring utilities — people already have a job description in the clipboard.

If the niche needs a sales call you will not take, pick a different niche.

## Related lists

- [awesome-artificial-intelligence](https://github.com/owainlewis/awesome-artificial-intelligence) — Courses, books, papers, AI engineering. Complementary, not a competitor.
- [awesome-personal-ai-assistants](https://github.com/elyase/awesome-personal-ai-assistants) — Self-hosted assistants on your devices.
- [awesome-ai-agents](https://github.com/NipunaRanasinghe/awesome-ai-agents) — Broader agent tooling census.
- [sindresorhus/awesome](https://github.com/sindresorhus/awesome) — The index. Do not submit this list there until it has been public for 30 days and the quality bar still holds.

## Contribute

Read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a PR.

Maintained by [Athena Studios](https://github.com/athenasgarden). Related shipping work (disclosed, not ranked as "best"): [signal-desk](https://github.com/athenasgarden/signal-desk).

## License

[CC0 1.0](LICENSE) — the list text is public domain. Linked projects keep their own licenses.
