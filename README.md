# Repolex Knowledge Graph of metatube-community/jellyfin-plugin-metatube

RDF knowledge graph data for [metatube-community/jellyfin-plugin-metatube](https://github.com/metatube-community/jellyfin-plugin-metatube), parsed by [repolex](https://repolex.ai).

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
rlex download metatube-community/jellyfin-plugin-metatube
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f7c1f336fc2bd3b35b82af7c6e69da09a196e3d2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f7c1f336fc2bd3b35b82af7c6e69da09a196e3d2
│           └── chunk-001.nq.gz
├── blob
│   ├── 068b5178a1b333e89146377e566d46e90d0e44c8.nq.gz
│   ├── 06b4423340450fcc9e74356b5069b954205e1af3.nq.gz
│   ├── 0a65f73fb892fe858bb36fd21efb8fd2942c2580.nq.gz
│   ├── 0b612e94b08300a0bc164eb909e0a66093412a40.nq.gz
│   ├── 0ed31608841e9f33119eb73c82aefd2542d54703.nq.gz
│   ├── 19332ec668745a3f4743f3e33867f231d2cb502d.nq.gz
│   ├── 1c7496376a9c5e4ceed56aaee0008896b43ae0e0.nq.gz
│   ├── 2d8596702479f72eb4544e3a2ef3f016680a76df.nq.gz
│   ├── 303003466ef7cf33b77cf2c918b44d81fddcaa26.nq.gz
│   ├── 30ecd953750ebe0f1bb3f18bb20d4605f9d7b0ea.nq.gz
│   ├── 329a2fb0629c6e357105229c06a218e68f3db9a2.nq.gz
│   ├── 32bd91481ebf7c0e083c2be799905b8cf910f9e7.nq.gz
│   ├── 373427378c0b6b5acf52e70d7c11ccc1c8249356.nq.gz
│   ├── 3e1194eb21b848c75b4014ba9368dab1e7e5fe5a.nq.gz
│   ├── 42c00dcff4b7581b17feee52f650e6f0f8b2f8fb.nq.gz
│   ├── 4dfc01dacb9e0d6d7b397ff29611c86e54ebc89d.nq.gz
│   ├── 4fff0fb234d4b9c12b49fd398071deff32608402.nq.gz
│   ├── 51a87754718b354e1c7392794735611b7dcafc33.nq.gz
│   ├── 52abc8236a9d684d9850bcaff28f2c1570f7662d.nq.gz
│   ├── 5dc6979d035927cc8c74df0a3f32cfcf433e6e9b.nq.gz
│   ├── 5edd1f1b20b4ae3fc4964d375a2ccaaa2a9ca4c5.nq.gz
│   ├── 61c7b12a5ed88bf8e07220f66593e46df578c18a.nq.gz
│   ├── 66233771a961ef0365fc1f10acbfbd82f4ae8729.nq.gz
│   ├── 67cbb1f56d374b60725120467b2b36b36e656aac.nq.gz
│   ├── 7c328cccce70bf91d777de323a001675f3eb9115.nq.gz
│   ├── 7d8fe3ae448db2ae20bb42bb7831b5807a24a0f9.nq.gz
│   ├── 88f0a6084862f4bdc783ed2ea362a84ee5eac501.nq.gz
│   ├── 9468e152d524825c87f85cca92aceb8ece85a774.nq.gz
│   ├── 99e1ce4e4a78b9983806874809fe268e8730ac2d.nq.gz
│   ├── abe37dd3f1c8df6691abf98afe701eb329439159.nq.gz
│   ├── b09d8ff09c6b9c56941e3ccc253df1b8d976c343.nq.gz
│   ├── b3f630515b90f8745dd6a0d098b722af552ffbb7.nq.gz
│   ├── b48a3972cccecf9f3483be177b00aed00f4ddd56.nq.gz
│   ├── b63eb0e3ec6a2fdbff1f60e2fe953cccbbb8e277.nq.gz
│   ├── b98e4129f9cd265b14990267a3b4e10993d95d4d.nq.gz
│   ├── bb065113a4b62f457e0d592e48a284a9508d67b5.nq.gz
│   ├── bbd2d68e3a5b41037d989d62f1f847b9f2dc5b49.nq.gz
│   ├── c5224867662d8fecb13e8c3502be79087bfe673f.nq.gz
│   ├── caf9b4765561e2c4a3169eb8bd8d2b8d174208ea.nq.gz
│   ├── cc7c017717bf91a7f120a3d827f78be6921127fc.nq.gz
│   ├── cc8d04d599a28ed5c647125be4681424e6b5d19b.nq.gz
│   ├── d0358b64eaf9e9481a2bb2670e4817388c2b6456.nq.gz
│   ├── d443886e939a799e978f7de9d62c93266d2cbd65.nq.gz
│   ├── da983cb27f426f3948a41933cfd9c5b68f09e029.nq.gz
│   ├── ef57f9dbe8ab273571c3acb0119ee8713b8f7906.nq.gz
│   ├── f1248dcb51e517fe41cd8123b5b88fe425c24ae5.nq.gz
│   ├── f162ce1317ddbde79c55ea71040c7d359b0f4d1a.nq.gz
│   ├── f5dea71e8f3fc3d1cecae426b6fb7e511cf942ba.nq.gz
│   └── f8b28504178894eeaf75534e2b3e2c36b1135adc.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f7c1f336fc2bd3b35b82af7c6e69da09a196e3d2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 57 files
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

[metatube-community/jellyfin-plugin-metatube](https://github.com/metatube-community/jellyfin-plugin-metatube)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
