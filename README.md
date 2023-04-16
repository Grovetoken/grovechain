## What Is an Ethereum Virtual Machine (EVM)?

Ethereum Virtual Machine (EVM) is a computation engine which acts like a
decentralized computer that has millions of executable projects.

It acts as the virtual machine which is the bedrock of Ethereum's entire
operating structure.

It is considered to be the part of the Ethereum that runs execution and
smart contract deployment.

The role of the EVM is to deploy a number of extra functionalities to
the Blockchain to ensure users face limited issues on the distributed
ledger.

Every Ethereum node runs on the EVM to maintain consensus across the
blockchain.

Ethereum facilitates something called smart contracts, a piece of code
that is running on Ethereum.

EVM is completely isolated meaning the code inside the EVM has no access
to network, file system or other processes.

Ethereum has two types of accounts: Externally Owned Accounts (EOA) and
Contract Accounts, both of which are treated equally under the EVM.

Account abstraction tries to reduce this to just one account meaning
both EOAs and Contract Accounts function like each other.

EOAs are controlled by private keys, meanwhile contract accounts are
stored in the smart contracts, also known as smart wallets.

A contract which is written in the smart-contract coding is converted
into something called a bytecode.

Most of the source code for using smart contracts is done using
programming language from Solidity.

It is then converted into opcodes for the EVM to interpret.

The EVM then uses the operation codes in order to complete certain
tasks.

So, the EVM works like a large decentralized or master computer to
complete all types of tasks on the blockchain.

EVM is one of the biggest projects in the world of cryptocurrencies.

What Is an Ethereum Virtual Machine (EVM) Nodes?\
\
Blockchain nodes are network stakeholders and their devices are
authorized to keep track of the distributed ledger and serve as
communication hubs for various network tasks.

A Blockchain node's primary job is to confirm the legality of each
subsequent batch of network transactions, known as blocks. In addition,
allocating a unique identifier to each node in the network helps to
distinguish a node from other nodes easily.

A Proof-of-Work (PoW) Blockchain, such as Bitcoin (BTC) or Monero (XMR),
includes miners who are responsible for the following.

Only "full nodes" must store all Blockchain transactions on their
devices. These nodes are in charge of validating blocks and
transactions.

On the other hand, lightweight nodes have low storage requirements
because they just need to download block headers to verify transactions.
A block reward is not always included in either of these versions of a
full node.

### Functions of nodes

A block broadcasts all the network nodes when a miner seeks to add a new
block of transactions to the Blockchain. Based on the legitimacy of a
block, nodes might accept or reject it (validity of signatures and
transactions). When a node accepts a new block of transactions, it saves
and stores it on top of the existing blocks. In a nutshell, nodes do the
following:

-   Nodes determine whether or not a block of transactions is legitimate
    > and accept or reject it.

-   Nodes save and store transaction blocks (storing Blockchain
    > transaction history).

-   This transaction history is broadcast and disseminated by nodes to
    > other nodes that may need to synchronize with the Blockchain (
    > updates on transaction history are important).

### Securing a Blockchain

The availability of a Blockchain node is another approach to classifying
it. For example, an "online node" is a node that is assigned to send
updates all across the network consistently and always to be online.

On the other hand, offline nodes only need to download the most recent
copy of the ledger every time they rejoin the network to stay in sync
with the rest. This process is termed synchronizing with the Blockchain.

A single node can potentially operate a complete Blockchain, but because
it is kept on a single device, it is particularly vulnerable to power
outages, hackers, and systemic malfunctions. The more complete nodes a
Blockchain has, the better it can withstand such disasters. It will be
difficult for a corrupt party to wipe out all of the Blockchain data at
once since the data is dispersed over so many machines. A single node
may potentially keep a full Blockchain running even if a significant
number of nodes fall offline and become unavailable due to a worldwide
catastrophe.

Even if all nodes fall, it only takes one node with the whole Blockchain
history to back up and restore access to all the data.\
\
\
How to install and run GroveChain nodes?\
\
Here are the step-by-step instructions for installing and running a
blockchain node using the Besu client:

1.  First, you will need to download the Besu client from the official
    > Github repository. You can do this by navigating to the following
    > URL:
    > [[https://github.com/hyperledger/besu/releases]{.underline}](https://github.com/hyperledger/besu/releases).
    > From there, select the latest stable release version of the client
    > that matches your operating system and download the appropriate
    > package.

2.  Once you have downloaded the Besu client, you will need to obtain
    > the genesis.json file that we provide in this respiratory. This
    > file specifies the initial state of the blockchain, including
    > things like the initial distribution of tokens, block parameters,
    > and more. Make sure you have a copy of the genesis file just in
    > case.

3.  Next, you will need to take a configuration file that specifies the
    > parameters of your node. This file includes information about
    > things like the network ID, the bootnodes, and the location of the
    > genesis.json file. You will also need to set up your data
    > directory and other options that you wish to use. Make sure that
    > your configuration file is properly formatted and that it
    > references the correct genesis.json file.

4.  Once you have created your configuration file, you will need to set
    > the path to it in the start.sh file that is included in this
    > respiratory. Open this file and look for the line that specifies
    > the path to your configuration file. Update this line to reflect
    > the location of your configuration file on your system.

5.  Finally, you can run your Besu node by executing the start.sh file.
    > This will start your node and connect it to the network. You
    > should see logs output to your terminal indicating that your node
    > is syncing with the network.

Congratulations! You have successfully installed and run a Grovechain
node using a custom genesis.json file and configuration. From here, you
can continue to interact with the network using the Besu client APIs and
tooling.
