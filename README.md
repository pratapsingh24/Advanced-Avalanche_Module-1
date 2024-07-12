# Advanced-Avalanche_Module-1

## Steps to deploy the project:

1. Set up your EVM subnet: You can use our guide and the Avalanche documentation to create a custom EVM subnet on the Avalanche network.

2. Define your native currency: You can set up your own native currency, which can be used as the in-game currency for your DeFi Kingdom clone.

3. Connect to Metamask: Connect you EVM Subnet to metamask, this can be done by following the steps laid out in our guide.

4. Deploy basic building blocks: You can use Solidity and Remix to deploy the basic building blocks of your game, such as smart contracts for battling, exploring, and trading. These contracts will define the game rules, such as liquidity pools, tokens, and more.



### Deploy your EVM subnet using the Avalanche CLI:
- Follow the instructions in the documentation provided in the module to install the Avalanche CLI in Linux.
- Deploy the avalanche subnet named 'mySubnet'.

### Add your Subnet to Metamask
- Make sure it is your selected local network in Metamask.
- use the information generated in the terminal to add the new network in the Metamask.

```
  
Browser Extension connection details (any node URL from above works):
RPC URL:           http://127.0.0.1:9650/ext/bc/EVjDqtHzLcPXLsf8BdMdX37AKDpwMvKwkDSDLGuzDHAtKzNmG/rpc
Funded address:    0x8db97C7cEcE249c2b98bDC0226Cc4C2A57BF52FC with 1000000 (10^18) - private key: 56289e99c94b6912bfc12adc093c9b51124f0dc54ac7a766b2bc5ccf558d8027
Funded address:    0xAA86F106389545f950b6d49C34255337CA74d724 with 600 (10^18)
Network name:      mySubnet
Chain ID:          120224
Currency Symbol:   PRO

```

### Connect Remix to your Metamask
- Use the Injected Provider.

### Deploy the smart-contracts

### Test your application!
- Using remix to interact with your deployed smart-contracts, deploy tokens, pools, and more.



## Author
Pratap Singh
[@pratapsingh24](https://github.com/pratapsingh24/)

## License
This project is licensed under the MIT License - see the LICENSE.md file for details
