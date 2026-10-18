# Repolex Knowledge Graph of pythonprofilers/memory_profiler

RDF knowledge graph data for [pythonprofilers/memory_profiler](https://github.com/pythonprofilers/memory_profiler), parsed by [repolex](https://repolex.ai).

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
rlex download pythonprofilers/memory_profiler
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fdf104d652a1d2b15a0a7af0d9bc91c6331845cc
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fdf104d652a1d2b15a0a7af0d9bc91c6331845cc
│           └── chunk-001.nq.gz
├── blob
│   ├── 07bee578290a9431fc1d7c717a691c6870f17ece.nq.gz
│   ├── 09ea1a58a9cdcd15e4e03deb9e81317d208eab4b.nq.gz
│   ├── 0a166d1461eac2a1185110367232bbc44dbf2020.nq.gz
│   ├── 10c3eaabdab1a4e4ba83bea49faa64801812a6ab.nq.gz
│   ├── 1fb0e1a1c7cc805713a33b58878dce0afa7fd6d6.nq.gz
│   ├── 2a61fbcef45040fd6d2f6f88fcb81a4627f5dbf3.nq.gz
│   ├── 2c49396664773be888ce94c4b232ba8a95f3257d.nq.gz
│   ├── 3336d68b0037eb30ee5f07efa3af7b0ecb4bc94f.nq.gz
│   ├── 36eb507f2e07b4a756df7c6e1c439782af5cb8de.nq.gz
│   ├── 3951d4ff1f84a594f395ee1b44e3cba5f2c19d3d.nq.gz
│   ├── 3981826a0deb51f66a622679ed00c5960e37fdba.nq.gz
│   ├── 3a37063de7572f69bd449c01fc0de4e421dd08b9.nq.gz
│   ├── 3e66e51163430f62d8b2a251d7f01aa3125e3abc.nq.gz
│   ├── 446700c937ce5f92fd630927b90b9e3b04d4eabd.nq.gz
│   ├── 4e8006c5c23ab048e7b365da5aa3d913e6909dd1.nq.gz
│   ├── 4ecffa41057f59c623f03afdfdf0bbb045062d8d.nq.gz
│   ├── 528cc240eed930b6fbc5931966b59a954789fb83.nq.gz
│   ├── 57d1de2b2ae2d7a16e53be831eb0251bcbfb4519.nq.gz
│   ├── 59a98372d58cece55b2d94c305085404c9566fb5.nq.gz
│   ├── 5e512aeac00e37eeda919ebfe9d2f396f6e53451.nq.gz
│   ├── 5fa334961c32c1c3ba19f212e7209c8d2fde6f22.nq.gz
│   ├── 606849326a4002007fd42060b51e69a19c18675c.nq.gz
│   ├── 6f156b30fe8fbc89a39de7a72a533670167b98bb.nq.gz
│   ├── 727da8b80d2ea2259e8f80eafdc8f3e66a94f578.nq.gz
│   ├── 7d64c3a5b60ce9b3fbc164b723fa1e5aa83c8dde.nq.gz
│   ├── 8c80d2707ee880e3285e505d76dbfb4227ff7170.nq.gz
│   ├── 8c84adcd3eb919f0273d563a6142961e32e48594.nq.gz
│   ├── 8d0a7403ff27eb7152035be97c9967c0220340e7.nq.gz
│   ├── 97d0524a6abbc2a1b87c62d4e7e65dc730f36f46.nq.gz
│   ├── a77982ee3895b78267c40a0bbd67e4cb84c728b2.nq.gz
│   ├── a7f99fa711800919d7637ed31f07a66ceb141adf.nq.gz
│   ├── a958835172dab0e075c40876529d1f98c0c39d3e.nq.gz
│   ├── adbd206ec81d50f1123add76bd7dbed4d2d3f2b2.nq.gz
│   ├── b57ddfe70ef44ca1bd3273bbee29711c20f93e0f.nq.gz
│   ├── b6757bee65005377d2b7ff2ddd477afe56c2cad3.nq.gz
│   ├── b9cc03d0eed2ab05a3da621e7a44f5954c215925.nq.gz
│   ├── bb9161d8a083f8f4b721565d9a958647fc65258e.nq.gz
│   ├── c8316d3cad16fde55b77a56d1cb6d8b3ec909a9d.nq.gz
│   ├── c9e795b70d066137b1c826ed92b217f4bb747253.nq.gz
│   ├── cedbc4cd4e17f9b511133e33540c219f6fabb5c2.nq.gz
│   ├── d0e8e963d4421e64f638dc36cf27f773f6d15ce0.nq.gz
│   ├── d4fdcb7dfa461fbed986c2aeaaa8cdec884bdf61.nq.gz
│   ├── dffcab80051ac8c2b2a5b1df42760ef6d559ade4.nq.gz
│   ├── f698e6936db8d6ddc5e413594b918e71b29f5067.nq.gz
│   └── fe86b8cb88ba784ba5947defbdb17f5ec496d948.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── fdf104d652a1d2b15a0a7af0d9bc91c6331845cc.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 53 files
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

[pythonprofilers/memory_profiler](https://github.com/pythonprofilers/memory_profiler)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
