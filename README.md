# Repolex Knowledge Graph of scrapinghub/frontera

RDF knowledge graph data for [scrapinghub/frontera](https://github.com/scrapinghub/frontera), parsed by [repolex](https://repolex.ai).

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
rlex download scrapinghub/frontera
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c94beae2f438492139d24759729d0201779ccf1c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c94beae2f438492139d24759729d0201779ccf1c
│           └── chunk-001.nq.gz
└── blob
    ├── 001eef1a81ac7a07e8d193c2eddcbc59c7337abe.nq.gz
    ├── 006fd874a3c9d814416c0270f188a179b9c0413d.nq.gz
    ├── 01aa296ae5aeb61de21eb5a6168f19f0b435578d.nq.gz
    ├── 03f6c8988ad8f53b9c79ff5afef7baf21472a696.nq.gz
    ├── 04031ad9f198562b83b22be626a2dab9a52ff38f.nq.gz
    ├── 045ce72609c76162c96a53f751178876d6a46543.nq.gz
    ├── 065fab2fdd6dc09730dc31167c53b749b272fa89.nq.gz
    ├── 06afb1808cb5a1d0b083be824aae25fb9a390771.nq.gz
    ├── 06e68ddbe8706ef562f2e4f30052709df09c2646.nq.gz
    ├── 0736ab3531cb0754fb33ad00c8c9024127c82660.nq.gz
    ├── 07931e9ead051e607f9ec409245cfd83f7ddc92d.nq.gz
    ├── 08225ef11bbe6570583138da6159cbfa4cbf7f0e.nq.gz
    ├── 08bcd4d56431b44ba0df711318aabf9fa3c19294.nq.gz
    ├── 097034c9f28038efeb66660f0b832f0f7b8485e3.nq.gz
    ├── 0bb1bdc2d91988dba1cab02c0bf3885dc5e69066.nq.gz
    ├── 0c2da83d9d06bc4a25f5168b25343bc1149c5afd.nq.gz
    ├── 0ea37083fad65f3ec3b5c39e39fb0f776651da91.nq.gz
    ├── 0f3d7d468511353499b2faa7a67084182979f02d.nq.gz
    ├── 0fa21a8085b8a94019330f9a42331b4cf02106b7.nq.gz
    ├── 0fdd852441f6226535c31e1491303867cc11c917.nq.gz
    ├── 0fe9c76ce9fae8f2aa3942712c6162150f9a0dde.nq.gz
    ├── 10c75326d8523ee4c8b29a6cf57099fb4b4929ae.nq.gz
    ├── 10e0f093f1d71eb74892e4868df966839ed30288.nq.gz
    ├── 10e5d5b530fed12218dd71e6377b403f8195ca5a.nq.gz
    ├── 11bff20f3ac8803e8ff41eba2ceaf81bb1a6e447.nq.gz
    ├── 11db9d88945142650601f6b1bf77eddc0d5368f4.nq.gz
    ├── 139615dd2729ec62bdf40c3dcb3f008bba9d7281.nq.gz
    ├── 15630e290ec4d04bb9dfb1f157ef25c65c80053b.nq.gz
    ├── 160cf7a2d168b137f263ad6c7de8f138975c5756.nq.gz
    ├── 1685ace2ba7e91907d67e26d9b39ecf4da5f1390.nq.gz
    ├── 182ae958c8a21858781848a7c41528936e51ae8c.nq.gz
    ├── 187cdef6b802f793a1fbf76dad7f36af077c4de7.nq.gz
    ├── 18d79415566d7c19b30409e1fe7976dea92cb2e3.nq.gz
    ├── 1909fdf0a4e193462be97c74653e5372770abebd.nq.gz
    ├── 197e7f326a0a2ce6bbebb240853a2132c89f9a2b.nq.gz
    ├── 1addc6ca30cdee4ff53b2f514c4dac82221d62e5.nq.gz
    ├── 1db9ea99e345ee1a271e1ad1de9fb0c5ac15e34d.nq.gz
    ├── 1e1747193a526acceb8907f54ac32a4a5e12aa35.nq.gz
    ├── 1f8f3b3da247b4d7f0215614f18b897865ea83bd.nq.gz
    ├── 1f942ad986e0951401e1f90e0ed0bbea64c2e174.nq.gz
    ├── 20c511b2b466ae3ef37d40a6b7c9e49fe80ef7e3.nq.gz
    ├── 224a77957f5db48dfa25c8bb4a35f535202da203.nq.gz
    ├── 232869ffea079c0c8c8781d1c50eb49f32de2e6c.nq.gz
    ├── 233fc842d2f67bd07808f8de777661310f938215.nq.gz
    ├── 253855695461fa90fa3822926e86f284ea9f531f.nq.gz
    ├── 2777d44ce260ec40b1b380e11d04a6094c6c889a.nq.gz
    ├── 281c956909669a411f2ca97d189d27a7a2c65030.nq.gz
    ├── 283a98a69862dec9879dc66188d38439d9583e36.nq.gz
    ├── 29bd671e8d2c984de4418f9746d8a45cfcc6d8d4.nq.gz
    ├── 2c98229504c64aca194610ecf734a5c2c15d2677.nq.gz
    ├── 2cae44c462669b790594e4f1a997afbbe6f5d3af.nq.gz
    ├── 2e0cc644b7f28076e511f1c495f72695aea15b9c.nq.gz
    ├── 2f4d379333362557bffe3d5731c14562000b900f.nq.gz
    ├── 2ff390eb4305bf748f5460bf646278cdc4cf5334.nq.gz
    ├── 300e8fffc867862f633de30b0bf9729467b46dec.nq.gz
    ├── 3063e4f2280ee9dd5fae395ff930493dbf221642.nq.gz
    ├── 306b97736ac9a029f5f57ee770235c70809f83e4.nq.gz
    ├── 3266292f80f2842e55f03e5c66a37cf384d2a2f3.nq.gz
    ├── 33582fff3063ce1f469400b5fa2a91062ac2fbeb.nq.gz
    ├── 341cf11faf9a29504168de4e54beaad182c5adc5.nq.gz
    ├── 34eb733c89356296f19759962dd3f2acfa8221b6.nq.gz
    ├── 36bdf2b4a772d72d91bbdc5a4bfc337e2a71974b.nq.gz
    ├── 3736de4122cb3cb7d235bca4313a6cf3eb155618.nq.gz
    ├── 37c47b60e9ed246cddc25d57ef6c4492421ab5af.nq.gz
    ├── 3804dc18e57da9018de6a2097edace069e34dd8e.nq.gz
    ├── 3822b597d65b9f0abaabd67e24866ec487ecc2c3.nq.gz
    ├── 399f6425b9807d9620ab00c9de4088d91d1b9f32.nq.gz
    ├── 3bd9313e837b6f1a2434dbc4cc45a8c9a1d6f3cf.nq.gz
    ├── 3d3c1859a570b552e9ae9d09be101e58d38e8f66.nq.gz
    ├── 3d9114563cdbb40d46ca350e8255517cb9f43237.nq.gz
    ├── 3efe1f24c99cf263407a66c385e75ad2047e5d16.nq.gz
    ├── 4090d716cde628001cb713344a95de9625ae070c.nq.gz
    ├── 40a96afc6ff09d58a702b76e3f7dd412fe975e26.nq.gz
    ├── 418c16f56ab0d00e2a07721819713aa0b4f804d3.nq.gz
    ├── 41a4e8a9796c23653b1bde96d8825e16e444d710.nq.gz
    ├── 41cc362524b5108d5e46ca11e17c38478063ea23.nq.gz
    ├── 4213fe6b2d4be2debaf9004ce7b30a72cfde9786.nq.gz
    ├── 438c89730e0bbde5ad9ac18a8185ad9ef4308306.nq.gz
    ├── 43b5f83f96bd670e3143306023122a2d4ac8a195.nq.gz
    ├── 458e8e9c28eb68d0683cf9584f2d4f35acca8fcd.nq.gz
    ├── 46b676fff4d95beb8ff2fe7bb7d8189e3b82f97c.nq.gz
    ├── 4791adc3714e29841f4f6079b0f637348a3c5055.nq.gz
    ├── 47ad084c23d0d6d8a6d2334323f9ae8e66b1c881.nq.gz
    ├── 4840327f6293f2c49136a841c7d2565e32c3fc62.nq.gz
    ├── 48b90f75cee222941ceceabdce8933d36967a269.nq.gz
    ├── 4a0e18ee5724a84fd408fe4ad8b3e51813a88761.nq.gz
    ├── 4a490b6c8b50e79da456aeba24a7a7bfafe280d2.nq.gz
    ├── 4b204c5f2a657900bc6c8f1325b2622fc935cf65.nq.gz
    ├── 4b9aaea2769fcd076f64f916ffa5eaf6542026ec.nq.gz
    ├── 4c40587a0ff0a6dfa0d040706f4482b15ead9127.nq.gz
    ├── 4c9f71c01edb4fe642c0fda16bc97a27ef56ee2a.nq.gz
    ├── 4e530ddc976e552b262f446c5c9fbd7511f4493f.nq.gz
    ├── 4e926831bff73703465c47293590d8313bac21ee.nq.gz
    ├── 4f48a6fe4d9251f5f53d456cd6fcfc50121c5bdc.nq.gz
    ├── 4fa2ce8d510781625a5b599c542a65d0bc03e2e7.nq.gz
    ├── 50615c8fbafc89bd425a13a3da3da27ac897026b.nq.gz
    ├── 523296cd2aac09921ebefbbcbdc325626a662c9e.nq.gz
    ├── 54cda77ce43608bbdaaadd156731492b4d0bafb8.nq.gz
    ├── 54d192353b452fbc684f3bf4004a4504a80698cc.nq.gz
    ├── 577eda76de706a053f07216cb1f7f05d8a5ccc45.nq.gz
    ├── 57ff9b877e18a909d6f5d1862eae6d80ffccc0b5.nq.gz
    ├── 587a8c100be4f3ad104977561c64f7cff445664c.nq.gz
    ├── 5f52295ec05fd43b54a839205a441d17897eacb8.nq.gz
    ├── 5f77f8607d92b79f11204ce3bdbd2bf2fcf79ed4.nq.gz
    ├── 6057e174cec77f3576c9102eefd3ba761f79d046.nq.gz
    ├── 6321b15d4932dc1f275bc7465d34be90da54db40.nq.gz
    ├── 6a28bfff52ec83df04b6503402138d4318616e5a.nq.gz
    ├── 6ae57729eeb22a9da37850c332408a0d58f90e79.nq.gz
    ├── 6b98864df066a33d2d03fac1b86edb1f05b23988.nq.gz
    ├── 6dc862e92f65aaa56e5b14a2dc507a81f31229fc.nq.gz
    ├── 6e1e0d3ea2167233dbce2f0870f1741e6e8a11f4.nq.gz
    ├── 6f77f70a83b628b18e587aa445cca9a9471de024.nq.gz
    ├── 7069667e730868bec4d10a09b958cbff171f01a9.nq.gz
    ├── 710a9f7537f1189321a59435c1a557fcc5febe9a.nq.gz
    ├── 74c6a81322dfba83cf9dd68bb8c9c5c0f3210743.nq.gz
    ├── 7683dc00d12868d18b861159853e92f675a7ab70.nq.gz
    ├── 76bd8d9d9d9b98daba12569562df7a85c67f249a.nq.gz
    ├── 784f245a083a5cdb25478567a2f2b212ed26d203.nq.gz
    ├── 78f97747a3ddb180ebe77f7e263687a18d8664fc.nq.gz
    ├── 7905547e210a9749abfcfecbfaa314b9cea300f2.nq.gz
    ├── 7954957285f0eed5dd7b9c5878093d9db615637b.nq.gz
    ├── 796faecdb6a42a23b17907638ab29e4e9058037a.nq.gz
    ├── 7a2f58b330ea9599a65351f66eb46d880306a7cb.nq.gz
    ├── 7a5a125e61614a7e36d180c93da7e09fd75ca91c.nq.gz
    ├── 7c68785e9d0b64e1fe46403c4316a9fe1ea36eeb.nq.gz
    ├── 7c87a5ed0495c856b7372b022b63f0f8e3b905d8.nq.gz
    ├── 7c91a5fa1d262afda1a491d2ebfc7658ccdade65.nq.gz
    ├── 7ca830a21aec4d699e2c48d4421e86d981961f2d.nq.gz
    ├── 7dd107246caa8134a30ad298ed2b23dee11df8c5.nq.gz
    ├── 7e678a6078db12888b8d81f284feefa3c5cdcb4b.nq.gz
    ├── 80dd7a9be0b953dedbc9fce5f3b1418f22a7061c.nq.gz
    ├── 811822dcdafe72d6c4d30851e9bfd96b9bd4833a.nq.gz
    ├── 817f23472dcacfbe5c460f1fe4bb415dc1610af1.nq.gz
    ├── 837e16675f3da3be16e1c86fa4920c4350f341c8.nq.gz
    ├── 849a12be0c0173a68c3ad272a5fdc01d4e1ddd04.nq.gz
    ├── 8729e4ff712aa175a52ba8db0dc6c2baa4e38d4d.nq.gz
    ├── 8750b58d93fbaf9fd45a10375646af098966da86.nq.gz
    ├── 87a352357de003de02db1fa48f721355b632c457.nq.gz
    ├── 87ebb22379f45f339a0148d99e6456fa716505ba.nq.gz
    ├── 889601c941600d37d76c9d46062ca27288333808.nq.gz
    ├── 88e44026789a1ea0cd8b14d6fb36b0d651f9ec07.nq.gz
    ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
    ├── 8b37ef49057d4bb6626a8a846aa8da61952c1bc3.nq.gz
    ├── 8bdc5fd67c6e9d1cc5673924b0c3826147a76d12.nq.gz
    ├── 8be5fb0af3578e859528bdf75f40fb621b36d328.nq.gz
    ├── 8c29ca17f3ce8f88466d0ac4d1b7b07c4f80080a.nq.gz
    ├── 8c6f76d48e809dcd1e613978801238b2a9cc272e.nq.gz
    ├── 8c83b852b6061f948f6fcd98d7dfe9714f76e97f.nq.gz
    ├── 8e10593768ada712d9c6c629e1024749eaf39747.nq.gz
    ├── 8f6d0a81614863d3dc3a7de2e5a1d4fe1bf559eb.nq.gz
    ├── 8f81af1840328ef9fcd2e8a767a5448f330c1077.nq.gz
    ├── 8f9006bfb0d9053f372390e97fc45ca7db540699.nq.gz
    ├── 90479e819d3b5a2c41104c88ed68008947c4cd7d.nq.gz
    ├── 92784b51d9bbae3e4801ff9d2b627f4f63b3a935.nq.gz
    ├── 946724fd826df50b28bf2a8013ab831fc9931def.nq.gz
    ├── 94992506546a18d1d4b99c7707344c0c8adffd2a.nq.gz
    ├── 9516d8416227f90f102f017bbd99861369f4709e.nq.gz
    ├── 95478361e9c71ed9550a798e5fc1cfbd4591fb9a.nq.gz
    ├── 962ee8a367f483a0a40204888ac70c2601b5c7da.nq.gz
    ├── 975049fc483c7ac8aa1ace92b6d66285a9af9926.nq.gz
    ├── 97b4627df3bc47054066abbcc4c9ea70a5d86986.nq.gz
    ├── 982ace9240fb78fa5266776a1f33e764fda473e1.nq.gz
    ├── 98914e372cf46407264cd47d19c476ffefcac4ba.nq.gz
    ├── 9b46d2efee3b4b14ac660c14c719b1657d420a34.nq.gz
    ├── 9b4dc7f3de30890f5b1cf1fc9ae86c3c2d635b18.nq.gz
    ├── 9b5e0577a5beaae5b39c589a111954c62566d6f4.nq.gz
    ├── 9f0e77f07a589f4408a903a6e744d892a945d944.nq.gz
    ├── 9f43052510350a5ed1c4b9acd48c0390b0b59060.nq.gz
    ├── a040d07e696faa35cba0612847850646e7ef6f8f.nq.gz
    ├── a18462b4df862f28f0570a85898eea6a46dc8b07.nq.gz
    ├── a211d0890a96b84149b1e4e97ecb43f6f0d1f0b4.nq.gz
    ├── a2fceb2bca8e62a73ea43df4c06c8c09992e1fe9.nq.gz
    ├── a450d57b42a6391fb1f3c9ecc7299ef48092d0d5.nq.gz
    ├── a49935c1321984b4083ee9eb0eb19e30681fd5dd.nq.gz
    ├── a50d6970d4f932f36854cfdc2ca7925b0f61662f.nq.gz
    ├── a64697d04a44b0a91f3282797c8609ea829acc2e.nq.gz
    ├── a9f6870441be0aa8cdd63e3259c47f6b6d958736.nq.gz
    ├── aa69f3103ac37219d57dc7de38cc6459deed1e8a.nq.gz
    ├── ab2fa09eb0dc1262b6e430167d482844bf05aa0c.nq.gz
    ├── ac8e2ab0316c6d51168e900595753d867120ef05.nq.gz
    ├── aced204ab2d1020d433b76f83ebafc37267bfe12.nq.gz
    ├── ad15ac46920c532894cf2b120eb14cd9756637a7.nq.gz
    ├── af6f6d992ad45b206fbbdb35b52253793b0c9a16.nq.gz
    ├── b038000f6d3f15692869a5596407d9fd4a2ad9d5.nq.gz
    ├── b0e586f86d36e2766b35054e59676e3b2ee27e58.nq.gz
    ├── b319aba0d97f9fa4aadb6fc5d155c991c20fb534.nq.gz
    ├── b35a160f8a945e5c3e8409715562911994f76466.nq.gz
    ├── b3d720e5c8e51309e0c34ec9eb123fa96484c560.nq.gz
    ├── b491ebcb62baac797051c7c43f4ab365963a46d7.nq.gz
    ├── b5bc31c0ef5e6c54ce3abc0dd377cb4706997806.nq.gz
    ├── b6a03e74322a25054ce628205e0979f419be8223.nq.gz
    ├── b7d90613f6a377b672a333f55a4fade240ad0501.nq.gz
    ├── b7e6a31fde0238adcee3a528a47c3c7ddd69bc2c.nq.gz
    ├── b9cdf63c9bc607e0904ef1b769b8802efb4ddfd9.nq.gz
    ├── bbee17b1153d60133c1cf2c048499f5d21196d49.nq.gz
    ├── bc8a23430ad8c48bcbcea8a1b0c685811104393e.nq.gz
    ├── bd2a7b2daa892152f9df160bd54fa443f5a3c41f.nq.gz
    └── bea9fe690537193e2b26a7d743679177d29ef94c.nq.gz

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

[scrapinghub/frontera](https://github.com/scrapinghub/frontera)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
