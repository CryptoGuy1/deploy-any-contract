# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
GAS_REPORT=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```


Deploy any contract by calling Proxy.deploy(bytes memory _code)

For this example, you can get the contract bytecodes by calling Helper.getBytecode1 and Helper.getBytecode2