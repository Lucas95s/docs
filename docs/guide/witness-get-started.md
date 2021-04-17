# Getting started with Automata Witness

<!-- ## Table of Contents

- [Introduction](#introduction)
- [Setting up MetaMask](#setting-up-metamask)
- [Adding Automata Network to your networks](#adding-automata-network-to-your-networks)
- [Connecting Your Metamask Wallet](#connecting-your-metamask-wallet)
- [Getting tokens](#getting-tokens)
- [Creating a workspace](#creating-a-workspace)
- [Creating a new proposal](#creating-a-new-proposal)
- [Voting for a proposal](#voting-for-a-proposal) 
- [Binance Smart Chain Info](#binance-smart-chain-info) -->

## Introduction

Automata Witness is an anonymous voting service for decentralized applications powered by Automata Geode. The Automata Witness aims to provide a fully decentralized voting platform where users don't need to worry about their privacy being compromised. In addition, the highly available service aims at a much lower transaction fee to generate new blocks.

This page will walk you through [Witness](https://witness.ata.network/) and the functionalities it currently provides.

## For Users

As a community member, to make an anonymous vote, head over to the proposal of a particular project you're interested in voting for. 

!!! attention

    Before making the vote, please ensure the following:

    - Your MetaMask wallet is connected to the **Ethereum Kovan Test Network** or **Binance Smart Chain Test Network**. You can get necessary info abount Binance Smart Chain [here](#binance-smart-chain-info) and follow [instructions](#adding-automata-network-to-your-networks) similarly to add it to MetaMask wallet
    - Your account has the necessary ERC20/BEP20 token for the particular project

<img src="/assets/voteproposal.png" width="673" height="463" />

You will be able to see your token balance of the current connected account.

<img src="/assets/checkp1.png" width="673" height="463" />

!!! warning

    **If you do not have the necessary tokens, you can refer to the [Getting tokens](#getting-tokens) section for more information**

Once ready, you can perform the vote by clicking on the appropriate option. Note that the current strategy employed is to calculate the token balance for each voter.

<img src="/assets/voteproposal.gif" width="673" height="463" />

The results of the proposal can be seen after it has been concluded and finalized.

<img src="/assets/results.png" width="673" height="463" />

## For Project Builders

Project builders can create a workspace for hosting proposals created by them or other community members. Currently the metadata is stored on the [testnet](https://d.ata.network) of Automata Network, so to create workspaces or propsals, you will have to connect to the testnet.

### Adding Automata Network testnet to your networks  

You can then add the Automata Network to your existing networks with the following details:  

|        Field        |          Value           |
|:-------------------:|:------------------------:|
|  **Network Name**   |     Automata Network     |
|   **New RPC URL**   | https://rpc.ata.network/ |
|    **Chain ID**     |            86            |
| **Currency Symbol** |           ATA            |

The option to add networks can be found by clicking on:  

* **Profile Picture >> Settings >> Networks >> Add Network**  

or simply:

* **Network name >> Custom PRC**  

<img src="/assets/addingautomata_m.gif" width="673" height="463"/>

### Connecting Your Metamask Wallet

If you see a **Connect wallet** or the **Not connected** text in your MetaMask, this means you are **not connected**!

<img src="/assets/check1.png" width="673" height="463"/>
<img src="/assets/check2.png" width="673" height="463"/>

You can follow the following steps to connect your wallet:  

- Click on the **Connect wallet** located at the top right corner
- Click on **MetaMask**
- Select the account you wish to connect with MetaMask
- Connect your account

<img src="/assets/connecting_m.gif" width="673" height="463" />

### Creating a workspace

You can create a workspace from the landing page of [Witness](https://witness.ata.network/).  

!!! tips
    Before creating a workspace for your token, please ensure the following:

    - **Your MetaMask wallet is connected to the Automata Network**
    - **Your account has the necessary ATA tokens**

    If you do not have the necessary tokens, you can refer to the [Getting tokens](#getting-tokens) section for more information.

Once ready, you can create a workspace by:

- Clicking on **Create** at the top right corner
- Fill in your workspace name
- Fill in your workspace spec
- Enter your token contract hash
- Click on **Create**

<img src="/assets/creatingworkspace_m.gif" width="673" height="463" />

### Creating a new proposal

Before any voting can begin, a proposal has to be made first. To do so, head over to the workspace of a particular project you're interested in creating a proposal for.  If the workspace has not been created yet, refer to [Creating a Workspace](#creating-a-workspace) to see how you can create one.

<img src="/assets/creatingproposal.png" width="673" height="463" />

!!! tips
    Before creating the proposal for your token, please ensure the following:

    - **Your MetaMask wallet is connected to the Automata Network**
    - **Your account has the necessary ATA tokens**

    If you do not have the necessary tokens, you can refer to the [Getting tokens](#getting-tokens) section for more information.

Once ready, you can create a proposal by:

- Clicking on **New Proposal** at the top right corner
- Fill in your proposal title
- Fill in your proposal's content
- Edit / Remove / Add your voting options
- Select the start and end date
- Click on **Publish**

<img src="/assets/creatingproposal_m.gif" width="673" height="463" />

## Appendix

### Setting up MetaMask

[MetaMask](https://metamask.io/) is a cryptocurrency wallet used to interact with the Ethereum blockchain. As it is required when using Automata Network, you can install the extension via the official download page [here](https://metamask.io/download.html), or simply add the extension for your browser via the following links below:

- [Chrome](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en)
- [Firefox](https://addons.mozilla.org/en-US/firefox/addon/ether-metamask/)
- [Brave](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en)
- [Edge](https://microsoftedge.microsoft.com/addons/detail/metamask/ejbalbakoplchlghecdalmeeeajnimhm?hl=en-US)

### Getting tokens
#### Getting ERC20 tokens in Ethereum kovan network 
To get your tokens, you can now head over to our faucet at <https://faucet.ata.network/>.

Simply copy the address of your account in MetaMask by clicking on **'Copy to Clipboard'** and paste the address into the input field for your desired token before clicking on the **Submit** button.  

<img src="/assets/gettingtoken1_m.gif" width="673" height="463"/>

When receiving ERC-20 tokens, the relevant contract hash can be found in the adjacent blue badge, which you can copy by clicking on the **Copy** badge.  

<img src="/assets/gettingtoken2_m.gif" width="673" height="463"/>

#### Getting BEP20 tokens in Binance Smart Chain test network
To get tokens in BSC test network, you can found the contract address using <https://testnet.bscscan.com/>, and use the faucet <https://testnet.venus.io/faucet> or <https://testnet.binance.org/faucet-smart> to get tokens.

### Binance Smart Chain Info
|        Field        |          Value           |
|:-------------------:|:------------------------:|
|  **Network Name**   |        BSC testnet       |
|   **New RPC URL**   | https://data-seed-prebsc-1-s1.binance.org:8545/ |
|    **Chain ID**     |            97            |