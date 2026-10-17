# Repolex Knowledge Graph of spacetelescope/asdf

RDF knowledge graph data for [spacetelescope/asdf](https://github.com/spacetelescope/asdf), parsed by [repolex](https://repolex.ai).

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
rlex download spacetelescope/asdf
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── bb9f3c8deca6b5f747bad5773ea64c79f24af782
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── bb9f3c8deca6b5f747bad5773ea64c79f24af782
│           └── chunk-001.nq.gz
└── blob
    ├── 0062bcfb6f4345029a0561d910902ff1c9afa5e1.nq.gz
    ├── 008f90fe326e883ba9ca48a87993e47f5dff5a1a.nq.gz
    ├── 00d5f47ae9358fba0335a3a5e72b0f476f50a907.nq.gz
    ├── 034003708ba0d68e56306213556e8405674590fb.nq.gz
    ├── 03d30fcb45c3426a3d19f5b7663715fe6f161689.nq.gz
    ├── 03fe97724c024a833948b65c23a2788df15eb273.nq.gz
    ├── 04860917ca6ef88530b9b3bafa39faaeee578a3e.nq.gz
    ├── 055ff6b669c17006610dce5bfdc841565c60203d.nq.gz
    ├── 059615addbe386cd5ac71cd652e5e03c6275d486.nq.gz
    ├── 05cbc22afde5ebe6ba84957ca412277bde1e4b08.nq.gz
    ├── 05db23351bebd6b319a44950323afb9d5249e6eb.nq.gz
    ├── 068ae9e9c4a8a1f900105e9c7d307728528d2484.nq.gz
    ├── 06c9ea0fd44a8ea560f58202200187488f17ec97.nq.gz
    ├── 08588dc8e6d1cb66fe18f52a168f4de0581feeac.nq.gz
    ├── 087e950c57f01029edc77d1bfc62c6536be1e06f.nq.gz
    ├── 08a00a753f7826aebfbd229f9cd00c073aea6b60.nq.gz
    ├── 08aab829a2a613833a174ce6138675f03a5cb345.nq.gz
    ├── 09024919da72ad2de716a0484455bddf1a908104.nq.gz
    ├── 090f49a0bf53153927809ae5c25ae1b41ce4835b.nq.gz
    ├── 091127375e920371969e1493c1715fd35b72179c.nq.gz
    ├── 09cc3c2f64d9a12cf98e67da4ce448d8b66ecfe2.nq.gz
    ├── 0ab1faa946b456b66c2686b2fb037ec94be76a71.nq.gz
    ├── 0ad690dd512a8d486054cfb061d58eb53b20f221.nq.gz
    ├── 0adfc069e3f153ccf2b1062a4615a7d6095c2bb7.nq.gz
    ├── 0ae5fe68aec77c6389fafa2c74ff3cb6e8e10964.nq.gz
    ├── 0b72263e980a5d75b013cfe414eb1c5209ec392d.nq.gz
    ├── 0c9483dc2cf6037aaae278f59f5bbc67590341f8.nq.gz
    ├── 0d44bced73f4c088c35b4d32b99a271710024409.nq.gz
    ├── 0d780b2ac4495467451a210b7c8bccc5e09af719.nq.gz
    ├── 0e03f078af3933f565f6c7d3384972b3103b6dd3.nq.gz
    ├── 0e4211028576a0d934b11384d5b818bf665f0027.nq.gz
    ├── 0ea927b500d1351942750cf1d1d05886b7011651.nq.gz
    ├── 0f8e1627ac801206ce534bbb18ffd54699b6d5a0.nq.gz
    ├── 0fa342556b0f060c4bc39d2ea56c95bb98d04de1.nq.gz
    ├── 0ffa6bf47b54f3d3d7701984b4cd9382cd58a80b.nq.gz
    ├── 12339ae57dfa205590134a8f27c3d384566d643c.nq.gz
    ├── 1243015753008b755015666ad24c511e07c062a5.nq.gz
    ├── 12dabaf4f95a70ea0f0fbdd57b60f3a8d35c63f4.nq.gz
    ├── 13f8141730f874c6bc3adc1a6034c6bd9f5912b0.nq.gz
    ├── 148c2b4dbe156e3697ceac5a0963d173c6afb493.nq.gz
    ├── 1587d068160edd3f6dd0114e680fe219a1081330.nq.gz
    ├── 16022acb553dd22b92abcbdee6b91436d71f9388.nq.gz
    ├── 16d30fa3aa32a802c7ff2c70f348ab1a7d8dd80b.nq.gz
    ├── 17b4df5144ad5b4d2faf722f5d09efdab89698a7.nq.gz
    ├── 195159e6ba1df5ada6227b36f142897201fc1fed.nq.gz
    ├── 1b1e161d5b1e1bf556b7738ba7f8870ec88778f2.nq.gz
    ├── 1b268f9f9eba8286a3b64c57bb88496da058a8aa.nq.gz
    ├── 1b5748b9fae9893c29f06534ca951b77ece2c822.nq.gz
    ├── 1ba4fe8edcfad8f4e7c33453e58e8e0bfc433e1b.nq.gz
    ├── 1bb4846d75764028061e1df6c1894e1a32cb221e.nq.gz
    ├── 1bc8eb21d3e4babc65083056136f9ebb497019cc.nq.gz
    ├── 1c2cafcc19b0e23409b024cdde10ec7b5e4f79a5.nq.gz
    ├── 1c35d7e610a29e2c8c7b57db136c4fc1073c0b4b.nq.gz
    ├── 1d5e7d4940b16d52dda6beed1e9f9348611f7a2c.nq.gz
    ├── 1dab4a4343d304270cf9a4b8984d509b764123d0.nq.gz
    ├── 1de72b7b231ca34e550298b12b6ea19e37d50a9f.nq.gz
    ├── 1e28fc29f691effba8474ac13583d2bc79bd29ae.nq.gz
    ├── 1e830bec3b9b13ab4cd0f6c7610372055d73b883.nq.gz
    ├── 1f1e6fb384acc21ff5f5e229a2e0cae73420e90a.nq.gz
    ├── 1f353670995bc99feb47ae9316cee61b0303a8be.nq.gz
    ├── 1f44a6313216706ad77f390bae60bc9912088a8d.nq.gz
    ├── 1f58d97e3e664992fb5602fb76729f111db61507.nq.gz
    ├── 1fe384cad09adfdee8584bc37ac241a44b470905.nq.gz
    ├── 201237096be9cdae92201d7b019ab9db1f71e29d.nq.gz
    ├── 20767959c9fb3ba02cb9a872da36f8de5f53c944.nq.gz
    ├── 20e01a9e2a5d3a6a10c0007a11989796ed6012bb.nq.gz
    ├── 2123c408d9a516739378c5b2d35ac92079083d3d.nq.gz
    ├── 21263958ad362c0849c582c2e7bf2d83266ebcda.nq.gz
    ├── 2248a0c80bbfc51b67863f848f60466f135cdb2b.nq.gz
    ├── 22d310e13a0282629e07ef255a22a1c43f7a895d.nq.gz
    ├── 23447242c91446db77700c67ab050e15c92b74e3.nq.gz
    ├── 236a6f1da932b7d2195a7d912bc8bac8835e2a40.nq.gz
    ├── 23b962e4b9dbf64f27d41c44c57c691ec46abfca.nq.gz
    ├── 242f713229251499b17a614ac6b29083093d0173.nq.gz
    ├── 24f4689842cde0ef21e15c7cec50c548e439f417.nq.gz
    ├── 25ccc7001dfe183b008bb19d8b52dd83644e0d6f.nq.gz
    ├── 264a7832498b89f98cc6b9b775eb583d337a7ccd.nq.gz
    ├── 275ba581f356e944778e1864c86a1793a9f991cf.nq.gz
    ├── 28278886279734a80be2be819b002cd5f747384b.nq.gz
    ├── 28289ce9f8e2bf017901a144b1e0626134125fba.nq.gz
    ├── 284e91912ed552ec825fba1cd986cbffa388b75f.nq.gz
    ├── 2853d8209644dd0c131b638258e3833993c7e922.nq.gz
    ├── 289a9b66c13d5c19f907098e549ccb4081ebdc5e.nq.gz
    ├── 28b0c4ce99bf3d232f52cdf7000faef0ad8565af.nq.gz
    ├── 28fd947edfb08632a6411e7dfa7c1e16bf0d6420.nq.gz
    ├── 2934dcef9bbf916136e6fe951e367b04cdc9deb1.nq.gz
    ├── 29661ff9fb185eea03ecbbe59f1cea87178fe1b8.nq.gz
    ├── 29700fda3090d1c67ad9cb8a07f11862fc67a191.nq.gz
    ├── 29e69c1356b609dbd2d50b33b8e0f85053d224af.nq.gz
    ├── 2a7a5d871d8461a92b15f5498b9fad940ca7dd75.nq.gz
    ├── 2ab2843d3ea4e6ff3a8e2a891822cb207366333f.nq.gz
    ├── 2b1a51520e92b2ba0f450393aad92a885f7ab878.nq.gz
    ├── 2baa38e9f488f8e1aff21857a577a5ca51355348.nq.gz
    ├── 2c6f71f6b0121538654a87d245b5317d50c80977.nq.gz
    ├── 2ccf666d7dfd28069c2154efd87026b0d25ae46f.nq.gz
    ├── 2d4f25c727f879f6e16b654124c2f36a566192f6.nq.gz
    ├── 2edbe012c06aaf2d755e648e2fda0b2fca9b83d9.nq.gz
    ├── 2f42c5fdf5a0abaa681a0acecf9133e0144233d8.nq.gz
    ├── 2f6e056a9ac2399582eaf05985a26acf9161f213.nq.gz
    ├── 30458bf49a72322a002d5ccceee34d81fb23cddb.nq.gz
    ├── 3056376e1e9a1cd0691f0ebbe3189d5d67a9f8f5.nq.gz
    ├── 311c9ef08cbfdd659d1dd01e6b6217a3d64e3cde.nq.gz
    ├── 31bb691770b4295de236db11bbacc3c8668cddd2.nq.gz
    ├── 331c3781c4608eda057f7da63a463356c9d9dc2a.nq.gz
    ├── 333abbb8234ae57a9398ca7413257b072515cafe.nq.gz
    ├── 34491770a99ed9a09cc2d6fa93b303884c0dd73e.nq.gz
    ├── 34ac3b1b15341c3dd60ec2507416f0af2089cbaf.nq.gz
    ├── 354bb48bf3231c79e030e220a38f29475b7cf7b9.nq.gz
    ├── 3602c7041a05ca20910e6234af26e135d6dd602b.nq.gz
    ├── 3626c7e07f6896b8c23cb3a60f754cb93668f7b8.nq.gz
    ├── 36a437260ba56b10f77a1243537468867d8714be.nq.gz
    ├── 36c823e6dc6dc3624516a3cd36fb514746dbd31b.nq.gz
    ├── 36dab19a692467cd9f45f6ad58fe50e0a10dc379.nq.gz
    ├── 37e1f0951b8d60bf5baf4651b632cc3aa55b227e.nq.gz
    ├── 38561f74ed37ecb2a5a3f71fb5a746920ebd2dbb.nq.gz
    ├── 386c99e60de0dd65285599e5b742ee0f6759a381.nq.gz
    ├── 388c881086b9610931678cbbb496a1eb08455028.nq.gz
    ├── 38eb576c19a7868f1b7225dac9785e819e3b40e2.nq.gz
    ├── 3931751bce96bdf3c6e9eafeea58b6af5cc191a0.nq.gz
    ├── 39a35097f8eee7d3b6bc663d0abb356fccd8bc2b.nq.gz
    ├── 3a2e5e44bde4d91ec4391429b7384fed5d1e24e2.nq.gz
    ├── 3a58bce13a0e19b2684d635e1edf0b1d7385661f.nq.gz
    ├── 3af875c9989e2b890aeae94ed211e620ff772a02.nq.gz
    ├── 3b4579c9f9bc6c7dfd8e80d8a0bb0cb2b26f9aad.nq.gz
    ├── 3b53a6b371a7b6b45ed28dd8eb352703bd58bd0b.nq.gz
    ├── 3d7371f59d20dc89b0f892500849da054c1f65cd.nq.gz
    ├── 3e4fca1d76ed59154243e6f86e5b23a15514e7da.nq.gz
    ├── 3eaf9ce2d2c01a5e28084948ba4051831056d727.nq.gz
    ├── 3f09158deef0a562dab603abda92e2a52806f357.nq.gz
    ├── 3f5a7430b27d2391f47f580861bd90993b8c4412.nq.gz
    ├── 3fedeb67565a4f092b3a63c3dba54e23a0def6bb.nq.gz
    ├── 40df83652784daefa0994fe7e1eb144cd9f38a6c.nq.gz
    ├── 412c9ff8348300604f6f6dfbb37b216fde6d11e9.nq.gz
    ├── 416c8e5700a5a5ab9d110e6f9909bf246f80a3c1.nq.gz
    ├── 423835dacf775af6774f802c30821bcadd34f813.nq.gz
    ├── 42a821822819d76bec3ebd2f9c065b986c00891e.nq.gz
    ├── 434c0f1f76124ddbae15cb29b5efed2f5445e4dd.nq.gz
    ├── 43ea1640a9ba2f6b66a8efb73285375b771fb03b.nq.gz
    ├── 45803dfa9691b79e8599a1779eb54d64d668e496.nq.gz
    ├── 459943bef0ce85ddc0d6121ef54e9ee4e0547090.nq.gz
    ├── 45e574a3e3c80ea5267544bacc7848ca2c1d1044.nq.gz
    ├── 46fafc9c22ab04812a561189275c482b14deeb81.nq.gz
    ├── 4706581f26582b577eedb34f864e312b65bec406.nq.gz
    ├── 47d5bd79dfb243ec45c37addc336ca1d887e52a2.nq.gz
    ├── 47d77aae778e83624dbab7124977877991bea258.nq.gz
    ├── 47fd5baa842a8bba805ef0925f1e209ff8d367c9.nq.gz
    ├── 4818df8b3244a33ff3972297eb5e2e525886a9e7.nq.gz
    ├── 4842d0036a7bd25a4f6a8d8f5205582739b1015a.nq.gz
    ├── 48e82a285384051b6f4a91e71b05bf3c58b49081.nq.gz
    ├── 4a368b3026751443d85fa38fe576caa8142a5775.nq.gz
    ├── 4b48d406080dd7d1a9db585dc988b6056db1b918.nq.gz
    ├── 4dc0c1d25d9257c5440232ff62d5055731253cf4.nq.gz
    ├── 4de42bcaba047cb146b763a5d3c17d03d333532b.nq.gz
    ├── 4dfa82e8f76cfb0937c1e24eee70137138f365e1.nq.gz
    ├── 4e4844869d9e43e76a35afc11f886566e104de85.nq.gz
    ├── 4e9dc721580d0648c74ce16006bced501e2a947c.nq.gz
    ├── 4ec85698c3b1fee3ffda37ee80de84721613aad0.nq.gz
    ├── 50b7b6dc4386143880e6eeb386eb62386e8a35b8.nq.gz
    ├── 50be86a0d0aa97c3b2c2e8825a435decdfa4a019.nq.gz
    ├── 50bf77f4f25155442b9538df5da7271dab38aab9.nq.gz
    ├── 50f3c23cec3b3cd3d3a4234855a8f003a9d3822d.nq.gz
    ├── 510a0e0acc5b2a5a4f7425e6c528ed7fb49d309d.nq.gz
    ├── 5113bd649009296c7dd1b59cb152a239f5ad6cb7.nq.gz
    ├── 51c8af3d6706b2177d917b95aeb23807d3f70aee.nq.gz
    ├── 51ef7ea118c34e8ac3da66c973bae02b9e8325d8.nq.gz
    ├── 543b99e7ee5fa5ac3de9d78c81414aedd8a9e987.nq.gz
    ├── 547ae2e938bd186a327e54cb8cd83d65ccc08ee4.nq.gz
    ├── 5549c0550463828e4d495aeebd73003b92fbceac.nq.gz
    ├── 55d33e21a5113732e122122d1106059e5797ff7c.nq.gz
    ├── 575dd00c2670e7e1779161bee78989dd4cc84fff.nq.gz
    ├── 5966b08ed3ca52b41b06e78b94a95a2f8635b6f3.nq.gz
    ├── 5ae559c02fcc561ae476c8a8524e905297c05723.nq.gz
    ├── 5b31474cfa0462e648fdd9c83da198951d3e6445.nq.gz
    ├── 5bd83cc6c0bde3b6b498d6c22656de1fc95b1613.nq.gz
    ├── 5bfbd058f5db90a3022b5ae5a3a7b30707989b0d.nq.gz
    ├── 5c6da8a3b5b299093e6d71f414cc1123075c9588.nq.gz
    ├── 5d8c86f11e07089d51b0852d11f8e174a49d09a0.nq.gz
    ├── 5e73fd7571e504990f7a055da960056f07dcdb19.nq.gz
    ├── 5eec9dadb968d77a92c6145ab0556d7eefabefa6.nq.gz
    ├── 5f0aed0cbbb1b5e9a8c7b338cb068b3a234b002e.nq.gz
    ├── 5f62a3ffa20be07dc813d6b8a154fa8451d0dc61.nq.gz
    ├── 5fca21d8252a4df9e7806d14ee9eef29c80583ed.nq.gz
    ├── 606b87ba2ec213d63b9e2035a6acc4edcb4b8357.nq.gz
    ├── 610b48364c602c2bfd773d29b9b4441a16b20b2f.nq.gz
    ├── 61eabb8e577fd27ba10413e56cb682bf82815649.nq.gz
    ├── 62960eabf9877635e8902dc2034cb8cfb38bc297.nq.gz
    ├── 633c268da1d4da5fce9022761ef85499e9920e71.nq.gz
    ├── 64db9480581aa5d1fe3f81ee0a7305c5fdf0cbbc.nq.gz
    ├── 6502fd374b2f97a4b4763f0402ad307596410c0b.nq.gz
    ├── 656ce8176e34eea72d76fc75f5d4b9cfce9db509.nq.gz
    ├── 65ab6d3020596cc41723aff1070da1701fa85328.nq.gz
    ├── 65b81ea110608d89e1679b19a2c93b977dfacac0.nq.gz
    ├── 661e8bba6ee1e2c11ada1fa9a262fcec2b7f5312.nq.gz
    ├── 66680097f3806447c0c6a55933aded45e79c5e9e.nq.gz
    ├── 66bc56f6f6c9188fd630634978d1ffc136565596.nq.gz
    ├── 676e6b53ad6d8d16ae248683a751a042da81fb3c.nq.gz
    ├── 67bc33c51515b894b643c505cd11f27abc1fbc34.nq.gz
    └── 6844a39eee0900d0ce7833567a0843bc3be63e92.nq.gz

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

[spacetelescope/asdf](https://github.com/spacetelescope/asdf)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
