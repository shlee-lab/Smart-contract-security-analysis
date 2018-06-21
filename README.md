# Papers and Tools for Smart Contract Security Analysis

This space tries to show all papers about security analysis of smart contract.

## Contents

* [Overview](#overview)
* [Tools](#security-analysis-tools)
* [2018 Papers](#2018-papers) : Proceeding
* [2017 Papers](#2017-papers)
* [2015-6 Papers](#2015-6-papers)
* [Security SCI(E) Journal list](#security-sci(e)-journal-list)
* [Links / Tutorials](#links--tutorials)
* [References](#references)
* * *

### Overview
| Vulnerability | ReEntrancy | Immutable Bugs | Minhandled Exceptions | TOD | Untrusted Value Dependency | Gas Costly Pattern | tx.origin |
|------------------------------|------------|----------------------------------------------------------------|----------------------------------------------|-----|----------------------------|--------------------|-------------|
| Subordinate Items |  | Integer Overflow/Underflow / Callstack Depth / Short Address | Unchecked Send / Unchekced Low Level Calls |  | Blackhash / Timestamp |  |  |
| Characteristics /Correlation |  |  | DoS, Interaction |  | Randomness | DoS | Interaction |

### Security Analysis Tools
*Tools which are available. There can be paid services to use full features.*

| Name | Available Path | Features | Related Paper |
| :---:         |     :---      |     :---  |      :---: |
| Oyente        | http://oyente.melon.fund  | symbolic execution  | [[pdf]](https://eprint.iacr.org/2016/633.pdf)    |
| Securify     | http://securify.ch    | formal verification  |  [[pdf]](https://arxiv.org/pdf/1806.01143.pdf)   |
| Remix        |  http://remix.ethereum.org     |  solidity compiler, debugger    |    |
| SmartCheck        |    http://tool.smartdec.net     | static code analysis   |  |
| Mythril        |  https://github.com/ConsenSys/mythril     |   concolic and taint analysis   |  [[pdf]](https://github.com/b-mueller/smashing-smart-contracts/blob/master/smashing-smart-contracts-1of1.pdf)  |
| why3        |   http://why3.lri.fr/try/          | formal verification, general tool   |  |


### 2018 papers
*Newly published papers (in this year) which are worth reading*
- **Securify: Practical Security Analysis of Smart Contracts** (2018), Petar Tsankov et al. [[pdf]](https://arxiv.org/pdf/1806.01143.pdf)
- **Ekiden: A Platform for Confidentiality-Preserving, Trustworthy, and Performant Smart Contract Execution** (2018), Raymond Cheng et al. [[pdf]](https://arxiv.org/pdf/1804.05141.pdf)
- **Smart Contracts: Security Patterns in the Ethereum Ecosystem and Solidity** (2018), Maximilian Wöhrer and Uwe Zdun. [[pdf]](http://eprints.cs.univie.ac.at/5433/7/sanerws18iwbosemain-id1-p-380f58e-35576-preprint.pdf)
- **ZEUS: Analyzing Safety of Smart Contracts** (2018), Sukrit Kalra et al. [[pdf]](https://www.ndss-symposium.org/wp-content/uploads/sites/25/2018/02/ndss2018_09-1_Kalra_paper.pdf)
- **Finding The Greedy, Prodigal, and Suicidal Contracts at Scale** (2018), Ivica Nikolic et al. [[pdf]](https://arxiv.org/pdf/1802.06038.pdf)
- **Scilla: a Smart Contract Intermediate-Level LAnguage** (2018), Ilya Sergey et al. [[pdf]](https://arxiv.org/pdf/1801.00687.pdf)
- **Formal verification of smart contracts based on users and blockchain behaviors models** (2018), Tesnim Abdellatif et al. [[pdf]](https://hal.archives-ouvertes.fr/hal-01760787/document)
- **Smashing Ethereum smart contracts for fun and real profit** (2018),  Bernhard Mueller. [[pdf]](https://github.com/b-mueller/smashing-smart-contracts/blob/master/smashing-smart-contracts-1of1.pdf)
- **Towards Verifying Ethereum Smart Contract Bytecode in Isabelle/HOL** (2018), Sidney Amani et al. [[pdf]](http://ssrg.nicta.com/publications/csiro_full_text//Amani_BSB_18.pdf)
- **SoK: unraveling Bitcoin smart contracts** (2018), Nicola Atzei et al. [[pdf]](https://eprint.iacr.org/2018/192.pdf)
- **From contracts to “smart” contracts** (2018), Massimo Bartoletti et al. [[pdf]](http://www.dmi.unipg.it/DLTWorkshop/presentazioni%20DLT%20workshop/bartoletti.pdf)
- **BitML : a calculus for Bitcoin smart contracts** (2018), Massimo Bartoletti et al. [[pdf]](https://eprint.iacr.org/2018/122.pdf)
- **Quantitative Analysis of Smart Contracts** (2018), Krishnendu Chatterjee et al. [[pdf]](http://pub.ist.ac.at/~akafshda/paperpdfs/esop2018.pdf)
- **Smart Contracts Vulnerabilities: A Call for Blockchain Software Engineering?** (2018), Giuseppe Destefanis et al. [[pdf]](http://dspace.stir.ac.uk/bitstream/1893/27135/1/smart-contracts-vulnerabilities-3.pdf)
- **Smart Contracts: Security Patterns in the Ethereum Ecosystem and Solidity** (2018), Maximilian Wöhrer and Uwe Zdun. [[pdf]](http://eprints.cs.univie.ac.at/5433/7/sanerws18iwbosemain-id1-p-380f58e-35576-preprint.pdf)


### 2017 papers
*Published papers in 2017 which are worth reading*
- **Ethereum Smart Contracts: Security Vulnerabilities and Security Tools** (2017), Ardit Dika. [[pdf]](https://brage.bibsys.no/xmlui/bitstream/handle/11250/2479191/18400_FULLTEXT.pdf?sequence=1)
- **Validation and Verification of Smart Contracts: A Research Agenda** (2017),  Daniele Magazzeni et al. [[pdf]](https://core.ac.uk/download/pdf/96761687.pdf)
- **Designing Secure Ethereum Smart Contracts: A Finite State Machine Based Approach** (2017), Anastasia Mavridou et al. [[pdf]](https://fc18.ifca.ai/preproceedings/101.pdf)
- **Ethereum: state of knowledge and research perspectives** (2017),Sergei Tikhomirov. [[pdf]](https://allquantor.at/blockchainbib/pdf/tikhomirov2017ethereum.pdf)
- **Quantstamp : The protocol for securing smart contracts** (2017), Richard Ma et al. [[pdf]](https://crushcrypto.com/wp-content/uploads/2017/10/QSP-Whitepaper.pdf)
- **Findel: Secure Derivative Contracts for Ethereum** (2017), Alex Biryukov et al. [[pdf]](https://orbilu.uni.lu/bitstream/10993/30975/1/Findel_2017-03-08-CR.pdf)



### 2015-6 papers
*Published papers in 2015-6 (2015 is when smart contract was born) which are worth reading*
- **Making Smart Contracts Smarter** (2016), Loi Luu et al. [[pdf]](https://eprint.iacr.org/2016/633.pdf)
- **Short Paper: Formal Verification of Smart Contracts** (2016), Karthikeyan Bhargavan et al. [[pdf]](https://www.cs.umd.edu/~aseem/solidetherplas.pdf)
- **A Survey of Attacks on Ethereum Smart Contracts (SoK)** (2016),Nicola Atzei et al. [[pdf]](https://eprint.iacr.org/2016/1007.pdf)
- **Writing Secure Smart Contracts** (2016), IC3. [[pdf]](http://upyun-assets.ethfans.org/uploads/doc/file/f035d9aa385448f280a785715fff89e0.pdf?_upd=devcon-ic3.pdf)
- **Step by Step Towards Creating a Safe Smart Contract: Lessons and Insights from a Cryptocurrency Lab** (2015), Kevin Delmolino et al. [[pdf]](https://eprint.iacr.org/2015/460.pdf)

* * *

### Security SCI(E) Journal list

* IEEE Transactions on Information Forensics and Security [[web]](http://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=10206)
* Computer & Security[[web]](http://www.elsevier.com/wps/find/journaldescription.cws_home/405877/description#description)
* IET Information Security[[web]](http://www.ietdl.org/IET-IFS)
* ACM Transactions on Information and System Security[[web]](http://tissec.acm.org/)
* International Journal of Information Security[[web]](http://www.springerlink.com/content/107927/)
* Security and Communication Networks[[web]](http://www.wiley.com/bw/journal.asp?ref=1939-0114)
* IEEE Security & Privacy[[web]](	http://www.computer.org/portal/web/security/home)
* IEEE Transactions on Dependable and Secure Computing [[web]](http://www.computer.org/tdsc/)
* Security and Communication Networks[[web]](http://onlinelibrary.wiley.com/journal/10.1002/(ISSN)1939-0122)
* Computer Fraud & Security[[web]](http://www.elsevierscitech.com/nl/cfs/home.asp )

### Links / Tutorials

*(Links)*
- **DASP TOP 10** [[web]](https://www.dasp.co/)
- **Yoichi's Formal Verification of Ethereum Contracts** [[web]](https://github.com/pirapira/ethereum-formal-verification-overview/)
- **How Formal Verification Can Ensure Flawless Smart Contracts** (2018), Bernhard Mueller. [[web]](https://media.consensys.net/how-formal-verification-can-ensure-flawless-smart-contracts-cbda8ad99bd1)
- **Reversing Ethereum Smart Contracts** [[web]](https://arvanaghi.com/blog/reversing-ethereum-smart-contracts/)

- **Smart Contract Languages** [[web]](https://github.com/s-tikhomirov/smart-contract-languages)

*(Tutorials)*
- empty

### References
- **Ethereum: A NEXT GENERATION SMART CONTRACT & DECENTRALIZED APPLICATION PLATFORM** (2015),  Vitalik Buterin. [[pdf]](http://www.the-blockchain.com/docs/Ethereum_white_paper-a_next_generation_smart_contract_and_decentralized_application_platform-vitalik-buterin.pdf)
- **Ethereum Yellow Paper**[[pdf]](https://ethereum.github.io/yellowpaper/paper.pdf)
- **Bitcoin: A Peer-to-Peer Electronic Cash System** (2009), Satoshi Nakamoto. [[pdf]](https://bitcoin.org/bitcoin.pdf)



## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
