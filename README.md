<div align="center">
  <img alt="starknet logo" src="./assets/starknet.png" width="200" >
  <h1 align="center">Awesome Starknet</h1>
  <p align="center">
    <a href="https://github.com/sindresorhus/awesome">
      <img alt="awesome list badge" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg">
    </a>
    <a href="#buildstatus">
      <img alt="build status badge" src="https://github.com/gakonst/awesome-starknet/workflows/Build/badge.svg">
    </a>
    <a href="https://github.com/gakonst/awesome-starknet/graphs/contributors">
      <img alt="GitHub contributors" src="https://img.shields.io/github/contributors/gakonst/awesome-starknet">
    </a>
    <a href="http://makeapullrequest.com">
      <img alt="pull requests welcome badge" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat">
    </a>
  </p>

  <p align="center">A curated list of awesome <a href="https://medium.com/starkware/starknet-alpha-is-coming-to-mainnet-b825829eaf32">Starknet</a> resources, libraries, tools and more.</p>

  <p align="center">This list is based on Cairo 1. You can still access the previous archived <a href="CAIRO_0_ARCHIVE.md">Cairo 0 Awesome Starknet</a>.</p>

  <p align="center">Please check the <a href="CONTRIBUTING.md">contribution guidelines</a> for information on formatting and writing pull requests.</p>

</div>

### Contents

- [Resources](#resources)
    - [Official](#official)
    - [Tutorials and Examples](#tutorials-and-examples)
    - [Articles and Blogs](#articles-and-blogs)
    - [Papers](#papers)
    - [Cryptography and maths](#cryptography-and-maths)
    - [Audits](#audits)
    - [Wallet](#wallet)
    - [Block explorers](#block-explorers)
    - [Bridges and on-ramps](#bridges-and-on-ramps)
- [Ecosystem](#ecosystem)
    - [Dapps](#dapps)
    - [Community](#community)
    - [Governance](#governance)
    - [Events](#events)
    - [Open-source and jobs](#open-source-and-jobs)
- [Additional developer resources](#additional-developer-resources)
    - [Developer Tools](#developer-tools)
    - [Starknet SDKs](#starknet-sdks)
    - [Cairo VMs](#cairo-vms)
    - [Node implementations](#node-implementations)
    - [Provers](#provers)
    - [Cairo libraries](#cairo-libraries)
    - [Dapps libraries](#dapps-libraries)
    - [Other libraries](#other-libraries)
    - [Sequencers](#sequencers)
    - [ZkEvm](#zkevm)
    - [Gaming](#gaming)
    - [AI](#ai)
    - [Storage Proofs](#storage-proofs)
    - [Security](#security)
    - [Oracles](#oracles)
    - [Indexers](#indexers)
    - [Misc](#misc)
- [Open-source projects](#open-source-projects)
    - [Defi](#defi)
    - [Gaming](#gaming-1)
    - [Governance](#governance-1)
    - [Misc](#misc-1)
- [License](#license)

## Resources

#### Official

- [Starknet Website](https://www.starknet.io/) - Official Website.
- [Starknet Documentation](https://docs.starknet.io/documentation/) - Official Documentation.
- [The Starknet Book](https://book.starknet.io/) - In-depth guide.
- [Cairo Documentation](https://www.cairo-lang.org/docs/index.html) - Official Cairo 1.0 Documentation.
- [The Cairo Book](https://book.cairo-lang.org/) - In-depth guide to Cairo.
- [YouTube channel](https://www.youtube.com/@starkware_ltd) - Official StarkWare YouTube channel.
- [Roadmap](https://www.starknet.io/en/roadmap) - What’s coming next for Starknet.
- [SNIPs](https://github.com/starknet-io/SNIPs) - Starknet Improvement Proposals (SNIPs) repository.
- [starkware-libs/cairo](https://github.com/starkware-libs/cairo) - Official Cairo Github repository.

#### Tutorials and Examples

- [Starknet by Example](https://starknet-by-example.voyager.online/) - Collection of examples from beginner concepts to advanced.
- [Cairo by Example](https://cairo-by-example.com/) - Introduction to Cairo, with simple examples.
- [Starklings](https://github.com/shramee/starklings-cairo1) - Interactive tutorial to get you up and running with Cairo v1 and Starknet.
- [Node Guardians](https://nodeguardians.io/dev-hub?s=devhub-campaigns) - Cairo 1.0 interactives tutorials.
- [Starknet messaging tutorial](https://github.com/glihm/starknet-messaging-dev) - Detailed tutorial to test messaging with Anvil and Katana.
- [WTF Starknet](https://github.com/WTFAcademy/WTF-Starknet) - English and Chinese tutorials.
- [Starknet Lesson](https://www.starknet-lesson.com) - The latest and best Cairo course classroom.

#### Articles and Blogs

- [Starknet Blog Posts](https://www.starknet.io/en/posts) - Official blog.
- [Developers Blog](https://www.starknet.io/en/posts/developers) - Official Developers Blog.
- [Starknet research hub](https://starknet-research.beehiiv.com/) - The place to learn more about the Starket ecosystem and stay-up-to-date with the latest news.
- [Cairopractice](https://cairopractice.com/) - Cairo blog.

#### Papers

- [Cairo – a Turing-complete STARK-friendly CPU architecture](https://eprint.iacr.org/2021/1063.pdf) - Cairo Whitepaper
- [A verified algebraic representation of Cairo program execution](https://arxiv.org/abs/2109.14534) -
  Proof Cairo's soundness using the
  [Lean proof assistant](<https://en.wikipedia.org/wiki/Lean_(proof_assistant)>).

#### Cryptography and maths

- Vitalik's STARKs series.
  - [STARKs, Part I: Proofs with Polynomials](https://vitalik.eth.limo/general/2017/11/09/starks_part_1.html)
  - [STARKs, Part 2: Thank Goodness it’s FRI-day](https://vitalik.eth.limo/general/2017/11/22/starks_part_2.html)
  - [STARKs, Part 3: Into the Weeds](https://vitalik.eth.limo/general/2018/07/21/starks_part_3.html)
- [Video: zk-STARKs Uncovered](https://www.youtube.com/watch?v=jg9KSNOO2XY) - Eli Ben-Sasson's Intense Masterclass, Basecamp Cohort.
- [Video: STARK 101 Workshop](https://www.youtube.com/playlist?list=PLcIyXLwiPilWoXrDbmwHPxaH8Gxk5I_fG)
- [Video: Stark @ Home](https://www.youtube.com/playlist?list=PLcIyXLwiPilUFGw7r2uyWerOkbx4GFMXq)
- [STARK Math: The Journey Begins](https://medium.com/starkware/stark-math-the-journey-begins-51bd2b063c71) - Starkware's series of blog posts explaining the theory behind STARKs.
  - [Arithmetization I](https://medium.com/starkware/arithmetization-i-15c046390862)
  - [Arithmetization II](https://medium.com/starkware/arithmetization-ii-403c3b3f4355)
  - [Low Degree Testing](https://medium.com/starkware/low-degree-testing-f7614f5172db)
  - [A Framework for Efficient STARKs](https://medium.com/starkware/a-framework-for-efficient-starks-19608ba06fbe)
- [ethSTARK Documentation](https://eprint.iacr.org/2021/58) - Computational integrity of STARKs explanation.
- [STARK Paper](https://starkware.co/wp-content/uploads/2022/05/STARK-paper.pdf)
- [FRI Protocol](https://eccc.weizmann.ac.il/report/2017/134/)
- [DEEP-FRI Protocol](https://arxiv.org/abs/1903.12243)
- [Aurora](https://starkware.co/wp-content/uploads/2022/05/Aurora-Transparent-Succinct-Arguments-for-R1CS.pdf) - Transparent Succinct Arguments for R1CS.
- [STARK: Endgame](https://starkware.co/resource/stark-endgame/)

#### Audits

- [Audit providers](https://docs.starknet.io/documentation/tools/audit/)
- [Nethermind Audits](https://www.nethermind.io/smart-contract-audits)

#### Wallet

- [Braavos](https://braavos.app/)
- [Argent X](https://www.argent.xyz/argent-x/)
- [Metamask Snap](https://snaps.consensys.io/starknet)

#### Block explorers

- [Voyager](https://voyager.online)
- [Starkscan](https://starkscan.co/)
- [Viewblock](https://viewblock.io/starknet)
- [OKLink](https://www.oklink.com/starknet)
- [Stark Compass](https://github.com/lambdaclass/stark_compass_explorer) - Open source explorer

#### Bridges and on-ramps

- [Starkgate](https://starkgate.starknet.io/) - The official bridge.
- [Bridges and on-ramps](https://www.starknet.io/en/ecosystem/bridges-and-onramps) - List of bridges and on-ramps.

## Ecosystem

#### Dapps

- [Starknet Ecosystem](https://starknet-ecosystem.com) -
  The [community-driven](https://github.com/419Labs/starknet-ecosystem.com) initiative to showcase projects and teams building.
- [Dappland](https://www.dappland.com/) - Discover dapps.

#### Community

- [Starknet Community Forum](https://community.starknet.io/) - Official forum.
- [Discord](https://starknet.io/discord) - Official Discord.
- [Twitter](https://twitter.com/Starknet) - Official tarknet Twitter.
- [Telegram Core Stars](https://t.me/sncorestars) - Cairo Core Stars Pharaohs group.
- [Online communities](https://www.starknet.io/en/community/online-communities) - List of online communities.

#### Governance

- [Starknet Governance](https://www.starknet.io/en/community/governance) - Official Governance page.
- [Snapshot proposals](https://snapshot.org/#/starknet.eth) - Snapshot proposals.
- [Community discussions](https://community.starknet.io/c/governance/15)
- [Starknet Foundation](https://www.starknet.io/en/posts/governance/welcome-to-the-world-starknet-foundation) - Introduction to the Starknet Foundation.
- [Starknet Foundation committees](https://www.starknet.io/en/posts/foundation/the-starknet-foundation-meet-the-committees) - Introduction to the Starknet Foundation committees.

#### Events

- [Upcoming events](https://www.starknet.io/en/events) - List of upcoming events.
- [StarknetCC](https://www.starknet.cc/) - Starknet Community Conference.
- [Starknet Summit](https://summit23.starknet.io/)

#### Open-source and jobs

- [Keep Starknet Strange](https://github.com/keep-starknet-strange) - Starkware Exploration team to kickstart exciting projects.
- [OnlyDust](https://www.onlydust.xyz/) - Contribute to innovative projects.
- [Ecosystem Jobs board](https://www.starknet.io/en/jobs) - Find a job with the best teams.
- [Nethermind Jobs](https://www.nethermind.io/open-roles) - Join Nethermind's remote-first, close-knit crew of builders and tech professionals.
- [Equilibrium Labs](https://equilibrium.co/join-us) - Explore the R&D company behind [Pathfinder](#node-implementations).

## Additional developer resources

#### Developer Tools

- [Starknet developer tools](https://docs.starknet.io/documentation/tools/devtools/) - Official developer tools documentation.
- [Setting up your environment](https://docs.starknet.io/documentation/quick_start/environment_setup/) - Environment setup guide.
- [Starkli](https://book.starkli.rs) - The recommended CLI.
- [Scarb](https://docs.swmansion.com/scarb) - The recommended build toolchain and package manager.
- [Vscode Cairo extension](https://marketplace.visualstudio.com/items?itemName=starkware.cairo1) - Official Cairo extension for VSCode with diagnostics, go-to-definition, completion and more.
- [Vim plugin for Scarb projects](https://github.com/swan-of-bodom/scarb-vim)
- [Starknet Foundry](https://foundry-rs.github.io/starknet-foundry/) - Toolchain for smart contracts development, testing and deployment.
  - [Starknet Foundry Forge Template](https://github.com/foundry-rs/starknet_forge_template)
- [Starknet Remix](https://remix.ethereum.org/?#activate=Starknet) - The official Starknet plugin for Remix, a browser-based IDE without the need for any installation.
- [Starknet Devnet](https://github.com/0xSpaceShard/starknet-devnet-rs) - Local testnet.
- [Katana](https://book.dojoengine.org/toolchain/katana/overview) - High performance sequencer that can be used as a local testnet.
- [Starknet Hardhat plugin](https://github.com/Shard-Labs/starknet-hardhat-plugin) - The Starknet Hardhat plugin.
  - [starknet-hardhat-example](https://github.com/0xSpaceShard/starknet-hardhat-example)
- [docker-cairo](https://github.com/xJonathanLEI/docker-cairo) - Multi-arch Docker images with Cairo binaries.
- [create-starknet-dapp](https://github.com/CerberusChaos/create-starknet-dapp) - Command-line tool designed to help developers quickly create Starknet Dapp projects. It offers multiple project templates.

#### Starknet SDKs

- [starknet.js](https://www.starknetjs.com/) - Javascript library.
- [starknet.py](https://github.com/software-mansion/starknet.py) - Python library.
- [starknet-rs](https://github.com/xJonathanLEI/starknet-rs) - Rust library.
  - [starknet-rs-example](https://github.com/xJonathanLEI/starknet-rs/tree/master/examples)
- [starknet.go](https://github.com/NethermindEth/starknet.go) - Golang library.
- [starknet-jvm](https://github.com/software-mansion/starknet-jvm) - Library for JVM languages (java, kotlin and others).
- [starknet.dart](https://starknetdart.dev/) - Dart library for mobile.

#### Cairo VMs

- [cairo-vm](https://github.com/lambdaclass/cairo-vm) - Rust implementation of the Cairo VM.
- [cairo-vm-go](https://github.com/NethermindEth/cairo-vm-go) - Golang implementation of the Cairo VM.
- [cairo-vm_in_go](https://github.com/lambdaclass/cairo-vm_in_go) - Another Golang implementation.
- [cairo-zig](https://github.com/keep-starknet-strange/cairo-zig) - Zig implementation of the Cairo VM.

#### Node implementations

- [Juno](https://github.com/NethermindEth/juno) - Golang full-node implementation.
- [Papyrus](https://github.com/starkware-libs/papyrus) - Rust full-node implementation.
- [Pathfinder](https://github.com/eqlabs/pathfinder) - Rust full-node implementation.
- [Deoxys](https://github.com/KasarLabs/deoxys) - Substrate full-node implementation.
- [Beerus](https://github.com/keep-starknet-strange/beerus) - Rust light-client implementation.

#### Provers

- [StarkEx](https://github.com/starkware-libs/starkex-contracts) - Starkware verifier.
- [STONE](https://github.com/starkware-libs/stone-prover) - Prover and verifier for STARKs
- [sandstorm](https://github.com/andrewmilson/sandstorm) - Cairo prover powered by miniSTARK.
- [awesome-prover-mechanisms](https://github.com/niluferokay/awesome-prover-mechanisms) - Awesome list of resources for prover mechanisms in the zkrollup ecosystem.

#### Cairo libraries

- [OpenZeppelin contracts-cairo](https://docs.openzeppelin.com/contracts-cairo/) - OpenZeppelin Contracts in Cairo.
- [Alexandria](https://github.com/keep-starknet-strange/alexandria) - Collection of useful algorithms and data structures implemented in Cairo.
- [Garaga](https://github.com/keep-starknet-strange/garaga) - Efficient pairing library using polynomial representation of field elements.
- [Herodotus cairo-lib](https://github.com/HerodotusDev/cairo-lib) - Set of Data Structures, Encoding, Hashers and Utilities for Cairo.
- [xoroshiro-cairo](https://github.com/milancermak/xoroshiro-cairo) - Xoroshiro PRNG implementation in Cairo.
- [graffiti](https://github.com/milancermak/graffiti) - Library for building XML based documents (SVG, HTML, RSS).
- [Origami](https://github.com/dojoengine/origami) - Dojo's gaming library.

#### Cairo plugins

- [hello-cairo-plugin](https://github.com/piwonskp/hello-cairo-plugin) - Example Cairo plugin.

#### Dapps libraries

- [Starknet React](https://github.com/auclantis/starknet-react) - React hooks library.
- [get-starknet](https://github.com/starknet-io/get-starknet) - Starknet's official wallet SDK for developers.
- [Starknetkit](https://www.starknetkit.com/docs/getting-started) - The wallet SDK for developers on Starknet.
- [vue-stark-boil](https://github.com/dontpanicdao/vue-stark-boil) - Vue.js boilerplate.
- [starknet-url](https://github.com/myBraavos/starknet-url) - Build & parse Starknet URLs.
- [starknet-deeplink](https://github.com/myBraavos/starknet-deeplink) - Starknet deeplink generator.
- [Starknet-Dapp-Template](https://github.com/CerberusChaos/Starknet-Dapp-Template) - Starknet Dapp Template with Next.js 14+, Tailwind CSS 3, TypeScript, DaisyUI, and Starknet-React.

#### Other libraries

- [Starknet in Rust](https://github.com/lambdaclass/starknet_in_rust#starknet) - Rust implementation of Starknet execution logic.
- [starknet-zig](https://github.com/starknet-io/starknet-zig) - Starknet library in Zig.
- [types-js](https://github.com/starknet-io/types-js) - TypeScript types.
- [types-rs](https://github.com/starknet-io/types-rs) - Rust types.
- [poseidon-rs](https://github.com/keep-starknet-strange/poseidon-rs) - Poseidon Rust library.
- [cairo_native](https://github.com/lambdaclass/cairo_native) - Compiler to convert Sierra to machine code via MLIR and LLVM.
- [tree-sitter-cairo](https://github.com/avnu-labs/tree-sitter-cairo) - Cairo 1.0 grammar for tree-sitter.
- [scure-starknet](https://github.com/paulmillr/scure-starknet) - Minimal JS implementation of Starknet cryptography.
- [wasm-cairo](https://github.com/cryptonerdcn/wasm-cairo) - Wasm bindings for Cairo.
- [starknet-abigen-rs](https://github.com/glihm/starknet-abigen-rs) - Cairo ABI parser and generator in Rust.
- [starknet-devnet-js](https://github.com/0xSpaceShard/starknet-devnet-js) - Interact with the Devnet using this JS provider.

#### Sequencers

- [Madara](https://github.com/keep-starknet-strange/madara) - Sequencer based on substrate.
- [Kraken](https://github.com/lambdaclass/starknet_stack/tree/main/sequencer) - Sequencer by LambdaClass.
- [Gomu Gomu no Gatling](https://github.com/keep-starknet-strange/gomu-gomu-no-gatling) - Benchmark tools for sequencers.

#### ZkEvm

- [Kakarot](https://www.kakarot.org/) - ZK-EVM type 3 written in Cairo.

#### Gaming

- [Dojo Engine](https://book.dojoengine.org/) - The Provable Game Engine.
  - [Awesome Dojo](https://github.com/dojoengine/awesome-dojo) - Curated list of awesome Dojo resources.
  - [dojo-examples](https://github.com/dojoengine/dojo-examples) - Dojo examples.
- [Starknet Unity SDK](https://github.com/NethermindEth/starknet.unity)

#### AI

- [Gizatech](https://www.gizatech.xyz/)
  - [Orion](https://orion.gizatech.xyz/welcome/readme) - Provable Machine Learning framework.
  - [Tic-Tac-Stark](https://github.com/gizatechxyz/Tic-Tac-Stark) - Provable Tic-Tac-Toe AI model using Orion and Cairo.
- [neural-network-cairo](https://github.com/franalgaba/neural-network-cairo) - Neural Network implementation from scratch for MNIST.
- [drive-ai](https://github.com/cartridge-gg/drive-ai) - Self driving car AI with Dojo.

#### Storage Proofs

- [Herodotus](https://docs.herodotus.dev/) - Secure On-Chain Data Access Solutions using Storage Proofs.

#### Security

- [Caracal](https://github.com/crytic/caracal) - Static Analyzer for smart contracts.
- [semgrep-cairo-rules](https://github.com/avnu-labs/semgrep-cairo-rules) - Semgrep rules for Cairo 1.0.
- [Toth](https://github.com/FuzzingLabs/thoth) - Security toolkit (bytecode analyzer, disassembler, decompiler, symbolic execution, SBMC).
- [Underhanded Cairo](https://cairopractice.com/tags/security/)
- [An introduction to Cairo 1 smart-contracts security](https://antoinemecker.medium.com/an-introduction-to-cairo-1-smart-contracts-security-1f96792b998a)
- [Under the hood of Cairo 1.0: Exploring Sierra](https://medium.com/nethermind-eth/under-the-hood-of-cairo-1-0-exploring-sierra-7f32808421f5)
- [Adventures with Account Abstraction – Risks and Mitigations in \_\_validate\_\_](https://braavos.app/adventures-with-account-abstraction-failed-transactions/)
- [Auditing Cairo 1.0 Contracts](https://extropy-io.medium.com/auditing-cairo-1-0-contracts-9cfdf479924a)
- [Video: Cairo Security (Peteris Erins)](https://www.youtube.com/watch?v=9CIhHNrliW4)
- [Awesome Starknet Security](https://github.com/amanusk/awesome-starknet-security) - Curated list of awesome Starknet security resources.

#### Oracles

- [Pragma](https://www.pragmaoracle.com/) - Decentralized, transparent and composable oracle network.

#### Indexers

- [Checkpoint](https://checkpoint.fyi/#/) - GraphQL indexing library.
- [Apibara](https://www.apibara.com/) - Open source indexer.
- [dipdup-io/starknet-indexer](https://github.com/dipdup-io/starknet-indexer)

#### Misc

- [Cairo Utils](https://cairo-utils-web.vercel.app/) - Web-based utility converter.
- [StarkTx](https://starktx.info/) - StarkTx Transaction Decoder.
- [rika-chan](https://github.com/kariy/rika-chan) - CLI toolkit.
- [jin](https://github.com/kariy/jin) - Contract storage dumper.
- [kipt](https://github.com/glihm/kipt) - Collections of Lua scripts to manage contracts.
- [rifle](https://github.com/rkdud007/rifle) - Blocktime estimator in Rust.
- [crypto-ecosystems/starknet](https://github.com/electric-capital/crypto-ecosystems/blob/master/data/ecosystems/s/starknet.toml) - Starknet raw ecosystem data.

## Open-source projects

#### Defi

- [Satoru](https://github.com/keep-starknet-strange/satoru) - Synthetics platform, inspired by GMX v2 design.
  - [zohal-interface](https://github.com/Zohal-Starknet/zohal-interface) - Zohal's Satoru interface.
- [YAS](https://github.com/lambdaclass/yet-another-swap) - YAS is Yet Another Swap.
- [Avnu Contracts](https://github.com/avnu-labs/avnu-contracts-v2) - Liquidity aggregator written in Cairo.
  - [Avnu SDK](https://github.com/avnu-labs/avnu-sdk)
- [Cygnus](https://github.com/CygnusDAO/cygnus-starknet-cairo1) - Cygnus contract.
- [Carmine Protocol](https://github.com/CarmineOptions/carmine-protocol) - Carmine Options AMM.
- [10kswap Contracts](https://github.com/10k-swap/10k_swap-contracts) - Decentralized ZK Rollup AMM.
- [ZkLend v1](https://github.com/zkLend/zklend-v1-core) - ZkLend v1 core contracts.

#### Gaming

- [Bibliotheca DAO](https://github.com/BibliothecaDAO)
  - [Realms World](https://github.com/BibliothecaDAO/RealmsWorld) - Realms Autonomous World.
  - [Eternum](https://github.com/BibliothecaDAO/eternum)
  - [Loot Survivor](https://github.com/BibliothecaDAO/loot-survivor) - Onchain arcade.
- [Roll Your Own](https://github.com/cartridge-gg/rollyourown)
- [Stark-lander](https://github.com/dojoengine/stark-lander)
- [PixeLAW](https://github.com/pixelaw/game)
- [Tsubasa](https://github.com/keep-starknet-strange/tsubasa)

#### Governance

- [Carmine Governance](https://github.com/CarmineOptions/governance) - Carmine Governance contracts.

#### Infrastructure

- [Nori](https://github.com/keep-starknet-strange/nori) - RPC request router, proxy and load balancer.

#### Misc

- [Tokei](https://github.com/starknet-io/tokei) - ERC20 token streaming protocol.
- [Focus Tree](https://github.com/focustree/contracts) - Focus Tree Contracts.
- [Starknet.id](https://github.com/starknet-id) - On-chain identity.
- [Carbon Protocol](https://github.com/Carbonable/carbon-protocol) - Carbon Protocol written in Cairo.
- [StarkRevoke](https://github.com/yusufferdogan/STARKREVOKE) - Revoke your ERC20 and ERC721 approvals.
- [Batchor](https://github.com/keep-starknet-strange/batchor) - Batch your ERC20 transfers with a CSV file.

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law,
Keep Starknet Strange has waived all copyright
and related or neighboring rights to this work.
