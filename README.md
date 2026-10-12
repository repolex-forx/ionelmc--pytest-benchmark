# Repolex Knowledge Graph of ionelmc/pytest-benchmark

RDF knowledge graph data for [ionelmc/pytest-benchmark](https://github.com/ionelmc/pytest-benchmark), parsed by [repolex](https://repolex.ai).

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
rlex download ionelmc/pytest-benchmark
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 07d519672687402e6c3fac1a543fbefd810d1e5b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 07d519672687402e6c3fac1a543fbefd810d1e5b
│           └── chunk-001.nq.gz
├── blob
│   ├── 0066b77f570d9439d10b9d998bd15972271d9a52.nq.gz
│   ├── 00d7fefa53c52ca132ad5be5156a3640031c3ae6.nq.gz
│   ├── 01a2cac6aac5ecc391c3a9ca18dcb49eebe43ddf.nq.gz
│   ├── 06faa735d44127d0c587770037192277b1e7faaa.nq.gz
│   ├── 08936d99094e1b728f76a1a13bc81ce1cdbe0cb7.nq.gz
│   ├── 0a01bcfa84b7d80a8d7a27110e0b45d4653a5379.nq.gz
│   ├── 0b4a2e82691c0e4a3e991804b7d1d44123a35911.nq.gz
│   ├── 117f9fcc8abea0b451bb5bf30ad2ad70a320ef4a.nq.gz
│   ├── 12a64c487bb304c146622eb73f8411159cc582fb.nq.gz
│   ├── 1d5bcae1c0f4567551b7d4ae081682e2157ac8c1.nq.gz
│   ├── 1ec5dc24e6479a1983e2614d7fba9644b439868c.nq.gz
│   ├── 23ddb4737e9d1421c46e644bd3c93bec3ba8812b.nq.gz
│   ├── 26a1493d49c1ac0c3c4bb44c6d670e58db6f2f4a.nq.gz
│   ├── 29845a0c4028e0a7f76bd9e5b03a01a1ed5fd1f1.nq.gz
│   ├── 2b0268f683d851db22bf131a3579820feceec9b2.nq.gz
│   ├── 2f4272f70b7d7a319d6ea2857e20c6fa6a280dc6.nq.gz
│   ├── 364a6abf0145e74e5d6471d7f1a3ca7321e061ea.nq.gz
│   ├── 38797a00a71a77edea5f9703817cbe29fabd0f6a.nq.gz
│   ├── 3ce90bc9902a668e15cc1209554bf5bf42cc510f.nq.gz
│   ├── 3ebc03de0f9bf9d5aa2bdd71d19c15b66d09340c.nq.gz
│   ├── 3f93988ccb9bc9e7b9abec8c039620230e0eb6d5.nq.gz
│   ├── 46a143b1039551f873f575238b1f3b9b9a9849f0.nq.gz
│   ├── 478f484c5c8482ae077c96f3f28071f51cb95db0.nq.gz
│   ├── 481afe3599196603b6df3b5c478b9cf205631311.nq.gz
│   ├── 482a35ccc1bb5c980fc976627cf3a61bfed32224.nq.gz
│   ├── 48d8c7a90d0345ee03902eb7dc4c32dd07ef4ea0.nq.gz
│   ├── 49e39a8f77fd6d49094502737913e0a2235b5607.nq.gz
│   ├── 4d756f9fabda9e8d061bd7edcb7966e32db6d565.nq.gz
│   ├── 54eaba762a9ec1fb90715d2ff3f3d41e235fe625.nq.gz
│   ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
│   ├── 56e76d0a64912b401e77049da5402bcf6469fc06.nq.gz
│   ├── 574a29f453ec23662e8125c11f421384822d221d.nq.gz
│   ├── 5a381723c6b0083a85f4fd8f3f75bee4ef6ca934.nq.gz
│   ├── 616caf600f34f211fc0d6d85eb74a1339760c67e.nq.gz
│   ├── 6243871556cb034caadef95347596ae8827c813f.nq.gz
│   ├── 657e7974d096935793232f939234ae1e70dfddaa.nq.gz
│   ├── 66c77281252b0d4f923797a3102b43da19a807aa.nq.gz
│   ├── 66fbf2d2a7064980ec83ebd2ccc6c1901f905a4a.nq.gz
│   ├── 6748a33f1202969df85ebaeb225dbd91b2e6cc26.nq.gz
│   ├── 678cda424ddc999bc610bf9775a08732348a3e63.nq.gz
│   ├── 69530c4abc19565c731b7b20190204a810c810b7.nq.gz
│   ├── 6b57f6262925be45bd6b20e32242923c9d02185b.nq.gz
│   ├── 6cedc701a1e7e1e4bf143390aabd5931b77aab14.nq.gz
│   ├── 6d0c1ef9dcdffaff62a84197e9839aeb4c41ad22.nq.gz
│   ├── 6d2c10fbcc91b95c5023fb5421684ad3eecbc883.nq.gz
│   ├── 711be4c8c8a4b7956820a777657aa01cbec1e441.nq.gz
│   ├── 747294da3d0ee6fe6fdcbc1770a11dc56bf73961.nq.gz
│   ├── 75e8ed9f387672ddc61d8378bf6f72b6827efa35.nq.gz
│   ├── 76d7cd1d5b5994f99974841ee2b1832e7770abc7.nq.gz
│   ├── 775dce15b430696f4bb12391b8f66322cbad565a.nq.gz
│   ├── 77b8d3ee0c80ea63d57130400c85e17ef09c99d2.nq.gz
│   ├── 7ef495eb3cc289634624e0ad521db17e6c5d4631.nq.gz
│   ├── 801ccbdab87aab0aa3b7064af5e9eb50389752f4.nq.gz
│   ├── 84b7c6b52e858978a469a4882a0e0d03c2483096.nq.gz
│   ├── 86c98b9821e8fc5ba517d54fa3cd1ecfc77395d8.nq.gz
│   ├── 879b1140f803affdbeed4cfce85210b74db52bf2.nq.gz
│   ├── 8950de3b70e324e3212b61994c0ccd161ca71d61.nq.gz
│   ├── 8a7fa5012dfe8e6bf0e4bb65fbdcb7b6cdeafcaf.nq.gz
│   ├── 8a98992baef13275846eabb51e9bdd2b4b2b5d59.nq.gz
│   ├── 8b6e65f98da2658c15535826a5a09e64889041c5.nq.gz
│   ├── 8f0c8dddb71f614ade12600f602a199ae143c5a5.nq.gz
│   ├── 9171d378eadc186b7795b4d47b9d6bd501156c65.nq.gz
│   ├── 962ff0e8a86432c831ecdb4411c398c84a523a9c.nq.gz
│   ├── 9aafda524b51e6a14a9edf1363d9c02056dbdb5e.nq.gz
│   ├── 9b19dbb1c9d68b4d4ce29ae2f5ab3197c52a860f.nq.gz
│   ├── 9d609700fa2e88679390eb4f7a49ae5a1abbb3cb.nq.gz
│   ├── a1964e98f9d55cf408c1cbec81ad6d5892e94d51.nq.gz
│   ├── a22bb859813208465985a9365f385c523eaff466.nq.gz
│   ├── a2d480bb79405d1371da3c20e8fe0f3999995624.nq.gz
│   ├── a581a35278b19491a012c811068907e21b3540b3.nq.gz
│   ├── a5e0dd3c854ff5dfd82273612e04f6d9d0687120.nq.gz
│   ├── a6482e814c505146b3a0cc7463c6d4040fa64c6d.nq.gz
│   ├── a7734fe46ac7cf431e7c7d4527152a4ed96f60c5.nq.gz
│   ├── a81e1ab3797aeb7c16dee21491ecc8d1e8e9f917.nq.gz
│   ├── a8338acd4e1dc515ec4f0b7e2415d12a952b52b0.nq.gz
│   ├── ad82bbdb433fc8677d90c841a55151247e12dd6f.nq.gz
│   ├── aefa2e2fa9d9d69baea054718b550fea875db407.nq.gz
│   ├── b2980243e2f08ef352de3c228cbcf0ef598712f8.nq.gz
│   ├── b62d604756b7d74f3476f0d92dafe552450cf180.nq.gz
│   ├── b6ad5b149ece3ce59a7cf418ecb0361aa5ef0c86.nq.gz
│   ├── ba9d87125f24f827dce46a2ac1b15c45f8689e5a.nq.gz
│   ├── bb53662c2728ffaac7400689ef584df8756de203.nq.gz
│   ├── c03e307ab39cd6807b9bc0d8f404e716707c2533.nq.gz
│   ├── c179ff5d5cf00f23f5d1ca02eadfd1c87b0df53d.nq.gz
│   ├── c1a280731498687c7c31c989352de02af0ada697.nq.gz
│   ├── c3f5565936445b8f6fb5db92511b77b0e1dabb98.nq.gz
│   ├── c81b83f12eb7686619a306e1b33759bc34f75ab8.nq.gz
│   ├── cb4764fb685f8a350175f032c6ad45645c342208.nq.gz
│   ├── ccaa491335fa591baff9490c51e505849144d8ed.nq.gz
│   ├── d16bd3c9a63968b58be255b414dd496f654cfece.nq.gz
│   ├── d48e3bce6e46406bd5b21b21f87736ff245db403.nq.gz
│   ├── d4e79c0c8cb08aceb279b1f35c2343b8b6f6a4ca.nq.gz
│   ├── d85633ff37c1d8c58b55bd4dde93acbf3523eef8.nq.gz
│   ├── df91502e60bc0e64d7650040af412a82d9c3c13c.nq.gz
│   ├── e122f914a87b277e565fc9567af1a7545ec9872b.nq.gz
│   ├── e18c3b20d5d6502717584c2f2413dc005be532c7.nq.gz
│   ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7add11ff4b6cbaf61e6160d5135ce6e17361ed7.nq.gz
│   ├── e9e83b09ae1f237eebcf27bea280842bb81a9934.nq.gz
│   ├── ebc441a3c90b52abc74a5b291f86e90ee6d8226b.nq.gz
│   ├── ec1652abf8c5897547115ceae43e6cd2f0cd6bae.nq.gz
│   ├── f4a4df75021fd86e54594a4cfc01a35b70b1a4dc.nq.gz
│   ├── f6c8e8df1e7d5d4267d82060ffa349af2964739a.nq.gz
│   ├── f95eb78d8a603b0fe5d17560d0dd04877d55c71c.nq.gz
│   └── fa57b08f0d6e1dd1cc399d20614fe93d6a20ccf3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 07d519672687402e6c3fac1a543fbefd810d1e5b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 114 files
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

[ionelmc/pytest-benchmark](https://github.com/ionelmc/pytest-benchmark)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
