# Build a scene

### Basic 

### Technology

### Create & Deploy

1. Install Andverse Cli
    ```
    npm install andverse -g
    ```

2. Init a scene
    ```
    acl init
    ```

3. Edit your scene content
    ```
    # Free play
    ```

4. Setting .env , put your Wallet Private key to `ACL_PRIVATE_KEY`

    ```
    ACL_PRIVATE_KEY=""
    ```

5. Deploy 
    ```
    acl deploy --target-content https://peer.testnet.andverse.org/content
    ```