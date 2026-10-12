# Repolex Knowledge Graph of pyca/service-identity

RDF knowledge graph data for [pyca/service-identity](https://github.com/pyca/service-identity), parsed by [repolex](https://repolex.ai).

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
rlex download pyca/service-identity
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6858d01dd8368ce4530ab776092bab50f899d510
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6858d01dd8368ce4530ab776092bab50f899d510
│           └── chunk-001.nq.gz
├── blob
│   ├── 057262b1bf99fb4b228fa07524df1aebc58c0046.nq.gz
│   ├── 131f0f3d8d14b78bfe4413426701adc383fdba63.nq.gz
│   ├── 24d3a35ad73550f71274d787bdd51b9358a272a5.nq.gz
│   ├── 251ea0aa09a68834758e8c76cd91433ea6ff6c25.nq.gz
│   ├── 27b94212d480e5f28e7062413df61d73fad1f009.nq.gz
│   ├── 2a6cc1570e92ac5380ae626cf472ba6f2f71d26d.nq.gz
│   ├── 3270562a8b4d75e7f37c5263c5755507fb07ee0d.nq.gz
│   ├── 3737ffe2dfc38325451d1f26fa8882af465e5b01.nq.gz
│   ├── 3acab7469a31f7e6eb99405371059a8adb1c48bf.nq.gz
│   ├── 3c71978e375022aba71d8a4b92cb9f8b6ee82d3a.nq.gz
│   ├── 4118aee5f16186c7a7c7f85cad34782968b14350.nq.gz
│   ├── 524d37a363ac415dd1958d36bb59f1e369b754d8.nq.gz
│   ├── 582e1073a5299635efa2e9b6c82682c1558965df.nq.gz
│   ├── 5873723c505af206d0989a138a2abfa0b8044dd2.nq.gz
│   ├── 5e5a83059a485b2d28ee1ea278931edb43529635.nq.gz
│   ├── 62878fe210a34a81767258eb40fd62fa787c4ac4.nq.gz
│   ├── 6324d401a069f4020efcf0ff07442724b52f47c2.nq.gz
│   ├── 66efc0fecd1554e6e4681fcb149692591f388bf2.nq.gz
│   ├── 70cd72d338531ee5eaff4f2a70114058135afaea.nq.gz
│   ├── 72083fee482321b1b3501a1c4edbfed3cae3d4e5.nq.gz
│   ├── 7ad898feb430e5c17122a6e1bea2bc50aa73b7fb.nq.gz
│   ├── 7c5100942aae489ca04d07d2c69a4d8f6f8470fe.nq.gz
│   ├── 823cb81875bb36d5ee168b050e856515c4fc406b.nq.gz
│   ├── 847e6329301f96e3e2074030930c1258570955df.nq.gz
│   ├── 8b78afd5b4bcfa0f5dbca90d66a9256bf1433c2f.nq.gz
│   ├── 8d886c5cab309792ef2bbd8a640d9bea12834474.nq.gz
│   ├── 92fd0f7a7a80d4b4c21ed8c4de9ee9aa5345bc29.nq.gz
│   ├── aa65cb326b0c35022440fa7b8fecd91e04bfd616.nq.gz
│   ├── b0395c240f7e92079d53aeded5e7e44da83143fb.nq.gz
│   ├── b320a584c64087a8cfd5f2411d20ec4d09c7a4b5.nq.gz
│   ├── c63a2942292058b998a873413e851dc7d7444533.nq.gz
│   ├── cd40a21f80701d3ac9b8a664cff612a2a0d636b3.nq.gz
│   ├── cd46bd07565aa2cf3aab3580363284ba2fac0458.nq.gz
│   ├── d123584123f61684d6d9c8511b97bdf62dd28943.nq.gz
│   ├── d1b3f6f84039c60168a8e53f1f5e1f0bb7a56f34.nq.gz
│   ├── d21501ce8568e0fb3086d69512cf2ae3156dd808.nq.gz
│   ├── d631d7d60c2611da2c70c2906902af6b422ca368.nq.gz
│   ├── d72f80f8fb529b3292b80b7baa799b7e9b973c2f.nq.gz
│   ├── db18c773ba6e6bc153bf5c7a852d55a4b162a088.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ebca546aed4220407aa6c6b8a26b05e5bd4b7f4c.nq.gz
│   ├── f514cc396abc9b0494449ca1cad12126e8ae8e99.nq.gz
│   ├── fae1685b975cfca27255b0bc8ce0391efe400989.nq.gz
│   ├── fef3e3e3d1a2779ca6f7895e837954f4a7ee8363.nq.gz
│   ├── ff07d53633dfbf35e97817e46fc9d71808f5b4ec.nq.gz
│   ├── ff55f7e210d430b04ea8bce67265ebce7eabb587.nq.gz
│   └── ffb59a8105a3a911e40c12cd6efeec1ac1cae079.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6858d01dd8368ce4530ab776092bab50f899d510.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 55 files
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

[pyca/service-identity](https://github.com/pyca/service-identity)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
