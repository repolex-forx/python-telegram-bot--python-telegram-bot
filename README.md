# Repolex Knowledge Graph of python-telegram-bot/python-telegram-bot

RDF knowledge graph data for [python-telegram-bot/python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot), parsed by [repolex](https://repolex.ai).

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
rlex download python-telegram-bot/python-telegram-bot
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8dec234225145f8ec0cc8fd97d42208a32d8f0e6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8dec234225145f8ec0cc8fd97d42208a32d8f0e6
│           └── chunk-001.nq.gz
└── blob
    ├── 0033452af7a6b3992830525bfc5629de818b9dfe.nq.gz
    ├── 003414419c89b8d59780b9644fe134b04bb32440.nq.gz
    ├── 0050a6402279976c25518d57edddab7e799f969a.nq.gz
    ├── 011a85bb884b60588c3f88180cb9074e262a73d5.nq.gz
    ├── 014bf8631b3bac716e8108a72d089bb777c20212.nq.gz
    ├── 0204af1ee472c579a121a67dd42b19bfd93fdc4b.nq.gz
    ├── 0354229e76f764e33013b2207da192fdec3a84a0.nq.gz
    ├── 0382ab61f340abd8968d5bb317ba78d7f41d713d.nq.gz
    ├── 03db3edaab16643061e9ef5fb15311970d748033.nq.gz
    ├── 044e957aa41a58ee7308dc9f25702934e98471d7.nq.gz
    ├── 04583cf99f59758c9bef2f40677ad21f7647317c.nq.gz
    ├── 05a5839595add6853784ee0615fae12bcd51d886.nq.gz
    ├── 063e8cc0ad39a1d60eacd71b991ded217c1ad0ae.nq.gz
    ├── 07203fbe80fd108a578a8afc17778fed0f3f1991.nq.gz
    ├── 072f4724c0fd3703b70c05e8e526170484468ad8.nq.gz
    ├── 0784d21c71f34763364e330be2327bea735c9fff.nq.gz
    ├── 07ac3417c343a508d038b6fa4cad57d5a8e843b3.nq.gz
    ├── 087e539e3976e061904b65541d85d9f8f5c191d9.nq.gz
    ├── 08e9dc0222a05902314ed14e9c4b6f0818a7319a.nq.gz
    ├── 093a5449b81594b4113066b1d615e67ecf0c0873.nq.gz
    ├── 0aeebe750b678f2f908083d57585d6d259e605b5.nq.gz
    ├── 0b0a987a0134cc70778456e36be232c63cac63a6.nq.gz
    ├── 0b2e51863af4be14e80089870a1dfd16d5fc1dfa.nq.gz
    ├── 0bd5939081ab8eb06e2d960683d393fafd20eaef.nq.gz
    ├── 0d9d1a12d32abb6327dcc2dbf23fec426d88616c.nq.gz
    ├── 0db160bfa4cfe2439379e46cc3a2d9418b97ee5f.nq.gz
    ├── 0e56db89db9def68b6b541cad90c2bed20f55d37.nq.gz
    ├── 0e69b89949cfc2cb2e3f7c6ef728595997ce164d.nq.gz
    ├── 0eddcdf469d3523c034eb07bec4a3e7e502530b4.nq.gz
    ├── 0f69756b371cd04d58a10ad3f1d17bfa60de27b3.nq.gz
    ├── 0f78027c7babcb63065878fa00f2f7330f0eefeb.nq.gz
    ├── 1056b73c829785299e83ba1153127a4456b0ae42.nq.gz
    ├── 10aa76f8085970b339b33d631654717b376d1e97.nq.gz
    ├── 10c5de3e33b6bffbd80920170bf2373758da5931.nq.gz
    ├── 11080cb71013599618a23adc52a363a2ddbc8903.nq.gz
    ├── 121d5b95b08620636776813cef1bad93bd6a9be1.nq.gz
    ├── 12fe8058ce9cc4941e7709b60bd663d4d13fdd7d.nq.gz
    ├── 130d061020fbe95ebd766696ee571d0732c541be.nq.gz
    ├── 143c042553bfcf861e9f72b39f8f689e8f415b1c.nq.gz
    ├── 148aaeb392d818b576b2fe04a791631852fd4b5e.nq.gz
    ├── 14bd8e4e12637b58a788c0cc779eed65a3ae59d1.nq.gz
    ├── 154298f853c9bbabe892ebf4d90fb497fcd2edef.nq.gz
    ├── 154f8b35fea8dab31fda83fc301b1cb1314d3611.nq.gz
    ├── 1600c05903f10123cd44e9fc5cc7e8314c38049a.nq.gz
    ├── 162ff4ed8c409970baa9566c7e9c668b2d5d1407.nq.gz
    ├── 16a73f15c177a1c27baf782bf0ed96a6dc7a162a.nq.gz
    ├── 16bfab5b754ca2fa80278e6dae6e5789692a37b1.nq.gz
    ├── 183e1818268d3749658293a37f78c2db283d976f.nq.gz
    ├── 19582f504b127c231f90dd9dd08121c9a25566f1.nq.gz
    ├── 197dbbe3967bf08ce0c75221ea7199898e4c9e3b.nq.gz
    ├── 19b26d609fa5a6f8fd28c2613b1c9949cd24a2f6.nq.gz
    ├── 19dee14e0eca2195937aa59a00a77f188c65c5ea.nq.gz
    ├── 1a0a0c6fc38825f077532e6394e3b4f56e40a852.nq.gz
    ├── 1aad333ff1c32d2da73ea293b56b45183aac284d.nq.gz
    ├── 1ae97580e62d098f4805d4a63b7190114cda4643.nq.gz
    ├── 1b0a09a48682a4899a29bb621d5b48e06acc5a36.nq.gz
    ├── 1b29b4c38d0c0bc1d3495d72e94b9abdeea78856.nq.gz
    ├── 1bc2d97a887234be0ed7d74dd49de15803efdd47.nq.gz
    ├── 1bddc1976ff94a6ce86cac66747fb404ceede0f4.nq.gz
    ├── 1d26e231b9eaaeb4fbee966981df6244aaa0bfee.nq.gz
    ├── 1e138240a791b9851fce21979bee1e5fc49b5d42.nq.gz
    ├── 1e30c27566c27c5ef71c0b890fecbc95b7c032e8.nq.gz
    ├── 1e4cf4e251d22fc26deebb1bdf3a12c6c72444b4.nq.gz
    ├── 1fc7a5a8d3d3286fa645fbcff5414e40449d8082.nq.gz
    ├── 211e3d511e17efe7c8582ae0e9949153abf5fedc.nq.gz
    ├── 220da04007eb4c9fb3ab1ea590ec98777dbc1cb2.nq.gz
    ├── 2392ff1ec5b41d856096ff19508221420735f5ad.nq.gz
    ├── 24424c4695a6631ebd21383206698d424124ced5.nq.gz
    ├── 24475848752dd93b34e95b6858e06058dd057655.nq.gz
    ├── 2534d84cd65f06bdec1709bf2077e23bb393a514.nq.gz
    ├── 257e57c95c85d22248b223becfb9e79587a34ac7.nq.gz
    ├── 26469d9979835d8baebb5a3e5768077d97fb3d91.nq.gz
    ├── 26e3560e0a5dbc090e460bb63b75424a4f6a4e05.nq.gz
    ├── 27550468e3b6aa797582b81bd669483f5531e460.nq.gz
    ├── 27f44d629de06f099811ddb99f869aead4be9fda.nq.gz
    ├── 2833f418b942e62d19d5eb609c691e4ab2a9ad27.nq.gz
    ├── 28c039fb1a9677e56c5e94dd0c17529ec8b1a0a8.nq.gz
    ├── 2926dffd338fc19fd7e9b9eb4345e72867a1b17f.nq.gz
    ├── 2986aba0b64eeacb40ce285d663554d041f64477.nq.gz
    ├── 2af6693ad19b82d49e02bf7e7b82451cc10bbbfe.nq.gz
    ├── 2c342b8dcb7bab0db0324452cc21a20222380083.nq.gz
    ├── 2fce0d39e71d146338311607b5de35ddfa82664e.nq.gz
    ├── 307e0ebf3028b01d97b3e5ac296cfe6bafb9f56a.nq.gz
    ├── 30f2377ac86e260c53b72d0ad7149e855ac5fa80.nq.gz
    ├── 31924b088fe0544991729b36935d50e67f2488a4.nq.gz
    ├── 319572984c9953a5c484261308d6d9bcfb238014.nq.gz
    ├── 31e63a6a7efd96019be76f64ca41ab24b687dc5c.nq.gz
    ├── 32764cfb43a7ea0a170c8fa4b759b6d4a7b7612f.nq.gz
    ├── 3316f0ab3c3d3af6152134b24d1bdfc110ff37d7.nq.gz
    ├── 331e991fe4184744399870bba31441f2e0748289.nq.gz
    ├── 365bb455d17e0957790af55e5259365cc813e39d.nq.gz
    ├── 370e72fa9e5f0bbee4761aa9c25de85b9cbe332f.nq.gz
    ├── 3782cb0d1a0bb85c53049aeab52aff0b48182ffe.nq.gz
    ├── 382b44de51b7f3f399b98ee0af17aa081de17674.nq.gz
    ├── 38ce19814c013dfc13d78fc510b2df12f39b0a5f.nq.gz
    ├── 38fafc4de3d7a5e143dfab3152fa61cd666af534.nq.gz
    ├── 395124b3c7b5f1b90fba9ffd489b8d0452d1b16c.nq.gz
    ├── 39891c777e58bba89a5980acba078004132f9b3e.nq.gz
    ├── 3aa78dd51a20437bfadeabd49c8b8ae756ebce94.nq.gz
    ├── 3ac7f9bd0e53972f42a415d222dd0734dbbbd006.nq.gz
    ├── 3b13a2ea8873582a9d1c304e200d12373342b4dc.nq.gz
    ├── 3c0d1e75c52a7a97447b75c9a2e3b52711cbe9e8.nq.gz
    ├── 3c2110271c004901b4506cb1a7b66a011d0aac53.nq.gz
    ├── 3c4dcf0a8cda81f780e1e7458db3f05279383049.nq.gz
    ├── 3d0e739c45660310f32e51120ec5694bac53f79e.nq.gz
    ├── 3df821033322604772c78ff5c9e43d33682ca08f.nq.gz
    ├── 3ef31c3b25e892b89e456f48edf7ef738e0bc1ce.nq.gz
    ├── 3fee7ac4e375111d58b0d6a2fb10a65558905267.nq.gz
    ├── 401bced18877d15edf66e3dffebe9da650eb461f.nq.gz
    ├── 40bd6fdb5c76691025d610982de65eca5af9fea7.nq.gz
    ├── 40fbf609a373a73c7b771bf9ecd6295f5c0487c0.nq.gz
    ├── 4219b05acbab5d705b409ab5bce23c57d4d0dad2.nq.gz
    ├── 42ba56708c048f95a9173156fa480039bdf55bd0.nq.gz
    ├── 434cf70b67d9471479e0261b64e3a9155fb79752.nq.gz
    ├── 43a7ca4f1e5d6526cf04dfef17603485aa20104f.nq.gz
    ├── 44aa70389d52ead076dc8dc3c3d9e34ec5dedfd9.nq.gz
    ├── 44e3dea0b67805601c2a19a9ecc6a1b8a2de0357.nq.gz
    ├── 459629b7ecc081671ea18e2573dffb5c92d7e1e9.nq.gz
    ├── 462780b1321c435f4adb057fc390cc8f8e9da397.nq.gz
    ├── 4765096edc6315b23a01b0960742565dc22eaa3d.nq.gz
    ├── 481b100ae90f19b979728fdd14bf9344ed42e500.nq.gz
    ├── 4826a584f632df98dcf0a0bce65b1ec164105d3a.nq.gz
    ├── 4870a48fc04dc1cd4704937e1b4b9f216557632d.nq.gz
    ├── 4889f9c9ec8b07c582bb199cee7f3085154c903c.nq.gz
    ├── 4907172ab713fc933756411629da84b8f207c63e.nq.gz
    ├── 49e75ac6015d2218fccb0ecad76212ed00dead32.nq.gz
    ├── 4a5ea46bcea9d9889c41674861930c055a683dd8.nq.gz
    ├── 4aeee4f2ddad30ccd7daef5346d9218aad154d4e.nq.gz
    ├── 4b1a3f25991fc8910793a596656026b84cddbf0a.nq.gz
    ├── 4b2a625b5e82be9222c7d24cd6fec4e6fd7e9926.nq.gz
    ├── 4b5e40bad26fdd1471c87650652ad9f32bcd8875.nq.gz
    ├── 4c5322456bb662db4cd13cc50d2de8de955b7660.nq.gz
    ├── 4ce6cc1d9bb0fcce846fb431cddc55763ed3591a.nq.gz
    ├── 4db32d4c9aaafca07d69f4debfbdb2e0958049fb.nq.gz
    ├── 4e638e33864ad68927f48785e387fb46edd0527c.nq.gz
    ├── 4ecceb796b8e367c11f7efec6901910e263af9a8.nq.gz
    ├── 4ee0e39fb3e41feb60e7a5ddc95c31c06b7edb0c.nq.gz
    ├── 4eef931d97265a3a707dd224182d8feadb780827.nq.gz
    ├── 4f3fa95b73e0c48304db7ceb821c4c1f9ce4f610.nq.gz
    ├── 4f58bbb0e5a586713d53bd5e813eea96c7f61755.nq.gz
    ├── 4fca643fbd58dec6a9adc8532ad60527292edfc1.nq.gz
    ├── 4fd73b4ad44c44ed5a10e8b1163dd53c8c48e058.nq.gz
    ├── 4fdd7798bb6f4ffdcec49d4596fe3cd81c5e1d4f.nq.gz
    ├── 4fe608aa047fbdef581319448ad7c541e2eb2342.nq.gz
    ├── 503e69ae82e99e9c339ff13ab90e25c3258579e8.nq.gz
    ├── 5066db58ab7405cf0a942d45e8f963fd6348a2c5.nq.gz
    ├── 506b05ec6cd7763a64e764db00b27d00fc016ec4.nq.gz
    ├── 50fca0a6916411b6ff5440d359e4b4cd86361854.nq.gz
    ├── 5111d8fdd48a6faa1a9cc4dbf114d859bd3f0114.nq.gz
    ├── 5130de5f988586c5f133410a20182c661d363ec3.nq.gz
    ├── 513808c72f87e0de1c18c17d2084a4f9fdacd52e.nq.gz
    ├── 5240b32477ff4875b949b811d66690b5ae3a57d2.nq.gz
    ├── 53632ac9bd40933f3cc22fb178815d5e60616ad8.nq.gz
    ├── 53c89496b216f385969d2cfb9ea7c47fcdae862a.nq.gz
    ├── 53d93db427174cb1297bd16a26dcd2109fcf9842.nq.gz
    ├── 53f55489f2f3da84afd19010becc04f1ec773b3f.nq.gz
    ├── 54281e298f039f0a3c36250262f53c2cc95634ce.nq.gz
    ├── 544c91e6df5e78fdd4dbaec8dd5406995c13494f.nq.gz
    ├── 5508daf4ef6919e4ee917f2d5a7562f9ad4ec98a.nq.gz
    ├── 5564b588d40a4321e5b80779db16d82ef9770820.nq.gz
    ├── 562258381804cc34e2cc51b1798a82dc541d02a3.nq.gz
    ├── 568bf07ef38c712da9db857f7c4e96902e44e5d4.nq.gz
    ├── 56a3a7ed90f8a33ea31fce95e7a29f7549cfb25e.nq.gz
    ├── 57261496a8ee3ea5c5c20d9ae333fb27d1ca0a52.nq.gz
    ├── 579721dcc456112c0c3d6bb978b811699536ee36.nq.gz
    ├── 584d132930bf6beaebab371e205d72e56071e9cb.nq.gz
    ├── 59e75163c9a53a17ebb1348f912e0bc6178f80e3.nq.gz
    ├── 5abcfed0aa7cb1f631889d89f3c37a4d64c57362.nq.gz
    ├── 5b3cb46d33e6500a16dd7907538979bd38618e9b.nq.gz
    ├── 5b730f185834e21776780f005a0d5b87d1936cea.nq.gz
    ├── 5b87074105c0d1956ac4afe9e693f133e20d8a89.nq.gz
    ├── 5cc432cd401807b01258d0633c961ceb98c454aa.nq.gz
    ├── 5f9ed0017d2add50e32921a95a1ca24f6d66abe3.nq.gz
    ├── 603a56f6ad2f05301b9ddb172ee7cc7bf81e273b.nq.gz
    ├── 6099fcbd870bc05fe2ecbebd5ee758dcd8f39328.nq.gz
    ├── 60d6034ce0c5926f97a08f58ce0441dbf519972e.nq.gz
    ├── 618fbc90587fee2e6a24f3c5d1e873ea1f049e77.nq.gz
    ├── 619b4a0c89f0a612b9e74b6ff1ffbecb7f080509.nq.gz
    ├── 621b99b540e8e9dbb8851a80bb0040b9964f1d42.nq.gz
    ├── 6252ffba0a0fdc2a08560fbfb40eec1de9e7f4f3.nq.gz
    ├── 6279a9461902b120a05e5ba08b39cf0de569ba93.nq.gz
    ├── 62b3e41f940c1d4c33bc6be58175d11adcdd4e00.nq.gz
    ├── 62bf1a2dac699376b20336f3512f24fd2a6a7f17.nq.gz
    ├── 63379122869b5b12bc3589ec1572a9bc6d3bd399.nq.gz
    ├── 640292b9b8d305ee71fd0c5b5c802ccc923c2325.nq.gz
    ├── 642ddd20209878237ec3e6313b0008c76931865e.nq.gz
    ├── 643ba3df8972a6f802dd367d9fa1e678e843fc6f.nq.gz
    ├── 64543e30d16eda14d6d531acde793c002726db1d.nq.gz
    ├── 649522d0dce1a7b9b4b27f15c68d5d7885d90f60.nq.gz
    ├── 649c61623af447ce263744f233662286c3082c23.nq.gz
    ├── 663c15e8181686c24929d14464f9d19abd92a1ba.nq.gz
    ├── 668a0c24cffe86018033d8e8956e13d6868d8423.nq.gz
    ├── 66c095b11aaaa2f50ebe1b616ae920064327e860.nq.gz
    ├── 6798caa22df2e11617b875a3bde98442bf0287b0.nq.gz
    ├── 67d4cdf23e57923bbad3a2c7033e8cf16444da48.nq.gz
    ├── 67f0e3bf8cbebec81a2735919b97b312f8e62f37.nq.gz
    ├── 683b1f13d12e82e5e525ade1bf2db2f4a59e7c51.nq.gz
    └── 6986a1019f9beed69ed05b78bee30586f2541061.nq.gz

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

[python-telegram-bot/python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
