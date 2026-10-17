# Repolex Knowledge Graph of MilesCranmer/PySR

RDF knowledge graph data for [MilesCranmer/PySR](https://github.com/MilesCranmer/PySR), parsed by [repolex](https://repolex.ai).

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
rlex download MilesCranmer/PySR
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1fd411441da9e66a10b9a88f9de92f6a91d1361b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1fd411441da9e66a10b9a88f9de92f6a91d1361b
│           └── chunk-001.nq.gz
├── blob
│   ├── 0223b98bcc92c9bf0ffc6efc2f6054777be1944a.nq.gz
│   ├── 03544064625fa5b8815ed0dfe9fb53edeb1aeed5.nq.gz
│   ├── 06ab2e95dae9502da8f4d5b54a6665cd6f08f158.nq.gz
│   ├── 08d44d766a45d5a2f729b03de1d245f4f82a521f.nq.gz
│   ├── 0b25a76a75f45ad384095ef03522921d4ca269bf.nq.gz
│   ├── 0e8714129084ca834767239ecdf9338ac8240b6a.nq.gz
│   ├── 0f240d73a90079f9e749e4254af8d6d930683873.nq.gz
│   ├── 10de46c997adc2bb90f7f366cb5baf65c4e68899.nq.gz
│   ├── 156c66f27c5e419bbe0e7dbc9625d94ef874b386.nq.gz
│   ├── 162d20c2a1642634483c64523dcdae4c5f6d68cd.nq.gz
│   ├── 1766b33c8ff19c72b22c3a169a64b77abe37df98.nq.gz
│   ├── 18090a78ea4197ce8b5e77fcdd681063754cbff5.nq.gz
│   ├── 187516d5dae69af6a30cbaa7565059c0173f77a4.nq.gz
│   ├── 1afd1e720d1034b2e80b385b030b6f97e33be46f.nq.gz
│   ├── 1c6592b6bb6b218c3c34c37316ec6c65186be2fb.nq.gz
│   ├── 1e4fcb5e1590b733dda3bed3492de673f9eaf555.nq.gz
│   ├── 1e9d052d22512917de968e778b31efe871bd4eba.nq.gz
│   ├── 1f0791188919ccfa3576c61fb4bb13e02fad97ec.nq.gz
│   ├── 1f30cb9d28100b8552002b741cfca2d541cab848.nq.gz
│   ├── 1f6273b48000d942f05b16b0621567139781da0b.nq.gz
│   ├── 21ca31c167dd5899f64d8c3aa0c952ed0ba816ad.nq.gz
│   ├── 22fbdbe4017817135e4bdd1eeb0afb8393fb2a42.nq.gz
│   ├── 24126097676e06d97100bea699e65e7dd8f9d6ed.nq.gz
│   ├── 24294b61fb76006c4c43869d8dc83110e527ceb5.nq.gz
│   ├── 2679c013a9f73f311c88efeb86d7c27cb9d79201.nq.gz
│   ├── 2709f115255e318f33005accd8375f47c39ae196.nq.gz
│   ├── 278e30ed02cb72789eb1048f321dd93bfe1fd947.nq.gz
│   ├── 2ce9e19bb5996c74fee79dff4b305ebcbf6beae6.nq.gz
│   ├── 2d538f1138b1ddeddab6ea12175d9630171349f1.nq.gz
│   ├── 2d5cc6e6fab3ad8e0391b73c57c101dabf8c2564.nq.gz
│   ├── 2dc8a6b49d6cbbbf54f987e33483d4ca1ff615d4.nq.gz
│   ├── 2e25d7e86558c60365aa8f4653f28442a30bd151.nq.gz
│   ├── 2ea847568bf4e9c871284534c76566c39b012aa8.nq.gz
│   ├── 2f2fa51bb69f7d9a56e9dfcb7e1ad6a89fb1cf03.nq.gz
│   ├── 2fd92828a7345deb29b0b950ee9c95c94803b2ef.nq.gz
│   ├── 30f7afa6be4a0c8d431eb3685f17fdaad0226d81.nq.gz
│   ├── 34f4e7d856470165d6d9d615f0d5cd40714ad6e2.nq.gz
│   ├── 3590808bc55b201507c8d83e6d94d68eddee252c.nq.gz
│   ├── 3603a0102d6feb374c3f514724c4fd0ad6a75e9f.nq.gz
│   ├── 367df0f79ce5df61012c25b4852bc9398e003d11.nq.gz
│   ├── 385fc64476d765cb2039f400d5f570e1fb0c5f87.nq.gz
│   ├── 3a5b49946ad3bd91681dd4536cde8bfa9c005c6a.nq.gz
│   ├── 3afb2de2501040fb1416e654fd936f0246bde75a.nq.gz
│   ├── 3dc4b68cbe4ba6460cf7d45224ffda7f6a806bbb.nq.gz
│   ├── 3e81c1f034da2905711c67d88fb409ccd634cb71.nq.gz
│   ├── 3e94931ce85e75cabe9cc36dbe2e5aeefadb3d5a.nq.gz
│   ├── 3fa3b743716675a774ffed469593391f41a563f2.nq.gz
│   ├── 41769c2ac852060e1b0074ae7b591dbfffe325d2.nq.gz
│   ├── 43130b842729f45d07d8a18a48eb0bc472ecbe3c.nq.gz
│   ├── 439235373abf52694358e9a212a563c023adf65c.nq.gz
│   ├── 44cb81a7559c6940cba24a74236b2ae4a58bd2bd.nq.gz
│   ├── 48cc74fd5bec2b607f982cd82cc60c68092eef60.nq.gz
│   ├── 4a60801199f4f74f381466302c6c1d9219e5b603.nq.gz
│   ├── 4ca34f51c7c3b823d939da9ece948f51ffd9f2b7.nq.gz
│   ├── 53b679410c5ab79aa0f728a80911eb6f0b79263b.nq.gz
│   ├── 56295f2757af56b1e18e8b69f23f13c130dd55b0.nq.gz
│   ├── 57cc5052cb7cfd08e8753e7c5efc040decc1833b.nq.gz
│   ├── 587f9b41099fba43378aa772a7ef5c09b5a86d8a.nq.gz
│   ├── 5b380d4cdbde1334098722b0d481911be8076559.nq.gz
│   ├── 5ddbab1210907b7d64c5a0af1bed4c3597d16ae7.nq.gz
│   ├── 5fb5008e63d4c2dcfb0dae4062d463534a23ac54.nq.gz
│   ├── 6037d22d8bf2c02deb36bcf3e95a6bf915258d1e.nq.gz
│   ├── 60f7ce394bc2658f5bc9a4014a0c62d4a6b00732.nq.gz
│   ├── 616da86dec142d3f1a306176e2ea2285b359d201.nq.gz
│   ├── 6377049eee94256443180e22362fa31a5deb2047.nq.gz
│   ├── 64330f32d02054627d6b947686368fd512efbfa4.nq.gz
│   ├── 66c29ef310daf5643bcc454e7e2ca442cb4dd184.nq.gz
│   ├── 69498a47733d75d002a569639571dec86052a259.nq.gz
│   ├── 6bf9de2f7be06b612cbe82b4ce43fc8e7245b05c.nq.gz
│   ├── 6ed9c80128dfb04bf867b99ecb2d2f650df3ebed.nq.gz
│   ├── 70cd1b93c8f6761f5a87b1b923c51827bf5c3128.nq.gz
│   ├── 7335100bfc7978ddd060d3745f1a74511fa379d4.nq.gz
│   ├── 73f5c6468e2e62f2e0d04c1df2f89b904da7d598.nq.gz
│   ├── 754cf5389faa5d15c2f9d714bc6482670a95bc9f.nq.gz
│   ├── 75c2d432e6dbd48ff1998f7fffc4478e8ad5b53f.nq.gz
│   ├── 797e7401871b51701d35682b364a8698505b0476.nq.gz
│   ├── 7c346434dcba3f4d459a71228020e5e83e2e1f4e.nq.gz
│   ├── 7de145bd8aaf376ef624abdc6d66e2e215d8e05c.nq.gz
│   ├── 8099e8b238f69eef504d486e0d21ed498579f295.nq.gz
│   ├── 821d7e6352e3d7bd81a76d6648fdca7df31d93ad.nq.gz
│   ├── 82e9d9b5090c7ed0fe2be5fe3fd8f0d9c513ca40.nq.gz
│   ├── 83144783b694f32f4f027b3c143b3e267ebee856.nq.gz
│   ├── 84228668f330e19d3aec6548a354b72a0c524294.nq.gz
│   ├── 850edc5453ee544074a2bbe5b714ae2d92bd3c91.nq.gz
│   ├── 875041cfdbe93ae4f7d7580793329ef2aff68628.nq.gz
│   ├── 87f658b44713edab248c21e02afde419b2dc29f7.nq.gz
│   ├── 886bd939d0910cc4ca8b710910b48f0000ef8953.nq.gz
│   ├── 8905f28238b773349952545d81cf1b50a7623e1f.nq.gz
│   ├── 8a1f5cb36f276f7cfacdfb146f1007e9fa6d8917.nq.gz
│   ├── 8d3072fbf85e04cb0a6b83470bbd8c24bb1020f7.nq.gz
│   ├── 8db9047e24c5ac76e166cb26cc96ea9c8a7d7740.nq.gz
│   ├── 914d0218877421b41a4fce156b3d71d623ef2bdb.nq.gz
│   ├── 91e70c668efcb65d245a3cc74f8618bd4bf48691.nq.gz
│   ├── 934e5cf8827a9d6b3a44f56c08a7ffb65f63db4a.nq.gz
│   ├── 939f7cb43057dd55ba7753983af61e5af3c0ce22.nq.gz
│   ├── 95f13e105f6e6d96be9e8bb4c52689d1d5c8981f.nq.gz
│   ├── 97af96b8fe4cba91b12692b28d981804f24606ad.nq.gz
│   ├── 98527864664d32f798edc06a53131e8d5a068295.nq.gz
│   ├── 9874e0880970ffb8aec2ff7d340a15c18b5b071a.nq.gz
│   ├── 9a0686d42bb225256fdb0215a224a3620c109756.nq.gz
│   ├── 9a2f133a6790315e0ea4b39e3ce363cc61cdc6b0.nq.gz
│   ├── 9badcb607190cf39d7dcc274656ef88955e36758.nq.gz
│   ├── 9e5bbb1c83b114c958c6589b2c9ed5b830a34625.nq.gz
│   ├── a0ec7604defe247a80fe60e06762747403aa69b6.nq.gz
│   ├── a1842ebf86b82305efed6891cb11bbabc868be71.nq.gz
│   ├── a266bc7fdfebafbd0dd6d681f260ffec0ea7fdd0.nq.gz
│   ├── a362035cba51ef616e375c6f14a2f1435aeda624.nq.gz
│   ├── a4c431c3ee29f2de7936bfc398c58d9dedc7e5b5.nq.gz
│   ├── a6eb41354e6ff946c213c398d35dbf9e9344626b.nq.gz
│   ├── a829e84b10266379999b4dd51f210b7273bfbfc8.nq.gz
│   ├── a9d9e674a8cb8cececf9324de04149bb5ce0427c.nq.gz
│   ├── aada700f5907afb651e32bd4cf8a4511f896957f.nq.gz
│   ├── ac4f6b2995757ae8c27b352793e18e306ce92815.nq.gz
│   ├── ad34a98b1ac8b256d21663dbf77a3471cc1b66e5.nq.gz
│   ├── ad625b0aa1590bb6d84faa3ad7d54c2725d0710d.nq.gz
│   ├── ade737c9771b95d9fdb78bd1d0fc90bef97c90d6.nq.gz
│   ├── ae6d0261df071b2846d4e06c8306566894ebde41.nq.gz
│   ├── af287ae599e38661435f5a3ea0e71421cbc985bf.nq.gz
│   ├── af8a68550dce0ea22164a27358bbd815a08c9d95.nq.gz
│   ├── b037dbf104fadd31d66bde30a5f424682de3cf60.nq.gz
│   ├── b16caaf84894a116116249391e0a1f3dd4cca2f1.nq.gz
│   ├── b5466ad53432a4c57f8f24ed24bffe659180a6b0.nq.gz
│   ├── b6cf4d755088e1132b66e9564c9b8fb1ddcfe49d.nq.gz
│   ├── b72225b85d175ecb295d586fc2c190518549d542.nq.gz
│   ├── b732af2697b8f52c83ab36dbb9a6a30b5ef8faaf.nq.gz
│   ├── b7474018e4d4135720dd3b841ccc57f5aaa8214d.nq.gz
│   ├── b7b757aa05d63c2fd6dc77c3ea2f37fe8ef1f978.nq.gz
│   ├── b8a5221c064aba5a16f75ace1ae86422b5ea5ea3.nq.gz
│   ├── ba1cdba342fff95a57df0da10a3ba5fa4ca9c10d.nq.gz
│   ├── bb49de6be7548a568fb435544c77f2bb3ac99e6a.nq.gz
│   ├── bc4607f789d14a5827c5803c09fc73dc15795e80.nq.gz
│   ├── be1f161359a213a9a11bb7dc785cf437f3193328.nq.gz
│   ├── be26f217ca4d95662f595b9e19ae9d5fb870534b.nq.gz
│   ├── c12491ebfa14f46ca758a1f428cf78a45dc0ddcd.nq.gz
│   ├── c39cab9cc4bc8a0ec7ff2f274c68c5d2b43c8922.nq.gz
│   ├── c3ef9dbdde42aec097631b0410a49f196ae0cf0d.nq.gz
│   ├── c4d161d00b67986cde30f2b10080dd9e817c50c8.nq.gz
│   ├── c4da64105f85edd3f929a2de5cc418b45ecde44e.nq.gz
│   ├── c515d6b65cdd6fb8f9d26df6cc631d93beef0a90.nq.gz
│   ├── c6783498575945643694e42dab32b7422240623c.nq.gz
│   ├── c7902dffd5b593d07ee893c396332da6fa20008d.nq.gz
│   ├── caabeb6ab04e781509c5be1daef5a0b56f2ef29e.nq.gz
│   ├── cb609e330e6fa20176c1d7dcbaa7c6bd5f0f3ce3.nq.gz
│   ├── cc8ad8194ec79362cbb8c3837be13ef3ccdd8a2d.nq.gz
│   ├── cd1d9b4ad899a5985a3bbcb9fd12041601823b7f.nq.gz
│   ├── cdd82b785f74d6868be706d7f5d4a4e94c3d9eba.nq.gz
│   ├── ce9675900726132c8de8faefc0f49199cbd3e1a7.nq.gz
│   ├── cef838089a135d1e95a687adef3a2a5c9e5ca695.nq.gz
│   ├── d46b06535d30d0644589dc8a5191893c454f0ac4.nq.gz
│   ├── d6a26a31d743525f6335c09486876ce0ff884f97.nq.gz
│   ├── d9afca052c44ece1983a64a6273b5eea87b0ae0c.nq.gz
│   ├── dbf06853523541c123f49d6c42e2b245e6c970f7.nq.gz
│   ├── df6abef0537d9148d7961a1f46df74aaa67530d4.nq.gz
│   ├── dfdcd16563fae448cf3d3c14236a9ec583da0170.nq.gz
│   ├── e17339e3d7cc1cce23e082596c0294a0944bb784.nq.gz
│   ├── e196f3c4243118f128bcdf75aac87883a203e8ef.nq.gz
│   ├── e352e62a844e372357408e1e8f4de4e8cd4b5660.nq.gz
│   ├── e46f0cb7f07368521c5c2ca9d329bf98311e7a26.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e757a89a234be552dd8c9f3d435ad0223f028069.nq.gz
│   ├── e8100c42e8dc622ff04ec73ca49841e91fe4b77e.nq.gz
│   ├── e9cd18200f1e851d0c61c66bc132f7b771ccb1b9.nq.gz
│   ├── eae0679a8615028041d3038f9ccbe0771377941f.nq.gz
│   ├── ec1c395bfc21ddc272efd2fb35691a8342433756.nq.gz
│   ├── ec2d719ec045bf041209b24363311c4cbbbef577.nq.gz
│   ├── ec847881705c56959ef6517bf6837e9028f4ff4b.nq.gz
│   ├── ec995d29be8dd17d293fae31cc0f888a1a9fdc89.nq.gz
│   ├── ecf1094b4f34991766ca20f1d5437841a3033fbc.nq.gz
│   ├── edaa2c0415d71430707872b9e602c3d95a24ec99.nq.gz
│   ├── f00fc48adf2e57bf542f37546d07b243e65a10c1.nq.gz
│   ├── f01023a7f5e0087dbd31947597507de1f33564bd.nq.gz
│   ├── f1a06fbcae039ec2993ec1b27703881834fd0da1.nq.gz
│   ├── f264feaf211031f5ed6ea2c9629eb895e3e5464e.nq.gz
│   ├── f2750518af49180624912c8b4aa4bff48bfadde6.nq.gz
│   ├── f2b93382cca153b26060bb57d0387080ebd8dabd.nq.gz
│   ├── f48b915420c56533ba6cc8a81f6f8ba5353d2b7a.nq.gz
│   ├── f5d91773ee548cd287a1f55b5610d498ec7c8221.nq.gz
│   ├── f61469b21a4c41749b6e6617e3029372968c4151.nq.gz
│   ├── f7411d1df942df253b600082349fd334ec775368.nq.gz
│   ├── f94de0e245adeccc664bccbeabcf23008ffdbebc.nq.gz
│   ├── fbf17468b352637f8ec395212d190025207b4bf7.nq.gz
│   ├── fd764a7324a2cca3f8d0f750a9de709d6d7d7443.nq.gz
│   ├── feac9fc6b3d4efe788a0ff7aa454751b2ae63f9d.nq.gz
│   └── ffb3b99cb3337cc0517dde485efa6737f30887fa.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1fd411441da9e66a10b9a88f9de92f6a91d1361b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 192 files
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

[MilesCranmer/PySR](https://github.com/MilesCranmer/PySR)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
