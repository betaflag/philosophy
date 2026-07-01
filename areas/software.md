# Software

Applies the [trunk](../PHILOSOPHY.md) to building software and products.

**The manuscript.** Write code the way you'd write a manuscript. The direction
and the structure are what matter, and keeping them clean is cheap, so do it from
the start. Editing is a different job: tests, hardening, security, CI, refactoring
to fit a contract. That work is wasted until the manuscript stabilizes. You don't
copy-edit a chapter you might cut.

1. **Less code.** The best engineering is the code you never wrote. Every line is
   one more place a bug can live and one more thing to maintain. Code is a
   liability you spend to get something back, and what you get back is the
   learning. Usage multiplies it.
2. **Engineer only what is the product.** Infrastructure earns its place by
   delivering value now. Starting a project with a background queue is rot.
   Building that same queue when async *is* the feature is the product. Treat
   scale and abstraction as premature until something proves otherwise.
3. **Structure always, edit when stable.** Keep the design clean and minimal from
   the first line. 12-factor costs nothing extra and keeps the mess out. Hold off
   on tests, security, and CI until a surface has hardened into a contract people
   depend on. Clean isn't slow. Minimal is what makes you fast, so go fast by
   doing less, not by cutting corners.
4. **Adopt the tool's vision, or leave it.** Use a library the way its author
   meant it to be used. Learn how they think about the problem instead of forcing
   your own shape onto it. Your judgment goes into picking the tool, not into
   fighting it. If it doesn't fit how you think, it's probably the wrong tool.
5. **Few strong tools.** Stay modern, but don't chase every new thing. Pick a
   small set of proven tools and build around them.
6. **Open by default.** The code is never the moat. The moat is some other
   factor, and figuring out what that is happens to be the real work. The only
   honest reason to close code is security debt, like legacy you haven't
   hardened, and that's a debt you plan to pay down. If keeping the code secret
   feels essential, you haven't found your real advantage yet.
