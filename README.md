# Repolex Knowledge Graph of pallets-eco/flask-caching

RDF knowledge graph data for [pallets-eco/flask-caching](https://github.com/pallets-eco/flask-caching), parsed by [repolex](https://repolex.ai).

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
rlex download pallets-eco/flask-caching
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0d131e699e978db12dfc22e511b79c4e7e1bfc9a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0d131e699e978db12dfc22e511b79c4e7e1bfc9a
│           └── chunk-001.nq.gz
├── blob
│   ├── 002d84d61d171f186b97692dff24827a38ab6062.nq.gz
│   ├── 0375dae3fe91b50b35ce587ce86aab66cc1af183.nq.gz
│   ├── 07af6baba8c897963a52158344731fceed6987d2.nq.gz
│   ├── 123d59e4beb95a6bdc5aef223c922385212a51b6.nq.gz
│   ├── 1719ec005c4e56263d18f02137486aa052710566.nq.gz
│   ├── 183c368963fdec681a80b2033f9e5b95b528eae9.nq.gz
│   ├── 19fe9a51d74033e7a2abdb56b5ea3c849cf3028c.nq.gz
│   ├── 1ba6293ca9a2848d8646db2553a9ab7c705b855f.nq.gz
│   ├── 25f64ff101c1a993e32da26eae689911b378a73a.nq.gz
│   ├── 27211b709452e237a093724c2d8b16e983dea3ed.nq.gz
│   ├── 273c23d5891a1a5c77bb263e2fbcf3208735f59d.nq.gz
│   ├── 2799450e76cf38de1023f8058ac240323b04641b.nq.gz
│   ├── 296ed0b7bec19785c02e9846803e05e9a99a9f7d.nq.gz
│   ├── 2b06925f8ee6ee0cce810fc5e857cef2225cb728.nq.gz
│   ├── 2e6f420642eb2699e2eb1b29094753b34f023852.nq.gz
│   ├── 2f873224281d03c0b90b61a15f8b0bdbcc697df8.nq.gz
│   ├── 309736a0104ccb0be06c50d9142c9bc8da770df4.nq.gz
│   ├── 319b329530805e67dc529463e7ad2fbc62440e2c.nq.gz
│   ├── 31e3ff7b605dd8036f91550209759aa7ba9f2259.nq.gz
│   ├── 35317428b5ea55e9ce0a9db97c93675cff3f9945.nq.gz
│   ├── 3fc9a3eadb854aa126a144070a310d7198ece072.nq.gz
│   ├── 4a710859034d17f1935700cb0b24bc4dd075ea8e.nq.gz
│   ├── 54aaac367b9bfdd735fdcbcd966c77e9abd7feb0.nq.gz
│   ├── 54d463766f18fd4974d56ea3ba0dfc73784eda66.nq.gz
│   ├── 5e0dcae54d24278e9f3e29d0ae7a41a70d74555d.nq.gz
│   ├── 5fbf3ee9d30a30499284b13401539081a894ae7d.nq.gz
│   ├── 60148d2bfebf0126bd90eef6aca4858428b28dd8.nq.gz
│   ├── 61ac05d1a2fcdd67bc6a1e1d6091528dfb628075.nq.gz
│   ├── 6350dfe57b10a26e30443a623c3cac9fb9dfb3d1.nq.gz
│   ├── 63de600384218d081b8b7492400418dfaa8ebda0.nq.gz
│   ├── 66d88c62c47c8b636d1d3465094e2de6f69ebb1b.nq.gz
│   ├── 719f5c3b8c4f839850664ce2402c68ce78d6fa59.nq.gz
│   ├── 75b6042a0a07fa5b2b9709d9a988517cde53c24f.nq.gz
│   ├── 7853e944cdf59ff5a96334c12e1c1d61183a15a6.nq.gz
│   ├── 7b072c90872748619ee10eb047a6f49b568c33df.nq.gz
│   ├── 7e5d720864df909feefdfb82e32a660a95dd561f.nq.gz
│   ├── 800e0ff6ead4becdf29b5ec6bd4316e0ede44f7b.nq.gz
│   ├── 84cd03fd8942ae26417d7d071b8a129119f1ac20.nq.gz
│   ├── 863385bfffaf6c8ad1c39512ea85b39444abad46.nq.gz
│   ├── 877da76afc073f278d755fc07e28410faa9ca279.nq.gz
│   ├── 881cac93d88a220642e598523f86ae6050b1a110.nq.gz
│   ├── 90bd81a542fc2b728422c3418b059791c770f181.nq.gz
│   ├── 90cea84c9fed4a80614233f0c19dfeb57a081c70.nq.gz
│   ├── 91f60f137171297f42b4acfcc7a0c42e5b72497c.nq.gz
│   ├── 986787f7186c9727018e8e0e179c784f6a6c827f.nq.gz
│   ├── 99c8f44586d6d29a320798bfc42df0578efb169a.nq.gz
│   ├── a1534402dd11a722604486b90a8badd1e9fa5e72.nq.gz
│   ├── a901ff7f1e130d11926ca41550def72d865b461f.nq.gz
│   ├── adbef834c011cf1b0b9048e2ed143c10e47460dc.nq.gz
│   ├── b3fa1cfc95be699e1ba25cee22e890652d253edd.nq.gz
│   ├── b6a54fb9cac2a443df6ddc6b004574576a5ea622.nq.gz
│   ├── be3c550595c34bd05cf71dbe215f732bddbdb905.nq.gz
│   ├── c2dd11997ec4afdbfc275f9cd1c236c2b96694ed.nq.gz
│   ├── d6795ed0bd07dc133d8f7856add371a7304ac50b.nq.gz
│   ├── d6b72b91257284b9d89dfa4007fb3f440e0860d8.nq.gz
│   ├── d74ce4bf67524fe4dc54c168465bb8fe23d7d54d.nq.gz
│   ├── d9e113ec685b92b018297dd2f200341d1fba01f9.nq.gz
│   ├── e33cf714c2392351e294a29481b0bf696cab21ee.nq.gz
│   ├── e3691cd6c34e167c352c6baae202d44ae2cd0745.nq.gz
│   ├── e57f6888da3b4ec40c9819dd34506cad8ce9e197.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e99f12a8954f034be28b546d072f04030c8f9b6e.nq.gz
│   ├── f7d175663e09206cedffd03c506124090451dec8.nq.gz
│   ├── f8a55b28a016866a1cb9686405f0dd224e8045df.nq.gz
│   ├── f8aa3564dbe62412ae3e991e7122666d2dd79a60.nq.gz
│   ├── f9d6cf5310b352503b249860f7ba6ee4f81786eb.nq.gz
│   └── fa675e602fcdf51bd0c5d0f26401bd9267838ef1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0d131e699e978db12dfc22e511b79c4e7e1bfc9a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 75 files
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

[pallets-eco/flask-caching](https://github.com/pallets-eco/flask-caching)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
