# Repolex Knowledge Graph of PennyLaneAI/diastatic-malt

RDF knowledge graph data for [PennyLaneAI/diastatic-malt](https://github.com/PennyLaneAI/diastatic-malt), parsed by [repolex](https://repolex.ai).

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
rlex download PennyLaneAI/diastatic-malt
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 37d629ea93ed2f8d2eed811219615bc1d63fcebf
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 37d629ea93ed2f8d2eed811219615bc1d63fcebf
│           └── chunk-001.nq.gz
├── blob
│   ├── 0050115a13b1d045a6d7fef29c8bafb8a6d4726b.nq.gz
│   ├── 011ba7ecd4affeae7b94be7a47fd8a11991ef531.nq.gz
│   ├── 02dfae2a715f1743ea5ea67289fd3bf9033b9a6c.nq.gz
│   ├── 036e3ab8cbc327fc40c8357f418fb9727f0522e5.nq.gz
│   ├── 040d1fb4593cc73cf47d72240ac1766f9bdb5a73.nq.gz
│   ├── 0618709e8a3be8cffe8bba0e45a26598b4909e7e.nq.gz
│   ├── 063bc2bd0a4e656ccf20653fbad617fa3cd3bd14.nq.gz
│   ├── 07a10250d07fe39a05c62e88762f199dbff55ddc.nq.gz
│   ├── 07a265276d480214d7d997c36150e26efc0c454c.nq.gz
│   ├── 08e84cfa1423c7104cc22ce9037c2789f6baa4bf.nq.gz
│   ├── 0ad9c63f6676de48fadbc0f9257c81f38e0658b0.nq.gz
│   ├── 0c5677aa6c9c97db27450ffbb52ebeefb45e83df.nq.gz
│   ├── 0d3814c1639a63d3c2aab12d1d664bccd553d259.nq.gz
│   ├── 0d544ee7725d9f327f59056e64314bcf3746f083.nq.gz
│   ├── 0e67a9344acb782217e7ffc8f3265be8cdb496a9.nq.gz
│   ├── 115c44701741e9c92a52f3fd3f6f2e59a3bc7ec7.nq.gz
│   ├── 1183ccfdd04438e48eec447a9b4951a684d9e841.nq.gz
│   ├── 127a9b6c366818e6b0e1e95acb8d39771794cdd2.nq.gz
│   ├── 157f49459683b481678abf514682696843fda1aa.nq.gz
│   ├── 18497047124f128708d599589a8d24c65368a180.nq.gz
│   ├── 1876c0c9c1ab01619826783d28ab9481bdb7eac7.nq.gz
│   ├── 18dd977750b4da83d25d2bd6f25f9989f39d4415.nq.gz
│   ├── 1b5964b94a2aeddbcb9aaf573f2a3c5e18453dab.nq.gz
│   ├── 1caf139f6e86a41edd3fe84babe365baed915655.nq.gz
│   ├── 1d1a6295e4f4c13236d5f718a3c55df77b6b81be.nq.gz
│   ├── 1d4bc53b12e23c88f612cac61d6a94f9c241cb30.nq.gz
│   ├── 1d7530c03deab3718e039545c22b97bcc315d1d1.nq.gz
│   ├── 1e06a4df3b59f5e8c8c342b920b6a958c88b4f39.nq.gz
│   ├── 1f45a02fc5f216746b038dcc1c1bd40f0011dcae.nq.gz
│   ├── 20927c486b82492361ff248be8431a722592264e.nq.gz
│   ├── 25739bae90db5ea19939f2d33f01d7c98e887e17.nq.gz
│   ├── 2587704d7ed5768f463c822ca01cf376a44effff.nq.gz
│   ├── 2595d6723860cd6c840f25c16baa6b753242e44b.nq.gz
│   ├── 277e01550185846bbc0e7b9b7bd746a0768791c3.nq.gz
│   ├── 2ad29c0f5785ff85fe9e425d9f9f60e437bc99f5.nq.gz
│   ├── 2be32d568f49173a2c65554a380ea927ce7f97d5.nq.gz
│   ├── 2c624ee653c52fb34b0c06766ac015644a5651d4.nq.gz
│   ├── 2d125e687ef842394d4117bc03276a69064d528f.nq.gz
│   ├── 2e256300e09a6da0fdb221cf15b482f91932d425.nq.gz
│   ├── 2f2b9208c9822e1d31e90402cf282781234dd07d.nq.gz
│   ├── 30cc1846d3fba68f84f282394989b8c74845d49d.nq.gz
│   ├── 31fc1bdbcdef18158e742d069af21b6cf7666b60.nq.gz
│   ├── 328dfc0c87e10a052a190e9a3491e71425e3b944.nq.gz
│   ├── 332686aed472fc7a45c5879c226d51385bc90403.nq.gz
│   ├── 333b56ee889acfea889c11d55da2480938cd5b0d.nq.gz
│   ├── 344e8fabc9d62b5e73e5f7b52b8d74c64ad160a8.nq.gz
│   ├── 34ce321bbe204f9a5ee813cdd7f3f3e1080be8d7.nq.gz
│   ├── 34e81c8dcb1e77b8aa9baef25845123d954d87e3.nq.gz
│   ├── 366ef837d1c8aa8b8461584c5890d74e9d74109b.nq.gz
│   ├── 3865482cf1d37f7768be250624e81b4afb939e5d.nq.gz
│   ├── 38aeddce7ee04734dfabb028694edcca9de42250.nq.gz
│   ├── 3dbefac78ff4dd024038b4a53959e7a595f59378.nq.gz
│   ├── 3ee5f5737e756613d2dd6e0a2b1896da2c858f2d.nq.gz
│   ├── 3fb6d6e71376a53d020f14a37ec44a2406b557ea.nq.gz
│   ├── 40452b2d09c641cbe24944ed1b26b1fa85791b6a.nq.gz
│   ├── 40e8578f6ab2a50d29e8cf9c2751bb85678c8608.nq.gz
│   ├── 410f51713e8fc3f040b52eeaf72fa9ea67d5cc44.nq.gz
│   ├── 41c3c7901835e97b1343c8566c95eac59344d995.nq.gz
│   ├── 456f3df3d929c0dc1f1b8a542506f40437169fd3.nq.gz
│   ├── 48c03f1228b44f38e9ec8d3ce9f9c0de594e347e.nq.gz
│   ├── 4d9ba039f61ea450733d75eb064ef5832a4f23e8.nq.gz
│   ├── 4f12712412a9d395e4adbbbdad7d1951f3881260.nq.gz
│   ├── 5233d8f4c214263840f19b3e2d066f2acc3c1416.nq.gz
│   ├── 5316854c6d47935930af7d18677f952ef5c7876b.nq.gz
│   ├── 53d990b66a360e9c070da7c388127576616cb111.nq.gz
│   ├── 54d85cc3d72253f3e3f141619e260a74c6954d1d.nq.gz
│   ├── 5609825028b52e79f867601d379a2a1256fcd620.nq.gz
│   ├── 56b536e8d9da6bbf740f71e670491f0eca53d355.nq.gz
│   ├── 572f73f6f51499a51564f4e2d031c6fc0c208e9c.nq.gz
│   ├── 590980e40a9ca9358740d02af8fc8916d31719e9.nq.gz
│   ├── 5fd0bb076f68b7b8d59de1821f89725bdb0a1914.nq.gz
│   ├── 5fd64e3c530e9bfb02a09de357ea652e13ecf5d5.nq.gz
│   ├── 6105f7d2d1426da9fc0a6de95a82e2d487b9117e.nq.gz
│   ├── 6135e4e5e3b5ac90da08a64459d121840b3591f1.nq.gz
│   ├── 61404374a75bb79bd5a9620fd2850ee725aece11.nq.gz
│   ├── 61dc4131b0e2cfc574b4d8637223417bd1ac6e33.nq.gz
│   ├── 630148b7ba68c463d0bdf9b0cdbc7e87febb641b.nq.gz
│   ├── 65d018665718be35d9a2c69424b7fd5ee5a2be41.nq.gz
│   ├── 66edd5cbe0ffd18eb1902ccddfa7b4503066ca67.nq.gz
│   ├── 68a57a1ce88fa97be742df2a0ab256b9d1894577.nq.gz
│   ├── 694566481c6b1d3bfc3d3089ea811c485ecfbd11.nq.gz
│   ├── 6b1808404aadb7103e7bd00270ca7a281e3cd568.nq.gz
│   ├── 6b55f42a89e720eb0b6d9f05177f87828eee1f7f.nq.gz
│   ├── 6c3ea55792cd0f415fee640ce4905e1313a45656.nq.gz
│   ├── 6d8618034e54dde8987f56db14d01013c25566cd.nq.gz
│   ├── 6f07e9e69ecf18a79e55675d8d617173513e4671.nq.gz
│   ├── 6f380c04f49103c7f9f21de1cfe65ede2503f0f6.nq.gz
│   ├── 6fe54ded8910e5617ebfbdc83a4a505ceb035b55.nq.gz
│   ├── 73f51198e4af3a66f80a6feae0f3a18a09778627.nq.gz
│   ├── 781480133793cdbd0d913f95fb91c94dc403d2c4.nq.gz
│   ├── 795bfad82bd40a50160127b8b0a93cd8c7312a44.nq.gz
│   ├── 79bacd4924c10b2b204577ea77bd892979cbb199.nq.gz
│   ├── 7b7c1e48ecb1c776c7d2ff895abcf34c03e46552.nq.gz
│   ├── 7b7de5efe80cc3b94d1baacc33d545fe655d5cb0.nq.gz
│   ├── 7bb03170bcf30a555975465f7e842e29cc15e9d4.nq.gz
│   ├── 7f0c23eecdb0ce914b487b793403b575f9d0e4d3.nq.gz
│   ├── 7fb3df401930285216a6a5f2f350861cb4986dab.nq.gz
│   ├── 82ca57f41202e743e9c139d43e52aa981465a455.nq.gz
│   ├── 834bb3a6a0c124a9019b490d2da8003256711365.nq.gz
│   ├── 8529322b6a72fc28baffae17f05c2f7f355cac63.nq.gz
│   ├── 85ffd02c00b168fc0c0f22f9b1da92ddecee5d0c.nq.gz
│   ├── 88a20b4875007b19f7513bb82868d7197310c8e0.nq.gz
│   ├── 8bc027e00560b67887ed85e72a45e1f3fae8978e.nq.gz
│   ├── 8d34d22704ff89e247039c825f0bb6f479cd0e55.nq.gz
│   ├── 8d5f939a8d1c672f58ed6608099e7696109756be.nq.gz
│   ├── 8d8146c3a45c1459cc67f26e81a63288caedff13.nq.gz
│   ├── 8d8ff24789e0b0ead508c213cf95bd5648dab7c3.nq.gz
│   ├── 8f69e3b9b7c250c552cd5ae779ab3b0ae7e5bf03.nq.gz
│   ├── 9065bf361dc6e3bc0cf791e9e922cc36390c7e82.nq.gz
│   ├── 90a64ea35e5d07509e3ba60d2950684e330e22b3.nq.gz
│   ├── 90ab1776ee3ac5d1df261e9043030691ceff110f.nq.gz
│   ├── 9383a507a480f055dd4d8f24c2a98454841da176.nq.gz
│   ├── 948a9a72bb808f22a323279c5b33065469a71aa5.nq.gz
│   ├── 95aab266ffc8013233b7732cab727c9b3ad40f43.nq.gz
│   ├── 95da8f21bc209b7661e2223a08c90f4c31115861.nq.gz
│   ├── 96a03ce0a6e9cb2f3a1a9446dfbb9d23bfc9d97a.nq.gz
│   ├── 9712400045538a69bd7c1180f36dc94b76001358.nq.gz
│   ├── 98cf4d6e20557590effd8f093b4e27e423ae6be0.nq.gz
│   ├── 9de5fc78719f3ac089bc99b802c9887660810485.nq.gz
│   ├── 9f4eb73753fef379f13da900da48830ac22a38cf.nq.gz
│   ├── 9f56d997677541a2598abf4df3dc4a98f361c30b.nq.gz
│   ├── a0f2d653107d934ff28fa7b9d27a2af76f83389b.nq.gz
│   ├── a21bc65e2ce45f85eb99074bfa72290c4ffcd168.nq.gz
│   ├── a288cc184fd992e9825f0171016a5acc76217707.nq.gz
│   ├── a56fe1e59546a69c28453797149f4ea99a876779.nq.gz
│   ├── a61b289ca71e51b3bed395ca096c211e82c520ac.nq.gz
│   ├── aa797a350ba412907ae9e568e1946651929fe891.nq.gz
│   ├── ab7c1070cdb2202204b1e9261b13e2a3df3521c1.nq.gz
│   ├── af466f545dc723ef582227330bf5585c61a01c32.nq.gz
│   ├── af8c0f4e68739a8cbc8359feeda1f3fac8c5a28f.nq.gz
│   ├── b5ebc0124ec6afd9c1ea0c9b98aa5b56f57a7140.nq.gz
│   ├── b7ed1ab8135ca0062c199bc3ffdd15730412603e.nq.gz
│   ├── b96107b48664b12be9ec738a12ffbf3091f3c9f6.nq.gz
│   ├── bb2f0de10d8d7a47686edf9ccd876cef12ef28ae.nq.gz
│   ├── bb97dead7e308daee303b744ba4bb907e26e0ec8.nq.gz
│   ├── bee8a64b79a99590d5303307144172cfe824fbf7.nq.gz
│   ├── bfe3c944cec5f534568df7705d7218e7199264df.nq.gz
│   ├── c0cde85de9947a2b6ad9aa7f93512bc93c42d361.nq.gz
│   ├── c103716e45e0087e17911d9122e579bcbad23682.nq.gz
│   ├── c26c1ea1bfeab95b7304e3673b0f69dff5134fc3.nq.gz
│   ├── c60026af02cfaf97905c2294e653085ce58e6316.nq.gz
│   ├── c758dcc26bb588ddfe47b6d032d219b425dab631.nq.gz
│   ├── c90f4574c89c69b2ad0378f2e5f536bfa546f060.nq.gz
│   ├── cc88fcc619e49bf349419c0932aaf283b2789d8d.nq.gz
│   ├── cdcef5fca28067baa0ebc2c52a4c52dd28b1f527.nq.gz
│   ├── d02c14e42df67f3a7f08983434f8b621c5dba452.nq.gz
│   ├── d0bc62a05ea787bb369538a6fcdbb4b0a1ea097b.nq.gz
│   ├── d0c8ff0409294a67e8c32044d1e7569e78bd50f1.nq.gz
│   ├── d2ef919366f0e96f5731fc7799419804e80c97fb.nq.gz
│   ├── d44099341a6cab9add2468e2bf7929556976753c.nq.gz
│   ├── d534c24267ded339a18586ddbcd5e7f42721d847.nq.gz
│   ├── d74b5c2dacb27703792ba802555a99bfe53614be.nq.gz
│   ├── d80ee1ec89de6737b190b27d6e996a799348bf30.nq.gz
│   ├── d921e2c9fb568409613a2ea40ddad12718807ff4.nq.gz
│   ├── dad222928c284c92fbef8a1a4b0cf5e09fc059af.nq.gz
│   ├── dc0161e58f50c28c01d139f73067bacb830f1ae1.nq.gz
│   ├── dc8ff37dcb9f524b5748c5a4cf7ceaf1e3b856f8.nq.gz
│   ├── dea137f500abe6d041347929bb9c91474113102f.nq.gz
│   ├── ded3ca4c4d74a24a6a47c66473dce191aba6bfe3.nq.gz
│   ├── e0ac45b0151b31c21d38e56731ec0d06c24126aa.nq.gz
│   ├── e0dde8f0284f364df0bd400d5da27adcdff8f67c.nq.gz
│   ├── e125a92d209f4aa7ae2e671d6bcb774508cae57a.nq.gz
│   ├── e328726f04792b3f39b2b5b1513fac92935e9efc.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6a7d5089f8072aec2ca307be93221d3d820588f.nq.gz
│   ├── e89206bdfd2ba98fd9a10d44d058aa32399d9648.nq.gz
│   ├── eb0e496e078cab61f47356e0e828736c45cab529.nq.gz
│   ├── eb412a4a9e87338bc63cf90cabda4de6938f3be1.nq.gz
│   ├── ec051f113b7b79232a800ec015ff606dfcdc16a5.nq.gz
│   ├── ec829bbf498276c93ebf602d3ebd57facf25f0db.nq.gz
│   ├── ed1aed28cffe7ee29df8f82b946192b67fa968ce.nq.gz
│   ├── ee67d4cc6c97823781035e65dfeea74c046ab933.nq.gz
│   ├── eeb098f36650bf3f2cf55ecd71bd26256b6d40d2.nq.gz
│   ├── eef4ac0f4d33e846acfde612226c26e84138529c.nq.gz
│   ├── f31213d506af53028d9f66a416224e259c7954e6.nq.gz
│   ├── f4a252e47981ddff9a8a81c0f5c3ee9b84aba6f4.nq.gz
│   └── f62271fe6113d13ca5f500f95c806e8ffd42c3f9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 37d629ea93ed2f8d2eed811219615bc1d63fcebf.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 185 files
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

[PennyLaneAI/diastatic-malt](https://github.com/PennyLaneAI/diastatic-malt)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
