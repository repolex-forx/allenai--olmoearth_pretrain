# Repolex Knowledge Graph of allenai/olmoearth_pretrain

RDF knowledge graph data for [allenai/olmoearth_pretrain](https://github.com/allenai/olmoearth_pretrain), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/olmoearth_pretrain
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 13ca06ffaf0247bd49b8a4fccf705a3a85fe9d6d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 13ca06ffaf0247bd49b8a4fccf705a3a85fe9d6d
│           └── chunk-001.nq.gz
└── blob
    ├── 0053ff8a00248e2fb7d36075eaa0d4c216042afe.nq.gz
    ├── 00922e1ca4c0d895cbbb4daa838d952beb9be9e0.nq.gz
    ├── 013ddea61e29020e109a60441ae91ac8acaa5d84.nq.gz
    ├── 0144af76e04de9a5d0e68b15c4ef4524ec65b7a5.nq.gz
    ├── 01b2ddecd22cf154de882b21616b9527d1abfe59.nq.gz
    ├── 02281ffe4641476463807e49c7c878f539ff0428.nq.gz
    ├── 02708e27b3edddaa8d3b2217d3a772da66566855.nq.gz
    ├── 032724089136327b7df20d940199628e143aa77c.nq.gz
    ├── 0345b91ace2ef52c2136df967c9d8e9c620c9243.nq.gz
    ├── 03cd63d41b2f55aa859aaa8c43ae4de2535492d7.nq.gz
    ├── 04680737386e141a6a9b5e546aafe478a63dfe48.nq.gz
    ├── 05698a084110cdb9cd730d83261832e76924f700.nq.gz
    ├── 06186d9e538d34327950eaccc00789175e3a0c4e.nq.gz
    ├── 0645934c5fdf1c83a064a7550d987887202ad14d.nq.gz
    ├── 0657d7e13f02e79d043fdc07bc33430715bc5c7b.nq.gz
    ├── 06a81a992718ad16bf1443adb8cad8bc954f98e5.nq.gz
    ├── 0a22c299cf9fe8c0e8df6ec3a66f90ad6e216c3c.nq.gz
    ├── 0a5eb6cfbc4b81d508f035b8be43d48d992e0391.nq.gz
    ├── 0b65eb54f2525bc0e10db83b6de48b3e8e69bfc4.nq.gz
    ├── 0ba7b7f159748d9d28ffe3c2e4ba8fbc61a077c9.nq.gz
    ├── 0bedacc99b2112c889bd59dfbced83a9dcd3627d.nq.gz
    ├── 0c4706cb7524a74ea3303369866602ba27778f80.nq.gz
    ├── 0ca6d7b15e50d32ef6e545c84bd2864e1367bae7.nq.gz
    ├── 0d124803b63fe5b7427c7af532efdcce99fafef7.nq.gz
    ├── 0de003539c490cc620a9ff051d388e7a9bfcbb10.nq.gz
    ├── 0de66e63e1381fc39977883780eacba7791f33a0.nq.gz
    ├── 0e586c15d40f1aaead59128f2b42d9cd37422001.nq.gz
    ├── 0e5eb4e30e1992c6e120f6edb6adffb2014799ac.nq.gz
    ├── 0ef8748f59c3d31b8ba2438f72c8a6c4f7fa3b58.nq.gz
    ├── 0f074cc28c0f48532b26fbb1f3909de295437502.nq.gz
    ├── 0f1f75ceff8a91223d4089f6b96ca881841ad977.nq.gz
    ├── 0f645b87107c8798ff159ffedd31fd6eef8c3d05.nq.gz
    ├── 10db2bdeb7d18f11c5ce097881cc145e29a9e18a.nq.gz
    ├── 11d0ac94f03970d7adc10991052f347540dc81ff.nq.gz
    ├── 11d4abe81fb0ec68bb17b826451b3ad6643561cc.nq.gz
    ├── 12be33a88efaadfc725b2a2a1db6d0929832402c.nq.gz
    ├── 134cb2c7b9e7399258739b0f8b2df4d225b45972.nq.gz
    ├── 14000fcfa398b10e38bb04599e86dbba2de897f2.nq.gz
    ├── 141339c11a9d3108ea0bc24e29e17fa83a254ec7.nq.gz
    ├── 14856903144b3aa1751492a9d97bf15f9837b4bf.nq.gz
    ├── 158b00f1d6eca09bb005d0a59ca54fcbdb8b6d7e.nq.gz
    ├── 162b67d2896c6010094e08a8e619172be51f68a5.nq.gz
    ├── 1665e79a6cd6b98f1e7420e2c4841d2dd5e5bda6.nq.gz
    ├── 16c67158392568c4ed7ca52b29699cd5af42f400.nq.gz
    ├── 1868f0ed1013ebd5635868bc082cbb6394efdada.nq.gz
    ├── 190c77a29d2e0c4c0ab9c7cb1b545d96214c4401.nq.gz
    ├── 193f3851cb61c0e4262e9fee1052eee01dee40e7.nq.gz
    ├── 19562d3ddc7b723f8a5c6282781bef171aef7bbe.nq.gz
    ├── 19579c09df1f687272c3a67a1cc3f0c853d8f103.nq.gz
    ├── 19a31b26eeaee848a709abe126d45572691ea08c.nq.gz
    ├── 1a445ba3ea5d7ef13a6b057f81baad73b75d0237.nq.gz
    ├── 1a5d9b1174e028e52acd7fc3d8f62a7d1584e287.nq.gz
    ├── 1b900329d97c6982150a5c5bfe749de342e7982a.nq.gz
    ├── 1b9282641c9db660c1b797377849dfadc02c7c54.nq.gz
    ├── 1cb5cffa6ee0f033772dc11bde3dc0e4870a17fa.nq.gz
    ├── 1cd7a9713ff5efd4951c50e41305aaa63c7b4706.nq.gz
    ├── 1d6b047a9209f2f03b6ab55a37684afe4ad2642a.nq.gz
    ├── 1d8d07855bc6749edc7f097c33e382396e58105a.nq.gz
    ├── 1db4639df92dabd77eb382ea56b61560874bb65e.nq.gz
    ├── 1e9a60ae086aa9817d0c173ec1d25f1f4d706d17.nq.gz
    ├── 1eb9a4887cd77e906a1f51c9ddb2aea17b78ef44.nq.gz
    ├── 2064bdf6b0c0a69edb5786d03ed64e461b14a9dc.nq.gz
    ├── 20ad490a5e3e860d722a803028f9966048a68bf9.nq.gz
    ├── 213d874b4582856e28bd84c238256cef50b61bfe.nq.gz
    ├── 221818b33981681b405e5e96af6f91e8d8bf0e97.nq.gz
    ├── 22280f7967b4858860e78d81d75ea99d6e26f35c.nq.gz
    ├── 251fa809b1c2d73e83df0c29622b47852c0c5651.nq.gz
    ├── 2564776f30e9bbad831b8f7406009d5fd600c82a.nq.gz
    ├── 2598659b60528d1f1eafb88b78c44d67ff39c78e.nq.gz
    ├── 263fef484355ab6280fc766a7c9a93a65028fe26.nq.gz
    ├── 26778433265058e92cc0ff0692b3b539c706cb69.nq.gz
    ├── 26d9e1795b08a0b5e3fd210e84d9fe4c29b73b0c.nq.gz
    ├── 274b776d287da064281e513953f3efdcc9eb1e2e.nq.gz
    ├── 28ac1d768fbb0d7da01c8785d71a007fc3a6e0dd.nq.gz
    ├── 28cfdc4aaab09524de9f0bbaefb2ba82e0174324.nq.gz
    ├── 298f1fb3f815b492784abdc252176f20e34b0ee8.nq.gz
    ├── 299134d7080bb18e25132d604cac8f9203cf5a84.nq.gz
    ├── 2c12e63502e408a6eaaf1a05c92f3c5f94c5dd2b.nq.gz
    ├── 2c58f6c73bc4241b5234a3754eed8d545ca934e3.nq.gz
    ├── 2c8d9e3807fe824d746f0f9782069a17de5c592f.nq.gz
    ├── 2ddebd3d1f7ee510c0acef7054dc2de2948f4a64.nq.gz
    ├── 2e029206a9a72512632dd8a7bda2e50674a76be3.nq.gz
    ├── 2f82e8bb3d38e2b92a341a98a1099534d888a792.nq.gz
    ├── 2ffae125074d60ad2b4a577e610eaacdd112635f.nq.gz
    ├── 306aa2e68d2222feea48483ee41ab24d4454d3c4.nq.gz
    ├── 30ba3d5ab2c8cd5fb68827d0a4afc9e847c1342f.nq.gz
    ├── 3193510acfc5e51d3633f827b85e33b84b2bb2c9.nq.gz
    ├── 33ce84567506fd4ae0473c7b66094e08f868bf82.nq.gz
    ├── 33de22d8f8cf5c20fe74b9d9e76b45dca820c5ee.nq.gz
    ├── 348854d1a222b0610628d88dc86977c3ad603614.nq.gz
    ├── 3493ed075e4a3971d9a61d02a645fcc75e669f8e.nq.gz
    ├── 34c93c06af551dbc167683547cdc02aad716a00b.nq.gz
    ├── 35df7cdc0a1d0fff802f03ca763af0ac70399d48.nq.gz
    ├── 365ddcbae7cbeed8687ff533b9b208d41815829c.nq.gz
    ├── 36a708f2f77fd6e98b0002ba3dbe4bd5e7819bb1.nq.gz
    ├── 36aec58fb2815ed9fe02b77e8f099197b367dbb7.nq.gz
    ├── 38e8ee24ba367e5791bbbd6d1f567d6e0938b907.nq.gz
    ├── 396aacf1a55030e1dc093524cd9d6eae2d57ca38.nq.gz
    ├── 39a5bf3c002a819555c11cfdf5c053078e662409.nq.gz
    ├── 39e2d7f077ea007e717b4049a97c619799a51506.nq.gz
    ├── 3a06afbc476f3ff808fc57dce5cc56480d718a14.nq.gz
    ├── 3a73d99a6bdd78eb2b985360e57330977738ab7f.nq.gz
    ├── 3ae3802ffd14adafc3d6608b73710292a9e1fb9c.nq.gz
    ├── 3bf1cfe113c199950944b880d17fdba33149d87e.nq.gz
    ├── 3c41c00d454f90824afa58da6f8380154e8a305f.nq.gz
    ├── 3c6682ba8acefa6daae23d2e9f5d6e85f20546fa.nq.gz
    ├── 3c7348dc55a3f6244a8934d10d0e2a7d161638a1.nq.gz
    ├── 3c9db59a3d7fce3ab5c587355e3d3c8e1f4d4b84.nq.gz
    ├── 3caa42af7c33ffa5e65ec8c29aa60bc10ee5af81.nq.gz
    ├── 3d5646b264285be76fb76248ccf1cf83646a5d63.nq.gz
    ├── 3d7d5b7b4983851ac9ede992d5802d581f3828a5.nq.gz
    ├── 3d879dba416fd023c466a27f4bfe395a9ae66017.nq.gz
    ├── 3dd055874c85c0b2f1df01513ff2b42eb152de6a.nq.gz
    ├── 3e111f00df323bacffe92e99dade764113552837.nq.gz
    ├── 3e95ae9c36ed9210a9f7f464ba8e0ba8e3849c6a.nq.gz
    ├── 3f00d2b4740e428a1a04c323827be12b01b91e6c.nq.gz
    ├── 3f7d7b5575b6c99dd985cbdf3b94b3c4205b31b2.nq.gz
    ├── 3f908b602501442616ca17e1525b07b8734cfbae.nq.gz
    ├── 40b5f902773b661f43dc6fa165bf2d19a1b261b8.nq.gz
    ├── 417ffc875e675b4017c9f3a845c46b27d4b6ba7c.nq.gz
    ├── 41816c2a4e6ac15e51a0aafa8904ed08b48b19f5.nq.gz
    ├── 419082d3bdc6c890d9b8c7fb45f4d9749d971969.nq.gz
    ├── 41dbc0c3fbf5d170c5d662866e0138def6976fc6.nq.gz
    ├── 42c655b88909416c9ca741d207ea704ed529385c.nq.gz
    ├── 42cb3fac674011357ca5a66513eb37ecc5aa1107.nq.gz
    ├── 439f496bca329a20585c2db6db66bbb0a42b893f.nq.gz
    ├── 44a6141758b6f82964caea5e137cceebd3ecf956.nq.gz
    ├── 4670c3bd644e395729355f7c0a27363b1c076cd0.nq.gz
    ├── 469530b0cc2b6f92a4d7c288f217b02dad128dc5.nq.gz
    ├── 4740ec35c75a2f2734c4747eb05901d1b99f2f32.nq.gz
    ├── 47465b1909255c009bcc44e9f724c0c4a139ccbe.nq.gz
    ├── 47cd2ba9ca37cccf96f4571afb110b3ae528c24e.nq.gz
    ├── 482e17884d3aa311b314d996133643406e8f2303.nq.gz
    ├── 486307ed9c8c702043dd69dba86cce307e03cbf2.nq.gz
    ├── 488c3a8ffb4bf9573cf412b2f67c4ac343e51a23.nq.gz
    ├── 4938e448bb3991e50cee58724c99d58efb083e7c.nq.gz
    ├── 494e5038473ef641ee9eb69b26d80f6ab3b4724c.nq.gz
    ├── 499b090c0ea2db14c401da1a2689df0a6db37233.nq.gz
    ├── 49f4d614c7756d2173236110dde8770f68ea188a.nq.gz
    ├── 4adeb9e816a1889f2a350ab731940fbe4f1caa5a.nq.gz
    ├── 4afdabb8fafdc982ebbe9e1fafec86e1406287ad.nq.gz
    ├── 4b1c04c43f69e6f6971177575af62de15cd3c57c.nq.gz
    ├── 4b689a4f2a8c7e8c509f9e3be70802951e5742cb.nq.gz
    ├── 4ba36e966dcfe133c06fce549d2c31b191990e6e.nq.gz
    ├── 4bfb5c387c7cd167d6746e19d886eff83fd1d3d2.nq.gz
    ├── 4c8c6fc5d2c6416f38dd7653a9ce4e0ea7b18207.nq.gz
    ├── 4d0c26a0dd1b4509d1edf6d0082ebe4221aa8436.nq.gz
    ├── 4d723d0a0520c2eb39dc63525738c10023162e02.nq.gz
    ├── 4d91a5b8ddfd6a5cb330065805dd42ac758e3303.nq.gz
    ├── 4db54816ce5bbcc38440ade0e99c95d292efc7d1.nq.gz
    ├── 4e694efe68f80e3843f10568af6ce60647e073c9.nq.gz
    ├── 50666f7b733c0e1aa7da470c46bad5b88c3746a7.nq.gz
    ├── 516205ca1da895c2c2949b6f0eca2bd201e344c3.nq.gz
    ├── 5250481277ed27c5c5a2c5017bea30fcf4f5b2df.nq.gz
    ├── 52f41c88d951b8f4bde977b122631453a956f6c1.nq.gz
    ├── 530123584b9eb57c3e8bbbfe883806d9f5f80be4.nq.gz
    ├── 5310a799d23cfb71f454099c9533e4dfd73eaf32.nq.gz
    ├── 541d412ee249495062421e173ff9ca704754866e.nq.gz
    ├── 5440c07fca509d2956b4b140a37eceb79ec246f2.nq.gz
    ├── 558ea9489ce82f86641a371bd0dc4ecd5438f977.nq.gz
    ├── 55ba1f13900710790f88460b1a24a508771f01b5.nq.gz
    ├── 5620a15a0dbd39f7c6d99a887c4617cb76d8e16b.nq.gz
    ├── 56895ca0d07028f3c0f2e0b22a988ebffd3212a2.nq.gz
    ├── 581ca41723560ad64b83df6abc3b840f8c13eb57.nq.gz
    ├── 588578e647820130052e2472463e87bbec36431c.nq.gz
    ├── 58c2e41b4af5ba2bd74d0329a1ecf717660671fb.nq.gz
    ├── 58f4c52c81b1b99b22e56b16c88dfaee38e591cc.nq.gz
    ├── 5931d75f6818fd15a3121d2f6c84f684e436094c.nq.gz
    ├── 594bbbd22dfe3c7efebb1b2741057c7a8f01d587.nq.gz
    ├── 59956ee5586a9830223459243e9c731e7e9626ec.nq.gz
    ├── 59b118e67b4f337c40bd39bf9d82f2c6dc475912.nq.gz
    ├── 5a6d9b9fe9b37e369f11c7e79c7ff14aff78c051.nq.gz
    ├── 5a809f6fe1ddf2463416ca94888d96f965f5b0fe.nq.gz
    ├── 5ab5e65f6e5c10728946bd7d2cc6e40bb16a4dc5.nq.gz
    ├── 5b123c7dee3ccdb8b574011973042982fa49821c.nq.gz
    ├── 5b398f849df9d8c5b4bcd65994a67083e55840f9.nq.gz
    ├── 5b4702906e5f76c0a36f9b8d928010f9dd2a52dd.nq.gz
    ├── 5b84917c64613d1536f258b63ece74251dcbd190.nq.gz
    ├── 5c3f62fcbbd8ee4a7c62d64d3a349865765cbb6f.nq.gz
    ├── 5ca20d9561fc65cc78b409a64d908b85f5dd3885.nq.gz
    ├── 5d058d436d49572dd76c01f538c7521fa77c114d.nq.gz
    ├── 5ecc8d33d3b40c20a5f5fbe78b59baf6bf1d39d8.nq.gz
    ├── 5fcfeddbcc20b2b64f406afa3806935bc27b5cd5.nq.gz
    ├── 60fc097cb190d00aceda163c5da4b1d8c7aa2e7e.nq.gz
    ├── 611cd1689d3f6ff951d1191787918d4bfebca1b9.nq.gz
    ├── 6179330e0225c5cfbfd2bd60621ae61429a0d779.nq.gz
    ├── 61db70130e2d460ad813e8cde83fa5cbc6534766.nq.gz
    ├── 628c36d13101031a3628202fba1a464529ef7443.nq.gz
    ├── 639986ebeb0039efc0e278f35deb0edfb9717b96.nq.gz
    ├── 63c4497d0c734f89204b6daef573c9830ecbdc98.nq.gz
    ├── 641fd87499da844b287e9b5e85cb428584a91849.nq.gz
    ├── 64a3317b076205cfbee0e9459a298a0620ac93d0.nq.gz
    ├── 663832c5d81407c5f9b9283bb56430d0b2643d1b.nq.gz
    ├── 663a94b522b96467040e0ddbcc6196653edac3b3.nq.gz
    ├── 66cf48124dd8f9a1addfa2de59534433c2dcef19.nq.gz
    ├── 66e13ba5edef15d86698482654a4e9b2aba9e6bc.nq.gz
    ├── 66e41d1f1f6f08b1417850caf671056e966d30e3.nq.gz
    └── 6753a54838b31cef2310a7a1cf135e1586c2aa81.nq.gz

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

[allenai/olmoearth_pretrain](https://github.com/allenai/olmoearth_pretrain)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
