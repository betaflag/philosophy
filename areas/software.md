# Software

Specializes the [trunk](../PHILOSOPHY.md) for building software and products.

**The manuscript.** Write code like a manuscript: direction and structure are
everything; keep them clean always — it's cheap. *Editing* — tests, hardening,
security, CI, refactoring for contracts — is waste until the manuscript
stabilizes. You don't copy-edit a chapter you might cut.

1. **Less code** — The best engineering is the code you didn't write. Every line
   is bug surface and future cost. Code is a disposable liability; the learning
   it generates, multiplied by usage, is the asset.
2. **Engineer only what *is* the product** — Infrastructure earns its place by
   delivering user value now. A background queue at the start is rot; a queue
   *is* the product when asynchronousness is the feature. Speculative scale and
   abstraction are premature by default.
3. **Structure always, edit when stable** — Clean, minimal design from line one
   (12-factor is free and prevents mess); defer tests, security, and CI until a
   surface hardens into a used contract. Rigor follows stability and use. Clean ≠
   slow — minimal *is* fast. Go fast *by* being minimal, never by cutting corners.
4. **Adopt the tool's vision, or leave it** — Use libraries as their creators
   intend; learn the mental model, don't fork it. Express your views in *which*
   tool you choose, never by bending one against its design. A mismatch means
   it's the wrong tool, not a project.
5. **Few strong tools** — Modern, but consolidated. Build around a small set of
   well-established tools; don't scatter across shiny ones.
6. **Open by default** — Code is never the moat; the moat is some other factor,
   and finding it is the actual work. Closing code is only ever a concession to
   security debt — never a strategy, and debt is meant to be paid down. If hiding
   the code feels load-bearing, you've mislocated your value.
