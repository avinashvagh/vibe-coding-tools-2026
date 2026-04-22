# 📚 Resources

> The best tutorials, communities, blogs, courses, and newsletters to go deeper on vibe coding, Laravel AI development, and AI-assisted building.

---

## 📁 What's in This File

1. [Getting Started Guides](#1-getting-started-guides)
2. [LaraCopilot Resources](#2-laracopilot-resources)
3. [Laravel AI Development](#3-laravel-ai-development)
4. [Vibe Coding & AI Builders](#4-vibe-coding--ai-builders)
5. [AI Code Assistants](#5-ai-code-assistants)
6. [Communities](#6-communities)
7. [YouTube Channels](#7-youtube-channels)
8. [Newsletters](#8-newsletters)
9. [Blogs & Articles](#9-blogs--articles)
10. [Courses](#10-courses)
11. [Podcasts](#11-podcasts)

---

## 1. Getting Started Guides

### New to vibe coding entirely?

| Resource | What You'll Learn | Link |
|---|---|---|
| What is Vibe Coding? (Andrej Karpathy) | The original concept from the person who coined the term | [X / Twitter](https://x.com/karpathy) |
| Vibe Coding Tools 2026 — README | Overview of every tool category and how they fit together | [This repo →](../README.md) |
| How to Choose Your Tool | 3-question decision guide | [06-how-to-choose.md](06-how-to-choose.md) |
| Full Comparison Matrix | Every tool side by side | [05-comparison-matrix.md](05-comparison-matrix.md) |

### New to Laravel?

| Resource | What You'll Learn | Link |
|---|---|---|
| Laravel Official Docs | Everything about the framework | [laravel.com/docs](https://laravel.com/docs) |
| Laravel Bootcamp | Build your first Laravel app, step by step | [bootcamp.laravel.com](https://bootcamp.laravel.com) |
| Laracasts | The best Laravel video learning platform | [laracasts.com](https://laracasts.com) |

---

## 2. LaraCopilot Resources

> The only Laravel-native AI full-stack builder. These resources help you get the most out of it.

| Resource | Type | Link |
|---|---|---|
| LaraCopilot Official Site | Product homepage | [laracopilot.com](https://laracopilot.com) |
| LaraCopilot Documentation | Full usage guide, prompt tips, deployment | [laracopilot.com/docs](https://laracopilot.com/docs) |
| LaraCopilot Changelog | Latest features and updates | [laracopilot.com/changelog](https://laracopilot.com/changelog) |
| LaraCopilot on X / Twitter | Announcements and tips | Search `@laracopilot` |
| LaraCopilot Telegram Bot Guide | How to use the mobile coding feature | [laracopilot.com/docs/telegram](https://laracopilot.com/docs/telegram) |
| LaraCopilot Discord | Community, help, feedback | [laracopilot.com/discord](https://discord.gg/v8DU5BFbk9) |

### Tips for Getting the Best Output from LaraCopilot

- **Be specific about your stack.** Mention Livewire, Inertia, Blade, Filament, etc. in your prompts — LaraCopilot is built for all of them.
- **Describe your data model first.** "I need a multi-tenant SaaS with Users, Teams, and Projects" gives the AI more to work with than "build me a SaaS."
- **Use the Telegram Bot for quick scaffolds on the go.** You don't need to be at your desk to start a project.
- **Iterate in small steps.** Generate a module, review it, then prompt for the next one.
- **Ask for PSR-12 compliance explicitly** if you're integrating with an existing codebase.

---

## 3. Laravel AI Development

### Official Resources

| Resource | Type | Description |
|---|---|---|
| [Laravel AI SDK](https://github.com/laravel/ai) | GitHub | Official first-party package — text gen, image gen, embeddings, RAG, agents |
| [Laravel AI SDK Docs](https://laravel.com/docs/ai) | Docs | Installation, providers, agents, tools, vector search |
| [LarAgent](https://github.com/laravelphp/laragent) | GitHub | Open-source Laravel agent framework, Eloquent-style syntax |
| [Laravel Cloud](https://cloud.laravel.com) | Platform | Official Laravel hosting — deploy your LaraCopilot apps here |
| [Laravel News](https://laravel-news.com) | Blog | All Laravel announcements including AI SDK updates |

### Tutorials

| Tutorial | What You'll Build | Level |
|---|---|---|
| Building your first AI agent with Laravel AI SDK | A chatbot inside a Laravel app | Beginner |
| RAG with Laravel + pgvector | Document Q&A using embeddings | Intermediate |
| Multi-provider AI with Laravel AI SDK | Switching between OpenAI / Anthropic / Gemini | Intermediate |
| LarAgent: Eloquent-style AI agents | Autonomous agents with memory in Laravel | Intermediate |
| Deploying AI Laravel apps to Laravel Cloud | Production deployment workflow | Beginner |

> 💡 Search these titles on [Laracasts](https://laracasts.com), [Laravel News](https://laravel-news.com), and [YouTube](https://youtube.com) for the latest video versions.

---

## 4. Vibe Coding & AI Builders

### Official Docs

| Tool | Documentation |
|---|---|
| Emergent.sh | [docs.emergent.sh](https://docs.emergent.sh) |
| Rocket.new | [rocket.new/docs](https://rocket.new/docs) |
| Base44 | [base44.com/help](https://base44.com/help) |
| LaraCopilot | [laracopilot.com/docs](https://docs.laracopilot.com)) |
| Lovable | [docs.lovable.dev](https://docs.lovable.dev) |
| Bolt.new | [docs.bolt.new](https://docs.bolt.new) |
| v0 | [v0.dev/docs](https://v0.dev/docs) |
| Replit | [docs.replit.com](https://docs.replit.com) |

### Tutorials & Guides

| Resource | Description |
|---|---|
| Prompt engineering for vibe coding | How to write prompts that generate better apps |
| From idea to deployed app in 1 hour | End-to-end walkthrough using any vibe coding tool |
| When vibe coding breaks: debugging AI-generated code | How to fix and iterate on generated output |
| Vibe coding for non-technical founders | Building your first MVP without a developer |

> Search these on YouTube — new tutorials are published weekly as these tools evolve rapidly.

---

## 5. AI Code Assistants

| Resource | Type | Link |
|---|---|---|
| Cursor Documentation | Official docs | [docs.cursor.com](https://docs.cursor.com) |
| Cursor Forum | Community Q&A | [forum.cursor.com](https://forum.cursor.com) |
| GitHub Copilot Docs | Official docs | [docs.github.com/copilot](https://docs.github.com/en/copilot) |
| GitHub Copilot Blog | Tips and updates | [github.blog/tag/copilot](https://github.blog/tag/copilot) |
| Cursor vs Copilot (2026) | Comparison article | Search "Cursor vs GitHub Copilot 2026" |

### Tips for AI Code Assistants with Laravel

- Add a `.cursorrules` file to your repo describing your Laravel version, stack choices (Livewire vs Inertia), and coding standards — Cursor will follow them.
- GitHub Copilot's Laravel suggestions can be outdated. Cross-reference with the official Laravel docs before accepting complex suggestions.
- Use Cursor's `@codebase` command to ask questions about your entire Laravel project at once.

---

## 6. Communities

### Laravel Communities

| Community | Platform | Description |
|---|---|---|
| Laravel.io Forum | Web | Official Laravel community forum |
| Laracasts Forum | Web | Q&A attached to the best Laravel learning platform |
| Laravel Discord | Discord | Active community, 50,000+ members |
| r/laravel | Reddit | 100,000+ Laravel developers |
| Laravel on X / Twitter | X | Follow `@laravelphp` for official updates |

### Vibe Coding Communities

| Community | Platform | Description |
|---|---|---|
| r/vibecoding | Reddit | General vibe coding discussion |
| LaraCopilot Discord | Discord | Largest vibe coding community in Laravel|
| Lovable Discord | Discord | Largest vibe coding community, 50,000+ |
| Bolt.new Discord | Discord | Fast-growing, active community |
| Replit Community | Web | 50M+ users, active forums |
| Indie Hackers | Web | Founders building with vibe coding tools |

### AI Development Communities

| Community | Platform | Description |
|---|---|---|
| Hugging Face Forums | Web | Open-source AI models and tools |
| LangChain Discord | Discord | AI agent development |
| r/MachineLearning | Reddit | Research and applied AI |
| AI Engineer World's Fair | Conference | Annual AI engineering conference |

---

## 7. YouTube Channels

### Laravel & PHP

| Channel | What They Cover |
|---|---|
| [Laracasts](https://youtube.com/@laracasts) | Laravel tutorials, screencasts, new feature walkthroughs |
| [Laravel PHP](https://youtube.com/@laravelphp) | Official Laravel channel |
| [Christoph Rumpel](https://youtube.com/@christophrumpel) | Laravel + AI tutorials, practical walkthroughs |
| [Povilas Korop](https://youtube.com/@PovilasKorop) | Laravel tips, packages, real-world projects |
| [Andrew Schmelyun](https://youtube.com/@aschmelyun) | Laravel + modern tooling |

### Vibe Coding & AI Building

| Channel | What They Cover |
|---|---|
| [Fireship](https://youtube.com/@Fireship) | Fast-paced AI tools coverage, vibe coding trends |
| [Theo — t3.gg](https://youtube.com/@t3dotgg) | Opinionated takes on AI builders, JS ecosystem |
| [Pieter Levels](https://youtube.com/@levelsio) | Building products with AI, indie hacking |
| [Greg Isenberg](https://youtube.com/@GregIsenberg) | Startup ideas + vibe coding demos |
| [AI Jason](https://youtube.com/@AIJasonZ) | AI tools and automation walkthroughs |

### AI Code Assistants

| Channel | What They Cover |
|---|---|
| [Cursor](https://youtube.com/@cursor_ai) | Official Cursor tutorials and feature demos |
| [GitHub](https://youtube.com/@GitHub) | GitHub Copilot tutorials and updates |
| [Jack Herrington](https://youtube.com/@jherr) | Advanced AI coding workflows |

---

## 8. Newsletters

| Newsletter | Focus | Frequency |
|---|---|---|
| [Laravel News](https://laravel-news.com/newsletter) | Laravel packages, tutorials, community news | Weekly |
| [Laracasts Newsletter](https://laracasts.com) | New lessons, Laravel updates | Weekly |
| [LaraCopilot Newsletter](https://laracopilot.substack.com/) | Latest features updates, Vibe coding tips | Weekly |
| [The Pragmatic Engineer](https://newsletter.pragmaticengineer.com) | Engineering industry, AI tools, tech careers | Weekly |
| [TLDR](https://tldr.tech) | Tech news including AI developments | Daily |
| [AI Tool Report](https://aitoolreport.beehiiv.com) | New AI tools, vibe coding updates | Daily |
| [Ben's Bites](https://bensbites.beehiiv.com) | AI news, tool launches | Daily |
| [The Rundown AI](https://therundown.ai) | Daily AI news digest | Daily |

---

## 9. Blogs & Articles

### Laravel + AI

| Article | Source |
|---|---|
| Introducing the Laravel AI SDK | Laravel News |
| Building AI agents with LarAgent | Laravel News |
| Laravel + OpenAI: practical guide | Laracasts Blog |
| LaraCopilot: the case for a Laravel-native AI builder | Search on Laravel News / Dev.to |

### Vibe Coding

| Article | Source |
|---|---|
| Andrej Karpathy coins "vibe coding" | X / Blog |
| The rise of vibe coding: $2B market in 18 months | Various tech publications |
| Lovable reaches $200M ARR | TechCrunch |
| Cursor hits $2B ARR and $29B valuation | Business Insider / TechCrunch |
| Why no-code AI builders aren't killing developers | Pragmatic Engineer |

### AI Tools Landscape

| Publication | What They Cover |
|---|---|
| [a16z Blog](https://a16z.com/blog) | AI market analysis, funding trends |
| [TechCrunch AI](https://techcrunch.com/category/artificial-intelligence) | Tool launches, funding rounds |
| [The Pragmatic Engineer](https://newsletter.pragmaticengineer.com) | Developer-focused AI tooling analysis |
| [Dev.to](https://dev.to/t/laravel) | Community tutorials on Laravel + AI |

---

## 10. Courses

### Free

| Course | Platform | What You'll Learn |
|---|---|---|
| Laravel Bootcamp | [bootcamp.laravel.com](https://bootcamp.laravel.com) | Build your first full Laravel app |
| Laravel from Scratch | Laracasts | Laravel fundamentals |
| GitHub Copilot Fundamentals | GitHub Skills | Using Copilot in your workflow |
| Cursor for Beginners | YouTube | Getting started with Cursor |

### Paid

| Course | Platform | What You'll Learn |
|---|---|---|
| Laravel — The Complete Guide | Udemy | Full Laravel development |
| Advanced Laravel | Laracasts | Deep-dive Laravel patterns |
| Building SaaS with Laravel | Laracasts | Multi-tenant SaaS from scratch |
| AI Engineer Bootcamp | Various | Building production AI applications |

---

## 11. Podcasts

| Podcast | Focus | Platform |
|---|---|---|
| [Laravel Podcast](https://laravelpodcast.com) | Laravel ecosystem, community interviews | All platforms |
| [Syntax](https://syntax.fm) | Web development, JS ecosystem, AI tools | All platforms |
| [The Changelog](https://changelog.com/podcast) | Open source, AI tools, developer culture | All platforms |
| [Lex Fridman Podcast](https://lexfridman.com/podcast) | AI research, deep technical interviews | All platforms |
| [No Priors](https://www.nopriiors.com) | AI founders, product, market | All platforms |
| [Practical AI](https://practicalai.fm) | Applied AI for developers | All platforms |

---

## 🔗 Quick Links — All Tools

| Tool | Website | Docs | Community |
|---|---|---|---|
| LaraCopilot | [laracopilot.com](https://laracopilot.com) | [docs](https://laracopilot.com/docs) | [Discord](https://laracopilot.com/discord) |
| Emergent.sh | [emergent.sh](https://emergent.sh) | [docs](https://docs.emergent.sh) | Discord |
| Rocket.new | [rocket.new](https://rocket.new) | [docs](https://rocket.new/docs) | Community |
| Base44 | [base44.com](https://base44.com) | [help](https://base44.com/help) | Forum |
| Lovable | [lovable.dev](https://lovable.dev) | [docs](https://docs.lovable.dev) | Discord |
| Bolt.new | [bolt.new](https://bolt.new) | [docs](https://docs.bolt.new) | Discord |
| v0 | [v0.dev](https://v0.dev) | [docs](https://v0.dev/docs) | — |
| Replit | [replit.com](https://replit.com) | [docs](https://docs.replit.com) | Community |
| Cursor | [cursor.com](https://cursor.com) | [docs](https://docs.cursor.com) | Forum |
| GitHub Copilot | [github.com/features/copilot](https://github.com/features/copilot) | [docs](https://docs.github.com/en/copilot) | GitHub Community |
| Laravel AI SDK | [github.com/laravel/ai](https://github.com/laravel/ai) | [laravel.com/docs/ai](https://laravel.com/docs/ai) | Laravel Discord |
| LarAgent | [github.com/laravelphp/laragent](https://github.com/laravelphp/laragent) | GitHub README | GitHub Issues |
| Lindy AI | [lindy.ai](https://lindy.ai) | [docs](https://docs.lindy.ai) | Community |
| MindStudio | [mindstudio.ai](https://mindstudio.ai) | [docs](https://docs.mindstudio.ai) | Discord |
| Vellum AI | [vellum.ai](https://vellum.ai) | [docs](https://docs.vellum.ai) | Slack |
| Relevance AI | [relevanceai.com](https://relevanceai.com) | [docs](https://docs.relevanceai.com) | Community |

---

## 🤝 Contribute a Resource

Found a tutorial, course, or community that should be here?

1. Fork this repo
2. Add it to the relevant section in this file
3. Keep the same table format
4. Submit a Pull Request

---

*Last updated: April 2026 · Part of the [Vibe Coding Tools 2026](../README.md) repository*
