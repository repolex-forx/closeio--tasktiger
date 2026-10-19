# Repolex Knowledge Graph of closeio/tasktiger

RDF knowledge graph data for [closeio/tasktiger](https://github.com/closeio/tasktiger), parsed by [repolex](https://repolex.ai).

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
rlex download closeio/tasktiger
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 881a59f58742a155ce55313c6b46a2fdd06f8962
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 881a59f58742a155ce55313c6b46a2fdd06f8962
│           └── chunk-001.nq.gz
├── blob
│   ├── 00646f3ddcfb0cbc0cdda4b6f22f7c22db95ab71.nq.gz
│   ├── 0075aede7642c5ad9924521a33186344c2f3461b.nq.gz
│   ├── 0116e1b3c919cf30b6366e1e07ffb5ede69dbd54.nq.gz
│   ├── 04abf31500c10ab74a65be38e4fb3fc2f81c1996.nq.gz
│   ├── 04b7c6a7869fced47495881755f15ea56cca2103.nq.gz
│   ├── 05ac0f484ece3fbbf347797c26032b867c01075b.nq.gz
│   ├── 0f455f26a9a508ad5cdc7e9ab430ebe20d1de851.nq.gz
│   ├── 119d64e9f92b732418386f1af5b56e19534b2553.nq.gz
│   ├── 19ea9018c6b0c6788ea3c9ea892fd25623682dc5.nq.gz
│   ├── 26c7a79b8bb5c1b064e56bb965b06b28e4a5b0ac.nq.gz
│   ├── 2b25c5c009476b9b9ad792bb51d136724e67c9a7.nq.gz
│   ├── 2d92bb3f017fdab2c857890e067192e3ca83da82.nq.gz
│   ├── 36b8b4d10c5b5bba5e8c6dcd33736a1d4ae21b87.nq.gz
│   ├── 374bcb0792f9d242ccacc2a398da0c666841f67f.nq.gz
│   ├── 3d3e52d23112a2e1284aa8584f8be6146db32c8c.nq.gz
│   ├── 3fe061c51b3ac76ba5f64c945674c34312f96115.nq.gz
│   ├── 40cf037b87df53ca3467d48a3578173ba21ef294.nq.gz
│   ├── 41cbcc2c2d88fa1699806644aa809bf6d84cf106.nq.gz
│   ├── 467663b1af44866b28152a323a64ba7266f3cbaa.nq.gz
│   ├── 4820f3bc9d8811c5a26405f4ce8515f6149f1578.nq.gz
│   ├── 49983eea8ca33b64a8697408f13029fcaa2648c3.nq.gz
│   ├── 4e3a8403d963a6cc1be01859fe00b7257f556bf4.nq.gz
│   ├── 4efb9af0012588f6ca8fffcf93fb967ec41c4a1c.nq.gz
│   ├── 50f8b174f8064149b53357f481c866629e48eece.nq.gz
│   ├── 529fbb8e95b28ccd9c95f0d371aa49f136a28687.nq.gz
│   ├── 5b93dfac19db5da0a0bc91449ae5084fb397b44f.nq.gz
│   ├── 61fc558b229403fc8a57ec233f33b6ede058b024.nq.gz
│   ├── 699cbd923d28557157da11846819eb44f3b85ae1.nq.gz
│   ├── 6d493024fac4f3b0d8c314904de6761e08749b41.nq.gz
│   ├── 703d4d27eb1f125032e40091f0d31ec38ef9c398.nq.gz
│   ├── 714feb1f6718cd09e68a324d40b1172e77efd855.nq.gz
│   ├── 7241f425df902d59af0d9805a99d454b9fbdba4d.nq.gz
│   ├── 76f41456f74d02dcf27fb33ddf627cc696dc7128.nq.gz
│   ├── 7ebe6ef77fd097c808c980c54a1b88627558520c.nq.gz
│   ├── 8137baf1d349f46b4a0d1c93fe38ae0ac97d7ac4.nq.gz
│   ├── 848386e4fe7b8942528917dc38d77b907c83171e.nq.gz
│   ├── 9e18582ce1863152510d57d6cc5d92358b3c0538.nq.gz
│   ├── abb8320658c11127cd886f897592d47e4656fcea.nq.gz
│   ├── b39d6315f47d0cc89f7538e2cf1d9b3b72ee75f9.nq.gz
│   ├── ba467629e07cdf1e8facd3fb859b1f4cd82acf5a.nq.gz
│   ├── be4de25313165a8482d9d9519273ae40da3d0c4e.nq.gz
│   ├── c30c67494c595514df336864c78ba00ad65bbd45.nq.gz
│   ├── c42653cb66db10b03e39c072585c57edaf9aa71b.nq.gz
│   ├── c8bad82ef1765352844ee4b5382224fac853ffe2.nq.gz
│   ├── cd5516fdf5f7049a2721c73f84c259d29667901e.nq.gz
│   ├── ce44f287c9d173fbf13e1533513b1b4bfb35a075.nq.gz
│   ├── dae11bbe98893dd4cc5bf3172c8524febbd822de.nq.gz
│   ├── dc22bb61f9051830b46cc553fb700c4c414a0c3f.nq.gz
│   ├── e3ee968d35b8d7296d71e76ad562b1de9f163bae.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ec0204754b2dea53ab95f976c57eb976d3335feb.nq.gz
│   ├── f17f52fa008299e799ae016328552dc17bdde9a9.nq.gz
│   ├── f33494acf7c86b0cbd1ad24d292297b64ee01a27.nq.gz
│   ├── f4fc94c04af113374a692f241285f12d2fbc769e.nq.gz
│   ├── f5f7fcb995c4634b6c77abe1106581ffb7bafe51.nq.gz
│   ├── f6c04d4368522507bc62d8cf7cc7d278f4542cd8.nq.gz
│   ├── f6cfe9f6a485df7e24f44ac6bf97f20a77a93fe1.nq.gz
│   └── f80bc487262492fd5a2edb69ec79def38711b732.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 881a59f58742a155ce55313c6b46a2fdd06f8962.nq.gz
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

[closeio/tasktiger](https://github.com/closeio/tasktiger)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
