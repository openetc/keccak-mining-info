# ECBP-1: Best Practices and Software that Implements Keccak-256 Proof of Work.
Best Practices for Ethereum Classic Keccak-256 Mining. All practcies here comply with the ECIP-1049 standard and activate at Block 13,500,000. Estimated to be aroudn Q3 2021.

Every resource on this page is maintained by volunteers and companies. It is added to the page or removed based on whethe it complies with the protocl. All management of this is handled through Github Issues.

### Statuses: 

Experimental - Operates locally or demonstrates a concept. 
Beta - Compliant with ECIP-1049, but not yet ready for mainnet.
Live - Compliant with ECIP-1049 and ready for mainnet.
Unknown - Unknown, but possible.

## Full Node Software

Listed below are major nodes implementations in the ecosystem of the Ethereum Standard. We'll add or remove to the list based on Github issues and as we're notified of support:

| Name | URL | Language | Status | License
| --- | --- | --- | --- | --- | 
| Besu | https://github.com/hyperledger/besu | Java | Unknown | Apache 2.0
| Core Geth | https://github.com/etclabscore/core-geth | Go | Unknown | GPLv3
| Geth | https://github.com/ethereum/go-ethereum | Go | Unknown | GPLv3 
| Mantis | https://github.com/input-output-hk/mantis | Scala | Unknown | Apache 2.0
| Multi Geth  | https://github.com/multi-geth/multi-geth | Go | Unknown | GPLv3
| OpenEthereum | https://github.com/openethereum/openethereum | Rust | Uknown | GPLv3
| Turbo Geth | https://github.com/ledgerwatch/turbo-geth | Go | Unknown | GPLv3

Because of the weight of the Ethash algorithm, and the DAG, we encourage users concerned with performance and maintaibility to consider Lite Node support, which verifies only Keccak256 proof of work from the time of transition. This is far easier, and recommend for IoT based devices.

Full Node Support: Able to verify from genesis the Ethereum Classic network proof of work, both Ethash and Keccak-256.
Lite Node Support: Able to verify the Ethereum Classic network proof after implementation, post block 13,500,000, only Keccak-256. 

## Mining Software 

| Name | URL | Status | Info
| --- | --- | --- | --- |
| Claymore Miner | https://claymoredualminer.com/ | Unknown | Closed-Source and well known Ethereum GPU mining software.
| Cosmic Miner | https://bitbucket.org/LieutenantTofu/cosmic-v3 | Unknown | Capable of mining Keccak-256 for 0xBitcoin.
| Eth Miner | https://github.com/ethereum-mining/ethminer | Unknown | Open-source Ethereum GPU mining softeware.
| FPGA SHA3 Miner | https://github.com/miscellaneousbits/linux-socfpga-sha3-miner | Experimental | Open-source SHA3-256 FPGA mining software. 
| Python Toy Miner | https://github.com/snissn/ethereum-cpu-miner | Experimental | A Keccak-256 miner capable of 200,000 Keccak hashes per second on a core. Useful to understand block construction.

## Mining Hardware

## Pool Software 

## Exchanges

## Mining Pools
