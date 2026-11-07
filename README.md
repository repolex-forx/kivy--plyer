# Repolex Knowledge Graph of kivy/plyer

RDF knowledge graph data for [kivy/plyer](https://github.com/kivy/plyer), parsed by [repolex](https://repolex.ai).

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
rlex download kivy/plyer
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4853b3a92a786237af966b86d07fa8242eee9aec
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4853b3a92a786237af966b86d07fa8242eee9aec
│           └── chunk-001.nq.gz
└── blob
    ├── 0065a6ab32e1528241ced341544d2dcc3c20e8e8.nq.gz
    ├── 00e87d4a7b25dab29ab8e298668f735545eb0171.nq.gz
    ├── 00eeb5c522221c369f38555c974e09b8954daf5b.nq.gz
    ├── 02c3a107c3debf9227cb49d749d13a7ac58369d0.nq.gz
    ├── 02c45c47abc501cde373bf36e26c3d402762c764.nq.gz
    ├── 0335054f590f5387c46f0df688dee245498b0738.nq.gz
    ├── 049a2d4adc9574a5be2602f3519dc7044b2c7e7e.nq.gz
    ├── 04b7440daf3fd899fdfbc8a5338323248723af47.nq.gz
    ├── 065869a433a6c431c8c5a15ee110da797a341ff1.nq.gz
    ├── 06d311ba67041a877e3d954956cb2b11ec5ce951.nq.gz
    ├── 07630e3d011004538fc3500923eb4b2af0800048.nq.gz
    ├── 093ac24e23d78f719d55c0f0743e91ae221bd7b2.nq.gz
    ├── 0abb3f2971f53dc9169ee27417a3df7db5c016a9.nq.gz
    ├── 0c47da878533bd4aca3527cd9396d358a0192ed7.nq.gz
    ├── 0de16985bf675aafdff4b2cfaf4ef5aee7d1f346.nq.gz
    ├── 0f8aa23669393370f02a274d04e07ecd5d531aae.nq.gz
    ├── 105ebd314f61ff7d9fcbf7c19ca8fb278bf11c31.nq.gz
    ├── 10c0c53070a2ad18182ad1acff27a9b706e90bd8.nq.gz
    ├── 119167cfea07e03959c170020d07a03ecb5c431f.nq.gz
    ├── 11e60e8971c10aa71dfcc225f26da0dfe7bd1485.nq.gz
    ├── 13dd39441cd0970f76c9e5bcefc0c06117c3f807.nq.gz
    ├── 176a94494177b8aefdbb5b8a9e994ffda5d6bfd0.nq.gz
    ├── 191dbbc70a30b15505ca4dec2eaf5bf12695d5ec.nq.gz
    ├── 1a798eca4d37daa7db7b19a5e57a34f52947a8a0.nq.gz
    ├── 1a8eb6c8129c62f48bbe1ba59e726dbacee0fe1c.nq.gz
    ├── 1aed295c8b67a3a831a7a261afd669185283cc06.nq.gz
    ├── 1d8202dc0e052d96715a6a8645a4120c0755445a.nq.gz
    ├── 2010bf3c335b84fbd7d1eb58cc4fa2fe6e626cdf.nq.gz
    ├── 23d119c01155680678faeb42a21e5c425e1c5a0f.nq.gz
    ├── 24627fa6fab75be9af34ef18f5884d25d46a8440.nq.gz
    ├── 248f5cf635252d30d261ebdfefed8a18465cded3.nq.gz
    ├── 26804ea44b016eee0abbd1f41ebcedd5be2cebb9.nq.gz
    ├── 286f7d0f79fffff0e664588e57443d21b80776a2.nq.gz
    ├── 289a5c01e6a4bf07c15a244cf00070848850b3a6.nq.gz
    ├── 28a28e0a93a57cab2ee9a178997f679012f07e21.nq.gz
    ├── 29d18faa24b01a0961febdbc549acede3d161a63.nq.gz
    ├── 2a1388c7d0ca0704efdc8fc552681f80c11191ac.nq.gz
    ├── 2a72e68703b8964b2c2393ea25cf157cfce60434.nq.gz
    ├── 2f073d88973f7db7f4ec5cd34bd934dfd11c05ef.nq.gz
    ├── 2fb37e841dc98c003a236c2fded5ccf763b72dc8.nq.gz
    ├── 3107560b1e04026a5cf99cfe90885cfa1158e875.nq.gz
    ├── 314ed341084ff5b3195daff9c3609c2cad04387d.nq.gz
    ├── 31d2d5bf2916c9f7ee511f2a99fbc153461b4fac.nq.gz
    ├── 32473c32726855f9aaa5c3694d84e3ee005460a1.nq.gz
    ├── 3384a66d7ff09c112cdea37cd56dfc80a4e400ba.nq.gz
    ├── 340653c8a79fa9355eb1d9f65e17c6d7fbf721b8.nq.gz
    ├── 345550c006f3bb7222bdb3510d0c79a6c901bda6.nq.gz
    ├── 37d58ff66735176527720de604aa7ad777778f1a.nq.gz
    ├── 38ab99d01c0c42dbc139668e21bc17f1e08e9b5f.nq.gz
    ├── 39327725f5b5c20ce9c9ba77660dbb62014c666f.nq.gz
    ├── 39d9d93d62dcbe7c4192d81bbd1a7de18446158a.nq.gz
    ├── 3ab9ce126e5a75684191b11531d50f741a2fdc2e.nq.gz
    ├── 3aee2fbb27318d83800a103df53aa2ad405d240f.nq.gz
    ├── 3db9b59d43db35df81baf6833664ce9bab9f9a7e.nq.gz
    ├── 3f8d2f382a73e662dd6557714f419f9b1a157644.nq.gz
    ├── 42dd9d9aa15768519e4a3ee64b6c37e14f6006d4.nq.gz
    ├── 42ff644a9e2b4d96ce531913583110140ffb0527.nq.gz
    ├── 43335a5af4a0d83e4c3de533d00ed14bcd9556f9.nq.gz
    ├── 439844b4f6684855c49be60b37e31f5c9f32082b.nq.gz
    ├── 443873e28c7808947a6ed91aec332333d513e5d4.nq.gz
    ├── 4475b94c79473b22af568f3617c3d16d4d94c21e.nq.gz
    ├── 44926b1c72358d6937a024896b47138291b90696.nq.gz
    ├── 4738cd6605dad295d84ca9a832ed2c94b0455188.nq.gz
    ├── 477d8a1435679b1ad0c2024ababe1dbda0241222.nq.gz
    ├── 485882454faa1e817b113a2478c1e8b4656c09ec.nq.gz
    ├── 498e28eded473f39f7930ecbfcff7c8ec487e319.nq.gz
    ├── 49bc64f83055045cadee096558070c8c90dad9ae.nq.gz
    ├── 49c5d4ddb4e3930a059f8631f48e56773b02f8cc.nq.gz
    ├── 4a58f1f0bccc50455efd3542ca27fa3a5db4091e.nq.gz
    ├── 4b231a853e071e3236eedbe1abcd50f811c9628e.nq.gz
    ├── 4bf1bf36d5365fe824d9dac895cb8f9b80697477.nq.gz
    ├── 4c0f9b76806e25727f707ecca730ae4326a5f8ab.nq.gz
    ├── 4c52738d92a6287002de0e1a8626ba4027b297e7.nq.gz
    ├── 4d302499ff16ec2fcf166696332391d9e224756d.nq.gz
    ├── 4e3506010a8a57901c413ef0dda95c8e0299719a.nq.gz
    ├── 51681e049579e4d5177e989e491b42c4446965c6.nq.gz
    ├── 51fd86c39ade4309364e19d65745439e3d8759eb.nq.gz
    ├── 529af25c3e2844a3c191e0eb33fed0cfd4e957ec.nq.gz
    ├── 538724bd13ae30a5deb25c8f1b9a7f7bd04c429e.nq.gz
    ├── 544e34318a9df126101f1c3e43be3b3f65b58ef8.nq.gz
    ├── 5494f4e52d219eaddffd4cd1fba9c1a3a0f7bd32.nq.gz
    ├── 55ec8476e8513e71cda912ddcdb83080649f1439.nq.gz
    ├── 565818f3b65f50105060f0c0506ed30ba7ef5b15.nq.gz
    ├── 57893003e9c4233fce3c12e9a48bdf16115f2068.nq.gz
    ├── 594082215c3344206b94e2c440002a76ac3fc282.nq.gz
    ├── 5958f0dd20bed960ec5a5f74d64bd80856b67977.nq.gz
    ├── 5b9ed4866def14ff30a97fe60c3424a215ccca39.nq.gz
    ├── 5bb16c62351467affd1797d6f90278fb867cedc0.nq.gz
    ├── 5c4c25e49ec81b8a7d0f34ccc7163381456e8c62.nq.gz
    ├── 5d0f21d25217f193ee469e291b3f594bb593d752.nq.gz
    ├── 5dc66225b31fbf6d0ca25d9135a040fcc03689be.nq.gz
    ├── 60ec4e7fdac070302ecf8ca8c66f5da34d900a94.nq.gz
    ├── 616db2f368840d015e32d5fb8a86858814a29bc1.nq.gz
    ├── 619a3b283fa808dbccfa797e9d57ea42258ee552.nq.gz
    ├── 61f70ee859c9880d22b58977a5fd896bb37198a9.nq.gz
    ├── 64cbb6d597eef44a5d3e71bc0e423b1bffce1976.nq.gz
    ├── 651b6a7ea7d398b4e64d7646107bdd66369fda42.nq.gz
    ├── 66a3490cf8c5dbde07d4efeac168d40611a71a71.nq.gz
    ├── 68fe038ddc0d42d2562e61ed1e5904e4e3f0a530.nq.gz
    ├── 695f168a5d22aa0e84701a3d394582bae7c6e61e.nq.gz
    ├── 6a2baa8110f2383ced537b35c0e8ff4f3d6077dc.nq.gz
    ├── 6b00a52b6752ee222a095705f23668e3beba72ef.nq.gz
    ├── 6d423911c150923b4c11ff18663d320172880a64.nq.gz
    ├── 6d8f3d1b21747da2b0ce73857e03daf33cd63549.nq.gz
    ├── 71406a9623045b808a9458903cc7476c547ff8a0.nq.gz
    ├── 725038433378a0ecbe3c5479a425fc5eb48fc0ba.nq.gz
    ├── 736674a25e6ecf0130b62df9e3e8c8c8afb6c4b0.nq.gz
    ├── 7436db82611454d87a32c116e4bca88ad3225556.nq.gz
    ├── 746800587fe218ca0f01daaed84b7d41e49b56d6.nq.gz
    ├── 74bb73af18937cbc6ef156ea6b18e9be02bd7b83.nq.gz
    ├── 74f2c3e72f674b552fb206ba65e2f4732130a15e.nq.gz
    ├── 755e820d2cd03b94b1f394d8b63ec81958ee3b41.nq.gz
    ├── 75d1e973bc9a8c2df4ae638abe17ebdb68fcef6b.nq.gz
    ├── 75d2b070131e5ae46fc32714a83c6990018e85c6.nq.gz
    ├── 766cc2b5ac9898912608bc889328815542a8881b.nq.gz
    ├── 7754579f393856815da8b4c16958d93b8fbd6cee.nq.gz
    ├── 77cd9115b0c1258dfec34c9d3279771cdec3e1b0.nq.gz
    ├── 78e17ac23e62184c93a627d9cd2efe28a9ed138c.nq.gz
    ├── 790b28fe714d35f16c38cf4a96351d06ba4f4e64.nq.gz
    ├── 7a393fd3ca7ad074c9d66bf0212dd07ece4901aa.nq.gz
    ├── 7acc33fb9ea0e5370db82e801bc1f23614ce9cdf.nq.gz
    ├── 7aeec83e6d0a3023bbe28f80994e660fbd6cb84b.nq.gz
    ├── 7af283b5a921f621633a686d8d496c8facb2a48a.nq.gz
    ├── 7b44f011a06b3307945389529fda1bff350da338.nq.gz
    ├── 7b7da7fe392bb0452b7ecf36912473026fcb081d.nq.gz
    ├── 7be16c4fe0e0fedc2e9bd5ea178b2aece199284c.nq.gz
    ├── 7bebaf33d8be473515de53a830b9edfbec96a809.nq.gz
    ├── 7c6f01f2f825d4d1885516771298f3b1441ba87c.nq.gz
    ├── 7cc62e67e06ae54fe1e070a51795b3afe634c6d8.nq.gz
    ├── 7ebfe87b859b47a9b816c839968f4a51a6cf3100.nq.gz
    ├── 7f0677d81f871c3cc82ede5e5422ed1fdbdfedb2.nq.gz
    ├── 8031c3417a73d5d6f784d0fefbf6cda5f3793c1a.nq.gz
    ├── 80d051ef505f89cdce343cc8f07b5b626407d41c.nq.gz
    ├── 818f0be4f706b6ab88fba35b84999e0faff49b71.nq.gz
    ├── 820fda6ac1b38faf488f067e88491543f15cf46a.nq.gz
    ├── 8272fde463051d1d69fee6ef06a064bd77678ef9.nq.gz
    ├── 855484b37368b6617904afae2e9b37ed0d79ae53.nq.gz
    ├── 861d90480ca748166f9bd46d77757cf1454046d0.nq.gz
    ├── 864c58b6f6b0dbdea8ab190bd3184a4008e7a22a.nq.gz
    ├── 8650968cf18e20caf1c150a4f888c36608a52f0b.nq.gz
    ├── 88024e5703721b8aff2a4b482d2acf55b514a4c3.nq.gz
    ├── 89413791b4d424c0158b230fbb854ad755e0009b.nq.gz
    ├── 894d3a065477e7ee2c7a21fa885f5a9666593e56.nq.gz
    ├── 8997c4d36ab0caf8b3f409dd53b7871c62fd85b9.nq.gz
    ├── 8a9c08bc4fe5df6b445ca70720deb404bfb1d825.nq.gz
    ├── 8bdffc94308c61e0a87c8ce4e8c7bde7fabbca97.nq.gz
    ├── 8cdf680567c73adc2830164635833fa0f020fcf0.nq.gz
    ├── 8d6ee2edc55c9de9ed0cc0b9f610ca78daeacf27.nq.gz
    ├── 8d722390d23af41e7aa6b26a1e295f3a67434795.nq.gz
    ├── 8fe12635338c1cf4eff966306f24ec3e9c5734fa.nq.gz
    ├── 90d8ca25dafaa3d113f4c869f7ae26fd02b85c8d.nq.gz
    ├── 91e72c37ffa3dc2071e3b75d78f7e199c6e990b9.nq.gz
    ├── 920559ff1477eb1eda7d44bd0e9883d877cf3203.nq.gz
    ├── 922182cd2956455508db56b829991638441e011a.nq.gz
    ├── 922685891431a98a21b8115fecebf4026d06a31a.nq.gz
    ├── 9306df61013635e869bcc0c95be0daea1cade88d.nq.gz
    ├── 93d5af3f29ff7fb7aeb208c2455e99ba14249f6a.nq.gz
    ├── 9443d2c697dd8a3cebeda3ab0dc6ec36762916e6.nq.gz
    ├── 944addf4cd616ce4940db9ddbf7d9afbb7780ccd.nq.gz
    ├── 94839a21244470aea4a5b146d875de2da1b6db07.nq.gz
    ├── 94a934ce5a27c9da0c2c3ece77626aa024bd919d.nq.gz
    ├── 95d3b43841253d0786d3e1b1d8e55ef87a795378.nq.gz
    ├── 95dfa5eeabbd9ed4c44e258fb2b0d961547fa2df.nq.gz
    ├── 9810562b310003c3e9215395a0dd6808c8297696.nq.gz
    ├── 99b224eb3f552c486fa4ec5ba38c80acb218776d.nq.gz
    ├── 9a55b14d2269fea2c53fc1ae157898917c4bf8bd.nq.gz
    ├── 9b26a784038f5731768d27186a72edc1742d8ef9.nq.gz
    ├── 9b5ae80038d260d3e954cae9b6b89141e8b2a74a.nq.gz
    ├── 9c6ea5fb5bc2c45a284fbe589ca072d3a83a02f5.nq.gz
    ├── 9cb4100b6b5c1a6e6c900ada7289a58f7e12b3d8.nq.gz
    ├── 9d1cf20af58975c9a1c9c9a473da8725ca1787cc.nq.gz
    ├── 9d3d4d9081c1bd6a7a7cc3270f583d6f44dc4032.nq.gz
    ├── 9ddf3a4c69d5747f2f517c2aa52b4449e13fa3f0.nq.gz
    ├── 9e1f25ba165b034e9626050935a6658b77a43989.nq.gz
    ├── 9e4846e611b7e132d75fbb7e72192bddd93fcc07.nq.gz
    ├── 9f000ff419dfa34a6727305a3e62f3be94800371.nq.gz
    ├── 9fc200bf50173b91e5aa417917f8fa652eb7b311.nq.gz
    ├── 9fe400b2b8d6eec65db721be08787c016733cccf.nq.gz
    ├── a00c7755f050a9de5759d20b7158d78019eeef1a.nq.gz
    ├── a05785874e653bff47b8c07ca4ebe82a390d9b92.nq.gz
    ├── a05b4e6c03e019dc4fc986514a535da78cb603a5.nq.gz
    ├── a2b1be0c544bb9cd377c25ab76b77e90fb21a987.nq.gz
    ├── a2bdaa59b4e691f68bd5d0ff4961e3451316a778.nq.gz
    ├── a2f1f2cde900e2cd0cf07bc5a1fdfd531f79c8eb.nq.gz
    ├── a318c3c43aea4bb0e231c6d07cdc7ad65cf38cbc.nq.gz
    ├── a36d6f391e0f526583a255cab183f15a737b8dcf.nq.gz
    ├── a408a9a8f2a3014a5c57fcc689f4e6f6cd65b6af.nq.gz
    ├── a5c5dc34484e03384a8455156f8cd59dbb38a188.nq.gz
    ├── a5dc76af50ecbcdf8cb590843b14fa2577f97761.nq.gz
    ├── a6263cde456e2fabf3a16d8fca0723b17b236a81.nq.gz
    ├── a76460d09ac165d62da536bf50a63cc69f309779.nq.gz
    ├── a7b315d7789996a01b1dda4305499a999d8cca88.nq.gz
    ├── a98bb331a2abd72c1eb5c4eea4113fcb56b72b15.nq.gz
    ├── aa549a7b104bdd21b0a733f8490076593cdb56cd.nq.gz
    ├── ab73a8c7381c2148371187880788b2415610de0c.nq.gz
    ├── ab7ab9dcc289d12b23ed46367f6415a224b51f8f.nq.gz
    ├── ac70b2ee7136d7b0d8572df9b375aade698c3da6.nq.gz
    └── ae4034acc8b53c53fba0d65c1dcbd54a153148f1.nq.gz

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

[kivy/plyer](https://github.com/kivy/plyer)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
