# Repolex Knowledge Graph of modal-labs/pingora

RDF knowledge graph data for [modal-labs/pingora](https://github.com/modal-labs/pingora), parsed by [repolex](https://repolex.ai).

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
rlex download modal-labs/pingora
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 82342e138c01aa472097b75dacc5f2a665babe49
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 82342e138c01aa472097b75dacc5f2a665babe49
│           └── chunk-001.nq.gz
└── blob
    ├── 0171180798d020e7580a88f13c664ceeb0263ee8.nq.gz
    ├── 020c90fbecfcfd40df246ae741c15b8876e4b951.nq.gz
    ├── 021c59d7ed8bcc9637f56bdad0b2cb29d0a8b8d3.nq.gz
    ├── 030864602f04bb5f0d22e52816de055ae89f5bf4.nq.gz
    ├── 035a65cc325167a7568b4ccaf2cad6d7ca8756b1.nq.gz
    ├── 040842584195b3ce90ab7bbb0d085b5beb80e39c.nq.gz
    ├── 059718eaea711d282980904626f9b7582fdc737d.nq.gz
    ├── 0604b6ec671ee42af9ea1719a57f58b9ae8de2c1.nq.gz
    ├── 07ca5f3f64f647a41dc85a12bcb17183b9a7d4ef.nq.gz
    ├── 085adb92ce1b5ff440a3fd94668f33b02f87a056.nq.gz
    ├── 0866a040df4fc4bf702a9bbab78fddeec33487ac.nq.gz
    ├── 097a8da5a352c918dc994ef2041d5550812f1374.nq.gz
    ├── 09a0ffc155b80521507841b2eeea89e7ffa0c4f9.nq.gz
    ├── 0a055acc0a79e30b6f4e855d49da9a169af3f2cb.nq.gz
    ├── 0a108b3801dfdadf0fb3bae4ce9e2dbdde702b04.nq.gz
    ├── 0a8cc017d61bc6bedf31bb8415b31b95abb2a33d.nq.gz
    ├── 0c9f87f9b58bcafa386b481d55690b6c736b3d52.nq.gz
    ├── 0ca94d5141016e406ed3936e0d5302fcf2169b19.nq.gz
    ├── 0cc322d1f7d347f18ce06be5854ad41d062367ab.nq.gz
    ├── 0dbd11034541946a1bbbd831aec51dc7d5acf9b6.nq.gz
    ├── 0df71336df77964768a4ec5aa4353bfa0edd6254.nq.gz
    ├── 0e1bc6e5b4bb3ca0a4a11f05167657f0a1d9cd3b.nq.gz
    ├── 0e78fbe1840db8920ee9ef00ffff572660a77e36.nq.gz
    ├── 0fb9ce90995df6e78577d7e8a94c7299acaf1643.nq.gz
    ├── 0fe68f2286c107dd340fc8e5158f1f35d1549f57.nq.gz
    ├── 10ae642f68c3379dc7b6ad832854a2cb4c871fe7.nq.gz
    ├── 10aee2f2893bad6e7c80fff10929ce4afd140325.nq.gz
    ├── 10df272f0370ba9ed025a6b2e9f159291e0cab40.nq.gz
    ├── 181a60b87416f058841dca864a3719c1174ee6b9.nq.gz
    ├── 183e6c12826f2267437a705082244cad19a76dae.nq.gz
    ├── 18e0fdfeda22640c591443eba3575b1da922acee.nq.gz
    ├── 19602491787aa57786f4af030b400ab83ddee8df.nq.gz
    ├── 1c0052f89a50ff98b1a9816fb22c0102a29dc796.nq.gz
    ├── 1c309bba00e1ed92f5e7437ccf815b8263ae8aad.nq.gz
    ├── 1c346c6fa0be1584698df021e427c62a32c929ee.nq.gz
    ├── 1c6a1df97b58892919cce5c933c35a7e209d3bb7.nq.gz
    ├── 1c887552928dd8771873f2d27862a8793763c460.nq.gz
    ├── 1e1b5d56d7df29c859520b2c1df5c544a97f62c3.nq.gz
    ├── 1e44723bd37d614da63dec1eef3522c13cc60f15.nq.gz
    ├── 1f18adfb4203ca60b18448b5c926ef39efdcddf9.nq.gz
    ├── 1f55859ea153e3d015c466dd7d59cc7ba58e36c8.nq.gz
    ├── 1f6c3e6176fd47b232664f7db960fa1a56994df3.nq.gz
    ├── 1f8cce037631d986512277f65ab937924517d5e1.nq.gz
    ├── 2025cda322ed6f2851f26449a27a23b621860f39.nq.gz
    ├── 22a4c4581997d2277cc7874e44555665ba646cf3.nq.gz
    ├── 23728c4f382e09fe91bede0b5e1140372d6c1faf.nq.gz
    ├── 237a827e44f64714f341e7fe002e0c4a756b0d5a.nq.gz
    ├── 2545cf7cb7cf92a2f63cf8a76ca599b75ad64739.nq.gz
    ├── 256e4ac5b3fe25880e8a3d236c0c3619a56882ad.nq.gz
    ├── 26c10ca6228021c11b5b9e859bf421ba7bd88b03.nq.gz
    ├── 271447e596187bfdb523f6c81ee65bff96674679.nq.gz
    ├── 27535e11eeb8e6b3ab34218d8e760bcad38f10c6.nq.gz
    ├── 277b5b409e9f93c9602c2be102aadf91538c37b0.nq.gz
    ├── 27ae7c93533e711261b6a3c8ca6ac3f02549c167.nq.gz
    ├── 2846e9f40eeb117aca89c47ef7fdd930b790a9ac.nq.gz
    ├── 28cdadff76560653a8e8a993e3d9f8f934037973.nq.gz
    ├── 28d62c271df0f6945d27bd20947dec835ecf27cf.nq.gz
    ├── 2cb2caf97f1ab1b2e2f67c57b9882f8dfc4d0ce8.nq.gz
    ├── 2d585e667506ad0a863f041c9e20bbc4c4f4b8d5.nq.gz
    ├── 2f77002775da1a568d3faef119285ee15bf0838a.nq.gz
    ├── 2f8c76b76d1a1bdfd4439249b67ddc597ed952a9.nq.gz
    ├── 30be7b2feb6942b3c5724657cf0bcf5a26a736f3.nq.gz
    ├── 3194979941d780140ced213667c5c11faacf31b0.nq.gz
    ├── 31a6b5a913f5e5ff491aa7225aa2ac588c0357e5.nq.gz
    ├── 3224cf42b6c892afa031ad02887d83cbe6de78d5.nq.gz
    ├── 329a5be4a8855eda6db27926e1408acddaf6db53.nq.gz
    ├── 335501b181841117ef70d0984f2237c88b419a27.nq.gz
    ├── 343688aaaf2243637fb66df072d472a6da473e3f.nq.gz
    ├── 363b7357dfe8b90bea00a49c3f93f1c6410a2746.nq.gz
    ├── 37c9e6fca031915ea49d7552df7bdca5a1545748.nq.gz
    ├── 391da5b2efd004001534e9167a22a92aead3ad21.nq.gz
    ├── 3976765ee0da3b8fd763f1ce2d7e990034abd096.nq.gz
    ├── 3a26366d4da66e27c821e462eed5ef057a896684.nq.gz
    ├── 3c1f3636081652105bd531d4189a44725084c148.nq.gz
    ├── 3c80f913871b3c9cb64e24969b0c185fd3b9c62d.nq.gz
    ├── 3e3c1c46249e34ecffbff6b194c36afc6041e53e.nq.gz
    ├── 3e5378fb9d1c40c05475423d8e79c640b6d0f299.nq.gz
    ├── 3e9d85edb02c48528ac0a5c252e6ab963c06102b.nq.gz
    ├── 3eae82b939c8827631481589e15e9301c2886aed.nq.gz
    ├── 3ec2fa2883ca065937bd1b1d4c434b4f1b984a1d.nq.gz
    ├── 3f852aec1b694b9a621a12027aa90cee08cc911f.nq.gz
    ├── 3fb788d498a561a437c475ca9244d6a9547d3f59.nq.gz
    ├── 401d827ceff3ac28b2e86d51b161526c859d59d4.nq.gz
    ├── 4064a3568e248957f3ddcda0cd70cbd7320ff14c.nq.gz
    ├── 406c0d0cdaa885197ddf65f58e607fd4e047132f.nq.gz
    ├── 40b52c50b9e05a06b48b4f11f9a3b5ac3c60ff39.nq.gz
    ├── 429b372439558a3b9b4da24c734852cd059cacd8.nq.gz
    ├── 434a12eb31d074551d0370b1200388a686ae64d5.nq.gz
    ├── 4367f75a48251dc82ec00b2989dbea230b234591.nq.gz
    ├── 43b2ace9588679e27ce518dab77c094d0fa975d6.nq.gz
    ├── 43c402a0591df6100b1455d54698a1b79891b10d.nq.gz
    ├── 43c6932ea8ba53762e5cc141a3100022bbd3d65e.nq.gz
    ├── 4510d2b4c44944025babc0d693d367b503df0a18.nq.gz
    ├── 4545ee2218bb9259706f3dac4e9be721ce588bcf.nq.gz
    ├── 46decd2ffdf74b4d80af116f7489a504dac44e04.nq.gz
    ├── 4760957a322b1bf8eccf9494ff7164e36ad23e53.nq.gz
    ├── 47dad53240c3578212937d339f70021875db9ca1.nq.gz
    ├── 4a95853c356bbdc9872ecc7085bc865c564104ad.nq.gz
    ├── 4aa70f7055735e889aa64c43dd9766ae3f818e96.nq.gz
    ├── 4ab3e8a225c2b4c396b36f0e14565685b4bbcca3.nq.gz
    ├── 4bae59882da7f29d03764290c60b29135ac3c2d8.nq.gz
    ├── 4bd1e9d43a2cc978c0b2e7e453a9fa6f3b311491.nq.gz
    ├── 4be5c4d95ae5312719aadbfe17d56f018c2b42c5.nq.gz
    ├── 4c162fbef893a929cf305905aae40ea979829dd0.nq.gz
    ├── 4decbbf80e5cae950d15a3f3ea708fbd52c67e40.nq.gz
    ├── 4dffd32b9468a181eabcbd7acd685030e7e0a218.nq.gz
    ├── 4e539335379c8aa48290dfdb1936a27a8e0e489d.nq.gz
    ├── 4e5bded457c8a88c2a6abe99b7f57c82ea66f565.nq.gz
    ├── 4e927ce4aa238d70849f974f20fcd706b8bb6f72.nq.gz
    ├── 4e9462fa40981ab6de04cebbd59d72c470c924e9.nq.gz
    ├── 4eaa881adfb11b5746f2394e8454a338fc72a970.nq.gz
    ├── 5148e417ddd9851d77736e792915de21da23b7a6.nq.gz
    ├── 5277eda61cb227e2c5ec831c3dee5f8441809821.nq.gz
    ├── 5428f71ba9fdb4a44c58c50ced73cf220b1d2167.nq.gz
    ├── 544a6790ca37fa2498ba30bba6d40adb262a854b.nq.gz
    ├── 54fc367f0c2cfd1a16dfb8689db525fabe878e87.nq.gz
    ├── 55f2e246d1e4a1476a9aba667e9fcd346d20c36d.nq.gz
    ├── 5633b09cb8cefc7e836612ab8db3b7d83f207e76.nq.gz
    ├── 5781629acaf7158f5c4c759ee479089d78fd838a.nq.gz
    ├── 58ecf3b65efd70519c814b9e4cd22639c5b9ed19.nq.gz
    ├── 59e85bed6fd7a43b2416ecc1909985688936d5f7.nq.gz
    ├── 5a46cef94a7847a175466f42c97ad0ae839106a6.nq.gz
    ├── 5bb6709e89f5bc3911ea13767cf751687a417753.nq.gz
    ├── 5c31864311668411a039ea6d4aa138d1b78b72e9.nq.gz
    ├── 5c6103208a1c1c8624b86bf44901a18792066a4c.nq.gz
    ├── 5cd402617ff6f290753b5b6e201661f484ef5dc8.nq.gz
    ├── 5d6507edf540c72aa4413800f8de01790ce30c12.nq.gz
    ├── 5d841a4c64b35f2fb19c2250600fda3d4b87b239.nq.gz
    ├── 5de4f26b19ab6244e7a2b423ec5beac05579bbac.nq.gz
    ├── 5df1526d22a25fc02567d1493508c01c8290570d.nq.gz
    ├── 5e97fb3693e958ca2c72d0b544f640db6f76c6dc.nq.gz
    ├── 5f9e461078fac3256b3a57814383e11c53201497.nq.gz
    ├── 5fc0e50a56413ba900ea054380dc4b25090a0a0f.nq.gz
    ├── 607e630377293811b7a182e8b3dfd413819a5485.nq.gz
    ├── 610c9386c6aa336d812395360855f8c4446e0db3.nq.gz
    ├── 6118100c374dc6a65d63fec7e7a1e839e74b4751.nq.gz
    ├── 62ecfcb6c7f8879d1e016e3eea65324dc6108049.nq.gz
    ├── 630791115bae01303856423ae7a6811b682eb0b9.nq.gz
    ├── 632d41ecdfe8685acb9ad595dea6db8155813b23.nq.gz
    ├── 64edfd101e11983c965552300e84729a5bdd470e.nq.gz
    ├── 64fd053d34e82b930ccf206493e2e2bf64ac5dc4.nq.gz
    ├── 66ad444e690283f29548d10061007f6bdd0ac795.nq.gz
    ├── 67428671e172c4a2b5f5fdfd9b57582b81cc4cbd.nq.gz
    ├── 6aae2aeea2a578a117cd82bdf2ade53678583314.nq.gz
    ├── 6ab57c808696187289c370914c06fb0ed642da3b.nq.gz
    ├── 6b19e085bfbb5cf9067bc10e182d43cdb96f1869.nq.gz
    ├── 6d295d0bfee5e38cb7cca5f83e0b74b4a1894b0a.nq.gz
    ├── 6dd4a57ec74fdaf0e1c70b84aa24e86c907f80b3.nq.gz
    ├── 6e26981a4444ad38f12c69048253b5b0f2cce29f.nq.gz
    ├── 6fd2f9124c41591d63e8f9944f89ef08177ad700.nq.gz
    ├── 6fe67deae5678fa90ea773a50a6141faeecd0d9c.nq.gz
    ├── 707f7be869f7c233e3436fc6f086e7665658c2d6.nq.gz
    ├── 71122bf3816015cd2a3bef29b5531c78b52e49a5.nq.gz
    ├── 72200041f6625b8447d55fefb1b0c01d1b5ce389.nq.gz
    ├── 72899257c3db2f99322011dd70c58dbfc3af4886.nq.gz
    ├── 7381fc93605c72e57b9bb493d72a8e796dd3163a.nq.gz
    ├── 739b862c7ef5fda3743caaf4171791b52032ccd1.nq.gz
    ├── 746e58a9ddbb472ecd0ed1cbe99921b55d819df0.nq.gz
    ├── 74840e1958bd690d8ca3e9c91f2656efa6d8714c.nq.gz
    ├── 77303fc30437a530d949210cf7d7d06cdeeec37e.nq.gz
    ├── 784a2d6f02f2736e56358c6da309efce8de02d3c.nq.gz
    ├── 7b30a3ae7067c6bbfbbecdc1dadc6211498a5068.nq.gz
    ├── 7c228f6c12f11f44b3b07b5a7e8dd2a08070352c.nq.gz
    ├── 7c45042808807e054b8751c929a36c6bd58bfa18.nq.gz
    ├── 7c9eccd9de91e2ec88e2d02bf149e52475d3b28f.nq.gz
    ├── 7d00005e12e3555871f83f20c3af1561c3014cb4.nq.gz
    ├── 7d2c1e2b159fa78ee47af30ad85edaf58dc90777.nq.gz
    ├── 7d6ce13f889e097376b5c0ace2dc765994925154.nq.gz
    ├── 7e24cd88b8617ab8a87f770a4a29c776cdfefd62.nq.gz
    ├── 7edd3761929f9a83a3be867723863d0734b6e40d.nq.gz
    ├── 80158edcaf7fba3dc5fa06bf9030f2b9e55cc6ae.nq.gz
    ├── 808da5bc503a67489d9e2b1c27d603bede4d47c1.nq.gz
    ├── 80b34de09946d9c597a4d187657530ee38de40b6.nq.gz
    ├── 813dbe50d33eacae42cbca997236f9ab54c8fee8.nq.gz
    ├── 8141f8c45b4acc72691844928ced9a1d17b73a0c.nq.gz
    ├── 81f0fd046ef7ca79ac36206c852c7c8daeb5fcae.nq.gz
    ├── 8215d6e869f991789f4c671f783973a69f656431.nq.gz
    ├── 82f1b65ef2e438b416d48937b8a0dd0db0950bae.nq.gz
    ├── 8337a825b1b1ee4f80d46de82800e059f8a88d86.nq.gz
    ├── 83a5e087cb949e9f63ace07cda53c959ea3695fd.nq.gz
    ├── 83b7c1cafbf6b1abf115d290b34a800b839cf0df.nq.gz
    ├── 843194b202919e38ae3e3902a75aed9bf4e07881.nq.gz
    ├── 84389d0d0069a6592f83704530995e9cfd95a966.nq.gz
    ├── 867cff086a1e46b81b1347631c3ace986773743b.nq.gz
    ├── 894244c0d7b2d898f4634e047cbcd26233d762c7.nq.gz
    ├── 89b186f209bfb87c9eac13432c32c37ba81d4854.nq.gz
    ├── 8a091d2786d0423d89e4a0a7eeb619b0a1454c3e.nq.gz
    ├── 8c2f5a8f74629fe5ab3cf7f97a9cc2a1d4156c1c.nq.gz
    ├── 8d4063c7aa61f8e04b62ff1a97ffb669a326305e.nq.gz
    ├── 8e187931a0365018be8955d3e7c4bd7edbb11c94.nq.gz
    ├── 93973448afe2c89d141d067272fd036591c7d597.nq.gz
    ├── 93f4524c2e63391de39f306f95dfe5d2ff18ec35.nq.gz
    ├── 94848bbd286bf2a4f20586a2319b95d617506612.nq.gz
    ├── 949887243ccebd9515b4092106e6633b86b3a2e2.nq.gz
    ├── 94fd1a592151a84166740e5c197dbc85e6fefec7.nq.gz
    ├── 954be81b13ae518299c75b6a015099f74063c212.nq.gz
    ├── 96e4348e158c69b537d71d4187fa1612fb4dbb52.nq.gz
    └── 9701c5985e2f435bbd551ad65b0a0f573f0bc7be.nq.gz

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

[modal-labs/pingora](https://github.com/modal-labs/pingora)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
