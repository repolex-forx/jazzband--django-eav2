# Repolex Knowledge Graph of jazzband/django-eav2

RDF knowledge graph data for [jazzband/django-eav2](https://github.com/jazzband/django-eav2), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-eav2
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3cc8e8fcc0f342ff1173145e3b704a5a25049737
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3cc8e8fcc0f342ff1173145e3b704a5a25049737
│           └── chunk-001.nq.gz
├── blob
│   ├── 01543a9bfaca3e9ca3e53a0ccd8e795ea3a46703.nq.gz
│   ├── 06a0a8690a15e0da8be172ee34bc5a91b7c2dce3.nq.gz
│   ├── 0741fb28e77e2bb581723eab3e79b0cf707c8403.nq.gz
│   ├── 1b62b90a423403f17f38dd8228c201a4d46f6331.nq.gz
│   ├── 2b4d23441cad2ca13d6aa63aeafcc7c2b81ef399.nq.gz
│   ├── 313036286588412a0d57ce957e7e0f730fd16d8a.nq.gz
│   ├── 39f1b881670d7bab1657670581f715cd64b613a4.nq.gz
│   ├── 3e49d90ff72480c30d4f3fb1421d80829eac3aa1.nq.gz
│   ├── 3e5736217740b7270826d70c1acddac1b1d4b6cf.nq.gz
│   ├── 405c05890b94bd5aae87e284f855229c102a6289.nq.gz
│   ├── 4141c09654713576bb7f7968a1293cb9d8d250de.nq.gz
│   ├── 43f6000604ffb03824bf64ed2d15e61840694e69.nq.gz
│   ├── 47cb3b2418de1b6e6f607853a7d23e27e8c3ecfe.nq.gz
│   ├── 4aefd19e75162fff39d13599889878fd2193a0de.nq.gz
│   ├── 55ad84dab0a9414b0362e94993d1b5751f43c6d4.nq.gz
│   ├── 57a03c90f2ae96ff6e3e624eb92f03877bbe2b56.nq.gz
│   ├── 5984f88a4d6aabf7f5792989f4ba471639776be8.nq.gz
│   ├── 5a95237b3a722a0010e85945e008e096b8b195f9.nq.gz
│   ├── 5ac9db86514664b0ff221d383ccfe02eb65b2292.nq.gz
│   ├── 5d464b0528c5a084d6cd93655ae5860a27a3d519.nq.gz
│   ├── 5e84aa5e760e528df85e196cb50d0e5f66f624ec.nq.gz
│   ├── 60b68e623f2246bafbbe65199c7a1482f6e9443b.nq.gz
│   ├── 648ffd9fe936505d25cf3e9392cd85627e22354c.nq.gz
│   ├── 67f49ab9c70c11df04400351e7ad87a00091787f.nq.gz
│   ├── 6bef57f3fe7175dc18aba2a3e053fda74e6a0d9b.nq.gz
│   ├── 7544c5762f0c9ea612493f442614842fa1d638b4.nq.gz
│   ├── 75b52484ea471f882c29e02693b4f02dba175b5e.nq.gz
│   ├── 75e82656e15ebac8eacc5f1a43306c2dd922d817.nq.gz
│   ├── 78480de55fb6b266e00abd312d2441d5cb37b5eb.nq.gz
│   ├── 7865cf8069eb86df9d69b1f6b4d7c171c5c5470f.nq.gz
│   ├── 78e3ee105e385db019b2845b796be6297dc5df26.nq.gz
│   ├── 79d0a7c9fcce90c37a31547fbad7de1dc2d1e683.nq.gz
│   ├── 7bd7720b4676842e5489cd55a808ea62fab018ad.nq.gz
│   ├── 7dcf0c9bca830e6f866eb4f0226762e8a1a0cb4a.nq.gz
│   ├── 803727fc112b2736ac7adb99ff7f3fa8a0279a73.nq.gz
│   ├── 8182881d8f99b4e2e14a27a2afc49df88905d6c3.nq.gz
│   ├── 82b107c2d257a2f6beb0b30e116ac64fb494dc07.nq.gz
│   ├── 83e9f5c838f5a0e9f0754f5ae6747e271abd3c91.nq.gz
│   ├── 8859bdc687e8fbc97a65033f862f4be071fe7c5f.nq.gz
│   ├── 895e6e4db8f5ec7d23d8c9f664ec3a2fd960f036.nq.gz
│   ├── 8977fbc41df571d35a93a39c6c3cb0230009638c.nq.gz
│   ├── 8a7cc4db83877af304aadd22ecd3975ed70a05ef.nq.gz
│   ├── 8ad4999c40eaa4f209070888badfe5aa15adafcd.nq.gz
│   ├── 8c5f057c05a9425e6e8111819926460db8a334e7.nq.gz
│   ├── 8e0282cf5f571012093b85d9ab43006a08d931c2.nq.gz
│   ├── 94397ee5b66e962b9e2c43f98674ed67e9407e34.nq.gz
│   ├── 952d586bd0513a46d575ac1453fd1d1905f52501.nq.gz
│   ├── 9595043494a46aac8b8f9aafd38bf1ce195fa9e0.nq.gz
│   ├── 97cc16c0d9abc9b87ac35417132f1abeaf511aaa.nq.gz
│   ├── 9a9d8634df9a6abdb2cccd735a0087ee827ca4ba.nq.gz
│   ├── a01a1c310ccda507092f2b486d46bbffbbb9f874.nq.gz
│   ├── a2c67c08766586f07971be51f18c1e6fb492f7eb.nq.gz
│   ├── a4ff61187facf2900f907b6838baad84d3de071b.nq.gz
│   ├── a81045ebf94a42c7265479cfe600c38c4b57904a.nq.gz
│   ├── b1e9bb19951db314436679ed8d05ff18ff4c39fd.nq.gz
│   ├── b54fea5d73c1e5b4c219a821a223c3758211a0dc.nq.gz
│   ├── b7d05aa98137337c675d150b1d2d94a2eab71785.nq.gz
│   ├── b7e39b5e60f24a610ce8050b2870b6994caf4a24.nq.gz
│   ├── b87d8c48116499c3b4c3c363d73eb8215166d1ee.nq.gz
│   ├── ba24fa05776c2fa49822e14f176bc33a55ab0d42.nq.gz
│   ├── becedce554ee45def8e799c19c6b0231651e2ce2.nq.gz
│   ├── c57ac4af9b56d8c3c4ba59f2dc092c5b22c2091a.nq.gz
│   ├── c678c3683c9e00aa6f10037b9dcbd858a35ae071.nq.gz
│   ├── c71b9bfa8b523960753e08d92187b529493330a4.nq.gz
│   ├── caf81c529c9facea24f672f5873bf3702530872d.nq.gz
│   ├── cda89e8433e15b87e112af83f7bd1efd088dc933.nq.gz
│   ├── d19478ef7e91fd303776b6ad0c9b9ab9a892c4cc.nq.gz
│   ├── d7e8db514054047c8c92c2a1616aad76a32a9171.nq.gz
│   ├── e00cfd902e47876e4484f5b064aef26b88af94fb.nq.gz
│   ├── e0d5efab56fb94577e7804603eb6f21f36977cb2.nq.gz
│   ├── e1606e1f99ef34c7bb187188169b03c7110623f2.nq.gz
│   ├── e62b42f26bbfd1af0082b4b198258b56943725ca.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ecae25b2e0d1d7964da55c6a0cd73a7642771541.nq.gz
│   ├── eddd1043d0061bb61a70c37b914fa776238245a3.nq.gz
│   ├── f071031a3f901a97b89722eaec10da888a80e8a2.nq.gz
│   ├── f3e81e2af182e209f485fd95f1cb3761e17a1ffa.nq.gz
│   ├── f9f2e0baf7781b73a48589568603c4b9a63d1978.nq.gz
│   ├── fa09417d1d3ef430fb2c62d0f926d1a00e150861.nq.gz
│   ├── fbdea4cb525285270e6fe4167392d1c47258a2c2.nq.gz
│   ├── fc11da235d37900392a0a344a8aecbdf71c2aca8.nq.gz
│   ├── fcd64e7df122c1da9c0d84c5ad6508e47cd64718.nq.gz
│   ├── fd09cee15abcf47b249bd4990ec13b794a311d51.nq.gz
│   └── ffe74251175e27f8f3d779da5223f05cdb910572.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3cc8e8fcc0f342ff1173145e3b704a5a25049737.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 92 files
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

[jazzband/django-eav2](https://github.com/jazzband/django-eav2)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
