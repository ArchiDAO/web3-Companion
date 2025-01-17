## Welcome to the ArchiDAO Ethereum Developer Companion

Early version of this guide were developed as a companion to the AthensLabs Blockchain Developer Bootcamp 2022. We have been updating this guide for use of Blockchain in Architecture-Engineering-Construction, including upgrading tutorials on newer development frameworks. Still, some of the fundamentals on blockchains remain unchanged. The guide focuses on the Ethereum ecosystem, currently (Jan 2024) the most vibrant smart contract and blockchain development ecosystem. It is designed as a series of structured links and content that will provide you with the basic knowledge to develop decentralised applications.

- The companion is used as a source of information on active learning that you have to develop, by designing, coding and deploying an actual decentralised application.


## Onboarding
- [Consensys Basic Training](https://courses.consensys.net/courses/bootcamp-basic-training)
- [Developer onboarding on Ethereum - Ethereum.org](https://ethereum.org/en/developers/docs/)
- [Alchemy uUniversity - solidity](https://university.alchemy.com/overview/solidity)
- [Cyfrin Updraft](https://updraft.cyfrin.io/courses)


## Setting up a development environment
- Linux distribution
  * [Ubuntu 20.04 LTS](https://ubuntu.com/download/desktop)
  * [Ubuntu 23.11](https://releases.ubuntu.com/mantic/)
  * [Linux Mint](https://linuxmint.com/)
  * [MX Linux](https://mxlinux.org/)
  * [Puppy Linux - best for old machines](https://puppylinux-woof-ce.github.io/)
  * [Fedora](https://fedoraproject.org/en/workstation/)
  * [CEntOs- best for enterprise deployments](https://www.centos.org/centos-stream/)
  * [OpenSuse](https://www.opensuse.org/)
  * [Linux Distribution watch](https://distrowatch.com/)

- Windows
  * [Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/install-win10)
  * [Ethereum developers guide to setting up WSL](https://consensys.net/blog/developers/ethereum-developers-guide-to-setting-up-windows-subsystem-for-linux/)

- MacOS: Latest is v13 'Sonoma' (sep 2023)
  * _you need an Apple computer to run MacOS_
  * [MacOS Monterey](https://www.apple.com/uk/macos/monterey/)
  * [MacOS Sonoma](https://www.apple.com/macos/sonoma/)


- Options for Ethereum Nodes
  * [Nodes and clients on Ethereum](https://ethereum.org/en/developers/docs/nodes-and-clients/)
  * [OpenEthereum](https://github.com/openethereum/openethereum)
  * [Geth](https://geth.ethereum.org/)
  * [Nethermind, a .NET client](https://nethermind.io/)
  * [Infura](infura.io)

-  Deployment of a personal development environment
    * [Stacks on Ethereum/](https://ethereum.org/en/developers/local-environment/)

- Editors and IDEs (Integrated development environments)
  * [Remix](https://remix.ethereum.org)
  * [Remix-Desktop](https://github.com/ethereum/remix-desktop)
  * [ethfiddle](https://ethfiddle.com/)
  * [Pulsar - the successor to Atom](https://pulsar-edit.dev/)
  * [Visual studio Code](https://code.visualstudio.com/)
  * [MS Visual Studio Live share extension](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare-pack)
  * [JetBrains Idea](https://www.jetbrains.com/idea)


- Git clients
  * [git](https://git-scm.com/)
  * [GitHub :: Desktop - best for MacOS and Windows](https://desktop.github.com/)
  * [Oh My Git - Learning Git game](https://ohmygit.org/)


## Review of blockchain technologies
- Blockchain Context
    * [The Byzantine Generals' Problem, by L.Lmport, r.Shostak, M.Pease](https://lamport.azurewebsites.net/pubs/byz.pdf)
    * [Byzantine Generals' problem](https://medium.com/coinmonks/a-note-from-anthony-if-you-havent-already-please-read-the-article-gaining-clarity-on-key-787989107969)
    * [The Byzantine Generals' problem by Ivan on Tech](https://academy.ivanontech.com/blog/byzantine-generals-problem-an-introduction)
    * [How Satoshi Nakamoto solved the Byzantine Generals' Problem](https://news.bitcoin.com/triple-entry-bookkeeping-how-satoshi-nakamoto-solved-the-byzantine-generals-problem/)
    * [The Bitcoin WhitePaper](https://fermatslibrary.com/s/bitcoin)
    * [How Does a Blockchain Work? - Video](https://www.youtube.com/watch?v=SSo_EIwHSd4)
    * [A Visual Blockchain Demo - Video](https://www.youtube.com/watch?v=_160oMzblY8)


- Distributed Ledgers
  * [A review of DLTs by N.E.Ioini & C.Pahl](https://www.researchgate.net/profile/Claus-Pahl/publication/328475892_A_Review_of_Distributed_Ledger_Technologies/links/5bd0085ba6fdcc204a036252/A-Review-of-Distributed-Ledger-Technologies.pdf)
  * [Distributed Ledger Technology: Beyond Blockchain - UK gov office for Science](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/492972/gs-16-1-distributed-ledger-technology.pdf)
  * [WorldBank on DLTs](https://www.worldbank.org/en/topic/financialsector/brief/blockchain-dlt)

- Consensus Mechanisms
  * [Consensus Mechanisms](https://mastanbtc.github.io/blockchainnotes/consensustypes/)
  * [Consensus Mechanisms in Ethereum](https://ethereum.org/en/developers/docs/consensus-mechanisms/)
  * [Review of consensus mechanisms](https://medium.com/wavesprotocol/review-of-blockchain-consensus-mechanisms-f575afae38f2)
  * [Understanding Distributed Consensus](https://medium.com/s/story/lets-take-a-crack-at-understanding-distributed-consensus-dad23d0dc95)
  * Proof of Work
      [Proof of Work](https://ethereum.org/en/developers/docs/consensus-mechanisms/pow/)
  * Proof of Stake
      [Proof of Stake](https://ethereum.org/en/developers/docs/consensus-mechanisms/pos/)
      [Proof of Stake vs Proof of Work](https://decrypt.co/resources/proof-of-work-vs-proof-of-stake)

- Transactions and Blocks
  * [Transactions](https://ethereum.org/en/developers/docs/transactions/)
  * [Blocks](https://ethereum.org/en/developers/docs/blocks/)

- Mining & Staking
  * [Proof of Work at Ethereum](https://ethereum.org/en/developers/docs/consensus-mechanisms/pow/)
  * [Mining](https://eth.wiki/fundamentals/mining)
  * [Ethash: Dagger Hashimoto](https://eth.wiki/en/concepts/ethash/ethash)
  * [Proof of Stake at Ethereum](https://ethereum.org/en/developers/docs/consensus-mechanisms/pos/)
  * [Mining vs  staking](https://major-capital.com/en/mining-vs-staking/)
  * [Bye, Bye Miners](https://www.bloomberg.com/news/articles/2021-08-14/bye-bye-miners-how-ethereum-s-big-change-will-work-quicktake)
  * [Start staking on Ethereum](https://ethereum.org/en/eth2/staking/)


- Network Peer Discovery and Messaging
  * [Analysing the Underlying Peer-to-Peer Network of Ethereum Blockchain, Wang et al](https://arxiv.org/pdf/2010.01373.pdf)
  * [Understanding Ethereum's P2P work](https://medium.com/shyft-network-media/understanding-ethereums-p2p-network-86eeaa3345)
  * [How the P2P networking in Ethereum works](https://medium.com/orbs-network/the-actual-networking-behind-the-ethereum-network-how-it-works-6e147ca36b45)

- Public and Private Blockchains
    * [Public and private blockchains - A blog post by V.Buterin](https://blog.ethereum.org/2015/08/07/on-public-and-private-blockchains/)

- Distributed Ledger Platforms
  * [Hyperledger](https://www.hyperledger.org/use/fabric)
  * [Corda](www.corda.net)
  * [IOTA](www.iota.org)
  * [Alternative Distributed Ledger Technologies Blockchain vs. Tangle vs. Hashgraph - A High-Level Overview and Comparison](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3144241)


## Blockchain Basics
- Cryptography
  * [Cryptography in Wikipedia](https://en.wikipedia.org/wiki/Cryptography)
  * [Schneier on Cryptography](https://www.schneier.com/blog/archives/2016/03/cryptography_is.html)
  * [Schneir's Applied Cryptography online](https://www.schneier.com/blog/archives/2014/01/applied_cryptog_1.html)
  * [Introduction to modern cryptosystems](https://www.giac.org/paper/gsec/2604/introduction-modern-cryptosystems/104482)
  * [Practical Cryptography](https://rizkia.staff.telkomuniversity.ac.id/files/2016/02/Practical-Cryptography-Niels-Ferguson-Bruce-Schneier.pdf)
  * [Overview of modern Cryptography](https://cryptobook.nakov.com/cryptography-overview)
  * [Lecture series on Cryptography by Christof Paar](https://www.youtube.com/watch?v=2aHkqB2-46k&list=UU1usFRN4LCMcfIV7UjHNuQg&index=25)

- Cryptographic Hash functions
  * [Secure hash algorithms](https://brilliant.org/wiki/secure-hashing-algorithms/)
  * [Back to basics](https://www.maximintegrated.com/en/design/technical-documents/app-notes/7/7015.html)
  * [MD5](https://searchsecurity.techtarget.com/definition/MD5)
  * [SHA1](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.180-4.pdf)
  * [SHA2 - Wikipedia](https://en.wikipedia.org/wiki/SHA-2)
  * [SHA3 - Wikipedia](https://en.wikipedia.org/wiki/SHA-3)
  * [SHA3 -'keccak'](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.202.pdf)
  * [ETH-hash keccak256](https://github.com/ethereum/eth-hash)
  * [Lecture by Christof Paar on Cryptographic Functions](https://www.youtube.com/watch?v=JWskjzgiIa4)

- Using Cryptograpic Hash functions
  * [How hash algorithms work](https://www.metamorphosite.com/one-way-hash-encryption-sha1-data-software)
  * [Cryptographic hashing on Hackernoon](https://hackernoon.com/cryptographic-hashing-c25da23609c3)
  * [Hashing functions in Blockchain](https://hackernoon.com/learn-the-blockchain-basics-part-3-hashing-functions-vt1435ow)

- Public Key Cryptography
  * [Symmetric and Assymmetric Public Key Cryptography](https://hackernoon.com/how-does-symmetric-and-asymmetric-public-key-cryptography-work-i6dy37pl)
  * [Public Key Cryptography Glossary](https://hackernoon.com/glossary-of-security-terms-public-key-cryptography-fri3u4d)
  * [Public key cryptography RSA keys](https://hackernoon.com/public-key-cryptography-rsa-keys-izda3ylv)

- Merkle Trees
  * [Ever wonder how Merkle trees work?](https://media.consensys.net/ever-wonder-how-merkle-trees-work-c2f8b7100ed3)
  * [Getting to the root of the "Merkle" tree concept](https://hackernoon.com/getting-to-the-root-of-the-merkle-tree-concept-and-how-it-affects-blockchain-technology)

- Using Merkle Trees
  * [Merkle Tree Introduction](https://hackernoon.com/merkle-tree-introduction-4c44250e2da7)
  * [What is a Merkle Tree](httpe://decentralizedthoughts.github.io/2020-12-22-what-is-a-merkle-tree/)
  * [Merkle Tree Demo](https://prathamudeshmukh.github.io/merkle-tree-demo/)
  * [Merkle Tree in solidity](https://soliditydeveloper.com/merkle-tree)

- Blockchain Structure
  * [Security and Privacy issues on blockchain technology - intro to basic structure of BC](https://www.researchgate.net/publication/325173502_A_survey_on_security_and_privacy_issues_of_blockchain_technology)
  * [Basic Blockchain Structure on O' Reilly](https://www.oreilly.com/library/view/mastering-bitcoin/9781491902639/ch07.html)

- Building a Blockchain
  * [Learn Blockchains by Building one](https://hackernoon.com/learn-blockchains-by-building-one-117428612f46)
  * [Create your own Blockchain using python](https://dzone.com/articles/how-to-create-your-own-cryptocurrency-blockchain-i)
  * [How to build a Blockchain in Python](https://www.activestate.com/blog/how-to-build-a-blockchain-in-python/)
  * [How to create a blockchain in Python](https://www.section.io/engineering-education/how-to-create-a-blockchain-in-python/)
  * [Build a Blochchain in less than 60 lines of code](https://medium.com/coinmonks/python-tutorial-build-a-blockchain-713c706f6531)
  * [Blockchain basics on Solidity](https://docs.soliditylang.org/en/develop/introduction-to-smart-contracts.html#blockchain-basics)

- Smart contracts
  * [Formalizing and Securing Relationships on Public Networks - first mention of Smart Contracts](https://firstmonday.org/ojs/index.php/fm/article/view/548)
  * [Smart Contracts on Wikipedia](https://en.wikipedia.org/wiki/Smart_contract)
  * [Smart Contracts on Ethereum](https://ethereum.org/en/developers/docs/smart-contracts/)
  * [Smart Contracts on Cardano](https://docs.cardano.org/new-to-cardano/what-is-a-smart-contract)
  * [Understanding Smart Contracts](http://www.gjermundbjaanes.com/understanding-ethereum-smart-contracts/)

- Blockchain Nodes
  * [What is a Node](https://coinmarketcap.com/alexandria/article/what-is-a-node)
  * [Blockchain as a service](https://www.infoq.com/articles/blockchain-as-a-service-get-block/)
  * [Blockchain Nodes 101](https://101blockchains.com/blockchain-nodes/)

- Blockchain Forks
  * [a history of bitcoin forks](https://www.investopedia.com/tech/history-bitcoin-hard-forks/)
  * [What are blockchain forks?](https://www.youtube.com/watch?v=boARRLlu5Uc)
  * [An oveview of forks and blockchain development](https://www.researchgate.net/publication/349492184_An_Overview_of_Forks_and_Coordination_in_Blockchain_Development)


## “Ethereum” Primitives
- [Ethereum "pre-history"](https://vitalik.ca/general/2017/09/14/prehistory.html) Vitalik Buterin blog post:
Interesting to read as Buterin goes through the internal thought process of creating a fee based ledger that is Turing complete, i.e a state machine. Note the simplicity of the programmatic loop he employs to validate his concept
- [Ethereum White Paper](https://ethereum.org/en/whitepaper/)
- [Ethereum Yellow Paper, Dr Gavin Wood](https://ethereum.github.io/yellowpaper/paper.pdf)
- [Ethereum](https://ethereum.org/)
- [Ethereum Docs](https://ethereum.org/en/developers/docs/)
- [Web2 vs Web3](https://ethereum.org/en/developers/docs/web2-vs-web3/)
- [Accounts](https://ethereum.org/en/developers/docs/accounts/)
  * Externally Owned
    [EOA by gnosis](https://docs.gnosis.io/safe/docs/intro_accounts/)
    [understanding EOA through deciphering a transaction](https://docs.ethhub.io/guides/deciphering-a-transaction-on-etherscan/)
  * Contract Owned
    [Contract & EO accounts](https://www.theengineeringprojects.com/2021/06/ethereum-accounts-definition-types-and-fields.html)
    [Contract deployment](https://programtheblockchain.com/posts/2018/01/09/how-smart-contract-deployment-works/)

- [Transactions](https://ethereum.org/en/developers/docs/transactions/)
- [Gas and Fees](https://ethereum.org/en/developers/docs/gas/)


- Blocks
  * [Blocks](https://ethereum.org/en/developers/docs/blocks/)
  * [Ethereum Block Structure Visualised](https://i.stack.imgur.com/eOwjD.png)

- Running an Ethereum Node
  * [PoS](https://ethereum.org/en/developers/docs/consensus-mechanisms/pos/)
  * [Run an Ethereum Node - general info](https://ethereum.org/en/run-a-node/)
  * [Spin your Own Node](https://ethereum.org/en/developers/docs/nodes-and-clients/run-a-node/)
  * [Guide to becoming a validator](https://blockdaemon.com/products/white-label-validator/ethereum-introduction/)


- Ethereum Virtual Machine
  * [Ethereum Virtual Machine](https://ethereum.org/en/developers/docs/evm/)
  * [Ethereum Virtual Machine illustrated](https://takenobu-hs.github.io/downloads/ethereum_evm_illustrated.pdf)

- Generating Ethereum addresses
  * [Generating Ethereum Addresses](https://hackernoon.com/how-to-generate-ethereum-addresses-technical-address-generation-explanation-25r3zqo)

- Elliptic Curve Cryptography
  * [Basic Introduction to elliptic curve cryptography](https://qvault.io/cryptography/elliptic-curve-cryptography/)
  * [Practical Elliptic Curve Cryptography](https://cryptobook.nakov.com/asymmetric-key-ciphers/elliptic-curve-cryptography-ecc)
  * [Maths behind elliptic curve cryptography](https://hackernoon.com/what-is-the-math-behind-elliptic-curve-cryptography-f61b25253da3)
  * [easy to understand primer on elliptic curve cryptography](https://blog.cloudflare.com/a-relatively-easy-to-understand-primer-on-elliptic-curve-cryptography/)
  * [Bitcoin Book:Elliptic Curve Cryptography](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch04.asciidoc#elliptic-curve-cryptography-explained)

- MainNet and TestNets
  * [Networks on Ethereum](https://ethereum.org/en/developers/docs/networks/)
  * [Development Networks](https://ethereum.org/en/developers/docs/development-networks/)
  * [Sepolia Test Netowrk](https://sepolia.dev/)
  * [Holesky Test Network](https://holesky.ethpandaops.io/)

  * [Connecting to public testnets](https://docs.openzeppelin.com/learn/connecting-to-public-test-networks)
  * [Testing Ethereum](https://www.innoq.com/en/blog/testing-ethereum/)
  * [How to set up a custom Ethereum Testnet](https://www.ulam.io/blog/how-to-setup-custom-ethereum-testnet/)


  - Layer 2 testnets
  * [Goerli for Abritrum](https://goerli.arbiscan.io/)
  * [Goerli for Optimisim](https://goerli-optimism.etherscan.io/)
  * [Goerli for Stacknet](https://faucet.goerli.starknet.io/)

  - Consortium Networks
  * [Create a private network](https://www.c-sharpcorner.com/article/setup-your-private-ethereum-network-with-geth2/)



- depreciated
  * [Kovan Test Network](https://kovan-testnet.github.io/website/)
  * [Rinkeby Test Network](https://www.rinkeby.io/#stats)
  * [Goerli Test Network](https://goerli.net/)

- Etherscan
  * [MainNet Etherscan](https://etherscan.io/)
  * [Sepolia Etherscan](https://sepolia.etherscan.io/)
  * [Holesky Etherscan](https://holesky.etherscan.io/)

- Tokens and Token Standards
 - [EthWiki](https://eth.wiki/home)

## Traditional and Decentralised application development
* [How to Get Into Ethereum-Crypto-Web3 as a Developer](https://dev.to/dabit3/how-to-get-into-ethereum-crypto-web3-as-a-developer-9l6)
- Decentralised application development
* [Similarities and differences between Centralised vs Decentralised](https://www.geeksforgeeks.org/centralized-vs-decentralized-applications/)
* [Setting up yur Development Environment](https://www.grizzlypeaksoftware.com/articles?id=947hoJYsqk86nRQku8szy)
- Key Developer Tools (metamask, remix, truffle, hardhat, web3.js, IPFS)
* [Decentralised Application Frameworks](https://blog.logrocket.com/top-5-decentralized-app-development-frameworks/)
* [Setting up your own Ethereum private network](https://hackernoon.com/how-to-set-up-a-private-ethereum-blockchain-proof-of-authority-with-go-ethereum-part-1)


## Development frameworks and environment
- [Solidity and Blockchain Development Big Picture](https://soliditydeveloper.com/solidity-overview-2020)
- Introduction
  * [Solidity Language Documentation](https://docs.soliditylang.org/en/develop/introduction-to-smart-contracts.html#blockchain-basics)

- Blockchain Development Tools & Suites
    * [Foundry](https://github.com/foundry-rs/foundry)
    * [Hardhat](https://hardhat.org/)
    * [Beginners Tutorial](https://hardhat.org/tutorial/)
    * [Brownie - python based](https://github.com/eth-brownie/brownie)

  - enterprise class
    * [Alchemy](https://www.alchemy.com/)
    * [Moralis](https://moralis.io/)

    Depreciated:
    * [Truffle Suite- in the process of being sunset](https://www.trufflesuite.com/)
    * [Ganache GUI](https://www.trufflesuite.com/ganache)
    * [Ganache CLI](https://github.com/trufflesuite/ganache-cli-archive)
    * [Drizzle](https://www.trufflesuite.com/drizzle)
    * [Trufflesuite guides](https://www.trufflesuite.com/guides)
    * [Trufflesuite PetShop Tutorial](https://www.trufflesuite.com/tutorial)
    - Truffle Boxes (Templates to base your project on)
      * [Truffle boxes](https://www.trufflesuite.com/boxes)



- Hardhat
  * [Hello world Tutorial with Hardhat](https://ethereum.org/en/developers/tutorials/waffle-say-hello-world-with-hardhat-and-ethers/)
  * [Create and Deploy a smart contract with Hardhat](https://www.quicknode.com/guides/web3-sdks/how-to-create-and-deploy-a-smart-contract-with-hardhat)

- Setting up HardHat guide
  * [Setup Hardhat video tutorial](https://www.youtube.com/watch?v=D4kPj10lKyQ)

- Developer Tools guides
  * [Ethereum Developer tools by Consensys](https://github.com/ConsenSys/ethereum-developer-tools-list)



## Solidity Fundamentals
* [Solidity Language](https://soliditylang.org/)
* [Solidity Documentation](https://docs.soliditylang.org/)
* [Solidity Cheatsheet](https://docs.soliditylang.org/en/latest/cheatsheet.html)

- Layout & Structure
  * [Layout of a solidity file](https://docs.soliditylang.org/en/v0.8.23/layout-of-source-files.html)
  * [Structure](https://docs.soliditylang.org/en/v0.8.23/structure-of-a-contract.html)

- Data Types and Variables
  * [Value Types](https://docs.soliditylang.org/en/v0.8.7/types.html#value-types)
  * [Units and global variables](https://docs.soliditylang.org/en/v0.8.7/units-and-global-variables.html)
  * [Variables by example](https://solidity-by-example.org/variables/)

- Functions
  * [Functions](https://docs.soliditylang.org/en/v0.8.7/structure-of-a-contract.html#functions)
  * [Functions by Example](https://solidity-by-example.org/function/)
  * [Function Modifier](https://solidity-by-example.org/function-modifier/)
  * [Functtion Selector](https://solidity-by-example.org/function-selector/)


- Storage and Memory
  * [Storage by example](https://solidity-by-example.org/data-locations/)
  * [Storage, Memory & the stack](https://docs.soliditylang.org/en/v0.8.7/introduction-to-smart-contracts.html?highlight=memory#storage-memory-and-the-stack)

- Reading Smart Contracts
  * [Solidity by Example](https://solidity-by-example.org/)
  * [Reading OpenZeppelin](https://docs.openzeppelin.com/contracts/4.x/)
  * [OpenZeppelin on Github](https://github.com/OpenZeppelin/openzeppelin-contracts)

- Smart Contract Application Binary Interface [ABI]
  * [ABI](https://docs.soliditylang.org/en/v0.8.6/abi-spec.html)
  * [ABI bytecode and the EVM](https://medium.com/@eiki1212/explaining-ethereum-contract-abi-evm-bytecode-6afa6e917c3b)
  * [Understanding ABIs step by step](https://www.quicknode.com/guides/solidity/what-is-an-abi)
  * [ABI on alchemy](https://docs.alchemy.com/alchemy/guides/eth_getlogs#what-are-ab-is)
  * [ABI encoding in Ethereum](https://docs.nethereum.com/en/latest/nethereum-abi-encoding/)

- Events and Logs
  * [Events](https://docs.soliditylang.org/en/develop/abi-spec.html#events)
  * [Solidity Events](https://www.tutorialspoint.com/solidity/solidity_events.htm)
  * [How to use events for logging](https://betterprogramming.pub/learn-solidity-events-2801d6a99a92)
  * [How to use eevents in solidity](https://hackernoon.com/how-to-use-events-in-solidity-pe1735t5)

- Factory Contracts
* [Solidity Fast Track Part 1](https://soliditydeveloper.com/solidity-fast-track),
* [Solidity Fast Track Part 2](https://soliditydeveloper.com/solidity-fast-track-2),
* [Solidity by Example](https://solidity-by-example.org/)
* [All About Solidity](https://jeancvllr.medium.com/all-about-solidity-article-series-f57be7bf6746)
* [Learn X in Y - Solidity](https://learnxinyminutes.com/docs/solidity/)
* [EthFiddle - Solidity < 0.7.1](https://ethfiddle.com/)

- Solidity patterns
  * [Solidity Patterns](https://fravoll.github.io/solidity-patterns/)
  * [Smart Contract Weakness Classification](https://swcregistry.io/)

## Writing Smart Contracts
- Introductory Smart Contracts
  * [Hello World](https://solidity-by-example.org/hello-world/)
  * [first app : count](https://solidity-by-example.org/first-app/)
  * [multi-sig wallet](https://solidity-by-example.org/app/multi-sig-wallet/)

- Inter-Contract Execution
  * [Basic example on stackexchange](https://ethereum.stackexchange.com/questions/1599/basic-example-of-interaction-between-2-contracts)
  * [Interactions between contract](https://dappsforbeginners.wordpress.com/tutorials/interactions-between-contracts/)
  * [Calling other contract](https://solidity-by-example.org/calling-contract/)
  * [Contract that creates other contracts](https://solidity-by-example.org/new-contract/)

- Inheritance
  * [Solidity Inheritance](https://www.geeksforgeeks.org/solidity-inheritance/#:~:text=Solidity%20supports%20inheritance%20between%20smart,is%20called%20a%20derived%20contract.)
  * [Contracts are Classes](https://ethereumdev.io/inheritance-in-solidity-contracts-are-classes/)
  * [Inheritance in Solidity Docs](https://docs.soliditylang.org/en/v0.8.6/contracts.html?highlight=inheritance#inheritance)

- Libraries and the Ethereum Package manager
  * [Libraries at Ethereum](https://ethereum.org/en/developers/docs/smart-contracts/libraries/)
  * [OpenZeppelin Contracts](https://openzeppelin.com/contracts/)
  * [Modular Network Lirbaries](https://github.com/modular-network/ethereum-libraries)

- Smart Contract System Design
  * [Building your Dapp](https://docs.openzeppelin.com/learn/building-a-dapp)
  * [Towards better voting protocols](https://blog.colony.io/towards-better-ethereum-voting-protocols-7e54cb5a0119/)
  * [Designing the architecture of your Ethereum application](https://blog.openzeppelin.com/designing-the-architecture-for-your-ethereum-application-9cec086f8317/)

- Writing a Smart Contract - proof of existence
  * [Proof of Existence](https://github.com/ramyhardan/proof-of-existence)

- Types of Smart Contracts
* [Simple Bank](https://nicogs.medium.com/building-a-bank-with-solidity-for-beginners-ethereum-blockchain-development-tutorial-ba50ce6e8eb0)
* [Multi-signature Wallet](https://github.com/ConsenSys-Academy/multisig-wallet-exercise)
* [Supply Chain](https://github.com/ConsenSys-Academy/supply-chain-exercise)


- Examples: Deploying a Voting Smart Contract
* [Deploying a Voting Smart Contract](https://www.youtube.com/watch?v=GB3hiiNNDjk)

- Games
  * [CryptoZombies](https://cryptozombies.io/)

- Guides
  * [Ethereumdev.io](https://ethereumdev.io/)
  * [Solidity Developer](https://soliditydeveloper.com/blog)
  * [Ethereum Blockchain Developer](https://ethereum-blockchain-developer.com/)

## Token Standards - EIPs

- [EIPs - Ethereum Improvement Proposals](https://eips.ethereum.org/)
  * [ERC20 - Token standard](https://eips.ethereum.org/EIPS/eip-20)
  * [ERC721 - NFT standard](https://eips.ethereum.org/EIPS/eip-721)
  * [ERC 1155 - Multi Token Standard](https://eips.ethereum.org/EIPS/eip-1155)

## Solidity Libraries & Design Patterns for Smart Contracts
- Smart Contract Libraries
  * [OpenZeppelin](https://openzeppelin.com/contracts/)

## Ethereum and the end User
- Web 3.0 Introduction
* [what is web3](https://www.freecodecamp.org/news/what-is-web3/) Decentralised Web Explained
- Web3 Packages
  * [Ethers.js](https://docs.ethers.io/)
  * [Web3.js](https://web3js.readthedocs.io/)
- Ethers.js vs Web3.js
  * [Ethers.js vs Web3.js Part I](https://blog.infura.io/ethereum-javascript-libraries-web3-js-vs-ethers-js-part-i/)
  * [Ethers.js vs Web3.js Part II](https://blog.infura.io/ethereum-javascript-libraries-web3-js-vs-ethers-js-part-ii/)
- [Interaction with Smart Contract using web3.js](https://medium.com/0xcode/interacting-with-smart-contracts-using-web3-js-34545a8a1ebd)
- Connecting web3.js to a contract
- [Truffle Pet Shop Tutorial](https://www.trufflesuite.com/tutorial)
- Metamask
  * [Metamask](https://metamask.io/)
  * [infura](https://infura.io)
  * [What is metamask](https://decrypt.co/resources/metamask)

- Integrating with React
  * [How to connect React to Ethereum](https://medium.com/fullstacked/connect-react-to-ethereum-b117986d56c1)
  * [How to fetch and update data from Ethereum](https://consensys.net/blog/developers/how-to-fetch-and-update-data-from-ethereum-with-react-and-swr/)

- Examples of Rimble use
  * [Rimpble App demo by ConsenSys - Code](https://github.com/ConsenSys/rimble-app-demo)
  * [Rimblee app demo by ConsenSys - Demo](https://consensys.github.io/rimble-app-demo/)
  * [Rimples examples](https://codesandbox.io/examples/package/rimble-ui)


- Web3 libraries as frontends for smart contracts
  * Web3.js [web3.js](https://web3js.readthedocs.io/en/v1.7.3/)
  * Ether.js [Ether.js](https://docs.ethers.io/v3/)

- Web3 and Python interaction - frontend
* Web3.py [web3.py](https://web3py.readthedocs.io/en/stable/)


## Testing & Debugging
[//]: # (add more good links here)

- Why test?
  * [What is unit testing?](https://smartbear.com/learn/automated-testing/what-is-unit-testing/)
  * [Why Testable Code matters: Unit Testing](https://www.toptal.com/qa/how-to-write-testable-code-and-why-it-matters)
  * [Software Testing Methodology](https://smartbear.com/learn/automated-testing/software-testing-methodologies/)

- Writing Tests
  * [Writting Solidity Tests with Truffle](https://trufflesuite.com/docs/truffle/how-to/debug-test/write-tests-in-solidity/)
  * [Testing Contracts with HardHat](https://hardhat.org/tutorial/testing-contracts)
  * [Writing Automated Tests](https://docs.openzeppelin.com/learn/writing-automated-tests)

- Tests in Solidity
  * [Writing Tests in Solidity with Foundry](https://soliditydeveloper.com/foundry)
  * [Solidity Unit Testing using Remix](https://remix-ide.readthedocs.io/en/latest/unittesting.html)

- Tests in Javascript
  * [Unit tests in javascript](https://docs.alchemy.com/docs/how-to-unit-test-a-smart-contract)
- Catching Errors In Tests
* [catching errors in solidity](https://codeforgeek.com/error-testing-smart-contract-in-solidity/)
* [common smart contract errors](https://blog.tenderly.co/how-to-debug-common-smart-contract-errors/)

- Smart Contract Best Practices
  * [Smart Contracts best practices](https://consensys.github.io/smart-contract-best-practices/)
  * [Known attack vectors and common anti-patterns](https://blog.sigmaprime.io/solidity-security.html)

- Exploits
- Gas Optimisation
- Safety Checklist
- Security Analysis
- Transaction Origin attack Demo
- DoS Example
- Re-entrancy example

## Full Learning Guides

* [Alchemy University](https://university.alchemy.com/home)

# Frameworks

* Foundry
* [Foundry](https://github.com/foundry-rs/foundry)
* [Foundry book](https://book.getfoundry.sh/)


* Brownie
* [Brownie](https://github.com/eth-brownie/brownie)
* [Brownie Documentation](https://eth-brownie.readthedocs.io/en/stable/)

## Learning through Gamification
- Security Games
  - OpenZeppelin
    * [Ethernaut](https://ethernaut.openzeppelin.com/)
    * [Damn Vulnerable DeFi](https://www.damnvulnerabledefi.xyz/)
  - SMARX
    * [Capture the Ether](https://capturetheether.com/)

## Visual No-Code Builder
- [Eth Build](https://eth.build/)

## Full Stack Development Tutorials
- [dAPP React development off a to-do list](https://www.dappuniversity.com/articles/ethereum-dapp-react-tutorial)
- [Complete Guide to full stack Ethereum Development](https://www.youtube.com/watch?v=WsZyb2T83lo)
- [Full stack marketplace](https://bestofreactjs.com/repo/dabit3-full-stack-ethereum-marketplace-workshop-react-react-apps)
- [how to get into web3 as a developer](https://dev.to/dabit3/how-to-get-into-ethereum-crypto-web3-as-a-developer-9l6)
- [Ethereum dapp crash course](https://dev.to/richardmelko/ethereum-dapp-crash-course-make-an-erc20-token-faucet-frontend-2m43)
- [React bootstrap Guide](https://react-bootstrap.github.io/)


## Developer Video guides
- [Create a complete NFT dapp](https://www.youtube.com/watch?v=WsZyb2T83lo)
- [Generative NFTs : HashLips](https://www.youtube.com/channel/UC1LV4_VQGBJHTJjEWUmy8nA)
- [10 blockchain ideas for beginners](https://www.youtube.com/watch?v=WsZyb2T83lo)
- [EthGlobal - Protocol Tutorials](https://www.youtube.com/c/ETHGlobal)
- [ChainLink](https://www.youtube.com/channel/UCnjkrlqaWEBSnKZQ71gdyFA)
- [Blockchain, Solidity, Full stack web3 Developmnet with Javascirpt 32 hour course](https://www.youtube.com/watch?v=gyMwXuJrbJQ)

## Decentralised Finance - DeFi
- [What is DeFi](https://ethereum.org/en/defi/)
  * [Finematics - DeFi Concepts Explained](https://www.youtube.com/c/Finematics/videos)
  * [Uniswap 2](https://solidity-by-example.org/defi/uniswap-v2/)
  * [Build a Flash Loan Bot - Part 1](https://blog.infura.io/build-a-flash-loan-arbitrage-bot-on-infura-part-i/)
  * [Build a Flash Loan Bot - Part 2](https://blog.infura.io/build-a-flash-loan-arbitrage-bot-on-infura-part-ii/)
  * [Security Flaw Walkthroughs](https://rekt.news)
  * [Decentralised Exchanges]


## Decentralised Autonomous Organisations  - DAOs 道
  - [What is a DAO](https://ethereum.org/en/dao/)
    * [DAO concepts](https://archidao.substack.com/p/top-10-words-to-know-about-dao-decentralized)

  - DAO Frameworks:
    * [DAOStack-depreciated](https://daostack.io/)
    * [Aragon](https://aragon.org/)
    * [Colony](https://colony.io/)

## Fungible & Non-fungible Tokens
  - ERC20
    * [Create an ERC-20 in 20 min](https://vitto.cc/how-to-create-and-deploy-an-erc20-token-in-20-minutes/)
    * [Create an ERC-20 in 4 steps - Alchemy docs](https://docs.alchemy.com/docs/how-to-create-an-erc-20-token-4-steps)
    * [How to create your own ERC-20 in an hour - Verified](https://steemit.com/ethereum/@maxnachamkin/how-to-create-your-own-ethereum-token-in-an-hour-erc20-verified)
    * [dAPP university: create your own Cryptocurrency in Ethereum](https://www.dappuniversity.com/articles/code-your-own-cryptocurrency-on-ethereum)
    * [OpenZeppelin - ERC-20 supplies](https://docs.openzeppelin.com/contracts/2.x/erc20-supply)

      - ERC721
    * [NFT School](https://nftschool.dev/)
  - Other token Standards
  - ERC777
  * [ERC777 at openzeppelin](https://docs.openzeppelin.com/contracts/3.x/erc777)


  ## Token Engineering
    * [Token engineering academy](https://tokenengineering.net/)
    * [Token Simulations]
    * [Token Engineering Frameworks]
    * [Ostrom Principles]

##  Developers on YouTube
  - [Eat The Blocks](https://www.youtube.com/channel/UCZM8XQjNOyG2ElPpEUtNasA)
    - [Eat The Blocks - Github Repo](https://github.com/jklepatch/eattheblocks)
  - [Dapp University](https://www.youtube.com/c/DappUniversity)
    - [Dapp University - Github Repo](https://github.com/dappuniversity)
  - [Moralis](https://www.youtube.com/channel/UCgWS9Q3P5AxCWyQLT2kQhBw)
    - [Moralis- Github Repo](https://github.com/MoralisWeb3)
  - [Austin Griffith](https://www.youtube.com/channel/UC_HI2i2peo1A-STdG22GFsA/featured)
    - [Austin Griffith - Github Repo](https://github.com/austintgriffith)
  - [Patrick Collins](https://www.youtube.com/c/PatrickCollins)
    - [Patrick Collins- Github Repo](https://github.com/PatrickAlphaC)
  - [Nader Dabit](https://www.youtube.com/c/naderdabit)
    - [Nader Dabit - Github Repo](https://github.com/dabit3)
  - [HashLips](https://www.youtube.com/channel/UC1LV4_VQGBJHTJjEWUmy8nA)
    - [HashLips - Github Repo](https://github.com/HashLips)
  - [EthGloba](https://www.youtube.com/c/ETHGlobal)
  - [Smart Contract Programmer](https://www.youtube.com/channel/UCJWh7F3AFyQ_x01VKzr9eyA/featured)


## Advanced Topics
- [Interplanetary FileSystem: IPFS](https://ipfs.io/)
- [IPFS simply explained](https://www.youtube.com/watch?v=5Uj6uR3fp-U)
- [IPFS, a beginner's guide at hackernoon](https://hackernoon.com/a-beginners-guide-to-ipfs-20673fedd3f)
- [IPFS and friends, a qualitative comparison of next generation Peer-to-Peer Data Networks](https://arxiv.org/pdf/2102.12737.pdf)
- [web3 storage, from the file coin creators](https://web3.storage/about/)

- [ENS (Ethereum Name Service](https://ens.domains/)
- [ENS explained](https://decrypt.co/resources/ethereum-name-service-ens-explained-guide-learn)
- [ENS: the good, the bad, and the ugly](https://arxiv.org/abs/2104.05185)
- [Why you need an ETH domain name](https://levelup.gitconnected.com/why-you-need-a-eth-domain-name-b16762fd16b4?gi=4d6a221cebd6)

- Upgradeable Contracts
- Oracles
- Formal Verification
- Scaling Chains
- Zero-Knowledge Proofs
- Ethereum 2.0,[links to Ethereum 2]
- Layer 2 Scaling
- [ChainLink](https://chain.link/)
* [Chain link tutorials](https://docs.chain.link/docs/beginners-tutorial/)
* [Oracles with Chainlink on Ethereum](https://medium.com/@aznagy/oracles-with-chainlink-on-ethereum-networks-tutorial-series-338b8a5f1726)

- The Graph
* [Building Graph QL APIs on Ethereum](https://dev.to/dabit3/building-graphql-apis-on-ethereum-4poa)

## Ethereum 2
- Sharding
- How to set up an ethereum 2 node
  * [spin up your own node](https://ethereum.org/en/developers/docs/nodes-and-clients/run-a-node/)

- Ethereum 2 node software
  * [Client divercity](https://ethereum.org/en/developers/docs/nodes-and-clients/client-diversity/)
  * [node as a service](https://ethereum.org/en/developers/docs/nodes-and-clients/nodes-as-a-service/)
- light nodes
  * [nimbus](https://nimbus.team/)
  * [helios](https://github.com/a16z/helios)
  * [lodestar](https://lodestar.chainsafe.io/)


## Ethereum Node Maps
* [Node tracker](https://etherscan.io/nodetracker)

## Other smart contract langugages
- [Vyper](https://vyper.readthedocs.io/en/stable/)
- Flint, a new Swift-like programming language for safer smart contracts
* [Flint programming language](https://www.imperial.ac.uk/media/imperial-college/faculty-of-engineering/computing/public/1718-ug-projects/Franklin-Schrans-A-new-programming-language-for-safer-smart-contracts.pdf)
* [Flint Repository](https://github.com/flintlang/flint)

## How Ethereum is Built
- Ethereum Improvement Proposals
- Core Ethereum

## Policy
- [Decentralisation](https://policyreview.info/concepts/decentralisation)
* [Hacker-engineers and Their Economies, by J.K.Brekke](https://www.tandfonline.com/doi/abs/10.1080/13563467.2020.1806223)

## Academic papers



## Non-Fungible Tokens
- [NFT-School](https://nftschool.dev/)

## News, Reviews and Interesting Sites
- [decrypt](https://decrypt.co/)
- [Fellowship of Ethereum Magicians](https://ethereum-magicians.org/)
- [Week in Ethereum News](https://weekinethereumnews.com/)
- [EthHub](https://ethhub.io/)
- DeFi Specific
  * DeFi Informational Resources
    - [DeFi Pulse](https://defipulse.com/)
    - [DeFi Prime](https://defiprime.com/)
    - [DeFi Rate](https://defirate.com/)
    - [The Defiant](https://thedefiant.io/)
- [Coindesk](https://www.coindesk.com/)
- [Coin Telegraph](https://cointelegraph.com/)




## History
Out of the Ether
Infinite machine


## Where to ask for Help
- [Ethereum at Stack exchange](https://ethereum.stackexchange.com/)
- [Gitter Ethereum](https://gitter.im/ethereum/solidity/)
- [r/Ethdev - Reddit Community](https://www.reddit.com/r/ethdev/)


## Additional GitHub Repositories
- [ConsenSys Discord Questions and Answers](https://github.com/ConsenSys-Academy/Emergent-Knowledge-Base)
- [ConsenSys Developer Tools List](https://github.com/ConsenSys/ethereum-developer-tools-list)
- [Awesome Ethereum](https://github.com/bekatom/awesome-ethereum)
- [Awesome Solidity](https://github.com/bkrem/awesome-solidity)

## Technical Research
- [Ethereum Research](https://ethresear.ch/)

## Where to find a job
- [cryptojobs](https://cryptojobslist.com)

## Companies
- [Protocols Labs](https://protocol.ai/join/)
- [Consensys](https://consensys.net)

## Project Brief

## Learning Outcomes

By Following the Companion,  learners will be able to **show evidence** of:

'''
1. Describe Blockchain primitives and basics and give examples for their usage.
2. Prepare and demonstrate setting up a development environment for Ethereum.
3. Compose basic Smart contracts and their tests and deploy them in a test environment.
4. Produce an evaluation of common security issues in smart contracts.
5. Build, Deploy and showcase a decentralised application on Ethereum.
'''

Indicative  Workload: Minimum 10 hours per week, with at least 4 hours per week hands-on practice, for 12 weeks
Recommended  Workload: 20 hours per week, with 10 hours per week devoted to hands-on practice, for 12 weeks.


_maintained by_
- [arlav](https://github.com/arlav)
- [HicoMcD](https://github.com/HicoMcD)
