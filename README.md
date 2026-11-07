# Repolex Knowledge Graph of huggingface/research-agent

RDF knowledge graph data for [huggingface/research-agent](https://github.com/huggingface/research-agent), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/research-agent
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d840fa46f7034480a45eb4e82fd60005a3b0e8fb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d840fa46f7034480a45eb4e82fd60005a3b0e8fb
│           └── chunk-001.nq.gz
├── blob
│   ├── 0145d859cacf543ea9b93e161bdb00fbf91334ae.nq.gz
│   ├── 01d062928de148f47414aacbf1f404760a5c6ab7.nq.gz
│   ├── 025cc62ad0790fae8676017c9f369e41f2f60c13.nq.gz
│   ├── 03988c4ea427243354b42c6c50abec5a08166e7b.nq.gz
│   ├── 0504a6555cc2ad51021a1ef16d60711506eb2bbd.nq.gz
│   ├── 05a1448f701a6769fed6bdf724236d7611bfbbf0.nq.gz
│   ├── 06df928475a77154fc843c4e052d83a67c9e9bce.nq.gz
│   ├── 081e17c0352b303d91179f2774f0191c7ae3767d.nq.gz
│   ├── 086ae291347278abfbc6eb147794531a305430d5.nq.gz
│   ├── 08f11da6e54ace17709eda01b5886e211ef79945.nq.gz
│   ├── 0b49152389628fdd1d252faffa69463f8febf5d1.nq.gz
│   ├── 12321b46085524edf56b671aca9bdba3fa731bad.nq.gz
│   ├── 128b052edd8b57f3f19729536bb7075b0a95c16c.nq.gz
│   ├── 1499b5a0ee7b1e0d3453b56ad9c0945c74e5ed01.nq.gz
│   ├── 15f7bdd7916ac5fca2274ad5d1239bafe0f0f5a2.nq.gz
│   ├── 174a7df6656068e5e0dca0db3fa0d607d61a64ce.nq.gz
│   ├── 18ed35c7405f4d3babfcc0ad8484d12492d47985.nq.gz
│   ├── 1aa5d20b1c0237789b3588f1bf6e0c354e1304d6.nq.gz
│   ├── 1b38249d296a92b4f0c7f1b0610159c381ca8ea7.nq.gz
│   ├── 1c3930a666e7d0bf00787216c2e29a5c1191ce6f.nq.gz
│   ├── 1dc34b9794666118346ff6ddeeac932220b4155b.nq.gz
│   ├── 228a518b71d0fed42f6bc0088979386a0e1aa6d3.nq.gz
│   ├── 23527726d6f3c49838f77e7d9c5ac07512811718.nq.gz
│   ├── 271133fc6c9c62e9e4a32aaefb6bfa5a008dee07.nq.gz
│   ├── 275da1c7357d686a8d6dfa8a9f02a94ee62b7c94.nq.gz
│   ├── 2b01c098329161c25af14702c385a5230982836d.nq.gz
│   ├── 2f348fd3fc2d892952797d3902b6661338c9d06a.nq.gz
│   ├── 303c6130d8390016033bd3bd2288d273df6c7913.nq.gz
│   ├── 350ff49074213543e12880da5b2843e6a2bff28e.nq.gz
│   ├── 3527e9d5bad98cd2d66e9611f40ef874ef92bf0e.nq.gz
│   ├── 3af2234f699b417418e2ee8af1bbda333236c513.nq.gz
│   ├── 3e65d40107702d9510f4fcfcb84d2c001e242002.nq.gz
│   ├── 3e6c303f72363922f36b28d094c8de8c16842667.nq.gz
│   ├── 3edcaa2309679fefb0a6dcab4b47f4258a363b3f.nq.gz
│   ├── 3ff369c5f8f962637d451f28b5af69a8c8c3034f.nq.gz
│   ├── 42d8331520ff5c57da0f650f37a28514061e8484.nq.gz
│   ├── 43c5d3c0c97a9150b19d10bc68f4c9042c5034cd.nq.gz
│   ├── 445c218cb85f182dbb5a09fadb10f59b5df6e10a.nq.gz
│   ├── 451c0b78c5fb09a125abe592e0e37f0fe05faa9c.nq.gz
│   ├── 472a250264a118825853b8668d80f1b84d288841.nq.gz
│   ├── 4a849eb3626f6a98da948bceb811ed349e6fdd63.nq.gz
│   ├── 4c378356969f26c593923b1adebbe3e7958c5e13.nq.gz
│   ├── 4e579be13ba0803f030eca811f2a5d9a700e8c4e.nq.gz
│   ├── 4f294522a46659a505c3d206cf61e594b0fb4ff9.nq.gz
│   ├── 515997d04b1ef3ddc193e6ba5feff0dc493823ea.nq.gz
│   ├── 549500fb9255bc0c91f991c39e78c8f109d4bb76.nq.gz
│   ├── 56ce10defe47aab70c73e26d070671f700770491.nq.gz
│   ├── 58f69420d4e7b3c21d3f5efb48b48770a0f8791d.nq.gz
│   ├── 5a9dcfe3ec8db3b154727fab31a4943622e4d445.nq.gz
│   ├── 5ad1b949a0c197a50891c5b7faab69074e27e5a9.nq.gz
│   ├── 5b097cd5f8b98b3f4cf5e10507a94085a3e3fff9.nq.gz
│   ├── 5beb5a85188ce29bc1f43bc425327b94b885a17c.nq.gz
│   ├── 5c813008a3beed051271f43fc0d349e42e6cee4b.nq.gz
│   ├── 5e496a00e1b414e775e98cda53d6e6bbcd5cb2a4.nq.gz
│   ├── 5edb137234a07b68d810174c08f492a97ca54102.nq.gz
│   ├── 615b2dc6cceaa4040bf64a2317b6e651c9e54ff9.nq.gz
│   ├── 68896edf297c9bf62c4c079a7b9f875671ff6d11.nq.gz
│   ├── 690c1432a99a849331b5065de3efbc291537cd3d.nq.gz
│   ├── 6a321d460f630f654c8e30a148f92922c736a97d.nq.gz
│   ├── 6ec5df9a0c5638a17796102b34c9353aba2f504b.nq.gz
│   ├── 71f99f1f530f68481b7243ef96e22ccd17adc29f.nq.gz
│   ├── 7764448ab0d475383599fb577a69d73243f5f61f.nq.gz
│   ├── 7bf9facb05353775df1dfcaf5e721aad333d2a6b.nq.gz
│   ├── 8292ab03591c8e2ab5e463b379494f44d8538a51.nq.gz
│   ├── 852e0c991af9fbd35f95ed6acc72691d62c00c6f.nq.gz
│   ├── 8533f9a90dbc70d3c57ae9f53f6898e95a4bf99e.nq.gz
│   ├── 8550e1dbdf79321acbfc1b608da3f1364e0a828b.nq.gz
│   ├── 85a3e39f1b4d6d970e8b0e622b922f4984d30628.nq.gz
│   ├── 8807dd7a2a2fcc14e5f2968f215a4d4c602a20f5.nq.gz
│   ├── 8876117a6806af9d322e165aa2713fdba2977d1d.nq.gz
│   ├── 894ed31d996eb1f6e542345269a8e8bd0531e2a9.nq.gz
│   ├── 8970a713884fc6fe67a8f8ec4c95a776c009e53d.nq.gz
│   ├── 89ae7bd7005a30e3c607e159e632715603dcecaf.nq.gz
│   ├── 8ceff4ff8a88c815c628104313eee51fd31c6aae.nq.gz
│   ├── 8d857a4aa4e5296624b207dcefd9308e77ed57db.nq.gz
│   ├── 8ee4e41be5a6194db2ef75cb7feff36e2d66d74e.nq.gz
│   ├── 93af71b27e16fdc54415b6a3e03636094d64f6ec.nq.gz
│   ├── 93b12e5e7282856b73e5234cc3c05bea8b1f4148.nq.gz
│   ├── 9413921e50efb2a52f0e6629c295018623ee6c04.nq.gz
│   ├── 9c672b341e76e6ecce0c4b9c315006a9f2492d1c.nq.gz
│   ├── 9f3d4484f4f0a0373ca81654c8bc76a5254f1f8f.nq.gz
│   ├── 9f5c4f0bb1a32c1c2e4870f98bae75a5b6d5371f.nq.gz
│   ├── a4506a27308e36dedd8c6cae42ba3728f0ef2b6f.nq.gz
│   ├── a48479daaec20cda070294fb5e51f60f07f9d728.nq.gz
│   ├── a4eb33f8140e06a95e6a3ec1a556badac37bd5bd.nq.gz
│   ├── a6d6f762e3e24636d3a88a478b71ac1bdbe5dde3.nq.gz
│   ├── a7288714f9daa0e1cb81137e37fa31cf1f852e23.nq.gz
│   ├── a7ffba13050445dc9befde80eda3891f39a00ad1.nq.gz
│   ├── a93bbd7bf17f631ceaac809c3db06fa47f7e5893.nq.gz
│   ├── abf6d962b342fe7e3e590ff64df705dbb2d42533.nq.gz
│   ├── ac666116630100afc53b8b9bec4b4dac83dfdcd4.nq.gz
│   ├── ae78153172ef74c6c2e299df47d57d2f73ff2cdb.nq.gz
│   ├── aff533fe31f360b3821458b42f58f3d996de1728.nq.gz
│   ├── b38a925eeffd21557808b19389e04e1f5c74452f.nq.gz
│   ├── b7bebf66a8f5e59fe59a4a8cb7579b3200f06c35.nq.gz
│   ├── bf123216eaa1538762fce87f83c72b1a4c0d8af1.nq.gz
│   ├── c0631f992cd67e5b05cfc87bec10d090147ecc59.nq.gz
│   ├── c6b3743a63498dd5f073257a0940c8df8eec0683.nq.gz
│   ├── c8d1a08f7ed1b3104d9340bfa125287ed91039cb.nq.gz
│   ├── c9eecdf34ed5b62787a8ebef6de7bc8863a7096e.nq.gz
│   ├── ca8311a019f7c66feb6739641481ded8dc326fff.nq.gz
│   ├── cd884252610de8bf4ee75fb560ed2287e65702f0.nq.gz
│   ├── d02f5289ea81df80146f61567092043eb6e506a6.nq.gz
│   ├── d272a9f5188c34eb569e78e7f26efe07061c1239.nq.gz
│   ├── d2fee1be0f5df9e52ffb64936d1d89bfed785ba7.nq.gz
│   ├── d94a6c45795d5fb10d987b6987b9ca833ddeab1f.nq.gz
│   ├── dd27d88db4891c017e7def95adc645c40ea4dfad.nq.gz
│   ├── df5a2c5c085c52ff9e75dedcabf5b790fe0cf0f5.nq.gz
│   ├── dfefd5bb15b36d92587e3b6e9d2a37d9b8fd05df.nq.gz
│   ├── e0442a961ed5910267c301a70a2bef69dbb3d2b9.nq.gz
│   ├── e611549a445690cb23c52f9403dae39afc921dc4.nq.gz
│   ├── e713e3faa89f49cb9208a89e6039eb9923ae9c79.nq.gz
│   ├── ea55d761a30ade1637f68066202d04988a4ad4ca.nq.gz
│   ├── eaafb446d8a864dd503aa21f38a821ad2cce3628.nq.gz
│   ├── eb5eb360a962ab1fc9d67f9443e7e181a5a03b82.nq.gz
│   ├── ee56d2d37ab9dc55d6f754d190651136591c3bda.nq.gz
│   ├── ef170393a61114b12cfced8281f02d233520b2e1.nq.gz
│   ├── f234973f2d0713c38d906bcd5e39ba402084919b.nq.gz
│   ├── f333ad063ad1d56a01c9cd6a1a1ecc8728820879.nq.gz
│   ├── f353e9191f76067cc74b2ad50a262fcd6856dd3a.nq.gz
│   ├── f4af5c00191edcd32b71f0012e480e6fb2df9df5.nq.gz
│   ├── f612d00080763faa972c0e2151160a0bbf407d6f.nq.gz
│   ├── f7b30bf7d356a9a84d548bfa4cb04646d5d615bb.nq.gz
│   ├── faeb08448f29b607caf89b933449e06af38b9259.nq.gz
│   ├── feac9f9111873e28218915c88c2e5a276aac1b4d.nq.gz
│   ├── ff857e524a6b9b59603382ed9b2f34672c6d479d.nq.gz
│   └── ffe195e306df0d70857306b998c5294d942a8166.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d840fa46f7034480a45eb4e82fd60005a3b0e8fb.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 134 files
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

[huggingface/research-agent](https://github.com/huggingface/research-agent)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
