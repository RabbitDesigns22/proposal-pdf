# proposal-pdf

**Sales proposals in PDF that look expensive and read like a friend explaining a good deal.**

`proposal-pdf` is an agent skill for Claude Code (and any agent that reads `SKILL.md` skills). Small-business owners read proposals on a phone, inside a chat, and decide in about 30 seconds. Agents tend to produce long, generic documents with invented numbers and promises nobody can keep. `proposal-pdf` makes the agent lock every fact against its source first, follow a short 5-page structure, write without promised results, design with the client as the hero (even when they have no logo), build the PDF from HTML and check every page before handing it over.

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

## License

MIT. Made by [Rabbit Designs](https://github.com/RabbitDesigns22).
