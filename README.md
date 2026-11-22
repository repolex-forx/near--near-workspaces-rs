# Repolex Knowledge Graph of near/near-workspaces-rs

RDF knowledge graph data for [near/near-workspaces-rs](https://github.com/near/near-workspaces-rs), parsed by [repolex](https://repolex.ai).

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
rlex download near/near-workspaces-rs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dc729222070b508381b8dc81c027b0c0e6720567
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── dc729222070b508381b8dc81c027b0c0e6720567.nq.gz
│   └── repolex
│       └── dc729222070b508381b8dc81c027b0c0e6720567
│           └── chunk-001.nq.gz
├── blob
│   ├── 03c56a0c977f1c9682116019ddff50bdc27fbfc6.nq.gz
│   ├── 04c0db7734a41c96c43965da9326245065f3e941.nq.gz
│   ├── 091f37862fb47551a34555187d9ad800bfcb4d3f.nq.gz
│   ├── 0aace4afe8e9826e56fee7ed1fb8fe53e6791a8f.nq.gz
│   ├── 0dd4af6f5ecc86762939860bea9040af3c55ed6a.nq.gz
│   ├── 0e719d3dfe9097f7bec54c438a9f734f7396036d.nq.gz
│   ├── 114dcc92b4c4c967225f1d0bc74a79ca4cce74a3.nq.gz
│   ├── 13d465aba14f41951f58d8ad0f239f8fe15ce214.nq.gz
│   ├── 175ed801eb872c75c5d5c3bba767ffaf73a41d83.nq.gz
│   ├── 18081b3522043f3decb42f76f7114be6990b8440.nq.gz
│   ├── 1945415466fe9a01a71a234a07320508e0088a7a.nq.gz
│   ├── 1deb83060045e92e8326cc6b2593c33d2729e98d.nq.gz
│   ├── 1ed23e2d94990ed56902d676215951d2f421e429.nq.gz
│   ├── 247013ac9978829ff897d26a9e9816bb5a10920f.nq.gz
│   ├── 2898dce529acf636baa2588e49028f6e109fd20f.nq.gz
│   ├── 297a1deb36233b48cad415086b12388b4c71a43b.nq.gz
│   ├── 2b57811ed571daaad9829ecd47aea5f69d54312a.nq.gz
│   ├── 2ba2e91d779fa612b384c312d0b48dcdc134550b.nq.gz
│   ├── 2c93e7fb001c55320e2b155b3739f357742c8c68.nq.gz
│   ├── 2e48e4411251bb5083e7d31c91a81bb4ed8d0148.nq.gz
│   ├── 313f4fda3a2917739b9a76b770a57c33dcb6d0ef.nq.gz
│   ├── 32833cd8b60580bcd3eaa8bfe2670ede08856959.nq.gz
│   ├── 32d46ee883b58d6a383eed06eb98f33aa6530ded.nq.gz
│   ├── 3706c406bf081393000ac12ad6ef5e0d93d69903.nq.gz
│   ├── 39db8abee6bc96994a690a234a906f84110d0c1b.nq.gz
│   ├── 3a8b691aab2f5b20d8d99ee1ac9dbb2a90649e25.nq.gz
│   ├── 3aca8277d12d4eb4ef8363c317b201d4435433a5.nq.gz
│   ├── 3cf7e1f6eeb71c57754546074ee814693b596099.nq.gz
│   ├── 3db45e1419394bf2177518bd03a71899007cb146.nq.gz
│   ├── 424e0a1d0b6b64eff99649fa8a03c771ae69962f.nq.gz
│   ├── 4331ed94dfc5e303e669038627e5f6af491cd019.nq.gz
│   ├── 450fb8729871ed65566bbfb2645413c2ba531ffe.nq.gz
│   ├── 483cb6aa4d5fc19defbc9e87849775f3916eec9f.nq.gz
│   ├── 49c0a26aafe2146951f4d7f422b13d71013b5406.nq.gz
│   ├── 5896551663967e8a1ea98e74cc8c32e644d22900.nq.gz
│   ├── 5fdff6408e80ee2081d85355c811acd0e1817222.nq.gz
│   ├── 60c1e3e1ab8db24e6f8847af3a3852ecb0628072.nq.gz
│   ├── 6168409fa467b991f50e21744e6f99a1b423b8b8.nq.gz
│   ├── 61bc10a92fe02e683a338af6dd93015bf442b2d0.nq.gz
│   ├── 62a6551cf5160503919bae0f54f0ba348cb30557.nq.gz
│   ├── 64e6455901bbc4bf8aa4ec32e9f67cef982da8b0.nq.gz
│   ├── 658d91d0f10f7f4acbc02cac4450d885142c7ccc.nq.gz
│   ├── 65ab75722f184f40f972495c29cdcb829185d2c1.nq.gz
│   ├── 69b6a1821724cb5e91ac60337403e5ab77fc8611.nq.gz
│   ├── 6a2416a4703b255999da0cbc4901047dd6719289.nq.gz
│   ├── 6d363072e211620f3e1bf2a1cd791882a0b46c5b.nq.gz
│   ├── 6deddd091f3f5ae4d862d4ce353a6580e0ed990d.nq.gz
│   ├── 6fc9978d02c83a8e52efeddf7ba57a785d9c3b99.nq.gz
│   ├── 749aa1ecd9bd558a60d45bfdd304f7d2c86e0ae9.nq.gz
│   ├── 74e1efcdd669fee57cb736786a169707d3bbeda1.nq.gz
│   ├── 785c9ce9be700353badd8daceab8abb7cb995a3f.nq.gz
│   ├── 7a070af4aa72db4f76de61f579610a3291d104fb.nq.gz
│   ├── 7a9d39107a725cce4f34571e9392bf87375b8d2a.nq.gz
│   ├── 7b7e88fe2e10cc68e0ec88b89893f22fe1577391.nq.gz
│   ├── 7c9828ac16ea56d94ed7e8ebdbb18cb7a8d9cf46.nq.gz
│   ├── 7ce19206aa3e79e138d755f7fa7d81a0ef85c289.nq.gz
│   ├── 7f04eafddf328a435330de7b5eb7b5e42029c115.nq.gz
│   ├── 808e64e8901e7348671097610d6b5e23778dd579.nq.gz
│   ├── 8299b968581871a955c8937cada424a9584fe160.nq.gz
│   ├── 82c3849d6fcf90aa2931bfdf53ed2b95207a1531.nq.gz
│   ├── 837fb3e2ca78b25a56c63d029c526d2d4fdcf487.nq.gz
│   ├── 8aa770d05de853059947d04a6a03520d19da8ed8.nq.gz
│   ├── 8af1c5b6056fe3d81132c8f563bee1a7015f5014.nq.gz
│   ├── 8f55eb9ff13dedaf77bd6507418eaea4bcec352e.nq.gz
│   ├── 914181efc742d0f81a611595333179f9fbc3e77c.nq.gz
│   ├── 936a36dcc7207a235436b7a34e6c8ff64718126b.nq.gz
│   ├── 96a2b229cc0c957627ce1ed813d32deb5ab03de9.nq.gz
│   ├── 98fbf96088b00fb4588e5882313e39209685cf39.nq.gz
│   ├── a2986ccd1baaa2692487310a842ec6d2f3843837.nq.gz
│   ├── a3d656f08f16fb1dd14b88c182a8d44b994cf571.nq.gz
│   ├── a7eda8cd714b6422ef3e38ab1eca4be2b7fe2003.nq.gz
│   ├── aa83e309c9b0d1d477ca8ead5e27cdcfa06d009d.nq.gz
│   ├── abefeddb4814a956ae9ab4379818118dacd83dd1.nq.gz
│   ├── adf0452f0d875e366132dd00ec0fe44b1b94b8d2.nq.gz
│   ├── b3e83f2b48deded6c1bc9a84ec3385673b3e38b0.nq.gz
│   ├── b52e16a4a051b60dd899c8aa87f40121b8d2253f.nq.gz
│   ├── b7e5056af2d7b84ed7ccad0ab02c7dd8c7463f49.nq.gz
│   ├── b9aa3c3eb2bbea42d212eb4a4f98c0f1d2a0f7d1.nq.gz
│   ├── c12042f66a93d0aee767d3d5b6a145da35634407.nq.gz
│   ├── c320abae621b7545c172633dcbeb695ad4fb4ec4.nq.gz
│   ├── c4481576e380e0dba7c458de4e8767de8a06b7ba.nq.gz
│   ├── c47296aec4c4e646a1d379a01ae1925b8455bcb4.nq.gz
│   ├── c957d7e3b89da80b908164e6286a16c75c4f6b54.nq.gz
│   ├── c9fc926b23380a4c8c8d4f49a42c476dc1fe1638.nq.gz
│   ├── cbdcd16b84e9070cb6c11d2495b398a2d5edd646.nq.gz
│   ├── cc605de62041d6b7203619f702d60fbbf513c9b6.nq.gz
│   ├── cc630a51202b1fb5e58311d5e3654af6d340ee9c.nq.gz
│   ├── cd835d48bc69ecf98dbf8f50ded525874d4724d4.nq.gz
│   ├── cf6ca470d0969e6483eba5f8d13841068c50dba9.nq.gz
│   ├── d026b8f593aefb4b08ec6fe05c3f9ef0e19915e4.nq.gz
│   ├── d3ed2a59b41b0d1852747b2867ffa796b943dd9a.nq.gz
│   ├── d503f2f6f9ced2c76e552d6a04c8a20e2876250d.nq.gz
│   ├── d5ef27cd769938ed9d5f36f62111c4ebfc1722ec.nq.gz
│   ├── da694856d06cfa06df6dbd136e2489aa10a589ee.nq.gz
│   ├── ddff8d8b12a396b6342bd53bd4c52a20ea95672e.nq.gz
│   ├── e1b64830aa1f73ad69796c5835ee85b6fc38ab5e.nq.gz
│   ├── e6b4f2ca71c4ab8b59b02471d027acacd69b415e.nq.gz
│   ├── ec50611ca4f3e7b8bf6d7d87203f263ded38b1b8.nq.gz
│   ├── ed3806f66970b0ff0cc890a10f1582c594a28f97.nq.gz
│   ├── ef9c8bd2e281b54dc7b2ca04b64ebb81d34c5b98.nq.gz
│   ├── f49a4e16e68b128803cc2dcea614603632b04eac.nq.gz
│   └── fd707785db1a07c752c116efdf83725926294ca1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── dc729222070b508381b8dc81c027b0c0e6720567.nq.gz
├── filetree
│   └── dc729222070b508381b8dc81c027b0c0e6720567.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 112 files
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

[near/near-workspaces-rs](https://github.com/near/near-workspaces-rs)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
