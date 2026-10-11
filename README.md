# Repolex Knowledge Graph of agronholm/aiokafka

RDF knowledge graph data for [agronholm/aiokafka](https://github.com/agronholm/aiokafka), parsed by [repolex](https://repolex.ai).

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
rlex download agronholm/aiokafka
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1855cdefa8ae8fb015c50819f7c792d0b959ce23
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1855cdefa8ae8fb015c50819f7c792d0b959ce23
│           └── chunk-001.nq.gz
├── blob
│   ├── 005b200174f1cadbe595d3d5459c7abd319c4f76.nq.gz
│   ├── 0119f3182959b7af894eae60208f233793ef36de.nq.gz
│   ├── 02530b352f9b0e95b3b4b26d1ab4f0d0b6f58371.nq.gz
│   ├── 036790bea73eb15762d90bed163e0890a49ebba6.nq.gz
│   ├── 03d104a59b187b53b6eed6cb87d321d3a2b1ccb7.nq.gz
│   ├── 0529ccb7ebd4a68b5be1b454c6e0f57e622b4bc4.nq.gz
│   ├── 07e9be3d75c706663f77a80345792d1744c6355f.nq.gz
│   ├── 07ff1d377378fa6859b111b9dd9ba781a6f9ee54.nq.gz
│   ├── 0980a1dba4a4a475bb1fac52959a6458b462767e.nq.gz
│   ├── 09ab5a7e08783979c1251b239f8470a7512e893e.nq.gz
│   ├── 0a97bc59fd0f9fe7ee36878c552f15d0ea8d8005.nq.gz
│   ├── 0c1209af02a6e680f2fdf518e3983a802d8a755e.nq.gz
│   ├── 0c6905fbcc92d073c093811699aa18871936083f.nq.gz
│   ├── 0e0dfda0b26523dbae65cecf6b4f21013e59642e.nq.gz
│   ├── 101b138769478dad2f9dc8534a484b756bdc2dfb.nq.gz
│   ├── 117d058eeb895cc46562772d693f17e0bf3d75ca.nq.gz
│   ├── 131ad135acba7fec711c97567b219c309a6504b9.nq.gz
│   ├── 15aec28e7d238563c6a81c6c96b8126e5c1db6ce.nq.gz
│   ├── 18dbadc00d20aa145915a966da12f2648c1eb668.nq.gz
│   ├── 1a2b6b65d8ea5125168fb7914be0808e0bbf9195.nq.gz
│   ├── 1c61c672cc375a5c1f37db57f77cddc3912e8c87.nq.gz
│   ├── 1dc7943413e9527ad22685406bca0b88baa6ff23.nq.gz
│   ├── 1f46e76e84dcfc02ee9746222032223ce9533f86.nq.gz
│   ├── 2522d44db11d5a329d5caac2925eae6dd489714f.nq.gz
│   ├── 25f97a25f43652c7636a7249d18abcbcb58cd39c.nq.gz
│   ├── 28c73322610b83a866b472a343ced52b8818ace5.nq.gz
│   ├── 2b2e378530a1a9619df88813def179bd9792b9b4.nq.gz
│   ├── 2bb17eebfec7f27b5d62f547a74f4279e7d10183.nq.gz
│   ├── 2ed57995e5dcc36882ae2fd784f72896670b2a5e.nq.gz
│   ├── 2edba90d6a28940ec2b88c12a705d6b652b074b7.nq.gz
│   ├── 308307e183416a6eaf7c64950d24f84cda1782a2.nq.gz
│   ├── 31993fe694d01cfe2c2bb8a6952d7ea0977b4728.nq.gz
│   ├── 326c689e2761e99b7caede72bfca8bff937a6931.nq.gz
│   ├── 329f2fc49774eb02bb6fd3c3e620a62b42663d13.nq.gz
│   ├── 33198be9bdc90c68ef5f088ab879d04e3e76184d.nq.gz
│   ├── 33ae0152710313dfc1a3aa2d495a524b491a4329.nq.gz
│   ├── 33dd4a2ec8712f8eb0cef870149376ecb424082a.nq.gz
│   ├── 36d79c1037db330bc14f8ab84b7c8b392791d1ed.nq.gz
│   ├── 3ba19d5bf81d694a74aac394fea50e68b4bd8996.nq.gz
│   ├── 3c10f31612c5f6f93235a1ebf26d1a547cc12522.nq.gz
│   ├── 3c46c2299fe8f33d359c725f964ba857168a5c8a.nq.gz
│   ├── 3d8d659a7913b2c74d810976fdec25ac2ee847c6.nq.gz
│   ├── 3e2701869040f79a74c61dc32143c405ce55a96c.nq.gz
│   ├── 3eafe6e7afa5e360a69a8bb973b99d5bc3c2b01b.nq.gz
│   ├── 3f51a2e2eb66c8c5a40741cbc0153f8082159653.nq.gz
│   ├── 3ff9aa3b2fda30520c1c77f90285aea2c6f1fa4a.nq.gz
│   ├── 416f5ed5f2e4d32c4a98d01974e35d5af7337985.nq.gz
│   ├── 417a2c890673d59443977909497c4b0a63f20a1e.nq.gz
│   ├── 420eb93bc49ca0873ae969c33450b53ab937158c.nq.gz
│   ├── 431544508695f0943bd502e93038e474a505a748.nq.gz
│   ├── 43c35a474096d1e816f9e3b4190ce9f31e1c3ea5.nq.gz
│   ├── 4c75acb1341913be8b010d944befddfe7bc7a36b.nq.gz
│   ├── 4d1538c374b3bb19fdf49706d09ea6fbd97af2c3.nq.gz
│   ├── 4d6a464fea2e4ae471e03b69ebfbb0baaec13ac8.nq.gz
│   ├── 4e9c1e3f04b20831189dee0a5270891d2d74fefe.nq.gz
│   ├── 50387dcc111668ff41b52e0ae36b6c8be933bd50.nq.gz
│   ├── 510480ea990f88862abd980affcc282caa629617.nq.gz
│   ├── 519b5d34a7b63844ec25cdbbd3417c8411b8afdf.nq.gz
│   ├── 51e04e7f0757d0b6d221bd0bf4cb5310f8c72a65.nq.gz
│   ├── 521767279586efa8c0c798a9f98ca26ebe9253de.nq.gz
│   ├── 534987ebda2f2dba67bc65543a465c6f2e119818.nq.gz
│   ├── 54546268141303657daf294acbc610cb3369b9ff.nq.gz
│   ├── 55d5a48d52ebdc4deaa8d640971610cf17442a2c.nq.gz
│   ├── 5606040b720c623e230c5754d0eaca4eb46b2bdd.nq.gz
│   ├── 56381eb05de2a12f3ff592575c1b07b8ea3950f2.nq.gz
│   ├── 5650d95b17fe79b149477355543510709aceee0c.nq.gz
│   ├── 56680f07d24b98c4107a17edd6635050ea810001.nq.gz
│   ├── 56cbdd73c651c4233e931c348d836f572bf0b2ac.nq.gz
│   ├── 58f0301384c6eeca7d9502f3dfdca88294227404.nq.gz
│   ├── 5c4d7c65063e426e3f8a06a38bb7c67e4e1793bd.nq.gz
│   ├── 5cd9fdde00a1444fdd0a8f475663c7f951bac419.nq.gz
│   ├── 6455acac02f4f906964ec46433789bedb833e1bf.nq.gz
│   ├── 6630f5f0cb4c3adeeff08378961bddf7fc1f273d.nq.gz
│   ├── 66f0b3b5a70c3c031cdd458e9e24ca948f1e8bea.nq.gz
│   ├── 678bb691888f98a084e8ae2b99dcf46e95863f9f.nq.gz
│   ├── 67cd2f7597a138a7266bcca7e0c4294dc67c7104.nq.gz
│   ├── 691361207f46bb2c731c5c8716cba39737dc7e8c.nq.gz
│   ├── 69ae269fbe802a3ba15e446598f23d648f5b898e.nq.gz
│   ├── 6ad506911e34e68874d88bf0d431c9133bf15c99.nq.gz
│   ├── 6b415dc1238c6bcf6c0e333c795691f8adb29a32.nq.gz
│   ├── 6f5cea74349c6a9bdd7cb8e503871d87f3671bb4.nq.gz
│   ├── 70ea32b46df6f4d3b046febf272a572be0f6f12d.nq.gz
│   ├── 7118b28c20be12808d301ce5343f92a792d1c532.nq.gz
│   ├── 71b2dc95b9ee750ce20dd60d2678af10a635db2a.nq.gz
│   ├── 724bfd65fe1236acaf1dc28e7d28d9beb1cbaa08.nq.gz
│   ├── 756c43cf0ce9b238013d96242cd614a2e771b082.nq.gz
│   ├── 75d807b8bc5f3c97d04a4672c8cb03cdd584a27b.nq.gz
│   ├── 76edc146836628a107db741940a453df58060c15.nq.gz
│   ├── 77a7a485b63f28739c2c7b2e1845e11c17165443.nq.gz
│   ├── 7903f6cadd2100f22875e01eaec7874393034921.nq.gz
│   ├── 79a5600a40adfc29d5594c7e127c8a736f91d86a.nq.gz
│   ├── 7bb3d44c674b3873deb30c845006756d0d1f5abf.nq.gz
│   ├── 7ce888885b77a3fecc2e72159e578597289b739d.nq.gz
│   ├── 7da6fc98099d4c6ac185f8c3d2d162f2d38320f3.nq.gz
│   ├── 7eadf7fb4d5619909534b46327e24f829aa48c99.nq.gz
│   ├── 814190a17f6a997b9b4a18a298f67b66302a7516.nq.gz
│   ├── 86397de05f3b9795f0a1cb9255e682816d1ece4c.nq.gz
│   ├── 875d774b940669fb3b1313232c6a6aea1ef615ef.nq.gz
│   ├── 8a228b7f913ed6ec916f35f2bfcf243c99922f9c.nq.gz
│   ├── 8ad7f32120552fc8eb166b36723bd8b99086eeb3.nq.gz
│   ├── 8e0b4f811b98d0fc452f82f06ee49fc446507575.nq.gz
│   ├── 90d88b02316de243a1e74c82392447346257f00e.nq.gz
│   ├── 92ea21977a10d5b5bfd127eba6223fee95016f35.nq.gz
│   ├── 9303c1ae6b213d401f69171a2e4814d22ac9612b.nq.gz
│   ├── 951deefd4b20ec75f8476401ccbd2c681e03d876.nq.gz
│   ├── 9537e781f53a4326b4c6f1c2f54b9a70378a9746.nq.gz
│   ├── 96c0793cd6cf91411c59f89b1ab6f27cac53ebfb.nq.gz
│   ├── 96fd2532d1ec21a835607490b9a3edd8f19f1dcd.nq.gz
│   ├── 98675803634da2bd5e3d21215d64a682c07e0052.nq.gz
│   ├── 997e31e5e916dc89ce3696ed14197ea5758b5a4b.nq.gz
│   ├── 9ad5f94397a4ad65ca4e32f11dc464c0543b46d1.nq.gz
│   ├── 9b323c857915e44cb06ba3714c1c8fdd5ff667c0.nq.gz
│   ├── 9bf086acab9926c24b72439462a634ce32c90c8c.nq.gz
│   ├── 9e0cfa5c2017064d1c9b13335476014931808dd6.nq.gz
│   ├── 9e4efb415c316d0f27537ce3c27c1c8a633aee11.nq.gz
│   ├── 9f56f98b40fe8a3695035d0838703649cae593f0.nq.gz
│   ├── a0b56f610055f7d0852e9fe94815a0a460172076.nq.gz
│   ├── a21d492b9d5ed3cf237922878c44d1553131e085.nq.gz
│   ├── a2402b72efea4dde577217740c81dd33ed525cae.nq.gz
│   ├── a7b327c915b1225cdb0508cef3cbc9f92a14003e.nq.gz
│   ├── a81b9663fe5219d3111ec3656e69f0b3d7b48f6a.nq.gz
│   ├── ab17ecc918d5026443367853dc0f33f00bbb3a3d.nq.gz
│   ├── abb9f21675068546bdf2420d01bb13d14ba565ed.nq.gz
│   ├── ad1848662d6e0bad95e3bad5ebbac29d2dfdb292.nq.gz
│   ├── adc142de86f383e936f53bde0e384a1cc3f39564.nq.gz
│   ├── ae306b04a78221f86a48a2f0ea629bd835106d52.nq.gz
│   ├── aed9d3a2c46feb05820691064dcbcb469e3a5973.nq.gz
│   ├── af0a7cb29c5ae19e6cbf17448e821dcd092f969e.nq.gz
│   ├── b0fda8c3ae5eb3b4a633d7f628e728267271c38a.nq.gz
│   ├── b1a81eadf9fa8131f44ea2e71e22af0fc0fd3a11.nq.gz
│   ├── b4f5c48f2e82b7e4b5c7d57660f509a7210ff51e.nq.gz
│   ├── b50843952d83b518300b3f0fd51c94ef9b07b373.nq.gz
│   ├── b718ce2f33b9e4e17f30b0406b77a254088b2b46.nq.gz
│   ├── b740fd958f5bcbfc24ef7311d8c6b457997344a8.nq.gz
│   ├── b75547a759f7a01d23ca7d33392bad77deb474da.nq.gz
│   ├── b99d5e51892061908a0c3f4e7a236b9ddcdb64fc.nq.gz
│   ├── ba49411d3deffc0d60ad4de969d3ac0050a6f08e.nq.gz
│   ├── bb3b2f616f1ca1bdaa58bf344484717026c1f310.nq.gz
│   ├── bcbaa3484092c516fc042a512e1fa034acda322f.nq.gz
│   ├── bde25e2fdf99fdbdd37d2bca602655bd4496ccd7.nq.gz
│   ├── bf3a50edb28d6d359f14ffb6dd67b1b9bc2e31c3.nq.gz
│   ├── bfceb9108734b901448ac1a83b3167cce3cfe13a.nq.gz
│   ├── cbe06f64630ae80d4c634468650afc1ddf80ff90.nq.gz
│   ├── cd09369edc2fd50cdf7d9750026ed792115704bc.nq.gz
│   ├── d23cfca6a18bf9d99cf831df774a012c8e3fa58c.nq.gz
│   ├── d31179373f1836317dbf1e8d3d4eaeafa42017f5.nq.gz
│   ├── d582386ca5333992fc89895a326b15ebd0ab5606.nq.gz
│   ├── d5858ddd36483afa627fc35597aa9a7aa70b9790.nq.gz
│   ├── d5fce397865cf7d74eac8020fba5e4a9209ca3dc.nq.gz
│   ├── d630c5f817fdcc68133264c3343d4d8987376377.nq.gz
│   ├── d67f78de63ac6412f41b737d4ef854de7f81a343.nq.gz
│   ├── d6b77a9fe2f4944ebd1791d02127d9f50238690d.nq.gz
│   ├── d754356e39a218751dc6c9b032447c6bb6480c2c.nq.gz
│   ├── d884db622fd6849f23ae26567dc541f49762bf33.nq.gz
│   ├── d8abaea851b9937f525f912bbdf667785d27221c.nq.gz
│   ├── d901e4feda1d82ac08f17cd5674bade64a49d474.nq.gz
│   ├── ddb86889bd52745ec39ed768030617082d260905.nq.gz
│   ├── de058323bf497b3022626c58271321f504736058.nq.gz
│   ├── e001b5713eafc71455f00f9c849ee0759241f91a.nq.gz
│   ├── e009d36a8fb280a0e6233db8ce4b5da3b2a7a8ea.nq.gz
│   ├── e1941230c6810e11d83189e7e8bbb91e61b8f460.nq.gz
│   ├── e2d9190fa7623ccb3a6427c591829626301805c4.nq.gz
│   ├── e34365d2be379f4468875525448beee722ff241b.nq.gz
│   ├── e3f5c5484e1c4cea0e7aa667d26ceb9455570f37.nq.gz
│   ├── e4cba70d84cafff416b09736a5207d22ef1f9066.nq.gz
│   ├── e517df14299dfc1614519898193866d1fd9b935a.nq.gz
│   ├── e55f616a018078ec066762de94a6d068af0a7588.nq.gz
│   ├── e5b99fcb5a39711026828f5a69aa4938fbc33af8.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6b3eec3a8217d6abb7ddd805c362c0d99928c79.nq.gz
│   ├── e75c92fb1e894a4a151f92cf533cc2878b8a4f1a.nq.gz
│   ├── e76b61b12c9debdadfcd381a5d7b5b74720ff694.nq.gz
│   ├── e9baaf5ff4eea3be68820af01b58eb4ff55e796e.nq.gz
│   ├── ea9734ab8896bcf7fb51bc4b2d4533ee424bee77.nq.gz
│   ├── eb9c9cdbebc163f1245655902c6c982a2a6fc697.nq.gz
│   ├── ebd2005efe09452ff7952b02346ccfa96ea3b7b8.nq.gz
│   ├── ec2986613c44fe76b8b1bc326b4e0b060485206c.nq.gz
│   ├── ed36a018390f6880813321e13dae5d88f1bad94c.nq.gz
│   ├── ee99c75ac90bdc100e3bdae8615315f56ab4e34c.nq.gz
│   ├── ef6c43b2552a8d8285dd61852169f676ae04702d.nq.gz
│   ├── efc6720529f8c71ac43c174fa9ef6d9b0d0bf02f.nq.gz
│   ├── f0864a386ead11c1794bf57f83ff38185d3477fc.nq.gz
│   ├── f0f4a075811b3c0a0683f22a0da055f7cfa5634a.nq.gz
│   ├── f2f6a5f2bac880d42f502337d8ae3ccf1fcfc76c.nq.gz
│   ├── f2fa58dac87c6dcc135b57cd276b0fce7a7f95b1.nq.gz
│   ├── f7d99612c9c9c098ecbb2d74cd3945dd9faaa99d.nq.gz
│   ├── fa44a807c85274a6793080ee81009dfaee8e159b.nq.gz
│   ├── fab457ceefe31f78b3c3caa6a4615409407889ab.nq.gz
│   ├── fdcc516a53285b9fa37e57dd87d46cd03f26346d.nq.gz
│   ├── fea0f82385edd813e50c6ae6925304f274cce0e2.nq.gz
│   └── fece6c97f55611cc3042b91f76c8cc967bdb7c0b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1855cdefa8ae8fb015c50819f7c792d0b959ce23.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 197 files
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

[agronholm/aiokafka](https://github.com/agronholm/aiokafka)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
