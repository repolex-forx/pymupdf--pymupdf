# Repolex Knowledge Graph of pymupdf/pymupdf

RDF knowledge graph data for [pymupdf/pymupdf](https://github.com/pymupdf/pymupdf), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download pymupdf/pymupdf
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 167ee108eb85c71671890afd9a724a2b867c0e17
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 167ee108eb85c71671890afd9a724a2b867c0e17.nq.gz
│   └── repolex
│       └── 167ee108eb85c71671890afd9a724a2b867c0e17
│           └── chunk-001.nq.gz
├── blob
│   ├── 0231abf962dc52b561da73eb5d4063134b855262.nq.gz
│   ├── 032b873294892718af712904a6e00adc55ed8063.nq.gz
│   ├── 03831ac27d9bd13e2bade4ccb85217398a3ebb9c.nq.gz
│   ├── 1591dd4ea9a00924caa942b5adba88067f702fb1.nq.gz
│   ├── 1609640cc9c789fff95fe977ede7b12573ef1018.nq.gz
│   ├── 179494ec91b24c52315238a8843db567aab50a19.nq.gz
│   ├── 184a2d6a3c959eebec0603b03611f3850c9e5b76.nq.gz
│   ├── 1a0c679a162b4c8c92d743d813d8a497f1a116fa.nq.gz
│   ├── 1a77c3c41616bb2e5cefdf39e55da1ab9f0dab00.nq.gz
│   ├── 233a9d7a97c8bc15b5d2e1d987a406d3f774bca4.nq.gz
│   ├── 27f18e97ec5dbb4689c4b55c4f1533e5313f980b.nq.gz
│   ├── 2876af262e3a7055eae00102597aad14add2222b.nq.gz
│   ├── 29dcaa407be527917e7f7196ed8cf2b8c354a9db.nq.gz
│   ├── 2b11a71db859348f8822accf38230c01b217c813.nq.gz
│   ├── 2be23e2f0dc1898da2e3892015600be6b99e6dfc.nq.gz
│   ├── 2d002f9d8d942dd49b2d37879509865f7ea90e07.nq.gz
│   ├── 2e2e731dd980f70e201037f2052a90c726e5505d.nq.gz
│   ├── 2e588f8beebbbbe02dc1d65ca8afb2e22a92f8b4.nq.gz
│   ├── 2f1ad059404b0ad602e2861f8b07c240ca5a47f1.nq.gz
│   ├── 31195b9c4637eff9a19690a086c9c89dbf3de6b6.nq.gz
│   ├── 345d77ccf192e4b23f32829a46f4e99ceab944db.nq.gz
│   ├── 34cfc67cbb231a1313362c1c2b592fb22c689e37.nq.gz
│   ├── 36591c89fbf3431cf0dae1f315f47ea15ad367b5.nq.gz
│   ├── 39d748df62d45ee1bcefc3ae83984b23760da1c9.nq.gz
│   ├── 39e2e522a0ca84653ea79258bd56944094ffaaa2.nq.gz
│   ├── 3b6b56076723ca71a1cc651ab0c7596e6652883c.nq.gz
│   ├── 3d577beb66e7429f86859613efe670c5cf1830d8.nq.gz
│   ├── 3f15d79071429056d133b9082fb230e99b94db1d.nq.gz
│   ├── 40f11c16cc43f391e5bf6ad9ea97d9570fea4d22.nq.gz
│   ├── 43d038fe718914d3fce86c22a6f79c4cecbd0f91.nq.gz
│   ├── 44d0cb04e822e4e6895cc5efd3c6379dbf4bdd23.nq.gz
│   ├── 464630edb9d2fdb81823520a76816ad9d39d03bf.nq.gz
│   ├── 48a7b276045e8e6c1d9376abfd79709a779484eb.nq.gz
│   ├── 52995fb0fb0572eb9f8d24d5a527018ec86a6837.nq.gz
│   ├── 54b425e2c44c657bd1f4aae443357a435954d811.nq.gz
│   ├── 566aef075b5e95a148fbbeca7127501fd86eb529.nq.gz
│   ├── 59636dee75f9b11fdbc708e34780055ff5126a42.nq.gz
│   ├── 5d1a8003b1e471567dca54ed884e777a148c93d1.nq.gz
│   ├── 62684459b99604ab18de3cd664a37cb10c650082.nq.gz
│   ├── 65be4d9c33351e3f1915ffa9c42e52bdf81635f1.nq.gz
│   ├── 665b40ee46e7b40f7281fda4e49786695cd49628.nq.gz
│   ├── 67cfd16befea297959e582d7508890a1e1c2b6d2.nq.gz
│   ├── 6b564a0d14096fea8335428ad28bf0fede4a0132.nq.gz
│   ├── 6bfb61d4aed24636ad80f0a866ee150bc5cd4652.nq.gz
│   ├── 6cc867296996890a5081bbd71e7206557d2dc25d.nq.gz
│   ├── 6d1de6443229392d24cf6ca2f05094f1886d84c4.nq.gz
│   ├── 6d5b0b5d1fc00457509aa302077c3c23592e93bf.nq.gz
│   ├── 715a588cf6d4f6c360dee51ed41f425bd42109af.nq.gz
│   ├── 7782d81a576688963b59ddf7397193607682e0ce.nq.gz
│   ├── 77a5048f891970ccc74307a714f2862d87209812.nq.gz
│   ├── 781a5b6ef7cccc291bffa9b6cb4df2c24b6bd552.nq.gz
│   ├── 7bdb5d540619c2ce89f1cd9107b3fa9b56d92076.nq.gz
│   ├── 81dccc560de1d8fd48c654a7d88520f3cc820837.nq.gz
│   ├── 836e3e88982589c26a669cd7248b9997bfa67f9a.nq.gz
│   ├── 840ccda25bb8436734e6e1479ee18587e4eda61e.nq.gz
│   ├── 895a614e64732ac6364b914badd0ab136a6f0d37.nq.gz
│   ├── 89c344484a18b79bf7e2d938578569ef078504c1.nq.gz
│   ├── 8c66f7b274e29d5af22a6052ce7887d70b4d7661.nq.gz
│   ├── 8d64f99832c3cdaf87fd97cab3cda5f431b92d34.nq.gz
│   ├── 8e09720552dbfcbf82d6cfaa0d9fa811a05fab99.nq.gz
│   ├── 93cf79e0720183ef4c58a315ab506ae29d0a6adb.nq.gz
│   ├── 94a9ed024d3859793618152ea559a168bbcbb5e2.nq.gz
│   ├── 96773715c446f8ddd8723fe6b542a70f636b1942.nq.gz
│   ├── 96960ead6be163c3b6de40625e5d8e55808f7fe5.nq.gz
│   ├── 9854dbc695ce2467efdf0beaf04d9756d4eae1ad.nq.gz
│   ├── 99d261755da0eb6662a41db18be74360a34fc028.nq.gz
│   ├── 9b9d93ff16bbc56cc6d3fda8876f4fc482cf5db6.nq.gz
│   ├── 9f17249351bed7079eb32cb4906216dfbc819f2a.nq.gz
│   ├── 9ff1b0bda73b4d0f1cf6481ef4efa550ec48ca19.nq.gz
│   ├── a1c00ee5b8b2cb22f4370d93886ac42c85f00363.nq.gz
│   ├── aad39261380f75e62fe0e0568215b8964f495bfa.nq.gz
│   ├── ad1c1087e102e64f46e3b42cea706ad1006c7398.nq.gz
│   ├── b27e04987b1a9cda16a951e24d580ef32e72d23b.nq.gz
│   ├── b47144841815f3d2ce5ebc3ecc0e950022fe839d.nq.gz
│   ├── b710d4b43619ff459acb9cf56676ce5e0ce8dc09.nq.gz
│   ├── b8c4cc010b7054163454837b24e05bec91e29edf.nq.gz
│   ├── ba82c8ad0ef10244c4c6215a223b22e7dd109fb3.nq.gz
│   ├── bdefa7f758d651cb2306f93e55f4584cd9978522.nq.gz
│   ├── c028781e2affa6621eb6cfea48e2d3d73b513e55.nq.gz
│   ├── c25e9a8ee08df589275eee4cb711c2969a0d5aeb.nq.gz
│   ├── c99094ecb7191d96f1633ee42f30670476c9127b.nq.gz
│   ├── cb62286c5d287a9b17e8b14ee24a2bc8e92f153b.nq.gz
│   ├── cb7e8749998ae43d0cb2cb6076f3a38d2ad5d89b.nq.gz
│   ├── d90712ca77eef7a0c3447aec730287a9d44ac930.nq.gz
│   ├── db1809d4523c79eec485bcd9e1091ba87128c290.nq.gz
│   ├── dba13ed2ddf783ee8118c6a581dbf75305f816a3.nq.gz
│   ├── dc03ee920ecec5c7ac486dd9fe65837994bca765.nq.gz
│   ├── de8c936fe0fdf3e2c98899ebbb8bda30b8780ba7.nq.gz
│   ├── e517937a72932e3f5dc09d4e081724401b2fec58.nq.gz
│   ├── e55e79db48811ed51864a563fbe67ccf079e3cc1.nq.gz
│   ├── e7be64298338dfd6b683b48be2d75438553a214c.nq.gz
│   ├── e828b46a0753b1ef6db2edc0c9991f97ea9038b6.nq.gz
│   ├── ec27159bbe309af9e9407e00e3a8e7630616c9da.nq.gz
│   ├── ee8582e5620241f27a54e8be754e578bc648abb5.nq.gz
│   └── ff75d097925b79c2aae768306d441d569f951948.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 167ee108eb85c71671890afd9a724a2b867c0e17.nq.gz
├── filetree
│   └── 167ee108eb85c71671890afd9a724a2b867c0e17.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 105 files
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

## Source repository

[pymupdf/pymupdf](https://github.com/pymupdf/pymupdf)

---
*Parsed on 2026-04-14 by [repolex](https://repolex.ai)*
