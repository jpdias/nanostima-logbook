## Nanostima Project
 
### Logbook

1. [1-13]/05/17
    - SOTA:
        - Why Distributed Public Ledgers such as Blockchain will not solve the identification and thus the authentication problem [LINK](https://www.kuppingercole.com/blog/kuppinger/why-dpl-will-not-solve-the-identification-and-thus-the-authentication-problem)
        - The Voyage of Discovery: Blockchain for Pharmaceuticals and Medical Devices  [LINK](http://beyondstandards.ieee.org/general-news/voyage-discovery-blockchain-pharmaceuticals-medical-devices/)
        
        - Proof-of-work
            - [PoET-intel](https://www.quora.com/What-is-your-opinion-on-PoET-intel-blockchain)
            - [Blockchain-Consensus-Models](https://www.persistent.com/wp-content/uploads/2017/04/WP-Understanding-Blockchain-Consensus-Models.pdf)
            - [blockchain-consensus](http://dailycoin.info/short-guide-blockchain-consensus-protocols/)

    - Hands-on: 
        - Etherum: 
            - [use-geth-to-setup-your-own-private-ethereum](https://medium.com/blockchain-education-network/use-geth-to-setup-your-own-private-ethereum-blockchain-86f1200e6d40)
            - [private-chain](https://souptacular.gitbooks.io/ethereum-tutorials-and-tips-by-hudson/content/private-chain.html)
        - [Sawtooth lake](https://intelledger.github.io/introduction.html)
        - [Naivechain](https://github.com/lhartikk/naivechain)

 2. [13-31]/5/17
    - Implementation of a PoC of a blockchain for Access Authorization
        - Based on Access Control List and Naivechain
        - Reverse hash calculation as Proof-of-work
        
        ![Example of Ops in Blockchain](./resources/Ops.PNG)


### Sidenotes

1. How to "snapshot" generic/random operations? 
  - Bitcoin has always a value / transaction stable specification
  - R: ACL
2. Need of local storage?
3. Temporal access vs rule-override
4. Group and individual ACL (e.g. nurses vs doctor x)
  - Fine-Grained Access Control with Object-Sensitive Roles
5. Permissions: Read / Write / R&&W
6. Snapshots?
  - At every 10 iterations do a snapshot, adding metadata
  - {ops: [ -- ], meta: {timestamp, entityname, snapshot(T/F)} }