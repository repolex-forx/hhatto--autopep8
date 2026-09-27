# Repolex Knowledge Graph of hhatto/autopep8

RDF knowledge graph data for [hhatto/autopep8](https://github.com/hhatto/autopep8), parsed by [repolex](https://repolex.ai).

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
rlex download hhatto/autopep8
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 11e31c92e940674cdc12958656a82c8be5381f47
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 11e31c92e940674cdc12958656a82c8be5381f47.nq.gz
│   └── repolex
│       └── 11e31c92e940674cdc12958656a82c8be5381f47
│           └── chunk-001.nq.gz
├── blob
│   ├── 0166d69a53efb78e1884f0889518993f9da03b11.nq.gz
│   ├── 01748f7ce3ad08aa5f31c513e06d5e1f3cbc7e06.nq.gz
│   ├── 02fdd4f825182ff5f1bde0ed7f6a0990825e73d0.nq.gz
│   ├── 03d67bb04299cc4b7602e5cc43768c84aac40102.nq.gz
│   ├── 0a25cb1f617893713719f9fb330cd4ea5f3a7eb2.nq.gz
│   ├── 0fd8fb0c448af43048cba00f191457f715eafc94.nq.gz
│   ├── 10a4283fdb51ff7e98db83b02c0dae00ebcae23c.nq.gz
│   ├── 11fb6572a7490a250b0b3b819ee6b853436be64b.nq.gz
│   ├── 163056d9e7553ddbed20f97b9368fabfdab1d535.nq.gz
│   ├── 1641824237cba91fa6b6232786f77b7a98a93c6c.nq.gz
│   ├── 16467649436b275986a4a01e0a7b461710635738.nq.gz
│   ├── 1be1007dfb50d9199e88f51d28276edae6c9cdc2.nq.gz
│   ├── 1fe66c12e16ff5ccf8a5d0b6b7f87d395cf19a88.nq.gz
│   ├── 2cee57942f8d765f54d8e14edbbbbc73ef790760.nq.gz
│   ├── 2f1ecc28c9263c8ed42c1f30ef5ab534c2e94868.nq.gz
│   ├── 2f25a877f34f8c8a62d50f8a8b5791fb639b61d9.nq.gz
│   ├── 2ff470b12e1ef1e68f1d4cb262ca4ca989a50d63.nq.gz
│   ├── 2ff5deadb39f993782030d43320f36604467c9fb.nq.gz
│   ├── 31ad6b951aeb99fd59da366ceedc93d6db037573.nq.gz
│   ├── 36fb4aa7ebe8e0940e732970e317c444d26ab551.nq.gz
│   ├── 37d0d4297bae9388bd588d4bac37bb3d458137d3.nq.gz
│   ├── 3a03b034e392b70295e8d11d05375d75e3468450.nq.gz
│   ├── 3a9e4473e5260183f744bb83a541b210c0d0901c.nq.gz
│   ├── 421d6b9a2e25bc156e3470065f7f834ecacfc828.nq.gz
│   ├── 42802ca82106c40060efb9f5155285411a7816e0.nq.gz
│   ├── 45e9a46fe84ad9711333bbd0e2b405ade7a2ca82.nq.gz
│   ├── 48db892716c65ead2a79d5cf526b833d35a032b8.nq.gz
│   ├── 4d625ac96cd0a020b7649999e24b5f2b06f4e151.nq.gz
│   ├── 50a8a9fa07db42455f32582a20f73e91f0b14dea.nq.gz
│   ├── 50d66711b8c81b288fd146476e0eb6b3eec4bedb.nq.gz
│   ├── 554814c47839f32df7413729bd66ffe72cb950df.nq.gz
│   ├── 5cac8648dede319634de6e18bd0f7591369b1e47.nq.gz
│   ├── 5d3edfa55659251872a57811080a5cac93c79a41.nq.gz
│   ├── 60322100485eaaa393257327ec31b5b59dd90d60.nq.gz
│   ├── 63ee8a7a849c5f190ae2e82d7c6ebdf7fe27d645.nq.gz
│   ├── 64feefde5e93eeded0084b675eca4bd2df9dad97.nq.gz
│   ├── 690840a6a17769d5dc0d2341b8945874267ad1b1.nq.gz
│   ├── 6ebd44e6d4f4fd8238c0acd5efdbe1a4c69e688b.nq.gz
│   ├── 712619d0785c2bb5dd51361bd610f006af1eb529.nq.gz
│   ├── 77e4584c86d22701bd536abfdf3951115c7ff041.nq.gz
│   ├── 8328cfba9e7f6075b58f4a819b4e3cd2c6ac2fda.nq.gz
│   ├── 87ba7d9cdd784dd3868f43466cf300fde15a85f3.nq.gz
│   ├── 888188006f65d6f4de2d96e74d88caeb6153a1c9.nq.gz
│   ├── 8bb801f1beaedfab59cceb71c768dfd8a9ab6656.nq.gz
│   ├── 8eb34cb39916a1ac0390e7575e828f8702462a0f.nq.gz
│   ├── 956cba2d0022d88424da5e6b29da98ddc0015c29.nq.gz
│   ├── 96b55b8790138ffbdc48c625244547b735e938a9.nq.gz
│   ├── 973d22ff9e9092246969b028c1ddb5d1497499e9.nq.gz
│   ├── 98160b2b09fac20f372f365aea2a5fe0c7720ce1.nq.gz
│   ├── 98b94318ebdfe156c279bbfbabc003bed1418fde.nq.gz
│   ├── 9c065c9494ebe1b30ef60202c869fdde585e16cd.nq.gz
│   ├── 9ddf877d315808eb6c262a85f1e51b4412a41acd.nq.gz
│   ├── a532bb3736d4ce476098f94c2ea5443475fac906.nq.gz
│   ├── a9d9276c369c12a1b447eebe48e14255851407ff.nq.gz
│   ├── a9f524450f06d1ec70e7f1ed9cfeed791a5569dd.nq.gz
│   ├── aa4435e0bc99d255d396ba49151e4d6468788e77.nq.gz
│   ├── b0531fac5f460c2fa3232feba337311f02a6c2a1.nq.gz
│   ├── b5f208638c6e5e4a1e7415598a0ac4a9e017c930.nq.gz
│   ├── b66a8a12aafb952717468e80fb1ba08a0656bfcd.nq.gz
│   ├── b67f375391f3b390c6da3a7fc616cf9ccc99eae9.nq.gz
│   ├── bb2bb7e1e75e4385e9a3c950b41dffe8a9bfed8e.nq.gz
│   ├── c36e80201d451a8603aeb81a4c599d8261d32ab3.nq.gz
│   ├── c4575efa15d9b9a970e52c1f38a1e05f46dd4b99.nq.gz
│   ├── c65f0fbaca8b17a6a3de2706efa6a15a5ef3c068.nq.gz
│   ├── c6e69133dbaa0334603e79b907cb041f68fdbd15.nq.gz
│   ├── c7d787a0c5f2e6daf9617b09872cd4d53885bb82.nq.gz
│   ├── c8163ddf2ae67f45f4e3a04552c1c4e3b328e9d0.nq.gz
│   ├── cd142e3933380f99be805ba311c58895d748ff9a.nq.gz
│   ├── d2d7bf356259bfc29ecd04516c750d12f200f736.nq.gz
│   ├── d324e52d95f320446b0e7402894dfe967c0e02cc.nq.gz
│   ├── d838e70e09e5af00106d3c39db80020ad64d377b.nq.gz
│   ├── d921c25f412ab97856b6acca98fb1c0eec05182c.nq.gz
│   ├── de66a090276c850b8ee888439c37e4ddc7551993.nq.gz
│   ├── de833ed1318347c7c9c343ff00fa7471be56ab49.nq.gz
│   ├── e2fbdffb1579e50e813dc5a1c88f1a5bb1186111.nq.gz
│   ├── e561fe795f9b4c51180b433232ab3bb351fba5c9.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb49479a253520bbc5c29bb77f4cdbb3b3ba34d6.nq.gz
│   ├── edbb1f0935de5b11e8eba70b4f30e66effb3b110.nq.gz
│   ├── efe5d34d77d5ed41dd781566bfa5181eafce3fff.nq.gz
│   ├── f334bfe6b2528ac0dfd5ef4b951aa3680d01cd62.nq.gz
│   ├── f3d0130289b904d5ab01da42c90513948e1a12ed.nq.gz
│   ├── f3e80faf6397ee2ada623b7be783c86607f41250.nq.gz
│   ├── f8425424e3ae1ab4825cd1b9546989607dd5fb56.nq.gz
│   ├── f9d3e8e17cb4d7f9fe9db4b44a63b0c8a9f8f65f.nq.gz
│   └── fc6a652916c7a5f1068adc07afa4c24ce4d98690.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 11e31c92e940674cdc12958656a82c8be5381f47.nq.gz
├── filetree
│   └── 11e31c92e940674cdc12958656a82c8be5381f47.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 96 files
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

[hhatto/autopep8](https://github.com/hhatto/autopep8)

---
*Parsed on 2026-09-27 by [repolex](https://repolex.ai)*
