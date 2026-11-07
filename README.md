# Repolex Knowledge Graph of ansible-collections/community.docker

RDF knowledge graph data for [ansible-collections/community.docker](https://github.com/ansible-collections/community.docker), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/community.docker
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0e35b1ef2878066e2ed9f24687ebdfa6a59deaed
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0e35b1ef2878066e2ed9f24687ebdfa6a59deaed
│           └── chunk-001.nq.gz
└── blob
    ├── 00268608dc8e730786bf896b3d0576715cc1e431.nq.gz
    ├── 012065c8539f2bd3e61eecc74acf5a046956de40.nq.gz
    ├── 01258f045fde02f4883fd19894e327b05855f2bf.nq.gz
    ├── 01339f04c5a9301ba4e372ada80247f62941e593.nq.gz
    ├── 02587e2d749ac66341c9e8329e2fa8440f60c0fd.nq.gz
    ├── 03f4bb8f7960f21d0cf96c12a261d0c98d922650.nq.gz
    ├── 04eda43c5bdbed5c5efea6ad8bb64bd0dbc63d19.nq.gz
    ├── 04fcae72133880cd69a0157cbec4419bc7c8d72c.nq.gz
    ├── 0530121256dc43595d7b37ee5b34a6449c924d87.nq.gz
    ├── 05fbe110083c312caf00ae9e38844b488fbd6e23.nq.gz
    ├── 062ac5aae2d35f0c212076ff3a67af7ff1f1c27e.nq.gz
    ├── 076ffd31433130027cc83c896fdc8b8a37207ba2.nq.gz
    ├── 07b32f69702420e40d33a1be818eece8e1e332ea.nq.gz
    ├── 07dc1340183652957f23da5e5c27cfa07b8e385e.nq.gz
    ├── 0837c7405a30781445ce4b8aaeed4a0d720e347e.nq.gz
    ├── 0966565378bf6cb9b7ebbab59735a94b706e4f9d.nq.gz
    ├── 099dcf9a831e2b9384ee58979fc301e2f96f25be.nq.gz
    ├── 09a5b0ed420a729dab25ab34af0c398569120da9.nq.gz
    ├── 09e4cdb0512d6f9fdf3e401321049cca0693f983.nq.gz
    ├── 0a20549f4af55fc4c1f42b2415dba53657c37f3a.nq.gz
    ├── 0a430dff10603cd09d5c557f4407946ed44bf233.nq.gz
    ├── 0a9e59946abe49ecd7e59629479b1ce3c024b8cb.nq.gz
    ├── 0b06951496610904501c7b1be970d637afb44baf.nq.gz
    ├── 0b16a700c9a13d7e48110a41525b6a2d2841919d.nq.gz
    ├── 0baadf3460a9387a50bf1d680ffc6bd958816f28.nq.gz
    ├── 0bf73ee861422588683c62d9bebe903fa7d28984.nq.gz
    ├── 0c3e49f9dcf8ba87c60b41ff5abafc56fb5c7b6e.nq.gz
    ├── 0cbf4ec31bd2bc7e2fc499b0ae3eb0c4d894a42e.nq.gz
    ├── 0d9215d1bf564ded5f4ac39088897c544b8c0457.nq.gz
    ├── 0f6a3d5676e091c821d671b93bcaa7e71684b169.nq.gz
    ├── 10267d493dd7dcd2588b3481c0aca6b2f0d127a3.nq.gz
    ├── 11771fdd9f58bf981699ed4b93ce5630070d592f.nq.gz
    ├── 119def8ad6e3958ee72f625122303008fd9162a0.nq.gz
    ├── 11cd67373f220033b98502a9bad187486cd3c9e8.nq.gz
    ├── 122cf059ada4add19a281feeb18f0baf5bdaa4a4.nq.gz
    ├── 131ed660213af6ed696392754b8d542cfc0683c6.nq.gz
    ├── 1376bc0a24d1037fd5eb137a2d240f4020f9a893.nq.gz
    ├── 13929c8cecc36882fbb16e70270febfeb9433a53.nq.gz
    ├── 13f97ae206136890511548b4677f64c24e2da06c.nq.gz
    ├── 142133ff32eb04b4a5098b3bbb7a6dfaf0d48f7d.nq.gz
    ├── 1485e0b2e87d6d1568f82264d11eec7f57b33c38.nq.gz
    ├── 15824726d305bb2a1063484ddc7ad556ab52b1d7.nq.gz
    ├── 15ac2e7e2049de6e8dcfc7f1bf3b53e5182a93b4.nq.gz
    ├── 15bbe920563e81a686a004eb27a6c7965f538661.nq.gz
    ├── 15f04cdb581ac0a036533c20ca7f2f5b33a5dfa6.nq.gz
    ├── 16991c48f8441532adceca8494be0767090d2d64.nq.gz
    ├── 169a128f72309b1cd632b76dcd5565b32b493fd6.nq.gz
    ├── 16d5b07e759b697b7eea85a669c331e1799fb462.nq.gz
    ├── 16f7ea44e449d8d7c5b840eb7fa5034385e387af.nq.gz
    ├── 1759b888b9808eaf70d91c2130ec025232fdd359.nq.gz
    ├── 186e1e5cbc31d751c9dc2e81413b78a02bc1baed.nq.gz
    ├── 18974cb2904009d1f51fb44c6454a9c83ceb1cea.nq.gz
    ├── 19b085f8fd273d4133e5866d2c852833e2e7a05e.nq.gz
    ├── 19c65551b41ae22e670780c78721750d9aaea29e.nq.gz
    ├── 1a1134ee696af885009280f4d0f4d563629feb3f.nq.gz
    ├── 1a2b80dc775186766b8c96385ac09d67e00e3150.nq.gz
    ├── 1abd6ea17ea79cccd78537e0671e370f37b3fbb0.nq.gz
    ├── 1ac44d90a1d1a1af95add02b307822ff7035583f.nq.gz
    ├── 1aeeb64924f97bf365b55d1365403ca258f2f774.nq.gz
    ├── 1b4f5171a8328e4ceaeb99e0f34a597161a95e9e.nq.gz
    ├── 1bf17e053a612aa6868dcc8d039cd248f97d874b.nq.gz
    ├── 1d08a2b258fa73ca731f65cd2a419b5a128b15fa.nq.gz
    ├── 1d77daf2dcf5e03bc6468719da95ca9b571100e1.nq.gz
    ├── 1dbff5a7bff4d5e31adbc6aa7c5579977b7203c7.nq.gz
    ├── 1f4b8e4f10ed86b84cdb431eca9be576bd8c62eb.nq.gz
    ├── 2027fba5c330b1bec5a13251e2726f74a7f7f7b0.nq.gz
    ├── 2084e097ed938bd775b98b0e1c3ce6c4c70bfa49.nq.gz
    ├── 211ce3e17efc5dedeebf4d872e9465b192a35ba9.nq.gz
    ├── 21354de462d32609d89ae3b98448d7266eaf8e80.nq.gz
    ├── 21f0cf419c03fc6be4d52243fea7b3b6be6b0bae.nq.gz
    ├── 22aa405aa56c67382a93cf84737f65cd4b32ee96.nq.gz
    ├── 24661489c0302ebfe4463054e5380d5a4e1ddb99.nq.gz
    ├── 24835607bfc31956251e714a1073f8eb0d37ec43.nq.gz
    ├── 24b1c926f3bae8b1ff7d2ef6deea46372ca2cfec.nq.gz
    ├── 25306d43d5893f8be7fe35912ad085f09a3cc845.nq.gz
    ├── 25b904385f58b134a85044f50cc07a0bd03e930b.nq.gz
    ├── 27ce6b08752cad6f018b31813b1fa52febd319a3.nq.gz
    ├── 2844f5e76de8c475e4aa1c4bc9cb561160cbf09b.nq.gz
    ├── 286094b9e441e7af9669230f1a0840299fe35b2c.nq.gz
    ├── 2868363923e50690a93685ab26715fba0ada54b5.nq.gz
    ├── 2a2a2c4c6ed8388b1ad68388eca53bd6476ad255.nq.gz
    ├── 2a6237784b7bab27563f11154f73cf114dd4ed6b.nq.gz
    ├── 2a770b7228cf58a18dea1f301ed476b76521f893.nq.gz
    ├── 2ad0ed18377749bbaef132444a4ca36a2a272f2c.nq.gz
    ├── 2b4069c857f99b09d0b2290b060627fbca8b2c50.nq.gz
    ├── 2c492fe7d28fb099f40ef4c820c69eb5d32995fb.nq.gz
    ├── 2cb96615a35d0d1aef9412e3dcd1e311f24c92b4.nq.gz
    ├── 2de0d8826fed7197f568d8e62b14d4f05ed89c35.nq.gz
    ├── 2e1acc0ad1c8ea23168a264f9393b4a455765f77.nq.gz
    ├── 2e6eefe6eeb305420ee989d7a5bec9c1f2d9a0fd.nq.gz
    ├── 2ed74f7e4b4adf83585f1b57f169df1290ff0a65.nq.gz
    ├── 2f32ac157fa740d58ceb76a41738cb40e03f47c5.nq.gz
    ├── 2fcd152f95cb8146ef0d4c0a1c9f97751b464c2a.nq.gz
    ├── 312bdfa5c3d55d7c6989c317fd4d15ae04b61ec3.nq.gz
    ├── 313b57d33a553cf54f687de5e77cc097375758fe.nq.gz
    ├── 313e689eee78d9d3cabf8092b503c4571dab6bcd.nq.gz
    ├── 318275d99c721caee4afcce96edfcd7e7db3b2b2.nq.gz
    ├── 319393903653dad8b1de80ebe004f50d2c3d8c03.nq.gz
    ├── 31bec8262edcd942fea893cff79c6f86cd48708b.nq.gz
    ├── 31cb4c87121b3b7e22e5588aa9602514301ebd01.nq.gz
    ├── 327404ad06fb7887d3219ee2f6de572a07479e24.nq.gz
    ├── 33b5b838f7126f2d0d006f056d4a46354d293639.nq.gz
    ├── 35ad0017abfb43822055fd40feca844b6366e27a.nq.gz
    ├── 35fe21bf7a3350a3859440de84c24cec2802c2c7.nq.gz
    ├── 363ef02e27e1d353ce78980b7c81cf9e1c38cb66.nq.gz
    ├── 36fc680af046cbeb4c0bbfb2d7674938a50a7b5c.nq.gz
    ├── 3748c55db7d7e4718d8616315dec387d8737b712.nq.gz
    ├── 376b22767e39acbbcd5a97829b81e0327acf2919.nq.gz
    ├── 38590f2e4ec486212f404e5f1405e69f7ec27db8.nq.gz
    ├── 39b8d2f6549d313bcb6027e43b22e2f908a0440b.nq.gz
    ├── 39e7eee557c5564b2e74b9e99c7900e8021b1bb5.nq.gz
    ├── 3a0ba2089acc65e0b962d70ad9204dd1dd2c1b22.nq.gz
    ├── 3a55751d945a8689b6b56e4db27ed8bd57da4e6d.nq.gz
    ├── 3a67ff2b67e086d0082b8a8994c41bb948d0f0e4.nq.gz
    ├── 3a9a873d3df567a3039400ef2d45d9405dd388b5.nq.gz
    ├── 3b04ccc503a4c94679e36191dc8ab4b28db03dbe.nq.gz
    ├── 3b9a088c7be323bf0e4bdc42871c7fac8a1f16ec.nq.gz
    ├── 3c882645947200490e2b68601073a15f54c6ae63.nq.gz
    ├── 3cd6bddbc79ce8612f2cc701d8a702e78e4a6de8.nq.gz
    ├── 3eeb32e57b5b5622f1752d3a460f970e3444034a.nq.gz
    ├── 40067d9d3bb8fe0a99f5205bd574e8beab319709.nq.gz
    ├── 40ef76e755a720b121b072c1b5ec65f11dcdc37a.nq.gz
    ├── 40ff81bb5aa789e1802c58df98b50ff8b2eb40e5.nq.gz
    ├── 4125749744cd05b638f9cbbc71d7484d33348d8b.nq.gz
    ├── 412fc5644153189cbe11097134b7d81c3a55cbfa.nq.gz
    ├── 419107f9102608a1acf5637769f448ade44334d6.nq.gz
    ├── 41a8bceb5a778c1b32e5a3487e7ae7513bcd4cc4.nq.gz
    ├── 429b9fceb8975a640b4c95e170ee8a3a05a09961.nq.gz
    ├── 42d7b923fb12dc3b2bcfe05ee1d5142fe355384b.nq.gz
    ├── 42e783d5fa0a3c129c693d431cb6142917295e73.nq.gz
    ├── 43496b87fcb7f6a3d039ca73d1032f1c520fa90a.nq.gz
    ├── 436eb2d643c22d997f06938544d1ee5dc1759784.nq.gz
    ├── 4371f6c14cfe82d9addc7493e95b5b213c082560.nq.gz
    ├── 44561e2ff381043538ac53f0de599529ad24230c.nq.gz
    ├── 448347352bd0ea2a68af8c17d311a6d2b49e7dcb.nq.gz
    ├── 44bdbe8d500a06324a4626e422f784a176451859.nq.gz
    ├── 45345673b8bef30ff36c63fa2ae0f5aef2f921fc.nq.gz
    ├── 45664631069fdeecb6399576b14357cfdf60c309.nq.gz
    ├── 4581ca9a8c41da54db58bcdb5d5076ff98a56518.nq.gz
    ├── 460074797942905e51397dba893f9cf352e42c7e.nq.gz
    ├── 46a47414fee1761c018eb8f9cb3708580e358c95.nq.gz
    ├── 46e50fd4df13f38f8a47a9a32ab6f4b3415c4923.nq.gz
    ├── 471ddd4129c125c18d2762da4a05249f0bf3814e.nq.gz
    ├── 4736350a267abf7922792206c041e7f1a62cd195.nq.gz
    ├── 48350e32e1e75959cbe9bb9d704f171db714cb01.nq.gz
    ├── 48eedc2694bccfa4683fd39d9f415e376b172bf7.nq.gz
    ├── 48f0cc99bf21a5deacdafa9d37aef5fa2e7ccda4.nq.gz
    ├── 493dabf795363a9a4a5fbb16159062476631bcc7.nq.gz
    ├── 4993cc5561dc9fb7004998aa34b13047704cb51a.nq.gz
    ├── 49c3b5af54c978eca61943b5b699bd26ccdbaefe.nq.gz
    ├── 49f5d8595a764057a536527b10f6e97469b972a9.nq.gz
    ├── 4a3dc629fdb5119510b1223ff8474ab8b7cbb993.nq.gz
    ├── 4bcbbb3b31313da35eff27ae8e26fdf5dfe39876.nq.gz
    ├── 4c971b4a9f318e552cc4dcbb4f7a287c5c76ff9a.nq.gz
    ├── 4de8c15e945c7815e1d1de472ec4666ee33dccb5.nq.gz
    ├── 4dec099ae567a3ab547016ad2c051327576f1b66.nq.gz
    ├── 4e162bbf19f91a543fae7653fd61c0be5eef12b9.nq.gz
    ├── 4e467307eef438e6066ee49b1d2c7d0b4f481a94.nq.gz
    ├── 4f84d3ac01b0759fddecaeb50c2f87a82f69fb41.nq.gz
    ├── 4fb7eb7fe9482fdf1d2b60314d7010e3fac8b1f6.nq.gz
    ├── 4fd67d0d724f1cd555c24698d747db0a3f1b470d.nq.gz
    ├── 4ff72d30edd8d677a37c2eb66db0baae6a9291b4.nq.gz
    ├── 50d2de650995b261ca95b7cce5c6fdc8d50f4f07.nq.gz
    ├── 50e0e5f3ab7dd8aa8977ba14209739c4cbb5d563.nq.gz
    ├── 50f92c29f6721df3787913d09b24f19c2b7a3199.nq.gz
    ├── 5114f753a9bc5836548c44018bc0c8d528238572.nq.gz
    ├── 511f9e4193942fc804a9b98817308d4e4a9f28a9.nq.gz
    ├── 5170fef16c67e712672ee1162c24202ed3e25287.nq.gz
    ├── 5217a34b3aafb6f079dce0c81d5ae22e25e49d19.nq.gz
    ├── 53171d07098e20eb8512d49e3b5d2cb195a7702a.nq.gz
    ├── 533f61fada8fe82e2e854cb93a1412cb059a2c9e.nq.gz
    ├── 53890d9f88eb4463b6254f2486e6f8a607372f6a.nq.gz
    ├── 53d0f135abb0cb4dc12e0a031d628bdba8bd08d7.nq.gz
    ├── 53dc5e3ef6ae979365c9d75b7234c69b2142e496.nq.gz
    ├── 544c21d1a9d2739949e3493b7c5f4a29ee133137.nq.gz
    ├── 548a1e958f0899c8726773834f8a9ef70f075d7a.nq.gz
    ├── 56262236d2f939bdc2b04069e7cf41e203d61ab6.nq.gz
    ├── 575c9a6f4ab3cf98f5709d41d4cb5f80d803e733.nq.gz
    ├── 575e1ba1c4f19aef5871df403f4c6896ee6e811a.nq.gz
    ├── 5769ff1cb38a979c670dbe3a6d608481904e5a58.nq.gz
    ├── 588aaf18778e55a1ad9b1a840131c082b2978845.nq.gz
    ├── 59c3d180c19fc486cfcf416e1f5ec48e6b2cc968.nq.gz
    ├── 59f684e056b542df3dd2a29e1def3e4c46ada68a.nq.gz
    ├── 59fe6050e34bd5b9eb829ee79d6a67e583604198.nq.gz
    ├── 5a2a84c30daff30eee48c05759928899f5f01aa7.nq.gz
    ├── 5b18c8ddf0c05f218b9f1dcc792b014fff262d6c.nq.gz
    ├── 5b47c0331f921048b7483f01e970f60dd1ccdef1.nq.gz
    ├── 5bcc696d0450a7f09c8fa5d197cd9fddbe43066e.nq.gz
    ├── 5c7093a3809e880f8967855661da8a4c167cbb90.nq.gz
    ├── 5c85a904462ad4bbae19ad26c4d142d831ca464d.nq.gz
    ├── 5d00aa6667cab1192efe37e296904df72a744933.nq.gz
    ├── 5d2709017126522e704d7f90038d873d2ab5d5ba.nq.gz
    ├── 5d4d569860e185be17bcce4c6ba5c1928d57ff84.nq.gz
    ├── 5d94644cd48bfc27aa9dccc6c4863120e112ab5f.nq.gz
    ├── 5dce767d5779029ca86835a1eeadfa84fcc4004a.nq.gz
    ├── 5ee7812edbb236187b2434d8d01342f71c10b922.nq.gz
    ├── 5f780f8521927281385be5ca2b069dc98f7bd751.nq.gz
    └── 5fdc6953e5a2c4fdea9daabfa8835801744f39c9.nq.gz

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

[ansible-collections/community.docker](https://github.com/ansible-collections/community.docker)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
