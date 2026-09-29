# Awesome Dots [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources, guides, tools and use cases for **OpenAI dots** — always-on AI agents powered by GPT-6 Astra, launched at DevDay on September 29, 2026.

_Unofficial community list. Not affiliated with or endorsed by OpenAI._

## Contents

- [What are dots?](#what-are-dots)
- [Official](#official)
- [Guides](#guides)
- [Building for dots](#building-for-dots)
- [Tools & Integrations](#tools--integrations)
- [Alternatives](#alternatives)
- [DevDay 2026 sessions](#devday-2026-sessions)
- [News & Reviews](#news--reviews)
- [Known issues](#known-issues)
- [Community](#community)
- [Contributing](#contributing)

## What are dots?

From OpenAI's launch post:

- **Always-on agents** that learn your goals and preferences and keep working in the background.
- **Powered by GPT-6 Astra**, each with its **own cloud computer and browser**.
- **4,000+ apps** through the ChatGPT plugin ecosystem.
- **Reach it anywhere**: chat or voice call in ChatGPT (desktop, web, mobile), Slack and Microsoft Teams. Texting is coming soon.
- **Proactive research**: looks for ways to help using read-only access to your connected apps.
- **You stay in control**: Custom Rules (allow / require approval / block), Activity View and auto-review. Sensitive tasks such as changing a password always stay with you.
- **Availability**: rolling out to ChatGPT Pro and Business Premium in eligible markets; Enterprise, Edu and Healthcare get an admin-enabled beta.
- **Price**: your first dot is included at no extra cost. More dots are planned but not yet available.
- **Specialist dots**: organization-managed dots with their own identity and system access, starting as enterprise pilots and coming to Microsoft Agent 365.

## Official

- [Introducing dots](https://openai.com/index/introducing-dots/) — Launch post: capabilities, safety, pricing and availability.
- [DevDay 2026 Recap](https://openai.com/index/devday-2026-recap/) — Every announcement from DevDay 2026.
- [Introducing the Agents API](https://openai.com/index/introducing-the-agents-api/) — Build cloud agents on the open-source Codex harness.
- [Introducing GPT-6.1 Sol](https://openai.com/index/introducing-gpt-6-1-sol/) — New model announced alongside dots.
- [OpenAI DevDay 2026](https://devday.openai.com/) — Event site.

## Guides

- [Dots Guide](https://dotsguide.com) — Independent guide: what dots are, pricing, setup and FAQ.
- [What are OpenAI dots?](https://dotsguide.com/what-are-dots) — How dots work and how they differ from ChatGPT.
- [Dots pricing and availability](https://dotsguide.com/pricing) — Plans, cost and what counts toward usage limits.
- [How to create your first dot](https://dotsguide.com/get-started) — Step-by-step setup, rules and approvals.
- [dotsbase](https://github.com/ylwl1997/dotsbase) — Unofficial community guide.

## Building for dots

Dots connect to apps through ChatGPT plugins, so building a plugin is how developers reach them. There is no dedicated dots API.

- [OpenAI Plugins docs](https://developers.openai.com/plugins) — Build, submit and distribute ChatGPT plugins.
- [Plugin extensions](https://developers.openai.com/plugins/build/extensions) — Sidebar homes, interactive panels and file viewers.
- [MCP events](https://developers.openai.com/plugins/build/mcp-events) — Let plugins trigger automations when something happens in a connected app.
- [openai/mcp-extensions](https://github.com/openai/mcp-extensions) — Official repo for building plugins that feel native in ChatGPT.
- [openai/plugins](https://github.com/openai/plugins) — Official OpenAI plugins repository.
- [Agents API computer use](https://developers.openai.com/api/docs/guides/agents-api/tools/computer-use) — Build your own always-on agents with the same harness as Codex.

## Tools & Integrations

- [dots-mcp](https://github.com/mergisi/dots-mcp) — MCP server to search dots resources from Claude, Cursor and other MCP clients.

## Alternatives

- [opendot](https://github.com/diggerhq/opendot) — Open-source, model-agnostic always-on personal agent.

## DevDay 2026 sessions

Breakout talks most relevant to dots. Recordings are due on openai.com. [Full list by stage](https://dotsguide.com/news/devday-2026-sessions).

- **What Will You Build With Coding Agents That Don't Quit?** — Lessons from a 1,000+ hour Codex run with goals, subagents and persistent plans.
- **What Comes After Loops? A Deep Dive Into Agentic Architectures** — From simple loops to collaborating agents.
- **Harness-as-a-Service: Building with the Agents API**
- **Build What's Next on the ChatGPT Platform with Plugins**
- **How OpenAI Puts ChatGPT to Work**

## News & Reviews

- [TechCrunch — OpenAI launches Dots, its bubbly agentic avatar](https://techcrunch.com/2026/09/29/openai-launches-dots-its-bubbly-agentic-avatar/)
- [The New Stack — Why dots matter for developers](https://thenewstack.io/openai-dots-gpt6-agents/)
- [Every — Vibe Check: OpenAI DevDay 2026](https://every.to/vibe-check/vibe-check-openai-devday-2026) — Hands-on review.
- [The Decoder — OpenAI launches always-on Dots agents](https://the-decoder.com/openai-launches-always-on-dots-agents-to-rival-metas-muse/)
- [Engadget — Dots are OpenAI's new personal agents](https://www.engadget.com/2272230/dots-are-openais-new-personal-agents-and-soon-youll-be-able-to-control-several-of-them/)
- [Axios — Meet OpenAI's dots](https://www.axios.com/2026/09/29/openai-dots-ai-assistant-devday)
- [Bloomberg — OpenAI unveils always-on AI agent Dots](https://www.bloomberg.com/news/articles/2026-09-29/openai-unveils-always-on-ai-agent-dots-new-500-paid-tier)
- [Dots Guide — DevDay 2026 recap](https://dotsguide.com/news/devday-2026-recap) — Every announcement in one page.

## Known issues

Early reports from the launch version. Open a PR if you have a fix or workaround.

- Permission prompts that fail or repeat ([Every](https://every.to/vibe-check/vibe-check-openai-devday-2026)).
- Dropped messages ([Every](https://every.to/vibe-check/vibe-check-openai-devday-2026)).
- Dot unable to connect to the in-app browser ([Every](https://every.to/vibe-check/vibe-check-openai-devday-2026)).
- Setup requires the ChatGPT desktop app or a desktop browser; mobile works only after setup ([OpenAI](https://openai.com/index/introducing-dots/)).

## Community

_Discords, subreddits and forums — PRs welcome._

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.
