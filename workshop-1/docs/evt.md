## Create first EVT

- Write Contract (Solidity)

   1. [Get source code](https://github.com/newtonproject/evt-lib/blob/master/contracts/evt-examples/HelloEVT.sol)

   2. Add a solidity file on your remix, and paste code in the solidity file. then you should change some imports by: 

      ```solidity
      // change packages
      import "../evt-base/EVT.sol";
      import "../interfaces/IEVTMetadata.sol";
      import "../libraries/HexStrings.sol";
      import "../libraries/NewtonAddress.sol";
      import "../libraries/base64.sol";
      // to
      import "@newton-protocol/evt-lib/contracts/evt-base/EVT.sol";
      import "@newton-protocol/evt-lib/contracts/interfaces/IEVTMetadata.sol";
      import "@newton-protocol/evt-lib/contracts/libraries/HexStrings.sol";
      import "@newton-protocol/evt-lib/contracts/libraries/NewtonAddress.sol";
      import "@newton-protocol/evt-lib/contracts/libraries/base64.sol";
      ```
- Compiler (Remix)
   1. Select compiler version to 0.8.3
   
   2. Compiler

- Deploy to testnet
   1. Select Environment - Injected Provider - Metamask

   2. Check you account address and balance

   3. Select Contract to HelloEVT

   4. Input the deploy params (NAME, SYMBOL, BASEURI, LOGO, FROM, EXTERNAL_URI) and Transact

   5. Confirm on NewMask

   6. The Contract deployed on Testnet, you can See it on Newton testnet Explorer, and Test functions on Remix