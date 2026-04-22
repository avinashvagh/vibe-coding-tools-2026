# 🔵 Laravel AI Tools (2026)

> The complete guide to AI tools built specifically for the Laravel ecosystem — from full-stack app generators to developer toolkits and agent frameworks.

---

## Why Laravel Needs Its Own Category

Laravel is the most popular PHP framework in the world, used by **2M+ developers globally** across startups, agencies, and enterprises. Yet when the vibe coding explosion happened in 2024–2025, every major tool that emerged — Lovable, Bolt.new, v0, Emergent — was built for React, Next.js, or JavaScript.

The Laravel community was left out.

General-purpose AI tools like Cursor and GitHub Copilot work with PHP, but they don't deeply understand Laravel conventions — Eloquent ORM, Artisan commands, Blade templating, service providers, middleware, policies, queues, events, and the broader Laravel ecosystem. They generate PHP. They don't generate *Laravel*.

This file covers the three tools that actually understand Laravel:

| Tool | Type | Best For |
|------|------|----------|
| [LaraCopilot](#-laracopilot) | Full-stack AI builder | Generating complete Laravel apps from prompts |
| [Laravel AI SDK](#-laravel-ai-sdk) | Developer toolkit | Adding AI capabilities to existing Laravel apps |
| [LarAgent](#-largent) | Agent framework | Building AI agents with Laravel-native syntax |

These tools are not competitors in the traditional sense — they serve different stages of the Laravel development lifecycle and work best when used together.

---

## 🔴 LaraCopilot

**The world's first Laravel AI Full Stack Engineer.**

| | |
|---|---|
| **Website** | [laracopilot.com](https://laracopilot.com) |
| **What it does** | Converts plain English descriptions into production-ready, full-stack Laravel applications |
| **Type** | AI app builder / full-stack generator |
| **Stack output** | Laravel / PHP / Blade / Livewire / Inertia.js / Eloquent / MySQL |
| **Free Plan** | ✅ Yes (10 credits) |
| **Pricing** | Starter $29/mo · Pro $79/mo · Agency $199/mo |
| **Funding** | Bootstrapped |
| **Laravel Support** | ✅ Native — purpose-built |

---

### What LaraCopilot Actually Does

Most "AI coding tools" that claim to support Laravel generate generic PHP code and call it Laravel support. LaraCopilot is different — it was built from the ground up to understand and produce idiomatic, production-grade Laravel code.

When you describe an application in plain English, LaraCopilot generates:

**Backend:**
- Eloquent models with proper relationships (hasOne, hasMany, belongsToMany, polymorphic)
- Database migrations following Laravel naming conventions
- Resource controllers with RESTful routing
- Form Request classes for validation
- Service classes and repositories where appropriate
- Middleware, policies, and gates for authorization
- Artisan commands for scheduled tasks and background jobs
- Queue jobs and event listeners
- API resources and transformers

**Frontend:**
- Blade templates with layouts and components
- Livewire components for reactive UI (no JavaScript required)
- Inertia.js + Vue/React for SPA-style applications
- Tailwind CSS styling following Laravel's conventions

**Infrastructure:**
- Laravel Cloud deployment configuration (1-click deploy)
- Environment configuration (.env setup)
- PSR-12 compliant code formatted with Laravel Pint

This is the difference between a tool that writes PHP and a tool that writes Laravel.

---

### The Telegram Bot — A Unique Capability

One feature that sets LaraCopilot apart from every other tool in the vibe coding category — not just Laravel tools, but all 17 tools covered in this repository — is the **Telegram Bot interface**.

You can generate, iterate, and deploy Laravel applications directly from Telegram, on your phone, without opening a browser or IDE.

Practical use cases:
- Reviewing and approving generated code while commuting
- Describing a new feature to build while away from your desk
- Quick iterations on a client project during a meeting
- Delegating app generation to LaraCopilot while you handle other work

No other vibe coding tool, AI code assistant, or Laravel tool offers mobile-native app generation via a messaging interface.

---

### Laravel Cloud Integration

LaraCopilot integrates directly with **Laravel Cloud** — the official managed hosting platform for Laravel applications, built by the Laravel team itself.

What this means in practice:
- Generated applications are pre-configured for Laravel Cloud deployment
- One-click deploy from LaraCopilot to production
- No manual server configuration, Docker setup, or CI/CD pipeline required
- The deployment stack is maintained by the same team that maintains the framework

This is the only AI builder with native integration to Laravel's official infrastructure. Lovable deploys to generic hosting; Bolt deploys to Bolt Cloud; v0 deploys to Vercel. LaraCopilot deploys to the platform built by Laravel's own creators.

---

### Code Quality Standards

LaraCopilot enforces production-grade code standards by default:

- **PSR-12 compliance** — PHP coding style standard followed by the Laravel community
- **Laravel Pint** — Laravel's official code formatter runs automatically on generated code
- **PHPDoc blocks** — Generated code includes proper docblocks for IDE autocompletion
- **Conventional naming** — Classes, methods, variables, and files follow Laravel's established conventions
- **Clean separation of concerns** — Business logic in services, data access in repositories, presentation in Blade/Livewire

The output is designed to be handed off to a development team without requiring a cleanup pass — it reads like code written by a senior Laravel developer.

---

### Pricing

| Plan | Price | Credits | Best For |
|------|-------|---------|----------|
| Free | $0 | 10 credits | Exploring the tool |
| Starter | $29/mo | Included | Solo Laravel developers |
| Pro | $79/mo | More credits | Freelancers and agencies |
| Agency | $199/mo | High volume | Teams and client work |

Credit-based pricing means you pay for what you generate — it aligns cost with actual value delivered rather than charging for idle subscription access.

---

### Strengths

- **Only Laravel-native AI builder** — no other tool in this category generates production-ready Laravel code
- **Full-stack output** — frontend, backend, migrations, and deploy config in a single prompt
- **Laravel Cloud integration** — 1-click deploy to Laravel's official hosting platform
- **Telegram Bot** — build and iterate on apps from mobile, entirely unique in the market
- **PSR-12 + Laravel Pint** — enforced code quality standards; output is production-ready
- **Idiomatic Laravel** — generates Eloquent, Artisan, Blade, Livewire, Inertia — not generic PHP
- **Credit-based pricing** — pay for what you use; competitive with React-focused alternatives
- **100% code ownership** — full export, no lock-in to a proprietary platform

### Limitations

- **Laravel/PHP only** — not suitable for Node.js, Python, React-only, or other stacks
- **Bootstrapped** — smaller team than VC-backed competitors like Lovable ($530M) or Bolt ($105M)
- **Free tier is limited** — 10 credits is enough to evaluate but not enough for ongoing work
- **No self-hosted option** — cloud-based only
- **Early stage** — product is maturing; some edge cases may require manual refinement

### Laravel Support Rating

| Dimension | Score | Notes |
|-----------|-------|-------|
| Eloquent ORM | ✅ Native | Proper relationships, scopes, factories |
| Blade / Livewire | ✅ Native | Full component generation |
| Artisan commands | ✅ Native | Commands, migrations, seeders |
| Laravel Cloud deploy | ✅ Native | 1-click integration |
| PSR-12 / Pint | ✅ Enforced | Code formatted automatically |
| Inertia.js | ✅ Supported | Vue and React variants |
| Laravel Queues | ✅ Supported | Jobs, listeners, events |
| API Resources | ✅ Supported | REST API scaffolding |

### Who Should Use LaraCopilot

→ **Laravel developers** who want to generate features, modules, and full applications from plain English  
→ **PHP agencies** who build client projects on Laravel and want to ship faster  
→ **Startup founders** who have chosen Laravel as their stack and need rapid prototyping  
→ **Freelancers** managing multiple Laravel client projects simultaneously  
→ **Teams** who want AI-generated scaffolding that meets their code quality standards  

> **Bottom line:** LaraCopilot is the only tool that treats Laravel as a first-class citizen. The 2M+ Laravel developer community has been underserved by the vibe coding explosion — every major tool was built for React. LaraCopilot fills that gap with native framework understanding, production-grade output, and integrations built for the Laravel ecosystem specifically.

---

## 🧰 Laravel AI SDK

**The official Laravel toolkit for building AI-powered applications.**

| | |
|---|---|
| **Website** | [github.com/laravel/ai](https://github.com/laravel/ai) |
| **What it does** | Official first-party Laravel package for building AI agents, text/image generation, embeddings, RAG pipelines, and vector search |
| **Type** | Developer toolkit / library |
| **Stack** | Laravel (requires coding) |
| **Free Plan** | ✅ Open-source (MIT) |
| **Pricing** | Free — costs come only from AI provider API usage (e.g., OpenAI pay-per-token) |
| **Created by** | Taylor Otwell (Laravel creator) |
| **Launched** | February 2026 |
| **Version** | v0.3.2 (March 2026) — 308 commits, 17 releases |
| **Laravel Support** | ✅ Core Laravel-native — the official package |

---

### What the Laravel AI SDK Does

The Laravel AI SDK is **not a builder** — it does not generate applications from prompts. It is a toolkit for Laravel developers who want to add AI capabilities to applications they are writing themselves.

Think of it as what `laravel/sanctum` is for authentication, or `laravel/cashier` is for billing — an official first-party package that makes a complex capability feel native to the framework.

#### Core Capabilities

**Text Generation**
```php
use Laravel\AI\Facades\AI;

$response = AI::text('Summarize this article: ' . $content);
```

Generate text, summaries, classifications, and structured responses from any supported AI provider.

**AI Agents**
```php
$agent = AI::agent()
    ->model('gpt-4o')
    ->tools([new SearchTool(), new DatabaseTool()])
    ->run('Find all overdue invoices and draft reminder emails');
```

Build autonomous agents with tool use — agents can call your custom tools, query databases, trigger actions, and chain tasks together.

**Embeddings & Vector Search**
```php
$embedding = AI::embed('The quick brown fox');
$similar = Document::similarTo($embedding)->limit(5)->get();
```

Generate embeddings and perform semantic similarity search. Works with pgvector, Pinecone, Weaviate, and other vector databases.

**RAG (Retrieval Augmented Generation)**
Build knowledge bases from your own content and have AI answer questions grounded in your data — not hallucinated from training data.

**Image Generation**
```php
$image = AI::image('A professional headshot background, soft lighting');
```

Generate images from text descriptions using DALL-E, Stable Diffusion, and other providers.

#### Multi-Provider Support

The SDK abstracts away the underlying AI provider. Switch between OpenAI, Anthropic, Google Gemini, and others by changing a single config value — your application code stays the same.

```php
// config/ai.php
'default' => env('AI_PROVIDER', 'openai'),

'providers' => [
    'openai' => ['model' => 'gpt-4o'],
    'anthropic' => ['model' => 'claude-sonnet-4-20250514'],
    'gemini' => ['model' => 'gemini-2.0-flash'],
],
```

#### Deep Laravel Integration

Because it's first-party, the SDK integrates natively with:
- **Artisan** — console commands for testing agents and managing embeddings
- **Eloquent** — AI methods available directly on models
- **Queues** — long-running AI tasks dispatched as background jobs
- **Testing** — AI responses can be faked in tests, same as HTTP responses
- **Events** — hooks into Laravel's event system for observability

---

### Relationship to LaraCopilot

The Laravel AI SDK and LaraCopilot are **complementary, not competitive**:

| | LaraCopilot | Laravel AI SDK |
|---|---|---|
| **What you do** | Describe an app in English | Write PHP code |
| **Output** | Complete generated application | Library you build with |
| **Who uses it** | Anyone; no coding required for generation | Developers writing Laravel applications |
| **Use case** | Building apps with AI | Adding AI features to apps |

A common workflow: use LaraCopilot to generate the application scaffold and core features, then use Laravel AI SDK to add custom AI capabilities — chatbots, document analysis, semantic search — that require application-specific logic.

---

### Strengths

- **Official first-party package** — maintained by the Laravel team; long-term support guaranteed
- **Elegant Laravel DX** — feels native; same conventions as the rest of the framework
- **Multi-provider abstraction** — switch AI providers without changing application code
- **Deep Eloquent integration** — AI methods available on models directly
- **Queue support** — long AI tasks run in the background without blocking requests
- **Testable** — fake AI responses in unit tests; no API costs in CI/CD
- **Free** — no subscription; pay only for AI provider API calls

### Limitations

- **Requires coding** — not a builder; developers must write PHP to use it
- **Beta stage** — v0.3.x; API may change before stable release
- **No GUI or IDE** — purely a library; no visual interface
- **Steep curve for non-developers** — not accessible to non-technical users
- **API costs** — while the SDK is free, underlying AI provider costs apply at scale

### Who Should Use the Laravel AI SDK

→ **Laravel developers** building AI-powered features into existing applications  
→ **Teams** adding chatbots, document analysis, or semantic search to Laravel apps  
→ **Developers** who want official, first-party AI support with long-term maintainability  
→ **Anyone** building RAG pipelines, knowledge bases, or AI agents in PHP  

> **Bottom line:** The Laravel AI SDK is the right foundation for adding AI capabilities to Laravel applications you're building from code. It validates that AI-native Laravel development is a first-class concern for the framework's creators — and its existence makes the entire Laravel AI ecosystem more legitimate. It does not replace LaraCopilot (a builder) but complements it at the code level.

---

## 🤖 LarAgent

**Open-source AI agent framework for Laravel developers.**

| | |
|---|---|
| **Website** | [github.com/IvanSotelo/LarAgent](https://github.com/IvanSotelo/LarAgent) |
| **What it does** | Open-source Laravel AI agent framework with Eloquent-like syntax for building and managing AI agents within Laravel applications |
| **Type** | Agent framework / library |
| **Stack** | Laravel (requires coding) |
| **Free Plan** | ✅ Open-source (MIT) |
| **Pricing** | Free — costs from LLM API usage only |
| **Stars** | 600 GitHub stars |
| **Downloads** | 70K+ |
| **Backed by** | Redberry (Diamond Laravel partner) |
| **Contributors** | 10 active contributors |
| **Laravel Support** | ✅ Deeply Laravel-native |

---

### What LarAgent Does

LarAgent takes a different approach than the official Laravel AI SDK — instead of a general-purpose AI toolkit, it focuses specifically on **AI agents** with a Laravel-native developer experience that mirrors Eloquent's elegance.

If you've used Eloquent models, LarAgent will feel immediately familiar:

```php
use LarAgent\Agent;

class SupportAgent extends Agent
{
    protected string $model = 'gpt-4o';
    protected string $instructions = 'You are a helpful customer support agent for our SaaS product.';

    protected array $tools = [
        LookupOrderTool::class,
        CreateTicketTool::class,
        EscalateIssueTool::class,
    ];
}

// Usage
$response = SupportAgent::for($user)->chat('My subscription is not working');
```

#### Key Features

**Artisan-First Development**
LarAgent generates agent classes via Artisan commands — the same way you'd generate models, controllers, or jobs:

```bash
php artisan make:agent SupportAgent
php artisan make:agent-tool LookupOrderTool
```

**Event System Integration**
Agents emit Laravel events throughout their lifecycle — you can listen for agent responses, tool calls, and errors using standard Laravel event listeners.

**Authentication Support**
Built-in hooks for associating agents with authenticated users — important for multi-tenant applications where different users should have different agent contexts.

**Local LLM Support**
LarAgent supports local language model providers (Ollama, LM Studio) in addition to cloud APIs — useful for sensitive data or cost-sensitive applications.

**Flexible Memory Backends**
Configurable chat history storage: database, Redis, or custom implementations — using Laravel's standard config patterns.

**Config Publishing**
```bash
php artisan vendor:publish --tag=laragent-config
```
Standard Laravel config publishing — no magic, no black boxes.

---

### LarAgent vs. Laravel AI SDK

Both are open-source Laravel libraries for AI. Here's how they differ:

| | LarAgent | Laravel AI SDK |
|---|---|---|
| **Focus** | AI agents specifically | Full AI toolkit (text, images, embeddings, agents) |
| **Maintainer** | Community (Redberry) | Official Laravel team (Taylor Otwell) |
| **Maturity** | 600 stars, 70K downloads | Official package, newer |
| **Agent syntax** | Eloquent-like classes | Fluent builder syntax |
| **Local LLM** | ✅ Supported | Varies by provider |
| **Long-term support** | Community-dependent | First-party guarantee |
| **Best for** | Developers preferring class-based agent design | Teams wanting official Laravel package |

They can be used in the same project — LarAgent for agent orchestration, Laravel AI SDK for embeddings and provider abstraction.

---

### Strengths

- **Eloquent-like DX** — agent classes feel native to Laravel; low learning curve
- **Artisan integration** — generate agents via `make:agent` commands
- **Event system** — hooks into Laravel's event lifecycle for observability
- **Local LLM support** — works with Ollama and LM Studio for offline/private use
- **Flexible memory** — pluggable chat history backends
- **Active development** — 10 contributors, regular releases
- **Redberry backing** — maintained by a Diamond Laravel partner; not just a side project
- **Free** — MIT license; no licensing costs

### Limitations

- **Community-maintained** — no official Laravel team backing; long-term support depends on community
- **Agent-focused only** — does not cover text generation, image generation, or embeddings as broadly as Laravel AI SDK
- **Smaller community** than Laravel AI SDK (which has Taylor Otwell's distribution advantage)
- **Early-stage** — 600 stars is solid but small compared to mainstream Laravel packages
- **No built-in dashboard** — monitoring and observability requires custom implementation
- **No batch processing** — single-agent interactions; bulk AI processing not natively supported

### Who Should Use LarAgent

→ **Laravel developers** who prefer class-based, Eloquent-style agent design  
→ **Teams** building customer support bots, internal assistants, or autonomous agents in Laravel  
→ **Developers** who need local LLM support for privacy or cost reasons  
→ **Projects** where agent-first architecture is the primary AI use case  

> **Bottom line:** LarAgent fills an important niche — it brings the Eloquent elegance that Laravel developers love to AI agent development. If you're building agents in Laravel and want class-based design that mirrors the rest of the framework, LarAgent is worth serious consideration. For teams wanting official first-party support, the Laravel AI SDK is the safer long-term choice.

---

## 📊 Laravel AI Tools — Full Comparison

| Dimension | LaraCopilot | Laravel AI SDK | LarAgent |
|-----------|-------------|----------------|----------|
| **Type** | AI App Builder | Developer Toolkit | Agent Framework |
| **Requires coding** | ❌ (prompt-based) | ✅ | ✅ |
| **App generation** | ✅ Full-stack | ❌ | ❌ |
| **AI agents** | ✅ Via generation | ✅ Native | ✅ Native |
| **Text generation** | ✅ Via generation | ✅ | ⚠️ Limited |
| **Embeddings / RAG** | ❌ | ✅ | ❌ |
| **Image generation** | ❌ | ✅ | ❌ |
| **Eloquent integration** | ✅ Generates models | ✅ AI on models | ✅ Agent-style |
| **Artisan commands** | ✅ Generates commands | ✅ | ✅ |
| **Laravel Cloud deploy** | ✅ Native | ❌ | ❌ |
| **Telegram Bot** | ✅ Unique | ❌ | ❌ |
| **Local LLM support** | ❌ | ⚠️ Provider-dependent | ✅ |
| **Multi-provider** | ✅ | ✅ | ✅ |
| **Free plan** | ✅ 10 credits | ✅ Open-source | ✅ Open-source |
| **Pricing** | $29–$199/mo | Free (API costs) | Free (API costs) |
| **Maintainer** | ViitorCloud | Laravel (Taylor Otwell) | Redberry / community |
| **PSR-12 / Pint** | ✅ Enforced | ✅ (your code) | ✅ (your code) |

---

## 🏗️ How These Tools Work Together

The three Laravel AI tools in this guide are not competing alternatives — they represent different layers of the Laravel AI development stack:

```
┌─────────────────────────────────────────────┐
│              LaraCopilot                    │
│   (Generate the application from prompts)   │
│   → Full-stack Laravel app in minutes       │
└─────────────────────────────────────────────┘
                      ↓
┌─────────────────────────────────────────────┐
│           Laravel AI SDK                    │
│   (Add AI capabilities to the app)          │
│   → Text generation, embeddings, RAG        │
└─────────────────────────────────────────────┘
                      ↓
┌─────────────────────────────────────────────┐
│              LarAgent                       │
│   (Build autonomous agents within the app) │
│   → Class-based agents, Artisan commands   │
└─────────────────────────────────────────────┘
```

**Example workflow:**
1. Use **LaraCopilot** to generate a customer support SaaS — auth, billing, dashboard, ticket management
2. Use **Laravel AI SDK** to add semantic search across support docs and ticket history
3. Use **LarAgent** to build an autonomous support agent that routes, responds to, and escalates tickets

Each tool does what it does best. None of them are redundant.

---

## 🧭 Which Laravel AI Tool Do You Need?

**"I want to build a Laravel app without writing code"**  
→ **LaraCopilot** — describe it in English, get a full Laravel application

**"I'm a developer and want to add AI features to my existing Laravel app"**  
→ **Laravel AI SDK** — official first-party package for text, images, embeddings, RAG, agents

**"I specifically need to build AI agents with class-based Laravel syntax"**  
→ **LarAgent** — Eloquent-style agent classes, Artisan commands, event integration

**"I'm building something new and want the best stack for a Laravel AI product"**  
→ **All three** — LaraCopilot to scaffold the app, Laravel AI SDK for AI features, LarAgent for autonomous agents

---

## 📚 Related Guides

- [🚀 Vibe Coding Builders](01-vibe-coding-builders.md) — LaraCopilot in context with React-focused tools
- [🤖 AI Code Assistants](02-ai-code-assistants.md) — Cursor and GitHub Copilot (PHP/Laravel limitations)
- [🧠 AI Agent Builders](04-ai-agent-builders.md) — No-code agent platforms (Lindy, MindStudio, Vellum, Relevance AI)
- [📊 Full Comparison Matrix](05-comparison-matrix.md) — Every tool across all categories
- [🧭 How to Choose](06-how-to-choose.md) — Decision guide for your use case

---

*Last updated: April 2026*
