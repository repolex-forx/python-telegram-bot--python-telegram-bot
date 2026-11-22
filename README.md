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
│   │   ├── 5a41d2ba85bd10bdb2b2c1047758a317eb091e5e
│   │   │   └── chunk-001.nq.gz
│   │   └── 8dec234225145f8ec0cc8fd97d42208a32d8f0e6
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 5a41d2ba85bd10bdb2b2c1047758a317eb091e5e.nq.gz
│   └── repolex
│       ├── 5a41d2ba85bd10bdb2b2c1047758a317eb091e5e
│       │   └── chunk-001.nq.gz
│       └── 8dec234225145f8ec0cc8fd97d42208a32d8f0e6
│           └── chunk-001.nq.gz
└── blob
    ├── 002b70d4ad589febe658aa69f839414a9c70cbd8.nq.gz
    ├── 0033452af7a6b3992830525bfc5629de818b9dfe.nq.gz
    ├── 003414419c89b8d59780b9644fe134b04bb32440.nq.gz
    ├── 0050a6402279976c25518d57edddab7e799f969a.nq.gz
    ├── 005dde65ee907c1cd3541b52abe4c473779c6ed5.nq.gz
    ├── 00ba68e0f95331328acc0e60528da0ad1514e10f.nq.gz
    ├── 00fea57564689cc0c36268420a1d89fe4d3cc78b.nq.gz
    ├── 011a85bb884b60588c3f88180cb9074e262a73d5.nq.gz
    ├── 014bf8631b3bac716e8108a72d089bb777c20212.nq.gz
    ├── 01c2cfda73f3c265d7d05a1d8955c877b2d1bdec.nq.gz
    ├── 0204af1ee472c579a121a67dd42b19bfd93fdc4b.nq.gz
    ├── 023a3a633c5bc82c308e7d7cb94e956a8138102a.nq.gz
    ├── 02ba5742b3f27d11f20f0c3a7e4570ece67f230d.nq.gz
    ├── 02ce1a1eea103808542fb78749eed042e310d7e6.nq.gz
    ├── 02db37a8a911a9332f7c37dcdcd50a051d3b3cf7.nq.gz
    ├── 0354229e76f764e33013b2207da192fdec3a84a0.nq.gz
    ├── 0382ab61f340abd8968d5bb317ba78d7f41d713d.nq.gz
    ├── 03b56bdb103f7a25fdaa597c2cdfdc0bf4659e40.nq.gz
    ├── 03db3edaab16643061e9ef5fb15311970d748033.nq.gz
    ├── 0433a6b6cc637b00197e135a1511b11980069c6c.nq.gz
    ├── 044e957aa41a58ee7308dc9f25702934e98471d7.nq.gz
    ├── 04583cf99f59758c9bef2f40677ad21f7647317c.nq.gz
    ├── 0536ace20a884354256e55811f03ca386af25ebb.nq.gz
    ├── 053bb74f00c7ba76e83c2cf9b929bd7f7c5b43b9.nq.gz
    ├── 059c8e264ca6a5b73c36875f5c8c3578cfbb97a2.nq.gz
    ├── 05a5839595add6853784ee0615fae12bcd51d886.nq.gz
    ├── 05e7a153c0182366ae651b1a011c6b2f1beb6d2d.nq.gz
    ├── 060021dc6afa9119c2b6e3605c02adf79965c7da.nq.gz
    ├── 062db4f4d00abd4ad033a701115a8e4b221a7f82.nq.gz
    ├── 063e8cc0ad39a1d60eacd71b991ded217c1ad0ae.nq.gz
    ├── 0666c85bf2ba401f5949356f3a0abe5b658d9fc9.nq.gz
    ├── 06985f552aa43d7d7037dbe2e5fd604aab641ad7.nq.gz
    ├── 07203fbe80fd108a578a8afc17778fed0f3f1991.nq.gz
    ├── 072f4724c0fd3703b70c05e8e526170484468ad8.nq.gz
    ├── 0784d21c71f34763364e330be2327bea735c9fff.nq.gz
    ├── 079ce948924c285388430bbc7f13f426135eea84.nq.gz
    ├── 07ac3417c343a508d038b6fa4cad57d5a8e843b3.nq.gz
    ├── 080fd3d07356980db468a714b0b5f20d0157ac11.nq.gz
    ├── 083de5ebf4afc4f3af56d3ec94c532ef1301f48f.nq.gz
    ├── 084ffb6f5ab22a805fe249be8c0068cbb40e43a2.nq.gz
    ├── 087e539e3976e061904b65541d85d9f8f5c191d9.nq.gz
    ├── 0883310f324ba77449d70402adc8693d2edd43f2.nq.gz
    ├── 08e9dc0222a05902314ed14e9c4b6f0818a7319a.nq.gz
    ├── 093a5449b81594b4113066b1d615e67ecf0c0873.nq.gz
    ├── 09b4b70adf604bcdc9c361ed97816797e1dd5a86.nq.gz
    ├── 09d96c159da612c49a313a56117487a4bd1a0a82.nq.gz
    ├── 0ad16d09659a125ecbee13c4653fbf26ffcab018.nq.gz
    ├── 0aeebe750b678f2f908083d57585d6d259e605b5.nq.gz
    ├── 0b0509dff2faf7f07c543d496f8b4fd42233d92f.nq.gz
    ├── 0b0a987a0134cc70778456e36be232c63cac63a6.nq.gz
    ├── 0b2e51863af4be14e80089870a1dfd16d5fc1dfa.nq.gz
    ├── 0b3126f852d2797a0ecaad8d34e4be285ad58a00.nq.gz
    ├── 0b6cc68d20781eece9de125b6fc4b5f4c0f4b1a4.nq.gz
    ├── 0baee3f89d705a956d5afef11f9bd7c3f659df2c.nq.gz
    ├── 0bd5939081ab8eb06e2d960683d393fafd20eaef.nq.gz
    ├── 0bd9b2e6fd8639efa9987850c0c22b0482eabe74.nq.gz
    ├── 0c3c3f0f2448d58070a6b3ea3ae3905df3525510.nq.gz
    ├── 0c5f19b03aefdbdba5225806d9114e0e718fe6ba.nq.gz
    ├── 0c726895c07eecfc6e8999fd274023e80733e4ac.nq.gz
    ├── 0c7c03cb737e85639a8b9183b1080a6e37cce94e.nq.gz
    ├── 0ce4efda72c68d6411ba40f82286a6ee1e7e0fcc.nq.gz
    ├── 0d9d1a12d32abb6327dcc2dbf23fec426d88616c.nq.gz
    ├── 0db147afd395a82783a5c7bbbf5675ba59c46b3c.nq.gz
    ├── 0db160bfa4cfe2439379e46cc3a2d9418b97ee5f.nq.gz
    ├── 0deaea2e2f5918b1cf537e5dc24ed6120ac43906.nq.gz
    ├── 0e42a2990f82cf1532e8e46f57453958505a87eb.nq.gz
    ├── 0e56db89db9def68b6b541cad90c2bed20f55d37.nq.gz
    ├── 0e69b89949cfc2cb2e3f7c6ef728595997ce164d.nq.gz
    ├── 0e7feba0a27addd116bc40bb1d467388c01353aa.nq.gz
    ├── 0e9f750d446a07a2f6ce06740d58a3bf3dbe0133.nq.gz
    ├── 0ea5eb3adefdbbefd7f6befa3a39741c248f5127.nq.gz
    ├── 0eddcdf469d3523c034eb07bec4a3e7e502530b4.nq.gz
    ├── 0f14d8f819a799092f32ba1e5fd6e79b15878938.nq.gz
    ├── 0f52602a8cbe224d9a16e6135b7e9a0ca6b4ebf9.nq.gz
    ├── 0f69756b371cd04d58a10ad3f1d17bfa60de27b3.nq.gz
    ├── 0f7771ccba77223cdac7aea163af392fc2d7bd97.nq.gz
    ├── 0f78027c7babcb63065878fa00f2f7330f0eefeb.nq.gz
    ├── 0ff91ad48c84853694f6547aa69a84e6de69ec5a.nq.gz
    ├── 1050f05baf7bb71fd2bc0cf63639e5e66f562f7c.nq.gz
    ├── 1056b73c829785299e83ba1153127a4456b0ae42.nq.gz
    ├── 105bd8580c00818e256b2f040c23224d070f069d.nq.gz
    ├── 10aa76f8085970b339b33d631654717b376d1e97.nq.gz
    ├── 10c5de3e33b6bffbd80920170bf2373758da5931.nq.gz
    ├── 11080cb71013599618a23adc52a363a2ddbc8903.nq.gz
    ├── 118f9feef6a1ad51db9ef4a11f5ae0bc6bc3b4b4.nq.gz
    ├── 119d5c0db90920ac3bde88f6997bc8bb72d13846.nq.gz
    ├── 11a50f99ea015c3c2d7f0cc3152cba25fcf814fa.nq.gz
    ├── 11e5e4980ee265c245325a982c5dccbf68db75c6.nq.gz
    ├── 121d5b95b08620636776813cef1bad93bd6a9be1.nq.gz
    ├── 1230bf48277f98f4ecd31e67cf8679033eeb5ba2.nq.gz
    ├── 1261d43e68bef80010f3e0b7b9169f03f65738be.nq.gz
    ├── 12940c2152bb6054dedfb6c089980bdc3736a69d.nq.gz
    ├── 12b5e2127a1846951870b01a52d9ad66e9cbf72a.nq.gz
    ├── 12fe8058ce9cc4941e7709b60bd663d4d13fdd7d.nq.gz
    ├── 130d061020fbe95ebd766696ee571d0732c541be.nq.gz
    ├── 13b8b8da8acc25170a815673e88d8ad04b182731.nq.gz
    ├── 13f2944722fe46e2f67c5d45eaad5e91992f4fff.nq.gz
    ├── 1414993bb4f7c483d5c67f825eaa97b564b9f373.nq.gz
    ├── 142545c341926e3b3b00605be128a9b3e9c29a64.nq.gz
    ├── 143c042553bfcf861e9f72b39f8f689e8f415b1c.nq.gz
    ├── 148aaeb392d818b576b2fe04a791631852fd4b5e.nq.gz
    ├── 14b8add118b69673e297ad7f073867ec8b5df8bd.nq.gz
    ├── 14bd8e4e12637b58a788c0cc779eed65a3ae59d1.nq.gz
    ├── 14e1b7afc0c2a0c16e67ff46bc3a8c7380301186.nq.gz
    ├── 154298f853c9bbabe892ebf4d90fb497fcd2edef.nq.gz
    ├── 154f8b35fea8dab31fda83fc301b1cb1314d3611.nq.gz
    ├── 1585c581aa11195d2a2c0297ce670ec44c069933.nq.gz
    ├── 15c783a3fed627694476371f17744b7b4cab34e6.nq.gz
    ├── 1600c05903f10123cd44e9fc5cc7e8314c38049a.nq.gz
    ├── 16290cde351c353ee2fe6460f3e689c74cff36cb.nq.gz
    ├── 162ff4ed8c409970baa9566c7e9c668b2d5d1407.nq.gz
    ├── 1651d73582a923e48c37802b06899fafc5e4deae.nq.gz
    ├── 165ab8886dfac847107446bddb6503786b0ff68c.nq.gz
    ├── 16965b643d8158b3f44bbb67be1ba3d8965f727d.nq.gz
    ├── 16a73f15c177a1c27baf782bf0ed96a6dc7a162a.nq.gz
    ├── 16b7676eb5bcfba8fd73d811b3ccd377cd71cea1.nq.gz
    ├── 16bfab5b754ca2fa80278e6dae6e5789692a37b1.nq.gz
    ├── 16e9da4995712939131885f00284a017d52d1272.nq.gz
    ├── 17eb22426e3432d95439c8f6df6f96f44a9c3f06.nq.gz
    ├── 1805e3b4dd7639c3d72ff4f699f4ba5dcaba5354.nq.gz
    ├── 183e1818268d3749658293a37f78c2db283d976f.nq.gz
    ├── 189a192917074cc6ee88cc1b9acef9b766b4cf96.nq.gz
    ├── 18ec28c0da9321824d8a2635496fcea053d2e65a.nq.gz
    ├── 1954cc4e07838a51b5d462be6060f71a89f0da66.nq.gz
    ├── 19582f504b127c231f90dd9dd08121c9a25566f1.nq.gz
    ├── 1970cfb3f945bc7a911c59e61e6bb75251b47b60.nq.gz
    ├── 19750cc41bd10ec1014b70dff5db7f5c89a18a65.nq.gz
    ├── 197dbbe3967bf08ce0c75221ea7199898e4c9e3b.nq.gz
    ├── 19a0d975c29c4c3d1d3fbd216a1429c939beefc5.nq.gz
    ├── 19b1e6db53d35e7fae94e06ff821acef6e3569dd.nq.gz
    ├── 19b26d609fa5a6f8fd28c2613b1c9949cd24a2f6.nq.gz
    ├── 19b602da112b31034348edbaa81717d4eb34e01d.nq.gz
    ├── 19bfbeea31ee53f0f68f24ad8bee120714817629.nq.gz
    ├── 19dee14e0eca2195937aa59a00a77f188c65c5ea.nq.gz
    ├── 1a0a0c6fc38825f077532e6394e3b4f56e40a852.nq.gz
    ├── 1a1b8893b656d4bd4dd8e242e859bfa8d5246bd8.nq.gz
    ├── 1a337077069892f413aad746847a6fc12f4da51b.nq.gz
    ├── 1aad333ff1c32d2da73ea293b56b45183aac284d.nq.gz
    ├── 1adacb2322c894864f9640cbe54f88917050555f.nq.gz
    ├── 1ae97580e62d098f4805d4a63b7190114cda4643.nq.gz
    ├── 1b0a09a48682a4899a29bb621d5b48e06acc5a36.nq.gz
    ├── 1b29b4c38d0c0bc1d3495d72e94b9abdeea78856.nq.gz
    ├── 1b29e2e8de6a23b2f54f43b9827050c18fc530d7.nq.gz
    ├── 1bb6b6301840d9d2ba7ff57f92eeee5f5972f8e7.nq.gz
    ├── 1bc2d97a887234be0ed7d74dd49de15803efdd47.nq.gz
    ├── 1bddc1976ff94a6ce86cac66747fb404ceede0f4.nq.gz
    ├── 1c30a303afc0b2b284e03c45e6ea04dc4f6f9864.nq.gz
    ├── 1c54dd6d8f55395fdf8b629b5e17764b58f86e0a.nq.gz
    ├── 1cc14095b0ca71c0555fd451cd205fff586d31f4.nq.gz
    ├── 1d231d9411479b03a1a50cf25188249bdc9d5f22.nq.gz
    ├── 1d26bde207611183f23943ab72cd61e2987e26f8.nq.gz
    ├── 1d26e231b9eaaeb4fbee966981df6244aaa0bfee.nq.gz
    ├── 1d315888e094e01570a199d80517e2230ffc827f.nq.gz
    ├── 1d41db92b85325a34147d25b03454f40da9e693c.nq.gz
    ├── 1d669f0e7a58dd38c2e318721821be63753c73e9.nq.gz
    ├── 1d8ce6619bdb63ce61d054721e7dcc2ff8566c07.nq.gz
    ├── 1dcaef13739f2353ab8a49e8a4830b5130ab0bd8.nq.gz
    ├── 1e138240a791b9851fce21979bee1e5fc49b5d42.nq.gz
    ├── 1e30c27566c27c5ef71c0b890fecbc95b7c032e8.nq.gz
    ├── 1e4cf4e251d22fc26deebb1bdf3a12c6c72444b4.nq.gz
    ├── 1f16b7393bc93201fb6bad661bcb941daa9d07f2.nq.gz
    ├── 1f7a86f0ebc935a5b2d0e48a394554a92935f6d0.nq.gz
    ├── 1fa6e104dcb25bbd9c7f348f572508ad964959c6.nq.gz
    ├── 1fc7a5a8d3d3286fa645fbcff5414e40449d8082.nq.gz
    ├── 1fd1dd0ab72cfae649b56ffd9faf4d2f7374d6d3.nq.gz
    ├── 2116f4f4c3345f6362d63452ab5d9a8cff03432c.nq.gz
    ├── 211d8abf7524af279213fa05fec7aff2fddd7260.nq.gz
    ├── 211e3d511e17efe7c8582ae0e9949153abf5fedc.nq.gz
    ├── 220da04007eb4c9fb3ab1ea590ec98777dbc1cb2.nq.gz
    ├── 22292c70d72e5d945a9c40d4ba7bb4f75db69893.nq.gz
    ├── 22434be3efb8435c0b187368c7e2f26908627bce.nq.gz
    ├── 224e05aa2faf61f972ab99e1309de41db909bc4f.nq.gz
    ├── 2257adb942a2adb10c14a1baeeb65898cd5a9dc0.nq.gz
    ├── 2292eb44573aa8972e04074eb03ed9c490615b04.nq.gz
    ├── 22a33b9bc5e2ba2f14cb86b5ce2104478c9dde74.nq.gz
    ├── 22e2f0c2860686d362ff83fa57cb1b6e45c5ed39.nq.gz
    ├── 23606faedce89631170d663fa56ddec981da9484.nq.gz
    ├── 2386f2e6a5c639ae79d630b0973b3b332f794fce.nq.gz
    ├── 2392ff1ec5b41d856096ff19508221420735f5ad.nq.gz
    ├── 23b6620985abf0ac860a900a0cd52159514c0ed1.nq.gz
    ├── 23c15053dfb877c3f76ba19ddaf730114f8fe875.nq.gz
    ├── 23cb8c67605bf8d7378582c9bb26ebb1ac81498d.nq.gz
    ├── 240b43ea6dd5748b43cff038d48d828113824ce8.nq.gz
    ├── 241379dbcfb51ee1f2b61a8e6cca525e425fd5af.nq.gz
    ├── 2434376d4598e09d6b15fd034b8fb6fe977f5109.nq.gz
    ├── 24424c4695a6631ebd21383206698d424124ced5.nq.gz
    ├── 24475848752dd93b34e95b6858e06058dd057655.nq.gz
    ├── 2489cd6e31ba4534a623b0a5e9db96213c2e3332.nq.gz
    ├── 24984e380e57132e66dd358f319018194420e5c7.nq.gz
    ├── 2522f8c58cf07ae0afdedc2bed3613464eac3ae7.nq.gz
    ├── 252fbda74468ca65673ff9fccfdeeafa67b2295d.nq.gz
    ├── 2534d84cd65f06bdec1709bf2077e23bb393a514.nq.gz
    ├── 257e57c95c85d22248b223becfb9e79587a34ac7.nq.gz
    ├── 25aab2334874e8b4c35b399bfdf5449ae5de17bb.nq.gz
    └── 25cf57c755cd8615f1c6d36e14898432c689833f.nq.gz

10 directories, 200 files
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
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
