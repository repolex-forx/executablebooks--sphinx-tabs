# Repolex Knowledge Graph of executablebooks/sphinx-tabs

RDF knowledge graph data for [executablebooks/sphinx-tabs](https://github.com/executablebooks/sphinx-tabs), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download executablebooks/sphinx-tabs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7e1d2eccd7e3ec002b0bc8626a491b218b54c131
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7e1d2eccd7e3ec002b0bc8626a491b218b54c131
│           └── chunk-001.nq.gz
├── blob
│   ├── 08a218d979cf04b0d5d992e4a61f89f186f9bde9.nq.gz
│   ├── 09bb679aa1dfd1325dc5c8eb45116707a9c082e9.nq.gz
│   ├── 1679ba1d728968661e1181e680462be869571f82.nq.gz
│   ├── 18157da6f7781063453a0d74577ffc71b320e791.nq.gz
│   ├── 1d1ec6e5a1f2856e3c70baaa0600a1d25c732f02.nq.gz
│   ├── 1ef24d7dae9486606031cb154d0935147a14b89e.nq.gz
│   ├── 1fc6dcbbf65552a072a7040e23ba71e7d843399e.nq.gz
│   ├── 242aa1224b3f7946b0d33c654e7f3820aa1b8a05.nq.gz
│   ├── 291ccfa497319202af49b9ba98928e0f06e5adce.nq.gz
│   ├── 2c78e1954a039212f61dfbb34000600f782f9b08.nq.gz
│   ├── 2d6e225c600dbfaa3d1b8ccce8378ae18b560a3b.nq.gz
│   ├── 312599cf6b7e838bd8629ecec7059f4169f26877.nq.gz
│   ├── 32c0985a414fe3a97a1061cd4966f4024041f73c.nq.gz
│   ├── 32e47a80e7ec0aaf5d5923dd6a7d9308c1a86735.nq.gz
│   ├── 3612f443a6262997fb665d7b26e0287fef12c0c7.nq.gz
│   ├── 3a8712710c5a22b7db66fa4ba65b7995dc968302.nq.gz
│   ├── 3abca8e76867db0eedb043b1bd288c926949f09f.nq.gz
│   ├── 48dc303c8c0165f4c8735d84bb8e09132d0edb58.nq.gz
│   ├── 4a3378bca518426e3e9e4be1390280f28389afb0.nq.gz
│   ├── 51b020320ddb3bb8a004a266546be94e3842cbc0.nq.gz
│   ├── 6203b3848df85ab0656d3d746b871a1072373fdd.nq.gz
│   ├── 6d33ca3f30c7cbc25698e4a1370c4fcfee06545c.nq.gz
│   ├── 8111e9314acbe408fe5fee102983132e11bc701f.nq.gz
│   ├── 81b333dfcab6ecbff154982162b6ea0b4f894354.nq.gz
│   ├── 8315dbb1474fb82f905dc9006d5d6cd1de32507d.nq.gz
│   ├── 840aebfb8020b341f8443b4e9cd82e1f46c74d62.nq.gz
│   ├── 86324c5d31f9ad28d6c3fab221e5d1c16c2aa386.nq.gz
│   ├── 919a1fe1fcd5a26afc9aa264767fb2d42afd9f90.nq.gz
│   ├── 957ba60d6989db4103dd1d921ba291879b0544e1.nq.gz
│   ├── 98401c5eb5bc4f0622f498640334ed72f6f517b1.nq.gz
│   ├── 99ef57deb47c870c2a3a62ee37b9566f31c3010d.nq.gz
│   ├── 9a778957fa852d4acbd0104264edcd1fe92a3d4f.nq.gz
│   ├── a25522fa51b27d1dad2632d99c74f863941d9df5.nq.gz
│   ├── a3dd89a7860402bdd4279fc1383848ee5a04ebd7.nq.gz
│   ├── a9f9f92c5527a9322326cedb51609ae3502fe605.nq.gz
│   ├── aa92b3e52b4804de3aa85305bbe0da0f68b887af.nq.gz
│   ├── aafb4d7c02d5be2fc7efc7c1b808c3618b4b3238.nq.gz
│   ├── aca2bdcec887ad75fb5a65a1d74ba07515812462.nq.gz
│   ├── b37e3d98234573019f2158fa0ce7873cc55a5157.nq.gz
│   ├── b86ae096b88a18afdd6bfd50c74aaf0dc886364a.nq.gz
│   ├── bb706e7743fc6a2641b2988aea047d369440b45a.nq.gz
│   ├── bc4e5b08a4e7426a17a272529108c47824063dba.nq.gz
│   ├── be7f38a7eb3cbd38d6600fcbc824349c01626262.nq.gz
│   ├── c124ccddfb3f2e93719ee37a06dfc89e56789b71.nq.gz
│   ├── cc9ffe5ff321cc721b51c83f6608e71647bdf625.nq.gz
│   ├── cd8602b8b12250205ff52671a8137ed8547b8a8a.nq.gz
│   ├── d1b3e77a0dc420f7752560e8e87b9653068ead93.nq.gz
│   ├── d1db3571c4d3be1b099904508800adb2f96ee844.nq.gz
│   ├── d1e8c4138e22c8adb458661cf39eb549fc10001b.nq.gz
│   ├── db690dc40b270248023f71ef70a365490391ea44.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6d02b57a954219435707d83c5a13897881025c9.nq.gz
│   ├── eccbf61d5d0393f593e61b8a3d3e1db17d6deae9.nq.gz
│   ├── f08d16e34f17bfa52b771388ee2662cce5f7ac34.nq.gz
│   ├── f1a0bddebf694b768b77c2b60be26e2759845c77.nq.gz
│   ├── fcc1d3ce607cd450bc8366a2430d65da7f6ec11c.nq.gz
│   ├── fd5e1ccd01b7211586c7aed4497e3b486f12fa90.nq.gz
│   └── ff35e605a01d92c363a94ae5919c81168c9fc0e5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7e1d2eccd7e3ec002b0bc8626a491b218b54c131.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 66 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[executablebooks/sphinx-tabs](https://github.com/executablebooks/sphinx-tabs)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
