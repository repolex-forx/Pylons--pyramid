# Repolex Knowledge Graph of Pylons/pyramid

RDF knowledge graph data for [Pylons/pyramid](https://github.com/Pylons/pyramid), parsed by [repolex](https://repolex.ai).

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
rlex download Pylons/pyramid
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 948c6bac3b8ec5160e85e3bf9653c767c978ed94
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 948c6bac3b8ec5160e85e3bf9653c767c978ed94
│           └── chunk-001.nq.gz
└── blob
    ├── 00c25d54b99440ddf631d091552079bad1aa29e7.nq.gz
    ├── 013d4538f3f18f5d187531ab6aa6009973df23cb.nq.gz
    ├── 01d366e7b88869081f8c76fe6eb55192764d0cea.nq.gz
    ├── 020403c8b7d19bf512a686e333b0080c67f4aecc.nq.gz
    ├── 02cd8ee3ac0ceae7a2d5d36a5232bc9a08d94723.nq.gz
    ├── 032c55584deb02ad62b3f430a937a26cb94451be.nq.gz
    ├── 03ad5c8d248c9d4324fa7890cd5808caddf7240a.nq.gz
    ├── 03ba0f669d679f1ac406182117878dba4a3c51d7.nq.gz
    ├── 054a741eb2a7fd839afe20d37c4de2ec6d143550.nq.gz
    ├── 054d037613f374724a137366827917406f97d6e1.nq.gz
    ├── 058b7254b111cccc89db267f9fb6b7caa3224e19.nq.gz
    ├── 05985fc308734c3b23f8e7a313a4c5ff849138cb.nq.gz
    ├── 0726cb6aa43fbd9b1fca22f2a25bd8bd3ba516f6.nq.gz
    ├── 07298940cb426dd2890198fba434b4ce96130e7c.nq.gz
    ├── 074237039909ee20d75ea00634950277a9a8a49b.nq.gz
    ├── 09315a77db5c59b7b9d446cf122036116a3f4832.nq.gz
    ├── 095666d67b2f49bba2f7eb116ed43da754237239.nq.gz
    ├── 095c3ef7613858d37030b48b414f6918ccc9def0.nq.gz
    ├── 0a43bc5e3b2a30ad5c0b4a538f73cfcc4c170486.nq.gz
    ├── 0a703dead7f423c228eff051c82a459af3d885a2.nq.gz
    ├── 0a71384dcd5b65d3b9a6bd120c565b1947e446f8.nq.gz
    ├── 0a8463740e1b43226e53b7917393b3e7fdfa2b73.nq.gz
    ├── 0b019fe825e15fcede8380e16eb92b00be305008.nq.gz
    ├── 0b192ed25f2f9b81b639943260b148a852cb2f93.nq.gz
    ├── 0b45f05f373a8d120044b56c2d08dbbfa7632087.nq.gz
    ├── 0b7554e23e24c19e2d524a06a021e534bc2b4e5f.nq.gz
    ├── 0b983a6c5f4609a625670a29a1c074c0b7d238df.nq.gz
    ├── 0bb7da1ba22fff3f0806c02803cade56ce13437f.nq.gz
    ├── 0caca02b4248f9936c3b89a455083e8cbd1084af.nq.gz
    ├── 0da8380f8f227ce0871893ad04adeb67a8c4d484.nq.gz
    ├── 0e17e57ab6c15328d9a02558fb2e09cfa5c5ced7.nq.gz
    ├── 0e8508558bbddfa3d03f49f8e1f8a674519f37a7.nq.gz
    ├── 0e9ea72bce7fab7ce5d501fbf5ce0043c368603e.nq.gz
    ├── 0eec3192cd0ffee786619313bd5374aaa604b246.nq.gz
    ├── 10c35ab7baf183c26b3849a95322befd2772a4c7.nq.gz
    ├── 1117a57aadb206c442b5e278a4e9dda534f9e553.nq.gz
    ├── 11e747d15281cd528f74c8399d32af899ab3b952.nq.gz
    ├── 120cfe5da11454095b0c1a901fbdec0f0e1c2e5e.nq.gz
    ├── 125b22a9f00b7aa675065da120a8bf0c373c12dc.nq.gz
    ├── 131373dc027e2869a27e11e45d3fd97ba6ad50b9.nq.gz
    ├── 1366a179532e7dee0df255d83d99b7fbfba6cb92.nq.gz
    ├── 1494882064b022834155f5bcb9fb475a13667862.nq.gz
    ├── 14b902fd100ae3e103b0a813a5658d7916df39e9.nq.gz
    ├── 1537777c93fd45544c8443f7fd14d751ed7621f0.nq.gz
    ├── 1541cdb230ef510e089e692c955fe898ec2e9113.nq.gz
    ├── 160d97abe7df1e9e2735a6ab1375f98f1c9e101d.nq.gz
    ├── 167f6171598524b4bcee89c4182640413d74a447.nq.gz
    ├── 17d6126d6f7b30cf34457afe211d2321e0f84f0a.nq.gz
    ├── 17f87bc198f6c51ccfc2d4d633849b82f26a1257.nq.gz
    ├── 1803f9de7055b30f7b7901c302f658b040b87b1f.nq.gz
    ├── 1853d983c76774f41f7710fb93711455f5527ed0.nq.gz
    ├── 18832d35117ef2f013c4009f5b2128dfaeff354f.nq.gz
    ├── 18f8b0cc191fd5476f764900e8a81c20c30c8f62.nq.gz
    ├── 1972c155d7907b1f3dc996261438a63456281948.nq.gz
    ├── 1a076de8599fbdab98608afdf35b6393f32460d1.nq.gz
    ├── 1a35cdb4aa12a6dd730ed371ee25522957273dc9.nq.gz
    ├── 1b4118b85a056ac38115acceb37acce0d19fba2d.nq.gz
    ├── 1c02a8ed2bcea001b4c557b9abb6a474f773c7fe.nq.gz
    ├── 1cc2f763c0edb3d22fb88b42fb9a19bf64cff940.nq.gz
    ├── 1cda9a53dc357ce07d3c67051b7615ebf7dc2f64.nq.gz
    ├── 1ee05bbba9695295c43651634651e6fe4c1ef707.nq.gz
    ├── 1f6783c068945e4005e133fe17e0f1250945ce37.nq.gz
    ├── 1f8fda09922543edc11e49c8457385f798347017.nq.gz
    ├── 1fb1cd53ee67f494f1a45658d73deef252c077b6.nq.gz
    ├── 1fba3ff317f83640ea32631ae6b328160e7b4cdc.nq.gz
    ├── 1fc831e66d28d285bc7db05325afd52ddb1a3b97.nq.gz
    ├── 1fd9db8ab248342897ba6d062205d61e5c1c64c1.nq.gz
    ├── 1fec15ce549b056920e1d2c0de3fcee234220bf9.nq.gz
    ├── 20d33b733308fce864876152073fabe7a7102cdc.nq.gz
    ├── 21c30e0b2f66ecb77c3e2b77c4fca26a5a3c7b59.nq.gz
    ├── 221617fa721edc0bfda2fc845dbb85d658edf309.nq.gz
    ├── 2245d8d0772a31b6a9bf194c56048f2ccc242720.nq.gz
    ├── 228f18f3644f4b6881ef57729250fa341950c889.nq.gz
    ├── 22aa8aad63cca31e7c98faadbe3196b9d8ef4e0c.nq.gz
    ├── 22b60961a757d789e78825e486c4cb1048c9b82c.nq.gz
    ├── 238e00b2a246280986c05ede6991023441b8a538.nq.gz
    ├── 25504ad4dc0d1b961da1577e357af0fed0159c4f.nq.gz
    ├── 25bab04d0062f7983985ea30c7c0779c6eaa7325.nq.gz
    ├── 2607c83f2a780df0e98e54e6e0c261c3cc973401.nq.gz
    ├── 2683e045162c851b5e54c15f7ffee41f9f4188a9.nq.gz
    ├── 2706cc184672e495ff6f02be02d1fc213608bc8b.nq.gz
    ├── 27970ed88bc26d5a62799f01e61d88c9c338dd73.nq.gz
    ├── 27b5450546d39e839412155291f14929892be1bd.nq.gz
    ├── 282ef327f2ee945da912b337231cf23092f960cf.nq.gz
    ├── 2924a5eb504d425c769b8aa3847f512c23832663.nq.gz
    ├── 29539c6b5bc3f506085949e84aa595b580146d66.nq.gz
    ├── 2b054c57841171389bd70b100ae552924890a50d.nq.gz
    ├── 2b4e84f30998305596c4fded7fcdd2eeef024a6b.nq.gz
    ├── 2b9c7da11262e207276893f7c797c7a85599317b.nq.gz
    ├── 2bcaad0b3a949825137d1727bee890e02085e7a3.nq.gz
    ├── 2c35d84ef1db4f2dc9fe1628328efdff03b7bef1.nq.gz
    ├── 2db39bf1a12d3a5dc40dd11ed9a5270789671975.nq.gz
    ├── 303ca2c5de5cdf60f3687fd6fffa9b357bddf9db.nq.gz
    ├── 3090d7e75e9b1c16ab94ce2312ec713787db53d0.nq.gz
    ├── 30d731d4a061a2536ad5f74adc2b04f48edcca09.nq.gz
    ├── 30e4f3e27a3551e60808a2828ba19b7a7ec34b46.nq.gz
    ├── 30f6079f2112a955a233418921caa9154194fa76.nq.gz
    ├── 320e01c9178dd75c22ad28510cb773cfdc6bf73a.nq.gz
    ├── 329c002083948c9f8599448b74dda9ac6dd3f327.nq.gz
    ├── 341cbb88434fedabf806abbae65b5cba45cf9d99.nq.gz
    ├── 35012fbf6a1c6bc0cd9b41e5fad1e88527256f9d.nq.gz
    ├── 35d9131df0cab635073d9a5d376ae0d11062f0e9.nq.gz
    ├── 35ef6aabef2d956ca48ad83b47ab165fed7681cc.nq.gz
    ├── 361d8f1cf36924d051b75b4fed2dce4764ad9b3b.nq.gz
    ├── 369ab9f38665452e87c95dbe99dda228f70a5945.nq.gz
    ├── 36b131242ba0a3f318b98b5739879980c8c400c1.nq.gz
    ├── 37101cff33b4376bcb3f4212ea867d30cd802cf9.nq.gz
    ├── 3729fb849e6af007670ed2245b2f4c49d6e5850c.nq.gz
    ├── 3767506fbc5d51a4b29c87fe496c16860fa5e186.nq.gz
    ├── 376c42ac88bf3301c254181570118a6eddc32374.nq.gz
    ├── 38501546e587b48dd7de398815316316f68acd24.nq.gz
    ├── 38712bfd2c571004e062f712f3b0bca6f2a38c72.nq.gz
    ├── 38fa7348d10e981ad3d58d5b5b563f0a3195a866.nq.gz
    ├── 39a384b3d75c261c4ae9804bca4c2cb8dfe81b9f.nq.gz
    ├── 39e35a89868be06f0c361eb56e1829cef003f4e2.nq.gz
    ├── 3b1e38c7df5caf80fcdcce4c028314a35c6b4f48.nq.gz
    ├── 3c0a379925714a84ea14928e8e6f087993cc9df7.nq.gz
    ├── 3c3d7293e3868944d3a4f2d4091b5893f9ce67ab.nq.gz
    ├── 3cd1e26aa3032d319c7e441731af1b0600a15cfa.nq.gz
    ├── 3eb4b040b377395e2dd936c95c781cd3d1baf87f.nq.gz
    ├── 3ed0bbccd8a8ebe16c8595ea09c6fb43732492c8.nq.gz
    ├── 3eeb7f26de3799c193fd0fd32efa2d6e6f80b5bb.nq.gz
    ├── 3eedddda1ff75f9c3d6033c93248c23a560fc284.nq.gz
    ├── 3fe74206626655514372bf5b374db345a55f24f6.nq.gz
    ├── 40002347ca4870b60d0a5984654035d6d87d1be2.nq.gz
    ├── 4045871dad3d590730e7aaafdc5f059eaf7015d4.nq.gz
    ├── 4071776f9f9260b871548ea2be3785179fbf101a.nq.gz
    ├── 4091bbfbc56ee93a88ebd84f12539abdeaf398b8.nq.gz
    ├── 409f3684977bd6668a113a53945552eb2233ba92.nq.gz
    ├── 40ad7f52762b4e3c5851ed44b88b642900fbcd14.nq.gz
    ├── 417b8c7b5b589ca8f3ec2becc176bcf1ce6ae5c5.nq.gz
    ├── 4248acbe72384d88c7e437df9254fd9cd1276f91.nq.gz
    ├── 42ae1e0b10b9d411005ec4ed32a77f9a21e39415.nq.gz
    ├── 431fdd5eccfdcf9d435be385c71d8fe4b506df35.nq.gz
    ├── 4381235ec7378a467f48b52dac9e9209c8d1a486.nq.gz
    ├── 457835663e916a766774a47c3461c93f369c785d.nq.gz
    ├── 45a3167a7d2ba5fd632deabb483925994d2473be.nq.gz
    ├── 45bc8518b34559fcd0fd0630bc7d0d5dc1b24874.nq.gz
    ├── 46b1e331be93bedefad3c4b3e3e3e8c5a902d3e4.nq.gz
    ├── 46ce86a4ec14c866f041b1d9133cd5e747284b09.nq.gz
    ├── 46ecd85814c7049cb837605afe257a0b073f7657.nq.gz
    ├── 473bacfc8f8bfbb1faffb02e45cc335ea2b22677.nq.gz
    ├── 488e7a6afbf36d26d42481d5102823ccb28091bf.nq.gz
    ├── 490f7e922147460b7ef0c326b9933fdb997038a5.nq.gz
    ├── 4a36f00fd5133d8af897c81331efeb5c5b834de8.nq.gz
    ├── 4ab837be95b9415834ae9f1dca729d3099cc670f.nq.gz
    ├── 4ac4c60a8c8cbb46523a6ee3e5999c3bf011035e.nq.gz
    ├── 4ad7ffb9fb69aaac1e183e9733af12de9e38a744.nq.gz
    ├── 4ae265a9694034704c4bbe593320045518aadd55.nq.gz
    ├── 4b2dac36d380c458cfec454a70bce3fa55e539ed.nq.gz
    ├── 4b912e2bdcaf09767cbedd30da3531662279433b.nq.gz
    ├── 4bbc01e11f238bf6d379020d8a207421c50a1d51.nq.gz
    ├── 4cfa4f90d34717a2605846b168ce9a831e0278fe.nq.gz
    ├── 4d58ce66cf99b4b938cefd810c2efb32b9b60e68.nq.gz
    ├── 4dc732acac1665b1110fe6e29c07c540f0358512.nq.gz
    ├── 4e5507e3a95908883493b70bb2bd4b69654fbffa.nq.gz
    ├── 4f7a97d300b3e9ff96dc97d555d8896c0d0d6077.nq.gz
    ├── 4fb4cf17466b9ff9e1806b28229b735fe5c341eb.nq.gz
    ├── 4ff858d89ee6b03e4b95ee14e57009b3dd5c42fd.nq.gz
    ├── 503cf3018863ae8469bdbab6343f90bf97bfde7e.nq.gz
    ├── 5062779a6d1873a4b1f124a8f439d9d73946dacb.nq.gz
    ├── 5088bd89a76dd071033a9b2e97fbe2edee800fb0.nq.gz
    ├── 50c34cbb5e956b4bf635e750045e92bc914b0e33.nq.gz
    ├── 52e002cf50c24b8f1569d8661ba7558b5d922de0.nq.gz
    ├── 535780d134f959924b52236dcb41ef4655d15f04.nq.gz
    ├── 5361188a3ace4a548ee573fd2932bf091314ae46.nq.gz
    ├── 53bc0f5c7c8d330e6f352b8e27d2b98d569f72fd.nq.gz
    ├── 53e105a8e92fb39f3752c6985d85f71ce10b2fca.nq.gz
    ├── 5476a9c7f3b5775bb8dfc29a33d903b9bf0950ae.nq.gz
    ├── 54c6e5fe72fb128924a82a4a32618aa5de76673a.nq.gz
    ├── 5546f87940b05d4956be18a7a6c869f9b03b6693.nq.gz
    ├── 567328307d2ca6d4d21010052a171cc303dc5292.nq.gz
    ├── 5737055179c779b424f85fe92776d847c5e82905.nq.gz
    ├── 57867a1ff5325e18b0d6ad6a0cec8a4ce24ca361.nq.gz
    ├── 57a80b3f5243aa38e18e04bbfe50d26f6c9845ca.nq.gz
    ├── 580b0f94fac930e36446b96aa3735f0aa2401e10.nq.gz
    ├── 580ea41c54728ce676935c13bea2a1ff9fdcf9e3.nq.gz
    ├── 5837f550455d60e67a0bf24cb21fa81753bd96a2.nq.gz
    ├── 58c3e82e80ac7e4add7080ef522a6d57b022c051.nq.gz
    ├── 58d23cff77a047edbec34ff8fae8552574542fea.nq.gz
    ├── 58db53c4ad269ebcfbdd4d7b64140af7a872f88f.nq.gz
    ├── 594acc8d6e7e82af9316dff70be3d47d52655e85.nq.gz
    ├── 59a37280e38c6dc9392a9e37c059fb47ece1b355.nq.gz
    ├── 59e8d0799d8353a0c43c3fc05b12a6f0f9efd3d4.nq.gz
    ├── 5a99fc1c619beffa57fc2f686d5e8364437c1898.nq.gz
    ├── 5ab01d337312cc8145b34f22a60c0b8195f72f2f.nq.gz
    ├── 5abebb2776a30750e57cbfa76baea77899ca4a17.nq.gz
    ├── 5ac1209d01ca10b6c08ed73477e1e3369de492f1.nq.gz
    ├── 5bb21fbcdebb03dc9525b43b1fd81bff85f67ef6.nq.gz
    ├── 5bb534f795ae0f566ba9f57c31944d8c6f45284c.nq.gz
    ├── 5ccbf4ea4279ad3a2e1fb68c753951088ed3bd2c.nq.gz
    ├── 5e28c8c0cf21134c32f43ecf5f2a66079cd7b9b1.nq.gz
    ├── 5e7317fc719ec0cad6983e9c989e7fdd6b53c1d7.nq.gz
    ├── 5edb15285d5e2ee7219bb8c980e59a145b41473e.nq.gz
    ├── 5ef28acd107d905848a878954bb629b250ea9004.nq.gz
    ├── 605f618577bcb1a82538857888a2abdd7e8959ce.nq.gz
    ├── 606495f13709552e826d8427b2e61855ae0cff79.nq.gz
    └── 60904188257851ce5f7a9e128554001702e38f1c.nq.gz

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

[Pylons/pyramid](https://github.com/Pylons/pyramid)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
