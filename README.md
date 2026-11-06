# Repolex Knowledge Graph of aklajnert/pytest-subprocess

RDF knowledge graph data for [aklajnert/pytest-subprocess](https://github.com/aklajnert/pytest-subprocess), parsed by [repolex](https://repolex.ai).

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
rlex download aklajnert/pytest-subprocess
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c24b26cb0bb23159244bfa103db660afaf4f24f6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c24b26cb0bb23159244bfa103db660afaf4f24f6
│           └── chunk-001.nq.gz
├── blob
│   ├── 0198b5db98f3c29f97b2eb5e8a3b80a054158b14.nq.gz
│   ├── 01b60293dc205129b2210aaf994be763916d5659.nq.gz
│   ├── 0382fa71b32f597bf5a3523fac1a93eb71f5cd6e.nq.gz
│   ├── 04e83bc08de066dc929e47aab7c49971e75d509f.nq.gz
│   ├── 0a24438a077ffd9e0f1260d6e2f49a756857702e.nq.gz
│   ├── 0acc12ea353a6691eae7d0d26a83d1b8943c9bf4.nq.gz
│   ├── 128d411b242a03e128dd39ce0175643e846237ca.nq.gz
│   ├── 13cfb1c1944c6798a155c95e45bbbd0db32682cb.nq.gz
│   ├── 1406048c0505626f9298f2c6116e1eecf532ed0b.nq.gz
│   ├── 1944440e396be1d0f5294f849f941d644b15be29.nq.gz
│   ├── 2088a1234061605b85ad91eef5481919483c5635.nq.gz
│   ├── 2ef55bf759ac8fc99a6d1ad956ecff1e8a89dd79.nq.gz
│   ├── 3da07899131694a13c05269efadce6a6d665d496.nq.gz
│   ├── 4040ea0621c8f0eec6b6a3d4cb651e5ea6b0f5b4.nq.gz
│   ├── 432a6d194f6cf2f1450cbb311ba137430b8abd9d.nq.gz
│   ├── 436d4185e41bf50caeddfbc06d7f7d8a4067b530.nq.gz
│   ├── 47ed72d43858d4a5e55f33194a8f52b9ed03e1d2.nq.gz
│   ├── 4a6061c5c5936304111379e1ec7ae4ce97588ab3.nq.gz
│   ├── 4fc26028c789fb287f38038a47321781065b0d87.nq.gz
│   ├── 51dc57379840765dcca7c652dba710a81e4aa94b.nq.gz
│   ├── 5a389c95ed366cdd7f03dc9d87d84590a81325c2.nq.gz
│   ├── 5f11f811f35c57f9bce2445860f7fafdfd8bbd0b.nq.gz
│   ├── 6777bd48e89a9bf1f69a65f23ea3c314870d70e0.nq.gz
│   ├── 67e6b20fd189775372055b83c531789951c3b564.nq.gz
│   ├── 6b386ef379af9ab9b74725b22db1964250857ee2.nq.gz
│   ├── 6b697f1bdf0462ae5705fa06d9d5ce90016f6824.nq.gz
│   ├── 6ef3678eaff1f5a33c5e36bd0219db0b3d56efb5.nq.gz
│   ├── 70262709b4fa20bc6d288c1d818b8878398ee21f.nq.gz
│   ├── 71eddbe7d1a9bc65a99c53a17d49b13b5868e362.nq.gz
│   ├── 730ff6f59ab1a241aab3a1dd1d9d2031cad486bc.nq.gz
│   ├── 732af6d8b9f4be952dce03ae44ba003e78c7ba09.nq.gz
│   ├── 73f8620e2a78c5d43f413d3fa14675769bbbca6e.nq.gz
│   ├── 7582d17cdba959815da44fb4c4c153445c7ddce5.nq.gz
│   ├── 76e0264aa4829fe6e56edcb1f039897a3edde731.nq.gz
│   ├── 7c6b74d927239a3eced89b5cd5c56b24e4275c42.nq.gz
│   ├── 7cd9772cd06cda3751f5adadb5d25b8585b897f9.nq.gz
│   ├── 7fba70dd83ab32baaa8dbb6a44aed4b4cd66dd53.nq.gz
│   ├── 82a629fb58ced99cc6017e4dff8c0d6e92c8d647.nq.gz
│   ├── 831cf380c74520859b09a1e55f72d21d45417ea5.nq.gz
│   ├── 84110f1967686af2d9dfd8901032e016f3967e66.nq.gz
│   ├── 8600bf804517e05c058fb2f81b8f915ea8fc1c0d.nq.gz
│   ├── 868e2a26b3db55fdddeb633c5f40864047c08ecf.nq.gz
│   ├── 86eb6e3979720a1a7e08f1b08ebc7f385dc1fe4c.nq.gz
│   ├── 88040a15b161c8b96fc189c0459c2c067e0b64fb.nq.gz
│   ├── 88feb4fd65744e5c22d8714deebb4328c146fb5c.nq.gz
│   ├── 8a2a1585ae52fda65e622bc115f234809ae75886.nq.gz
│   ├── 8e83c8adb1b665333307181878101eb291cd7780.nq.gz
│   ├── 922152e96a04a242e6fc40f124261d74890617d8.nq.gz
│   ├── a012d03261d3d16af72de4b8d4634a5499f640fa.nq.gz
│   ├── a09f310fa1aa2fb8c772e33a372b1069b2218d4a.nq.gz
│   ├── a3277299a7728374cb10a7dbf8b86f1c547284f4.nq.gz
│   ├── a42545c6bdab118049a1cdbcf0079180f46abce0.nq.gz
│   ├── b1386ea2d61c9c8138d6b61e780a5e5fea795d7e.nq.gz
│   ├── b2093bca8f687cd9f811be78d22185d5b80b1c89.nq.gz
│   ├── b2b983f87cd684b733379e0a22a853e73444ccc1.nq.gz
│   ├── b30a470bd28cb96b6318c81f1099c97ce6e4f7b9.nq.gz
│   ├── b32bdf4a108a40abccd1f4e4f168e3097799e857.nq.gz
│   ├── b668f2607cd557ddf61d877d2ceb7417feecbbcc.nq.gz
│   ├── baaf76b11681613d32e77227792066e278bee487.nq.gz
│   ├── bb6989915c13770de11a26e308d9ae7a0243a817.nq.gz
│   ├── c15adffea1b1b8a821cb1ccd2bc7f08832a3fb80.nq.gz
│   ├── c515aaf7cd195e6518ea6be0af8145be1378f6c7.nq.gz
│   ├── c532595a214453ccc3e1e699d0405dd50adbe5fa.nq.gz
│   ├── c68b19ecdfc0567e3c89f252e0e6d5be8fa75a2a.nq.gz
│   ├── c896416a5607543d7987b3db135a92aa14285026.nq.gz
│   ├── ca847e77c7a68ae294459404eec00023c29b8e27.nq.gz
│   ├── ccea1638dd30755ffe3a35f9db6e6f8bfa964c53.nq.gz
│   ├── d07b2b91874d0beb051bdeee51706904023b7920.nq.gz
│   ├── d11926dc7185b7ba78f2ad3a74485fc39a437455.nq.gz
│   ├── d2b684d81ec785948a1811afd0075282c9110bd3.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d9aa425132ce0d22ca2287cc84e18d6dd67b83e0.nq.gz
│   ├── e2704fb1a6c37daecac049724ece6ae27b36aded.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f80cbc829093622889b95fc7ae6c4eafe96e9ba8.nq.gz
│   ├── fae5b56484b60c31cacab7958f41efb25aa7db1c.nq.gz
│   ├── fb9464221388fa76561d86651046b0b5b58aef80.nq.gz
│   └── ff87d5b958b8fa0841961d13345d87a42d5e966a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c24b26cb0bb23159244bfa103db660afaf4f24f6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 86 files
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

[aklajnert/pytest-subprocess](https://github.com/aklajnert/pytest-subprocess)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
