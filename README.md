# Repolex Knowledge Graph of twisted/treq

RDF knowledge graph data for [twisted/treq](https://github.com/twisted/treq), parsed by [repolex](https://repolex.ai).

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
rlex download twisted/treq
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 99f17121ab7e42fa4f4d12578e45cf3a26e118d9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 99f17121ab7e42fa4f4d12578e45cf3a26e118d9
│           └── chunk-001.nq.gz
├── blob
│   ├── 10f0a5b2e6d3cc2ade39d11eaab726e1ad701bdf.nq.gz
│   ├── 278afa65f040da8bbfdca47885c223a375a9bfe4.nq.gz
│   ├── 2d5ec9faca95e6e30c0b3a15c1fc89290f745aaf.nq.gz
│   ├── 2e234d5febc9ca7d0143a6c4c1bcbb642349d99a.nq.gz
│   ├── 39fda12d68e5730c016765ab059df772aa00cf49.nq.gz
│   ├── 3ba9725e7f2fbb1e3c4121510b908f823b8d3c6f.nq.gz
│   ├── 3ef562558cc939667df80e042165f611a15aed28.nq.gz
│   ├── 414c70d5b2a5880e87f87d7a545c7a2713ffeea0.nq.gz
│   ├── 4450dd893eca2a8e715d43321951c77f3a00bad2.nq.gz
│   ├── 4553660c447af64ee496bb8c0c540f5cb05fdcba.nq.gz
│   ├── 4614342df31d580cbeb3c180f7f4fcaeeba37b1d.nq.gz
│   ├── 4f78198d1d21100b88d9b5228be9ccdaecbef223.nq.gz
│   ├── 51cb05a7e332ffeecdf03a40384c3c4c27e1274e.nq.gz
│   ├── 530c6c6bb472ce676355de72d5a2d0976910a874.nq.gz
│   ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
│   ├── 5a80ee1bb9180571c3519a2f24f0a2b00695f5d2.nq.gz
│   ├── 5f92964b21f31e3c29c9b8d748917aad3b84aa09.nq.gz
│   ├── 612d22b119c92f2d94a46434a10008aefa560654.nq.gz
│   ├── 66238727d8c34bfbbbb36ef6937b4baca2471563.nq.gz
│   ├── 6a37693716817beec48f6fc8ad1a4f566cfedd63.nq.gz
│   ├── 6eada6cdaf3cf43e4fb3b6e19818d41937eab762.nq.gz
│   ├── 6ec015b9f3d889c82bf3126066fe1789f4414fb1.nq.gz
│   ├── 71923b51851be8f350a01ae59351cd81d51cc7e1.nq.gz
│   ├── 72df4568212ae8e5ea845bdb378d457238701b00.nq.gz
│   ├── 730d724aee4ec1ff0a6c32da710df850e9ca9b48.nq.gz
│   ├── 78016c451ee577ae5720bb35b052f3683f332501.nq.gz
│   ├── 7b8d59682456e9f1b37d721d8a52dfcb78768cf9.nq.gz
│   ├── 7c6852047edc2eb69d7b98d997cbc8a5b1898c65.nq.gz
│   ├── 7dd572c70cac4c66d66b8c1c11974b0da70a9f7b.nq.gz
│   ├── 8832e349c84ba627a6ca34f072b77fb7350661aa.nq.gz
│   ├── 8b981adb7da14e31058fa765c919b7815c976adf.nq.gz
│   ├── 8c7b23c7a71b827e532917475e9a659e13ab71f5.nq.gz
│   ├── 8d5786008284bb9b5bbfc79cd2c4f53ca8ec5db6.nq.gz
│   ├── 8e8073d0f0314a2d824f1ac59fc5f45ae9a42bba.nq.gz
│   ├── 94a52c176851cb40f62b3950da0e8275cb2361b9.nq.gz
│   ├── 9b0442bd425b08d14cfe42950ad8d89e91a29ef8.nq.gz
│   ├── a2909a19d380f64782ba979a119ae743179b088a.nq.gz
│   ├── ac1eeb8939c0238de64bf07b92220a7c1f46ac5a.nq.gz
│   ├── ad83e5dfbcdc1b33c3817b2c2b3623b4e59ea8ae.nq.gz
│   ├── b1607fca55c2c79138ac144a14596d6672106894.nq.gz
│   ├── b4a238f9997ff8ea0dbe5c535215e682c1589fdf.nq.gz
│   ├── b6379cc0a2c6d41e695eaff96e7a2391762e369e.nq.gz
│   ├── bdbd40da248d77522af062047aacaad9ac590b56.nq.gz
│   ├── be94578e255f1504760affe4096085b32a2fd576.nq.gz
│   ├── bef3a60b84dd0f54c232f578e3c390397646eee9.nq.gz
│   ├── bfaff93601189de3e24ee6a117f92ffe0c9ea374.nq.gz
│   ├── bfdfa989215de059366121871911b48b3369aa1a.nq.gz
│   ├── bffc91e3af55815745cf9480a2b311a99d78e27b.nq.gz
│   ├── c03ca002bab4721f724497181fe3c627f89aab34.nq.gz
│   ├── c31fcbc0c1421bed7fcab2fcc677f53d16814d3f.nq.gz
│   ├── c71eb811b103cd5505cde7dcf86c678dfd597794.nq.gz
│   ├── c84c6cd8ecec998bfd2b706e0d74f91b3fe2ce00.nq.gz
│   ├── c8e9083808b30e39d59019e592df72c435ff4a1c.nq.gz
│   ├── c91a83519133b56702b35087f8a0ad4c1ee9119c.nq.gz
│   ├── cf2c7eb267d6f571b7ed491b8c45e82f100a7d94.nq.gz
│   ├── d01e930f244d317bafea7da6789109eb1aaa0ab1.nq.gz
│   ├── d3b412183c24e729b2236c6a06f5e528306fbf5d.nq.gz
│   ├── d9dad123cab9342489f682a2b911086d5438b7d4.nq.gz
│   ├── daa3b8418f540c713b636e76256cdc64a1797b77.nq.gz
│   ├── daac6e167c91dd7ec5c418fce939a54a3be929e4.nq.gz
│   ├── e290c6bb1a4d5681e908802ac46bcc908a76190b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea9d64e808f53ba66b45fa3b93f8e1119d8cbfb8.nq.gz
│   ├── eb19f5948e79754c4d473db000afdefdb9cfac91.nq.gz
│   ├── efc16a5c7471a150c1bf87b2545d0e7d5f2b42af.nq.gz
│   ├── f4063507c6c04589058c758a304b952fe7fa3293.nq.gz
│   └── f724d339facfe5ed84f4821f795a54d549fc516c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 99f17121ab7e42fa4f4d12578e45cf3a26e118d9.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 75 files
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

[twisted/treq](https://github.com/twisted/treq)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
