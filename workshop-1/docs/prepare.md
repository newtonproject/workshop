## Prepare
   1. Develop tool
      - [Online Solidity Editor](https://remix.ethereum.org/) and [Remix Documentation](https://remix-ide.readthedocs.io/en/latest/#)
      - [Solidity Documentation](https://docs.soliditylang.org/en/latest/)

   2. Blockchain

      - [Newton testnet Explorer](http://e.testnet.diynova.com/)

      - NewMask

        ```bash
        # For Chrome
        git clone https://github.com/newswap/newmask-extension && cd newmask-extension
        # If no Node installed, Install nodejs v10.16.0, See https://nodejs.org/download/release/v10.16.0/
        # Than install yarn
        npm install -g yarn
        
        # install packages and build
        yarn
        yarn dist
        
        # Add dist/chrome to Chrome plugin
        
        ```

        - Setting NewMask (If you already have an account , Ignore this)
          - Then you can get NewMask in your [explorer extensions](chrome://extensions/), Run NewMask and Create new account
          - Select Network - NewChainTestNet
          - [Get Test Coin](https://www.newtonproject.org/en/faucet/)
          - Check your balance