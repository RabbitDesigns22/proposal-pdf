# proposal-pdf

**Sales proposals in PDF that look expensive and read like a friend explaining a good deal.**

`proposal-pdf` is an agent skill for Claude Code (and any agent that reads `SKILL.md` skills). Small-business owners read proposals on a phone, inside a chat, and decide in about 30 seconds. Agents tend to produce long, generic documents with invented numbers and promises nobody can keep. `proposal-pdf` makes the agent lock every fact against its source first, follow a short 5-page structure, write without promised results, design with the client as the hero (even when they have no logo), build the PDF from HTML and check every page before handing it over.

## See the difference

> **You:** Make the proposal PDF for the bakery.

**Without the skill:** a long generic document with an invented price and a "guaranteed sales" promise.

**With the skill:** five short pages, every price and phone checked against its source, no promised results, one clear next step, and every page reviewed as an image before you get it.

**Skip it if** you need a legal contract, not a sales proposal.

**Status:** in daily use in the author's own setup. Plain instructions, no scripts, no network calls. MIT. Issues and suggestions welcome.

## What it does

| Problem | How proposal-pdf fixes it |
|---|---|
| Wrong price, phone or business name | Every fact is written down with its source and checked against the PDF text |
| Long proposal nobody finishes | 5 pages: cover, what you get, what's included, investment, next step |
| "Guaranteed sales", "first place on Google" | No promised results: it describes the work, not what the platform will deliver |
| Client has no logo | An elegant wordmark of their name, never a fake logo |
| Ends with "let me know if you have questions" | One clear question with two easy answers and a direct contact |
| Cut text, empty pages, blurry logos | One PNG per page, reviewed at full size before delivery |

## Install

With the [skills CLI](https://skills.sh):

```bash
npx skills add RabbitDesigns22/proposal-pdf
```

Or manually: copy `skills/proposal-pdf/` into `~/.claude/skills/` for all your projects, or into `.claude/skills/` for one project.

## Works well with

- [`easy-for-them`](https://github.com/RabbitDesigns22/easy-for-them): the message that goes with the PDF, ready to forward.
- [`small-budget-ads`](https://github.com/RabbitDesigns22/small-budget-ads): the ads plan the proposal sells.

## Español

**Propuestas de venta en PDF que se ven de agencia cara y se leen como un amigo que te explica un buen trato.** El agente comprueba cada precio y dato contra su fuente antes de escribir, arma 5 páginas (portada, qué gana, qué incluye, inversión, siguiente paso), no promete resultados, pone al cliente como protagonista aunque no tenga logo, construye el PDF desde HTML y revisa cada página antes de entregarlo.

Instalar: `npx skills add RabbitDesigns22/proposal-pdf`

## More skills from the same setup

These come from one real workflow: a small agency run with 15+ Claude Code sessions in parallel. Each skill fixes one problem that kept happening there.

| Skill | What it fixes |
|---|---|
| [one-pass](https://github.com/RabbitDesigns22/one-pass) | get it right the first time; stop paying tokens for rework |
| [hora-exacta](https://github.com/RabbitDesigns22/hora-exacta) | real date and time in every message, so nothing lands on the wrong day |
| [hands-on](https://github.com/RabbitDesigns22/hands-on) | the agent does what it can and only asks you for codes, keys and payments |
| [easy-for-them](https://github.com/RabbitDesigns22/easy-for-them) | steps people actually follow: direct link, one action per line |
| [one-answer](https://github.com/RabbitDesigns22/one-answer) | one thought-through answer instead of plan, fix, new plan |
| [never-twice](https://github.com/RabbitDesigns22/never-twice) | a shared error log so no session repeats a known mistake |
| [report-now](https://github.com/RabbitDesigns22/report-now) | status checked live this minute, stamped with the time |
| [sort-me-out](https://github.com/RabbitDesigns22/sort-me-out) | one ordered list of what is urgent, waiting and forgotten |
| [in-the-loop](https://github.com/RabbitDesigns22/in-the-loop) | a live board so parallel sessions know what the others changed |
| [study-first](https://github.com/RabbitDesigns22/study-first) | reads everything in full and answers point by point, no invented details |
| [session-watchdog](https://github.com/RabbitDesigns22/session-watchdog) | wakes the sessions that got stuck mid-task, leaves the rest alone |
| [skill-harvest](https://github.com/RabbitDesigns22/skill-harvest) | reads your sessions and finds the skills you are missing |
| [small-budget-ads](https://github.com/RabbitDesigns22/small-budget-ads) | Meta Ads rules for 1-5 USD a day ad sets |
| [whatsapp-closer](https://github.com/RabbitDesigns22/whatsapp-closer) | evidence-ranked rules for a WhatsApp sales assistant that closes |
| [whatsapp-number-onboarding](https://github.com/RabbitDesigns22/whatsapp-number-onboarding) | connect a number to the WhatsApp Cloud API in the safe order |

If one of them saved you a redo, a star helps other people find it.

## License

MIT. Made by [Rabbit Designs](https://github.com/RabbitDesigns22).
