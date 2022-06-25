1. What is a hash? Why do people use hashing to hide information?


   Hash is a series of representative integer value to represent data, which is mapped by using some function or algorithm, the hashing in blockchain is SHA-256. The reason for using the hashing is to prevent the exploit of plaintext, an example would be password. We don't want to store plaintext password in database, therefore we need to hash it before.


2. What is a smart contract?


   The smart contract is one of the core concepts that Ethereum has to support blockchain development. The smart contracts are batch of script programs stored on-chain with pre-set conditions. Once conditions are met, the blockchain will automatically execute the agreement. The participants will not need to wait for the execution through third party authentication or verification.


3. What are gas fees? Why is gas optimization a big focus when building smart contracts?


   On Ethereum, the computational effort needed to complete a transaction is expressed in terms of "gas." Each transaction has a cost because it needs certain computational resources to complete; these costs are known as gas fees or transaction fees.


   The gas optimization helps to reduce the cost of transaction, as every interaction on-chain requires the fee. The gas optimization is critical to lower this cost to allow people use the service. If the gas fee is high, it means user needs to pay more to do the interaction. Therefore the better the optimization the lower the cost, the better the user experience


4. You have the ability to quickly count the number of leaves in a tree. How can you prove this to a friend, without revealing the exact number of leaves?

   - Ask the friend to pluck the leaves from the tree.
   - I will count the leaves.
   - Ask the friend to pluck a number of leaves from the tree.
   - I will again count the leaves and subtract the number of leaves from initial value.
   - Now I will have the remaining leaves number to proof that I know the number of leaves.

5. How are smart contracts deployed? List the necessary steps.


   In order to deploy a smart contract several things are needed. The bytecode of the contract, some Eth, access to a Ethereum node, and a deployment script.
   
   The contract first need to be compiled from human-readable code to bytecode, then it can be deployed to the blockchain. It is done with the deploy address and number of transactions (the nonce).
   both the deploy address and the nonce are then hashed with the keccak-256 algorithm.

   When deploying the contract user will need to pay the gas fee. The gas fee is the cost of the transaction. As deployment count as an interaction on-chain.


7. Is the new design better than having separate confirmReceived and refundSeller? Why or why not?

 The new design is better than having separate confirmReceived and refundSeller. As the new design only require one transaction this will help to save the gas.

9. Does the circuit behave as you expected it to?


   Yes it did return the correct multiple of the value!
