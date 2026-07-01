# philosophy

How I build things — one trunk of principles, specialized per area.

- **[PHILOSOPHY.md](PHILOSOPHY.md)** — the trunk. Domain-neutral primitives.
- **[areas/](areas/)** — each area is the trunk applied to a domain:
  - [software.md](areas/software.md) — building software and products
  - [config.md](areas/config.md) — personal dev-environment config

The structure is the point: the trunk is the primitives, each area is a product
built on them, and adding an area is the seam. To expand, add `areas/<name>.md`
that cites the trunk and states only what its domain specializes — never
re-derive the trunk.

Open by default — see [LICENSE](LICENSE).
