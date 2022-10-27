# ⚔️ A Historical Collection of Reentrancy Attacks

[![👮‍♂️ Validate links](https://github.com/pcaversaccio/reentrancy-attacks/actions/workflows/ci.yml/badge.svg)](https://github.com/pcaversaccio/reentrancy-attacks/actions/workflows/ci.yml)
[![License: WTFPL](https://img.shields.io/badge/License-WTFPL-blue.svg)](http://www.wtfpl.net/about)

**📌 Definition of a Reentrancy Attack**

> Unsafe _external_ calls that allow malicious manipulation of the internal and/or associated external contract state(s).

**📚 Types of Reentrancy Attacks**

- Single-Function Reentrancy
- Cross-Function Reentrancy
- Cross-Contract Reentrancy

**📜 Reentrancy Attacks List**

A chronological and (hopefully) complete list of reentrancy attacks to date.

- [WETH white hat attack](https://github.com/pcaversaccio/reentrancy-attacks/issues/1#issuecomment-1188680199) – June 11, 2016 | [Exploit contract (TBD)](), [Exploit transaction (TBD)]()
- [The DAO attack](https://medium.com/@zhongqiangc/smart-contract-reentrancy-thedao-f2da1d25180c) – June 17, 2016 | [Exploit contract](https://etherscan.io/address/0xC0ee9dB1a9E07cA63E4fF0d5FB6F86Bf68D47b89), [Exploit transaction](https://etherscan.io/tx/0x0ec3f2488a93839524add10ea229e773f6bc891b4eb4794c3337d4495263790b)
- [SpankChain attack](https://medium.com/swlh/how-spankchain-got-hacked-af65b933393c) – October 9, 2018 | [Exploit contract](https://etherscan.io/address/0xc5918a927C4FB83FE99E30d6F66707F4b396900E), [Exploit transaction](https://etherscan.io/tx/0x21e9d20b57f6ae60dac23466c8395d47f42dc24628e5a31f224567a2b4effa88)
- [imBTC Uniswap pool attack](https://defirate.com/imbtc-uniswap-hack) – April 18, 2020 | [Exploit contract](https://etherscan.io/address/0xBD2250D713bf98b7E00c26E2907370aD30f0891a), [Exploit transaction](https://etherscan.io/tx/0x9437dde6c06a20f6d56f69b07f43d5fb918e6c57c97e1fc25a4162c693f578aa)
- [Lendf.Me attack](https://slowmist.medium.com/slowmist-details-of-lendf-me-reentrancy-attack-3e168ab5f2b1) – April 19, 2020 | [Exploit contract](https://etherscan.io/address/0x538359785a8D5AB1A741A0bA94f26a800759D91D), [Exploit transaction](https://etherscan.io/tx/0xced7ca813081fb594181469001a6aff629c5874bd672cca44075d3ec768db664)
- [Akropolis attack](https://peckshield.medium.com/akropolis-incident-root-cause-analysis-c11ee59e05d4) – November 12, 2020 | [Exploit contract](https://etherscan.io/address/0xe2307837524Db8961C4541f943598654240bd62f), [Exploit transaction](https://etherscan.io/tx/0xe1f375a47172b5612d96496a4599247049f07c9a7d518929fbe296b0c281e04d)
- [ValueDeFi attack](https://inspexco.medium.com/value-defis-invalid-share-calculation-exploit-in-depth-analysis-1c8f97c1416e) – May 7, 2021 | [Exploit contract](https://bscscan.com/address/0x4269e4090FF9dFc99D8846eB0D42E67F01C3AC8b), [Exploit transaction](https://bscscan.com/tx/0x9dab872598ee7a6290ed7d6f3a903f44a8794246c3089cc91d6cfb69be4d58b4)
- [Rari Capital attack](https://nipunp.medium.com/5-8-21-rari-capital-exploit-timeline-analysis-8beda31cbc1a) – May 8, 2021 | [Exploit contract](https://etherscan.io/address/0x2f755e8980f0c2E81681D82CCCd1a4BD5b4D5D46), [Exploit transaction](https://etherscan.io/tx/0x1655592eda3ebbba7c530ab3327daeae95fa95d05c3dec40338471245da10cfe)
- [BurgerSwap attack](https://quillhashteam.medium.com/burgerswap-flash-loan-attack-analysis-888b1911daef) – May 27, 2021 | [Exploit contract](https://bscscan.com/address/0xAE0F538409063e66ff0E382113cb1a051fC069cd), [Exploit transaction](https://bscscan.com/tx/0xac8a739c1f668b13d065d56a03c37a686e0aa1c9339e79fcbc5a2d0a6311e333)
- [Iron Finance attack](https://thedefiant.io/not-just-a-bank-run-new-evidence-shows-iron-finance-crashed-due-to-code-exploit) – June 16, 2021 | [Exploit contract](https://polygonscan.com/address/0xa37DD1f62661EB18c338f18Cf797cff8b5102d8e), [Exploit transaction](https://polygonscan.com/tx/0x05d5c121251cb7cea91a89aaa164451639acb328b4a0a8001470aea531d77a7a)
- [PolyDEX attack](https://polydex.medium.com/plx-locker-smart-contract-incident-post-mortem-75342124a3e8) – June 20, 2021 | [Exploit contract](https://polygonscan.com/address/0x287F8Cf077666e60e2d238bF77a525051481D769), [Exploit transaction](https://polygonscan.com/tx/0x6b3f057683083d7f0a25e4d3898ca68308cfe2335878143466f84b3003ebe3a2)
- [DeFiPie attack](https://medium.com/defipie/hacking-investigation-85e07454f1c9) – July 12, 2021 | [Exploit contract](https://bscscan.com/address/0x6d741523F1FcBa87Bb8ddA1Ab85D765a9544E6a6), [Exploit transaction](https://bscscan.com/tx/0x45f6f792638d114f31f6608dca4c79b1216bd5c7c45218a5fd8f1c2e309c6d75)
- [Sanshu Inu attack](https://sanshunft.medium.com/woofdate-2-2-0-keanu-compensation-mfund-rebase-update-bcac09707e19) – July 20, 2021 | [Exploit contract](https://etherscan.io/address/0xe30DC9B3c29534E9b4e9A166c2f44411163aD59F), [Exploit transaction](https://etherscan.io/tx/0x00edd68087ee372a1b6e05249cc6c992bb7b8478cc0ddc70c2a1453428285808)
- [XSURGE attack](https://medium.com/@Knownsec_Blockchain_Lab/knownsec-blockchain-lab-comprehensive-analysis-of-xsurge-attacks-c83d238fbc55) – August 16, 2021 | [Exploit contract](https://www.bscscan.com/address/0x1514AAA4dCF56c4Aa90da6a4ed19118E6800dc46), [Exploit transaction](https://www.bscscan.com/tx/0x7e2a6ec08464e8e0118368cb933dc64ed9ce36445ecf9c49cacb970ea78531d2)
- [C.R.E.A.M. Finance attack](https://inspexco.medium.com/reentrancy-attack-on-cream-finance-incident-analysis-1c629686b6f5) – August 30, 2021 | [Exploit contract](https://etherscan.io/address/0x2E95B91FA678b47660aBA811B74a28Ca1F4ED111), [Exploit transaction](https://etherscan.io/tx/0xd7ec3046ec75efbd04b3eea8752a8a6373a92c0dd813d08b655661054d3239c5)
- [Grim Finance attack](https://rekt.news/grim-finance-rekt) – December 18, 2021 | [Exploit contract](https://ftmscan.com/address/0xb08ccb39741d746dd1818641900f182448eb5e41), [Exploit transaction](https://ftmscan.com/tx/0x19315e5b150d0a83e797203bb9c957ec1fa8a6f404f4f761d970cb29a74a5dd6)
- [Visor Finance attack](https://sharkteam.org/report/analysis/20211223001A_en.pdf) – December 21, 2021 | [Exploit contract](https://etherscan.io/address/0x10C509AA9ab291C76c45414e7CdBd375e1D5AcE8), [Exploit transaction](https://etherscan.io/tx/0x69272d8c84d67d1da2f6425b339192fa472898dce936f24818fda415c1c1ff3f)
- [HypeBears attack](https://blocksecteam.medium.com/when-safemint-becomes-unsafe-lessons-from-the-hypebears-security-incident-2965209bda2a) – February 3, 2022 | [Exploit contract](https://etherscan.io/address/0x49AB6aBd4be00Df45E5C8e8949Dd41389c34A704), [Exploit transaction](https://etherscan.io/tx/0xfa97c3476aa8aeac662dae0cc3f0d3da48472ff4e7c55d0e305901ec37a2f704)
- [Bacon Protocol attack](https://coincodecap.com/bacon-protocol-hacked-reportedly-1m-lost) – March 5, 2022 | [Exploit contract](), [Exploit transaction]()
- [Paraluni attack](https://coincodecap.com/paraluni-hacked-reportedly-1-7m-lost) – March 13, 2022 | [Exploit contract](), [Exploit transaction]()
- [Hundred Finance attack](https://twitter.com/danielvf/status/1503756428212936710) – March 15, 2022 | [Exploit contract](), [Exploit transaction]()
- [Agave Finance attack](https://twitter.com/Mudit__Gupta/status/1503783633877827586) – March 16, 2022 | [Exploit contract](), [Exploit transaction]()
- [Revest Finance attack](https://slowmist.medium.com/revest-finance-incident-analysis-6fcd9b6be207) – March 27, 2022 | [Exploit contract](), [Exploit transaction]()
- [Voltage Finance attack](https://rekt.news/voltage-finance-rekt) – March 31, 2022 | [Exploit contract](), [Exploit transaction]()
- [BNB Brokers attack](https://twitter.com/BlockSecTeam/status/1519249933832171520) – April 27, 2022 | [Exploit contract](), [Exploit transaction]()
- [Fei Protocol attack](https://certik.medium.com/fei-protocol-incident-analysis-8527440696cc) – April 30, 2022 | [Exploit contract](), [Exploit transaction]()
- [Bistroo attack](https://bistroo.medium.com/post-incident-review-bist-single-asset-staking-binancesmartchain-security-breach-5194590605f) – May 7, 2022 | [Exploit contract](), [Exploit transaction]()
- [Ownly attack](https://twitter.com/ownlyio/status/1524362090940895234) – May 10, 2022 | [Exploit contract](), [Exploit transaction]()
- [Omni attack](https://twitter.com/BlockSecTeam/status/1546141457933025280) – July 10, 2022 | [Exploit contract](), [Exploit transaction]()
- [Thunder Brawl attack](https://twitter.com/peckshield/status/1575890733373849601) – September 30, 2022 | [Exploit contract](), [Exploit transaction]()

> Some of the exploits carried out involve multiple separate transactions as well as multiple exploit contracts. I have listed the most critical exploit contract and the most devastating exploit transaction for each attack.

## 💢 Disclaimer

![nobody-reads-ever-a-fucking-disclaimer](https://user-images.githubusercontent.com/25297591/167394075-1813e258-3b03-4bc8-9305-69126a07d57e.png)
