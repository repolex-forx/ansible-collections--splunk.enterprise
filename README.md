# Repolex Knowledge Graph of ansible-collections/splunk.enterprise

RDF knowledge graph data for [ansible-collections/splunk.enterprise](https://github.com/ansible-collections/splunk.enterprise), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/splunk.enterprise
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 70df46791d114101bafe1d1947d816786c131f7d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 70df46791d114101bafe1d1947d816786c131f7d
│           └── chunk-001.nq.gz
├── blob
│   ├── 010a73c4fceea88e489a8eda94584101e038276c.nq.gz
│   ├── 03be69242da7cef859cfa70dbc358720e819ee9f.nq.gz
│   ├── 05ed6287f5c4b35ff1c74f527bfdbb110ef0ba36.nq.gz
│   ├── 08965e522347c9a7677b5c74918dbc1a98cfd087.nq.gz
│   ├── 120733623e5ba8044a4f31fbd97cd0516d7f57ee.nq.gz
│   ├── 1fdb9b2071cd98b80a81d0a91237c0af1ea047d3.nq.gz
│   ├── 27884c55502b9433ae39e7e215d08186056c0c0c.nq.gz
│   ├── 31368dcb706b75bcac97144613cf8c5b6bfe7002.nq.gz
│   ├── 404bb0c3b0116f36ac336146f9ff031af007172d.nq.gz
│   ├── 41f52926485cae3f864b9cce011be1ef3642fb62.nq.gz
│   ├── 475bcdaada0fec07849a5a4bb6cd60ac026d7c5b.nq.gz
│   ├── 4806e5c6d5f5af1b01b786e675bee4d1cb548591.nq.gz
│   ├── 49302844f1eacab711c16926a0f713293a5b44ef.nq.gz
│   ├── 49c7554d4b2efff8e88120c51a2ac96526c1dba7.nq.gz
│   ├── 4cd27b3cb2f633f1145ba98fd5d8975885caa790.nq.gz
│   ├── 4d9a1d540ee17bdfeba3cfcc1a202cbfd6f6ee91.nq.gz
│   ├── 4e9555dd3b6046e399d0b8171b77e9f4fa3a7535.nq.gz
│   ├── 4ebb95395297a5f3d890d498985015e6d7251955.nq.gz
│   ├── 503949180197d878b760b74a1ae2b975eb2171eb.nq.gz
│   ├── 5081e1c79ca0be9a94fcc2ea2d2d538e7fedeea5.nq.gz
│   ├── 5163b098e014162a9b21dae5f7235f7a2c5019b1.nq.gz
│   ├── 53ed891fa0be59bcaecc71fd742c13d21df3889e.nq.gz
│   ├── 542b09c3752728a97b8fdd3f4657bbecff09ba9b.nq.gz
│   ├── 54ab8e9a14cd5e46a383ae4483e8664ab55e593b.nq.gz
│   ├── 5b70cbd6b2ba5736d7b1f29d65e1f85b774cc877.nq.gz
│   ├── 5d838fad79c10c6ed99b8095a77db0d83cb5d8ab.nq.gz
│   ├── 5e94a88848bed70788b8e700c95e5a0f476ffda0.nq.gz
│   ├── 652949408ec481dc9798d2fd3ddb98249534bf34.nq.gz
│   ├── 740c8115458b12e3a8f24220e718e0b33ef2e16d.nq.gz
│   ├── 783e745d87877c5098c3c8e244bc6b2637e2eae0.nq.gz
│   ├── 7ac266b790e58f00bbb626166075d20545f34507.nq.gz
│   ├── 81f8641d065dd3cd349cba5e49c42cd0d8e82522.nq.gz
│   ├── 83d9cfaad44f506e06f61892feb084409a39ca54.nq.gz
│   ├── 88b39061db7b1b279a66e551797ea879327da555.nq.gz
│   ├── 8ad8271638f730da38a8f5a87978c54080a282d5.nq.gz
│   ├── 92fe7a2b60d6b05cf3fe50cb14be27e09fa85f29.nq.gz
│   ├── 97697711fae3ebb77eba6b1bd291459a853f789c.nq.gz
│   ├── 9ff63b3830cab0da153d421739f0d104da802f60.nq.gz
│   ├── a358b4be1f9ac5e04525d1408dafbe89aaf9f46d.nq.gz
│   ├── a7b162de3576dfadc78fe16d28b1728e7c3ea697.nq.gz
│   ├── a947fdf013c094d1fab17bf5d424afd03db120e1.nq.gz
│   ├── ab051b0b7be2e949c31c5df3d6fd9d05b52e9b07.nq.gz
│   ├── ac4800ce543dc1c388de4ba724c82e033dfb6a5a.nq.gz
│   ├── aca1e0798793c0d6171113057fa7de3f09a20eb2.nq.gz
│   ├── b59f9b844fcd86599041269ff284d20377fa2c7b.nq.gz
│   ├── b6a8e09cf71328cc0ad8c81dd46986dc30fa925c.nq.gz
│   ├── b8efb6f57b70ded19995076bd1e78c96d58f4c3c.nq.gz
│   ├── c0ea5886e81352d5347c38c8fa03e5dae6ea1eab.nq.gz
│   ├── c3e502fb56212f381dfdbfd239978d846b799014.nq.gz
│   ├── c5bd32b9fa2127d7f2978fba844a94203c4fb6d8.nq.gz
│   ├── c76281c9c1c549de8406cf29c46da654f7fd8c89.nq.gz
│   ├── c77c91a907b70246b052ad4ea0abe51f052aa88f.nq.gz
│   ├── d3ad61ae5f43e8e76f0521f195c655ecf9be2d8d.nq.gz
│   ├── d8e72b0c2ebddc0012c637e69930612303d4cfdb.nq.gz
│   ├── e080c26408b0f39bbc31a6586c16015db02daab7.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ead6593908418f87d8c2f6d64ff3e6303d30319a.nq.gz
│   ├── f08f43191b8b85ff1a00ce3bcbfbe470179dfebe.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f3113dd0a9feec711ba19e92ede7cbe96df454fd.nq.gz
│   ├── f3f1d1bae83ba3a8341f6bb4d672dec95e9b05f0.nq.gz
│   ├── f7165f06de17c6411b805048375829669868d00f.nq.gz
│   └── fb273549b80a85f83b82e00ab671c1e1803aef68.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 70df46791d114101bafe1d1947d816786c131f7d.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 70 files
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

[ansible-collections/splunk.enterprise](https://github.com/ansible-collections/splunk.enterprise)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
