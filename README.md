# Repolex Knowledge Graph of samuelcolvin/notify

RDF knowledge graph data for [samuelcolvin/notify](https://github.com/samuelcolvin/notify), parsed by [repolex](https://repolex.ai).

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
rlex download samuelcolvin/notify
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 128bf6230c03d39dbb7f301ff7b20e594e34c3a2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 128bf6230c03d39dbb7f301ff7b20e594e34c3a2
│           └── chunk-001.nq.gz
├── blob
│   ├── 007c178aea39ba64227a1b39589064a4a670b844.nq.gz
│   ├── 03a4124114ca7de68179f469190849192d493368.nq.gz
│   ├── 058ed109ae9d5e50f3efec06d81f6d6827161a7e.nq.gz
│   ├── 05a7e9b6f77ae34144347969675920482fa845e3.nq.gz
│   ├── 066bc8e03705b3981855bf9536a54889bcc63646.nq.gz
│   ├── 070336e097c0ec4fb9d426a801a631385fbd41fd.nq.gz
│   ├── 07c9dfc17eee2f0aed25255a9551f3208dcd7d0a.nq.gz
│   ├── 08e6e34aa7e0c48c45f84a999149fe1c4c5c6304.nq.gz
│   ├── 0996fd66678d04f1ced4dcd339ba08cfab8dc3c2.nq.gz
│   ├── 0b2d24f22ccb32d68da64f6c6690ae1770ca2f7c.nq.gz
│   ├── 0ea8339ba2fdbc250f652e6d41c84b1c338f9df6.nq.gz
│   ├── 0fc277b41cb49fba8eaa5982fcfdacf47a7b06f6.nq.gz
│   ├── 10ba0902c642eda4308d9f5661f836f8156be7b5.nq.gz
│   ├── 113747907ebf39c2d2358cb47a697981e8ddc69a.nq.gz
│   ├── 13159813073420de3039d0217be49ffdb60b170f.nq.gz
│   ├── 1519a62ad29c83e2386c7990468adc02edcbe369.nq.gz
│   ├── 158bd11cfcb48f4bf07dcecb83525654da6dd55d.nq.gz
│   ├── 15d719e24621bec8f434769a27dbb520a921684f.nq.gz
│   ├── 16b9e65e7a3ad424ffde657501ecaab646985268.nq.gz
│   ├── 17203e2916866c8adadb620fbf3f7ecda87a3b01.nq.gz
│   ├── 19a49bc747d749f3303d1d75951011a0de98bce6.nq.gz
│   ├── 1d678d7c804effe1883d725478728bfcc406f17d.nq.gz
│   ├── 2a4aed2d2c20f73aa5078dae040e2f50c1fb6a94.nq.gz
│   ├── 2ac5540c3f925dd46142e9a35f408c2df7f51889.nq.gz
│   ├── 2db507e7ca291543340de187a2f366f2326f6c70.nq.gz
│   ├── 2f3645714a56ffaab3b3acdb2d1e16b13e61cb1e.nq.gz
│   ├── 2fa7f722951755db721e211fb6140ddd709c1530.nq.gz
│   ├── 32bd1e52076171c7f5db93f803fbb1723126200a.nq.gz
│   ├── 37ec4723c61e06dde2fc82f1afc88583cdec99dc.nq.gz
│   ├── 3b3879cf89876f5c572333ce23e7a5021d708ba3.nq.gz
│   ├── 3d0db31bb691dd2349f64ed5383470d3683aea28.nq.gz
│   ├── 3e3106981a719024fe846ffc7101845d08442316.nq.gz
│   ├── 42a324068f9c00cb4a4b56e4f22507f25d5e1e2a.nq.gz
│   ├── 48415aaf46d925a539b9853a1d36305707e36e39.nq.gz
│   ├── 4a338d91eb461296c585551921c600c7c5245cf4.nq.gz
│   ├── 4a8a152ccdb83b3198a811dd69c19cbe82a8c380.nq.gz
│   ├── 4c1c72e3eaec8dc62a34d34ec29f40b45681bd23.nq.gz
│   ├── 4d47e79a88ce5d0e9314f51f31af384e5ebec015.nq.gz
│   ├── 553dc1aaf1f6d43610aa333604f550bee9585ac1.nq.gz
│   ├── 55ae706eea67f49e989baf526a2257304f3cf98e.nq.gz
│   ├── 5833715d459ad2681a3a6e6b1a0718b302ee3778.nq.gz
│   ├── 58ad8c815dea9137114f4298b206b561c6fe7b7f.nq.gz
│   ├── 5e334cc5afcec191bf79851ab90c36c646fc5c66.nq.gz
│   ├── 5f809e5d6b1179c52fecc16b0e4e2b425f092004.nq.gz
│   ├── 62f65596fff7c417b807098863cfbd754c49ada8.nq.gz
│   ├── 652da128ea3aa5b87c886b15a893943ecc113f75.nq.gz
│   ├── 6f4952e7dd4562d5463ccdc1d3d87e364ce300f6.nq.gz
│   ├── 72197279950a5d8db5e607d856c7dbcd1ab45d17.nq.gz
│   ├── 7295f1bf51d6994f11dda5780f348a0ebcb1e81f.nq.gz
│   ├── 72b593017f104288fc1d4c874b1d8ea96c8992dd.nq.gz
│   ├── 73567027e37e832a4dcb9286a7feb1a0f9dd3fb2.nq.gz
│   ├── 74fc18052944cfbd7906975e895795a32cce3918.nq.gz
│   ├── 750c0db3e93a408076467af52a17b73911e644c8.nq.gz
│   ├── 79c1322efd8ac0a4ceabba81bcd6f02ffab0abcf.nq.gz
│   ├── 7c38f66207be23059ad2123360e5a22230ce0ae1.nq.gz
│   ├── 7ca8b873daa58fed306ae2a32f91d823b4dff679.nq.gz
│   ├── 7db0e806bab27f37cf43e6bfed06ed33b298db60.nq.gz
│   ├── 7e3e4c9927c4bdd1d08c2e48770abfbcdf2f3f86.nq.gz
│   ├── 7eb23c42c2af84f405d3c84e1e6abee910cd29c3.nq.gz
│   ├── 8118f330b42ddd7bb49fac93efe193cea2bf9d2b.nq.gz
│   ├── 81c6bd3480bbe39e7f672bf685ff8159de496629.nq.gz
│   ├── 8266ffe6244008712c1ad9cdcc5acbb0dfbe3981.nq.gz
│   ├── 84f3020917e5cd4cf8895da2e0195aed8e3679f9.nq.gz
│   ├── 85b32dc3c9a6da9233fa3c95efa76bcc4d687667.nq.gz
│   ├── 85e0f5bc04d7b815c76202d3fe3408abfbacedd0.nq.gz
│   ├── 87245c8047939beffa1d41f03acfb7849ee928c0.nq.gz
│   ├── 87cc695a3d711ba3e5b825c2fe7b2166f1c44084.nq.gz
│   ├── 88944eb890b40070979e93c599b64595d0d81fc2.nq.gz
│   ├── 88a9b20e1dc0321af373e2a69518b8ef290834a9.nq.gz
│   ├── 8900fb1572f2782de741fd0fd668f7321613d069.nq.gz
│   ├── 8c3e2ae075810548545777450b5cc1b2b93b9e82.nq.gz
│   ├── 9044379de849386e631f5cf238e6220863e3e0f9.nq.gz
│   ├── 90cee241f5ea1329d19b74fafdead0f5e0014e0c.nq.gz
│   ├── 92e9d59b2575a32ce7f9a23f3e34066e924afdc5.nq.gz
│   ├── 9851bf5d4848cbbdab214b231491ed452d99e378.nq.gz
│   ├── 99397f510e7969a1ed623111beca62c7916ff275.nq.gz
│   ├── 994381a470f4083ad6c8892f03a100d7b85e8522.nq.gz
│   ├── 9ac4e5e0e3a993ce93375650310471d2bb92d891.nq.gz
│   ├── 9dc95c97c665be2a9032c9890f722cf73a487ef2.nq.gz
│   ├── 9f44bdc75e86a30a5179940b5a0304935d1d141a.nq.gz
│   ├── 9f9c900d2bb4a582bd7b0081dcf8fbfc221de899.nq.gz
│   ├── a361f3ccdd27c70709775a380e5777bc669f36a5.nq.gz
│   ├── a524a468ad630c2743362de70325dcd26ff3cff1.nq.gz
│   ├── a588eb789c941ecfd07ffb2b7e6cba633371be40.nq.gz
│   ├── a6253cd3398bd9cd26b026b980ea863a6b768342.nq.gz
│   ├── a7f14e3d5e6720487fa5d64663857d4454d73d54.nq.gz
│   ├── aabfe24d01c9c7d53ff2b1d9b3159e22cebc854f.nq.gz
│   ├── ab0db488c35c2692eae835dc2a640a7b41c5d902.nq.gz
│   ├── abe1c870ee5f47b9fa587dc675ebdd8267eeb71d.nq.gz
│   ├── ac728487c77625dd4775c7812e6b5593bf124b3f.nq.gz
│   ├── adfcf761d3bf0ab23d6f1892a8b955ee4d9839a2.nq.gz
│   ├── aef1405ac6fbf58f65d592656883649fc1be9311.nq.gz
│   ├── afea033e356ba3889353fa6f91f218a05a183ed7.nq.gz
│   ├── b2292a3ff034fe6c7adaf6f659899364b05ead65.nq.gz
│   ├── b24f90b8e710956ac77709209601d034c5595a66.nq.gz
│   ├── b511c2ddbee4d550c059296c786ef0ad30a35993.nq.gz
│   ├── b59bdfbad4ce7221cfa170c9e3bd3e6fdf02c736.nq.gz
│   ├── b6d4036d057cc16bc394d43beb8b74187e8efcd6.nq.gz
│   ├── ba63992f3cb7c7558a30d892974d25a1029db909.nq.gz
│   ├── bb440fdd75c828d14f90783310020746cf2657e6.nq.gz
│   ├── bbcd80d9149189b5ef4e2941d065639461eea887.nq.gz
│   ├── beac5c79413d105478dce281348eada6790f4dbb.nq.gz
│   ├── bed94127670f2cba7a0e6598052bec39c71bbe47.nq.gz
│   ├── bf3bba4044118dc0a0cc9406c618f39cdae2d7d1.nq.gz
│   ├── c1c770f0cb301332e9d119d081e31abf77e1488f.nq.gz
│   ├── c25d93e083bbbd2f00943056b619aaedea206e52.nq.gz
│   ├── c5654a5f8fa461b7566e1c749fed77421f64025e.nq.gz
│   ├── c5fdb65d9fd7eb58caa6cda5cacd088217dbf33e.nq.gz
│   ├── c6fc76722ffa44418ab8fb4502fbfebc345d5f30.nq.gz
│   ├── ca6eb94b3e3e725314575320f55c2f4b90b80701.nq.gz
│   ├── cc9fed679bea6e58086b0e4f8a75fbbffe8e3acf.nq.gz
│   ├── cfd8a846b9e892aef806f331d7991e2c76224d51.nq.gz
│   ├── d272f92981bdf783d529ad6945429b7bfd743d54.nq.gz
│   ├── d53a1c278edb9f3d115b3975634aca1646e786ed.nq.gz
│   ├── d89c2230541171ab5a0938aa9ba4c8c272497edd.nq.gz
│   ├── d90ea56eda0616a32acc77a3835da4f71ad14e84.nq.gz
│   ├── d98beff4d285559051cb7056c664c320bc2d0d6b.nq.gz
│   ├── d9dc10d4cb5fc79c07278672bd4d038de9adb5fb.nq.gz
│   ├── db697cc6596ebf755886ffcb0c55a35b38b9ba9b.nq.gz
│   ├── dc825ae590bf62e19224bc9596b420df7a41350f.nq.gz
│   ├── df2e5d2da32d5e1523f5d4068321148918c5210c.nq.gz
│   ├── dfa0fca59b6a95fcb7e9354c8078aaeb63be48e1.nq.gz
│   ├── dfdf16fcd55ecc46cb1f9cb4fdc655fa0cf5460f.nq.gz
│   ├── e04d9f81aeca40f8f2b7d062ff570b704a0e5280.nq.gz
│   ├── e11e9624b407ab7ef7fb333338afa3670c3d3f64.nq.gz
│   ├── e2ec9e33a9f00f30b7e5f215476112fcfd1d219d.nq.gz
│   ├── e554a00d6f27ec8e0d5f6a478124ed7619656f78.nq.gz
│   ├── e58801b32d9667503d5bd69867fe0ad87b4a532a.nq.gz
│   ├── e6cc5f4b8b68efcd3b0f427f7e8202689417c5b0.nq.gz
│   ├── e7340efc639023c50445128a83ed4734412e707c.nq.gz
│   ├── e7dbac995b59a7fbb514634f86d2ca04a1b735eb.nq.gz
│   ├── e7e8f9093abaf2009c26122b7ac5bdcd15fc19c1.nq.gz
│   ├── e879dba6e6b984ed2dbcb345e263f6c09d30c818.nq.gz
│   ├── e956a7189151bf820c243b9e57ee885d9d3ea68b.nq.gz
│   ├── ea8c4bf7f35f6f77f75d92ad8ce8349f6e81ddba.nq.gz
│   ├── ec1dd6d116ecec26e80185c3699e7db7648164eb.nq.gz
│   ├── ed276ace9e7e6bdc57b2026021affbd007c551ce.nq.gz
│   ├── ed7b794278fb13c3312872b11eec4e81dca25ab8.nq.gz
│   ├── efe4111bf3eee90bdc016a39e3d2c06f0aa940cb.nq.gz
│   ├── f0000f3e41cb898fe05d9a8f72c1736ecaa38fda.nq.gz
│   ├── f05f37f7f1e666a6848697b17c614bb4db28b11a.nq.gz
│   ├── f87395baadd95d053017d4d70b7b04b47e018d3a.nq.gz
│   ├── fac2346e9e5c104dc446d3d144331ff4c6ecf2bc.nq.gz
│   ├── fc411488cd0747ec31104465f4c5f272c6926417.nq.gz
│   ├── fec0898a3d6d9781b3899874bb3a26c005e840cf.nq.gz
│   └── ff584ccd524c74ad582d90e525fd5ba079261a14.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 128bf6230c03d39dbb7f301ff7b20e594e34c3a2.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 152 files
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

[samuelcolvin/notify](https://github.com/samuelcolvin/notify)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
