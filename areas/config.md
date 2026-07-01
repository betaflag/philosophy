# Config

Specializes the [trunk](../PHILOSOPHY.md) for personal dev-environment config
(dotfiles, editor, shell, terminal). Config has no product value to create — it
only has cost — so here every deviation trends toward snowflake, and the bar for
crossing the grain is high.

1. **Defaults first** — Configure only to fix what's broken, match a shared
   convention (platform-native, community-standard), or make one coherent
   low-cost choice (a single theme or palette); never accrete idiosyncratic,
   hard-to-infer tweaks. Stock behavior is predictable and self-documenting.
2. **Simple to operate** — Obvious, low-ceremony interactions. Nothing you must
   memorize. No power justifies ceremony you have to remember.
3. **Reproducible & reversible** — One command, bare machine to ready. Every step
   idempotent and undoable. (This is the config-specific form of the trunk's
   *reversible by default*.)

**Which grain wins.** When a tool's default conflicts with the platform's native
convention, prefer the platform — it's more inferable, not less (native tabs
over a tool's custom titlebar). When two grains conflict, the more widely shared
and inferable one wins.

**Snowflake vs. expression.** The enemy is cost and sprawl, not expression. One
coherent choice that imposes no cost — a consistent theme or palette — is fine.
Minimal means few and coherent, not bland.
