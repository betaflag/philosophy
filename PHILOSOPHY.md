# Philosophy

The trunk. These principles hold across everything I build: code, products,
config, writing. Each file under [`areas/`](areas/) applies them to one
domain. The repo is built the way it preaches. The trunk holds the
primitives, each area is a product built on them, and a new area is just a
seam.

**Go with the grain. Cross it only where crossing it is the point.** Every
tool, platform, and community has a grain: the conventions people already
expect. Follow it by default. Conventions are leverage you didn't have to
earn, and every deviation is a bill that keeps arriving until it rots. A
snowflake is a deviation that isn't the point, the accidental kind, or just
taste. A differentiator is a deviation that *is* the point: deliberate,
load-bearing, worth its cost. Follow the grain everywhere else so the whole
novelty budget goes to the few differentiators that define the thing. Then
commit to those and keep them coherent.

The artifact was never the point. Code, config, a draft: all of it is
disposable packaging around the two things that last, what you learned and
how much it gets used. That's why the enemy is rot. Work that sits unused,
unshipped, or closed isn't neutral. It's a loss that looks like an asset.

1. **Absence is the default.** Add only what earns its place. Everything you
   add is something to build, maintain, and one day remove; nothing you
   leave out ever sends a bill.
2. **Build the core from primitives.** Small, composable pieces with clean
   seams. Expandability comes from how you cut, not how much you build, so
   it costs thought instead of machinery. Pull primitives out of what you
   already use: the ones invented for an imagined future tend to be wrong
   about it, and by then they're load-bearing. That's how a product changes
   direction without rotting at its core.
3. **The next person shouldn't need a manual.** A user, a teammate, or you
   in six months: they should figure it out from what's in front of them.
   Whatever they can't might as well not exist.
4. **Reversibility buys speed.** The cheapest way to evaluate a reversible
   decision is to make it: act now, state the assumption, and let reality
   do the review. Save the deliberation for the one-way doors. Walk through
   those slowly.
5. **Ship, or it rots.** Value is something work *does*, not something it
   *has*, and it does nothing from a drawer. Default to open and in use;
   hiding has to earn itself.
6. **The best default is no option at all.** Constrain over configure: make
   the wrong state impossible instead of merely non-default. An imposed
   opinion feels arrogant and is actually a gift. It spares the decision
   and prevents the snowflake by design instead of by discipline.
7. **Replace, don't deprecate.** When the new path lands, the old one gets
   deleted. Two ways to do the same thing is rot on a schedule, and the
   schedule always slips. When a cutover carries real risk, stage it: fork
   the path, deploy the new one alongside, merge so only the new one
   remains. The fork is scaffolding, and scaffolding that never comes down
   has become a second building.

**The test.** Before anything goes into what you build (a line of code, a
feature, a dependency, a sentence), ask three things. Is it needed now? Is
it a convention, or a deliberate differentiator? Can the next person figure
it out? One "no" and it stays out.
