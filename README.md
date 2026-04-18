# Repolex Knowledge Graph of webpack/css-loader

RDF knowledge graph data for [webpack/css-loader](https://github.com/webpack/css-loader), parsed by [repolex](https://repolex.ai).

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
lexq download webpack/css-loader
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b2b2de789d69fbfc02832d48b4f1abefadbcbbcf
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── b2b2de789d69fbfc02832d48b4f1abefadbcbbcf.nq.gz
│   └── repolex
│       └── b2b2de789d69fbfc02832d48b4f1abefadbcbbcf
│           └── chunk-001.nq.gz
└── blob
    ├── 0101f9c3e61cdb62f82cc127a850fb920763aeda.nq.gz
    ├── 017265bd01f9689a437b13cececcf4b9d8338d4a.nq.gz
    ├── 02eb0d344428fd549def78501a08db2826bfc1e3.nq.gz
    ├── 04ec56734d521f76975b91cb7533bde55ffe627e.nq.gz
    ├── 051e9d940a1a385e93759d2b0c87550251e0b16b.nq.gz
    ├── 05620ab4f2ec94c0ddd922ee8ec7e91765911f0e.nq.gz
    ├── 05c2f754813dcbcd54ec7ec930d6259a1cd93d03.nq.gz
    ├── 05ccb50cfb30653eeff8508b68ccad91e05ff4d3.nq.gz
    ├── 0680bc71704cf4d81a2717a04a273cc5f9e8e360.nq.gz
    ├── 072520b4cad5926051ba6798e8bf9b8ecf095b59.nq.gz
    ├── 074d81682db33430d790d1bc6357faf1d14725fa.nq.gz
    ├── 075f5246b02414d35070c60e232694873c15bbb2.nq.gz
    ├── 0823d4be5df0bb1da1f55ee99aa3ae62b0c0b63c.nq.gz
    ├── 085fa70cff4bf377f2e6157c3914b25e98ac48f1.nq.gz
    ├── 08b97c6e63c8b3a344d3d9358712c77eb3b657fd.nq.gz
    ├── 08fb42fd2ac7f7dacf849941633531e36209e126.nq.gz
    ├── 090df1bf07fd3a91946cbc36bc4b8c47394ac0ff.nq.gz
    ├── 09835dce7903709ce1199cf940822f20a5ebaf90.nq.gz
    ├── 09d8478a5023727b64d8a5a94521001b177f9f9c.nq.gz
    ├── 0a789dbb113dc1de305f1a7b04dae44f0b1f671e.nq.gz
    ├── 0b273d7b693f23dd6594fcb7514d24cde08433ee.nq.gz
    ├── 0b5140a27e4ad7141424678eae3aed6a665b0eff.nq.gz
    ├── 0ba9d9be1593370d3c4a8d8ffae78d9d39bd6ca6.nq.gz
    ├── 0bac822253fcbabe5ca6b995b877e187fd9c77ce.nq.gz
    ├── 0c035a8c0c9576ed18211841410fcac2e6579c1a.nq.gz
    ├── 0c18d6bfb798be7f2921a401929759281ab2b05b.nq.gz
    ├── 0c3438f4921a92c4c9e0af9e169944d1f2a93de8.nq.gz
    ├── 0c42185c0c887fb32571b84da14d7945f4862f36.nq.gz
    ├── 0cdaf23a011cbd8ca5dc744abc1c67243e593e46.nq.gz
    ├── 0d260864fbef3475f83c857d605647326a1a414b.nq.gz
    ├── 0f057898287f6466e093a070975e9e225e39f621.nq.gz
    ├── 0f13810261b6af380b74ae4ef46b46d7a0b80e94.nq.gz
    ├── 10b9ec77ded40254ad0bee4e3abf8ee24a9ecd2a.nq.gz
    ├── 110ef1ae7c10ac288dc08cbdd3cf9726ae122808.nq.gz
    ├── 1135b17d1a64ddddd83cc13f7bf1ef329bf35c3c.nq.gz
    ├── 113c2f02b6f0131538a74159c2e79390373ae2f3.nq.gz
    ├── 129fab9244302a2aec8475b494e49903c7395c3e.nq.gz
    ├── 13a954d011103fde37ded54f5957b5b15c5b77ec.nq.gz
    ├── 142e105fb89d58cee9517ad76035041f33ef563b.nq.gz
    ├── 14dab2de0c0559525f693b8c08c8edcfc69c7f19.nq.gz
    ├── 14efd103d01c49a1dc6a9f88df2c065e91ac25dd.nq.gz
    ├── 1585e7f227a88c1f1bfb34d9ad242b5a58222137.nq.gz
    ├── 15b9dca28f77aa557562d3903463b3d835f02529.nq.gz
    ├── 15c8c37affb622d6221b90a72d93b67d1ae3c4fa.nq.gz
    ├── 1685f3b4e6ca9f08ad009702eceabb056b03fcbe.nq.gz
    ├── 174a7f4bf74c78c7cace625c5fe87d291581a799.nq.gz
    ├── 174f8fed8cb9b3930faea69f93f1cdf665b8a4c8.nq.gz
    ├── 17bd070d991fbe08b1fb2f46f3a58ab7a17c0702.nq.gz
    ├── 17fd95e02f8ad1858650db8ff99826526ea853ff.nq.gz
    ├── 188d1483a9b74887079f3cfa7059fe8a3ccbb7f1.nq.gz
    ├── 1996779ec68b27b6899f7afa4883f57120b93ce9.nq.gz
    ├── 19f8df1f81263831eba2fae0d0a1bfdec3f8126c.nq.gz
    ├── 1a59b04f811e39b8b3aab4066128fe6fd36e78ce.nq.gz
    ├── 1a72d52fce4cd14da3315808e0e2d35e7cf8d3d8.nq.gz
    ├── 1abaadd3c94b9f1dc1c58570883e1629b0189398.nq.gz
    ├── 1ad8aff9192c97d0b0f7f8ee781227dcb355c918.nq.gz
    ├── 1b2e16dd2e5e804602b19f60b83156c80d1dc78a.nq.gz
    ├── 1c39afc0c6ec49c287da242b0c4a5f39d8f74b43.nq.gz
    ├── 1d8c4a8ed59d72c69f1705b92ca444aa6fce3161.nq.gz
    ├── 1dfac23168149dbb2e69a662b0e19f6187ee29d0.nq.gz
    ├── 1e1ba3aa772d5054d78cd3f9818e7b2a348dedc1.nq.gz
    ├── 1f9fb325c8007490029fffd20bef9845ed71862c.nq.gz
    ├── 20dddfba40c25f7d83e9dee4687a99d5c6ce0e31.nq.gz
    ├── 213d023ddd3cae72a5ae29b599a4046a0d810db1.nq.gz
    ├── 218435a66987e5e94199d489e81fafffff5607c2.nq.gz
    ├── 218aa9c38cc95b329f236b139cd2db0d8669d253.nq.gz
    ├── 21aaefe0ac033b37c8714bd19692c37b24ba9b53.nq.gz
    ├── 21be73c7a839a4616620561e4cbffcffaf0d5b38.nq.gz
    ├── 21d4def7f5723841a0ac6c8b33e2a1294aebbc2e.nq.gz
    ├── 22c74e0bb0199344ccb08084a90b09a911314fa2.nq.gz
    ├── 22e1bf6092456b5f003a83062d5be88c9fc29d0b.nq.gz
    ├── 2410ba39109b899337c9cb7dcbe019531fa5e892.nq.gz
    ├── 265c40b1e361962c2f056910299ee8f27ab0d1fa.nq.gz
    ├── 279092f1dbce4879bb41130435b18218f106e0ce.nq.gz
    ├── 27b0fcf648ab21faefc7e265c53219184705f1a9.nq.gz
    ├── 2880e77f47288aee0c04d278afad7f565bd94399.nq.gz
    ├── 2894e2715766e5af043189592c0faf5a9a86d663.nq.gz
    ├── 2a2aceb0190102b9de2be8b8cc6507438dc8e26e.nq.gz
    ├── 2a683179f9cdd55f241d5fbc4bf93ca615dda1ea.nq.gz
    ├── 2b75b778be74f9a05c0695f7248f292fb24a9d26.nq.gz
    ├── 2bc400971259f94cfc4133a438382e99899ad11b.nq.gz
    ├── 2be9b58fba6173a9f793fcc746ad5f5aed57baf9.nq.gz
    ├── 2d46cad5be2d214eb303c2c70fe4cdd5ab935288.nq.gz
    ├── 2d82e7f652d7581e8d6d9d65c72be31abffb1200.nq.gz
    ├── 2f7c8d882eea99ad9c456f271b2cc99bd4d509a6.nq.gz
    ├── 2fe422a795afea2a69c80e52e73aca2392b8c0a5.nq.gz
    ├── 3010843382c225130f37f367ecf3e3b76e3de587.nq.gz
    ├── 311d46d824ff7b6747eb2a8fc3be7560b0b2881b.nq.gz
    ├── 3127b421fa5726dd020d03c57209a2c37c949c49.nq.gz
    ├── 319f2869d463da440255389257f87e86c6e44c4e.nq.gz
    ├── 320ac0d70043a41082ab3f582a93516b31903027.nq.gz
    ├── 32d68bb57f7baf85d74f9531379e5196f9bf9346.nq.gz
    ├── 33c01a14747ddba063a7e09ff0938cce0e8423a2.nq.gz
    ├── 3520c43e9636997cc0157729f69c376ab8ba7caf.nq.gz
    ├── 35fdc4701d00d59f183bfc60de402aa837b9f399.nq.gz
    ├── 3769f6a2031069c1524ba1eca69c83a30e5972be.nq.gz
    ├── 37b001bc138fdc99f8b6558881c2843a367ae2f2.nq.gz
    ├── 3865420ed590cf4744b1cddd05c691aea0c68877.nq.gz
    ├── 3c89c371dc94a589193ef52de2a6f5006a1cdbf2.nq.gz
    ├── 3de3a87bb908bc5b437838c716c90641b4f434d2.nq.gz
    ├── 3e23caf85ef193f3222c2fd38093ff259f257cab.nq.gz
    ├── 4163dc5644a428c2a930a58856fc48e0fe2fd976.nq.gz
    ├── 425542ca7e4ee6e34c808e3b233a2a9ac8ed3b71.nq.gz
    ├── 4410be1e4db82f4f586f90efc627d1a500fb7cba.nq.gz
    ├── 442fcb11b4cc3be01b7957f8f64a36f5de6c0406.nq.gz
    ├── 4459531856a09bab177ad0f8774fdc34725cbd8f.nq.gz
    ├── 447a788b10071faf36a5ac59dbc37514becdde56.nq.gz
    ├── 44b6701783083fe4bcc822528057beddd9e4cbb6.nq.gz
    ├── 44c9cc8a41895a4908d86d4f26fe38354e5c1cce.nq.gz
    ├── 4544dd648cbf0a74e4c0f58e2cf8c09f3b78db8b.nq.gz
    ├── 45724d97f4ffefebbb0a142d153bf2f0ea92b4ad.nq.gz
    ├── 45baff5e2dcbf7020016847f64c113391cae3d32.nq.gz
    ├── 46865129fad42100708336e0932cd7937b66e5ac.nq.gz
    ├── 46fd3f6edfd6564ad52d1b6ac42735f53e37e275.nq.gz
    ├── 47a327b2dbe3c8174b32da2d887b2fba87e3794f.nq.gz
    ├── 48c8cd90650a4028fd01025baecdcf086ffb7df6.nq.gz
    ├── 491ad56b6e98b715216a07837c76009b05f98956.nq.gz
    ├── 495ed248467183f1faa49111a5dffa314eb47fa0.nq.gz
    ├── 497fdf9cdea0b6162fce4755e4d484d1b9a3d5c4.nq.gz
    ├── 4cd3d00b26a7bf69ab3d8225670bcc2b9fcc8598.nq.gz
    ├── 4d715aa2381b82ce33531d9f86798d0ec07e2ee9.nq.gz
    ├── 4df752682888395d6e05f012ce0f9c8e8d7d25cd.nq.gz
    ├── 4e24e926f7e9b3afb8125469ba8188f2cbaa5ba3.nq.gz
    ├── 4e2fe077398ebbd4fd1eec98dc9d69e1eadedca8.nq.gz
    ├── 4e8d1c36597047ffe7cbe2152953c0e7a02bd687.nq.gz
    ├── 4e9fb508c08eb4b985d6e42297181962c21603a7.nq.gz
    ├── 4f0fe9e03a976202eb207e820b2dffa2c8965c64.nq.gz
    ├── 50366086c2bf9b78aca166da5a38620bf30d1023.nq.gz
    ├── 516def19397154c5a8733545fc931c24bec404fc.nq.gz
    ├── 536ef32c1314471e8e5bd41ce4d8ca43de9bcf02.nq.gz
    ├── 538fa56f4ac4d34883c1b652c0b606c4a7e20e0b.nq.gz
    ├── 5399bd6b10ca60580310191e9a49fa97b303d703.nq.gz
    ├── 5451a331f9cea48685352ed1a64b5d211c631ccd.nq.gz
    ├── 54be34bdb9eb488b179bf8bf1fc910937d7fc52f.nq.gz
    ├── 550ec2a545f78dfff7abb56050cf5008b8bd0da1.nq.gz
    ├── 557ae21c026563a8ad2e5831c2a33b54adedb3ab.nq.gz
    ├── 559392dd66da42457dae35e5b2abfd1a00b3399e.nq.gz
    ├── 55da4f3d52764eea3bdde23dcc7dd6a2c6a00a3c.nq.gz
    ├── 55e62d09e5fc8addb375594e4acab4df10d992d3.nq.gz
    ├── 56d9d4aab578e5f69ad48575ded9e2d51aa22e4e.nq.gz
    ├── 5829b0b360404f3126f1d962a18b49e1f43682f3.nq.gz
    ├── 585626e07d82f87d8284bdf1aa15ecb7b1b0bdac.nq.gz
    ├── 586ef5e743ab7321765cfbe6b8082ed39dce48b7.nq.gz
    ├── 58869fbbe5e058c4f809f3e0a1ed83cbc02ec75a.nq.gz
    ├── 5a29b4859fed0c7d73687aecd6c970725f0c3ec4.nq.gz
    ├── 5b48d42edd61a6392f8704f4cd5d90434afdf759.nq.gz
    ├── 5b4cfcd1a1df95cab83a85c70edc58ab2b5936ab.nq.gz
    ├── 5da099d9671a976a5e30520e0d41d922685235c9.nq.gz
    ├── 5f4be13f2be353cfd8aa9f7d48109a305eb20dd2.nq.gz
    ├── 5f7952820781fd0eb6556e4bfd7a00ffcab1656c.nq.gz
    ├── 5fe2c12244c964078d37974eb1392f23df935688.nq.gz
    ├── 60ab22917d04eee7d818da86ff906f63a57a742f.nq.gz
    ├── 611d255658ab4acefd310791e9fa29d782bc3d2e.nq.gz
    ├── 61a78024f153d026533236a6800feb62dfd51b24.nq.gz
    ├── 61bc392b44bcf88523ddc6df8f01f87c5be0107d.nq.gz
    ├── 6264f97310eb2552ebf957e2a6ba091236060c2a.nq.gz
    ├── 628cfe52e96a6164cda5be7476105e3e5ba32449.nq.gz
    ├── 628f3ed659b8d00197f4f747d0638d864df57f50.nq.gz
    ├── 63446188dc0ec736ee147d0e8886705e8c02a540.nq.gz
    ├── 6393b50466682ab10f2cf535d34f7065c2b4cee6.nq.gz
    ├── 63f231df57701898037da144023b21f9faf99cda.nq.gz
    ├── 64a8f521f22fa74cc863d9dd3c8833ef616f0216.nq.gz
    ├── 661f7a55d67bf7e00c6fc523626a12502d864385.nq.gz
    ├── 66940a7113fdc39273c8a877362b2d0d9d8f43cd.nq.gz
    ├── 679c427bc887476b01b9e1b2a3ca7fb5bf61a711.nq.gz
    ├── 6824d672a438f9e13ffbf68dced635c2f46ea964.nq.gz
    ├── 68ce09f04c39b6a77263c09ab5424f51e1b46dad.nq.gz
    ├── 6941e2d6cea48f2d8e79757bdc5b3ba8ba41bdd8.nq.gz
    ├── 69b027e93839a32956f0deb042c45566376474be.nq.gz
    ├── 69c05163385e9d318254e2837f2046494a2ae1cb.nq.gz
    ├── 69c880836651a9b242e528ebfd2871685fc25c91.nq.gz
    ├── 69e56efa390e1ee9be85cad00f6fdc884ad48f51.nq.gz
    ├── 6aecc67380437d5926490dc85382b5f840fc4ff2.nq.gz
    ├── 6aeedd4251618b0dcda42f9026b303603f61e9b9.nq.gz
    ├── 6b946d233f64178d735fd3a0b73a4a560a57092f.nq.gz
    ├── 6c1ec23d112a69721229ae7ec6d1193a12899405.nq.gz
    ├── 6c70a337f295fc804eec7e93dfd3b25781591482.nq.gz
    ├── 6c990472cb107537492ed4be70d5090b234619ff.nq.gz
    ├── 6cd410c8a5587842996ad6bdbbc3673bd5d430fd.nq.gz
    ├── 6d22c4f809ba3220782b5b09c9bbadf6129b055d.nq.gz
    ├── 6dcbdaf7bc6cafe25eda86018a93227f38c3701a.nq.gz
    ├── 6ed696f834b7cff836a6cc03e5a698b479f8d646.nq.gz
    ├── 6fcfa73246f3e45ffcc62f96236f9557df8c4328.nq.gz
    ├── 7007a4e77ec1d5516e6ff723dd88501453bdf4cf.nq.gz
    ├── 71693e9871c0a4cc4724a74aee1ffcf2862a414d.nq.gz
    ├── 71acd66b8cb29ad4b39fe805fdf48c762e684e02.nq.gz
    ├── 72156c3ad7ca3de732817294d1887229bbd9e636.nq.gz
    ├── 72921bc7434c80cd1af57d0e73be74a82c361f7a.nq.gz
    ├── 72afb950acf86dc210789f88f9f91e37196d046f.nq.gz
    ├── 73597627ba741e7719752ce2df9396b508050b40.nq.gz
    ├── 73635f2e17ea3d9705955d78229fcaf7070c0732.nq.gz
    ├── 738626eb7804684170a4f12b6d8a3f2de29aa8d3.nq.gz
    ├── 76621bdd2852cde59fc0c9f4fc009c0da4a4491b.nq.gz
    ├── 7662cfb536dd1d146fb8098d2043a6fd6543ab62.nq.gz
    ├── 76a8327a52d7acc10ddf6252b5b44f6ccace5b28.nq.gz
    ├── 76d2785e2fe545225da1831515a5892d69a6d227.nq.gz
    └── 770c9e3d8b6f24cea5bf3b0acb6c3e30daf1ecef.nq.gz

8 directories, 200 files
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

[webpack/css-loader](https://github.com/webpack/css-loader)

---
*Parsed on 2026-04-18 by [repolex](https://repolex.ai)*
