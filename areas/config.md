# Config

Applies the [trunk](../PHILOSOPHY.md) to personal dev-environment config:
dotfiles, editor, shell, terminal. Config creates no product value. It only
carries cost. So almost every deviation here is a snowflake, and the bar for
crossing the grain is high.

1. **Defaults first.** Change a setting only to fix something that's actually
   broken, to match a shared convention, or to make one coherent choice like a
   single theme. Don't pile up little personal tweaks nobody else could guess.
   Stock behavior is predictable and explains itself.
2. **Simple to operate.** Keep interactions obvious. Nothing should require
   memorizing a private set of shortcuts. No amount of power is worth ceremony
   you have to remember.
3. **Reproducible and reversible.** One command should take a bare machine to
   ready, and every step should be safe to run twice and easy to undo. This is
   the config version of the trunk's reversible by default.

**Which grain wins.** When a tool's default fights the platform's own
convention, go with the platform. It's easier to recognize, not harder. Native
macOS tabs beat a tool's custom titlebar. When two conventions collide, the one
more people already know wins.

**Snowflakes vs. expression.** The problem was never expression. It's cost and
sprawl. One coherent choice that costs nothing to understand, like a consistent
color scheme, is fine. Minimal means few and coherent, not bland.
