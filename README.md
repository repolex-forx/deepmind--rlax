# Repolex Knowledge Graph of deepmind/rlax

RDF knowledge graph data for [deepmind/rlax](https://github.com/deepmind/rlax), parsed by [repolex](https://repolex.ai).

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
rlex download deepmind/rlax
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 036c859d6be16659db1dce7e4381431149a8eed3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 036c859d6be16659db1dce7e4381431149a8eed3
│           └── chunk-001.nq.gz
├── blob
│   ├── 020af07180b81c9c5dd951b4c5d9dd20998bcd64.nq.gz
│   ├── 0d417129faf5dc658394fd0d49fe6ad14cb2ae97.nq.gz
│   ├── 0e6729d3406c0d584e58d6db8b44c4f2de290b24.nq.gz
│   ├── 122b65c429cb2cebc530a4560f303110d0353493.nq.gz
│   ├── 13736d1038199219651136167c6c89456071fbca.nq.gz
│   ├── 17373b162b98a9ff6ecf301b48daa16b8cdd6476.nq.gz
│   ├── 1b36d4d330148c374a3ff7f9b72fe49bbff345a4.nq.gz
│   ├── 21a8fe73db79521a9a0db2e1e501e7a27f371c17.nq.gz
│   ├── 267388b721cc94391737b1fc3358f0d6625bbd2e.nq.gz
│   ├── 3679759c8b95677087273039dba72be5804ec995.nq.gz
│   ├── 3a3412167684cd1915601f7de456dbe605163d4b.nq.gz
│   ├── 3a7da7f22fe384e4abd344301bed35185481047d.nq.gz
│   ├── 3d7771970ab363b95772e82ab2494137eaf9c86c.nq.gz
│   ├── 4a2fda8de9a351d30c3670672e0d4a5c45efce9a.nq.gz
│   ├── 4c576ee6714e6bf9b289cedf24845876581116cc.nq.gz
│   ├── 50c1d7456edb4519bca8001e3f5829a07d7bf2d7.nq.gz
│   ├── 521b2a33d743c80c009eb44715b5e1e3fb26af69.nq.gz
│   ├── 53fc4c6f568acfd9349308ad182f20f966ba2ad2.nq.gz
│   ├── 55a87ef10de2647f84504f81d93abdbd69b38703.nq.gz
│   ├── 639a832cfe810249fbef520048bf1b5d10201234.nq.gz
│   ├── 64a130a2560acfce7524dc41de7cd5f606384140.nq.gz
│   ├── 650b0126c3bd9d69bb9d3ebec36862bc1c55c552.nq.gz
│   ├── 662c9c8cf294a103fae0a2ee666e5af966ef4642.nq.gz
│   ├── 66478f50de9523f32f3f65d5d0074cca60e4e42f.nq.gz
│   ├── 674850597ed9d082939c6385ab29f1b12193c337.nq.gz
│   ├── 6cbd5dbf06fcb36dc7e8b814ddb22226f86143da.nq.gz
│   ├── 75c5f220e71903f8b30142b2dc6f3b96fdd888d3.nq.gz
│   ├── 77460d9802c381a5690e91221241e853db5580d1.nq.gz
│   ├── 7d985c1b8d0d767927ac21c175ef80e98c88747e.nq.gz
│   ├── 811692f5548e91570b8da998a0494219c4d4cc6b.nq.gz
│   ├── 85998eee75a9a708d4167dffe2204b2de2fefb36.nq.gz
│   ├── 8cc5474eae2cc85dab553ce85a60130a675ca00b.nq.gz
│   ├── 91c8eef6c5a2ecd5933a38bf55de2cff17901924.nq.gz
│   ├── 9337d4ecb4a6de696730ab4cf6224617dcffd483.nq.gz
│   ├── 9d97904575707db9ef5e36379837f12fccc1b975.nq.gz
│   ├── a52761d9eaf9dad5fb1d2300fa91c4ce7c4f7a1a.nq.gz
│   ├── a6340ea518457beb37062ed76688e18758f57238.nq.gz
│   ├── acda1bb7cc6f1d30fbd42571fb0378934c9c958e.nq.gz
│   ├── b0bfc14dfe76d85a500f26d0e62fbe033d36f1bc.nq.gz
│   ├── b190276349a4e053c6196ec4484ef27a207df7b7.nq.gz
│   ├── b3ca14a5e841c42037cd7e59d16b55dbbdcf7535.nq.gz
│   ├── b64324bd732fd03628bbabf587fc3f633ef40dc2.nq.gz
│   ├── b6c1aafc6b71a90c32a562c764611618e2e28016.nq.gz
│   ├── ba179c7ee98a2431c2e2ef16ec2f299c42146563.nq.gz
│   ├── c247f00561eb379c9ba389fc01d26075ee267e32.nq.gz
│   ├── cdde5a267b0ed3fd31bc882569704b3d5eb6c426.nq.gz
│   ├── ce8e6ced63d97dde8b78679230aa9c95084460b8.nq.gz
│   ├── cf51c9b12d58c819395661555dfe3da3ab9e6ada.nq.gz
│   ├── d43e517f49325f8ec3ed19659b223f4e64b727c3.nq.gz
│   ├── d52bb5bc24fca9533b171b6f078bf2567571c6e1.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── dcecf184182c07aca7c4c0c65ea14f5a48240a9a.nq.gz
│   ├── dd63cc881ec1d4850f90dde1054dde0acedc0d2c.nq.gz
│   ├── ddca8e64f64f654e882dad905281214822051d3e.nq.gz
│   ├── e16ed296b50b3bfcf4da8e3abdfec60f5d36cd4e.nq.gz
│   ├── e171a94bb3086e0fbe6f0c3bfdc64841ec29b62a.nq.gz
│   ├── e1d19dd5deeb9fa6cc7024cb17d20640a8461b50.nq.gz
│   ├── e35d8850c9688b1ce82711694692cc574a799396.nq.gz
│   ├── e4832d24aff7f9ab0bc5f27ced4d4fd03796c543.nq.gz
│   ├── e869e60e88f6f8681fde06a3861db7af942f70ac.nq.gz
│   ├── ea21c85d455d43c34319c90a3bd892da3a133765.nq.gz
│   ├── ec35f74aed2cc663efd062d1e0a2b1a5628cd9fd.nq.gz
│   ├── f1a17854590811c812917ad04eec1145a63f74cb.nq.gz
│   ├── f2362eec9267248ac93ac17860e622ec34e3b300.nq.gz
│   ├── f86e791e1a1b01483c4e53fd6ad524ae568bf9b8.nq.gz
│   ├── f8fcabe1079b5590dd302c5e8d165c94b3ed8fc9.nq.gz
│   ├── f9a5c18f392fc4005b203f158a4a34c1d5632680.nq.gz
│   ├── fa90b847b200341ee1924ee615fcaa11de1b633c.nq.gz
│   └── feca1eaaa7f301cfaf9a09c4bfb06d0a58e7bb17.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 036c859d6be16659db1dce7e4381431149a8eed3.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 77 files
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

[deepmind/rlax](https://github.com/deepmind/rlax)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
