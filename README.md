Tutorial: Deploy a Smart Contract

1. Set Up Remix IDE
Access Remix IDE in your web browser: https://remix.ethereum.org/
2. Create the Smart Contract
In the left-hand file explorer pane, create a new file named HelloWorld.sol.
Paste the following Solidity code into the file.

pragma solidity ^0.8.0;

contract HelloWorld {
    string public message;

    constructor() {
        message = "Hello, World!";
    }
}



<img width="720" height="414" alt="add-contract 0e2bb80 1440" src="https://github.com/user-attachments/assets/66283c99-b282-46cb-9bc3-ec0796c89c3d" />


3. Compile the Smart Contract
Select the HelloWorld.sol file in the Remix file explorer next to the sidebar on the left side of the screen.
In the left-hand sidebar, click the "Solidity Compiler" icon.
Open the "Advanced Configuration" sub-section and sure you are using the "Shanghai" EVM version.
Click "Compile HelloWorld.sol."


<img width="1440" height="1087" alt="solidity-compile ad5f6e7 1440" src="https://github.com/user-attachments/assets/a444772a-5403-4422-b8a1-65084aa37543" />

4. Deploy the Smart Contract
Make sure your Ethereum wallet is connected to the ZenChain network.
In the left-hand sidebar, click the "Deploy & Run Transactions" plugin icon (it looks like an Ethereum diamond).
Under "Environment," select "Injected Provider".
Select your compiled contract HelloWorld under "Contract."
Click "Deploy." Confirm the transaction in your wallet if prompted.

<img width="1440" height="889" alt="deploy-contract 4b3544d 1440" src="https://github.com/user-attachments/assets/1990f961-26d0-4e24-9db6-74b60a959c96" />

5. Interact with the Smart Contract
Once deployed, your contract will appear under "Deployed/Unpinned Contracts" section of the "Deploy & Run Transactions" pane.
Expand it to see the message variable.
Click the blue "message" button to read the stored message. It should display "Hello, World!" in the Remix console.

<img width="1440" height="482" alt="interact-with-contract aa17549 1440" src="https://github.com/user-attachments/assets/36b0a80a-2509-418a-a2fc-58132ca9835c" />

Fauchet https://faucet.zenchain.io/
