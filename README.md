# Repolex Knowledge Graph of dtolnay/indoc

RDF knowledge graph data for [dtolnay/indoc](https://github.com/dtolnay/indoc), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download dtolnay/indoc
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8d78216b3f127f523d198475ea44090f8f6894d5
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 8d78216b3f127f523d198475ea44090f8f6894d5.nq.gz
│   └── repolex
│       └── 8d78216b3f127f523d198475ea44090f8f6894d5
│           └── chunk-001.nq.gz
├── blob
│   ├── 0be342f051e493045cce1f09a64b9d144754d374.nq.gz
│   ├── 110e4410626f3f246c4f0a4f92fd5632d2c07c8a.nq.gz
│   ├── 12a6c6464445e456d38371a0bd5dcab3ec0822a4.nq.gz
│   ├── 174ea95a847185db45cc1e7fc5bcde8de468ecb1.nq.gz
│   ├── 19965c38cd9b768c3a286975a10751308f47bc3f.nq.gz
│   ├── 19d0ea5430d17f60951888c8abd9dec395564451.nq.gz
│   ├── 1b5ec8b78e237b5c3b3d812a7c0a6589d0f7161d.nq.gz
│   ├── 22c3ebc0e245c78581aab4fe7fafbaa0221ca630.nq.gz
│   ├── 23a6a065ec960a031726c8c26222b0405d4f5851.nq.gz
│   ├── 23fc1719d9b646277044163ee3b5bac642bd3b5a.nq.gz
│   ├── 24e500e66510cf676adac489893c693faa3ee98d.nq.gz
│   ├── 31aa79387f27e730e33d871925e152e35e428031.nq.gz
│   ├── 4c1d4279cb39866d20524baa8310b21d6141a1e3.nq.gz
│   ├── 54dc432af38ecefc4ccdfdd577da57c3610514ca.nq.gz
│   ├── 661e3a0b611509c11a3a7b8950366f3e519e161b.nq.gz
│   ├── 717d4a217c296b9ddd3f133423f1c7102a52fbbc.nq.gz
│   ├── 750707701cdae985156601cc906195021ba6a6e5.nq.gz
│   ├── 76219eb72e8524f15c21ec93b9b2592da49b5460.nq.gz
│   ├── 798907c5e8e14b82074cabe78de38c1dbd50f825.nq.gz
│   ├── 7a76bc4f7387d4c0ec8e8d1de9067f6368db5a2d.nq.gz
│   ├── 7ae0cd2c0573ff599d3b27e7fe4df39514eae980.nq.gz
│   ├── 7bd11e2d24bf14ef415e273015e25006616e837f.nq.gz
│   ├── 8027a6cbbb975cc5a4fce99b4cfdd3b2fcbc22d6.nq.gz
│   ├── 86a0fcea0cd31d4294981a73eff6370e0325517d.nq.gz
│   ├── 90ea148a194a7fc84a14a526a35c56278307c600.nq.gz
│   ├── 965b606f331b51d566b46025f9ff311a7aad0c12.nq.gz
│   ├── 9df7df1b2cf31cd7905e666a932c31c3e55da64d.nq.gz
│   ├── 9e2795875ce3539e90dc31884af133aba08a34cf.nq.gz
│   ├── a1fb07862b4b4281eefae8ac46a707d3d373cc57.nq.gz
│   ├── a37f79ad8eeb72c998907e288fe4a24cdb56ece9.nq.gz
│   ├── b26d005ef1affce00103948cfc366035ad6479fc.nq.gz
│   ├── ba1b7466c0a7981aa8eb7719e3a4a9da71f52abf.nq.gz
│   ├── ba284e32aefc3b7013a183cf2d07921dcadcda3d.nq.gz
│   ├── bed418d92f26580b11d4ec251c00d3eb93b7ce34.nq.gz
│   ├── c98b3c0aff5f4e741f35cc6954dc36e93d0cddd7.nq.gz
│   ├── ccf12f71117f9a69e827bddcf49406a8ba88fd43.nq.gz
│   ├── cedc84edf7bc33539b0e47087a6285b4ed1234a1.nq.gz
│   ├── d3e8dbe65434589b0dc83e9d39680f8e432807e0.nq.gz
│   ├── d51072d8849397bd254827812528e870565e5fab.nq.gz
│   ├── d6c25cfc24a96aa39b5f981798d8bc87dcbdda88.nq.gz
│   ├── dc182bdd9a48d1658f56dd8606915cdcab107fb9.nq.gz
│   ├── e4d5d9799735f90f1414ec6654e17499eb3a7f17.nq.gz
│   ├── e9e21997b1aca0707f8749ea13c09aec66c899d2.nq.gz
│   ├── ea394d8f226f91728649d24854ee240125ef7908.nq.gz
│   ├── eccdecfca246dc9263d40edaed092c804475e1c3.nq.gz
│   ├── f56787eec6d338113b93412af5d9ab282951be00.nq.gz
│   └── f979fed4262d4a99101b75f1ee0c6e56603d1362.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 8d78216b3f127f523d198475ea44090f8f6894d5.nq.gz
├── filetree
│   └── 8d78216b3f127f523d198475ea44090f8f6894d5.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 57 files
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

## Source repository

[dtolnay/indoc](https://github.com/dtolnay/indoc)

---
*Parsed on 2026-04-22 by [repolex](https://repolex.ai)*
