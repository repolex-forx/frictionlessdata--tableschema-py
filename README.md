# Repolex Knowledge Graph of frictionlessdata/tableschema-py

RDF knowledge graph data for [frictionlessdata/tableschema-py](https://github.com/frictionlessdata/tableschema-py), parsed by [repolex](https://repolex.ai).

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
rlex download frictionlessdata/tableschema-py
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 75d2accb985c3bfe2e72fc6ee987b6b16628d295
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 75d2accb985c3bfe2e72fc6ee987b6b16628d295
│           └── chunk-001.nq.gz
├── blob
│   ├── 00e154e4e0180c7319005fd005dceab79de15ea0.nq.gz
│   ├── 03613c0246feac929c9301e8f17a58946ded745d.nq.gz
│   ├── 04af5e715e5b6af913e0a07a7489a5ce4e8498f6.nq.gz
│   ├── 0967ef424bce6791893e9a57bb952f80fd536e93.nq.gz
│   ├── 0b1f4967cb50b1e4fbd3a14aff9dabff528a9ac9.nq.gz
│   ├── 0cf2a48f2e87a4bde6a81325467234e605289ced.nq.gz
│   ├── 1192dc0f362c90a8e515d46b83e690ef1953071f.nq.gz
│   ├── 1285d0d72047ff393f0fe1a1555348db5a66198d.nq.gz
│   ├── 136f1dede9b93c422fa63c7b94012c542cacc1d5.nq.gz
│   ├── 13f45d596be80ea6b7b63864848f317734e62929.nq.gz
│   ├── 1d73e509a102fa6eded0599c7eb5512b31a7c436.nq.gz
│   ├── 1e172f901810fcd243a90337afba423ba77f374c.nq.gz
│   ├── 1e1e019e7bdab9ec41e9b1705b8709c64d6a1bdf.nq.gz
│   ├── 1f4390fe2f86d818e458ca0f5d9fec16de7f2e09.nq.gz
│   ├── 25563422ad2416fc34d3707c0661d5554bcfb25a.nq.gz
│   ├── 295b97a2aa729e0652a729cbda1ce473a7aedfc9.nq.gz
│   ├── 2b365d4bc6f5b31c5e14780e1fc146625c74f2a0.nq.gz
│   ├── 2bd09a1f27b9985d9670ce9d23d6b8fe7e1510be.nq.gz
│   ├── 2c5d1b1f42eea63a2d747efdb0c48804f42b93e8.nq.gz
│   ├── 2fe2111f311b713e15b2c8fd805e0b31cf9ac6d9.nq.gz
│   ├── 3447ef8e3a364e41ed64a236ee9b9fec01f9b736.nq.gz
│   ├── 35e24db4d6e046628412fe1d78f023a41a03f6fa.nq.gz
│   ├── 3c6e79cf31da1c0433d2fa666bf50b53f6359f26.nq.gz
│   ├── 3ef248e02bbc9b1af7c7dd3ebd05165861953d96.nq.gz
│   ├── 3f4927494e2a4da1bfe9c49772a7928043379332.nq.gz
│   ├── 4084806519948daa58a8600c5eb9a9d99154edc2.nq.gz
│   ├── 4152c2f95c8c4acdd3f1bacfe91358a386c50940.nq.gz
│   ├── 4499d28ec0db62ff159c0cc2895d411c518b1cb6.nq.gz
│   ├── 44d93527170d4789f0b9d369af96f2a537be95ce.nq.gz
│   ├── 463fb1e4d33c434e429b3cf2430f38ca5a52549d.nq.gz
│   ├── 48ac8619771f6559745122486521f73c4dc3af29.nq.gz
│   ├── 48e61170268b052d05f983daf48044263cde9a3e.nq.gz
│   ├── 4af60a14b96cd0aa45c2dc482afe6527de9a4624.nq.gz
│   ├── 4b7da690d09fcc71b6888fc6691cb762c6393729.nq.gz
│   ├── 4c6b503cf972e85a18047c2d290d81aed6bc00ce.nq.gz
│   ├── 4d9626033c9c18007a460a89f5140a2afb1bcb47.nq.gz
│   ├── 4e3e450a05a0d1307f9709abfc1e36dcd3c263a5.nq.gz
│   ├── 50b8383c1c0d5d9609748048d42609cccd72527d.nq.gz
│   ├── 554c90502e84e164996388d89ca639aa1f6bf9c7.nq.gz
│   ├── 5714835e3cac171e938934d66f0ea11801792a5c.nq.gz
│   ├── 5854d663b216421c30284b30a840097b8fc105bc.nq.gz
│   ├── 5a36952c42ccfd283ef866b46c344a227fcf5f9b.nq.gz
│   ├── 5a65b3235dbd04eb3a5b71f6f22a28a01930ef85.nq.gz
│   ├── 5ae7a769f8386b1fb49a4acd74df61aebab37839.nq.gz
│   ├── 5d71242ad85c3bf329172367e9dc513bda53b057.nq.gz
│   ├── 5ee6477165727539aa0701c22b47da2ceaedeff5.nq.gz
│   ├── 5f8a91659051145a830df51207a3274fe22e4295.nq.gz
│   ├── 60d180225fa370ebaab7f9f97dcb9b54f755c483.nq.gz
│   ├── 64bf820e0e354b97c4f1ae56cb8ddfe00755c702.nq.gz
│   ├── 66463cb46629fc909deb7ff14836c10ec8daaa55.nq.gz
│   ├── 67302b5f35231ae72ed57125061414be9e1aa656.nq.gz
│   ├── 692bc531237244e57f93d47bf837289bd90bd3a4.nq.gz
│   ├── 71b0e8cf6369a1a985c7240efa31d63b9b9eb631.nq.gz
│   ├── 7407fc5e50e33b03ced57e709705dd9a7b7a2dd0.nq.gz
│   ├── 75bede24368f8f7410f13ec2ad43bf173e95a21c.nq.gz
│   ├── 75e43afc3a9d539dc6f0023b892e729613a02f60.nq.gz
│   ├── 7b463c78af5344436b11b258bbc2fed3a22d5c62.nq.gz
│   ├── 7bd4e61fd2009b3732bc9d7d6caadc36a41ed95e.nq.gz
│   ├── 7f783580538f1ed6f4a443a5308a7bc7ea6c97b1.nq.gz
│   ├── 8527867363759e9aaf795447f6ea1b7805273895.nq.gz
│   ├── 8956c8be899d50ab838a1d1a3f863adcbb712c44.nq.gz
│   ├── 89e7fbad56675bee9f1f8cacd6b685533b6fe742.nq.gz
│   ├── 8b32cc0bacda15112e3e847d1c5f4182fd6fc5bf.nq.gz
│   ├── 912c4fb4ccce0df1ca787131ae8b29502daab0ab.nq.gz
│   ├── 92add0c219267778d722d5604d2cd6c5cec4515f.nq.gz
│   ├── 969b7dda29aa5505719c19bdaf83c0cf4836f602.nq.gz
│   ├── 97daafe812049e0f38764f2faa824bd6caad127d.nq.gz
│   ├── 9a9e3c6bd596f6e2c32c38a0303000350aad7973.nq.gz
│   ├── 9ae19d28880f6d0b5bc68b28814bfe1523dc0fee.nq.gz
│   ├── 9b75ff82744eaec9adf1161d8f57f671c3baa386.nq.gz
│   ├── 9c55441d2476d15d4f897d5d1e313636c320b48d.nq.gz
│   ├── 9d13cd3e27b26448da778bb459c6e32197d1eb26.nq.gz
│   ├── 9e7d28cb7535540831309c1cdc4624e5e6b70dc4.nq.gz
│   ├── a0be438e015aa080c0ad5223a9fa1710b46dc9aa.nq.gz
│   ├── a4bcd51848856dcbe450007cee55c529c71d9017.nq.gz
│   ├── a71aeb89db05fad9ecf6bda647179dc93037d53e.nq.gz
│   ├── a80b5647133a6125c4ebe7eae5117703afff4650.nq.gz
│   ├── ae94ddfdc386cd780a03637e3a647b404e729aa0.nq.gz
│   ├── b0730c044b9a700cc7abca6871e1bce096e74c25.nq.gz
│   ├── b0ce14a57aa19a7ccf8211b74070a78aa812412f.nq.gz
│   ├── b13d1fa74c2e7252a51bbb4b7c0737b58a4bd083.nq.gz
│   ├── b477c66512529ec49c46924f5f476f4de7468904.nq.gz
│   ├── b54508d1d7787f73d96d12a94ba14e8d5a596d4a.nq.gz
│   ├── bdf3aee95b13ad9d2500e636c8074e4b850c8551.nq.gz
│   ├── bedfaa3aaf3fbfbd35c926bbb657296d9b6350c5.nq.gz
│   ├── c164388dd86443558e614f31a139047c4f9e1e67.nq.gz
│   ├── c647870ccffc4d75283782fdf256799c15af5d51.nq.gz
│   ├── c8ab5f5658fbbfef66224f64fd90f17ef56cd7f8.nq.gz
│   ├── cc7278093cce88f10c3348a9c45df31d31c1be14.nq.gz
│   ├── ccb701128806885e6b6985aefdd3682a56fc485c.nq.gz
│   ├── cdb0b3a61b2a572f287800cca1e299b1f77f9230.nq.gz
│   ├── cedb36402dc642da561dde49d68f4b3f30b5a2e0.nq.gz
│   ├── cf01cb1929351d5ab39a84f7a04233d891a928be.nq.gz
│   ├── cfb1ac7165afd16101035ab0d39bb7b1d3d00976.nq.gz
│   ├── d207ea9bbcfceb86b1e0c4288a9ddda7442c78b2.nq.gz
│   ├── d2e25eadb9b8e5ab02b39dae457637b4e00d5513.nq.gz
│   ├── d8839fafa625f66d78dd630a1942fa93b64e6a44.nq.gz
│   ├── dae5baee99ed0a261e57cd5202ff6ffe2d8056df.nq.gz
│   ├── de4d4e0100854e84c67fc1aabeaf7c401948c391.nq.gz
│   ├── e4264e9848df949deadfb46aea5ceef989282126.nq.gz
│   ├── e6253b7c4d24a50afffd70a8bc08cb09ed2e7618.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6a1e1e3577b28e6630dfec33189cdcb195eed91.nq.gz
│   ├── e8b747f77f1d8d1677a84755c4ae2ea01454ad6a.nq.gz
│   ├── ead9cc751e4bbacf36e9260faa43ab301270c638.nq.gz
│   ├── ec042986a90d037799c657275845c9e19ba55fbf.nq.gz
│   ├── eca4c47363e4a7f8a0c03ce3c30865b1f8c81b3c.nq.gz
│   ├── efa39cfc8a5723ac2214a6d64132b93b124e165a.nq.gz
│   ├── efb1577d9ecff7cf2ce8c12e1ec1023eb0a07ccc.nq.gz
│   ├── f0572d624af635f17a64b65017f2d82123a6f871.nq.gz
│   ├── f0bf5af809b2c3490740186b0ed2e8f6c0de6e0f.nq.gz
│   ├── f7574d0a32717321f53630ad454d135d41bbcbf4.nq.gz
│   ├── fa6191ac25ff64bf1dc2caa3222465413f9379c5.nq.gz
│   ├── fc7c80e9c2ce59c6f61d760d70cb5e776266c32b.nq.gz
│   └── fe51488c7066f6687ef680d6bfaa4f7768ef205c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 75d2accb985c3bfe2e72fc6ee987b6b16628d295.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 123 files
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

[frictionlessdata/tableschema-py](https://github.com/frictionlessdata/tableschema-py)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
