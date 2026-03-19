# Repolex Knowledge Graph of dart-lang/http

RDF knowledge graph data for [dart-lang/http](https://github.com/dart-lang/http), parsed by [repolex](https://repolex.ai).

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
lexq download dart-lang/http
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 405395b1eb9398966ac784301b6fa5a382bb88c9.nq.gz
│   │   └── 56adf66b8c3505288444c05fb0bd86ea7aebaa31.nq.gz
│   ├── lsp
│   │   ├── 405395b1eb9398966ac784301b6fa5a382bb88c9.nq.gz
│   │   └── 56adf66b8c3505288444c05fb0bd86ea7aebaa31.nq.gz
│   └── repolex
│       ├── 405395b1eb9398966ac784301b6fa5a382bb88c9.nq.gz
│       └── 56adf66b8c3505288444c05fb0bd86ea7aebaa31.nq.gz
├── blob
│   ├── 030ad20fc7cb8290b7cd26310b6aa371511c2660.nq.gz
│   ├── 29ab172294f0935286593806ede284b87200ec45.nq.gz
│   ├── 389ce9856341060a86b921208098db2dee739375.nq.gz
│   ├── 49ce72d76a2dd00f5226c667ca5caad6081eee29.nq.gz
│   ├── 5cc86fdd0f282d270829463a906439c7c97af465.nq.gz
│   ├── 5d53a966da1620adad9ab0832532c0193dba9dad.nq.gz
│   ├── 615b92ff9638c69d62a66c503307514cdc7eb6d5.nq.gz
│   ├── 863c36e426cf88681c085ca78995d115bc7c3910.nq.gz
│   ├── 8870dbb2ed01cb07125f2417011f6b694a2ca38b.nq.gz
│   ├── 908463eb291b49f41f5b7bcfe24a687e50ea5f0b.nq.gz
│   ├── 9124e035b5376708c43de7ebd437eeb623038972.nq.gz
│   ├── a10d4c5a05c981eb3b5a454f1af297abfdf18b18.nq.gz
│   ├── d1aa1633dd46b0c52cc07546241bec4b98913a10.nq.gz
│   ├── da41cf27639a3b9eceab6ab8cf0837fa9a48724e.nq.gz
│   ├── e1b08fdf8891be40a2ddc056a3db3576d8817dbf.nq.gz
│   ├── e8063a8cd6e55e48e8b3f30aa4f172bda9c4c133.nq.gz
│   ├── e86dbe6b2a91c44e7c6202f70676ee1d1f314bed.nq.gz
│   ├── e8ed4057bcb689cbd4e0e6af10781b16ec720b24.nq.gz
│   ├── f61b00fb7917984a272729451f153c9613e0dccb.nq.gz
│   └── f9298d15d37a2b836e5957cac188ff7cdb8720f4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
└── files
    └── dart-lang
        └── http
            ├── aggregate
            │   ├── ast
            │   │   ├── 405395b1eb9398966ac784301b6fa5a382bb88c9.nq.gz
            │   │   ├── 56adf66b8c3505288444c05fb0bd86ea7aebaa31.nq.gz
            │   │   ├── 64b3450e68dd193a4bc4035c6ccfc5dadfc9845c.nq.gz
            │   │   ├── ba03ec18c34bc253d285076f9cc3d6e4a436b84e.nq.gz
            │   │   └── f35d1e1467092f6a5edb2abf7071c4a99e8c737a.nq.gz
            │   ├── dataflow
            │   │   ├── 405395b1eb9398966ac784301b6fa5a382bb88c9.nq.gz
            │   │   ├── 56adf66b8c3505288444c05fb0bd86ea7aebaa31.nq.gz
            │   │   ├── 64b3450e68dd193a4bc4035c6ccfc5dadfc9845c.nq.gz
            │   │   ├── ba03ec18c34bc253d285076f9cc3d6e4a436b84e.nq.gz
            │   │   └── f35d1e1467092f6a5edb2abf7071c4a99e8c737a.nq.gz
            │   ├── lsp
            │   │   ├── 405395b1eb9398966ac784301b6fa5a382bb88c9.nq.gz
            │   │   ├── 56adf66b8c3505288444c05fb0bd86ea7aebaa31.nq.gz
            │   │   ├── 64b3450e68dd193a4bc4035c6ccfc5dadfc9845c.nq.gz
            │   │   ├── ba03ec18c34bc253d285076f9cc3d6e4a436b84e.nq.gz
            │   │   └── f35d1e1467092f6a5edb2abf7071c4a99e8c737a.nq.gz
            │   └── repolex
            │       ├── 405395b1eb9398966ac784301b6fa5a382bb88c9.nq.gz
            │       ├── 56adf66b8c3505288444c05fb0bd86ea7aebaa31.nq.gz
            │       ├── 64b3450e68dd193a4bc4035c6ccfc5dadfc9845c.nq.gz
            │       ├── ba03ec18c34bc253d285076f9cc3d6e4a436b84e.nq.gz
            │       └── f35d1e1467092f6a5edb2abf7071c4a99e8c737a.nq.gz
            └── blob
                ├── 000cd7becadd0c8369478f825174e164de9b8f91.nq.gz
                ├── 014fd31c7802c1cb1bd566a9364dcfb07335c1a3.nq.gz
                ├── 01899887a75be79b25a263798b249743bf56f2e6.nq.gz
                ├── 0191a05cb96dcd908389278fbd66b744ca9639bc.nq.gz
                ├── 01d7ebb8d571db410405db4c2b4f9894bef3ef44.nq.gz
                ├── 025957198ea9f1c7294595e7e8bc8531bb803065.nq.gz
                ├── 02932329830bcf05e63837dbe253e45ba366172f.nq.gz
                ├── 030ad20fc7cb8290b7cd26310b6aa371511c2660.nq.gz
                ├── 0725c6112397566b6e64097a3f3738bb4fde1d2e.nq.gz
                ├── 07758b9097fb5713eebfed084c0643c7da3a2b7f.nq.gz
                ├── 07b5381d6e413da3d545084e6ea8d2c1bc52cd11.nq.gz
                ├── 07fffd3ca4d0d7608f6a37607f4a0b2f5957ede3.nq.gz
                ├── 0fbd11b2881d71bdc944f683e8ed60a5707a37bc.nq.gz
                ├── 1114180cba763c3cb01d0652d28e16edec81e5a4.nq.gz
                ├── 12695e71234c109d66af506b5adae0879bc01331.nq.gz
                ├── 176d66f5e98227f36444a5f7ae75ab6e0b3db1b7.nq.gz
                ├── 18fc78d0f9b0e6945bf758faf308f97f5617e8d1.nq.gz
                ├── 1a34d50d7e3bf4953d0e86e722c59d248f159e37.nq.gz
                ├── 1ea751eab1500a5b7e01e22ffa17b61e69f7fce4.nq.gz
                ├── 1eaa918a2a785f0fa9a91d27b33ffc33b4b0c52d.nq.gz
                ├── 1fb25b5a3f7d30fa6cfad7d806936ade8a7d011e.nq.gz
                ├── 21744858b3eb9cef84ea4552a264686fd10f1304.nq.gz
                ├── 21c7d9aa9700fcc5410eb751c253eea2fca1a3fc.nq.gz
                ├── 22130840df721aaf668d8cdded167f45a9b5b046.nq.gz
                ├── 22ed98654e9c24ffc1ebc9f4b319cc6b3cfedb89.nq.gz
                ├── 243278ea7fde4aae653b4619f740be6db8f10eae.nq.gz
                ├── 2438fd6da36918a50686affc13d6c2a7726be7b3.nq.gz
                ├── 28759282ba03e637c2332087065215b66bf101ed.nq.gz
                ├── 290678f0818099f847aeb56eb63b9efb3ae04194.nq.gz
                ├── 29ab172294f0935286593806ede284b87200ec45.nq.gz
                ├── 2beab18a650e3e83cf3b7f62509fe8345f3f1108.nq.gz
                ├── 2cd0e5c7a490666b82ed5ef78d2d70faf19ba399.nq.gz
                ├── 326914b50dbb38bd513c8a75838cf75bf8ea5b67.nq.gz
                ├── 34149188badd59893075f08e85ba27058af8d5cc.nq.gz
                ├── 35a710dbd413e35695ebab2ede8772c7ba039ff5.nq.gz
                ├── 36d9614f9a3b36dd6a06a5f33df7d145e795e746.nq.gz
                ├── 38061c1ef4e874000d41264e8129820d51d51989.nq.gz
                ├── 389ce9856341060a86b921208098db2dee739375.nq.gz
                ├── 412fc5c5cf51ae5435322e16fa22bd411313438e.nq.gz
                ├── 444b36b3d248d3c3e438fec6cd5852ac78b37f77.nq.gz
                ├── 45030ab00ad329193d230c13f143bc601376a4a4.nq.gz
                ├── 45d2c610a5da85d96b8d60e95775e2015e71f416.nq.gz
                ├── 49ce72d76a2dd00f5226c667ca5caad6081eee29.nq.gz
                ├── 4baa3e603ef5eb1b369d4e709e5abe009b14b81b.nq.gz
                ├── 4c92b94c4e0be80f1889866cce21f5aef1cbe9d6.nq.gz
                ├── 4d34a99c071e18d0f98eecab0548eb22adec4c67.nq.gz
                ├── 4d89c6cfeb86d582b5c8def1fe07e4241a110b45.nq.gz
                ├── 52dcbc61b8c6e13a528816798d9298cd07278017.nq.gz
                ├── 52efa2c2f830b93e81f64bf58b9b090334554254.nq.gz
                ├── 532b2276b294c237fe0757e721e80ed7333057ef.nq.gz
                ├── 53d112131f2dc3718987c188760ffc4c518ca607.nq.gz
                ├── 541664aaecb243041b89d1bd62b184ab95c9f4a2.nq.gz
                ├── 544e436d4bc14bb817bdd6d1c0f5c69eb1afca86.nq.gz
                ├── 58b1d862df21214cba632116b55a5e6282999df7.nq.gz
                ├── 59cb0988c58dc18fb8af074efe730ab9364b3ff1.nq.gz
                ├── 5ac1a6441d1139f188d9003cb5652fd67499b94b.nq.gz
                ├── 5b74bff593c86fd4f3f7525eb3a445f31141a21a.nq.gz
                ├── 5c1cbf0e8f544ebb1b28729020414a23ae062208.nq.gz
                ├── 5c60afea399d2ab2cb4e701b720f10300f498e90.nq.gz
                ├── 5cc86fdd0f282d270829463a906439c7c97af465.nq.gz
                ├── 5d53a966da1620adad9ab0832532c0193dba9dad.nq.gz
                ├── 5dcc6013c13575eae91cad4072e1a576d0288ead.nq.gz
                ├── 60a8ea8a36252f8835d85f22c4a61d3a2579f0bd.nq.gz
                ├── 615b92ff9638c69d62a66c503307514cdc7eb6d5.nq.gz
                ├── 6503749a81005a76c498b53ae79113223e24d870.nq.gz
                ├── 6a00a5ca7a006e5cb750fa353caccdfb18f0138b.nq.gz
                ├── 6e2fc13bffd57b568a2862dc3c4b5b16f17830b0.nq.gz
                ├── 6f03d9d14859cf2f48f1496ca1af786d835d68fd.nq.gz
                ├── 72466a9e2fbfe29567803dada0714a1b393b0aa3.nq.gz
                ├── 757bfaa26c0f3f67e0e392dada8c0ea704ef18fc.nq.gz
                ├── 767dda054a2f61638e5eecaaf82220e3ae35e0c5.nq.gz
                ├── 7dbf0350d64b57c3f6895c7c3b120d62c5428807.nq.gz
                ├── 7e94ef138629dc24b969947f56712f21f201d8ed.nq.gz
                ├── 82602a8f782fd09610704fe08cb839e77357bd20.nq.gz
                ├── 85d3681861fe50d5775bf152a0ef51afa1e8c7ff.nq.gz
                ├── 863c36e426cf88681c085ca78995d115bc7c3910.nq.gz
                ├── 8870dbb2ed01cb07125f2417011f6b694a2ca38b.nq.gz
                ├── 88a61ae3705bd9684ba33b3f73abc488b0761ae9.nq.gz
                ├── 8aa7d499748e5b8e10d1cf69877c60d286e5576b.nq.gz
                ├── 8e10eb218e7d95d6fe8a2b9c1445da99b35920d3.nq.gz
                ├── 907bcaffee2db90ef1c8128a27b92b5233d867fe.nq.gz
                ├── 908463eb291b49f41f5b7bcfe24a687e50ea5f0b.nq.gz
                ├── 90e7507df26dc5a805cd8ccacc5a04f4488da3bf.nq.gz
                ├── 9124e035b5376708c43de7ebd437eeb623038972.nq.gz
                ├── 9128b2e4b9d97608e573929eb67523bddc8f0b90.nq.gz
                ├── 92a3fb2afccefafc483c15935a6e7e49f938ed31.nq.gz
                ├── 97555f9782fd9add8f91396641869ce583781e36.nq.gz
                ├── 9a62ddb222495f238bd52fc85bebb706a6eddeb9.nq.gz
                ├── 9aeffa23eb2e63e06d8644cf3da89903f93d1bb2.nq.gz
                ├── 9c2f2adc61ae94733fcebdf0f898393fe0d1bb9b.nq.gz
                ├── 9d0648e3592ccb40ce92bb6b5649f76728f7ac24.nq.gz
                ├── 9dd5d3eb15fcc3fa7fd1ab208af59f60aaa6ba99.nq.gz
                ├── a09dcea4ed85fd2e7b024688dcb3f40c1e0a3d66.nq.gz
                ├── a107d0c4d88ad9bb5e89658538d725fe26d790ca.nq.gz
                ├── a10d4c5a05c981eb3b5a454f1af297abfdf18b18.nq.gz
                ├── a9d76945c0491ac382e0bf90ae3af63252320ebe.nq.gz
                ├── abe5808a995dfb978b82508be637164b7165d9da.nq.gz
                ├── abfcde20e3de98ed93ad412b645eefc135ad3f63.nq.gz
                ├── ac98e87d12e0f74c95d74192c09b4a62cb9a6272.nq.gz
                ├── ad85a67114194911e1fbb3a750268ea6cd987476.nq.gz
                ├── b046b01993c0c69b55bc813b8019a857f2aa50cd.nq.gz
                ├── b2304415fe71166f1ce80605a978ed369d639d19.nq.gz
                ├── b5b073f11858e59e639880144d6f832db55ec8ec.nq.gz
                ├── b647e4069728bdd2b9d0fc471dad8f5b1a87c3f9.nq.gz
                ├── b83e6a71b4cb87a813f0d54931254e58dac1d079.nq.gz
                ├── ba87e52b3ec12de4dca723698eca0e5982de1766.nq.gz
                ├── bb199d8c1741744b187e05753dbb92c3ba22597b.nq.gz
                ├── bb7556e31b4f785168abccc877ede8c2a074714f.nq.gz
                ├── bbb8448abe4df3ab668e1e2a709b1371c894dffb.nq.gz
                ├── bfd5216165d7602ccc4188b79153e1945a6a3e67.nq.gz
                ├── c5581e34c023aa5896adf8b56623ef764b2af42e.nq.gz
                ├── c773098953126f2556ce1a8fecf2ec95833963b4.nq.gz
                ├── c7dc9bfdbc6dad83af08b7d112b61b07cab5b5e6.nq.gz
                ├── c8c801d866f89664cbb4fab59270789af1a4e934.nq.gz
                ├── c92a861a5b02284e257a93f816cd63fd9ae37b50.nq.gz
                ├── cb7f152e6fab9b68bcba01ca31ea2398e90c7ee1.nq.gz
                ├── d057fa4c2834d4cec604e960cb4ccf01a5feca6e.nq.gz
                ├── d1aa1633dd46b0c52cc07546241bec4b98913a10.nq.gz
                ├── d2208fbbede36e2e0f6c342e01eaa3b59fd6422f.nq.gz
                ├── d4d495836a15c9e3d1944e85adc1568ba953d37d.nq.gz
                ├── d4f166e786319b9c7ccc2b1bedad69e6dcb6e6fe.nq.gz
                ├── d5c13b6c1953bf792de0cf892740444a3c1c3a74.nq.gz
                ├── d856efba43801abdaae9aeb50c24d4710f6dfd6c.nq.gz
                ├── d877ce54134f0c79196f829790b2e149ea4be320.nq.gz
                ├── d882d88cf1fb568f0e858f16bda4471d662cf402.nq.gz
                ├── da41cf27639a3b9eceab6ab8cf0837fa9a48724e.nq.gz
                ├── db04d4f8cf700aa485042353359abfa8e633f7a5.nq.gz
                ├── db561c51d6d35626ef348907624d389b2b0dde14.nq.gz
                ├── e082dced0ec8a5b516c781a3d522fcad88eb8273.nq.gz
                ├── e1b08fdf8891be40a2ddc056a3db3576d8817dbf.nq.gz
                ├── e2494d5f0d97922c32bd4108b60dcc6f7ae183c5.nq.gz
                ├── e3df378c4d9e88dd68404b283f9be4e028f44432.nq.gz
                ├── e53008f97b150a53fd79570556b68b770785cd1e.nq.gz
                ├── e5bd66fa0ad2381f2b0fb0458b527dd8130d8ff2.nq.gz
                ├── e79108e88ab83ddc3b541bf0d5b1baa355774f83.nq.gz
                ├── e8063a8cd6e55e48e8b3f30aa4f172bda9c4c133.nq.gz
                ├── e86dbe6b2a91c44e7c6202f70676ee1d1f314bed.nq.gz
                ├── e8ed4057bcb689cbd4e0e6af10781b16ec720b24.nq.gz
                ├── eaeccfef6bdccb8aa8f618ad7fdf9a5e4f458528.nq.gz
                ├── eed1472bd0aa5b7d742b88e9c5201a2c202f47af.nq.gz
                ├── efb065f70e6b93704e538b556b29ae42da033b7d.nq.gz
                ├── f2225962eb3ac58ee4f7dac7f336d5a853987268.nq.gz
                ├── f2333f5322dabf5aed621a6d74a9fcb59277346f.nq.gz
                ├── f3546c73e9920d2667815d14e1b2e7880a31e579.nq.gz
                ├── f61b00fb7917984a272729451f153c9613e0dccb.nq.gz
                ├── f89a0c58ca447e278b579e6a66b22021ad52ea72.nq.gz
                ├── f9298d15d37a2b836e5957cac188ff7cdb8720f4.nq.gz
                ├── f9804651b3cd7af5a4f972d922c080b324f3982d.nq.gz
                ├── f9cc8654fe9af76a29801fdd109cd60527a0b40f.nq.gz
                ├── fa4f19934b7138c5d8bda38832d41b4d82edb3d9.nq.gz
                ├── fa8169b7ef0640f155e4b250249ea6ae6f3f43b6.nq.gz
                └── faf35b3f4835a861ea64ae25a172324459612d58.nq.gz

17 directories, 200 files
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

[dart-lang/http](https://github.com/dart-lang/http)

---
*Parsed on 2026-03-19 by [repolex](https://repolex.ai)*
