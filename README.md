# Repolex Knowledge Graph of tokio-rs/bytes

RDF knowledge graph data for [tokio-rs/bytes](https://github.com/tokio-rs/bytes), parsed by [repolex](https://repolex.ai).

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
lexq download tokio-rs/bytes
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 417dccdeff249e0c011327de7d92e0d6fbe7cc43
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 417dccdeff249e0c011327de7d92e0d6fbe7cc43.nq.gz
│   └── repolex
│       └── 417dccdeff249e0c011327de7d92e0d6fbe7cc43
│           └── chunk-001.nq.gz
├── blob
│   ├── 08d2f254e81964cc5cd162a2bd9118ca8a4513a8.nq.gz
│   ├── 099016e24c7123acda2b437adcc12f84a43da92d.nq.gz
│   ├── 0a5bd144a960ac4d8eb771da7eea36094e088375.nq.gz
│   ├── 0c0159be1defc615af2c0ea104724390df667575.nq.gz
│   ├── 1203b419880bced46512ce6e8d6c3e6df5f915a3.nq.gz
│   ├── 15e67d94c663926cc30c4036b60dd5123eb7e772.nq.gz
│   ├── 192034fbed82fb6b6333981f86d74d2eb6ec50ad.nq.gz
│   ├── 19a16324ee9f4b4483bddb19a7771e1f64773d9d.nq.gz
│   ├── 1bf0a47e8d04582ad0887d8a091eddb0d806aa43.nq.gz
│   ├── 3154dfeca8e258c4405834cfd7fc49b0ee8970e6.nq.gz
│   ├── 4284791f15b1b6ff5a5064f4b0e5a566e05ffe78.nq.gz
│   ├── 441ca80d7577f94ecea3b52108d7acccab51c1cd.nq.gz
│   ├── 4758dc2f9e6281b97e1befd2f7586c17c1d90818.nq.gz
│   ├── 48e2df99b588cb7062a5b25a925d1856a1b716d2.nq.gz
│   ├── 4fffb2f89cbd8f2169ce9914bd16bd43785bb368.nq.gz
│   ├── 5214949587da046c4c58ad5e9edc71dfaa35da48.nq.gz
│   ├── 55d5636b199594db2921cf0e09cf383f9d324ae9.nq.gz
│   ├── 57df5910d7ffae2f069b2655b869e92dd33c89b1.nq.gz
│   ├── 58fb29a12384e4a5f41a97bcfc7f6f9b2016903d.nq.gz
│   ├── 5cccb362c14214d49481646949047565c12a3208.nq.gz
│   ├── 616d18748839aa95e14b5d9ce1dfd644a2702fb3.nq.gz
│   ├── 74f9b991eaf66f322cca94528fb8150d4a261090.nq.gz
│   ├── 79b57dafde126db315a7a104a7aaa200be29f9c8.nq.gz
│   ├── 82d0aa5e3bee15993a1c095b80271aca9dc9f8cf.nq.gz
│   ├── 8782d00669e19b4a01754ab1f4d866feb001d03e.nq.gz
│   ├── 90d631c97fce70e2469494cdb645740ed7ce7579.nq.gz
│   ├── 9c7601717c4cd732b3c8685e5b0e71cec77fa62c.nq.gz
│   ├── ad97574493b4f621826ef1e44266b2ca999a4b95.nq.gz
│   ├── aea096ae69d56ff8a0b8e6bf39c5300e6ea5bced.nq.gz
│   ├── b069436210058094f410038801b9e3f1280ad036.nq.gz
│   ├── b422be538333d342bee7e29cc9f4aef1f4503a95.nq.gz
│   ├── b74a831cb3b85e626e4b4125829c2fbf8de8dbd4.nq.gz
│   ├── b8a0eafafd077d625eb9ee4d399681f8c0b49053.nq.gz
│   ├── b9bd5e12b571f7f86fb530ef641a125c46facb17.nq.gz
│   ├── bad901860e5f608c1eaca5da7052ef134d5d4583.nq.gz
│   ├── c809290923a46e5679fabd2dd0037305472c1dd6.nq.gz
│   ├── c8bc36de96d21f1d8911fb95f6d8a2c8b5f8863e.nq.gz
│   ├── ca520bd7fd0492d1c73fdd0a12d51bfe7b2f41d4.nq.gz
│   ├── ca7f41df583776d789cf9af4ff10f29be75dbd16.nq.gz
│   ├── cf4aeffa78542677cf8f737d6ede0af9def92bad.nq.gz
│   ├── d8621f3f35b866f487bcbe3954f8538caa08c37d.nq.gz
│   ├── dc40cc5f0e9e4121165a2913d7eea0a4c729ba67.nq.gz
│   ├── e72348f40f638675e51f7d6c9e0415f951ad1f1b.nq.gz
│   ├── e809f44f1f4a8169ace178ce9c2f9a1097c6291c.nq.gz
│   ├── f1bd3b0a0f14860a6b280b604fc4e5b4ce1b0d4e.nq.gz
│   └── fb5c506e8867682698b43add973f85c6ec69a713.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 417dccdeff249e0c011327de7d92e0d6fbe7cc43.nq.gz
├── filetree
│   └── 417dccdeff249e0c011327de7d92e0d6fbe7cc43.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 56 files
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

[tokio-rs/bytes](https://github.com/tokio-rs/bytes)

---
*Parsed on 2026-09-07 by [repolex](https://repolex.ai)*
