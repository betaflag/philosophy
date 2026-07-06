# Software

Applies the [trunk](../PHILOSOPHY.md) to building software and products.

**The manuscript.** Write code the way you'd write a manuscript. Direction
and structure are what matter, and keeping them clean is cheap, so do it
from the start. Editing is a different job: tests, hardening, security, CI,
refactoring to fit a contract. That work is wasted until the manuscript
stabilizes. You don't copy-edit a chapter you might cut.

1. **The best engineering is the code you never wrote.** Every line is a
   place a bug can live and a thing someone has to maintain. Code is a
   liability you spend to buy learning, and the learning is the only part
   that appreciates. Usage multiplies it.
2. **Engineer only what is the product.** Infrastructure earns its place by
   delivering value now. A background queue on day one is rot. The same
   queue when async *is* the feature is the product. Scale and abstraction
   are premature until something real proves otherwise, and "we'll need it
   eventually" has a losing record.
3. **Structure always, edit when stable.** Keep the design clean and
   minimal from the first line; 12-factor costs nothing extra and keeps the
   mess out. Hold the editing (tests, security, CI) until a surface hardens
   into a contract people depend on. Minimal is what makes you fast, so go
   fast by doing less, never by cutting corners. And once a thing is
   stable, finish it. Craft is the reward of stability, and a proven thing
   left half-polished is its own kind of rot.
4. **Adopt the tool's vision, or leave it.** Use a library the way its
   author meant it. Learn how they think about the problem instead of
   forcing your shape onto it. Judgment goes into picking the tool;
   fighting it afterward is judgment spent too late. If it doesn't fit how
   you think, it's the wrong tool.
5. **A few strong tools beat many new ones.** Stay modern, but make the new
   thing beat the proven thing at something that matters. It usually just
   beats it at being new. Pick a small, proven set and build around it.
6. **The code is never the moat.** Open by default: the moat is some other
   factor, and finding it is the real work. The only honest reason to close
   code is security debt you haven't paid down, and that's a debt with a
   date on it. If keeping the code secret feels essential, you haven't
   found your real advantage yet.
7. **Watched it work, or it doesn't.** Nothing works because you wrote it
   carefully. Before a surface stabilizes, verification is you running the
   thing and looking. Once it hardens into a contract, build the looking
   into machinery: tests you've watched fail, types, linters, hooks. The
   machinery waits for stability; the looking never does. And when a change
   touches anything shared, know the blast radius before and check the
   state after.
