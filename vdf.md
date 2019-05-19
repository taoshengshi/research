## VDF Research
## 关于成立VDF中国技术社区的倡议:
拜占庭将军问题和Paxos算法的提出近40年，真正大规模应用是过去10年，因此Leslie Lamport在2013年获得图灵奖。

Bitcoin从2008年提出至今已过10年，其共识机制PoW算法也稳定运行超过10年。

2018年6月12日VDF函数机制提出，即将满一年。

VDF的提出，是应用加密学，分布式系统和区块链领域的重大技术突破，为区块链的consensus from resource，proof of spacetime，secert leader election等难题奠定可行性的基础。

不仅如此，作为一种delay service 和 randomness beacon service，也可以应用到其他领域。

所以，过去的十年是paxos和pow的十年，未来的十年将是VDF的十年。

因此我倡议成立VDF中国社区，共建硬件和软件生态，一起研究，一起探索新的应用领域。

请志同道合者联系：taoshengshi01@gmail.com


#### What’s a Verifiable Delay Function (VDF)?
A verifiable delay function is a function that takes a certain amount of time to compute, and cannot be accelerated through parallelization/additional processors. Once computed, the output can be quickly verified by anyone.

Verifiable Delay Functions take a prescribed time to compute, even on a parallel computer, yet produce a unique output that can be efficiently and publicly verified.

#### How Can VDFs be used?
VDFs can be used to create resource-efficient blockchain protocols, and can assist in the construction of proof-of-replication algorithms. You can find more detail about these use cases and others here.

VDFs have a wide variety of decentralized systems: public randomness beacons, leader election in consensus protocols, and proofs of replication.

#### Is this just a new type of mining?
No -- While VDFs can be seen as a type of ‘proof-of-work’ or hashcash, VDFs differ in that the work can not be greatly parallelized. VDFs have the potential to help create secure consensus algorithms with drastically lower energy costs.

#### Can we use them today?
 Efficient VDF constructions exist today and can be implemented. However, if malicious actors have access to specialized hardware they can speed up their evaluation, breaking the security of the protocols that rely on VDFs :(

#### VDFs channels
funded 50/50 by Protocol Labs and the Ethereum Foundation
* https://www.supranational.net/
* https://github.com/supranational
* RSA MPC : ligero (to be funded)
* https://vdfresearch.org/
* https://twitter.com/drakefjustin
* https://ethresear.ch/
* [MIT VDF Day](https://dci.mit.edu/vdfday)    

#### VDFs read list
Constructions:    
2015—Lenstra, Wesolowski [A Random Zoo: Sloth, Unicorn, and Trx](https://eprint.iacr.org/2015/366.pdf)    
2015—Lenstra, Wesolowski [A Random Zoo: Sloth, Unicorn, and Trx -- slides](https://pdfs.semanticscholar.org/4acb/198ee26778843c4986cc57a1b5985191800f.pdf)   
2018 (12 June)—Boneh, Bonneau, Bünz, Fisch [Verifiable Delay Functions](https://eprint.iacr.org/2018/601.pdf)   
2018 (12 June)—Boneh, Bonneau, Bünz, Fisch [Verifiable Delay Functions -- slides](https://crypto.iacr.org/2018/slides/28858.pdf)   
2018 (12 June)—Boneh, Bonneau, Bünz, Fisch [Verifiable Delay Functions -- vedio](https://www.youtube.com/watch?v=_-feyaZZjEw)   
2018 (22 June)—Pietrzak [Simple Verifiable Delay Functions](http://drops.dagstuhl.de/opus/volltexte/2018/10153/pdf/LIPIcs-ITCS-2019-60.pdf)   
2018 (20 June)—Wesolowski [Efficient verifiable delay functions](https://eprint.iacr.org/2018/623.pdf)    
2018 (30 July)—Boneh, Bünz, Fisch  [A Survey of Two Verifiable Delay Functions](http://theory.stanford.edu/~dabo/papers/VDFsurvey.pdf)   
2019 (13 Feb)—De Feo, Masson, Petit, Sanso [Verifiable Delay Functions from Supersingular Isogenies and Pairings](https://eprint.iacr.org/2019/166.pdf)   

[TRUST, AND PUBLIC ENTROPY:A UNICORN HUNT](https://csrc.nist.gov/csrc/media/events/random-bit-generation-workshop-2016/documents/presentations/sessionv-3-benjamin-wesolowski-presentation.pdf)    
[A Subexponential Time Algorithm for the Dihedral Hidden Subgroup Problem with Polynomial Space](https://arxiv.org/pdf/quant-ph/0406151.pdf)         
[SoK: Transparent Dishonesty: front-running attacks on Blockchain.](https://users.encs.concordia.ca/~clark/papers/2019_wtsc_front.pdf)    

Explainers/Articles:   
2019—Bruno Skvorc [Two Point Oh: Randomness](https://our.status.im/two-point-oh-randomness/)   
2018—Bruno Skvorc [Two Point Oh: The Beacon Chain](https://our.status.im/two-point-oh-the-beacon-chain/)   
2018—Bruno Skvorc [Two Point Oh: Explaining Validators](https://our.status.im/two-point-oh-explaining-validators/)  
2019—Maxwell Foley [Qi Hardware—VDF FAQ pt. 1](https://qihardware.org/2019/03/17/vdf-faq-1/)   
Oct 2018—Arthur Breitman [Better randomness](https://medium.com/tezos/a-few-directions-to-improve-tezos-15359c79ec0f)    
Oct 2018—Trail of Bits [Introduction to Verifiable Delay Functions (VDFs)](https://blog.trailofbits.com/2018/10/12/introduction-to-verifiable-delay-functions-vdfs/)   
Sep 2018—Justin Drake [Minimal VDF randomness beacon](https://ethresear.ch/t/minimal-vdf-randomness-beacon/3566)   
Aug 2018—Jeromy Johnson [A VDF Explainer](https://reading.supply/@whyrusleeping/a-vdf-explainer-5S6Ect)   
Jul 2018—Danny Ryan [VDFs are not Proof of Work](https://medium.com/@djrtwo/vdfs-are-not-proof-of-work-91ba3bec2bf4)   
Apr 2018—Anatoly Yakovenko [Proof of History: A clock for blockchain](https://medium.com/solana-labs/proof-of-history-a-clock-for-blockchain-cf47a61a9274)    

Randomness beacons:   
2018 (26 September)—Drake [Minimal VDF Randomness Beacon](https://ethresear.ch/t/minimal-vdf-randomness-beacon/3566)    
2018 (16 July)—Drake [VDF-based RNG with Linear Lookahead](https://ethresear.ch/t/vdf-based-rng-with-linear-lookahead/2573)    
2018 (8 June)—Jensen, Kristensen, Michno [Developing a Trustworthy Randomness Beacon for the Public](https://projekter.aau.dk/projekter/files/281196661/main.pdf)    
2017—Bünz, Goldfeder, Bonneau [Proofs-of-delay and Randomness Beacons in Ethereum](http://www.jbonneau.com/doc/BGB17-IEEESB-proof_of_delay_ethereum.pdf)    
2017—Bünz, Goldfeder, Bonneau [Proofs-of-delay and Randomness Beacons in Ethereum - slides](https://drive.google.com/file/d/0B5PcPC6ZC_Gyb3V6NnRMZ2VZMFU/edit)   
2016—Darknet [RANDAO: A DAO Working as RNG of Ethereum](https://steemit.com/ethereum/@darknet/randao-1-0-is-here-or-a-dao-working-as-rng-of-ethereum)    
1998—Goldschlag, [Stubblebine Publicly Veriable Lotteries: Applications of Delaying Functions](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.53.284&rep=rep1&type=pdf)    

Proofs of space/replication:   
2018 (August)—Fisch, Bonneau, Greco, Benet [Scaling Proof-of-Replication for Filecoin Mining](https://web.stanford.edu/~bfisch/porep_short.pdf)   
2018 (24 July)—Fisch [Tight Proofs of Space and Replication](https://eprint.iacr.org/2018/702.pdf)    
2018 (16 July)—Cecchetti, Miers, Juels [PIEs: Public Incompressible Encodings for Decentralized Storage](https://eprint.iacr.org/2018/684.pdf)    
2018 (14 July)—Fisch [PoReps: Proofs of Space on Useful Data](https://eprint.iacr.org/2018/678.pdf)   
2018 (17 Feb)—Pietrzak [Proofs of Catalytic Space](https://eprint.iacr.org/2018/194.pdf)   
2017—Benet, Dalrymple, Greco [Proof of Replication](https://filecoin.io/proof-of-replication.pdf)   
2017—Cohen [Proofs of Space and Time](https://cyber.stanford.edu/sites/g/files/sbiybj9936/f/bramcohen.pdf)   
2014—Lerner [Proof of Unique Blockchain Storage](Proof of unique blockchain storage)    
2013—Dziembowski, Faust, Kolmogorow, Pietrzak [Proofs of Space](https://eprint.iacr.org/2013/796.pdf)   
[video youtube PoS](https://www.youtube.com/watch?v=evx7gH_R-Mc)  
(pebbling-based PoS)[SpaceMint: A Cryptocurrency Based on Proofs of Space]()    
[Proof of Space from Stacked Expanders]()    
[Beyond Hellman’s Time-Memory Trade-Offs with Applications to Proofs of Space]()    

Other relevant reading:    
2018 (21 July)—Buterin STARKs, [Part 3: Into the Weeds](https://vitalik.ca/general/2018/07/21/starks_part_3.html)   
2018 (9 Feb)—Cohen, Pietrzak [Simple Proofs of Sequential Work](https://eprint.iacr.org/2018/183.pdf)     
2014—Gnos1s [RSA UFO](https://anoncoin.github.io/RSA_UFO/)   
2013—Mahmoody, Moran, Vadhan [Publicly Verifiable Proofs of Sequential Work](https://www.cs.virginia.edu/~mohammad/files/papers/15%20TimeStamp.pdf)    
2001—Buchmann, Hamdy [A Survey on IQ Cryptography](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.5.7192&rep=rep1&type=pdf)   
2000—Boneh, Naor [Timed Commitments](https://www.iacr.org/archive/crypto2000/18800237/18800237.pdf)   
1999—Sander [Efficient Accumulators without Trapdoor Extended Abstract](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.28.4015&rep=rep1&type=pdf)   
1996—Rivest, Shamir, Wagner [Time-lock Puzzles and Timed-release Crypto](https://people.csail.mit.edu/rivest/pubs/RSW96.pdf)   

video：   
Justin Drake: [Ethereum's Audacious Roadmap to Build a True World Computer](https://www.youtube.com/watch?v=QDwaAnhSJk8)   
2019—Dan Boneh [Verifiable Delay Functions](https://www.youtube.com/watch?v=dN-1q8c50q0)   
2019—Jeromy Johnson [VDFs and Filecoin](https://www.youtube.com/watch?v=GZZ2G9bPXsM)   
2019—Justin Drake [Towards Productions VDFs](https://www.youtube.com/watch?v=Kmm6BXXfsnI)   
2019—Benjamin Wesolowski [A Hybrid VDF prover](https://www.youtube.com/watch?v=NtzNdsbkFt0)   
2019—Erdinc Ozturk [Low Latency Modular Multiplication](https://www.youtube.com/watch?v=ITf4Wt2YgDE)   
2019—Abhi Shelat [Threshold Factoring from Factoring](https://www.youtube.com/watch?v=RwrJXO_ecRI)   
2018—Ben Fisch [Verifiable Delay Functions: Applications and Candidate Constructions](https://www.youtube.com/watch?v=qUoagL7OZ1k)   
2018-Justin Drake [Ethereum 2.0 randomness](https://www.youtube.com/watch?v=zqL_cMlPjOI)   
2018-Justin Drake [Ethereum 2.0 randomness - Devcon4](https://www.youtube.com/watch?v=rUOBPu4W28c)   
2017—Benedikt Bünz [Proofs-of-Delay and Randomness Beacons in Ethereum](https://www.youtube.com/watch?v=kK4qN2K44Ms&t=918s)   
2017—Joseph Bonneau [Verifiable Lotteries](https://www.youtube.com/watch?v=1jVPVPxwFWo)   
Justin Drake:[The Ethereum Community Conference](https://www.youtube.com/watch?v=83DGZPJoyPQ)   

drg:   
[Expander Graphs](https://people.seas.harvard.edu/~salil/pseudorandomness/expanders.pdf)   
[An introduction to expander graphs](https://people.math.ethz.ch/~kowalski/expander-graphs.pdf)    
[Basic Facts about Expander Graphs](http://www.wisdom.weizmann.ac.il/~oded/COL/expander.pdf)    
[Practical Graphs for Optimal Side-Channel Resistant Memory-Hard Functions](https://eprint.iacr.org/2017/443.pdf)   

consensus:   
如果比特币没有出块奖励 [On the Instability of Bitcoin Without the Block Reward]()   
[Snow White: Provably Secure Proofs of Stake]()   
[Ouroboros:A Provably Secure Proof-of-Stake Blockchain Protocol]()   
[ALGORAND: the efficient and democratic ledger]()   
[The Honey Badger of BFT Protocols](https://eprint.iacr.org/2016/199.pdf)   
https://github.com/poanetwork/hbbft   
https://medium.com/poa-network/poa-network-how-honey-badger-bft-consensus-works-4b16c0f1ff94    
[RANDO Whitepaper](https://www.randao.org/whitepaper/Randao_v0.85.pdf)    


#### VDF Pojects  
* [chia.net](https://www.chia.net/) 
* https://qihardware.org
* [VDF FAQ](https://qihardware.org/2019/03/17/vdf-faq-1/)
* [ethereum.org](https://ethresear.ch/)   
* [protocol.ai](https://protocol.ai/)    
* [Ethereum Research on VDF](https://ethresear.ch/t/verifiable-delay-functions-and-attacks/2365)   
* [VDF Research Effort](https://vdfresearch.org/) 
* https://web.stanford.edu/~bfisch/   
* http://itcs-conf.org/itcs19/itcs19-accepted.html
* https://crypto.stanford.edu/~buenz/
* https://notes.ethereum.org/s/BJC7m0gB7

    


