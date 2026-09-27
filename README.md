# Repolex Knowledge Graph of asimov-systems/asimov.systems

RDF knowledge graph data for [asimov-systems/asimov.systems](https://github.com/asimov-systems/asimov.systems), parsed by [repolex](https://repolex.ai).

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
rlex download asimov-systems/asimov.systems
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5a4207dd02975851aca1c892d62623b081425cee
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 5a4207dd02975851aca1c892d62623b081425cee.nq.gz
│   └── repolex
│       └── 5a4207dd02975851aca1c892d62623b081425cee
│           └── chunk-001.nq.gz
├── blob
│   ├── 0336b7d7a5b1fed1dbc995e07c63f89f052b13e5.nq.gz
│   ├── 06c481e94fec8b10d1cfc55580d5dc9ee5ce4e9c.nq.gz
│   ├── 076deafbc8a84b027ac16a26fdcbe6013c622ed2.nq.gz
│   ├── 091e182f18ef98ae0f678b14c306c669d1ad22f3.nq.gz
│   ├── 09cff2849ead52997e20dcbcd748201acde841b5.nq.gz
│   ├── 0aa0aa1c53a160775d709cdd0dec811513b05d01.nq.gz
│   ├── 0ad376d972079d1b3fbc0d797e2749002d4253d8.nq.gz
│   ├── 0c0584444b7f73ae77ef7bd124b4e0bae1d0563e.nq.gz
│   ├── 0ec4106f7e4f80efe937fb419eb293e2f8483f38.nq.gz
│   ├── 10f0f23826363f3a3bdbef1e8128e2c4b7a3276f.nq.gz
│   ├── 11eedb5ad33fd19e0395cc841a58e5dd3151fa08.nq.gz
│   ├── 12197d948bc2606232d3adbc4ae3211761fe131e.nq.gz
│   ├── 1229e7cc00b46ba971a06147818836a8335f61fc.nq.gz
│   ├── 131970da3e4cae339f5a8fb33a29c83ca395ca02.nq.gz
│   ├── 13d756c38d8e2737b6694276d9c3ab58d8bf68f3.nq.gz
│   ├── 14aca7add38b952229ed54968a5d3f200cadf9a6.nq.gz
│   ├── 175cc7d92fdc6c834d828fe282a89509cf808931.nq.gz
│   ├── 1e4e453567022c73b2f4fbf75db5d3ed07cc545d.nq.gz
│   ├── 1e9b53580c9c0ff484d512071f43c840e4749125.nq.gz
│   ├── 209390d0cbb50d72cf8eac74a9b7d59048c16d87.nq.gz
│   ├── 2199fbdb3e67aa6c97082ae29ce5c3b651df4eab.nq.gz
│   ├── 223b97fc95e8f0e2b64e7f6f22d414d8a92c6b90.nq.gz
│   ├── 239f17c66c4da0eb8990c414328c9121e832175f.nq.gz
│   ├── 251fe4bbd1b65b7b911d44b00d182dd472bda05c.nq.gz
│   ├── 277c03d8981e8b1099c4af7c9b1d63f85498556e.nq.gz
│   ├── 2839ba8cd34522851b191eb2c438346150b53adf.nq.gz
│   ├── 28c19bf4b13b8a816e49fde903c6459bbafffa3d.nq.gz
│   ├── 28f4c7673da607c419591767de4e67082cbe4a2f.nq.gz
│   ├── 2bd5a0a98a36cc08ada88b804d3be047e6aa5b8a.nq.gz
│   ├── 2c8d12c1a2d856048b5992e9fe60558b42b036dc.nq.gz
│   ├── 2d2f7f13a742166a4bbb3f304f7e28730033e197.nq.gz
│   ├── 31998c7cb28f21a9485c66a25c9b19d08647ef93.nq.gz
│   ├── 33fc97381265bc8266252ca69ec9425d4546cea4.nq.gz
│   ├── 39abc6041828c232a95dcf1be62af920a86d7dea.nq.gz
│   ├── 3c7a3adf1086302cfd23371b044257bc15bf092a.nq.gz
│   ├── 3ec5414f506639802eda31083b09595048ec1ae3.nq.gz
│   ├── 40b7175c11c04992baa7e36b91509797c9e7ccad.nq.gz
│   ├── 419cea3bb5901c63831edd72d89153e52868b587.nq.gz
│   ├── 4277417425a2374ee6a34d03ee97093b53df31d5.nq.gz
│   ├── 458ccd898024aa18f5e6ff6acd4d83453b412c51.nq.gz
│   ├── 47e95568a4d655b0cb11c631d47238357307307a.nq.gz
│   ├── 49555e7665e6971b9619f243279d1afdb56fe649.nq.gz
│   ├── 4a73cce028094e2acb3f839370d1d3f216062269.nq.gz
│   ├── 4ac69b3cb118e59eae3bdc4682d741d6fce93739.nq.gz
│   ├── 4bfc26a77bbedb4c1a726da780b842a638b699b2.nq.gz
│   ├── 4d6f52e79a8e9303376239ad6216054449a9a46b.nq.gz
│   ├── 4fad79a5a2294fcc790db8a898b1add54242cc08.nq.gz
│   ├── 5543f3bd32abf488526676e6103c5e3a5c868ef1.nq.gz
│   ├── 55cd010fdb094d03c610bd99cf058d20a349eac4.nq.gz
│   ├── 56a0fa083267b8b47b7f8514f8eba8c75e97492b.nq.gz
│   ├── 578268f348f36c0669831dbba2d666a81d080c65.nq.gz
│   ├── 57de34b3dd1898bc2e1de19750667f1bfac5a0de.nq.gz
│   ├── 58c7ccbdd56e21e4be7844fa0a2278c322710881.nq.gz
│   ├── 59a5cfcad8e7f95524a2079cbab2ff32414d6214.nq.gz
│   ├── 5b05382d9e4dd507d134075ebc71f1964931cd63.nq.gz
│   ├── 5b735634948f6c3e0bbfa4af395fa089ab630fec.nq.gz
│   ├── 6089a9f6e07c105c87ad0a6ee87f412904608108.nq.gz
│   ├── 6186b7ef2f764cac8ab1c55c94568a0fa15acdce.nq.gz
│   ├── 62f731ccdd56e94ac7b0ef82851e6e2279df6306.nq.gz
│   ├── 6369d964c7673a94cca57c4f9e8ffa568683fc59.nq.gz
│   ├── 680920783bb340d2c71ce4eaae0777e133823ed6.nq.gz
│   ├── 69c8acd0cdabdcbcf9285f9f36ff1ebef8c921ee.nq.gz
│   ├── 6a7fbe10c8e86631548d27b4352a211f7abd5780.nq.gz
│   ├── 6aaaa4824469630baef9225de20f8baf49a4172e.nq.gz
│   ├── 6f277afb846b9890a9bb16394831c8eac3599286.nq.gz
│   ├── 6f88d42b5b980c7636122a695f256cf7f74dc238.nq.gz
│   ├── 7168b695b138114fa59747397d86d31bbdd5cf85.nq.gz
│   ├── 736b612989c664d4d317a1aec8cd5e60e96ca812.nq.gz
│   ├── 7455bf8a6ceddef28911db8b6518d7d300d51147.nq.gz
│   ├── 75bbc40335fb9ff8148f614c41c1ae577fac496c.nq.gz
│   ├── 798a4b3cd1e85a5bb1f425e403913259c27f2ea6.nq.gz
│   ├── 7cd80a3d4b67c10750d37afc567b150687a3078b.nq.gz
│   ├── 7cdc0910111e7360bc13bf3fc576533996f80a64.nq.gz
│   ├── 7d00561116c3dcd89279e4c8707486c07486c79a.nq.gz
│   ├── 7fe7eeacdb1d22844f0cd0b907312a96fb633faa.nq.gz
│   ├── 82ab71bdf1b6d16d2b3a4c064be91aee8bf1e6cf.nq.gz
│   ├── 83676d1a2077424dd04a579da36a41158aaf3b14.nq.gz
│   ├── 86594468554152a5390efab065b4d83a8fe69209.nq.gz
│   ├── 86718283f59e56691fae3a0bb1ff8cdfc26f76d3.nq.gz
│   ├── 871431894254d339b6ef93a494287f800919a284.nq.gz
│   ├── 88177e7e91f419263c441dbc68fe34770c56ba81.nq.gz
│   ├── 907ddcdcacce43dec09ee2381ef2cdf1b533506e.nq.gz
│   ├── 92421200606c81163f1dcb950025f081254b99f7.nq.gz
│   ├── 92de3f19d2c646f842bf27da45fb78bd1343165c.nq.gz
│   ├── 93ef243a967eab3e50912b5938945ae1beb68e47.nq.gz
│   ├── 94b20bf7a5827e6779dd92a1ec2d111faed68d91.nq.gz
│   ├── 95cbbe465484765e81d96f7f6e431a9d9e345021.nq.gz
│   ├── 9722260ed102afed0f7e3af01cef10b698d35305.nq.gz
│   ├── 9814a723a5a833a504a512157f24cccbbeed0991.nq.gz
│   ├── 997156f553b91c56ee24f4f726aeaeb2d2080c4b.nq.gz
│   ├── 9a15737be5e53bb4fb83fb8aa71fc776d8f74cc9.nq.gz
│   ├── 9bf63c6625c6f8cb0c0598f62609c288a36e193b.nq.gz
│   ├── 9d92dc46a9809b2b20193668c0f98359924751c7.nq.gz
│   ├── 9e2d7bb0d995e867ec44223bdb8198891ca87f80.nq.gz
│   ├── 9ed66d7ba08d9c52d1b09b980885c272bcf7b23d.nq.gz
│   ├── a2d4c82d96fb055c4c0ebb47e03b8e70f925db1d.nq.gz
│   ├── a5335e3f436f2866d16741a31d96c4c22b047d25.nq.gz
│   ├── a75ba78f1018e4db0e3cb918473661f1cbeb2ca5.nq.gz
│   ├── a7b9b8adf7fe703328a03068ae0edc545a6b258d.nq.gz
│   ├── a83283d680802c57c9e3b25e20553961a7a1e818.nq.gz
│   ├── a899f34ba01d2674890fb85f4af4630bfcd5ad65.nq.gz
│   ├── a8cefd5b28bf56133b0cb8fb440072e5832ca6ad.nq.gz
│   ├── a921ac0fad52576fba7382fd0913dcf8c598d3fa.nq.gz
│   ├── a9b3d4390b9d80a36c2d8c7243361e3b806caffe.nq.gz
│   ├── aa01c47c73ef6fa913701d72bcc61de986f3e0d9.nq.gz
│   ├── aac6190c814f7ec0327e676ed37da55c68733a48.nq.gz
│   ├── ab306f4c88417833d071319f2b7656562d38b6b7.nq.gz
│   ├── abd118dfc0823c8b958e7839f66eb52ff11c9e2c.nq.gz
│   ├── ac4c14120046b190d8fefa003f0abd9982474bbf.nq.gz
│   ├── af8037def69638aa1f7f182a278b603982e3606b.nq.gz
│   ├── afdcff9790385942a0535854e62ce0cbd4ed15fd.nq.gz
│   ├── b25412a40cb131f1ac3aec946ac9b07dcfc7e7fe.nq.gz
│   ├── b2caa824bb223345ab515d7461f2e4807cfd1c1d.nq.gz
│   ├── b34e014854c5ee6fde14117ab731f8107309901e.nq.gz
│   ├── b448cf2e32e3b5a30bdf62b0388eb5f3e9d379d9.nq.gz
│   ├── b8764ab3a25a4f5f7399a0479ee45e2ec6b941bf.nq.gz
│   ├── b8aeb53439661aba1e2e2a3fc5191ef5b6693018.nq.gz
│   ├── b9c3e0e0099e071ccd301e9c2287f68bfbc71f52.nq.gz
│   ├── be1bf347585875f86ea37b5deea989bb466ed78b.nq.gz
│   ├── be25a0c61f36cd9fe0f84785456ba3b432c72eb4.nq.gz
│   ├── be5a7e0fbf5d9f852e03bda91e252887b7890c49.nq.gz
│   ├── be804dcdca2fd2d20a0970451ad134d78a8cb55f.nq.gz
│   ├── c16892d39fa40227035247657ade070a92cc1798.nq.gz
│   ├── c3fd3acdd5419ac3b3e7951ba1d7d242e62a7c39.nq.gz
│   ├── c4405b30384f09a6170913d210ec80eb8997a340.nq.gz
│   ├── c550342679c45fa1111f375f464d4fc39974bf20.nq.gz
│   ├── c94dcf53b4d5b977a15da6e992ff960126d7d35b.nq.gz
│   ├── ca5757200d0355c1dd4f4b5efa481d50cdcd7f00.nq.gz
│   ├── cd45567291ffc5adbcb6e779150abe9df9fce6d6.nq.gz
│   ├── cd9012f186ee4ade60568e32f7b1cf85a4cc6001.nq.gz
│   ├── cdcdfb4a28375dc01f4425ae737b550b7739b93e.nq.gz
│   ├── cf8aa93e7cfc44a70803a45561bdd3da8f7fcb56.nq.gz
│   ├── d47e6b6b7fabfa7a5188510998d04340f661a099.nq.gz
│   ├── d550901a663d66d649b22db1d8200c5f17054072.nq.gz
│   ├── d696b7a6010778ea3689a941be71a00f29b96771.nq.gz
│   ├── d9120ef72e713de76288d1a7db5500c3dd7caed9.nq.gz
│   ├── d9d661d670a413cb3460244edd21ea7dc5b8fd73.nq.gz
│   ├── d9dfb98a1fb6e290796e5e195dae0805f4c890b9.nq.gz
│   ├── da15d2a9c71f240830dae947b3e6a0ef5a64778c.nq.gz
│   ├── db8fb57374edb8f5e7351369a92a34cfb315e91d.nq.gz
│   ├── dc108a40e35dc40d5c5e270b96f1e93ab412a942.nq.gz
│   ├── dc80f79ab7e4b51f70b9d7f6a7da77be85559604.nq.gz
│   ├── dd17407f5a4f3c6011629aea53f2ef447e718d12.nq.gz
│   ├── e133ca37613e4f005c9ee71879779a62522fd47c.nq.gz
│   ├── e279129787c416512463d57f1a6f4ca294e58694.nq.gz
│   ├── e671421bdecb745368d0e6ea4221ea0dde7b89f7.nq.gz
│   ├── e6a3e1371bf39cf2d7b23d426f7dc36f461a1d17.nq.gz
│   ├── e773cb05ce4e04ddbcef1df4da68684c72ee8db9.nq.gz
│   ├── ec4383e190d867fcb4b17ab58bb92dd5e3b23818.nq.gz
│   ├── f00ce4e0f15205bad0fb25f68d4ca4a50c8958cd.nq.gz
│   ├── f630f831874f058921d421d925571ec422b4c4f5.nq.gz
│   ├── f68bdbdf60ec25721936bdcc379ad02dccb97edd.nq.gz
│   ├── f7e9e6f0fe7bb540d4782dc46f6600b565210535.nq.gz
│   ├── f86609c8669b23aa59941b4d87442796a2d344ff.nq.gz
│   ├── f914bb49315724bc3bb443fdd098b83a0d9bb2cd.nq.gz
│   ├── fa09eeef9d57ba6788d83eb639883c4b1cb4710e.nq.gz
│   └── fa95935a2e2f0eb4f3969b5213fb0dfed42c99e4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 5a4207dd02975851aca1c892d62623b081425cee.nq.gz
├── filetree
│   └── 5a4207dd02975851aca1c892d62623b081425cee.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 166 files
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

[asimov-systems/asimov.systems](https://github.com/asimov-systems/asimov.systems)

---
*Parsed on 2026-09-27 by [repolex](https://repolex.ai)*
