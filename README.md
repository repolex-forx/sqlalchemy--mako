# Repolex Knowledge Graph of sqlalchemy/mako

RDF knowledge graph data for [sqlalchemy/mako](https://github.com/sqlalchemy/mako), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download sqlalchemy/mako
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 91b120725753beb34c8072ebd56e266ddada533b
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 91b120725753beb34c8072ebd56e266ddada533b.nq.gz
│   └── repolex
│       └── 91b120725753beb34c8072ebd56e266ddada533b
│           └── chunk-001.nq.gz
├── blob
│   ├── 004cc444f56ea2f2179170f47de5f4cda91372ba.nq.gz
│   ├── 01e996171d16be446ee849ceafafaf2cf699f256.nq.gz
│   ├── 060e113dd78e05cf4ca364b2e1bc11e8f84b0b53.nq.gz
│   ├── 061e9ddd7594e0b55185ab7e5d7ed8a367573933.nq.gz
│   ├── 0d6fce37917fba9c63de5dc5669338c988317ebf.nq.gz
│   ├── 118668de2c19d987a15eea5f0e29ca3c9a068035.nq.gz
│   ├── 11ffb986471eb465cf6bec91e8c5847ebbb05134.nq.gz
│   ├── 138e0ae2503731465eb1bd2d79a65bb3b5ce88d5.nq.gz
│   ├── 15bd54b16e5f35690e5f8970c04c810701ae5e5d.nq.gz
│   ├── 17c9b99dca8cdcccc0928f019f53d2e5d8ef3eb8.nq.gz
│   ├── 1a431c8059bf58680d5d699104c0c5c09ee215b7.nq.gz
│   ├── 1a5944b2429c763c5b38279f92a4e441345e333b.nq.gz
│   ├── 1c1760124768841121dc3c09cdefe7159995674c.nq.gz
│   ├── 21f2db54db507b236146432c39d4b4cc40bb2f9a.nq.gz
│   ├── 22221cd20c4a65054ad0f6fec17640255671a81d.nq.gz
│   ├── 22b6bac031ec732dcb1f8a69449975c61849beb3.nq.gz
│   ├── 23401b70c8917fdab24bfa050038e647af7d5c16.nq.gz
│   ├── 247f2e1acf59cd26055b0b0e56093ab4c1192edd.nq.gz
│   ├── 25324e3c3cfc3b4c40cf217a5bd19a85c5dc4526.nq.gz
│   ├── 25ad35e7746b82a2e65a4c33c70da701912ccf00.nq.gz
│   ├── 267411c33a38a176af34ac3dcf356c140d67a2bb.nq.gz
│   ├── 28735841691c1724d6dc224462ee8b12e1dab1c9.nq.gz
│   ├── 2c11000836100632fb6f0579e2fec9ae773e40a7.nq.gz
│   ├── 3104ca9579f927422368bc5b3383be15eda468b6.nq.gz
│   ├── 311d312234b20d8123c748e4c4fb008cfe6d9a4c.nq.gz
│   ├── 320d94a208ac9819d3cdb70917bc43b48fc23a8f.nq.gz
│   ├── 36ec5fac9dd0cace866d8f52107b09bfc02f601d.nq.gz
│   ├── 37afb4de2991fb281e2eac7d2acfdebc3e53d364.nq.gz
│   ├── 37b2d14a395f5c27ed608955860471d597e2ae3d.nq.gz
│   ├── 385d7a0087db05bef6432cb8790ef0e7af366646.nq.gz
│   ├── 38998c2a37a63c05be7b9fb9cdbc0ad0d3339579.nq.gz
│   ├── 39644a399b8cd3fc38b7639b7d3e874b8ae1de72.nq.gz
│   ├── 3fff197ba76b91819825ba38ed840a4e03d1ba73.nq.gz
│   ├── 41f9afdaa57799b886f47e2d9c2883ca8e691859.nq.gz
│   ├── 432487fbc6e696b1ce47531695333f4573f74544.nq.gz
│   ├── 45b826250f5e57542e3713bb1409f7bfaf4b62b9.nq.gz
│   ├── 470713a5172f268a7b7bfcd7b5a9f90000cfb7f8.nq.gz
│   ├── 4c18adee3da2a51fb5b2b77567cb408ea4395b50.nq.gz
│   ├── 4dea2b35583266bb9d30f860c5f5adec6d8dcadc.nq.gz
│   ├── 4ee3d0a6ed770aba19adb757ffd552d504c5b9e2.nq.gz
│   ├── 541ea54091c80974ab9091ad478692673816befa.nq.gz
│   ├── 5ae9d38d3d590d51cfe4486dab31589207a287d3.nq.gz
│   ├── 606849326a4002007fd42060b51e69a19c18675c.nq.gz
│   ├── 609c5c29882b36165a381f527938f939c55010ee.nq.gz
│   ├── 680d7a40c96f268726073cab5f744fb57b6187a5.nq.gz
│   ├── 68ea903c6ebc18c7ae6c2c68d3bc691f346524c7.nq.gz
│   ├── 68ebec464c264dc2503584cec2e8e5f184994b43.nq.gz
│   ├── 6a797d7a4b6f83aa475110ca9378db7273179fc7.nq.gz
│   ├── 6aeb2d274e3509cca3278ac9d5da21d8294aa02e.nq.gz
│   ├── 6c2675b89796335b99dd604af92aced17b94cd76.nq.gz
│   ├── 6e2faa80e371a3ad225606a66ffb0119ab88749a.nq.gz
│   ├── 726f5d74fb64b13ac75b28f9855bc330c31dde4d.nq.gz
│   ├── 74a8fb9dbcf6578b30ba8874ac31838c221ac19e.nq.gz
│   ├── 761f9463d38f171ae23474b16644ec696ea91dbf.nq.gz
│   ├── 77823437804fc32633a80a302c8f9a03457ce45f.nq.gz
│   ├── 785c652304a5f2adc4decfe4e00d10482b97f270.nq.gz
│   ├── 7f79d7a3f38c6cfd8da983a7291aa274ba9adec4.nq.gz
│   ├── 81d16dc1a95cbe7a60cac2a9b8e93bb7f7d8b938.nq.gz
│   ├── 829ed097ce1dd90fd517760f0f49ee23d41cf8c6.nq.gz
│   ├── 82c7cba8b450ffe9dd2cd91739db1c3e2596ca54.nq.gz
│   ├── 82cfa11665168ce08d4bd3fab195fbcffedf457b.nq.gz
│   ├── 842b8fcd3c2642e4ab0b1ae65c9ff781bc32f76d.nq.gz
│   ├── 84e23380df7ea584b46cca664288c250cff6f776.nq.gz
│   ├── 870312a1d71e54cf9e0d6fd68d370d38d7b10de4.nq.gz
│   ├── 886e8dd059856838baacb031571ce56fe78b302d.nq.gz
│   ├── 88e5a9673550bc23e37d20ffd3b3f77f02cbf0de.nq.gz
│   ├── 8adc14263b408b26d76a4abb8562060ead6202b0.nq.gz
│   ├── 9341d933ccf6ec35f12e1748e90956f3fecae65f.nq.gz
│   ├── 95c1cb451960ef9bae15759aa1797d77bc601f66.nq.gz
│   ├── 96aecb2add690a3f7c08ebfb669382f028d23b9e.nq.gz
│   ├── 989ddebdb9a174eb1dc1cf3145bf0a81655c8b1f.nq.gz
│   ├── 98d541bd37f7a2bb51ae120eda5bed90a6a082bf.nq.gz
│   ├── 9aa2f23cbefce6b462a4fd353cb771a100175fd4.nq.gz
│   ├── 9df72e01912be20d3fb272adfe5edf45f2b01ce1.nq.gz
│   ├── 9e0d5598af6a9b9f36c39314fc7380efb8b0e66a.nq.gz
│   ├── 9f63750d6f62ecc540556805ceb23603d785bcc8.nq.gz
│   ├── a51a463e31b3f0a54a5291e44b6455799197f978.nq.gz
│   ├── aca6eab21249c45a27292ac34a1788697454fc3b.nq.gz
│   ├── af0474ab9c303a9d457e64b75649f50db7477f5d.nq.gz
│   ├── afd323d675f6ac01b14e2fbf0d7adfdcd93dd7ec.nq.gz
│   ├── b1392f30f684de1dc830888a11337d20afb478bc.nq.gz
│   ├── b4c3323c66aea2e577f44933aa1a6a39335c944d.nq.gz
│   ├── b5293f4757f1216d0b87013e9b3d52b9d0d167ae.nq.gz
│   ├── b5bfe26e9fe355c839ebed095de432337e852f84.nq.gz
│   ├── b6b0544f1a60f262fb8caf91703be110bb2d2602.nq.gz
│   ├── b77d0c08084b0a9b1b5e7395e1bd54895ba689e6.nq.gz
│   ├── bb9e72df36519fd21ce61f301a6026523ab66a7a.nq.gz
│   ├── bd18eca1eec29a9260796ee2edd036269fe984d6.nq.gz
│   ├── be2fbf718581de16304ed3eac5a960525db78b0e.nq.gz
│   ├── beed529fb35a5f431906eb9b03109e2a1228e847.nq.gz
│   ├── c35420f52fc4bbe0630d37de2c8033bf3aa6e262.nq.gz
│   ├── ca0f9696757490fdddde2041bbcee31967410e10.nq.gz
│   ├── cfe79b62e8a0fd9252540f85b08198d2bbc8d821.nq.gz
│   ├── d2117dbc09aa419f6dd9051ad4517e83a4f7dc19.nq.gz
│   ├── d5338bd9cf2972e7d7a956920c24f62cba39f709.nq.gz
│   ├── e1654ff79e6d3d0960119ac9cd9bbe294396e2e2.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ecbbe0fc88dd24f71de339021b04e6102a333212.nq.gz
│   ├── f1c224345ddcf38e8964f35f0e59056abe4f5c2b.nq.gz
│   ├── f3e40e01fd9bc17389842cf5bb72ce259af5e0b5.nq.gz
│   ├── f54bd1580f5b2de6761b61d5f92c75bd0c3e8ad9.nq.gz
│   ├── f67e22e5adcf00d2726b93500182e11895cc317e.nq.gz
│   ├── f7bc72a3c62332c0512a6c3fa770a66f0081a5c3.nq.gz
│   ├── f7bdda8d670624401d0a3dc78faf596e170b828b.nq.gz
│   ├── f942ad9ba94418f1e22f5be3ebc51fce83fa7a17.nq.gz
│   ├── fa6c759996f963f4254e074a93c25fadbdb11c15.nq.gz
│   └── fc365272254d2ebae202c3fdd4f974b637daec67.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 91b120725753beb34c8072ebd56e266ddada533b.nq.gz
├── filetree
│   └── 91b120725753beb34c8072ebd56e266ddada533b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 117 files
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

## Source repository

[sqlalchemy/mako](https://github.com/sqlalchemy/mako)

---
*Parsed on 2026-04-15 by [repolex](https://repolex.ai)*
