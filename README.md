# Repolex Knowledge Graph of zenml-io/zenml

RDF knowledge graph data for [zenml-io/zenml](https://github.com/zenml-io/zenml), parsed by [repolex](https://repolex.ai).

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
rlex download zenml-io/zenml
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2babcd8c72e39e91e16647c25cfcd87f27e6631d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2babcd8c72e39e91e16647c25cfcd87f27e6631d
│           └── chunk-001.nq.gz
└── blob
    ├── 004a88a01dac300e8acfc3ced88efaf95b513fee.nq.gz
    ├── 00e844f4bf9157d02d4ecf055f167e0ba61e558a.nq.gz
    ├── 00f707abab84f81b33c7eea3b2f02481b60490b2.nq.gz
    ├── 01807479bd8dd91035db93e9499a3bb6b18a9332.nq.gz
    ├── 01d4cfb1fc030b052bab9b2e82a31712d852b230.nq.gz
    ├── 020cb8db61c50807a3faf2ec6f8f12b049fd55e6.nq.gz
    ├── 02a7ea849a16932d70c467ce5da7f7ce7583edfb.nq.gz
    ├── 02cc656a22cd286a4c36d066429700b54a443b07.nq.gz
    ├── 031d4b6fcd0eb8b92a595401c6b747ff5cc77faa.nq.gz
    ├── 0349ff93ddec3692506f0b28944899eac0ea5749.nq.gz
    ├── 0365c2eca95a0c23cf9c982a2f2b98ecbc7920b5.nq.gz
    ├── 04169b9182b28b0d7f1f467b776b7db16b076e53.nq.gz
    ├── 04ca472c20949723be721f31c1ce7f4b113840ba.nq.gz
    ├── 04ff8483f6dbcdbd092eab9c309090346912bc07.nq.gz
    ├── 05054627523d870c3c5b519104cedcf7da9f26f7.nq.gz
    ├── 05d9cfab6a18338f33b19a75b78e571a08109efe.nq.gz
    ├── 06f3a49e3fe66e328b3fd73711858d8d1cefdfd1.nq.gz
    ├── 08970219f27d8dd7b5c74cc2961a0c6d48e151ce.nq.gz
    ├── 08dec3f5dcc80c57f6d509ca545c442654a961f5.nq.gz
    ├── 09248bb898b81aa4beba46599d62926d3b91b0f8.nq.gz
    ├── 097e591297d8e26bcd0627775fbe13234a3db6a4.nq.gz
    ├── 0a8e10c53eada64344283525d5cb6e498847afc1.nq.gz
    ├── 0b0d7e1c40f98d9547025dada6ac987970a9c14c.nq.gz
    ├── 0b99140e53f05cdf419caff2fbdef18741d732a3.nq.gz
    ├── 0cabb341aec6a87c6ffb0000f8fdad94b72e0f10.nq.gz
    ├── 0cc3398a1efa3bf449429e3e9518869037dbe6be.nq.gz
    ├── 0ce3fe30c1880d8ed2d25d4eb709acb7c6256b4a.nq.gz
    ├── 0dea85995c016afa406d8767b68b187573756247.nq.gz
    ├── 0f07c12ce5e607cf34a68cfce8ab8a5282e6a9b4.nq.gz
    ├── 0f823e370960818569e48ff1b08bc6e3c479a349.nq.gz
    ├── 11136043cb4d7b1a75f100593746627b3e73041c.nq.gz
    ├── 11cceb15c3a2eeca690af833039d1a291c979789.nq.gz
    ├── 1227e70629d1d28bbee8271f7817727fe8db7e2c.nq.gz
    ├── 13fd85dfc9abfcbcca8d390f671ecdf54d309c0f.nq.gz
    ├── 14120226c3ca792a494642ece2514dee617454ac.nq.gz
    ├── 141b73418b7bd8894dd08a81a041d2a59c441f08.nq.gz
    ├── 1467c5cc8445bb7bb0cabcaaac36a9e3f7f1294d.nq.gz
    ├── 14ac96bdefcb0066b4b83b46999bb1a80097e397.nq.gz
    ├── 14b2d6e5af7845117479307d23b4052df3536020.nq.gz
    ├── 14c78e0e47650a61d5a8866d748f7454b9b448be.nq.gz
    ├── 15355ff86c6de66a9cc06af125e9163074dc8722.nq.gz
    ├── 164f4b66b808dd77bcd9986b95dbf2f62f70bd5a.nq.gz
    ├── 1696f7779c6bb8936bbee8c3974d38f9d56780a6.nq.gz
    ├── 16c291d4b4fbcb70794722cf5fa9bd006d4e1569.nq.gz
    ├── 16c8b269ae9c13cdc0108d94a0186b7b9de03b0c.nq.gz
    ├── 171566655b06de64d3a2aa3e9c87cb08d96e79af.nq.gz
    ├── 17806d6e0584780862115074cccac945c65154ad.nq.gz
    ├── 180712a7b27db7db5dad1e34a2b958110e062798.nq.gz
    ├── 182e0869140a8635a503b471b3cc11a67d0d60b5.nq.gz
    ├── 18633ae27c0eb2ac5cae18eef38dfae37e41778e.nq.gz
    ├── 186d2f52f01e23c89e2239a5f39c77e5e3d875e8.nq.gz
    ├── 1989691a792f2f113f70562b992785f0dae85320.nq.gz
    ├── 19bb2f73a9bbb3609e23923857458868122a0982.nq.gz
    ├── 19d30c2b75638fb4c5bae261fa42a2377ecb71e3.nq.gz
    ├── 1a9a2cbfc3d1001f270fe0b6bf7e29cca47326f0.nq.gz
    ├── 1b7534d88e85bd44413ccd513669a5855dc90b65.nq.gz
    ├── 1bc1e19dfe83ac8d99cdc63bf1305d4e7f0fe41d.nq.gz
    ├── 1c0b8fb86e2d83254c79b2b89b19c9fef7b82766.nq.gz
    ├── 1e0a8ac5dac0af2d2749d72b8d20e905d89b215d.nq.gz
    ├── 1e238c376f6ea00a545587650bba3d98c99b1ed1.nq.gz
    ├── 1e4bc5a0ba408a30e8d701e17696248a3126d0db.nq.gz
    ├── 1e8897ed74758747b5210d27d0454e4d108c7a22.nq.gz
    ├── 1f5630338a4d48dac5cdf2b605283de9a9aa5d56.nq.gz
    ├── 1fbeedec96ab15e935bceec58c81e305a95b92d0.nq.gz
    ├── 1ff09e5c8d20a1f9f56e8229bd4e19ee6bdda3b1.nq.gz
    ├── 202891676b51fcda65072a310eb4dab182c5efc3.nq.gz
    ├── 214d8f5442e53775a46290cd11f03204fb24608b.nq.gz
    ├── 2171efab7347ef56b6b5b72b0b011489ea0bd966.nq.gz
    ├── 21783e9d4284c27fc250517a9786d2d683526d1e.nq.gz
    ├── 226c2e6a5c62f9929098b65d3d44f2505f28e5c9.nq.gz
    ├── 228660f2c06ebae19b2833f869fafd0ac5c90e87.nq.gz
    ├── 22a12f050e0d64184a8f3b41fbfee347017c10b7.nq.gz
    ├── 239253021f179292aff61e122e8341a3a5fdcbea.nq.gz
    ├── 2462641637f65aa0eb51160e7680103a476d0644.nq.gz
    ├── 24b11e82f36e77211ac805df2423892da6b323aa.nq.gz
    ├── 253de828de930c28b2c2d89cd3db38fb8c308bcc.nq.gz
    ├── 261774a8279f1982ee9f2081fcb5b1906d16344c.nq.gz
    ├── 26789a5331a28acdd1c2d0ede27931d282b1b176.nq.gz
    ├── 26d42a664df6e7e73a1930551fafeb8f1349bc22.nq.gz
    ├── 28ee97c62cdd3154e69a0cc1d598d62cd8e44072.nq.gz
    ├── 294802377f60e7adfd1cf6a573297e134b8fa7c6.nq.gz
    ├── 29deaf510c77fd8d9f172dfbc3c22b66e18aade5.nq.gz
    ├── 2a5655241667588b34aa58cbe15677921b60496f.nq.gz
    ├── 2a8dec35c3e1ff8c3b3456eb8fac67533e966de6.nq.gz
    ├── 2ba424666fadd15381beb81af57e0f01b70584d4.nq.gz
    ├── 2c763904645708b0510ce66e97aafdd0924802f7.nq.gz
    ├── 2ce181e8671df8e269c0e4a5f49547b7fd4a2129.nq.gz
    ├── 2d3dcce039429c092d4ae47a1d5e298487b2d2c0.nq.gz
    ├── 2d65a6ee439f25f7dff437ff0cdc5091947db2cf.nq.gz
    ├── 2dc0a034327a89196905d33b6202fee14c29a231.nq.gz
    ├── 2e976c8240765e856090976ecc43298c53b85677.nq.gz
    ├── 2eb3fb0e2b5e202264bb7f6973ce57e87317e123.nq.gz
    ├── 2ef2991a51c73d7f42015abd76dc94cc875cbe2a.nq.gz
    ├── 2f72266bd55e9e226555d10bab39d23d2e5f32d2.nq.gz
    ├── 2f740d1f76646a601a9bf66f297fdbce7078ce3e.nq.gz
    ├── 30726a8889c3d82d7c767962bb22a1ba8d153da1.nq.gz
    ├── 316f9923a131c07f53707e49e92ff87386366756.nq.gz
    ├── 319a80f0b165965b3d96645c400f492e9a495751.nq.gz
    ├── 326aa18c68da4e260bd289aa4baa979c7ef468e5.nq.gz
    ├── 32e4b2a527c5eab3d4bfe4358dfca2731cad0327.nq.gz
    ├── 330c22be58007e1a58802570f288f86e6e4f6f92.nq.gz
    ├── 34d8e1ebb065e67db1f079b6d6d57eb50fd334ec.nq.gz
    ├── 35d11e73156a09a64e94a295aa6be8f88c22963b.nq.gz
    ├── 36d2df9e89c2837877bcd9a42099b4728a5a68a2.nq.gz
    ├── 36dcb2a645e2bcdb1d1b296f5566dba441394c01.nq.gz
    ├── 36f214d709dae348fed72c3f88185255787a3f0e.nq.gz
    ├── 37ae6db3c6632c2f1c4530e79b58a7e281eb583e.nq.gz
    ├── 37f6072802784027f796e80da5f5470238e9dd63.nq.gz
    ├── 385071f65ee750d4bb092f8018f6bbfc6cea5721.nq.gz
    ├── 38576890000822d8f24212659e1a85edd8578b59.nq.gz
    ├── 3864f84c973fdbdfdcf3e73de4f7461fb9fc6d2d.nq.gz
    ├── 38ba5fecfa3b41c711e5052d846701a187a1c966.nq.gz
    ├── 38c704c148e67d726646a625a382721e85c56060.nq.gz
    ├── 391654b49bb38ab9d759650b7db743813aef4dbf.nq.gz
    ├── 395f1c5fe9c4f0a100673a70ee480295a8c9e215.nq.gz
    ├── 398fdfc83c143b2c22961ea16dab4c29a8d51f7c.nq.gz
    ├── 3a28ac129bd0475f597d9376440ca6d1bb9a8548.nq.gz
    ├── 3a5c351a474b2481a599f9441bcb00d1da6f8e1a.nq.gz
    ├── 3b62cad5bf477735024122eba88f6483c2922655.nq.gz
    ├── 3c60fd29e84681102d6f552516ab59650a957b78.nq.gz
    ├── 3c825256370baf2a09243c58a31d74fd257e2030.nq.gz
    ├── 3d1a65bc95017295a44e609647cf1eb9680408a3.nq.gz
    ├── 3f1af21bf55cbd294b283510570050fd3993afcf.nq.gz
    ├── 3f4884e41878d146fdecf9967103b053df7a953f.nq.gz
    ├── 403984ee73319c76e2681735c045275db60dce2d.nq.gz
    ├── 408712af01458e3c044847fca4712931829e70d6.nq.gz
    ├── 414a291613ce4c7256210d79bc6b2bd1d7bfd8bd.nq.gz
    ├── 414abdd47cc3ca574f2b289b4957f1744384e93f.nq.gz
    ├── 4187d4c68031d73863ee6245665689b8b2b07ea9.nq.gz
    ├── 4251f774672461ae31939220d037f1e0c5715067.nq.gz
    ├── 425b5616f45384e72e44b97738c5e15923243ffe.nq.gz
    ├── 43c5b4531752fbecde53bf61e9653a56cdfa3158.nq.gz
    ├── 43dba764912c610ae6ae3ef5fb0fccf28eab809f.nq.gz
    ├── 448d53446c9e74dfddd65105404f836a7f435fac.nq.gz
    ├── 44eded77d9a8e02e92cc7344872dcbaef1748b54.nq.gz
    ├── 44fef994d029d63318f468caf0ed8ac68b77bd18.nq.gz
    ├── 454ddfff1c565295e0ff3780b595b3878a0c7dc1.nq.gz
    ├── 455f4d7aed45e1272b330a2054eab17dbff9fd12.nq.gz
    ├── 456dad6971540e36e127461557f9d877f9900a31.nq.gz
    ├── 45813bf11255bab271e6c7d8d3787c8f0e535c75.nq.gz
    ├── 46573ebb9fd107a4c4608ac3bf2f36363abe7c32.nq.gz
    ├── 472d0d1ecd0731daf23acf29e50769eff2f8b5cd.nq.gz
    ├── 476a7e9e60ffc86a71bacf5b2781865e19cd68dc.nq.gz
    ├── 480d6648be89dd5c57e6e25aa0bb4ab9441c4dee.nq.gz
    ├── 4823294fb42d134ac293ed61ecabd37959091639.nq.gz
    ├── 492eae1e7b0e62e41c935ec421d23dd3d8542ce5.nq.gz
    ├── 493334086366ae12dfe24056e92113d0f0b81c78.nq.gz
    ├── 4961bd7993baebeecc942c0ef2fb8993d80406ce.nq.gz
    ├── 4b70abb65046b37308708da9f99db9006e161fa2.nq.gz
    ├── 4beec30d033f5a0682f489da01ff0d977f10e0b9.nq.gz
    ├── 4cbeefc8696c085cfd47f96df84bc488cec2ad43.nq.gz
    ├── 4d997d8adf15b65c7d0a3260283ee085618335a4.nq.gz
    ├── 4dec51e0c76a9d59fbc0f8feeb0cfe72ffeaaaf1.nq.gz
    ├── 4ebcc449e7aefa70a6f8b3f730c627168015d2de.nq.gz
    ├── 4f19560448dab39854fb7821ea14f54ba93ff802.nq.gz
    ├── 4fe7e5d7b156ddbee473f5a438f5520c37e97afe.nq.gz
    ├── 50bfe7f52b8c0609e52d3a73ac784551f47c9547.nq.gz
    ├── 5164e8c0c1412043b927278c71f2363dacfe3333.nq.gz
    ├── 523e7059801006ad45da2205c2f7531d002d2b56.nq.gz
    ├── 528f1ad138a731ab1114ea45da7d83f492a08018.nq.gz
    ├── 534a029d6df56a6c238ce7f622ae230a75dac0d2.nq.gz
    ├── 54214928ad3699a959ef3eb05374135fb0ade315.nq.gz
    ├── 54429adcd7247c92e5a5ceeee8d16a1e3e17916c.nq.gz
    ├── 54594007d6b86c3474213e3a40e8919762387658.nq.gz
    ├── 551804b083b3fa013cda3c35af96d8eec1c0e38d.nq.gz
    ├── 5560405876a9f4a8bb7e1ab28b7c39ff56878b7d.nq.gz
    ├── 558894ff20fd07237f6c0a5db60465d6921cefec.nq.gz
    ├── 55a3af1387231c727a666a20c8a06b6342a34b36.nq.gz
    ├── 55a6da34d3d8caa3d634200c93fcd2c9e021ed22.nq.gz
    ├── 55ea56b80260845f5f1c0e895aa50a196f6b11ec.nq.gz
    ├── 568bf117416ca586c5b59ba0d184fb8eca3b661c.nq.gz
    ├── 569033b1401b1c356efcda3d691819d423e0499e.nq.gz
    ├── 569652cf1cf944381eb305b68eca35a2f9044df6.nq.gz
    ├── 57e46e622e3e1210356a774b7ed567458e7f2e5f.nq.gz
    ├── 58182d05757a6dd8c1066cb01c38740c789b4d2c.nq.gz
    ├── 59bfd99af0fc4d5ab91fabf8e12f6e14bed9984d.nq.gz
    ├── 5ab7d6299e8ba5df0da49ac876e9a5b90709aa9e.nq.gz
    ├── 5cb2373ef3ffceaf7578f4c13997d075142bf55e.nq.gz
    ├── 5e0585391669924d49dbf5f0917fe77501072318.nq.gz
    ├── 5e1ca4a9dc71bfc7bd58a89c1d76d6ac577c6d31.nq.gz
    ├── 5e944d59dac14c7178b648f7fedfaf2de081ab5e.nq.gz
    ├── 5ea67d5ba014dbecdeb0cfa485253c507f52ec17.nq.gz
    ├── 5eaabfd328ce035eb7ba0f22673eb7bedaad8965.nq.gz
    ├── 5f27346ca181a61ec6dd41cc6137323fe145699e.nq.gz
    ├── 5f391ff957d5a4359c5a169e1c127e992654afa1.nq.gz
    ├── 5fb60228db02ce227e0505daee20eade46f4e0f6.nq.gz
    ├── 61b3375c0d20e14cd2929b7c0e9065447d4a840c.nq.gz
    ├── 622ffc8169dfe23a579442f307c25191ace56f62.nq.gz
    ├── 62dee6933574c511dd2fba90d030502652f5d0e3.nq.gz
    ├── 635242755b12c2f74473886552ac759a345c1a41.nq.gz
    ├── 6353a929512fa824c4813de6758a80982d8becab.nq.gz
    ├── 64bcb628fc7515dddfe5488eca4e2fd85963ae09.nq.gz
    ├── 6592d9fc0beb0298371364e361c7379e89043d14.nq.gz
    ├── 65be6057f13ef012d320a47c2455dd4244a1020b.nq.gz
    ├── 65df2b924f2231956df01cbd2721394367fd2dbe.nq.gz
    ├── 667ae28e50a9d8b1f51931ac83454b35f0dac64e.nq.gz
    ├── 66ad4f684d0161ad24593a0a2e37534bd675310d.nq.gz
    └── 66f16d0ec8796db48e7515377f72dfc5b40bdef2.nq.gz

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

[zenml-io/zenml](https://github.com/zenml-io/zenml)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
