# Repolex Knowledge Graph of UKPLab/acl2026-generating-impact-summaries

RDF knowledge graph data for [UKPLab/acl2026-generating-impact-summaries](https://github.com/UKPLab/acl2026-generating-impact-summaries), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/acl2026-generating-impact-summaries
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2ef0c424b2defdc0f114a4110c4bca8d1489da02
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2ef0c424b2defdc0f114a4110c4bca8d1489da02
│           └── chunk-001.nq.gz
├── blob
│   ├── 08dec855b6c0cbdb752137a28549f506b21f15d3.nq.gz
│   ├── 0a4fd8c1c2fa2815dd540da5bf8b131504026947.nq.gz
│   ├── 0d03bf268c448d14aeb9becbc045bcde4ae6c9b7.nq.gz
│   ├── 20395e7adef39a27ddd233862526079a0cba7f10.nq.gz
│   ├── 229edba242bb190698662cdce6bdacde9f0769fe.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 291e621e686ffdb59ef69cb2d650c1f4b1040d53.nq.gz
│   ├── 294c0697f322f0e405266eac98fd24910b7b625e.nq.gz
│   ├── 294d667d472b8cf85a697af6eaa9d5da7615e8d5.nq.gz
│   ├── 3048acc7b5699d7a8bcddfdc7df2a074395c3b74.nq.gz
│   ├── 58da86eb4a8826b1f79c4e5e85234d5ea309317c.nq.gz
│   ├── 5ba6623360f111ec31901aa94dffe810cba1dc93.nq.gz
│   ├── 5e9bf9c65b49be320034171fcb1b7fc4ac8508a4.nq.gz
│   ├── 68d3d286aab2421c3cb2f7a7003b0d2ccf26bdda.nq.gz
│   ├── 68fd3f261bdfdf122af14ee23f0d3a65e7e3669a.nq.gz
│   ├── 6cc5f1376c81f08f1ed8a059f99b3d9c8e6e98b2.nq.gz
│   ├── 6d5fe0e142d980fbaaa7834682cc37a9be7414f2.nq.gz
│   ├── 7314e8c38b34600d9b7f02a869d40fb62a434796.nq.gz
│   ├── 7e77a04d5460aae955ea341fcf174d9fda988998.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8f9058a5c298bbdb3f589ae3646e2ebc08f416d0.nq.gz
│   ├── 904860719345f8bf671b129669367fc75f2aa4e5.nq.gz
│   ├── 94a0ec8b1b1e4226fa0f4bd9e853902fff7f6769.nq.gz
│   ├── 9a38fb045e8d89a1e99c36512dfb155e9499d674.nq.gz
│   ├── 9ef58e9b97b471bf7d3ec406a3778df788a771f4.nq.gz
│   ├── a45f036b093c376e02787dfe7ac97b93f66fa59b.nq.gz
│   ├── a617d1aff3331e560dc64aaf183eaf4d1da84b91.nq.gz
│   ├── af9dfc46adeb0b4723e5e307fd9799e3574839ec.nq.gz
│   ├── b9ff2c28cffb269c690b0ac1d30addaf4e7a64fe.nq.gz
│   ├── ba18e37c97cb2b6855a785a5ba4e812f3ea336fc.nq.gz
│   ├── c08a79032592be8f5e7318991b0242323389469d.nq.gz
│   ├── c242a925d543f9930e264a43046846c3a4aabf73.nq.gz
│   ├── c6718de5c5ae59d2c22141a147f5afba41af9cbb.nq.gz
│   ├── c75d3c44e725df8d40e1173d1ebad99327486513.nq.gz
│   ├── cf94adc5011b99f3b795327dfb229406b631669f.nq.gz
│   ├── d44029da0188899bc192b4a6922c894bbbd5ed00.nq.gz
│   ├── d514709aabb1d689834fab585f4f4364becb5869.nq.gz
│   ├── d59183e640bb0a86294ea28e1e7ea5a01f485777.nq.gz
│   ├── d62fc66df4b9acdd5381753fde4173a5775b1ddf.nq.gz
│   ├── e0e7b3839e3ba145c60c2f093090628e29844719.nq.gz
│   ├── e52e976d15559da231c2bc6ac0262396f491a784.nq.gz
│   └── f96d334d4faf5a11387eb29c238cae90ff8cc2da.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2ef0c424b2defdc0f114a4110c4bca8d1489da02.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 49 files
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

[UKPLab/acl2026-generating-impact-summaries](https://github.com/UKPLab/acl2026-generating-impact-summaries)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
