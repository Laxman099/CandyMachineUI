# CandyMachineUI

- A simple UI for mint the NFTS using the spltoken.
- https://www.solaneyes.com/address/6UKXw4GAMcezGqRZEkXkbB3ou3uRr9Ph6Wz1UoUNrjmQ?cluster=devnet
- ![image](https://github.com/user-attachments/assets/d8eb0647-4f24-4d23-9846-acfb49593346)

  
## Prerequisites
- Solana CLI.
- Basic Frontend Knowledge.
- spl-token library.

## Steps  to Follow for Creating SPL Token
```
1.solana-keygen new --outfile ~/my-solana-wallet.json
2.solana config set --keypair ~/my-solana-wallet.json
3.solana airdrop 2 --url https://api.devnet.solana.com
4.spl-token create-token
5.spl-token create-account 
6.spl-token mint 

```

## Steps to Follow to Create,deploy,mint CandyMachine
```
 1.sugar upload : to upload assets.
 2. sugar verify : to verify the config.
 3. sugar deploy :to deploy the assests to the candymachine.
 4.sugar validate :to validate candymachine.
 5.sugar mint : to mint the assets to solana account based on the config file.

```
## Getting Started 
-- Git clone : clone the repo using the repo link to local machine .
-- navigate to root directory.
-- run npm install.
-- modify the environmnet variables.
-- npm run dev : to start the application on the localhost at some port .

# Author
- Laxman .
  

