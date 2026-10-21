# Repolex Knowledge Graph of sympy/sympy.github.com

RDF knowledge graph data for [sympy/sympy.github.com](https://github.com/sympy/sympy.github.com), parsed by [repolex](https://repolex.ai).

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
rlex download sympy/sympy.github.com
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 03a7bc94602530171364077abe9101fce9913bea
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 03a7bc94602530171364077abe9101fce9913bea
│           └── chunk-001.nq.gz
├── blob
│   ├── 031f44b08004741ad36ea433955413f804b3bab0.nq.gz
│   ├── 06423a2a9f099b270eaebc23d827fa909b76cc40.nq.gz
│   ├── 09d615b7d9fdc103de2101d2e136bba71a446ae2.nq.gz
│   ├── 0bec6fbaaa7edad316d540b28e32e601bfe84326.nq.gz
│   ├── 0f2f98bfb32d29483ff78596e3206ccddfa6a63b.nq.gz
│   ├── 0f366f7c8476a64927a8ed4e0cba4e6c6552b19d.nq.gz
│   ├── 0f54d854f42081bb51aff2ef2e0f183945ccce4f.nq.gz
│   ├── 131c1b5dcb6a7ddd6e3a7f13f5dee86630a1b76d.nq.gz
│   ├── 1610f45258c39ce109d8323c85bddc4f4b5c66e3.nq.gz
│   ├── 1c9de66f1304a3c953499e95a72f7be92dd0c20d.nq.gz
│   ├── 1cf4077b1f0263b76c634dd06cac17d75e0b333e.nq.gz
│   ├── 23309977e505de9777cf991ca778e04695e5f717.nq.gz
│   ├── 2ee037aa2467ed4ee57033e3f145776c0431895e.nq.gz
│   ├── 3036ccfd58a6f712d9444eb6c901e21da39a2dc7.nq.gz
│   ├── 363f7c433d278e1a70e8f4b9751575ee60b6796f.nq.gz
│   ├── 3ac7f63232519ac6136f686eb3601c46260810ff.nq.gz
│   ├── 3ae2f0946ec1c72668ef731c4a134c99023b8f5b.nq.gz
│   ├── 407b3bfa9aa59a60e71eb97298d5835f467f926a.nq.gz
│   ├── 410b87b753c802c6820fab52cbc5fb7bb0045d6f.nq.gz
│   ├── 41aa7b086e9c6479630210b13d8410f09a446cb2.nq.gz
│   ├── 41fa5339230116bb378e36b6b5330c7dd29156f1.nq.gz
│   ├── 4ff6cc618c841d30aa930b42ac4613ea95d1e5c3.nq.gz
│   ├── 55c931d7770bd4ba98dc052d9fdbe0c02d3a270c.nq.gz
│   ├── 5a1308fe3c477ee12ed05c8e76ef5e842a1942d8.nq.gz
│   ├── 5b88ddec482f4abaf2d2a6625003018d670c5d9b.nq.gz
│   ├── 5d3739804b2bd181fb109ca1c9b5e4f571c95737.nq.gz
│   ├── 5d598049f7d9a704d212a54cf8bd42765c60afb7.nq.gz
│   ├── 6104cbfb4d19224534d1774b7e2c00840a90aac6.nq.gz
│   ├── 614e79f523136502715fba46bf9c06035d2ab17b.nq.gz
│   ├── 6457294da61d4e3066d537ef864f22f91d4fe5ea.nq.gz
│   ├── 6603944744886d5440d6e8c9a0b7cda2df64e8f3.nq.gz
│   ├── 66b3403b9aca620d6a6f179d5175769b72af12c3.nq.gz
│   ├── 6b99009966677fcfcc0f12afffecd6acd027c145.nq.gz
│   ├── 74f4b8aaea5083a387dfb5c54d2a043cc9be11d0.nq.gz
│   ├── 7b82e32fefbd936bf0d0d9ec804e46c6ee80fbb7.nq.gz
│   ├── 7cd19b81a5dfb18527b3db8e8387bf67f67fa947.nq.gz
│   ├── 7dcbc745a7c74dc4a3fe311de0fcfbec0bb9cb7c.nq.gz
│   ├── 8465fcde2c2bc4ea62c26afffe847225fa1c676d.nq.gz
│   ├── 888edaa337351897729ca6e38ba1c3c760414276.nq.gz
│   ├── 8b985e17c3cfb1e15361ab767c66d3ee045de1f1.nq.gz
│   ├── 96a233d22e2a49232e49aa183006b81639cda091.nq.gz
│   ├── 97ac90d3c24705c796bc0eac66b458b40f03bd83.nq.gz
│   ├── 9a62fbc2041507eb51123e59b3541009aeee0d9c.nq.gz
│   ├── 9b9a0e9c34fa5391b69ee7d15cacfd7ffa359104.nq.gz
│   ├── a1bd9d34db93b518bbdf971ca5f8e4a4210e4296.nq.gz
│   ├── a21b49545fb3318babd16e1f2777f89788d94950.nq.gz
│   ├── a8bf677e40740d4e7312a784cdf69516b784a49e.nq.gz
│   ├── ac6011191ffbf4fa06c35d626b6bb057056cccd4.nq.gz
│   ├── b0740274ee204421d392da2e1156db136d1eb9e1.nq.gz
│   ├── b44dd37b700b0c16d1a8623ab4c0f6cc0114e663.nq.gz
│   ├── b48bbca9d81c968b746915fb6f54ce04f6f12a49.nq.gz
│   ├── b7c44941eb51ef6a4a999652f7bca86f9e63d71e.nq.gz
│   ├── ba45b5895d84533c405b2fe35bf22e80358f01e3.nq.gz
│   ├── baaa4adf44e64b5ad9b37a95b10eff6b5715d742.nq.gz
│   ├── c0a077eaa0d32fb344528866b5cfd9c5af831111.nq.gz
│   ├── c0e370d7c6c8c86a0ff711ed505d82df576262c5.nq.gz
│   ├── c2a4541e7a685927df65e228d3e2d616a60c7458.nq.gz
│   ├── cc054dae3f62d3ebf7ab87eafa1bdc23e05e27bd.nq.gz
│   ├── cd4320d5760f69ac77f3dbb869c5e8e82589296a.nq.gz
│   ├── d5f06a4f2ee3fcf904e42728d1723b322622feab.nq.gz
│   ├── de72758b29a3bff369d989ad8200c66992a10b75.nq.gz
│   ├── eecdc95fcb8b9debe42607a17bf9b5c8dea2c954.nq.gz
│   ├── f636bff3c64771f905c21ec2f5da49923ff8a77c.nq.gz
│   └── ffce3d40025ced9effae2e1443b5942a9afae7bb.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 03a7bc94602530171364077abe9101fce9913bea.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 72 files
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

[sympy/sympy.github.com](https://github.com/sympy/sympy.github.com)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
