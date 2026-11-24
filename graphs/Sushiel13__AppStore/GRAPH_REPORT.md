# Graph Report - target  (2026-11-24)

## Corpus Check
- 4 files · ~15,084 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 7 file(s) not represented in the graph (top: (none) 3, .apk 2, .mobileconfig 1)

## Summary
- 15 nodes · 18 edges · 4 communities (1 shown, 3 thin omitted)
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `6e51fa73`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- AppBucket
- _this

## God Nodes (most connected - your core abstractions)
1. `_this` - 5 edges
2. `AppBucket` - 5 edges
3. `qrPolynomial()` - 4 edges
4. `What's in it` - 1 edges
5. `Add or update an app` - 1 edges
6. `Reviews and other messages` - 1 edges
7. `Run locally` - 1 edges

## Surprising Connections (you probably didn't know these)
- None detected - all connections are within the same source files.

## Import Cycles
- None detected.

## Communities (4 total, 3 thin omitted)

### Community 0 - "AppBucket"
Cohesion: 0.33
Nodes (5): Add or update an app, AppBucket, Reviews and other messages, Run locally, What's in it

## Knowledge Gaps
- **3 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `qrPolynomial()` connect `_this` to `qrcode.js`?**
  _High betweenness centrality (0.113) - this node is a cross-community bridge._