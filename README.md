# Repolex Knowledge Graph of apple/containerization

RDF knowledge graph data for [apple/containerization](https://github.com/apple/containerization), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download apple/containerization
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 56916452e9fb09ed8ff94b80d8a95dd1a8ca66ac
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 56916452e9fb09ed8ff94b80d8a95dd1a8ca66ac.nq.gz
│   └── repolex
│       └── 56916452e9fb09ed8ff94b80d8a95dd1a8ca66ac
│           └── chunk-001.nq.gz
└── blob
    ├── 002f6c18ab03b6fd7a6b3dd46fc81f06862767aa.nq.gz
    ├── 004143b308b264ee1eef839c73ae075fda6d827c.nq.gz
    ├── 01893bd9134860b46056a463b62bb9e38452497c.nq.gz
    ├── 03860144e869c0a3a6b5271eb7f84399899eb680.nq.gz
    ├── 070cee870674cc786ecd04b199cd425dd5490318.nq.gz
    ├── 077d14a6633237883e2fea9aa9cbcb429fce834f.nq.gz
    ├── 0833eb32d2efb6e07a16256978b9ffebe6e943c4.nq.gz
    ├── 0848e680c7d93561af364a777a5ad7f6136be78c.nq.gz
    ├── 08bece0ca4c6846940f6c238f4c18dc2a08a0526.nq.gz
    ├── 09159cac6b8239fe65f8f85bc7ce99534ccfcda9.nq.gz
    ├── 097f314d19887db2776c8b99bc9841337015d6f0.nq.gz
    ├── 0ae8f65109843be840f788efa5f8ed006fa0118a.nq.gz
    ├── 0caee8b32d83d9e544da8aebda64ece295a535ce.nq.gz
    ├── 115aa6661ecd252f26b7185f707287e41f112420.nq.gz
    ├── 11d9f8039fff15b3fbba0b5d5da4ab9f8f453364.nq.gz
    ├── 12dd67d95768d87abf2c3d773f86e105f6167655.nq.gz
    ├── 13fe9432473a126b9ea5b9d9aa98632ac3ed38a5.nq.gz
    ├── 15031a2c33b4da70bf7304930f44b1b6774bce75.nq.gz
    ├── 1600090fe9f212a83339069d578e129527eb82a0.nq.gz
    ├── 17280a7d860b43ae1b9375e38d7271b7ccc42c27.nq.gz
    ├── 193ca10c0371158f681ef1d8c29478eb8be87643.nq.gz
    ├── 19478f0bb0145c5be2c695b9b85126a0aed86a8d.nq.gz
    ├── 1a435d0e5997da6504f6e440b32941427ac7cbb7.nq.gz
    ├── 1aea7a010a817a98b668dcccdfeb50766a6a59bd.nq.gz
    ├── 1b9723574a7be8d9c107239fc298723a32c0d5ae.nq.gz
    ├── 1bd91ee6f37771a12a225ae1f2e14929f35ee4ca.nq.gz
    ├── 1c22f54f53a2357ebc324d45ba588206bf4f11f5.nq.gz
    ├── 1c330b6e001134840c977673cfe4b7ddd0f74e77.nq.gz
    ├── 1ca9ef95cdbdfac4166e9602b4bee54242527927.nq.gz
    ├── 1eef8b0a4aef15ee76544c6322e0cd029027f732.nq.gz
    ├── 1f2be2a26c7b7a574833fe7485d8983fe340a45f.nq.gz
    ├── 1fa9d753a2a14ea8173394da808dbcb739c42d82.nq.gz
    ├── 20cafc65919d558cf3811fadba41e957d0bf46eb.nq.gz
    ├── 2136a569b8f099434064fa4357ab40f231e1936c.nq.gz
    ├── 217069797e44e87ef3d666163412dc9fcf4fbbf1.nq.gz
    ├── 21f9831310b62b77d8ef43665b660b1d576afbbf.nq.gz
    ├── 22383627c4d578b762bc1358eb5d11b618a5552f.nq.gz
    ├── 24a8e2f601f04575587fbb9636b258ce97b5c3af.nq.gz
    ├── 25c0dcb39236d8703f930a732920eb00a4f6722a.nq.gz
    ├── 2691fd1c3a44e417d18880d9dd71ead8b1235c1a.nq.gz
    ├── 26f7c47e934b6bde65f7844689da2cc8d3109aae.nq.gz
    ├── 27849729e8798e24b2ccefcfdca9083f5b2f47e8.nq.gz
    ├── 27c17a0114914e3a789eb131bc23081eb2688335.nq.gz
    ├── 28ea32a86db939a493b1ad1f28b67bf80bfc8ec1.nq.gz
    ├── 29e17945c4539c9757e757e1075dd84dc7f8b971.nq.gz
    ├── 2aa11dea05237ffbf7c25eb8e5eb0f69fa5f8d84.nq.gz
    ├── 2b40e2032c01bbda858c7e6cd7b88b74c374eda9.nq.gz
    ├── 2c076a192a46bbfa5d8c1d9ca6c93b611b2da69b.nq.gz
    ├── 2c7bdb65ac3e96f4717c2e96b3a28347c9b6ba4e.nq.gz
    ├── 2cbadb1c8184178d2d8a0ad0ecf4beb47b2d139a.nq.gz
    ├── 2d1b36fc85c9ef4e78e1efab534a0642bc208b10.nq.gz
    ├── 2d2cbdbedfaf4eca40c01234709a6c742b553410.nq.gz
    ├── 2d855509875dd4533a56a1cfeced235a72978c5d.nq.gz
    ├── 2d8b07c15a0cd31abcb5d0e0af14c79cc140927c.nq.gz
    ├── 2f3b5c459cd4fc57d373e428e794aaf50f50c45a.nq.gz
    ├── 2fb30c76c3f5b48b7250cfcbf11dfc0c34b5473b.nq.gz
    ├── 3027389896c2d04f604603b748d6365334d09546.nq.gz
    ├── 3106c6902410405cd5335ff3111c0c8f235f6bb6.nq.gz
    ├── 32111e378b5bc5eb0be57ac30abfe0189c23756d.nq.gz
    ├── 330620d32c0ff0db4d8bb325480bdfb60d90aca5.nq.gz
    ├── 3326a3d17720d24add8e4ec16ab2974fe402b437.nq.gz
    ├── 341ba50cef1006d1a03f056cfa87a44e65ef481f.nq.gz
    ├── 35358126675f90af5fa7ca2edcd68182308ba145.nq.gz
    ├── 36f50aaaf5e5d3bd15d2fdd2cea04106c749c863.nq.gz
    ├── 37135a107156e381b4bfcc21d823383b4dd2c7f3.nq.gz
    ├── 379e9582702c55e542ca8b8f97fa4f286c0c2d6c.nq.gz
    ├── 38cbee9eafbca6f3087ce10f2d08e003809736d3.nq.gz
    ├── 38e80bbc766dceec647840d519808f03654e20f3.nq.gz
    ├── 3a96452d16c43aba4ef6ba09a1a591cd0550a8c8.nq.gz
    ├── 3b82940165c1ea674b91b3fffed53234dab41481.nq.gz
    ├── 3c11638026025710402d30db79da339c6f1dc524.nq.gz
    ├── 3e3cc72771bb96da34e6dc12bc69253740328622.nq.gz
    ├── 4070196c8a7046b532f2a187421977c58f823388.nq.gz
    ├── 40abedd527aeca1bd7dfc5aaea6bd3cb37686c0d.nq.gz
    ├── 422ed107be805e8720f3c3dce86f5cb64ee3ccbf.nq.gz
    ├── 4271220587ffe1ea3431cb9053c3399d91272edc.nq.gz
    ├── 4330a04c8f5366217f83a2d030cab0fa935938a9.nq.gz
    ├── 43b81fcf308211d0de1b67a7db066822a33b3621.nq.gz
    ├── 450109ac520f3a33f9699084fcddf555d070e31f.nq.gz
    ├── 45a2291b13d57e8f787c6052a3befc4838e317eb.nq.gz
    ├── 4606ade6586785d08038d98a283472dd7d40501f.nq.gz
    ├── 48682b3879dab81d794eeab04baa9b777c74939d.nq.gz
    ├── 4a21d758a7b8ba25b5fd1b1bdf1496a19b9077a1.nq.gz
    ├── 4b7fdc92ebc5039cf700223ac50a69849e95aa3e.nq.gz
    ├── 4be362650a4e318f4b34caf1c703db490baac831.nq.gz
    ├── 4c5673d6efb41a414e04866cba0e4ccf74618781.nq.gz
    ├── 4e3ac2e64d9e0e7e352701c5e32489c2ab5e2e2c.nq.gz
    ├── 4ef676d63e8bf9bc1bf3e11eb664d26f9093bcb5.nq.gz
    ├── 517426e442f880ad372678ad2c838b4afe308ae9.nq.gz
    ├── 518ab9c7a80d78a1592c70893154f9ebc2b246a9.nq.gz
    ├── 51fe708eb738f7e51d20d79a0f596e4d7675b982.nq.gz
    ├── 5250ced78b4cbd70bc5a8eda648bc271fb73b039.nq.gz
    ├── 537f60b5e8defb1ace40071d8f6ea834fd59cbac.nq.gz
    ├── 53dba03f4156b0e072b7dfad3c871eed8b2b07f6.nq.gz
    ├── 54274aa7943179f7005b55d2c277aafadb8ee8d0.nq.gz
    ├── 54733ba40d9d008d7b9c215c790f6ee0705fbaab.nq.gz
    ├── 54da7a52ce323fbefecf653c01ab6623894a4e44.nq.gz
    ├── 563c07ef8f9c0155d7b8606233c5ccb40a603365.nq.gz
    ├── 57133196e5277a9a5003831d3aef9b76075dea1f.nq.gz
    ├── 5737d5a1d51738beb9c294ff52a174009ec9c784.nq.gz
    ├── 576e7c7312be1029308921290e3f9573f85aa5c8.nq.gz
    ├── 57bc29bafa6a56aaaa95c530761823a6274194c1.nq.gz
    ├── 58c96269d4a8b38f0533ab5c88f53a7fb19395bb.nq.gz
    ├── 59c813a2ec4f0c4b92f50b5b970982eea74f8f30.nq.gz
    ├── 5a773952370ba1e9085adec8eef7a4a9e421d15c.nq.gz
    ├── 5ad43d2de0fb44074e692401b95b2259a00d74fe.nq.gz
    ├── 5b65475f61e291ce8460ef4fafbf747616f24724.nq.gz
    ├── 5b68ece6dabd0a0865cdeb8ba181db517e5d7163.nq.gz
    ├── 5dd93502eeaf3ed70bffb29805a0ac289710e10d.nq.gz
    ├── 5e81924fb49c75a8ae18780e46200b65fc72b647.nq.gz
    ├── 5eb32a414c476596f183cb3eff3fbc9d02bd080f.nq.gz
    ├── 5eec76d3806e08a1c33888a692765e1c9b4e8746.nq.gz
    ├── 5f3650ee0fb85947e553af0715615c86df172351.nq.gz
    ├── 6038ecd1ccdaec7f70a8f71203c88a03f93e2b15.nq.gz
    ├── 63804c1fb6490c13909bd3b4529a90e486892fa3.nq.gz
    ├── 63fbe7b4f2587d3760d13c2543984572857ff897.nq.gz
    ├── 654ee9785a55314027d61eac0b5eb19031a71ab2.nq.gz
    ├── 6653dfe342f96923723430eec593041390d5fdce.nq.gz
    ├── 66b03f0edb6b9eddad98d211bf62b1900d6a1c5d.nq.gz
    ├── 68cca066f4a446294e14942483d9c8fc1134a1a1.nq.gz
    ├── 69497dfad4dc52d361da7f686acec060b6b0286b.nq.gz
    ├── 69abc2730c525cfcaad8986d765293d77ee145d3.nq.gz
    ├── 6a744bbceb00804fee6703172c76db7894eb1691.nq.gz
    ├── 6a98df515cba266e71ab6fd51eda4aa2a382a42e.nq.gz
    ├── 6b00ea5e3f06caa405b222e8a937268f48b14bee.nq.gz
    ├── 6b0f2077af66633dc561dba35b355a41d8c59731.nq.gz
    ├── 6bfe3e9d509a6ab8124ea9387429ae8d72fca051.nq.gz
    ├── 6c6fd06183b9345103616e0e2a4880e3b9fccc9a.nq.gz
    ├── 6c86781568e28903133d41ea2013e3e689c8f97d.nq.gz
    ├── 6f149e74a0e1dec6ef11d0da4d4fa1f9fe3d4fca.nq.gz
    ├── 7027797041941637849bfcf533daf1e4aefcbab8.nq.gz
    ├── 70500a061c98fd43f6bde52f9f76dd4ffd21995b.nq.gz
    ├── 712aab55b48be6b670c46ca946dd7547fc2eabd5.nq.gz
    ├── 720ab8c38666b199576acef357f50977008ef082.nq.gz
    ├── 72831f77a0970c1422660fc3283a30c57c36777b.nq.gz
    ├── 728a9937e964d297f52a7116e92fd2c96d2a71d5.nq.gz
    ├── 7326c97a6ad5e2f494aae12ec6ecd5561a709363.nq.gz
    ├── 73f8889b728a0569c0f26f12a05c4d369d6d4e14.nq.gz
    ├── 748bd671faad1b4cd6887e7bb3cd26afcaa64e7c.nq.gz
    ├── 783a848a077905dd09ed9847fdcb0112d7753244.nq.gz
    ├── 7851ce80b0545f65f4881771aeb4c7baa0e85b05.nq.gz
    ├── 787344df471869f418c795e73abc4135f5e48843.nq.gz
    ├── 7a4a3ea2424c09fbe48d455aed1eaa94d9124835.nq.gz
    ├── 7a7b36faa2d1c0efa77f04ae0858e7eb2e577098.nq.gz
    ├── 7bd0b8d0a09f65bcd3dc6582e560be5152ff37a4.nq.gz
    ├── 7d64b8f9ca92e1ec029b8b0705e9e62b0ba2560d.nq.gz
    ├── 7e0f79d80c385aa15325cb89814338fbc21a5250.nq.gz
    ├── 7e81eb17001c7abd888424778668b9f3ad682ee6.nq.gz
    ├── 7ef25babf4007a4d87ebf5d9f082101421294c02.nq.gz
    ├── 7f446bbe49c6eac9a2fc7c48edaedbe6f64634ab.nq.gz
    ├── 7fd059eb140a18a646681adfaab959a3854b38e7.nq.gz
    ├── 807746e78fd96d84026768e5d3f325abf389f509.nq.gz
    ├── 80eac49b1d0d22511e41e993754bd0d96404717d.nq.gz
    ├── 82f5a652e0177ac9728cdb5256d79bb958e13b98.nq.gz
    ├── 830496844e092196faa480391553b9b879f8970b.nq.gz
    ├── 83652de5b6c91a677538d3744b0f8b8d90ea7e48.nq.gz
    ├── 844ce00ca4c82b7150a1f0aeb82f4b962151a231.nq.gz
    ├── 8522b7c204209c8f7b34a88a9b9d6056f3ee4cd8.nq.gz
    ├── 865dfea759e424d4f00f4a50b05999d95f79b493.nq.gz
    ├── 878a5993f5fc5e9ba0fd5374297389e635e2f37a.nq.gz
    ├── 87b4c3873b1aa40a892c3737ce00ea4ff3845522.nq.gz
    ├── 87d226438c52e35f777a4ebd39f97c80648395fc.nq.gz
    ├── 8962833b158aabc6b8270e3b0d397b900f9ebe43.nq.gz
    ├── 8977a526c033bbc1cd2a2bf870a017cf57818fad.nq.gz
    ├── 897af361be005f8fe419d7696b908697a7f7b342.nq.gz
    ├── 89a1fb3062bf5ab9bda26007e47008c65d42a495.nq.gz
    ├── 8b0ace619f6c6f7c941fca00c4f32a1da515ce5c.nq.gz
    ├── 8b40f16c538e90932adbf1437e99b57d1fc72203.nq.gz
    ├── 8b562ece2a01b6c56b15bcb8b68f86690eb15098.nq.gz
    ├── 8bf21511904d6d307de0f18ca4960bbc345b3f7d.nq.gz
    ├── 8bf93a15b6738d37089038e60da757e939c2ccfc.nq.gz
    ├── 8de868223f695a02a4da72b1e79a6545868048c5.nq.gz
    ├── 8f600e50e9343853a939e98e4e398cc7e6bd2b39.nq.gz
    ├── 9016b707ff644f81ab99b283ffe335a2758e5380.nq.gz
    ├── 914b50d70c7cb96d24ea669643cfc95a651253c8.nq.gz
    ├── 91c3ac265a39989d21cca05dba895fb274188d58.nq.gz
    ├── 91defe53f05e9d94d0912ea17005a690b2480500.nq.gz
    ├── 92cf57c079d91a478673be0aa7cfc6b3c72f98fd.nq.gz
    ├── 93802e9bf5b4c4179e034f7be12e15962d9de99a.nq.gz
    ├── 938cb1d6108ca3431c5ed2322ebad47180ec5ead.nq.gz
    ├── 939c6a529be284e123a816679faabe32cbf6807b.nq.gz
    ├── 951952501f2ac9f8173224d56971f2918dec1363.nq.gz
    ├── 951e4b12009259d21392fd43609241ec39c3172a.nq.gz
    ├── 960345b90ce3cdabd1fe222ccb86f8594cdef1ba.nq.gz
    ├── 979bb1ca86abefb33e792898a9dcb92017d58864.nq.gz
    ├── 97f5cdafbf90b4b85f05327b5dca49fafe72329e.nq.gz
    ├── 995bc6e762dbf283bbaa666904edd9a6a50961e1.nq.gz
    ├── 99ef24e272dc9c4933dc447eb637dd701802e199.nq.gz
    ├── 9a64c6fcfa2c65847992032561b46014cc63af7b.nq.gz
    ├── 9b339fc532e5ab50931067c30611b27b9b855f58.nq.gz
    ├── 9b46d1ff88d3d659fddf11685c296c75350cd06e.nq.gz
    ├── 9b74aca214bd2ca98af9ead03b5af9e403b8c3c6.nq.gz
    ├── 9ba79c5193baac15c24d016b432beed3f9d46f56.nq.gz
    ├── 9bc39a7f24906f251f85741f55dbb8f69a9bbc8d.nq.gz
    ├── 9bcda38ddc1f9926fc62d48259e85723acfee38a.nq.gz
    ├── 9bd03192163543ddca0f5c4b022a180b3ba0fb70.nq.gz
    └── 9e429c5acb622434d0cc733e48439a032ec87a5e.nq.gz

8 directories, 200 files
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

## Source repository

[apple/containerization](https://github.com/apple/containerization)

---
*Parsed on 2026-04-22 by [repolex](https://repolex.ai)*
