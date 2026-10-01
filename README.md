# Repolex Knowledge Graph of Cognition-Labs/BioConceptXplorer

RDF knowledge graph data for [Cognition-Labs/BioConceptXplorer](https://github.com/Cognition-Labs/BioConceptXplorer), parsed by [repolex](https://repolex.ai).

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
rlex download Cognition-Labs/BioConceptXplorer
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 60ed4299ea429195a0a049e24250650dc0086c20
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 60ed4299ea429195a0a049e24250650dc0086c20.nq.gz
│   └── repolex
│       └── 60ed4299ea429195a0a049e24250650dc0086c20
│           └── chunk-001.nq.gz
├── blob
│   ├── 02f20089fb3b024299fcc7f761f253382f35aaf9.nq.gz
│   ├── 032464fb6ec40a523899b8c8a593242f3108a420.nq.gz
│   ├── 0384dce58866ba3cc5c1f87dcd362d2c4921e6d3.nq.gz
│   ├── 080d6c77ac21bb2ef88a6992b2b73ad93daaca92.nq.gz
│   ├── 0db72c5184b03bdfbb4dff8e98d6d5387817d4b9.nq.gz
│   ├── 13a28491c6860533b4e57ba4970590b441d6d4ad.nq.gz
│   ├── 1758f84b1748e37ffb9b20934f5fd2d8fbdc6a62.nq.gz
│   ├── 1d6b2a3b8c2847dc95424a8baf074ddaf5f7689a.nq.gz
│   ├── 20108dc33f0406550e2b3f15cb434e3f7296dc91.nq.gz
│   ├── 254a2b1dc904b34ddbc9e78ff60af92902b56015.nq.gz
│   ├── 274afb71ca7b6d8be730b251d1355676b307f5fa.nq.gz
│   ├── 2a68616d9846ed7d3bfb9f28ca1eb4d51b2c2f84.nq.gz
│   ├── 347344cd23cdc223e736862f66151fe669482c00.nq.gz
│   ├── 41c17934a510af14e4e39eb97f7f6dccd75f3313.nq.gz
│   ├── 4438a8386c71ce30beb2c2ee8a64c78c86a2cb4d.nq.gz
│   ├── 49a2a16e0fbc7636ee16bf907257a5282b856493.nq.gz
│   ├── 4d29575de80483b005c29bfcac5061cd2f45313e.nq.gz
│   ├── 512be86b2618aa8709628a3acfcb7ebc3a4fdeeb.nq.gz
│   ├── 53f2f323591843fd42b7f4afe49d6cc19f13f863.nq.gz
│   ├── 53f528ef202a11909aa1d6eaa8540945a60a8e66.nq.gz
│   ├── 542670669e6215ec1b9a2cea12324a8a5b0f2b1a.nq.gz
│   ├── 6431bc5fc6b2c932dfe5d0418fc667b86c18b9fc.nq.gz
│   ├── 667fefec250e3187045a7141846bb1307cab746e.nq.gz
│   ├── 6b09b55d18ea2c1d08198d186a85594987746e6c.nq.gz
│   ├── 7177ebc59f09a89d1c87e21b7e0aac788826b190.nq.gz
│   ├── 71d4abc84f340ba2af8d6b00aedc245e17ae52d1.nq.gz
│   ├── 74b5e053450a48a6bdb4d71aad648e7af821975c.nq.gz
│   ├── 858aabe5db9f0db8ea72ca567e6a61ed62c086e1.nq.gz
│   ├── 85c24dfc4e40447aaade847ef3017161ba3f9428.nq.gz
│   ├── 8e7b504373131cc62ce777c42d8ea82083f35a29.nq.gz
│   ├── 8f2609b7b3e0e3897ab3bcaad13caf6876e48699.nq.gz
│   ├── 91f649ac3634c94dafbc1ea7363cd21d8de214ea.nq.gz
│   ├── 93be33fae575e04ae92180b9ab8db706971b2441.nq.gz
│   ├── 9dfc1c058cebbef8b891c5062be6f31033d7d186.nq.gz
│   ├── a11777cc471a4344702741ab1c8a588998b1311a.nq.gz
│   ├── a273b0cfc0e965c35524e3cd0d3574cbe1ad2d0d.nq.gz
│   ├── a4e47a6545bc15971f8f63fba70e4013df88a664.nq.gz
│   ├── a53698aab3c66049c61980112dd0109dd2cd0845.nq.gz
│   ├── b0b4c802ad7a80251828341646b60ca5a48878ba.nq.gz
│   ├── b3f38f5ac4f67a5ea5d9893ce12fa12c96b752d8.nq.gz
│   ├── b40a98ef518e590689e7a0684ab0a454289045ff.nq.gz
│   ├── b58e0af830ec5dbc90534e641396406fd17bf11c.nq.gz
│   ├── bbd69bfcd839ac9085075120c8f5eb97ce79e6d0.nq.gz
│   ├── be2b7434d1f8d6b4ad1313d2b1b37c0a3b03b7b7.nq.gz
│   ├── c732e6ca5328fd42a2743039ad8d7cc2aa70acaf.nq.gz
│   ├── cc9830308ca572892472e5655366309c774ab505.nq.gz
│   ├── d360c21d066f10e7ae56aa89308541c8e84c284e.nq.gz
│   ├── d557b765ea7718fade0dc06918f73e73317d9ad5.nq.gz
│   ├── de19a91b091284b8a96004bbb6e840ed3a7ad3df.nq.gz
│   ├── e043eca1f279402b8b8cdb82d1ef2ae77c2aaade.nq.gz
│   ├── e18b0978ab0a74f01e26200947dcd26ab36e2381.nq.gz
│   ├── e2867476c6fd4b54a649b6f53151f04d3cfdd64c.nq.gz
│   ├── e40b80196effa2183d1a30abd2610e20caf7aa9b.nq.gz
│   ├── e5f51c7e8f702127c796df82647342c0f0b793ae.nq.gz
│   ├── e7725d1302f24db773a9a9fa1bf4010ecda93f63.nq.gz
│   ├── e9554b62912ac4baa448e0f394ce24d6f8ba84e4.nq.gz
│   ├── e9e57dc4d41b9b46e05112e9f45b7ea6ac0ba15e.nq.gz
│   ├── ec2585e8c0bb8188184ed1e0703c4c8f2a8419b0.nq.gz
│   ├── f6cb95daadd3fa1b3429c8e36abaf5538fa7285e.nq.gz
│   ├── f707f966de3e864fd83d0253513e32f6bd7afdee.nq.gz
│   ├── f9f732972fda3f21361c89d9a37cff4717df498d.nq.gz
│   ├── fc44b0a3796c0e0a64c3d858ca038bd4570465d9.nq.gz
│   └── fd2d106c8b20216c1d2dc52b82380e80db4a0d18.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 60ed4299ea429195a0a049e24250650dc0086c20.nq.gz
├── filetree
│   └── 60ed4299ea429195a0a049e24250650dc0086c20.nq.gz
├── issue
│   └── issue.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 72 files
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

[Cognition-Labs/BioConceptXplorer](https://github.com/Cognition-Labs/BioConceptXplorer)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
