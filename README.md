# knowledge-base-thesis

Personal knowledge base for a master's thesis in Politcal Science. It tracks literature, decisions, reflections, and evolving synthesis.
The thesis manuscript and experiment source code live in separate repositories.

## Structure

| Path                | Owner    | Contents                                         |
| ------------------- | -------- | ------------------------------------------------ |
| `raw/literature/`   | external | PDFs of papers, `references.bib`                 |
| `raw/interviews/`   | external | finalized interview transcripts                  |
| `raw/datasets/`     | external | external data files                              |
| `wiki/literature/`  | LLM      | one summary page per source in `raw/literature/` |
| `wiki/concepts/`    | LLM      | cross-cutting synthesis pages                    |
| `work/`             | user     | experiments, modules, external repos             |
| `diary/`            | user     | `YYYY-MM-DD.md`, one file per working day        |
| `admin/`            | user     | deadlines, supervisor notes, ideas, todos        |
| `decisions/`        | user     | ADR-style records                                |
| `archive/`          | user     | abandoned experiments, scrapped drafts           |
| `manuscript-notes/` | user     | thesis-writing context                           |
| `inbox/`            | user     | capture surface for thoughts awaiting processing |
| `index.md`          | LLM      | catalog of the wiki                              |
| `log.md`            | LLM      | append-only chronological record of operations   |

`CLAUDE.md` (symlinked as `AGENTS.md`) is the schema and workflow specification for any LLM agent operating on the knowledge base. Read it before working with the repo through an agent.
