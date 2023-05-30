# Consensus Algorithms

Consensus Mechanism, is a protocol or algorithm in a blockchain network or distributed ledger that enables participants to agree on a shared block or list of transactions. The consensus mechanism is used to ensure reliability, security, and integrity in distributed systems.

Consensus mechanisms are crucial components used in decentralized networks powered by blockchain technology. These mechanisms are employed to verify transactions, add new blocks, and ensure consensus and harmony among nodes that are part of the blockchain network.

###   The primary purposes of consensus mechanisms are as follows:
  
-Transaction Validation: The consensus mechanism ensures the validation of transactions occurring among nodes in the network. The verification and approval of transactions form the foundation of a reliable and secure blockchain network.

-Block Creation: The consensus mechanism is used for the creation and addition of new blocks. Participants contribute to the creation of the next block and reach an agreement on the order and content of the blocks.

-Prevention of Double Spending and Fraud: Consensus mechanisms are designed to prevent fraudulent activities such as double spending. They work to ensure that each transaction occurs only once and to establish a reliable transaction history.

-Network Security: Consensus mechanisms are used to ensure network security. They should be resistant to attack attempts and enable all participants in the network to transact securely.

![konsensus-5](https://github.com/umaysafak/Blockchain-Fundamentals/assets/83416728/8fafe9d9-dae0-450f-82ab-4516272d45ea)

### Some popular consensus algorithms include:
  
-Proof of Work (PoW): Proof of Work is the first consensus algorithm used in blockchains like Bitcoin. It is also known as mining. Miners use computational power to solve complex mathematical problems and validate blocks. Miners need to solve these problems and produce a hash in order to confirm a block. PoW is a consensus algorithm based on computational power.

-Proof of Stake (PoS): Proof of Stake is a consensus algorithm used in some blockchains like Ethereum 2.0. In Proof of Stake, the validation and confirmation of blocks rely on the stake or ownership of the blockchain. Validators lock up their assets for a certain period of time and, in return, gain the right to validate blocks.

-Delegated Proof of Stake (DPoS): Delegated Proof of Stake is a consensus algorithm used in certain blockchains like EOS. In DPoS, a specific number of delegates or stakeholders are chosen to validate blocks. These delegates verify and confirm blocks. DPoS is a faster and more scalable version of the PoS algorithm.

-Practical Byzantine Fault Tolerance (PBFT): PBFT is an algorithm used to provide secure and tolerant consensus in decentralized systems. PBFT is based on the concept of Byzantine Fault Tolerance (BFT) and enables nodes to reach an agreement through collaboration.

-Raft Consensus Algorithm: Raft is a consensus algorithm used in distributed systems such as blockchains. The Raft algorithm employs a leader-follower model and ensures that nodes are governed by a leader node. The leader node validates blocks and establishes consensus among the nodes.

-Proof of Authority (PoA): Proof of Authority is a consensus algorithm commonly used in private blockchains. In PoA, specific authorities or trusted nodes are selected to validate blocks. These nodes validate blocks and verify transactions. PoA provides advantages in terms of transaction speed and security, but it has a centralized structure.

-Tendermint: Tendermint is a consensus algorithm and blockchain engine for distributed applications. Tendermint utilizes the Byzantine Fault Tolerance (BFT) consensus algorithm and enables nodes to reach an agreement. This algorithm provides fast and reliable consensus.

-Proof of Elapsed Time (PoET): Proof of Elapsed Time is a consensus algorithm developed by Intel. PoET allows for the sequencing of transactions and the validation of blocks to occur randomly over a period of time. This algorithm provides fast and reliable consensus while reducing energy consumption.

-Byzantine Fault Tolerance (BFT): Byzantine Fault Tolerance is a consensus algorithm that is resilient against faulty nodes (Byzantine faults) in distributed systems like blockchain. BFT algorithms provide reliable consensus that can withstand the presence of faulty nodes and communication errors.

These consensus algorithms represent various approaches to different use cases and requirements in blockchain technology. Each algorithm offers different security models, performance characteristics, and scalability advantages. It is important to choose the appropriate consensus algorithm depending on the requirements and use case of your project.
