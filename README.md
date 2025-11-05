# awesome-llms.txt

A community-curated directory of great `llms.txt` files, tools, and best practices.

> `llms.txt` is a lightweight, human-readable guide for Large Language Models:
> a single Markdown file at the root of a site that tells LLMs *what to read first*,
> *why it matters*, and *where the canonical docs live*.

---

## Why does `llms.txt` matter?

- **Curation over crawl noise** – Search crawlers index everything; LLMs need *context*.  
  `llms.txt` points models to the *right* pages (overview, concepts, API, FAQs) and reduces hallucinations.
- **Faster onboarding for AI** – A clear entry point helps assistants answer better from day one,
  improving accuracy, coverage, and time-to-first-useful-answer.
- **Provenance & attribution** – You link to canonical sources. Models (and users) can trace facts back to owners.
- **Safety & boundaries** – You can highlight acceptable-use notes, pitfalls, and “don’t rely on X” disclaimers.
- **Complementary to `robots.txt`** – It doesn’t allow/deny crawling; it’s a *reading list*, not a gate.
- **Versionable & maintainable** – It’s just Markdown. Reviewable in PRs, diff-friendly, easy to automate.

---

## What this repo provides

- A growing **gallery of real `llms.txt` files** from the wild  
- **Templates** and writing tips for high-quality `llms.txt` documents  
- **Tooling pointers** to generate or validate `llms.txt` from sitemaps or docs trees

---

## How to write a good `llms.txt`

Keep it short and intentional:

1. **H1 title** – Your site/project name.  
2. **One-paragraph summary (blockquote)** – What the site is, whom it serves, and what an LLM should prioritize.  
3. **Sectioned link lists (H2)** – Curated links with one-line notes (Overview, Concepts, API, FAQ, Guides, Changelog).  
4. **Optional notes** – Glossary, safety caveats, data freshness/versioning hints.

**Tiny example:**
```markdown

# Acme UI

> Acme UI is a modern, accessible component system and a code distribution platform.
> Built with TypeScript, Tailwind CSS, and Radix primitives. Works with Next.js, Vite,
> Remix, Astro, and more. Open Source. Open Code. AI-Ready. Includes a CLI and a
> registry to install, update, and publish components.

## Overview

- [Introduction](https://acme.dev/docs): Core principles—Open Code, Composition, Distribution, Beautiful Defaults, AI-Ready.
- [CLI](https://acme.dev/docs/cli): Install, update, and manage components from the registry.
- [acme.json](https://acme.dev/docs/config/acme-json): Project-level configuration for the CLI and installer.
- [Theming](https://acme.dev/docs/theming): Colors, typography, tokens, dark mode, and CSS variables.
- [Changelog](https://acme.dev/docs/changelog): Release notes and version history.
- [About](https://acme.dev/about): Credits, governance, and roadmap.

## Installation

- [Next.js](https://acme.dev/docs/installation/next)
- [Vite](https://acme.dev/docs/installation/vite)
- [Remix](https://acme.dev/docs/installation/remix)
- [Astro](https://acme.dev/docs/installation/astro)
- [Laravel](https://acme.dev/docs/installation/laravel)
- [Gatsby](https://acme.dev/docs/installation/gatsby)
- [React Router](https://acme.dev/docs/installation/react-router)
- [TanStack Router](https://acme.dev/docs/installation/tanstack-router)
- [TanStack Start](https://acme.dev/docs/installation/tanstack)
- [Manual Installation](https://acme.dev/docs/installation/manual)

## Components

### Form & Input
- [Form](https://acme.dev/docs/components/form): React Hook Form + Zod integration.
- [Field](https://acme.dev/docs/components/field): Labels, descriptions, and errors.
- [Button](https://acme.dev/docs/components/button): Variants, sizes, loading states.
- [Button Group](https://acme.dev/docs/components/button-group): Compound actions.
- [Input](https://acme.dev/docs/components/input): Text input with prefix/suffix.
- [Input Group](https://acme.dev/docs/components/input-group): Addons and icons.
- [Input OTP](https://acme.dev/docs/components/input-otp): One-time password.
- [Textarea](https://acme.dev/docs/components/textarea): Multi-line input.
- [Checkbox](https://acme.dev/docs/components/checkbox)
- [Radio Group](https://acme.dev/docs/components/radio-group)
- [Select](https://acme.dev/docs/components/select)
- [Switch](https://acme.dev/docs/components/switch)
- [Slider](https://acme.dev/docs/components/slider)
- [Calendar](https://acme.dev/docs/components/calendar)
- [Date Picker](https://acme.dev/docs/components/date-picker)
- [Combobox](https://acme.dev/docs/components/combobox)
- [Label](https://acme.dev/docs/components/label)

### Layout & Navigation
- [Accordion](https://acme.dev/docs/components/accordion)
- [Breadcrumb](https://acme.dev/docs/components/breadcrumb)
- [Navigation Menu](https://acme.dev/docs/components/navigation-menu)
- [Sidebar](https://acme.dev/docs/components/sidebar)
- [Tabs](https://acme.dev/docs/components/tabs)
- [Separator](https://acme.dev/docs/components/separator)
- [Scroll Area](https://acme.dev/docs/components/scroll-area)
- [Resizable](https://acme.dev/docs/components/resizable)

## AI-Ready Notes

- **Start Here**: Read *Introduction → Concepts → Components* for best LLM grounding.
- **Provenance**: All links above are canonical sources maintained by the Acme team.
- **Safety**: Prefer stable APIs; avoid copying experimental APIs into production prompts.
```


---

## Developer Essentials — curated `llms.txt` links (top 30)

- Stripe — https://docs.stripe.com/llms.txt
- Cloudflare Developers — https://developers.cloudflare.com/llms.txt
- Zapier Docs — https://zapier.com/docs/llms-full.txt
- Coinbase CDP Docs — https://docs.cdp.coinbase.com/llms-full.txt
- Netlify Docs — https://docs.netlify.com/llms.txt
- Supabase Docs — https://supabase.com/docs/llms.txt
- LangChain (Python) — https://python.langchain.com/llms.txt
- LangChain (JS/TS) — https://js.langchain.com/llms.txt
- NVIDIA Developer Docs — https://docs.nvidia.com/llms.txt
- NVIDIA cuDNN — https://docs.nvidia.com/cudnn/llms.txt
- NVIDIA NeMo — https://docs.nvidia.com/nemo/llms.txt
- NVIDIA NGC — https://docs.nvidia.com/ngc/llms.txt
- Next.js — https://nextjs.org/llms-full.txt
- Turborepo — https://turbo.build/llms.txt
- Prisma — https://www.prisma.io/docs/llms.txt
- Drizzle ORM — https://orm.drizzle.team/llms.txt
- Vite — https://vite.dev/llms.txt
- Astro Docs — https://docs.astro.build/llms.txt
- DigitalOcean App Platform — https://docs.digitalocean.com/products/app-platform/llms.txt
- Anthropic (Claude) Docs — https://docs.anthropic.com/llms.txt
- Svelte (Core) — https://svelte.dev/docs/svelte/llms.txt
- SvelteKit — https://svelte.dev/docs/kit/llms.txt
- Nuxt — https://nuxt.com/llms-full.txt
- Nuxt UI — https://ui.nuxt.com/llms.txt
- Nuxt Content — https://content.nuxt.com/llms.txt
- Auth0 AI Docs — https://auth0.com/ai/docs/llms.txt
- Langfuse — https://langfuse.com/llms.txt
- Mintlify Docs — https://mintlify.com/docs/llms-full.txt
- PostHog — https://posthog.com/llms.txt
- Svelte MCP (overview) — https://svelte.dev/docs/mcp/overview/llms.txt

