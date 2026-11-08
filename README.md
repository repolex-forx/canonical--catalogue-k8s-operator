# Repolex Knowledge Graph of canonical/catalogue-k8s-operator

RDF knowledge graph data for [canonical/catalogue-k8s-operator](https://github.com/canonical/catalogue-k8s-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/catalogue-k8s-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 86343dfa48ee5adb8052b5281fa04e40c8620d6e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 86343dfa48ee5adb8052b5281fa04e40c8620d6e
│           └── chunk-001.nq.gz
├── blob
│   ├── 0517c11516114930dacf6cb9436a10d7071de9df.nq.gz
│   ├── 069f7d175051c6e5dff1e8f143e9056931a85edb.nq.gz
│   ├── 0fccb8c5421ce4bd4647f4e63965f12615d036e4.nq.gz
│   ├── 1527248b125dabe30867ea3750b2a727c6797536.nq.gz
│   ├── 169da982099be9a6f21e3603ff134913b68e2fb6.nq.gz
│   ├── 1b64f95273cab98dee69550daa30bb0b838a40c9.nq.gz
│   ├── 1bb45e9085b56696c3b53307f0da6268b4b3d16a.nq.gz
│   ├── 219793a0aa948e6766e7ef5ea130682b05755c83.nq.gz
│   ├── 2faae50a9d668375ed74eb2a5b18e7df80e26690.nq.gz
│   ├── 315cead98c47a94db8e5555f7fb1da9d753038eb.nq.gz
│   ├── 37e23fc79825737e27a043dda0062a2ad475cf8e.nq.gz
│   ├── 37f999b9f499a852d1a4b205b962f4dba5169c4a.nq.gz
│   ├── 381d00aab7beab9f83f9fcd306a1163c3906d5ab.nq.gz
│   ├── 39333cadbe404fc353656762421ddaea8c97774d.nq.gz
│   ├── 4280a9f3780a6c30bac35615cf3a4e94c43d91a2.nq.gz
│   ├── 440a11b5a310749418c1f53975387d7c9b9aaca7.nq.gz
│   ├── 44e412e1b5ca28aa734eec6ee9ae247df975e5cd.nq.gz
│   ├── 4b04c55bc9f34898a18606fc15bc5b8c3a72b852.nq.gz
│   ├── 513b0131f3da3400da75c371b81f637346f53171.nq.gz
│   ├── 525946222b7b03a242f656599fcbef9f12d8ac39.nq.gz
│   ├── 57315f921b3cb198248ac211d1fb664237a86620.nq.gz
│   ├── 583a93b527de9134adde06b0d7639d8bea93216e.nq.gz
│   ├── 5863d31e4a9c33340150921a0674645e929318ef.nq.gz
│   ├── 62bd4b6688b7d93279daa3f8b21afc06f1bb790d.nq.gz
│   ├── 62c53eb47b8d83d73828cd6c2d71c90561fb9577.nq.gz
│   ├── 652c7d218edf2dc1dcf39f46f745b352c2172801.nq.gz
│   ├── 6e0892c7ad3ef13272868fa8192a49337b536cb3.nq.gz
│   ├── 7e9d50461abcf8053278e38c1eb264abc49fac0d.nq.gz
│   ├── 7f764c80fb46b6746c20e6bc64066be4e74c7a6d.nq.gz
│   ├── 81e7082068b90c4d884b9ee587eff236d5e24771.nq.gz
│   ├── 8227ab78bc7ff2ad5b3e59131860a5c273c32c5e.nq.gz
│   ├── 888c85583f72dc67ed997c9868566452e70cf898.nq.gz
│   ├── 88ff1492be46a0699eeca8676d36750066c2ac8c.nq.gz
│   ├── 89159f6e56e30ccf82700cae9f9ddb7f3bd810e5.nq.gz
│   ├── 932b3d78353a8ba35dfccdd8779fcb1f9f12c9f6.nq.gz
│   ├── 94c125e67adaa41a8bb6b8005f9f18a489efdbd2.nq.gz
│   ├── 95b6970d480e4ba54b47c6431fad6da018bea4cf.nq.gz
│   ├── 9abd3a73c43f344f2e4ae53a87d2be4527861efc.nq.gz
│   ├── 9b5886559671c2e26f6e3d58d4912f7fc0cafe37.nq.gz
│   ├── 9ce3fa107c426a601fd9843309e0b3ce26945837.nq.gz
│   ├── 9d2acf38872845d2700778b9b0b7bddb5bc4abcf.nq.gz
│   ├── 9f27e2a89e84cd46798e9b0344715554c23442a2.nq.gz
│   ├── a27ceb9c0aed35a221fba2ada0408f45e8899e06.nq.gz
│   ├── a5529e240f9be6fac90db715d75a5c0f91dfaf41.nq.gz
│   ├── a6b7b50fb21b8e1abe0a1bec41669a70824a2a92.nq.gz
│   ├── a6bc694830f81ad29fcff5f5da49f618d6987156.nq.gz
│   ├── aa5eb485602eccf092fd2260582d3dc681cd7a4d.nq.gz
│   ├── b154d958e5e9dc65c1071f77c413fea86cd65449.nq.gz
│   ├── b574111210bdadde237b35f3feb7611e1e966881.nq.gz
│   ├── c0d299798c30548d25d29abb55423441f48ce75c.nq.gz
│   ├── c59fa8ced9af8b0638258b0d7023233e83c1c6b5.nq.gz
│   ├── c7109908f2af5c9bb0ad130c13ac143929643aa2.nq.gz
│   ├── c7f7558b7f5cda06804923010dcde901538ba656.nq.gz
│   ├── cd75452be964577d5c9929e1210caa283e9dbaa8.nq.gz
│   ├── d021add6b02ea499cdf8b649044f68f80d171d75.nq.gz
│   ├── d0294c7f3265fced23625ce06e7c1b6b0125f943.nq.gz
│   ├── d25729588b7ddd229cb0756c0b098ea3709a7a6e.nq.gz
│   ├── d39bc833ef1dc43963a51169b50642f951d46855.nq.gz
│   ├── da2a3010bd32f8787f610f588416d3ba70224518.nq.gz
│   ├── de535d0f97c5fd103dfccb173b400b7e71461bd6.nq.gz
│   ├── dfd5cbc9d3506d91b9b2823c1adabc0369032716.nq.gz
│   ├── e16afb445022173c8ef7ee9bfc7531ca0b48c7a4.nq.gz
│   ├── e7a22848109bd31a59674c061438c7f133d70b59.nq.gz
│   ├── ec005e4ddc08f7ac8051a311ad4cd2e01a67d15b.nq.gz
│   ├── eff237d12e64e81f29d21a8b8f885e32e8932d91.nq.gz
│   ├── f35143eb2ace2ec8c395b78e06459ca40e03caad.nq.gz
│   ├── f49a4e16e68b128803cc2dcea614603632b04eac.nq.gz
│   ├── f8e0e87bd6796e3e67d46f4b90a03153b994b48f.nq.gz
│   ├── f93b8632edcddcb5e23f05b83117b0b4d9d3e924.nq.gz
│   ├── fbc269ad945f3b1b353cd6ba1a0d667da065facd.nq.gz
│   └── fefd50700dbef46e14414f253e464c4d009239c4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 86343dfa48ee5adb8052b5281fa04e40c8620d6e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 79 files
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

[canonical/catalogue-k8s-operator](https://github.com/canonical/catalogue-k8s-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
