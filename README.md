# Solana_AgriChat_FrontEnd
Uses Solana Smart Contract to run AgriChat and message can be passed with each other

- [See contract] https://github.com/Tejesh1606/Solana_AgriChat_SmartContract.git

## Config environment
Check this repo for pre dependencies : https://github.com/Tejesh1606/Solana_AgriChat_SmartContract.git
### Install project

- `npm install`
- `ng serve`

### Run
- Step 1: Install Phantom wallet from https://phantom.app/download 
- Step 2: Copy the secret recovery phrase and save it
- Step 3: Goto Menu on the top left corner and click Settings
- Step 4: Select Developer Settings and switch on testnet and select any option from the available 3(devnet or testnet or local) for solana chain
- Step 5: Copy public available on the top of the wallet and goto https://faucet.solana.com/ and get some SOL for transaction
- Step 6: Run and get program id from the link https://github.com/Tejesh1606/Solana_AgriChat_SmartContract.git
- Step 7: Edit: src -> app -> shared -> idls -> solana-chat.idl.ts -> Change the program id in both places 
- Step 8: `npm start`
  ![npm start terminal](https://github.com/Tejesh1606/Solana_AgriChat_FrontEnd/assets/96534599/eabfca38-0978-489b-a57e-679d1d8c34ab)
- Step 9: Use this code for creating file to nft and post it in the app.

#### Required dependencies

- `npm i @solana/web3.js`
- `npm i @coral-xyz/anchor`


#### Dependencies to avoid possible errors

- `npm i --save-dev @types/bn.js`
- `npm i --save-dev assert`

#### Possible mistakes

- [process is not defined...](https://github.com/twilio/twilio-client.js/issues/284)
- [Buffer is not defined](https://stackoverflow.com/questions/50371593/angular-6-uncaught-referenceerror-buffer-is-not-defined)
- [Error window.solana](https://stackoverflow.com/questions/66120513/property-does-not-exist-on-type-window-typeof-globalthis)

### Output

