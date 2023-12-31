# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```

It's possible to write an ERC20 contract that allows the owner to pause token transfers.
This can be useful in a disaster situation, or when a security bug is discovered.
Pausing transfers can give you time to upgrade the contract, or distribute a replacement token to existing users.
