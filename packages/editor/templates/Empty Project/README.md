# Empty DApp project

This is a bare bones dapp project containing a smart contract and boilerplate app files to get started.

## The smart contract

> Find the smart contract file in _contracts/MyContract.sol_

### 1. Configure

![Configure the contract](./images/hw-configure.png)

Configuring the contract allows you to set the name of the contract and the initial values sent to the constructor as arguments. You can configure the contract by clicking on the gear icon in the left panel.

### 2. Compile

![Compile the contract](./images/hw-compile.png)

Solidity is a compiled language, and you need to convert the Solidity code into bytecode before the contract can run. In the file tree under the contract file, you can compile the contract by clicking the _Compile_ sub-section, and output will appear in the _Output_ pane.

### 3. Deploy

![Deploy the contract](./images/hw-deploy.png)

Every smart contract runs at an address on the Ethereum blockchain, and must be deployed to an address before it can run. When using Studio, the browser simulates the network, but there are several test networks and one main network for the Ethereum blockchain.

Deploy the contract by clicking the _Deploy_ sub-section (nested under the contract file in the file tree), and output will appear in the _Output_ pane.

## Where to go from here

Check out the tutorials to find our more how to build your dapp.
