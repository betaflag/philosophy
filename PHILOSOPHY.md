# Philosophy

The trunk. These principles hold across everything I build: code, products,
config, writing. Each file under [`areas/`](areas/) applies them to one domain.
The repo is built the way it preaches. The trunk holds the primitives, each area
is a product built on them, and a new area is just a seam.

**Go with the grain. Cross it only where crossing it is the point.** Every tool,
platform, and community has a grain: the conventions people already expect.
Follow it by default, because conventions are free leverage and every deviation
is a cost you pay until it rots. A snowflake is a deviation that isn't the point,
the kind that's accidental or just taste. A differentiator is a deviation that
*is* the point: deliberate, load-bearing, worth its cost. Follow the grain
everywhere else so your whole novelty budget goes to the few differentiators
that define the thing. Then commit to those and keep them coherent.

What lasts is the learning and the value you transmit, not the artifact that
carried it. Code, config, a draft: all disposable. What compounds is what you
learned, multiplied by how much it gets used. So the enemy is rot. Anything that
sits unused, unshipped, or closed teaches you nothing and delivers nothing.

1. **Minimal surface.** Add only what earns its place. Absence is the default.
   Everything you add is something to build, maintain, and eventually remove.
2. **Primitives over products.** Build the core from small, composable pieces
   with clean seams. Expandability comes from how you cut the pieces, not from
   how much you build, so it costs thought rather than machinery. Pull primitives
   out of what you actually use today. Don't invent them for a future that may
   never arrive. That's how a product changes direction without rotting at its
   core.
3. **Legible to whoever's next.** A user, a teammate, or you in six months should
   be able to figure it out without a manual.
4. **Reversible by default.** Prefer decisions you can walk back. Make the
   one-way doors slowly.
5. **Ship, or it rots.** Value only exists once it's transmitted. Default to open
   and in use. Hiding or hoarding is a cost that has to earn itself, never a
   strategy on its own.

**The test.** Before anything goes into what you build (a line of code, a
feature, a dependency, a sentence), ask three things. Is it needed now? Is it a
convention, or a deliberate differentiator? Can the next person figure it out?
One "no" and it stays out.
