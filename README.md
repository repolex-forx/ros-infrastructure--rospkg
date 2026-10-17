# Repolex Knowledge Graph of ros-infrastructure/rospkg

RDF knowledge graph data for [ros-infrastructure/rospkg](https://github.com/ros-infrastructure/rospkg), parsed by [repolex](https://repolex.ai).

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
rlex download ros-infrastructure/rospkg
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dd46467d3f364446862ec3c972b29d451d450f6b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── dd46467d3f364446862ec3c972b29d451d450f6b
│           └── chunk-001.nq.gz
├── blob
│   ├── 05648d8d9dfde1d59598f13d80e1dd004655e94f.nq.gz
│   ├── 07db8a66a621d5001e17e01ed3695cd504d7100e.nq.gz
│   ├── 0ca48d9a8e5fb5a6bf4ea1966a9813016eebe494.nq.gz
│   ├── 11365005f6ecf275115125b2e9494e1daa26e978.nq.gz
│   ├── 13398cc72c06c77c32c06be40f43f7e356f0769d.nq.gz
│   ├── 149209927c4dce89bfb74ed37bfdceb90db99342.nq.gz
│   ├── 1687c9d63f638746b1f08d989bfc89eb8cfbac7c.nq.gz
│   ├── 16a406f81a09d46410de09606b1a4d69ce1b3628.nq.gz
│   ├── 1962469ff630c2306581fea91bd8b343b469826c.nq.gz
│   ├── 19be6cc5b3ed7c1e9cf6e4f990c6174f7cc9124a.nq.gz
│   ├── 1bc43d46e5f375a14b6cec8e88d60deb82012eeb.nq.gz
│   ├── 21aa1f1215251b336fcbbcd843a93d3344abbc1b.nq.gz
│   ├── 21f2c7ac3f923b46663cc1cc437b2c2b3908d75b.nq.gz
│   ├── 21f42a13185234e6b881df586b74f71f8575f0af.nq.gz
│   ├── 221709b6f1eb5b0060f5c265f8e89384a2db00e7.nq.gz
│   ├── 22f568588dea3a64b48512acbd954895e9cb3d78.nq.gz
│   ├── 23ada6e334d126ada5c11b85f65800a13ac3fd73.nq.gz
│   ├── 24bbd85da270990448d941405daa73f0417c3abe.nq.gz
│   ├── 24eb255c8e8ff6cdf9d6be301ad60c1de367ec1c.nq.gz
│   ├── 2650ac4ece3b45a7d7a1c5c8c900122302928727.nq.gz
│   ├── 29ae48fe1e31c155431dba52fa78bfde669cd798.nq.gz
│   ├── 2b45ba40282765031e91196c041c65dc44de7f05.nq.gz
│   ├── 2baf5a08e173024f89cc23d55dd125fed357831f.nq.gz
│   ├── 32254fa7cfa77dd4c734eb570b558577b2fc062c.nq.gz
│   ├── 32b704e8612367209eaf9d57aa54ae54148e4e55.nq.gz
│   ├── 34091a751c206ffca5a12cb65cb7ffa538686b6a.nq.gz
│   ├── 39836f3efd486f23c272981da17b311b3fe77315.nq.gz
│   ├── 39b50f7412692e248846421521fea8be7207d87d.nq.gz
│   ├── 3b105b690d7425ce236fe046b11599a2c3f5bc6a.nq.gz
│   ├── 3b4979c13dc6e5d2564be0906c73478de111bcbb.nq.gz
│   ├── 3e4af5859979c0fde6456a2833b16045a7ac83ac.nq.gz
│   ├── 409a4282e7dd3309e00a7fb52011cc5f60fdab7b.nq.gz
│   ├── 40f6ae9cddd549688d9dd53474cb9308d6599546.nq.gz
│   ├── 4293d5b55e4704c005a95c274467345e26588abb.nq.gz
│   ├── 42c9650ad0b621744308c795e86911be850d49a8.nq.gz
│   ├── 436894df1bc4f82cd334749653e9d1555f862d12.nq.gz
│   ├── 43a98a7a83fed0033e9aef6019668584fedeee92.nq.gz
│   ├── 4e2270b0f7c2993b9a9d6aa531b6ea57daed9bf3.nq.gz
│   ├── 4e55c55f5f85ef0b3e15c7a29655d83833e6a54e.nq.gz
│   ├── 523335a4749a183c25013b7f910ca230d64f5cdb.nq.gz
│   ├── 5468597e2b46bfd51b5408fd85f288b638af8288.nq.gz
│   ├── 555ec90b3a17f6d3b33371919e3c8bb07939b316.nq.gz
│   ├── 5e36b2fa23d559c78effbc9b44b9ee43b0e6715f.nq.gz
│   ├── 60c94b88f57b6a8948dcf5949b72bd6537f72137.nq.gz
│   ├── 60cf97b806264d1ca9769d0e2939718337730f6b.nq.gz
│   ├── 6433e2dac647275ec358603371196203bec6bef1.nq.gz
│   ├── 67a0652adbcf72293d92cc63e2115cb5f1037e7b.nq.gz
│   ├── 67be85f1274474029aad8a75b823592324305aa4.nq.gz
│   ├── 6873193c2852434d4015168af258bde29899da39.nq.gz
│   ├── 753ba36c852446295d3bb35b10a4a1d1a7f7f42a.nq.gz
│   ├── 78bef9fa8eb3ff007e1dd2a6b0ca0a5907d67afd.nq.gz
│   ├── 7921e74059255b9cd2995c44d187ab8aee159295.nq.gz
│   ├── 7dd21ebf0c4646978f18315f5b67421841c812cc.nq.gz
│   ├── 7e468320313f0091496adc5a9d9e895e63ba857e.nq.gz
│   ├── 7fa954f97a1bc8b16a602151dabed6edfe5cd994.nq.gz
│   ├── 8485426680059969b16ec365a720f16010f057f9.nq.gz
│   ├── 87544975306416110c42bedbf7421e3c8a42b62f.nq.gz
│   ├── 883452e04cfcfbc2321ecd486429f9e99f180bb9.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 909488c805905139cbd290cf8a8c48447fda999c.nq.gz
│   ├── 910983fcb2461fff2a16d86c56b7aac1cde61bf9.nq.gz
│   ├── 91bd796e872972e496c0951221c35ea08850cfef.nq.gz
│   ├── 93acb3fead4adc536baceedac7fac91d548173c0.nq.gz
│   ├── 94a1c961639101c8c633c6684c00cbf4f04217a7.nq.gz
│   ├── 98504d2fd036827401bb83482c4820e0183661f3.nq.gz
│   ├── 98b716f4141bf1814155abafed0086a6d8ce5af0.nq.gz
│   ├── 9a8acc8cb1a34de3a889de099267a432ce45979f.nq.gz
│   ├── 9ae3220aa65961b8e40a7f3f72c7c668c5faa996.nq.gz
│   ├── a005023c9c5cc037e1cd415f2a66ff3e0a34665b.nq.gz
│   ├── a381d0299fe9829c0529295ee6712eb3c73f6520.nq.gz
│   ├── a4c2bcd0a1ab825b2d3017edc2316714351bdb7f.nq.gz
│   ├── a82e37a1cb64b5f127ec900bf8358994371b13ad.nq.gz
│   ├── aa2b558138e187597ed962e558e261c2fd89cc49.nq.gz
│   ├── ab20c530ea18166ac3fee525c7e27a7c4d0cbea7.nq.gz
│   ├── ad4072b4c84e508a670c6f317149fa6547f98ed0.nq.gz
│   ├── ad922972b2b9966d996a1e97fee1b36d0d4bfb91.nq.gz
│   ├── ae930c133e8262949bbca57cfb02beeb56111d1b.nq.gz
│   ├── b29e04fe87245859a7a540b951ecb1f99f39c081.nq.gz
│   ├── b2f95d8a50ea1ff630f6a6434b240ad59c823c37.nq.gz
│   ├── b34e331aaa87deb3093ebcf6f4c4f1e2b99579e8.nq.gz
│   ├── b490d38bd7fef0fb01f775c30749c22acc52144a.nq.gz
│   ├── bd2b9e5b4de555a3ca85101791f84f63d9175a70.nq.gz
│   ├── bd52097f2c11f6245732ce7ce9b7db41434fdcd1.nq.gz
│   ├── be5e79c9d4d895c70bfdd69b1c9289ef24fa58af.nq.gz
│   ├── bf2d6cf0f32e69e03ecb880e8369898394402037.nq.gz
│   ├── c65117758ca5299e5e82d3e8d0d3f991cea92eb0.nq.gz
│   ├── ca3d0d50dab17862c0b38356c01ebb12f4c88768.nq.gz
│   ├── cc5e4b5cf9891a45d2f0a43b3edff8939303c74e.nq.gz
│   ├── d133a24a2cd338376435e601fd33818bd09f7b77.nq.gz
│   ├── d2a8be84d804fbdbca2c8b63f32f0126804b41d0.nq.gz
│   ├── d75a4ffb862f22cd8ea693272861f3d958687678.nq.gz
│   ├── d85160a15901c3ede45a3ac8ed337dd520bd0f76.nq.gz
│   ├── dca80001867e5b4d1de71bfccb80937b957b2b71.nq.gz
│   ├── dccdc7a866d1ea76fadbf41d2041ee08823dd754.nq.gz
│   ├── de39b017f4577d0a4bd18c43382ce7fdf20d0252.nq.gz
│   ├── dee24702022ed0e0f7b7889e5ee31fee1fa23748.nq.gz
│   ├── dee7873314bbd1de4e58c16edffa2a6be4a32f2b.nq.gz
│   ├── e06ac240a2d60350ecc0c68f7e5451d41f57b527.nq.gz
│   ├── e0d81db777f56ec6ce771fa073929b52c93341b7.nq.gz
│   ├── e120716f160ff97a7d90b98e6261ee0c016a3cc0.nq.gz
│   ├── e167e9880c31361a64071c07e7f8e9baf3818f2a.nq.gz
│   ├── e3c6e1c8e65106996d29d56df818f5174903ee07.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e80797893e76b41c294d6c36d159e46c40af2c37.nq.gz
│   ├── e83156e71b0bde97e6a99890a624d27d045d7358.nq.gz
│   ├── e9585d6438e1725d813bba65048d9133efa13989.nq.gz
│   ├── ee4038e128747edffb65faa3e0d43f9fba1888f4.nq.gz
│   ├── ee74ef5d13ab3680ca61f8fb69a9101a9de496ab.nq.gz
│   ├── f0d216908c6dbd12dbb9575675ab542843c9a37c.nq.gz
│   ├── f4353a1bd6fb5794482a7d6aa0525d12eb27cc4d.nq.gz
│   ├── f6647e7bb119df491e4991cede465974afbd23dd.nq.gz
│   ├── f6aa0ee2c7154379978129ab2cedb32b61a5f488.nq.gz
│   ├── fa77798ee0d9b6dc6b237fc66b6fd684cd8d26e6.nq.gz
│   ├── fc897088152008e99be8fb72596f81d8a0e83b7f.nq.gz
│   └── fea7ba97859ffdec5921ab122a6c80edcb90766a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── dd46467d3f364446862ec3c972b29d451d450f6b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 123 files
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

[ros-infrastructure/rospkg](https://github.com/ros-infrastructure/rospkg)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
