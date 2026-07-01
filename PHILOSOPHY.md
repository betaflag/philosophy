# Philosophy

The trunk — principles that hold across everything I build: code, products,
config, writing. Each file under [`areas/`](areas/) specializes them to a
domain. This repo is itself built the way it preaches: the trunk is the
primitives, each area is a product built on them, and adding an area is the seam.

**Go with the grain — cross it only where crossing it is the point.** Every tool,
platform, community, and audience has a grain: its conventions and expectations.
Follow it by default — conventions are free leverage, and each deviation is a
cost paid until it rots. A *snowflake* is a deviation that isn't the point:
accidental, taste-driven, peripheral. A *differentiator* is a deviation that *is*
the point: deliberate, load-bearing, worth its cost. Default to the grain
everywhere so you can spend your whole novelty budget on the few differentiators
that define the thing — and make those coherent.

The asset is the **learning and the value transmitted, not the artifact**. Code,
config, and drafts are disposable; what compounds is what you learn, multiplied
by use. So the enemy is **rot**: anything unused, unshipped, or hidden produces
no learning and transmits no value.

1. **Minimal surface** — Add only what earns its place; absence is the default.
   Everything added is built, learned, maintained, and eventually removed.
2. **Primitives over products** — Build the core as small, orthogonal, composable
   pieces with clean seams. Expandability is *how you cut*, not *how much you
   build* — it costs design thought, not machinery. Extract primitives from
   present use; never anticipate absent futures. This is how a thing shifts
   without rotting at its core.
3. **Legible to whoever's next** — A user, a teammate, or future you should infer
   it without a manual.
4. **Reversible by default** — Prefer decisions you can undo; make one-way doors
   slowly and deliberately.
5. **Ship, or it rots** — Value exists only when transmitted. Default to open and
   used; hiding or hoarding is a cost that must earn itself, never a strategy.

**The test** — for anything entering anything you build (a line, a feature, a
dependency, a deviation, a sentence):
Needed now? · Convention, or a deliberate differentiator? · Can whoever's next
infer it? — one "no" and it stays out.
