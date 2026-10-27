# Coldworks design reference

A one-page reference for Coldworks: architecture, the record model,
extraction lanes, rungs, phases, roadmap, and proposed ideas. It is static
HTML with no build step, published by GitHub Pages from the root of `main`.

**This repository is public.** GitHub Pages on the organization's Free plan
serves only from a public repository, so everything here is readable by
anyone.

## What may go in

The page summarizes private records. Before you add a line, apply the test
from the pre-publication register: would a stranger learn something the
company would rather sell than give away, or something that belongs to
somebody else? These never go in:

- Pricing, dollar figures, savings claims, and tenant or user counts.
- Prospect names, outreach, and competitor names or positioning.
- The retired public name for the reviewer.
- Links into private repositories, and founder-queue item ids.

## Sources

Each section restates one of these records. When a record changes, update
the page from it, and change the date in the sidebar and footer.

| Section | Source record |
|---|---|
| Overview, vision, rungs, future state, proposed ideas, gates, what not to build | `hq/docs/company/unified-product/README.md` |
| Architecture, checks, decision records | `coldworks/README.md`, `coldworks/docs/decisions/` |
| The record, sources and force, record types | `coldworks/spec/ir-0.3.0.schema.json`, `spec/fixtures/0.3.0/` |
| Phases | `hq/docs/roadmap/roadmap.json`, `phases` (as of 2026-09-26) |
| Roadmap | `coldworks` merged pull requests and `HANDOFF.md` |
| Captured ideas | `hq/docs/ideas/IDEAS.md` |

## Preview locally

```
python3 -m http.server 4173
```
