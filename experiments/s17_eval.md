# Session 17: prompt evaluation - v1 baseline vs v2 structured

Answering model: `openai/gpt-oss-20b` · Judge model: `openai/gpt-oss-20b` · Date: 2026-10-16

| Criterion | v1 (S14 baseline) | v2 (S16 structured) |
|---|---|---|
| Correct label | 15/20 = 75% | 0/20 = 0% |
| Cites the right house rule | 10/20 = 50% | 0/20 = 0% |
| Follows the reply format | 20/20 = 100% | 1/20 = 5% |
| Invents no policy | 20/20 = 100% | 15/20 = 75% |
| **All four criteria** | **10/20 = 50%** | **0/20 = 0%** |

Tickets graded: v1 20/20 · v2 20/20 (a ticket the judge could not parse is not counted, and is listed below).

Human spot-check: judge and human agreed on 3/20 = 15% of graded criteria (3/20).
