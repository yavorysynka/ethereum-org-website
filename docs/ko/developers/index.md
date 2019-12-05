---
title: 개발자 가이드
meta:
  - 
    name: og:title
    content: 개발자 가이드 | 이더리움
  - 
    property: og:title
    content: Ethereum for Developers
  - 
    property: og:description
    content: Guides, resources, and tools for developers building on Ethereum.
lang: ko
sidebar: auto
sidebarDepth: 0
---

# 개발자 리소스 {#developer-resources}

<div class="featured">이더리움 위에서 개발하는 개발자들을 위한 가이드와 개발 도구 그리고 각종 자료를 다룹니다.</div>

## 시작하면서 {#getting-started}

**만약 당신이 이더리움을 처음 개발해보신다면, 여기 제대로 찾아오셨습니다.** 이더리움 커뮤니티에 의해 쓰여진 이 가이드들은 이더리움 기술 스택에 대한 기초부터 기존의 앱 개발과는 다를지도 모르는 새로운 개념들을 소개해 줄 거에요.

좀 더 준비운동이 필요하시다고요? 그럼 [ethereum.org/ko/learn](/ko/learn/)로 들어와 주세요.

이더리움 가상 머신(EVM)에서 작동되는 프로그램들은 흔히 "스마트 컨트랙트(smart contract)"라고 불립니다. 이더리움 위에서 쓰여지는 스마트 컨트랙트 언어로는 **Solidity(솔리디티)** 와 **Vyper(바이퍼)** 가 있지만, [다른 언어들도 매우 활발하게 개발되고 있습니다](https://github.com/ConsenSys/ethereum-developer-tools-list#smart-contract-languages).

**Helpful Resources**

- [이더리움 쫓아가기](https://medium.com/@mattcondon/getting-up-to-speed-on-ethereum-63ed28821bbe) _Aug 7, 2017 - Matt Condon_
- [이더리움 In Depth, 파트 1](https://blog.zeppelin.solutions/ethereum-in-depth-part-1-968981e6f833) _May 11, 2018 - Facu Spagnuolo_
- [이더리움 In Depth, 파트 2](https://blog.zeppelin.solutions/ethereum-in-depth-part-1-968981e6f833) _May 11, 2018 - Facu Spagnuolo_
- [이더리움 개발 연습, 파트 1-5](https://hackernoon.com/ethereum-development-walkthrough-part-1-smart-contracts-b3979e6e573e) _Jan 14, 2018 - dev_zl_
- [이더리움 101, Parts 1-7](https://kauri.io/collection/5bb65f0f4f34080001731dc2/ethereum-101) _Feb 13, 2019 - Wil Barnes_
- [풀스택 Hello World 투표 이더리움 Dapp 튜토리얼 ](https://medium.com/@mvmurthy/full-stack-hello-world-voting-ethereum-dapp-tutorial-part-1-40d2d0d807c2) _Jan 18, 2017 - Mahesh Murthy_
- [마스터링 이더리움 - 온라인으로 무료로 제공되는 포괄적인 교과서](https://github.com/ethereumbook/ethereumbook) _Dec 1, 2018 - Andreas Antonopoulos & Gavin Wood_
- [이더리움 개발자 포탈 - 이더리움 개발을 시작할 때 필요한 모든 것](https://ethereum.consensys.net/ethereum-dev-portal) _Updated often - ConsenSys_
- [솔리디티 컨트랙트를 해부해보면서](https://blog.zeppelin.solutions/deconstructing-a-solidity-contract-part-i-introduction-832efd2d7737) _Aug 13, 2018 - Alejandro Santander & Leo Arias_
- [풀스택 Dapp 튜토리얼 시리즈 ](https://kauri.io/collection/5b8e401ee727370001c942e3) _Updated Often - Joshua Cassidy_

## 스마트 컨트랙트 언어들 {#smart-contract-languages}

블록 탐색기는 특정 거래, 블록, 컨트랙트 및 기타 온체인(on-chain) 활동에 대한 정보를 검색하여 이더리움 블록체인(테스트넷 포함)을 탐색할 수 있게 해주는 서비스입니다.

이더리움 커뮤니티는 여러 개의 테스트넷을 관리합니다. 테스트넷은 개발자들이 이더리움 메인넷에 배포하기 전, 애플리케이션을 여러 가지 다른 조건하에 테스트하는 것에 사용됩니다.

- [개발문서](https://solidity.readthedocs.io)
- [깃허브](https://github.com/ethereum/solidity/)
- [솔리디티 깃터 채팅방](https://gitter.im/ethereum/solidity/)

이더리움 네트워크는 호환 가능한 클라이언트 소프트웨어를 실행하는 수많은 노드로 구성되어 있습니다. 대부분의 노드는 [ 게스(Geth) ](https://geth.ethereum.org/) 또는 [ 패리티(Parity)](https://www.parity.io/ethereum/) 클라이언트를 구동하고 있으며 각각 니즈에 따라 다양한 방식으로 구성되어 사용할 수 있습니다.

- [개발문서](https://vyper.readthedocs.io)
- [깃허브](https://github.com/ethereum/vyper)
- [바이퍼 깃터 채팅방](https://gitter.im/ethereum/vyper)

**Looking for other options?**

- [이더리움 개발자 툴 리스트 #스마트 컨트랙트 언어들(SmartContractLanguages)](https://github.com/ConsenSys/ethereum-developer-tools-list#smart-contract-languages)

## Language Specific Resources {#language-specific-resources}

We're building a suite of language-specific landing pages for developer to learn about Ethereum in their preferred programming language.

- [홈페이지](/java/)
- [깃허브](/python/)
- [Ethereum for JavaScript developers](/javascript/)
- [Ethereum for Go developers](/golang/)
- [Ethereum for Rust developers](/rust/)
- [Ethereum for .NET developers](/dot-net/)
- More coming soon! Don't see your language here? [Open up an issue](https://github.com/ethereum/ethereum-org-website/issues/new/choose)!

## Developer Tools {#developer-tools}

Ethereum has a large and growing number of tools to help developers build, test, and deploy their applications. Below are the most popular tools to get you started. If you want to dive deeper, check out this [comprehensive list](https://github.com/ConsenSys/ethereum-developer-tools-list).

### Frameworks {#frameworks}

**Truffle -** **_A development environment, testing framework, build pipeline, and other tools._**

- [깃허브](https://www.trufflesuite.com/)
- [개발문서](https://github.com/trufflesuite/truffle)

**Embark -** **_A development environment, testing framework, and other tools integrated with Ethereum, IPFS, and Whisper._**

- [홈페이지](https://embark.status.im/docs/)
- [깃허브](https://github.com/embark-framework/embark)

**Waffle -** **_A framework for advanced smart contract development and testing (based on ethers.js)._**

- [개발문서](https://getwaffle.io/)
- [깃허브](https://github.com/EthWorks/Waffle)

**Etherlime -** **_Ethers.js based framework for dapp development (Solidity & Vyper), deployment, debugging, testing and more._**

- [홈페이지](https://etherlime.readthedocs.io/en/latest/)
- [깃허브](https://github.com/LimeChain/etherlime)

### Other Tools {#other-tools}

**Ethereum Grid -** **_A desktop application for downloading, configuring, and running Ethereum clients and tools._**

- [홈페이지](https://grid.ethereum.org)
- [깃허브](https://github.com/ethereum/grid)

**Buidler -** **_A task runner for Ethereum smart contract developers._**

- [이더리움 개발 도구 목록 #프레임워크(FrameWorks)](https://buidler.dev)
- [GitHub](https://github.com/nomiclabs/buidler)

**OpenZeppelin SDK -** **_The Ultimate Smart Contract Toolkit: A suite of tools to help you develop, compile, upgrade, deploy and interact with smart contracts._**

- [비주얼 스튜디오 코드](https://openzeppelin.com/sdk/)
- [애저(Azure) 블록체인 워크벤치 플러그인](https://github.com/OpenZeppelin/openzeppelin-sdk)
- [샘플 코드](https://forum.openzeppelin.com/c/sdk)

**The Graph -** **_A protocol for indexing Ethereum and IPFS data and querying it using GraphQL._**

- [홈페이지](https://thegraph.com/)
- [Graph Explorer](https://thegraph.com/explorer/)
- [Documentation](https://thegraph.com/docs/)
- [GitHub](https://github.com/graphprotocol/)
- [Discord](https://thegraph.com/discord)

**Tenderly -** **_A platform to easily monitor your smart contracts with error tracking, alerting, performance metrics, and detailed contract analytics._**

- [홈페이지](https://tenderly.dev/)
- [GitHub](https://github.com/Tenderly)
- [Discord](https://discord.gg/eCWjuvt)

**Python Tooling -** **_Variety of libraries for Ethereum interaction via Python._**

- [홈페이지](http://python.ethereum.org/)
- [web3.py GitHub](https://github.com/ethereum/web3.py)
- [web3.py Chat](https://gitter.im/ethereum/web3.py)

**Brownie -** **_Python-based development environment and testing framework._**

- [이더리움 개발 툴 리스트 #통합개발환경들(IDEs)](https://eth-brownie.readthedocs.io/en/latest/)
- [GitHub](https://github.com/iamdefinitelyahuman/brownie)

**web3j -** **_A Java/Android/Kotlin/Scala integration library for Ethereum._**

- [깃허브](https://web3j.io)
- [개발문서](https://github.com/web3j/web3j)
- [Docs](https://docs.web3j.io/)
- [Gitter](https://gitter.im/web3j/web3j)

**One Click Dapp -** **_Generate a frontend directly from ABI for fast development and testing._**

- [깃허브](https://oneclickdapp.com)
- [개발문서](https://npmjs.org/package/oneclick)
- [Remix Plugin](https://github.com/pi0neerpat/remix-plugin-one-click-dapp)
- [GitHub](https://github.com/pi0neerpat/one-click-dapp)

**Looking for other options?**

- [깃허브](https://github.com/ConsenSys/ethereum-developer-tools-list#frameworks)

## Integrated Development Environments (IDEs) {#integrated-development-environments-ides}

**Ethereum Studio -** **_Web-based IDE ideal for new developers looking to experiment with smart contracts. Ethereum Studio features multiple templates, MetaMask integration, transaction logger, and a built in-browser Ethereum Virtual Machine (EVM) to help you get started building on Ethereum as fast as possible._**

- [깃허브](https://studio.ethereum.org)
- [개발문서](https://superblocks.com/ethereum-studio)
- [GitHub](https://github.com/SuperblocksHQ/ethereum-studio)

**Visual Studio Code -** **_Professional cross-platform IDE with official Ethereum support._**

- [이더리움 개발 도구 목록 #프론트엔드이더리움API(Frontend-Ethereum-APIs)](https://code.visualstudio.com/)
- [Azure Blockchain Development Kit for Ethereum](https://marketplace.visualstudio.com/items?itemName=AzBlockchain.azure-blockchain)
- [Azure Blockchain Workbench plugin](https://azuremarketplace.microsoft.com/en-us/marketplace/apps/microsoft-azure-blockchain.azure-blockchain-workbench?tab=Overview)
- [Code samples](https://github.com/Azure-Samples/blockchain/blob/master/blockchain-workbench/application-and-smart-contract-samples/readme.md)
- [GitHub](https://github.com/microsoft/vscode)

**Remix -** **_Web-based IDE with built in static analysis, and a test blockchain virtual machine._**

- [홈페이지](https://remix.ethereum.org/)

**EthFiddle -** **_Web-based IDE that lets you write, compile, and debug your smart contract._**

- [깃허브](https://ethfiddle.com/)
- [Gitter](https://gitter.im/loomnetwork/ethfiddle)

**Looking for other options?**

- [홈페이지](https://github.com/ConsenSys/ethereum-developer-tools-list#ides)

## Frontend JavaScript APIs {#frontend-javascript-apis}

**Web3.js -** **_Ethereum JavaScript API._**

- [깃허브](https://web3js.readthedocs.io/en/1.0/)
- [GitHub](https://github.com/ethereum/web3.js/)

**Ethers.js -** **_Complete Ethereum wallet implementation and utilities in JavaScript and TypeScript._**

- [홈페이지](https://docs.ethers.io/ethers.js/html/)
- [GitHub](https://github.com/ethers-io/ethers.js/)

**light.js -** **_A high-level reactive JS library optimized for light clients._**

- [Documentation](https://paritytech.github.io/js-libs/light.js/)
- [GitHub](https://github.com/paritytech/js-libs/tree/master/packages/light.js)

**Web3-wrapper -** **_Typescript alternative to Web3.js._**

- [이더리움 개발 도구 목록 #보안도구](https://0x.org/docs/web3-wrapper#introduction)
- [GitHub](https://github.com/0xProject/0x-monorepo/tree/development/packages/web3-wrapper)

**Looking for other options?**

- [깃허브](https://github.com/ConsenSys/ethereum-developer-tools-list#frontend-ethereum-apis)

## Backend APIs {#backend-apis}

**Infura -** **_The Ethereum API as a service._**

- [깃허브](https://infura.io)
- [Documentation](https://infura.io/docs)
- [GitHub](https://github.com/INFURA)

**Cloudflare Ethereum Gateway.**

- [홈페이지](https://cloudflare-eth.com)

**Nodesmith -** **_JSON-RPC API access to Ethereum mainnet and testnets._**

- [이더리움 개발 도구 목록 #테스트도구(Testing-Tools)](https://nodesmith.io/network/ethereum/)
- [Documentation](https://nodesmith.io/docs/#/ethereum/apiRef)

**Chainstack -** **_Shared and dedicated Ethereum nodes as a service._**

- [이더스캔](https://chainstack.com)
- [블록스카우트](https://docs.chainstack.com)

## Storage {#storage}

**IPFS -** **_InterPlanetary File System is a decentralized storage and file referencing system for Ethereum._**

- [테스트 이더 파우셋](https://ipfs.io/)
- [Documentation](https://docs.ipfs.io/)
- [GitHub](https://github.com/ipfs/ipfs)

**Swarm -** **_A distributed storage platform and content distribution service for the Ethereum web3 stack._**

- [테스트 이더 파우셋](https://ethersphere.github.io/swarm-home/)
- [GitHub](https://github.com/ethersphere/swarm)

**OrbitDB -** **_A decentralized peer to peer database on top of IPFS._**

- [테스트 이더 파우셋](https://github.com/orbitdb/field-manual)
- [홈페이지](https://github.com/orbitdb/orbit-db)

## Security Tools {#security-tools}

### Smart Contract Security {#smart-contract-security}

**Slither -** **_Solidity static analysis framework written in Python 3._**

- [깃허브](https://github.com/crytic/slither)

**MythX -** **_Security analysis API for Ethereum smart contracts._**

- [홈페이지](https://mythx.io/)
- [깃허브](https://docs.mythx.io/en/latest/)

**Mythril -** **_Security analysis tool for EVM bytecode._**

- [깃허브](https://github.com/ConsenSys/mythril)
- [Documentation](https://mythril-classic.readthedocs.io/en/master/about.html)

**SmartContract.Codes -** **_Search engine for verified solidity source codes._**

- [smartcontract.codes (alpha)](https://smartcontract.codes/)
- [Documentation](https://github.com/ethereum-play/smartcontract.codes/blob/master/README.md)

**Manticore -** **_A command line interface that uses a symbolic execution tool on smart contracts and binaries._**

- [이더리움 개발 도구 목록 #이더리움클라이언트(Ethereum-clients)](https://github.com/trailofbits/manticore)
- [Documentation](https://github.com/trailofbits/manticore/wiki)

**Securify -** **_Security scanner for Ethereum smart contracts._**

- [개발문서](https://securify.chainsecurity.com/)
- [깃허브](https://discordapp.com/invite/nN77ckb)

**ERC20 Verifier -** **_A verification tool used to check if a contract complies with the ERC20 standard._**

- [홈페이지](https://erc20-verifier.openzeppelin.com)
- [깃허브](https://forum.openzeppelin.com/t/online-erc20-contract-verifier/1575)

### Formal Verification {#formal-verification}

**Information on Formal Verification**

- [How formal verification of smart-contacts works](https://runtimeverification.com/blog/how-formal-verification-of-smart-contracts-works/) _July 20, 2018 - Brian Marick_
- [How Formal Verification Can Ensure Flawless Smart Contracts](https://media.consensys.net/how-formal-verification-can-ensure-flawless-smart-contracts-cbda8ad99bd1) _Jan 29, 2018 - Bernard Mueller_

**Looking for other options?**

- [스마트컨트랙트 취약점 분류 레지스트리(Smart-contract Weakness Classification Registry, SWC Registry)](https://github.com/ConsenSys/ethereum-developer-tools-list#security-tools)

## Testing Tools {#testing-tools}

**Solidity-Coverage -** **_Alternative solidity code coverage tool._**

- [컨센시스(ConsenSys) 개발문서](https://github.com/sc-forks/solidity-coverage)

**hevm -** **_Implementation of the EVM made specifically for unit testing and debugging smart contracts._**

- [이더리움 개발 도구 목록 #모범사례패턴(Patterns—best-practices)](https://github.com/dapphub/dapptools/tree/master/src/hevm)
- [DappHub Chat](https://dapphub.chat/)

**Whiteblock Genesis -** **_An end-to-end development sandbox and testing platform for blockchain._**

- [홈페이지](https://whiteblock.io)
- [Documentation](https://docs.whiteblock.io)
- [GitHub](https://github.com/whiteblock/genesis)

**Looking for other options?**

- [깃터 채팅방](https://github.com/ConsenSys/ethereum-developer-tools-list#testing-tools)

## Block Explorers {#block-explorers}

Block explorers are services that let you browse the Ethereum blockchain (and its testnets), by finding information about specific transactions, blocks, contracts, and other on-chain activity.

- [깃터 채팅방](https://etherscan.io/)
- [Blockscout](https://blockscout.com/)
- [Etherchain](https://www.etherchain.org/)

## Testnets and Faucets {#testnets-and-faucets}

The Ethereum community maintains multiple testnets. These are used by developers to test their applications under different conditions before deploying to the Ethereum mainnet.

**Ropsten -** **_Proof of Work blockchain, test-ether can be mined._**

- [홈페이지](https://faucet.ropsten.be/)

**Rinkeby -** **_Proof of Authority blockchain, maintained by the Geth development team._**

- [홈페이지](https://faucet.rinkeby.io/)
- [Universal faucet](https://faucets.blockxlabs.com)

**Goerli -** **_Cross-client Proof of Authority blockchain, built and maintained by the Goerli community_**

- [홈페이지](https://faucet.goerli.mudit.blog/)
- [goerli.net](https://goerli.net/)
- [Universal faucet](https://faucets.blockxlabs.com)

## Clients & Running your own Node {#clients--running-your-own-node}

The Ethereum network is made up of many nodes who run compatible client software. The majority of these nodes run [Geth](https://geth.ethereum.org/) or [Parity](https://www.parity.io/ethereum/), each of which can be configured in different ways according to your needs.

### Clients {#clients}

**Geth -** **_Ethereum clients written in Go._**

- [홈페이지](https://github.com/ethereum/go-ethereum)
- [Discord chat](https://discordapp.com/invite/nthXNEv)

**Parity -** **_Ethereum client written in Rust._**

- [홈페이지](https://www.parity.io/)
- [GitHub](https://github.com/paritytech/parity-ethereum)

**Pantheon -** **_Ethereum client written in Java._**

- [pegasys.tech](http://pegasys.tech)
- [GitHub](https://github.com/PegaSysEng/pantheon/)

**Nethermind -** **_Ethereum client written in C# .NET Core._**

- [이더리움개선제안(EIP) 목록](http://nethermind.io/)
- [이더리움 개선제안 깃허브 레포지토리](https://github.com/NethermindEth/nethermind)
- [이더리움 개선제안 토론 게시판](https://gitter.im/nethermindeth/nethermind)

### Running your own node {#running-your-own-node}

**Ethnode -** **_Run an Ethereum node (Geth or Parity) for local development._**

- [GitHub](https://github.com/vrde/ethnode)

**Ethereum Node Resources**

- [Node Configuration Cheat Sheet](https://dev.to/5chdn/ethereum-node-configuration-modes-cheat-sheet-25l8) _Jan 5, 2019 - Afri Schoeden_

**Looking for other options?**

- [Ethereum Developer Tools List #Ethereum-clients](https://github.com/ConsenSys/ethereum-developer-tools-list#ethereum-clients)

## Best Practices, Patterns, and Anti-patterns {#best-practices-patterns-and-anti-patterns}

### Smart Contracts {#smart-contracts}

**DappSys -** **_Safe, simple, flexible building-blocks for smart-contracts._**

- [dapp.tools/dappsys](https://dapp.tools/dappsys/)
- [GitHub](https://github.com/dapphub/dappsys)

**OpenZeppelin Contracts -** **_Library for secure smart contract development._**

- [openzeppelin.com/contracts/](https://openzeppelin.com/contracts/)
- [GitHub](https://github.com/OpenZeppelin/openzeppelin-contracts)
- [Community Forum](https://forum.openzeppelin.com/c/contracts)

**aragonOS -** **_Patterns for upgradeability & permission control._**

- [hack.aragon.org](https://hack.aragon.org/docs/aragonos-intro.html#aragonos-provides-the-following-functionality)
- [Documentation](https://wiki.aragon.org/)

**Smart Contract Weakness Registry**

- [SWC registry](https://smartcontractsecurity.github.io/SWC-registry/)
- [GitHub](https://github.com/SmartContractSecurity/SWC-registry)

### Security {#security}

**Smart Contract Security Best Practices Guide**

- [consensys.github.io/smart-contract-best-practices/](https://consensys.github.io/smart-contract-best-practices/)
- [GitHub](https://github.com/ConsenSys/smart-contract-best-practices/)
- [Aggregated collection of security recommendations and best practices](https://github.com/guylando/KnowledgeLists/blob/master/EthereumSmartContracts.md)

**Smart Contract Security Verification Standard (SCSVS)**

- [securing.github.io/SCSVS/](https://securing.github.io/SCSVS/)

**Looking for other options?**

- [Ethereum Developer Tools List #Patterns—best-practices](https://github.com/ConsenSys/ethereum-developer-tools-list#patterns--best-practices)

## Developer Support & Training {#developer-support--training}

### General Learning {#general-learning}

**Ethereum Stackexchange**

- [ethereum.stackexchange.com](https://ethereum.stackexchange.com/)

**ConsenSys Academy -** **_An end-to-end Ethereum developer course that is self-paced and open year-round._**

- [consensys.academy](https://consensys.net/academy/ondemand/)

**Solidity Gitter Chatroom**

- [gitter.im/ethereum/solidity](https://gitter.im/ethereum/solidity/)

**All Ethereum Gitter Chatrooms**

- [gitter.im/ethereum/home](https://gitter.im/ethereum/home)

**Chainshot -** **_Web based dapp coding tutorials._**

- [chainshot.com](https://www.chainshot.com/)

**Blockgeeks -** **_Online courses on blockchain technology._**

- [courses.blockgeeks.com](https://courses.blockgeeks.com/)

**DappUniversity -** **_Learn to build decentralized applications on the Ethereum blockchain._**

- [DappUniversity.com](http://www.dappuniversity.com/)

**B9lab Academy -** **_Home of the oldest professional Ethereum dapp developer course & further learning for auditors and QA. Incl. mentoring and code review._**

- [academy.b9lab.com](https://academy.b9lab.com)

### Game-Based Learning {#game-based-learning}

**Cryptozombies -** **_Learn to code games on ethereum._**

- [Cryptozombies.io](https://cryptozombies.io/)

**Ethernaut -** **_Solidity based wargame where each level is a contract to be hacked._**

- [ethernaut.openzeppelin.com](https://ethernaut.openzeppelin.com/)

**Capture the Ether -** **_The game of Ethereum smart contract security._**

- [capturetheether.com](https://capturetheether.com/)

## UI/UX Design {#uiux-design}

- [Challenge of UX in Ethereum](https://medium.com/ecf-review/challenge-of-ux-in-ethereum-122e1a33688d) _June 25, 2018 - Anna Rose_
- [Designing for blockchain: what’s different and what’s at stake](https://media.consensys.net/designing-for-blockchain-whats-different-and-what-s-at-stake-b867eeade1c9) _March 22, 2018 - Sarah Baker Mills_

**Rimble UI** **_- Adaptable components and design standards for decentralized applications._**

- [rimble.consensys.design](https://rimble.consensys.design)
- [GitHub](https://github.com/ConsenSys/rimble-ui)

## Standards {#standards}

The Ethereum community has adopted many standards that are helpful to developers. Typically these are introduced as [Ethereum Improvement Proposals](http://eips.ethereum.org/) (EIPs), which are discussed by community members through a [standard process](http://eips.ethereum.org/EIPS/eip-1).

- [List of EIPs](http://eips.ethereum.org/)
- [EIP github repo](https://github.com/ethereum/EIPs)
- [EIP discussion board](https://ethereum-magicians.org/c/eips)
- [Ethereum Governance Overview](https://blog.bmannconsulting.com/ethereum-governance/) _March 31, 2019 - Boris Mann_
- [Playlist of all Ethereum Core Dev Meetings](https://www.youtube.com/playlist?list=PLaM7G4Llrb7zfMXCZVEXEABT8OSnd4-7w) _(YouTube Playlist)_

Certain EIPs relate to application-level standards (e.g. a standard smart-contract format), which are introduced as [Ethereum Requests for Comment (ERC)](https://eips.ethereum.org/erc). Many ERCs are critical standards used widely across the Ethereum ecosystem.

- [List of ERCs](http://eips.ethereum.org/erc)
- [ERC20 - A standard interface for tokens](https://eips.ethereum.org/EIPS/eip-20)
- [ERC721 - A standard interface for non-fungible tokens](https://eips.ethereum.org/EIPS/eip-721)
