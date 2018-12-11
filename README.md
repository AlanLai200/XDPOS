# About the XDPOS: XinFin Delegated proof of stake consensus

XinFin’s token XDC supplants proof-of-work consensus algorithm (popularly linked with mining and High Power Consumption) with proof-of-stake consensus algorithm, fundamentally using the concept of “validators” to Optimise Speed of the transaction, efficiency, reduce the cost of the infrastructure. This 
Validators are special nodes used in the DPoS consensus algorithm which validate each transaction occurring on the blockchain network. The result of this validation is to finally append the transaction on the blockchain. A transaction may be accepted by the validator or rejected. 

XDPoS relies on a system of 5000 Masternodes and 21 Validator node with Proof of Stake consensus.

XDPoS Supports all EVM-compatible smart-contracts and Protocol function but optimize GAS to reduce transaction fees near to zero to the user to make network more use-case friendly. 

XDPoS support Inbuild KYC/AML Feature to create Public trust network.

Our website : Https://XinFin.org

Github : https://github.com/XinFinorg 

Developer Resource Document and API : http://docs.xinfin.org/ 

More detail About XDPoS:

Here is the scope for the XinFin Blockchain DPoS (Delegated Proof-of-Stake) Consensus Network Scope.

Reward: 10,000 USD worth of XDC
1. Staking
First a user will send his coins to the contract, that will register what the user staked. The user will have to wait for 2 epochs (epoch N+2N+2) before being able to vote for a delegate.

2. Voting
After 2 epochs, a user can vote for a delegate with the coins he staked. His vote will be effective in the epoch N+2N+2, NN being the current epoch.
A new vote can be casted every 2 epochs.
We like to  choose LL validators for a certain epoch NN

3.  Master Node-KYC AML Certificate upload
Propose Masternode-holder need to upload 3 Third party certification for KYC and AML : The one who wants to become a masternode needs to complete the KYC Process. This document will be open to public.

4. Validator Node- Delegate Selection
One who become the part of the masternode network need to stake XDC and the XDC will be locked. No one can be the part of the network node without staking XDC. Minimum 1000000 XDC 
Highest 21 XDC stake based node will be act as Validator node. Rest node will be act as backup node or/and act as private node to host internal use case application and they can able to connect public node using parity bridge. Total masternode should be cap to 5000

5. Backup/Private Nodes
Incase, if one of the delegate is down out of 21 node, then the 1st waiting delegate node (22nd node) according to the stake will join the network and the node which was down will be removed from the network for 5 days.
Once the down node is ready to function, it will send a message into the network about its availability and it will again enter the network by replacing the node which replaced it provided it holds higher stake.

6. Reward to MasterNode
The delegates which are consistently propagating blocks will be rewarded only. Also it depends on how much time the delegate was available for block validation. Reward will be given on monthly basis from new Block generated in Network.
Daily Reward Calculation: 1 coin after creating 1000 blocks reward will be calculated based on stake and on daily basis but credit to wallet on monthly basis.

7.Biased Node / Prejudiced behavior
Delegates consistently propagating blocks late
Delegates being offline for more than 24 hours
If the network finds this behavior. Stake should be reduce from 4% to 100% depends on task execute by the node.
Wrong KYC /AMA certificate lead to 100% stake reduction. Such masternode will be out of the network.
Suppose if a node is misbehaving and we are removing it ,so will the node be present in the validators list or the node is no more part of the network.

DPoS References Github Repo:
Existing DPOS projects for Refernce Code:
TomoChain: https://github.com/tomochain/tomochain/tree/master/consensus/posv

Tron: https://github.com/tronprotocol/

EOS : https://github.com/EOSIO

Ethereum Proof Of Work (PoW) Conensus Refernce code: 
https://github.com/riteshkakkad/go-ethereum/tree/master/consensus

