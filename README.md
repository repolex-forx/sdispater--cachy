# Repolex Knowledge Graph of sdispater/cachy

RDF knowledge graph data for [sdispater/cachy](https://github.com/sdispater/cachy), parsed by [repolex](https://repolex.ai).

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
rlex download sdispater/cachy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dd1da618d58d14a677df110517baf7b796f5c111
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── dd1da618d58d14a677df110517baf7b796f5c111
│           └── chunk-001.nq.gz
├── blob
│   ├── 0bb6ac7aa9a2b63a57718b5c93a8eada81e81a7c.nq.gz
│   ├── 0f145032e47cbdde173792f85d90befc5928ffd6.nq.gz
│   ├── 10ab3362f95b04a81bbe7b35b2978eb7d9a658af.nq.gz
│   ├── 1e9c6d5e1b4382703180fee39b84386ee75b37eb.nq.gz
│   ├── 1fe6ac4b22b4685a4693ea487bfd0d88c9d821a7.nq.gz
│   ├── 235308d935971ac407e07ca08781fa60bfcda009.nq.gz
│   ├── 3b292921d988ce8a47e047f2b941a8359c91adb0.nq.gz
│   ├── 3d12c262de84fbb4cabf18732d8af75f87b784d3.nq.gz
│   ├── 4b3a7f0b121eafa0791b3a27609a51aead240d24.nq.gz
│   ├── 53cd36a1140149c6c35b66e29c5c9470eb8be547.nq.gz
│   ├── 562414abc80843d50b4dcfe7d4b582e91e07b3b2.nq.gz
│   ├── 594f0ea955737b51c9297ba7a7749b6d9ffa6730.nq.gz
│   ├── 5a005a3761d6d7a0242d684e2045a159a397a534.nq.gz
│   ├── 5b96dd727747a6d20ff9c63abb7a739488c53ed1.nq.gz
│   ├── 5cbe1b00927e312c27b9ddb9532ff0a38ce5b406.nq.gz
│   ├── 606b30b8bd86dc135ece2ea5d71a2928f06cd4b9.nq.gz
│   ├── 633f866158ac742cf754a2c43edcb07e3a094f3c.nq.gz
│   ├── 701df228d97e9bf3f2b10c5634107daff2f7bd3d.nq.gz
│   ├── 7237d7a6a5ca5acbb0ae7f067e32f0d374aeab2a.nq.gz
│   ├── 79a44a0f6d27b561a65ff12b261901c6a325754c.nq.gz
│   ├── 7ab6fe1d6be6f6ed1a0102078dfbae428b7b5d17.nq.gz
│   ├── 7cf64288fa93ab7f917c93d6b27a84b90a842fb9.nq.gz
│   ├── 862d6d5e6dfa0cdfbd33d341edcc761c33d50d49.nq.gz
│   ├── 916eaaba2ee2311b10a8fa10b8a2c61cba1c965c.nq.gz
│   ├── 9427a9d688c3cd32452c744405f2f9f069156e87.nq.gz
│   ├── 9f1573b09bcaafed38c98c6e7bbab2292ec92e29.nq.gz
│   ├── a1658dc3ea44ea56d20aec17c111b4e82a6db774.nq.gz
│   ├── a5009f45968d1f8404df450feac3c61008684fa3.nq.gz
│   ├── aaf0d0fd698ff14b492fc81c34ea55bb43105e8d.nq.gz
│   ├── ae9dda4d2aa81235948e54ae350888b40fba2eca.nq.gz
│   ├── aeb53b74ab04bd63901ff7e2a17a7ea0f4b60fee.nq.gz
│   ├── b1c63d0dfe55c991626182bd3379939c503c2634.nq.gz
│   ├── b2574a35a5ccb98b728cb51e55d46ac8a4e94ffe.nq.gz
│   ├── b4843aa736b71a0ef292bb69f3a87288d7ccf6bd.nq.gz
│   ├── bc39d3a0378f303620932c7c03f7429631f87f22.nq.gz
│   ├── be8989f821f2851bfc0c64a950fbae43dd60f83c.nq.gz
│   ├── c3194f16a76b2ec9eac08e366906fb759d7e0855.nq.gz
│   ├── c41680b6c1b0fac09f8ffbc612948c41a5b2e85c.nq.gz
│   ├── c5e754affa6c0b2d7c05ba31e8257c137491f77b.nq.gz
│   ├── c62e51819f7118be43f1bd02e2b0ed49ebd9523f.nq.gz
│   ├── cefdc69931b428dd43a13e16e35eac37adc17157.nq.gz
│   ├── da884788e4f1e17e025398aece7d1d79706488be.nq.gz
│   ├── e225eb30be2c7af38fe45e52a307e287400f7d9d.nq.gz
│   ├── e3550198025e7326ae48177cc61a646b8d858e92.nq.gz
│   ├── e73c7b8e82ba88ce966efc8f71000f7702003a4b.nq.gz
│   ├── ebfb3eb2162bec2fbd7f5859cea0f8acfba2b7b3.nq.gz
│   └── f68b0b91f812de3778538ed170a780300ef7b491.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── dd1da618d58d14a677df110517baf7b796f5c111.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 55 files
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

[sdispater/cachy](https://github.com/sdispater/cachy)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
