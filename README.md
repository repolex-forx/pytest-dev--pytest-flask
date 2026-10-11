# Repolex Knowledge Graph of pytest-dev/pytest-flask

RDF knowledge graph data for [pytest-dev/pytest-flask](https://github.com/pytest-dev/pytest-flask), parsed by [repolex](https://repolex.ai).

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
rlex download pytest-dev/pytest-flask
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 22120c079d83c619403c67714a72405423889013
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 22120c079d83c619403c67714a72405423889013
│           └── chunk-001.nq.gz
├── blob
│   ├── 02567022e882e9c3bf243f57f779743becd64f7c.nq.gz
│   ├── 0e5c66b4326c043c7362c1a2683e6945e457fb80.nq.gz
│   ├── 1186a1e426edb7e3e99ca938e0d0b5ec44e59733.nq.gz
│   ├── 1d5ede8c81a68a056cd63521fedbff0e6a87da24.nq.gz
│   ├── 1e2585ce8e2944eba66a02ae004433c0b3cd0ae7.nq.gz
│   ├── 2e0dbb240266be991069b7759c1e08ef8df70fb9.nq.gz
│   ├── 300cf4f7a6b1e78ef028abfa549ad6520cb9806c.nq.gz
│   ├── 357c114bcb2eac7e7a2e0e1f875937f3214b2944.nq.gz
│   ├── 3f365aa3422c0bc2cf43793309dbe38c4899bb8e.nq.gz
│   ├── 3f967119a45e2903c8ddf02e172cb3c3674fa963.nq.gz
│   ├── 42f2c5edf359bcbc807f16c943b0faf257c19e14.nq.gz
│   ├── 462818222b531ec0c2569ba4cac22bef11bacc88.nq.gz
│   ├── 51a9b3444fdd65324323fa6b9cef1d3c14ace104.nq.gz
│   ├── 5f2150e9afeb79ae75e197843aba2b3b598e6fba.nq.gz
│   ├── 6bb78d575021459c2876d50eaefc5604966d74c2.nq.gz
│   ├── 7a201c87c0515b5031f0fc5fd0ad930803cbfedc.nq.gz
│   ├── 885199ccf2be5b70d8edd67874043dab7afa5cc8.nq.gz
│   ├── 8db6e7c5087101edfb01cbd44494ca36e70a3c47.nq.gz
│   ├── 8fe2302e7146d1213490ea25351faee97551f62e.nq.gz
│   ├── ab3f3dd41579d859f9a6c836bdafde70209c6e45.nq.gz
│   ├── b31b3313b2552d6bec13e9b2cc4402785cfc2022.nq.gz
│   ├── b38af95f3a3a7ffa43ffefbc4f8cae1ed85db31b.nq.gz
│   ├── b872be24e1b7a53da94a5d1373673b4b6e1f7cb2.nq.gz
│   ├── bc1ae158ff0ccd87353dceb7f2eb139fa9ae3122.nq.gz
│   ├── bc2a66ca09c9036b900061588df65304df4f206b.nq.gz
│   ├── c30a17eb270be0d68cd559eab7fb5c0d52fb774b.nq.gz
│   ├── c3ee4d37e4a1ef7c46f69a1fe5ceeb4a015bbf07.nq.gz
│   ├── c4c78f3690fcba1bfbad7daeb2fdc8edd7d9384e.nq.gz
│   ├── cd13966d26cab65ece18b7f30ae80526521ec64b.nq.gz
│   ├── cfef50892e5f3566297aef384f0e388f607dcf1f.nq.gz
│   ├── d15f0421a985916d2b82ab8d9d3d3c8acdb41036.nq.gz
│   ├── d2957e4134c1a814a848f49a0e237bc8e9db3a26.nq.gz
│   ├── d6001563fdc0b8b97529a9e3f9b0d2945d13a036.nq.gz
│   ├── d7404a02e711002fcee603fab50ed283e6c0312c.nq.gz
│   ├── d91d7006a312300696d85a10ebeaca959e633852.nq.gz
│   ├── df5231428f645ad5b02b91a7f7ff0dc7fb412dc0.nq.gz
│   ├── e339ea4a7f910488467a638e6be6fee4f1d03793.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── efe407d1b74c33f14c51d80a2af38a0c20890819.nq.gz
│   ├── f832bdf5b89044aa5c09c049b381251ef4b56025.nq.gz
│   ├── f86836836dcc58525326d9f4805f36ba24716c16.nq.gz
│   └── fefa40d5f6188617cfc008b6ba9f0e8ea46c725d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 22120c079d83c619403c67714a72405423889013.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 50 files
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

[pytest-dev/pytest-flask](https://github.com/pytest-dev/pytest-flask)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
