# Repolex Knowledge Graph of beeware/toga

RDF knowledge graph data for [beeware/toga](https://github.com/beeware/toga), parsed by [repolex](https://repolex.ai).

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
rlex download beeware/toga
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c7d1d4e75505d69554dd6f68da4fa12ed58eb80e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c7d1d4e75505d69554dd6f68da4fa12ed58eb80e
│           └── chunk-001.nq.gz
└── blob
    ├── 0070cab6cb2bec7a58e71168d9e130411ebcf0c7.nq.gz
    ├── 00fb654ffc4156aed71a7a075497243b804ca07d.nq.gz
    ├── 013fe1e050b0dc671b0de796b278c8443f13b248.nq.gz
    ├── 017082d0bca8aac14f4ebf81df249fc30cf790a2.nq.gz
    ├── 021b751de09b58dfe5743dd5980c793971ea0aee.nq.gz
    ├── 036fc66bdc549c52b11525077a855f96adce3c98.nq.gz
    ├── 038da1758338d0b7db4ef20aed66e61a5f9ad8b5.nq.gz
    ├── 04e704a1c81a4a6e126ae2d3f8945562b65f8ec1.nq.gz
    ├── 05117ca0ec3a54b29ea987030969c3a89c29bd08.nq.gz
    ├── 05aef1c2cc63d1104e931fcc2b765d53090d31e9.nq.gz
    ├── 06aa2ed98cd05a94c955eba43cb88cd73ad78385.nq.gz
    ├── 07a0fe5bc7ab74899b934142d8544cf129c56e21.nq.gz
    ├── 07b0f80f36b9155c826e530b1a400823fe5fd568.nq.gz
    ├── 07f0a3266300ef8fcfbc8af1190fbf40fef2f9b3.nq.gz
    ├── 07f1c354ffb68febcd885f34598e9d1733f6402f.nq.gz
    ├── 08a805bbcd70c9e8fce31755a081ea96f5d25abf.nq.gz
    ├── 093aab8343de7915574a9a98ce7244e710d5a980.nq.gz
    ├── 0953580f7065c73cb6d9fdb01f9c31070f12b7eb.nq.gz
    ├── 0978af73cf251e6d74add164bd9e6518a7944409.nq.gz
    ├── 0985337e0d7c49673b4d30362d6387bda8009afc.nq.gz
    ├── 0a215e6748fa661994adefef792ba4f6fa146929.nq.gz
    ├── 0a234fcc08333218292b3eea3467eda041fee71f.nq.gz
    ├── 0a27611416d76a6174808c8ca44bbe4fc031fafd.nq.gz
    ├── 0bec3bb975901e1ae02447c4a1f528fa73265cc2.nq.gz
    ├── 0c316c16e80d941c0a52e6d985c0b5cd30e395dd.nq.gz
    ├── 0c9dfb2cb4ec5de19237399f0011672984ca66b8.nq.gz
    ├── 0ccb8c4ec6d18a0e6cce419dad21f78abcc3c665.nq.gz
    ├── 0d23e6478d8921a3ec7d29f398a6c9587a6970d3.nq.gz
    ├── 0d6c555538cdded4a7f5a4728aaa54a2d7b788fb.nq.gz
    ├── 0d983b91984d1c473d7c41304e2a8cffab22e076.nq.gz
    ├── 0ebf7fdc0471fca7e2d68bd0b9639b8a391da4da.nq.gz
    ├── 0f1f5163bb0f88d6593640e5fb654a9c321bd669.nq.gz
    ├── 0f24ca06d8d4c480d7bffea02a1528dcbcefc05f.nq.gz
    ├── 110fedd61973542657d6fba2382ebf26d8347e6b.nq.gz
    ├── 13573c1552be4c29333093fa0e2258ed14a87ff6.nq.gz
    ├── 1357bb862390a1a212f58f81fc5ca4e415b3e867.nq.gz
    ├── 137a11fff83976942b2f02be785c6890768b39d9.nq.gz
    ├── 137db483d7015ccddea4f8aee4fbebdd7ac9e9a5.nq.gz
    ├── 13947c47b522d6cc80027d08365d92281f6d96df.nq.gz
    ├── 14c5362f3270f84db54518c9f8dbeb6c20b065fe.nq.gz
    ├── 14da237b6f7617e3c2e7497440ecebbf1ab1c583.nq.gz
    ├── 1526ba2849577bb76580151d00f8bec0f4c976f6.nq.gz
    ├── 15fef29e3453d53480c8f75bc6b3c304433a1c78.nq.gz
    ├── 16348b28c354837b48f93c5b3bfb1a1c3c78c8f3.nq.gz
    ├── 168f1ec045d744abebe75e34586d75bc5b624fdd.nq.gz
    ├── 16d0c6cade5bd913f005e45b219f6624990bbbdd.nq.gz
    ├── 172244fd0e8a60df93bb3f2c66c44a2a1b24db40.nq.gz
    ├── 1767fbc81dbbb3c926104b8c900246b47400bf0e.nq.gz
    ├── 179fe4707854972f34355ee987d7702ef9e100f9.nq.gz
    ├── 1838c1ed54c17a0fc82f9e05ae1dcfbdafa78189.nq.gz
    ├── 184dc61f23853610b72b0c51611dc42f85eca0aa.nq.gz
    ├── 18a8ef9a00362438aec4e3bf4766f1f1bda32108.nq.gz
    ├── 195592e46e7f9727140f3d7185f0e7c10b14e62d.nq.gz
    ├── 1a3c370e4f83ee846e327f03a954b2d885bcce80.nq.gz
    ├── 1a3e9dd0018ef0cb6f89a7ce3f723b06979a8fce.nq.gz
    ├── 1a760c90de7c7c17375314c7d170b9b29933567d.nq.gz
    ├── 1c1bde08e376389946b9b8d8fb88a32fc0f17086.nq.gz
    ├── 1c6588d643804365232fedd20292afbc08e92407.nq.gz
    ├── 1d1168690f648cb64e208f11143f535eb48d59ac.nq.gz
    ├── 1f07cebfb4ff168ec3cb4f4d7d555df232e02637.nq.gz
    ├── 1f3a4fe3e437b8ce6861922d442e8a0fcd1e2ad8.nq.gz
    ├── 1fc21ed9bc10c1129fdd691e73c6e238bc5cba9f.nq.gz
    ├── 21336454d3474b4bb2b2d20c085bc42a1b06b27d.nq.gz
    ├── 219f5e9af92bee55e1ed7cf0bd72412f715b8275.nq.gz
    ├── 21c1f1b3bb4d57f8fff0f0244afbc2e8fafae8b3.nq.gz
    ├── 225def689bd330af65a2e3d24adaade7162d1332.nq.gz
    ├── 22718a3f36fe0cec5a84589cc434518ad0e4799b.nq.gz
    ├── 22e869912bc441f18baa95d1f08b34a6317444fc.nq.gz
    ├── 231f8f0a77ffd645beaf63fb89fccfba7e24f9b4.nq.gz
    ├── 23f5e25e95b51e460b33e778868682c55bc4709b.nq.gz
    ├── 2550a48167e46070838530cdb286778a110b790f.nq.gz
    ├── 255c1113c5ba4e388ab78e5430e07cef10db8c3b.nq.gz
    ├── 25c2be2d50b05a33dd52ffcc2f8a06909aa88fdb.nq.gz
    ├── 25f03af74766b7772889d812e87b246f089996e2.nq.gz
    ├── 261deae9987222c38fc6d84c3e33b6783a15e91a.nq.gz
    ├── 26b4b206f7c844f89669462bb5d4035c56b2b63e.nq.gz
    ├── 27b43d39d1c038a7bf7c8c5f26dd6b5f1b141417.nq.gz
    ├── 27c869b1b90042e92058c06fd621142e341a97f6.nq.gz
    ├── 27f2b5e92975b0b2ae406cf4c02b90db4704e294.nq.gz
    ├── 283e5e936f2316e9ac9fb13134b1dce1a9ecd73e.nq.gz
    ├── 28a1db42e052de6979c99eaae733b54ce907036d.nq.gz
    ├── 29ab02cb6d9aba6d9643fafb440fcdba9f41ad7f.nq.gz
    ├── 2a52b2d62822abf74c171007dea3c65369ab0be4.nq.gz
    ├── 2a91889eb9876c54c4d95b1c6b68d8ac91641e7f.nq.gz
    ├── 2b3f7e46a23339eb8c09f24d5b6a5918217c4bd5.nq.gz
    ├── 2c3432cdafe7cfed83e9397d430fda10e4189aa3.nq.gz
    ├── 2c77f8c30319a30a8967b16197b9e365c975c2f3.nq.gz
    ├── 2d3abf2f1730bb7930736707ae60e5018eaca6fe.nq.gz
    ├── 2d78b96f59edaa24065686f86f369736428ce093.nq.gz
    ├── 2e09ac0c488f79b3ea510738d7e0de841cc713f5.nq.gz
    ├── 2eedfd8770bcf8a5e22c6fe8c0784cb1b1e572e4.nq.gz
    ├── 3098fcff6dce8556c40542b1ed3bcfc68025ba4b.nq.gz
    ├── 30e8d2faf66511a389a0b8f84ad2503c989cb152.nq.gz
    ├── 320678a0fb602d40b966e3ccc11a43bd4df9e68c.nq.gz
    ├── 3245cda40bd75be8479eb4e1e55bd305b328a4b6.nq.gz
    ├── 33b0ea58324f7b2407740019b1cfbf1a2382259f.nq.gz
    ├── 3437b2d2f08784295755ed8d3ec52e577897e96d.nq.gz
    ├── 34661cf5b9097d6ce4214019137ff3f616bcc4ac.nq.gz
    ├── 34edcd84946f3382680227a57a278d8141870e59.nq.gz
    ├── 3524138b8a06458d6d0cc8bb0dcfde3636365aaf.nq.gz
    ├── 357ada2a58668dd92596fb8d362b4cbcd6dc9329.nq.gz
    ├── 36095614e9a612f4967c2e0f406049f624a8aa91.nq.gz
    ├── 36326b653e1700a0adca15b0a68cf63288d30b65.nq.gz
    ├── 3638c0f00d29e71871f7a6ced8d8c3220eb03eca.nq.gz
    ├── 367e2df5ad567b3dcd958d11a712de9fe7d3bac1.nq.gz
    ├── 3791bbe7654f4a4c91c29cc1726d6505a387081b.nq.gz
    ├── 38b6167911f2b10fdce973bb8f587ea39a7b4773.nq.gz
    ├── 38fa2a7f4f665b1ed9689c524ffc397c9e20f70a.nq.gz
    ├── 39184054eb47edaf5eee5584c5a7fa1e034550a3.nq.gz
    ├── 3ab23a839e9f6354d55ef288491143e35730c15e.nq.gz
    ├── 3ab9adec7146225fbb86ed8b412b7a9a8498b37b.nq.gz
    ├── 3dc0bd0e50f5d9c5a3e2fcbab8bc0cec18ef2778.nq.gz
    ├── 3e9364b251b9d710e35afab14bcc409d4246df4e.nq.gz
    ├── 3fbdac1602b8cffdb8d2bd85bd406d502b7bf9fc.nq.gz
    ├── 40ba71056cea6589072c96944ba6568e06257ce6.nq.gz
    ├── 42dab728a809023679d36fc720315f8871391832.nq.gz
    ├── 42dbe02483fd2b2a3425b2833f9defa80aae076e.nq.gz
    ├── 42e3a46761cc1410d1f073370b1d4a8ba9ea0474.nq.gz
    ├── 43510851dc20b3e78100ade09f66aa1a7a5aa2af.nq.gz
    ├── 43938185ede26d9bea91c9051be3e21fadb86d01.nq.gz
    ├── 43a404746cdcaf4b390495d5fb020e57c56ce1d4.nq.gz
    ├── 43e0ee13cca21422adca677d484bbe7941be0e5d.nq.gz
    ├── 443347aef4a1c5b1bd6bf8a42e19b383fb8385ce.nq.gz
    ├── 444ef56da72657929d9943c23baec17b5b7344de.nq.gz
    ├── 4555cd2c51e443c8cef7ce8267e34c3ea2fd24fe.nq.gz
    ├── 457109a8f3876ef0859441e8f6aa75ce48b502f4.nq.gz
    ├── 45fd950eaa9c2e6b594be5221049bfe1ac098e4e.nq.gz
    ├── 46c47edc880be1d12cf2e78adfc2b87b778e9f1d.nq.gz
    ├── 47487adc51c0e0645ec6962335a6b12cac15f8e4.nq.gz
    ├── 478f93b878de63993019dc3581fcef346bd37cf7.nq.gz
    ├── 48a3029b80cb4d3f0aafcb8879f18a12460402f9.nq.gz
    ├── 48a88481b406e57161cd983c0b1d4f56e2ef9ac3.nq.gz
    ├── 4903c19acb55ef4f3ff4cf1e53344989c492d0a4.nq.gz
    ├── 496d938a58f5f3a80b334c403e81e3ee9c126ebe.nq.gz
    ├── 49d40bf3f1b53cb77bb6ddea04452244fb45d233.nq.gz
    ├── 49e519a0fada3706f90f2e35ed03579471f130f3.nq.gz
    ├── 4b04dc33c4164f5fc1759dfeb8d5852ae62a2d58.nq.gz
    ├── 4b4091f8eec1a50d9556fcbee0b6ed4d0e80bf0c.nq.gz
    ├── 4b5fcee940ed683cd3fa4979187022ca07290964.nq.gz
    ├── 4c50eb358d61630ffe9bb5bc8f6ca4129baa68e9.nq.gz
    ├── 4ca19f318ea52d9958b0e68cca52933461c0a369.nq.gz
    ├── 4cf71c1d314aa4f334a666906111edb479310668.nq.gz
    ├── 4d75927787e94e7254960249afc8c1b1ff8a416a.nq.gz
    ├── 4dc13163f141c62e8f0a266a5059e9364c447ca8.nq.gz
    ├── 4df42ee9fb6f79b99f741468e13fe0599d8a24af.nq.gz
    ├── 4e5c474d2a25bd4b17d728ffb1ea72eaa397257f.nq.gz
    ├── 4e7f1f7e4d32634d8aea142a720fe04842320a12.nq.gz
    ├── 4fbee634cb77d38ffb12da9465349aca766cae13.nq.gz
    ├── 4fe60845c082703097fe64be8572b9fe7169e7a1.nq.gz
    ├── 50a2e21479930d64245bbc0b1f6492e14c373357.nq.gz
    ├── 50f3b6b1a0ca00e5aecc0f57706b3870b0d90c5d.nq.gz
    ├── 5103db5807ffde015909405e5b6bb39155deddb9.nq.gz
    ├── 527b9581ae9aa29e85f00bc8a3982c5fa56985c3.nq.gz
    ├── 52f95c2f1f3eef227b5241ab4c2d3950f0e77b08.nq.gz
    ├── 533536f4487f67d83a304eb1206e91550f27fe97.nq.gz
    ├── 534f029748f3a0fd877da918c1e86fa95510e2e6.nq.gz
    ├── 5356d1113e478e5fd1bd91136f28ce2983c0b531.nq.gz
    ├── 53c4599dcf097dedaf5a1295bbb1470bcd53e02d.nq.gz
    ├── 540040a5ecb2e24b02b7c4e4c72d4c39106da2e3.nq.gz
    ├── 540a86c039bfbb9fc2248e847b5958d633d09680.nq.gz
    ├── 55417570384ca63d430444394c6168fc8d8ac864.nq.gz
    ├── 564d783e6d4e7e74e2e59c99b29abb3bd718d4c1.nq.gz
    ├── 56b1f330e959779e7d0b1727b177018cc03e9e61.nq.gz
    ├── 57e3958e0c8a58437159d20f1e2ce73847a43c6a.nq.gz
    ├── 57f728b872bf1e79c0894d37733cd1e9500e72c5.nq.gz
    ├── 5834ddb36d71664a13a0ffffd5306c96b3af239d.nq.gz
    ├── 58f69847d8bc44f016ac25cca5fe3cf68bb7a043.nq.gz
    ├── 5a0fb57c35d6ba0f735ac0bebcb2988b8d888a60.nq.gz
    ├── 5a5af0d4fc2a8e538c570a35f3e7b9644fe859d6.nq.gz
    ├── 5a6a1f43300930cf169e02f00ef03f8ddcfee977.nq.gz
    ├── 5aad9d74188f7754b9d49e3ce7106bb991488432.nq.gz
    ├── 5acce35058932047bfbd90bc3d8494ba4ef5067e.nq.gz
    ├── 5c953d1926f9c565865d7246b6d3505af2401406.nq.gz
    ├── 5d69ef7ae26749f791ca882efe42336c39aa4eb6.nq.gz
    ├── 5e030f1b2dcb907ff63f6921f21ee08a4429b19e.nq.gz
    ├── 5f5dc4639ff204f425df54c26f3577f1783f5888.nq.gz
    ├── 5f662339e2dfdae39560642266ce81857ae8e9ce.nq.gz
    ├── 5fa5881ce05c3d8dbde28488ae817a47f0be8a16.nq.gz
    ├── 60cd8ad9f5a73ee1f11572b64adaa2fa8f928bfb.nq.gz
    ├── 615086b552029e578d62162cb2f73dc7336dba77.nq.gz
    ├── 6211be339a892064ade9469ad0b5bb16e574f2ac.nq.gz
    ├── 626c4eb5a72b9248ccce5427c1f60d69a4b3440c.nq.gz
    ├── 635ffb38ee9d6d6fc74e32b0109d56b312f0b382.nq.gz
    ├── 645368abb5b3768f705d80d3788133159a3c2218.nq.gz
    ├── 648fe8cb8d984e4ac79cd41379b14f3e3979ad56.nq.gz
    ├── 64d811b17a043c997dd0040501547706bad54fcc.nq.gz
    ├── 6535c613aa6122712e5ce140c9056a6fc7e27fd5.nq.gz
    ├── 6554db0e5eddf8ff17de2754665a1a3e0f4911b9.nq.gz
    ├── 6629d8b39d074a8e5348328edc1f2bac12a4cb81.nq.gz
    ├── 664f183025b8ae8f15ba1dd8c5f4b637ac627f4c.nq.gz
    ├── 667dc4da6abb26ed543064953c1c514807ee90bb.nq.gz
    ├── 66c4ede0d61b405c61f3c4744cfe287e4b84dc8b.nq.gz
    ├── 67b3d2c55b317f6c140962e891655300abcc7e2d.nq.gz
    ├── 69c433175e08118988ea4a951cfb2e1403cb9eef.nq.gz
    ├── 69eabe04a45dd0a944865aacde0c6a15cfee0dbb.nq.gz
    ├── 6a297af34a1a1b8874227e9458203459c673a9fe.nq.gz
    ├── 6a419b88a2212def90ec1891333bf6749be9dfdf.nq.gz
    └── 6b591745c12773516d64a666840949b64b899029.nq.gz

7 directories, 200 files
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

[beeware/toga](https://github.com/beeware/toga)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
