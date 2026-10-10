# Repolex Knowledge Graph of pola-rs/polars-cloud-client

RDF knowledge graph data for [pola-rs/polars-cloud-client](https://github.com/pola-rs/polars-cloud-client), parsed by [repolex](https://repolex.ai).

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
rlex download pola-rs/polars-cloud-client
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0ac61f7239e05285164d1fa9779a1c96b30a5a86
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0ac61f7239e05285164d1fa9779a1c96b30a5a86
│           └── chunk-001.nq.gz
└── blob
    ├── 013521ac7e0548e550d4c78943d72359703c4a2c.nq.gz
    ├── 028e5d7c99915419312185bae9515b1eeff9a26c.nq.gz
    ├── 0364f37a64c9172656b9db0ca6853fa8749f6f00.nq.gz
    ├── 05738390641430c64695bb652c1c0638e75a7433.nq.gz
    ├── 0601d87d95c084c237572d1b7392a54954fa153a.nq.gz
    ├── 06fa848e7d89cce6bf8a1c92a465e8f77011f7ae.nq.gz
    ├── 07f65523b559768d090c061e263c2e5dbb3463a2.nq.gz
    ├── 086eec3b441a6c5243b803505278349643ce999b.nq.gz
    ├── 09c0248d3c6aa00582a2ae7cbb608739323ab59d.nq.gz
    ├── 0a8f2dd4af143e7ef6cea23087a605a187b1e927.nq.gz
    ├── 0b032aadc3618da100cb8ccaba05a817c9ec8fb1.nq.gz
    ├── 0b0356ce74a8f17c20249c47ada691f7d92ad812.nq.gz
    ├── 0c745fa5fc6a4fdbedeb96846963da7f8331fb3e.nq.gz
    ├── 0ccfaf6bdfd468ce0b3f63c25ad07ba3378cdb23.nq.gz
    ├── 0d00400f261bb272b662e596454acba556fc5a4f.nq.gz
    ├── 0e1859ceac7fbaf6f22d18681f631b2a32c73d56.nq.gz
    ├── 0e93fca5ae781995c59ebe32ecc1007be4ddb212.nq.gz
    ├── 0fdddf4be5fc392c34ababc09cc0e4d4d9364895.nq.gz
    ├── 10967163d6af69948c6fd17d9f7fae4703c92567.nq.gz
    ├── 116c7fd861a7687cfb91698a610942c5806a37ce.nq.gz
    ├── 132fbabc7b87d310a94ec4a148e9c76654b47ed8.nq.gz
    ├── 13e358058ff4f2946eaf200377dfd2efc7cfa5c8.nq.gz
    ├── 15cad92059b86563937f2e756b4f71dfe6c0a82b.nq.gz
    ├── 166220ef7feedfa6b30592143f3b681eb897315a.nq.gz
    ├── 1702160fe9f2642860ae2e29420807caba1f44d0.nq.gz
    ├── 18f87c81db1e581626db9e3e45a906e03e9048d7.nq.gz
    ├── 1c482f7fd0bac3b1d110edabd9a3d3953762a962.nq.gz
    ├── 1cd4a0643237854227c5c4d42b4e40d76faff8fe.nq.gz
    ├── 1f367dbe8d9b22167f7034a4c0e064b5cddc8a8f.nq.gz
    ├── 21ac21d9567f06243eb6d703673aabdf5fcc0cc8.nq.gz
    ├── 2218ef302549e38f3921063fd512a6d3c4f61cf0.nq.gz
    ├── 234fedd5eeafd3f18c2cb0e7051e53ad43adc8aa.nq.gz
    ├── 2466383534fbab54331b05405778c2f43bd7a202.nq.gz
    ├── 24f94a0a9280680ad14e888d07f49fcf79aec9e5.nq.gz
    ├── 25ea5c3a61969f3c81c4bcc8e08c8c0c5700b5e5.nq.gz
    ├── 2640fcb8f875669cabe11777c9a1475189179e78.nq.gz
    ├── 26ff5ce56f260ead83728a3a6b5d72e1810e9ef8.nq.gz
    ├── 27fd231f9267fe91734ddc4015f9377abb2a3526.nq.gz
    ├── 2a8602133c124377095cf87c8da4de5c56f7e23b.nq.gz
    ├── 2badb611ef7903a149308425cfb67fdf01303983.nq.gz
    ├── 2c0fb0a348dcbd945934f3f90a28c2a2da5f0a28.nq.gz
    ├── 2c2569ca6cd27f49cce82de20db61c9984a5d88a.nq.gz
    ├── 2cdef8d6da6646c72f965fa1617d723b7c734b6d.nq.gz
    ├── 2d2fa679cdd5f256a83fd7aec05d6cdb78e89a12.nq.gz
    ├── 2e2dce03fa3e109a95e8e21502f9ebc30229be4f.nq.gz
    ├── 2ed0952a465f5125dfdc961cfe4037db7237f6db.nq.gz
    ├── 2f831a8e9243b6dd6dddf0f2b5aef04bf594b90a.nq.gz
    ├── 2f9ecb2c5a2260ac23f351e5983f75910454552a.nq.gz
    ├── 2fb1dfbf86598878fa847c7dd6f23c942d3ce7f1.nq.gz
    ├── 31b35f2672ea8c30cfcc10042fae39c543a5a158.nq.gz
    ├── 31d96fb70a21cd5c19a63712411a274202df462a.nq.gz
    ├── 336c9eafc14efca065ce949f8cb74f872ea7fbdd.nq.gz
    ├── 35a220c8cf04c0135066d5b4213cc50cf057fb6a.nq.gz
    ├── 36259d7a3c2522f984153fd7f8f9a1e16eab3f65.nq.gz
    ├── 38429fb027e1ed376d41704308d71d749b08a826.nq.gz
    ├── 395bb89a613ceeee5dc3cc29f325146aef0d750e.nq.gz
    ├── 39c07023cc6e9d08df0024213ca2bc8be89dc504.nq.gz
    ├── 39da55d5d1217eabcb7241348281ae58a37be49f.nq.gz
    ├── 3b95a133a57ac6a705aadd693aef95f7636e8c91.nq.gz
    ├── 3caf0f77e652d4608375fc04c0278377370c39b9.nq.gz
    ├── 40e1ad207192ae4e2abbf27e76b39442eef24a11.nq.gz
    ├── 423085e86fd5371a1619934fb7270cd69993cf37.nq.gz
    ├── 425c643fd24236532efa9a2e2d8e9e2f7f55b649.nq.gz
    ├── 440b662ba071d4367c71e60db6221f4c04441efe.nq.gz
    ├── 44b80af6102aa8f07ed25e2c316a6d53b57c2af9.nq.gz
    ├── 4655e3be7fa2b2ac4148f33545e9e0657e4735c7.nq.gz
    ├── 479a240e71913cfc72a664f04ba056d59e0e0936.nq.gz
    ├── 4898f0a0c7f1f0337fd6a607bb68bd0294f14368.nq.gz
    ├── 489f7e820053cc6c8a17b1134fce3c37f939a2d9.nq.gz
    ├── 48c3f7d25c1330d8db125cd3197172d150ccd015.nq.gz
    ├── 4c704e3c38ebe197616f5240851f350e3c180309.nq.gz
    ├── 4dca6eb29f47cb895c26052041d6c6199cc35f27.nq.gz
    ├── 4f49a7ee914a706bd44c0a9c547d3f4e6e1c5cf3.nq.gz
    ├── 4f76ee130595f160eeefddc3c690c37a929aab09.nq.gz
    ├── 4fd2627d89dfa6fb61943b6d72960fd0c84ae0a0.nq.gz
    ├── 4fe2a35a69a55a54e106f05e6e89efe8c9429f6e.nq.gz
    ├── 51106a3375baf247d2456b360f3186224a8b58f9.nq.gz
    ├── 51976583651d1e03e9c9be8451f6164ef40042bb.nq.gz
    ├── 52b9d80f82a932c2304ef9202a0a8f1a3513bee9.nq.gz
    ├── 5399943697ea7bace62d62c02c9675835463a1bb.nq.gz
    ├── 5565a802cd53a7c9e61b057ac4dc9808d7f13d42.nq.gz
    ├── 557511fddb905c40dad9e4a6d447d790cc4a1bc9.nq.gz
    ├── 589185b999ca70c839b993255226dd43506d4f71.nq.gz
    ├── 59104c2d327b360ffa0f2d9daed04806d3c83ab3.nq.gz
    ├── 598680cbbe719cb0dccc7205b57396c029957ab3.nq.gz
    ├── 59c4548104ebfd5d581499636dcaeb77225dd74e.nq.gz
    ├── 5a2a4e882d20b7c5735644431d8d30a86392b7fe.nq.gz
    ├── 5b810bfd0d9a0e1c2240ccb9f5fccecf4df925e5.nq.gz
    ├── 5b846c806bd317fed7976f95a57504254377e4ec.nq.gz
    ├── 5cffa8bf31360ef6994312e32fe6c73a02201d0e.nq.gz
    ├── 5d264734f3c385c344bd2761df829b11a2d8d0b2.nq.gz
    ├── 5d65f044223408a4deb1bdbb8c2015a85f53949e.nq.gz
    ├── 5e886e927f0cfb94a808946067d25d5f48d6a8bb.nq.gz
    ├── 61d42204c3bcad32b35eb2b96729d4a476922eff.nq.gz
    ├── 62eb11f3dac2eda008f06b7034cf00378d7ab6f8.nq.gz
    ├── 63335a92c878d3aad1438ed6b6990913659c6d31.nq.gz
    ├── 63508ee1ca09446baca08aebfe8785dd6d00e318.nq.gz
    ├── 69c2b69a51640e66f38c2936f25fa6a37beee17a.nq.gz
    ├── 6a0ae6d2cb0730e9ec0e03ab7f7c7fefa6ff162a.nq.gz
    ├── 6af7de9d15953d46d0ac1b6d829f266d23a2d184.nq.gz
    ├── 6bda9f28bf834f8b4f541c506b3efcfb99d865ee.nq.gz
    ├── 6c5d84ad5fcc1475b0028d7f215f5c300cfed103.nq.gz
    ├── 6caa989b356df010ac01329f746737528d3ed196.nq.gz
    ├── 6d5180b5702b40f8b39f26e53eff35e38e2c35c8.nq.gz
    ├── 6d5c5bbfbde21c3f7cb3c7405f2ebbf309c6a2e6.nq.gz
    ├── 6f45cc8607ca9f726a7000115fa993204187a532.nq.gz
    ├── 6f84dc78cd10b0d3ae8dd37503c80d8de32578c3.nq.gz
    ├── 7186bccb9270aa65caa8b48d4064f54c2b01ce63.nq.gz
    ├── 72e3f10bd63980b0fdd3cda14d8924f95af85c28.nq.gz
    ├── 73bfb83236533f1771d235b3f2e182915445d3d2.nq.gz
    ├── 768b32788f7eb2cdc37264be0c7cfe7fdb0bd8ab.nq.gz
    ├── 768dabbcd75fed92d728672619566b7762c3bb3c.nq.gz
    ├── 772602ccf6ee8b7d0569a8e33e8819721fad5d99.nq.gz
    ├── 7a07e5b2bb1eb4daafac0617ad2f0d6988af2d1f.nq.gz
    ├── 7afe21b519e4df97254b10d59ac01f0fc8f9f50b.nq.gz
    ├── 7b080d8227aa10fdc21535b34cae7f58f5677e1b.nq.gz
    ├── 7b22297fc45078e428cd978860a5ec139b2bd582.nq.gz
    ├── 7b729fbfc32854483d8d9a234896c977fb4cccbc.nq.gz
    ├── 7c7b671cfd78da909a452259b70bc444e0c48567.nq.gz
    ├── 7d0bd9d012a8e94656c7ab7623f01374e6d33dc9.nq.gz
    ├── 7e08dc4217b5be2ed1ab70a096e1b0c4eeb13cd7.nq.gz
    ├── 7eeecb7a27c5db38b3c69f91d9a3696263b8f037.nq.gz
    ├── 82b93ca39b06b17eb361816d22889f9f93b51802.nq.gz
    ├── 831e8272ec4b013324b2507d180c8962c151a157.nq.gz
    ├── 833ef405acf8a087011c352d4637249f0f3e5671.nq.gz
    ├── 861f50914c157fd7c2f316e3f2519b7af2cbcf99.nq.gz
    ├── 86704d351a48633ad33fe44ebfe9db15e2862541.nq.gz
    ├── 870404919477d3bd78673e43bef94f54f4f26a2c.nq.gz
    ├── 8711fab5fa587c30f47ddc71685f97b77c80d309.nq.gz
    ├── 87fc9e41271910d347ce477e43448e1423af8f9e.nq.gz
    ├── 8a64716b082887e7eb2cf7ef6f4980eb566aee69.nq.gz
    ├── 8b44fd913661cdb0ac73683ed8b471035e04dbca.nq.gz
    ├── 8c4dcdb4c929ea105fb05769ce2e9cd2c651d303.nq.gz
    ├── 8cbc5f3b88faba8104d218823cfaf75d72a893d9.nq.gz
    ├── 8d9f9fcf7195fe037b8be678059d7a74ebb7e483.nq.gz
    ├── 8e2cbf24ae243c8559bf17683373c263013bb4a6.nq.gz
    ├── 8e75f582304c9a6dbc9ea4d359b191e039006d0e.nq.gz
    ├── 8f86839147116a96f77438b465f540c0de0ec05d.nq.gz
    ├── 91968360e33ae436f59eea0e8a3ddf3ec5998a79.nq.gz
    ├── 927dced7ee84df38f8c97a7bee5ae0427a68e2b8.nq.gz
    ├── 93e79b65f9ab9c4c2586e2a38eae9e5ff12d0382.nq.gz
    ├── 9516dda905e89dda3b5da5ec47f48f88a5515e99.nq.gz
    ├── 966f1a86d21efa903f81c8b1549875ebed2e5f0e.nq.gz
    ├── 97561e79342836723c3c0a623fdc055d2e87ad33.nq.gz
    ├── 9847877a86db45702e9e9ff137017c39c37e5735.nq.gz
    ├── 984d02ec52e08210ed2fe666533b99376e1d9758.nq.gz
    ├── 993c32e4825694f672cd0aaba57ab284640fe282.nq.gz
    ├── 9bcf697b3732cdf7c04e307c02719e08ea54e858.nq.gz
    ├── 9cadd620fe7e49f9f3a9f9b68f2945d7014cf7e2.nq.gz
    ├── 9d3a21443e1bae868dd3c56d129cabdafb3098bd.nq.gz
    ├── 9d4588205216790d19da7000b5c36eb14d7aba07.nq.gz
    ├── 9e387ad9dcdd7b28fe10645bb6705c58036bc460.nq.gz
    ├── a0b18ca57d57039e7e81921237ec57161e798c31.nq.gz
    ├── a1ee0efdb8c3e8791f36ac8ce335a31dd3b6125a.nq.gz
    ├── a39f0ec7cda51d9addb03d9f76dd9f8b4eb1f1e7.nq.gz
    ├── a4038e0fc28b6884f78ffcd174cfea73703917c5.nq.gz
    ├── a45329a3af4f86e62a6278a100094776b21d09ee.nq.gz
    ├── a5d763fa24bceef1139c6346873116b7788637bc.nq.gz
    ├── a74bc9cc4d84de19182b26218897d2b1887d0d63.nq.gz
    ├── a7d08be0ea9134d074300d47442b780f611d0156.nq.gz
    ├── a98ac62b59ae8971ebd6310748dd474177fe69a7.nq.gz
    ├── aaea02fdc43f33028cda0cc016e624d0aa915f22.nq.gz
    ├── ada1f0d059398d1113709e3b26578ad0a5ef7870.nq.gz
    ├── afa1602ffe66bda5af472759c553a2c684975bf3.nq.gz
    ├── b0047187442a27de6eaf90f43cfd9cec1c5025ab.nq.gz
    ├── b12773fdef50685d347e56d300aa235364cdcea5.nq.gz
    ├── b44083eab111f24452badbb32106d4e0ab96d3a0.nq.gz
    ├── b44671f15df46c43b54ad7ea901328972052ba91.nq.gz
    ├── b48d43617ae8253fad2700f61e75ab278c397ecd.nq.gz
    ├── b55993937957b79772f02de82b42e53ce0ffe18e.nq.gz
    ├── b5ac0d6b615b7fc71da53b3364d23b865a43cdee.nq.gz
    ├── b5cde014783e3290696dce6b19696861e1d7fd26.nq.gz
    ├── b63bf0f59b59bad4fd224997d15c6c839aaa416b.nq.gz
    ├── b68bd8c311de96d23e744d3a4ca35affae7dd24e.nq.gz
    ├── b79ab6d6d6a21df209e2a6da792b26c009d00350.nq.gz
    ├── b8662e55d8e86224c7d82e97866b43f3baef5c07.nq.gz
    ├── bacab00aace8f5d1b97ee6bcf2563310a4bd9508.nq.gz
    ├── bb4d2b9a1c7c9a3c46cd484a7592d11fdab40e18.nq.gz
    ├── bb5e901107c26af12ef0ebf78d009418caeb03bf.nq.gz
    ├── bbbe29d4eaf8c7c2500759f9d1f5ef65d1a55220.nq.gz
    ├── bc0ffd41f21021609e15fc6cf7e6d627781d36d9.nq.gz
    ├── bec6acc59aecf8fa4b7c24677e507b2dda747933.nq.gz
    ├── beeb1e769553a8e059e9e38d53ca1aab908ebc4f.nq.gz
    ├── bfead518ede8dfc5bba2d0ad0115e9d230c49a6f.nq.gz
    ├── c2ed1886b217ec1f9203c7d1f02207934e0bc829.nq.gz
    ├── c594067b8fcee937ba705c29bd12bca5facefd0d.nq.gz
    ├── c654ca7282874052299730104970a5f91546f368.nq.gz
    ├── c74861a96af1e92b483adbc5c6296a6e372310fa.nq.gz
    ├── c75ecec72a22aedb6697c4b6f8ef8b8e69898d07.nq.gz
    ├── c923f327826c3f94039b3796ad48b13dfb2b8aaf.nq.gz
    ├── c9420a3833acf627cf3aaa4e12dd54f877a14599.nq.gz
    ├── c9daa751c009f42f6e1991d791f488b2c6643952.nq.gz
    ├── c9f32f3643c93c68ec9436e056129452e9be8636.nq.gz
    ├── ccb8f702c5828970d0d6e808e8ef165bad4426cf.nq.gz
    ├── d0c0cd3daac99ca3dac796edac22927d874a5712.nq.gz
    ├── d0febedb56841667d6f1e62236719e1042b699ed.nq.gz
    ├── d13653fe3a199344e50e7696669cb4c039391099.nq.gz
    └── d2e4d9a21576a59433fd6212613b947c7a850f2d.nq.gz

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

[pola-rs/polars-cloud-client](https://github.com/pola-rs/polars-cloud-client)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
