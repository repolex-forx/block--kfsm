# Repolex Knowledge Graph of block/kfsm

RDF knowledge graph data for [block/kfsm](https://github.com/block/kfsm), parsed by [repolex](https://repolex.ai).

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
rlex download block/kfsm
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 45edb7a1ce581d634c6b042b6556c231be7e3e49
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 45edb7a1ce581d634c6b042b6556c231be7e3e49.nq.gz
│   └── repolex
│       └── 45edb7a1ce581d634c6b042b6556c231be7e3e49
│           └── chunk-001.nq.gz
├── blob
│   ├── 0428c5947db18da863596321b3d0f55762e227ce.nq.gz
│   ├── 0650afa22b1184b817cc7ace6aecd6a610acc439.nq.gz
│   ├── 0a30b2a9e069651e6288a08ce7e70b9093853ac3.nq.gz
│   ├── 0a9c9645ec7391fa5f5a65642d5876116fd13a18.nq.gz
│   ├── 0c79957cc70be756a8ecb34ea3955a25797107c1.nq.gz
│   ├── 175d4b8e293de59fc2d3cc98916f51b6ac61ab94.nq.gz
│   ├── 17bbcdd57aac6d03c3f3cd873a1d329357924fbb.nq.gz
│   ├── 17e39b4b97ef863a25a9ca53a5d0a5edb8fc5984.nq.gz
│   ├── 1cac6efe705a48fd7be4a3f938d3f52fd4389c4c.nq.gz
│   ├── 2027aa64cfca7ee750d05a46e8a6a60ad52cad64.nq.gz
│   ├── 213a2b09f1139dc4b8836d711d45908b1a9b396b.nq.gz
│   ├── 23163d537fa8b94abbeb518d8b2c1d59923ec621.nq.gz
│   ├── 25ed078a45508b2481a6014b6959fc5d39aa09ab.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 26912bdb45b0ccaffb5999c414a1a75c6b9009dc.nq.gz
│   ├── 280325491963e23d7d52fc4bd93bdd5a154d42eb.nq.gz
│   ├── 28b20ee9ba7187eac7344d159387d78c07ed9ad9.nq.gz
│   ├── 2b11e4d42da468dfc4ce2592823be5a2dd75e062.nq.gz
│   ├── 383f4511d444516caed0fd113ee8a2b640cd2290.nq.gz
│   ├── 39ed54786ef71823c237061c6588efaf6fb2caa3.nq.gz
│   ├── 3c0bac29fbb653b1a43868c9ac198276a73a9d39.nq.gz
│   ├── 43294f569fed3a26cfa471f3fc5e2e61234292bb.nq.gz
│   ├── 453f8eef15e11e5f5c2368fe3a9bc90e873ff9a7.nq.gz
│   ├── 45c40d557eb2b797f0fb709e99b4d54a46aca8cc.nq.gz
│   ├── 49c6212c924c49c38896d1631a9cf21dd8613eda.nq.gz
│   ├── 54e4d026a88fa51d3f1ae0d8cfb92d64cc788622.nq.gz
│   ├── 55447e57db1a9dceab6ddf2c10b247eaff9fee6f.nq.gz
│   ├── 5902090e012dd1d279cbc8d354535e3476316995.nq.gz
│   ├── 59e7fc1a7ca9907a4158ae1e7884fe52b3660c3e.nq.gz
│   ├── 5b9dc074bb1ae23fa5641bd5181bdee53c1ab810.nq.gz
│   ├── 5c051f0ff2479275b32214ce91f4e03ad3d94613.nq.gz
│   ├── 6129aead8e5a0bfcb6ab6501e3d70cd08d8e2d9b.nq.gz
│   ├── 63ae2844ce214e2dcc871c00a8e9d0fbafe0bc8a.nq.gz
│   ├── 674b964e6867e1e149d2ab60263dac8b89ba812e.nq.gz
│   ├── 6b75786d4ff41f3f08220402bda0bce6b1b1c574.nq.gz
│   ├── 6ffd1ca461b8ed8508367e7e67933628e1ba09bd.nq.gz
│   ├── 73b00963938b810eaa796581d0f486dfbe5dc05a.nq.gz
│   ├── 7949d1909ff2a656ad0cded158aae6df9ed5c8c8.nq.gz
│   ├── 79d24e261125897289fa77fd76f641768b1a5364.nq.gz
│   ├── 7a24617d7b4860d983759b43d7a4987a561aba2d.nq.gz
│   ├── 7fef769248e85eab6c828b9f2f7b802296cddadc.nq.gz
│   ├── 855540fec20f85b9328218401bae5e37c2b16f2b.nq.gz
│   ├── 88daeb667d9b784a3d751659ae5f67296055df3e.nq.gz
│   ├── 8a7957dc1bcfc7a28eee8e5a1bf5fd00522383cf.nq.gz
│   ├── 8c38d951ac1057f43f0dc07c7c7de97e585b0d91.nq.gz
│   ├── 95b648c4e4ee2a36db7fd1570dc18d91d0bd401a.nq.gz
│   ├── 9a878189d7176926e5652e8361f123219e195b4f.nq.gz
│   ├── 9c9f388e74e79695ac38d48647e93cf1b40a75bc.nq.gz
│   ├── a4a00765f5ce361f2316e6b21aafa4035b6f9f73.nq.gz
│   ├── a58cf93f1112c0c3ad69ff6c3c10f99491af7d54.nq.gz
│   ├── a6b50483409b7328cc1a0c8dc3e1f1882d562c8e.nq.gz
│   ├── a7ddf60b76843c748e49defdb755daa996b02a88.nq.gz
│   ├── bf8810cd05e7b134c7a6c84a7765d0d9868efc18.nq.gz
│   ├── c45573843c3ed0f21ea233d719039bec1364d107.nq.gz
│   ├── c5c5902d9bd540a535209e5002f986d3505e8767.nq.gz
│   ├── cb5542085747a4d7d26e0ba944f3cf651da629c7.nq.gz
│   ├── d38b84eca95c31ac4e4b31099b63bfdd895f38d4.nq.gz
│   ├── d80905a588a94edee47a41a342686a9fefcc5079.nq.gz
│   ├── dc252abc4dfeb59d312c2737162b1429d3c65a37.nq.gz
│   ├── deda7d86bd43c8201c9ffdd05c1fff5550520037.nq.gz
│   ├── deedb67be15719ae8e2f0b6b66440c560af4a138.nq.gz
│   ├── e09641059b813d1682d00d27af3251156a143920.nq.gz
│   ├── e12ac75290abd75a21b59e8d9c5892bb57c7824d.nq.gz
│   ├── e2399c6c59f69a0e2156f45dfbd096a6063873bb.nq.gz
│   ├── e278c7d855c23e1cfbb15e6aff5b4bbb9a1ff682.nq.gz
│   ├── e47b92e43eeaff9d87861b9e51c06cb093281365.nq.gz
│   ├── e4ef514523b1c4420747817415572013db3626f5.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e889550ba4cbc92a720527042e5f6e7a303bfcbc.nq.gz
│   ├── e9da4a7df0889409875ebd7e38ec0e9b6eff90b4.nq.gz
│   ├── eac9b66028d8ebe21cc0fb9ec973369320865db1.nq.gz
│   ├── ed6a8034438bfe9b5421f54b0309e588e5b40fe1.nq.gz
│   ├── ee4786ecd24da5c667b954c2d88b956d89e5e5c0.nq.gz
│   ├── f3b0694cc3fb05e0cef38594f084357971ecca0b.nq.gz
│   ├── f855b54a2a35be59a201bd06db35a7cffb6e0120.nq.gz
│   ├── fb365209d3c7f3de2b42aa957bb5d2e3f8809ac1.nq.gz
│   ├── fbd55fef34355982fe1f827bf6486f08a1c73b28.nq.gz
│   └── fe28214d3352b0ed40820a4999317694c8b1ef57.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 45edb7a1ce581d634c6b042b6556c231be7e3e49.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 87 files
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

[block/kfsm](https://github.com/block/kfsm)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
