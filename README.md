# Repolex Knowledge Graph of litestar-org/api-performance-tests

RDF knowledge graph data for [litestar-org/api-performance-tests](https://github.com/litestar-org/api-performance-tests), parsed by [repolex](https://repolex.ai).

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
rlex download litestar-org/api-performance-tests
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 956b96c0ce4015703704fac84a1653207445cc31
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 956b96c0ce4015703704fac84a1653207445cc31
│           └── chunk-001.nq.gz
├── blob
│   ├── 123014908bebbfb7ecfa1d15daaceb272fabe05b.nq.gz
│   ├── 130a0d7f5632b8fd94cca2465818b324db3978db.nq.gz
│   ├── 136f6e2c874146c861d4b595dea5f90e0d993504.nq.gz
│   ├── 27155421b0210285294660c435b40c200c40d4df.nq.gz
│   ├── 2c011d2e52a0018ccf50586f3e48218d520a9423.nq.gz
│   ├── 2fda1f9ba2d7ccf666a546e67aef9704ee41c92c.nq.gz
│   ├── 30f4790d3bd4d500437dce5bb1f12e49667b7ad2.nq.gz
│   ├── 35573d5e48f11eb39c037c8a1dec837d4e4fa0f9.nq.gz
│   ├── 381530f68bea1e14e639166195b7ca753e39911e.nq.gz
│   ├── 38d142be03fc84329afb21b9b9811fca1187c3d3.nq.gz
│   ├── 39809fd638a800ef85fc8abfc61219a798e83020.nq.gz
│   ├── 3dd34a5129f447ea78760559259b8cf49d4abda3.nq.gz
│   ├── 3ed5b8ea09d82f706fe91cd8c9764cf408db75fb.nq.gz
│   ├── 44a1d770938ae1c871e018d417049a53b146e15e.nq.gz
│   ├── 4aa565fa6a83a858664ae260e2d71b654e23edf1.nq.gz
│   ├── 4ce020ad1c672cfe0b89c236a0805371c8ac9be4.nq.gz
│   ├── 4d3604f112a8496a3ac946a978811c9b7fa91615.nq.gz
│   ├── 4ef03ecb6056712c1167354bb9c08a9baaa5ec8d.nq.gz
│   ├── 55313990139b564cea5488e02b61da085c3bec02.nq.gz
│   ├── 56938454941143bb36c1f2ff040273886e3da052.nq.gz
│   ├── 5c3d88bc4663472ad3b190f08a40c63a2022a5d7.nq.gz
│   ├── 62d3f5d1b5976861a2c2b6d047abccae2122caa0.nq.gz
│   ├── 62d6e9b8798b06adf4d8330aba0251d0be6bec39.nq.gz
│   ├── 682b814197abbeb13415127655224d317b9bc189.nq.gz
│   ├── 6b5c1b48d2e5539c4126cac6b5752d9cf9a93ad5.nq.gz
│   ├── 6ba2605f653200ef943f7fd31f25b7135fadb439.nq.gz
│   ├── 8001269b0bc4c4d8758f8b2d53d7a59e8a675b8e.nq.gz
│   ├── 862a89e316432681a7a6693970908cebc610a168.nq.gz
│   ├── 86a09eedae93e5e8b44361bdad1e8826fc667733.nq.gz
│   ├── 87744f9d39d0d610591c67642de0b643b37a4b93.nq.gz
│   ├── 89baaca36c927557172857286244df78023524a0.nq.gz
│   ├── 91c3aebf75385d483aa95c369e85323dca2c0bc8.nq.gz
│   ├── 97550d1249ecc4f8f94fb1c4a054d13171d21264.nq.gz
│   ├── 98dcca0c2836ae53d67260be8a5431b855e461bb.nq.gz
│   ├── 9cfc77a748d3262794600b83338709e80895cb8a.nq.gz
│   ├── 9e9afc3d4caf1adc02f56e3619f59715b43f4840.nq.gz
│   ├── a0fc9848fad580948bc18559ea05b4ae743b8bd5.nq.gz
│   ├── a7536abc9e3f21f8606ae6dc4bb344cccfa691d6.nq.gz
│   ├── abc5ea535ab5e6176f7872e7698506c967cb0278.nq.gz
│   ├── b0fd28e5e58b4488b6333dfc36f6af6cbf1e677c.nq.gz
│   ├── b10122c51112061f2eaa01e8a084eeb9726c4eee.nq.gz
│   ├── beecedb467c08568f1db81bb804ca24ca27e100d.nq.gz
│   ├── bfac0909289edd0b233083bd4d84e13e3af49ccf.nq.gz
│   ├── c77c069ecc9b7f8b1f97dbcfec905725db0253a8.nq.gz
│   ├── d6484118314f79c4fd356658ce44642cd0680603.nq.gz
│   ├── d7c75644901a7eac7a2cb1cc1df17b8978ce0621.nq.gz
│   ├── db225bd3d51966764a983c8976e513a1feb5e483.nq.gz
│   ├── dfbe81576465df84853915015aee201f7167956b.nq.gz
│   ├── e1acea6dbf30fd3f866f57ebb17798e82d2ad7f6.nq.gz
│   ├── e6935faa83e2a71b4622852002e6b0b09f4bf45d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e912d9c5fa88fb4ca8fc7d7d568ef37880e1f999.nq.gz
│   ├── eb1579f2609937efc1de1e21b9032a0df1e22b42.nq.gz
│   ├── f57a6e225a9b2d67da97a99ddd786686ddac387b.nq.gz
│   ├── f57cf620295f18c0456a7a7c2d69bc298e376cb8.nq.gz
│   ├── fa1ba82cb883439039617df36926b6827aae3c74.nq.gz
│   └── fb86b9cd9899c91bce4c7a82598c89f7af9ed0d3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 956b96c0ce4015703704fac84a1653207445cc31.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 65 files
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

[litestar-org/api-performance-tests](https://github.com/litestar-org/api-performance-tests)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
