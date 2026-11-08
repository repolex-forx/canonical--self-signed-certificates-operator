# Repolex Knowledge Graph of canonical/self-signed-certificates-operator

RDF knowledge graph data for [canonical/self-signed-certificates-operator](https://github.com/canonical/self-signed-certificates-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/self-signed-certificates-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 782770e0a71c2bf7648d5280a0d08f6d43fa64bf
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 782770e0a71c2bf7648d5280a0d08f6d43fa64bf
│           └── chunk-001.nq.gz
├── blob
│   ├── 0124f27d851dca57886af88a15fd715ac2be2ca6.nq.gz
│   ├── 0787d4cb6c0b7c67b26427ce04b6d5f8fda1bca4.nq.gz
│   ├── 0a979cecd4d50bd8e260fb23f7e66e7fbb1fa14c.nq.gz
│   ├── 13af703428e23ce7d56cf7a1bc7061b64a8f6a18.nq.gz
│   ├── 161dcb887d2829af95cdef2458c1a9acab2b03e9.nq.gz
│   ├── 2045502c4f0f0932b6f02950782a65f1914044d8.nq.gz
│   ├── 209b594e821c9885e609d877590fa64803e13b97.nq.gz
│   ├── 38ac36a583219a9ee75b5498006e1d2f8e4792e7.nq.gz
│   ├── 3973668891b5a7ec3675794357780ccb915ce277.nq.gz
│   ├── 43fb7928e83659ca847daa849525ba916ee269df.nq.gz
│   ├── 4486f30efd244db7d8cdfb8165989e79f9cf069e.nq.gz
│   ├── 49ceba4747b08695b69b9ce4836d4e20703af4f2.nq.gz
│   ├── 4cda9e4b01972b5bcb4f0364e5d9ed397945cd3f.nq.gz
│   ├── 57a959f5e9ef48dae796e72c5f1d024ad0d75b21.nq.gz
│   ├── 5ed66d97990120b1eb2f1ca39ec08a7c84174f09.nq.gz
│   ├── 5f01f58fc93b104e347e9441797ee59f071b2060.nq.gz
│   ├── 62501b21dfadbedb0d6e9eb392a0df5f5838cc74.nq.gz
│   ├── 6da5605f63c08097a851eb4c88728e8f1358b1df.nq.gz
│   ├── 782cf0ca55eb1d5b509366cf6d9c045f9a38617c.nq.gz
│   ├── 7b769be04c46bba9543efa14e1e6d4046468fd42.nq.gz
│   ├── 8816255a258384e63bc09be4eb68a8295c011373.nq.gz
│   ├── 88b0e7af1382409234807f3db3fdabd57ae557f4.nq.gz
│   ├── 8d4330a366722a069b5d5d47c873aeb6790b3bd9.nq.gz
│   ├── 8d771e187ba4b2ced1b643c804548e5c014bab70.nq.gz
│   ├── 8db6fffad8d7ef7d6b92a6b9f303b1acbd644f0d.nq.gz
│   ├── 94af9f85d7d16735d00569b02b91efd69aba6fd6.nq.gz
│   ├── 9712918895e8a1b0a4748bcbf0756bf7a172d801.nq.gz
│   ├── 9bdec77ac5b29e31199d9f45b0a26f8714ffe787.nq.gz
│   ├── 9ca56a8830a92c94a3be6a6aeb3dfe77d9cd869b.nq.gz
│   ├── a01af04de542d8b61d8beb043e196b0a2f23e807.nq.gz
│   ├── b0af6bc9b4c595a6f5e69e1d186c5a381597ce12.nq.gz
│   ├── b9fbbe1bbe45afb706b0bce3f1bbba3d04bf1f30.nq.gz
│   ├── bc948a752558020b38c14348979f501f7895ec0d.nq.gz
│   ├── cccdb2ddbd289cdc22784a294b4313dba4dc306b.nq.gz
│   ├── cd48f83f014a8471d778fb16516908322edf504d.nq.gz
│   ├── d2a2b966b53037faa85d0293f1f6b42e7ffc23d8.nq.gz
│   ├── da6949321228c52a272cdf9cd095ef336f65050d.nq.gz
│   ├── dead8577361c1005b70aa5cbaa5b85c83dec8a11.nq.gz
│   ├── e3994ae1b380085a8d146276772fc6b3bb752863.nq.gz
│   ├── e654f19d857731f1ed2ae76b5da054aa2108ccd5.nq.gz
│   ├── eb4133ab4e6ef7325e9c6a83eab357971e68b2ab.nq.gz
│   ├── edad3ff524ed5cd262f89be973645f3f29b1e0fa.nq.gz
│   ├── eea91459ea41c97e0554b229bd4be0ce17db4692.nq.gz
│   ├── fa6c4c4242ddde9c12673e4e2dbd1fe818b4c73e.nq.gz
│   └── fbbf4caee883abda797acaafd4b7be12a8101306.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 782770e0a71c2bf7648d5280a0d08f6d43fa64bf.nq.gz
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

[canonical/self-signed-certificates-operator](https://github.com/canonical/self-signed-certificates-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
