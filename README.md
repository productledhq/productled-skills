# ProductLed Skills

**The frameworks from Wes Bush's *Product-Led Growth* and *The Product-Led Playbook*, as installable skills for Claude Code and AI agents.**

Most AI advice about product-led growth is a remix of blog posts. These skills are different: they're built from the primary source (the books that defined the category) and they don't give you advice, they run the actual frameworks on *your* business and produce the artifact: a readiness verdict, a homepage with real copy, an onboarding audit with a kill list, a scorecard with owners.

Install them once and your AI assistant knows how to apply the MOAT Framework, the Market Ascent, the Bowling Alley Framework, value metrics, and the rest of the ProductLed System, with the diagnostics, output formats, and voice rules the books themselves use.

## Install

The fastest way (installs into `.claude/skills/` in your project):

```bash
npx skills add ProductLed/productled-skills
```

Or clone and copy the skills you want:

```bash
git clone https://github.com/ProductLed/productled-skills.git
cp -r productled-skills/skills/* your-project/.claude/skills/
```

Skills work in Claude Code out of the box and in any agent framework that reads `SKILL.md` files (Claude Agent SDK, and compatible tools).

## The skills

Two **advisor skills** cover each book end-to-end:

| Skill | What it does |
|---|---|
| `product-led-growth` | Strategy advisor from *Product-Led Growth (2nd Ed.)*: should you go product-led, what flavor, are you ready, where you sit on the Market Ascent |
| `product-led-playbook` | Execution coach from *The Product-Led Playbook*: diagnoses your funnel leak and runs the right component of the 9-part ProductLed System |

Nine **task skills** each do one job and produce one artifact:

| Skill | Ask it |
|---|---|
| `plg-readiness-audit` | "Should we launch a free trial?" → go / no-go / not-yet verdict |
| `choose-your-plg-model` | "Free trial or freemium?" → one committed model with the free/paid line drawn |
| `market-ascent-diagnosis` | "Where do we stand competitively?" → your level + the barrier to the next one |
| `build-your-moat` | "How do we defend against copycats?" → the 2–3 moats you can actually build |
| `define-your-user-endgame` | "Who is our ideal user, really?" → filled User Endgame artifact |
| `write-your-homepage-offer` | "Why isn't our homepage converting?" → a 5-section page with real copy |
| `audit-your-onboarding` | "Why do signups never come back?" → Bowling Alley audit with a kill list |
| `price-with-value-metrics` | "What should we charge for?" → your value metric + tier ladder |
| `find-your-north-star` | "What should we measure?" → North Star + 6-metric scorecard with owners |

## How they behave

Every skill follows the books' operating rules: diagnose before prescribing, quantify everything ("easy setup" is banned; "12-minute setup" is the bar), commit to one recommendation instead of hedging, and push back when your plan contradicts the frameworks. Written output is checked against the books' voice guide. No AI filler.

## What's inside a skill

```
skills/plg-readiness-audit/
├── SKILL.md          # when to trigger, how to work, output format
└── references/       # the distilled frameworks the skill runs
```

The references are distilled framework files. The full books, with the stories and step-by-step reasoning behind every framework, live at [productled.com](https://productled.com).

## License

Free to use in your work, commercial or personal. See [LICENSE.md](LICENSE.md). The frameworks and their names remain the intellectual property of ProductLed. Don't resell or republish this content as your own product.

## About

Built by [Wes Bush](https://productled.com), author of *Product-Led Growth* (the book that defined the category) and *The Product-Led Playbook*, founder of ProductLed. If these skills help you, the books go deeper, and [productled.com](https://productled.com) has the full system.
