# Repolex Knowledge Graph of jsonpickle/jsonpickle

RDF knowledge graph data for [jsonpickle/jsonpickle](https://github.com/jsonpickle/jsonpickle), parsed by [repolex](https://repolex.ai).

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
rlex download jsonpickle/jsonpickle
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9bf812997efc5e2d0a2dd2a27073d068569604ae
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9bf812997efc5e2d0a2dd2a27073d068569604ae
│           └── chunk-001.nq.gz
├── blob
│   ├── 05d0c79243e92ccb7d21d970708a972c49a19cdf.nq.gz
│   ├── 124aac0cff8f152bd6b6d1a31c59bc7cab9e614f.nq.gz
│   ├── 163aa273e402210a2c2d32343f73727cbac14592.nq.gz
│   ├── 1738475f4ee1cab9eb16a612ccab7e14ac78072f.nq.gz
│   ├── 1a293516cc7c029614cca9e5bb9e918d4a2fb46c.nq.gz
│   ├── 1abc9b7ef2012aba7bdd6471400e0bd029c461e3.nq.gz
│   ├── 1cb7063d0744ece1837aeb5434e3447194b3ff98.nq.gz
│   ├── 1e2eea5c079164a95ca2d1f7f23b1fc5d11277ff.nq.gz
│   ├── 24fb8c5d3a405723aac88b347cc71ee2077134e9.nq.gz
│   ├── 25af9e8bf0052e6a6c2f912a93d2ad2abbc04e0b.nq.gz
│   ├── 269f5937cda2ed8fdb6a2941e86db7703dfb0e1a.nq.gz
│   ├── 2c472693bb42080111328f85778fc41431e78ddc.nq.gz
│   ├── 2c501951c513d0ab54f7505c79d3bb26c0be26bf.nq.gz
│   ├── 2ca51a47637622d8b764e5b994cc3ece68fca3b8.nq.gz
│   ├── 2d48f1dced12afa6a336b7005cd21592f4242d1e.nq.gz
│   ├── 2e05682ba276fa05b8604625303dc4dc4baf9f08.nq.gz
│   ├── 2e0bab72e2107889340676307d1867cde58137b8.nq.gz
│   ├── 2e22cae2e5d467e87ca478fe336dd0b09133b43b.nq.gz
│   ├── 332ec53458941210471956e967ab59dc6bf53bcf.nq.gz
│   ├── 3b825d76cdd987673eb5919fbf013c6d3cb444dd.nq.gz
│   ├── 452f93270d851543dbc069b4ba8351937b1e13db.nq.gz
│   ├── 4544158f9066caa5e9d8814fddc731eecf9a7c33.nq.gz
│   ├── 4775397978f36302f03a8cf3ee94f3fd9f0e5d5c.nq.gz
│   ├── 47eb1aca3c20bbdb0ed99fa6de264913f5a95f52.nq.gz
│   ├── 49d286785d2dcb1e577ad97395f6c55208af9927.nq.gz
│   ├── 4b2f026be6c6b09002901ad5ec2d120f97fb2f67.nq.gz
│   ├── 4b73460346fcc47e094f9e71cca5a0d0c8ca64ef.nq.gz
│   ├── 4e2381e80797c6ea2f7266c40d516154a114873c.nq.gz
│   ├── 521b47f6e98e897524bf4be9039723f26aa3e759.nq.gz
│   ├── 532e3a2fc3c3c6f3bcc1e8e9eac8334bd835aa68.nq.gz
│   ├── 5366af4b308336d7be8326533303414f0bce49ba.nq.gz
│   ├── 53991a3dccf0a7da935f8f14f87191c50ca736dc.nq.gz
│   ├── 590410734f069560498d81b92581052ea9be90b2.nq.gz
│   ├── 5d7bf33d948c45d40befd4769d0c15f74615472b.nq.gz
│   ├── 5dbf304a277d0b7d8282a0e9492237907202583b.nq.gz
│   ├── 5e6abca3328bcd09bf77cc9081e887d245c22e93.nq.gz
│   ├── 5e7557df05fac150a89651761ea81ef0136db617.nq.gz
│   ├── 5ebc9446c02df6fb46e2dce18f805393314dfd2a.nq.gz
│   ├── 65170f8495f60cc6b2779c6b441684e4612d5edf.nq.gz
│   ├── 66aae4cf628690f3edb70998eaabed1bf499cf4e.nq.gz
│   ├── 6a1c99a98f1bdc2454b915738fcd380bcdd8b288.nq.gz
│   ├── 6bf91e8ff31543b47b767ae2e1ce4a28ee0fe20d.nq.gz
│   ├── 6cf25f1277d82cb9910968ec21793eb98feaa76b.nq.gz
│   ├── 7bfe078b64016ba5b6778afa1bf311bbe890490d.nq.gz
│   ├── 7c895cba7f9a3a47efcffb7c79bc6183de7f6215.nq.gz
│   ├── 7d36f257a17197de1d0fb17f034002649425a7ff.nq.gz
│   ├── 8248abee4872cf8580b61031e1a39914a833df86.nq.gz
│   ├── 82e540d17f62572004a30aa64621d91ab94ef952.nq.gz
│   ├── 88c25925b6d5325660b06855446fbad3155be70e.nq.gz
│   ├── 8977ad20bf78e14234d4b03d521b4f72de82202f.nq.gz
│   ├── 89a19adbeaa86dd06474f3e9f1edd8ae0450896e.nq.gz
│   ├── 8b6ec982b15a172e27dbfd990ff11f341773847c.nq.gz
│   ├── 8beb9d7f9834a0d9c4f6146941893473cd4a5cb3.nq.gz
│   ├── 8ca1dd2989c79a40ed4f9a9055d2464be47b0364.nq.gz
│   ├── 8cacecc5d0442de1ac0b8ebccc202659a9b95e20.nq.gz
│   ├── 8e217503ba1a68826af8e1e9db4bd16ce7a21857.nq.gz
│   ├── 8f707506461876fb1ac52f4bc3e68e4bcd3a6bd8.nq.gz
│   ├── 9dc69509242288aca8220ffc918d7b8c16368a02.nq.gz
│   ├── 9fb7d5e277b07005b000ad834f65914c317ee447.nq.gz
│   ├── a6d0080b7e57b71630e8c3da6e1e52b42d93333c.nq.gz
│   ├── a782a693c57b8a86b654610071475ee2de43b127.nq.gz
│   ├── af24994784feca081c7a8499b9b28d517c7fe19b.nq.gz
│   ├── af87866ce399bf36020e6ed2da7539ea5a256651.nq.gz
│   ├── afc67fe8dac5f6d00037ec1ec58e166988c11667.nq.gz
│   ├── b150a02ea66cf1a6d27a19c08924f90b972f9e8d.nq.gz
│   ├── b52f1ece9411dcfb77b06fede9f300e50a79312c.nq.gz
│   ├── b91c3b6d65779c372449c1552bbfeae6b7d2cf6b.nq.gz
│   ├── bb64854fb95439285adc2886f7cc30ae49e74094.nq.gz
│   ├── bdbb629302c7b9ad38c944b31994d27b4d497054.nq.gz
│   ├── be1ed1220e94b311ab86b8ba4ae41b64c55e12a3.nq.gz
│   ├── be8e76ce4903d7de429f5a37fb9457fa0fe51aab.nq.gz
│   ├── c4ea4401587714bc1a667e5f534c03ba9038b0eb.nq.gz
│   ├── c6da22904c66ff63e18938e53e0fe9c1496bf8ec.nq.gz
│   ├── c7b98c454af5cb9b0aa7cd433b6b72beb62c19af.nq.gz
│   ├── c89c906b87edbce552eee160f81e9cf6d1050064.nq.gz
│   ├── c9a22d56d91bb6155df6130a69583424d91f8f52.nq.gz
│   ├── cb13db3fe6e870af184e69c5f4be65ef3a75d291.nq.gz
│   ├── d1c1bba27fcb10b9c3ce8fd9fda8eb3d0a78bf41.nq.gz
│   ├── dbee2880ec3af389139806b3ba229314c53a3157.nq.gz
│   ├── de30f582d1822a71f152b8a7fc17605adf409285.nq.gz
│   ├── e1fe68650249ff1c7c7a6eec0657946a67fba025.nq.gz
│   ├── e2431ed5e42a8ec8aa333b8e1102b29a75fb72b8.nq.gz
│   ├── e43686bde42b73b2db5825e7bde2f807be694e03.nq.gz
│   ├── e6359014ed3a24187ecb91627d38b46230fb0a07.nq.gz
│   ├── e64097d711984bafcc358b8bd10aab5cc51b1a64.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9f1f187e51507c3ac0c8dc6f22e89ba385f7701.nq.gz
│   ├── ea706a62319f3aded10f43516de69e578472a53a.nq.gz
│   ├── ede50263a117ac51e8a2427507eb37c27e938d2d.nq.gz
│   ├── efce3fe894bf57f07c32dc3bbe8c60a960d53324.nq.gz
│   ├── f042ccedf340d7cd30b14bf74dc4841c0e572192.nq.gz
│   ├── f0da162db503da3c7ead254d31b71e45ceb55cfb.nq.gz
│   ├── f35ceb1d675bf4cf8838aff34b173a00efe3e3fa.nq.gz
│   ├── f70e56535c9f9f56dc76631ae2ca6d81480b6a5c.nq.gz
│   ├── f86ad37d96f3ea71d9391319e355552a6baa800d.nq.gz
│   ├── fb841d190c8ffb1f5a268b072265ea029f06e832.nq.gz
│   └── ff5c36bf8131699bea3df0ed7d506373efd8adfe.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9bf812997efc5e2d0a2dd2a27073d068569604ae.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 105 files
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

[jsonpickle/jsonpickle](https://github.com/jsonpickle/jsonpickle)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
