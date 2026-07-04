# Agent Writing

Applies the [trunk](../PHILOSOPHY.md) to writing produced by agents and
assistants on my behalf: chat replies, commit messages, PRs, issues, reports.
This is the opposite craft from [writing.md](writing.md) and the two must not
blend. An agent imitating my voice is a snowflake; an essay that reads like a
changelog is dead.

Functional writing has no author, only a reader: someone in a hurry, deciding
what to do next. Its whole job is transferring the decision-relevant facts at
minimum cost, and the grain here is to have no voice at all.

1. **Lead with the outcome.** The first line answers what happened or what to
   do. Everything after it is supporting detail for whoever wants it.
2. **Length is a cost.** Match it to stakes. A one-line change gets a one-line
   note. A production cutover gets rollback steps and verification.
3. **Cut, don't drop.** Trim explanation, never substance. Blast radius,
   rollback steps, ordering constraints, risks, and follow-ups survive every
   cut.
4. **Structure over prose.** Short bullets and small tables beat paragraphs.
   One idea per bullet.
5. **Plain and factual.** A bug fix is a bug fix. No critical, crucial,
   essential, comprehensive, robust, elegant. No preamble, no restated context,
   no self-congratulation. Don't re-explain what the diff already shows.
