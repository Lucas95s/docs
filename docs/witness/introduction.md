# Introduction

Automata [Witness](https://witness.ata.network) is a customizable voting service for decentralized applications. Witness provides a fully decentralized voting platform (with privacy features) across different blockchains.

## Features

* **Privacy**: You can choose different types of votes with different privacy levels e.g. Public (full disclosure of voter address and number of votes), Medium (only number of votes), and Private (only voting result is published — voter identities and number of votes are not).
* **Low-cost**: Voting is conducted off-chain so there is no gas cost and a wider range of token holders can participate in governance without being deterred by high gas fees.
* **Chainhook**: Trigger on-chain execution based on the voting results. Chainhook enables calling of the on-chain contract which was registered at proposal creation.
* **Modularity**: Each of these functions can be used as standalones, or together. If a project wants to use Witness as a signaling tool without on-chain execution, that is also possible.

## Platforms

Witness currently supports the following with more to be added in future:

* Ethereum (Mainnet, Kovan Testnet)
* Binance Smart Chain (Mainnet, Testnet)
* Plasm Network (Dusty Testnet)
* Clover Finance (Testnet)
* Darwinia (Pangolin Testnet)
* Moonbase (Alpha Testnet)
* Polygon (Matic Mainnet)
* Avalanche (Mainnet)

Next, we will be adding other [EVM-based chains][evm-chains] and [Substrate-based chains][substrate-chains] to the list.

### Feature Support

|          Platform           |   Private Voting   |     Chainhook      |    Public Voting   |
|:---------------------------:|:------------------:|:------------------:|:------------------:|
|      Ethereum Mainnet       | :white_check_mark: |   :construction:   | :white_check_mark: |
|   Ethereum Kovan Testnet    | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| Binance Smart Chain Mainnet | :white_check_mark: |   :construction:   | :white_check_mark: |
| Binance Smart Chain Testnet | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| Plasm Network Dusty Testnet | :white_check_mark: |   :construction:   | :white_check_mark: |
| Clover Finance Testnet      | :white_check_mark: |   :construction:   | :white_check_mark: |
| Darwinia Pangolin Testnet   | :white_check_mark: |   :construction:   | :white_check_mark: |
| Moonbase Alpha Testnet      | :white_check_mark: |   :construction:   | :white_check_mark: |
|          Polygon            | :white_check_mark: |   :construction:   | :white_check_mark: |
|         Avalanche           | :white_check_mark: |   :construction:   | :white_check_mark: |

[evm-chains]: https://chainlist.org/
[substrate-chains]: https://polkaproject.com/#/projects?cateID=1&tagID=0
