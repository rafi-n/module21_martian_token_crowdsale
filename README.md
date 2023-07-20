# Module21: Kasei Coin - Martian Token Crowdsale

## Buying tokens

1. Once all contracts are deployed, select an address from the dropdown other than the original Wallet address. Copy this address.
2. Enter a number of wei to purchase tokens with.
3. Click the `BuyTokens` button in the Crowdsale contract, after pasting in the copied address.
4. Make sure you have met the goal of the contract by clicking the `goalReached` button.
5. Make sure the contract is closed based on the time allotted by clicking `isOpen`.
6. Click `Finalize`.

## Evaluation Evidence
KaseiCoin contract compile:    
![token_contract](Images/KaseiCoin_compile.png)

KaseiCoinCrowdsale contract compile:    
![crowdsale_contract](Images/KaseiCoinCrowdsale_compile.png)

KaseiCoinCrowdsaleDeployer contract compile:    
![deployer_contract](Images/KaseiCoinCrowdsaleDeployer_compile.png)

### All contracts deployed and working:    
VIDEO: Deploy the KaseiCoinCrowdsaleDeployer contract:    
![deploy_deployer](Images/deploy_deployer.mov)

#### The deployer creates contracts for the crowdsale and token, so they only need to be loaded from their addresses:    
VIDEO: Crowdsale:    
![load_crowdsale_token](Images/load_crowdsale_token.mov)

VIDEO: Buy Tokens:    
![buy_token](Images/buyTokens.mov)

VIDEO: Check Balances:    
![check_balance](Images/check_balances.mov)

## Optional
Contract Creation:
![](Images/opt_contract_creation.png)

Contract Creation Review in Ganache:
![](Images/opt_contract_creation_ganache.png)