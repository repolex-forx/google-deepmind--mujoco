# Repolex Knowledge Graph of google-deepmind/mujoco

RDF knowledge graph data for [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco), parsed by [repolex](https://repolex.ai).

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
rlex download google-deepmind/mujoco
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 651bae11c3c38efe483f033b4b7e869e7ce3f4ec
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 651bae11c3c38efe483f033b4b7e869e7ce3f4ec
│           └── chunk-001.nq.gz
└── blob
    ├── 012970b447f9985dd338ed4ff77babe17d0871c1.nq.gz
    ├── 01c9703bbabd1b31a6e5cda47d692ff2a26def62.nq.gz
    ├── 01d0a5036f47931b286f40c3bda70e04c670efae.nq.gz
    ├── 01f0183d99b18bb5ba6fc4761a95214828ce1243.nq.gz
    ├── 02c6abba56b45b01aba8958bc969a8299bdd8edc.nq.gz
    ├── 03a31d9d65f21f90b84847d446d61fb69d2bdd47.nq.gz
    ├── 040fb9ac2b7f9d72464c359f7d0b35faebe7778c.nq.gz
    ├── 0464ef7233fba92d0ca877aff78e2efe46d34773.nq.gz
    ├── 06a2b7e7745f70bd4dd32fde52ac16d7b84fceec.nq.gz
    ├── 06ea6d32c38be25ea15fe3a80340881c2e0269bc.nq.gz
    ├── 07998425e79c18a2da4178b6911e06369a9d9798.nq.gz
    ├── 08500cc46786272284269db9bf889dd8737a7524.nq.gz
    ├── 0875358a9948279bf6dd55d8517effbafb78979c.nq.gz
    ├── 0a19ddf78608eea86f3576452385fca23ec4845d.nq.gz
    ├── 0ab791f05ad6b022e573a7bb13af6aa0efdddc1d.nq.gz
    ├── 0b509cc253b139da4f8cc9a0f2b22a164e9e2499.nq.gz
    ├── 0ba11f8626b9624760d4c4e8aa560d0c64099b85.nq.gz
    ├── 0ba381e5c71a48c59102b9991f461257a7588b2b.nq.gz
    ├── 0bd77ea0f713e1894b95fc22c443708277592177.nq.gz
    ├── 0be1c1add18418b9094615471a95a77f362cb077.nq.gz
    ├── 0c1c08b14b51188ba03cbd2a51c517dff64b9c35.nq.gz
    ├── 0c8084caffa56dc275f80aaa3b44a2347e0570a0.nq.gz
    ├── 0ca53ddab1b54da130568a7f37793417c4fbbc9b.nq.gz
    ├── 0cbf4f27016ece3a27487eba1e1cf7bf7b6b78a4.nq.gz
    ├── 0ce6d969d1c97ba0626d05ddf76a804465d0f699.nq.gz
    ├── 0e59f1e459d71b7566aa247b8c7feb416bda3dc1.nq.gz
    ├── 0e72b6a2b9282ee7e9da22ecdc80755918e8dbd5.nq.gz
    ├── 0eb41494644188c166557b107465e921007e3d48.nq.gz
    ├── 0fe99feb3e8e056cc9e081565aad5c4ecf557721.nq.gz
    ├── 1011f169f4debdebe930846bd1cd4550597f7231.nq.gz
    ├── 10414fdc53cfe3f80b31b716988f3288ea7997e7.nq.gz
    ├── 1094012302a91326fa46d2cc4714bb51b2d17681.nq.gz
    ├── 10cf7dfc40e6368b3393a71500acffd36c3d6341.nq.gz
    ├── 1140f49678b885162aefbc139059aef8970c40c6.nq.gz
    ├── 1211b82379337e3fc3987690b5ccca85b842b401.nq.gz
    ├── 12ace95765301127a3d59081dc970b53755d720d.nq.gz
    ├── 12d033089bdb30c6f6cf7c712f3b5d3953203329.nq.gz
    ├── 13a3586b31e820374e6c9d8e53d3d75b8e803b83.nq.gz
    ├── 1422ccab7dcc0f2193a3774d09f86410d3d1715a.nq.gz
    ├── 14382a782eb280cdd5898972816497b8b466dc45.nq.gz
    ├── 149915b859b47cf4efddbf5399284a96ff054086.nq.gz
    ├── 152d90d488d299a4b3c01bb042b9096d424b057c.nq.gz
    ├── 16187b4d10dbe8aa8aaac3050c806284299c35bc.nq.gz
    ├── 168310bcbceb3cddde803f1537824f0c73797d8f.nq.gz
    ├── 17182ec16f55322371a53afb0dcd0dab10188f6e.nq.gz
    ├── 1839436e429e1f6ef21f248d503e91780daacfed.nq.gz
    ├── 18577bc961c6001c60190bc6ca0c3e3f63a5acf3.nq.gz
    ├── 1886f514a2ff8dfb249c6dab50d0adf1a71f43e4.nq.gz
    ├── 18d916e09d74eeb6f6503620af2c1c47bd5e02ea.nq.gz
    ├── 1a5aacda1694b75937742cebf1769351c78ff4a0.nq.gz
    ├── 1b42d5f2f1b499708595f488a1f6f4012983ec1a.nq.gz
    ├── 1b4e68e8b7c8aab821172042bc6a2ac50dce8663.nq.gz
    ├── 1c5ff755e845728144802429382683da341dbf09.nq.gz
    ├── 1d055fa4ca4d4c50329687d64af59b115ef25547.nq.gz
    ├── 1d69b88b163847f3ff11a235f37cc450718036db.nq.gz
    ├── 1e0358b84512ee5ad63926d7ab943a4859668740.nq.gz
    ├── 1ef771560460ffa7fcc934bed6c2a7fe9f9721a9.nq.gz
    ├── 1f5a5306991411ff55ed8cae03c8cae2c0c46710.nq.gz
    ├── 1f98808d49a998354354902a7ba5b24adfbf6e23.nq.gz
    ├── 1fcdf0b84c9a525bc671d8633ac7515b9be5549a.nq.gz
    ├── 20281e6151c1e80f99ec0228db34f5878f2610ae.nq.gz
    ├── 22a0b82f45cd3cf35da4cd64870990b594c3f679.nq.gz
    ├── 22d78c7f0610eca510f53b011fda94ae8e225e28.nq.gz
    ├── 22fcde5eaed42e9281756aacfdede509ac4933d1.nq.gz
    ├── 233c20b1a65fe6a4977652ccc5f4ba7d83d2c6e2.nq.gz
    ├── 238a494ba5b303484cb33bf13d47c6486f058a4c.nq.gz
    ├── 2397bf8c13787ef2d8f1b43763cbf727414e824c.nq.gz
    ├── 23a81010c6b7111e44acffd4a6dce1b6de610a26.nq.gz
    ├── 244e71a3ad8fda5b64ecb14c471ba8b7aa1aa092.nq.gz
    ├── 24f296e29f0dacfe2efb58426741cb173155e8bf.nq.gz
    ├── 257c6c07042ee5d0cd2fc781f307e78995e39167.nq.gz
    ├── 2612c78f697b81b9b9bfb878f91b0f2ced388bdf.nq.gz
    ├── 26d0a98be379ce9625139a97b9fe04ea9684e56e.nq.gz
    ├── 26ec62269a1f1906a7c950839a90aa1d253d536d.nq.gz
    ├── 26f0a2f1e97c21c39f5ed82204cdce5ac4652ef1.nq.gz
    ├── 279978af72307e3979f22d7ea891c0f4ddc133cf.nq.gz
    ├── 28dac939c54c7e33e5fe64ac658f341c5d25b408.nq.gz
    ├── 291674e32417ad0a9b66e71df5da97dd187618dc.nq.gz
    ├── 29708bc7d3e6d824e49291d02246dfbade8bdcab.nq.gz
    ├── 2bbb2fac01daf8267a99d9a1f74d47bfa78181d7.nq.gz
    ├── 2cb840de6cef3e8bbb3a721eddddb9bd85fd7c0c.nq.gz
    ├── 2e8658d22f0f908ddccf0ba5cc5436bb66ca90c8.nq.gz
    ├── 30a5f3d446f8fbae5b75d84bcb26b976a0cc70a6.nq.gz
    ├── 3209879ef4573cafb15e433366ea4f8c6b28435b.nq.gz
    ├── 3377006b203a84a731fc56ccb6411334c5933a79.nq.gz
    ├── 3398d634e1aee53162e17ecffa4319eae7ea06cd.nq.gz
    ├── 33a0ca0f632b6158fc2a16df7548ccaa62a414be.nq.gz
    ├── 3482d0a5ee1be1b2457f63f5baa37e60b47d5e48.nq.gz
    ├── 348db943cbb6cfe378a9e4273813af58da7f5adc.nq.gz
    ├── 34e814c95eafdf1626e6f22e1ea2f781899b010f.nq.gz
    ├── 358c6aec4b91d5981d3f376a50c5f7450debccbe.nq.gz
    ├── 35b48b3830a848e87f539409fa8147786491eb99.nq.gz
    ├── 3787db6f630788aaff035cb81ca7fc9a0951abab.nq.gz
    ├── 37fb519a31a8efed17f71f4426996a135f009f51.nq.gz
    ├── 38671f21c12a203b72e1973a3ac39a3a2895bd39.nq.gz
    ├── 38d414355efff6ca52b31ec032dcd33e8bb7e9fe.nq.gz
    ├── 38e81355c861154bf8dc169aefcfe46235b08659.nq.gz
    ├── 39800ad6827f63c6ba652f6b22bd9164e670713e.nq.gz
    ├── 39e77e3b35dd8d239384c609d7f01de50783683f.nq.gz
    ├── 3a23c2c892548522e18a3e6bb08cc17c710aa942.nq.gz
    ├── 3a3d2275637f86a5cfe05d5af39752dba5c47ce5.nq.gz
    ├── 3bdce83f5ad7682f93d4fa20f4e248691203f1fd.nq.gz
    ├── 3c4265d326b0711d9ae6adbcc8c03e7e4bcf277d.nq.gz
    ├── 3d6b697787e5ba68e08a405959951b24c2bc6c92.nq.gz
    ├── 3d82efefbba1118b1f5823aa0dc09f9be3991f18.nq.gz
    ├── 3dde2baa07ad8feba3286dcd6955caec31de17ed.nq.gz
    ├── 3e4b16c323f02e3b1906611b6eaac9fb6e56233e.nq.gz
    ├── 3ed9c5fc7d0c6dbd1f818b232e2ded5f94388e3b.nq.gz
    ├── 3f6fec32bfd891f5b9e9bed0bbb06adeaaaa271d.nq.gz
    ├── 413d46753fb3b1005a7284f979440ca67468c7ff.nq.gz
    ├── 41e203f8a21b674ee4160bb595675d987d41d865.nq.gz
    ├── 424905e15295a0bc25419ae2578e474c3fcf4bdd.nq.gz
    ├── 430de44dcf9647b0248b0b27b7a83a12db09ec59.nq.gz
    ├── 43699ea89a583a73e5aced0fb7bd138c0a51fe3c.nq.gz
    ├── 437477bf77edac71fdfa3f9869f2011f3d0b5b47.nq.gz
    ├── 443754917708c2bcff4b9a10e73aa4c4c573fe8f.nq.gz
    ├── 4443f4bcb3877910eacdcb37c3bcbe577cede19e.nq.gz
    ├── 444a8232447b23744d07f6f38ef274ba0ee84349.nq.gz
    ├── 44ee699e5d24a3a36095d5d2c32739d9921b931a.nq.gz
    ├── 455b45c6004f36f6fddeeaebda14fe27ce38072f.nq.gz
    ├── 45e1febe88ddc7442bb9e2f6095a50e729c0afc4.nq.gz
    ├── 46865eacfbab9afd8f051096760ace1ab3ef059c.nq.gz
    ├── 4810ec2d18a194f28a4b9254a44bcbfb3705515b.nq.gz
    ├── 484a3a3b9242dfa745ddd010efd6fc471254f613.nq.gz
    ├── 48fb29aff4a086c4728baf071ca7314ac733f2ee.nq.gz
    ├── 491171de83a2c8d169b8013c40794377c19b2d01.nq.gz
    ├── 4adfd5706f848e7bc4482cb722d88455a06dcc6e.nq.gz
    ├── 4afc67be0c1267146a02d194f90071de4120969e.nq.gz
    ├── 4b85347fd7d13aec26dc7a09b1cbda5d9f58cba1.nq.gz
    ├── 4cab6cc37b144e897c856733a4de44c81370e84c.nq.gz
    ├── 4d6fef358e50772858c2a4ba0d60f7499144701b.nq.gz
    ├── 4dbbdef621cf709d808957bb12337152575ac542.nq.gz
    ├── 4eb022811fa5054b0dfcfbaebe8646d8ce478c23.nq.gz
    ├── 4f88762b4026b164139ccf27b5c1d066a950c928.nq.gz
    ├── 4f8af64823a4266cef9ecc41c41db1a3fbb81077.nq.gz
    ├── 4fd2b146a13c8972d92a85e3ee5cd8fa9b7c7b64.nq.gz
    ├── 50ed82e440b5af870f881ac2567dd5a9c3d4dc10.nq.gz
    ├── 5180de813a8f70ba5198ce7082c86277fa39b6b9.nq.gz
    ├── 51949e599225af64fa30f015cf710d71168dad4e.nq.gz
    ├── 51952b3af7701eae64ef59314dbebd81c60f8967.nq.gz
    ├── 51b9810b4ff2531f41c289760ee7af4a5d11544b.nq.gz
    ├── 51bbd0287adba63e95716eb308ae9256740835db.nq.gz
    ├── 51c2172aaf57fc2c936de65cd4c25895ffec0ab9.nq.gz
    ├── 520969d26da3db585a055748d6179c26b5e76bed.nq.gz
    ├── 52c5187caf6868c6efd9acedbc091745d38fe348.nq.gz
    ├── 52e68014610a152d9b085f4443435b6ac8d350c8.nq.gz
    ├── 52e8b23d86b31156e821ff18ec9e68699457a6c5.nq.gz
    ├── 53692919cc00f91f4624d5f7ef219857e8b76f36.nq.gz
    ├── 5384c9a23d672e013a0837af5c6e8ab56aebe52e.nq.gz
    ├── 538b728fc6e705d832d0a2a1cde4296808ad030e.nq.gz
    ├── 53cd0c7137cfa28a6da0b05f6a66de94000a4936.nq.gz
    ├── 56af2b1ca9ade7ea59cb0293b3b0083f47f9ec34.nq.gz
    ├── 5846b1ec92abae69d9effa8997dddf40a3a76dc0.nq.gz
    ├── 58624198b5dcf786d575b2342bf47bdd2eef1396.nq.gz
    ├── 58b5265d933779d3ef2d2e68718b2c5e48cad628.nq.gz
    ├── 591b0898838dea36b0d2e621ccd65d347a5d22b5.nq.gz
    ├── 5947b31ac98e5202dad33c4f2e34c61b654eb025.nq.gz
    ├── 59885477b37cdf1d0f52f46ff53f15dc57e795d5.nq.gz
    ├── 59de76491225bf103d8528bed149aed0a105e108.nq.gz
    ├── 5a9a35dd536bda1c28613b05fc0bf18ed29e36b8.nq.gz
    ├── 5cc025cf7d91fd067fa2a4485b56c43ac479d7f6.nq.gz
    ├── 5d08a7517107cd167e3dbf931f9e0387837fb561.nq.gz
    ├── 5d1b1f69413c146e92cac083affa1056c5d039e9.nq.gz
    ├── 5ec8426ab3701f0fed117b8cbc9cfa2ec853f39d.nq.gz
    ├── 5f077f4cb87f718cd70660abf57abe94a44b9ebd.nq.gz
    ├── 5fa58da974fc66bc2c46623557c86f39f1b1a087.nq.gz
    ├── 5fabdc36e0139deda878889fc49e3ac86be451dd.nq.gz
    ├── 5fedc3f728b6c0b1f53601c45f946ed4971d61b7.nq.gz
    ├── 6036211eecddb8b839b37bc28b565b16515f4e6c.nq.gz
    ├── 603dc775f98ad68db0df0972dbb842c8ef156572.nq.gz
    ├── 615875849c120738c28960f380654ec818c4e1da.nq.gz
    ├── 6174560cc5ff1363d17dba14916a2289045dab8d.nq.gz
    ├── 61a47d492a0edb36e6d464edf9e4286bb98ebf28.nq.gz
    ├── 6237625754220e9a140438860a2009266ab8a081.nq.gz
    ├── 62f4cc19129e23d52e4cf3adfd4ec08563a991b4.nq.gz
    ├── 63b9f21d15e6dc258034f012f03c65871ff78a75.nq.gz
    ├── 64662eb4e075ab96ac596e6318c30ed263376986.nq.gz
    ├── 648520c935b53d549c4c808e872a1b1cd879e61d.nq.gz
    ├── 64dbb44ac3358faba213ae5dedb757218331419c.nq.gz
    ├── 664e8bacb3fb264efbf99b0814da033f87e70af2.nq.gz
    ├── 671cc12e48665627b1cbfb42f5dd8ae20e162f34.nq.gz
    ├── 672674ad503fbff91ce12c0e136290d9ca3c583e.nq.gz
    ├── 6782c03a0c85ac6075433305f027061f7e88b2d2.nq.gz
    ├── 681765bd634b51a44c6ddcb6178c1dd017000e16.nq.gz
    ├── 68263c633c60e119790c51f15447f6a850738806.nq.gz
    ├── 6833f2c84b2fe1dd01b9c2edf584e51cf2796f10.nq.gz
    ├── 68d0ea7cda7964f69d6a1af07d690fdac4c2bf88.nq.gz
    ├── 69bb0ecd19d05adc598d37c0d6c827884a0542d4.nq.gz
    ├── 6ae3e13784b6ca7af02846d948107e9f28c060a8.nq.gz
    ├── 6bcae8ec9d1e95cc7bc3dddd963a82596c1eff5f.nq.gz
    ├── 6c851a959bde6aa998e73436bfdf942e83d88bc9.nq.gz
    ├── 6cb2644f60ad304daf12d353c3db940a0194f322.nq.gz
    ├── 6deea84cf52ccc4f2591246adaa0af54c885a5d8.nq.gz
    ├── 6eac0a6f2522d524ea6e88fdcd0eaabcc9fe8f26.nq.gz
    ├── 6f16e9f4ee4e043ccdc4720c8350193f9c69c68b.nq.gz
    ├── 6f1cebf7aa09b36b221ef097afaa7fcd4dd8483f.nq.gz
    ├── 6f1d1d1b243cff8520dab6561183cfe24a1b9829.nq.gz
    └── 6fb1f708e605f3008779297e8566215f5d322455.nq.gz

7 directories, 200 files
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

[google-deepmind/mujoco](https://github.com/google-deepmind/mujoco)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
