# Smart_Contract - Joint_Savings
Created a joint savings smart contract for 2 addresses

### Functionality of the smart contract

Use the `setAccounts` function to define the authorized Ethereum address that will be able to withdraw funds from your contract

Setting Account addresses:
![setting accounts](..\Execution_Results\setAccounts.jpg)


Test the deposit functionality of your smart contract by sending the following amounts of ether. After each transaction, use the `contractBalance` function to verify that the funds were added to your contract:

Transaction 1: Send 1 ether as wei
![First transaction](Execution_Results\transaction1.jpg)

Transaction 2: Send 10 ether as wei
![Second transaction](Execution_Results\transaction2.jpg)

Transaction 3: Send 5 ether as wei
![Third transaction](Execution_Results\transaction3.jpg)

contractBalance shows total of 16 ether after all three deposits.

Once you’ve successfully deposited funds into your contract, test the contract’s withdrawal functionality by withdrawing 5 ether into `accountOne` and 10 ether into `accountTwo`. After each transaction, use the `contractBalance` function to verify that the funds were withdrawn from your contract. Also, use the `lastToWithdraw` and `lastWithdrawAmount` functions to verify that the address and amount were correct.

Withdraw 5 ether into 'accountOne'
![First withdraw](Execution_Results\withdraw1.jpg)

Withdraw 10 ether into 'accountTwo'
![Second withdraw](Execution_Results\withdraw2.jpg)

Require functionality blocked non approved withdraw
![Rejected](Execution_Results\rejected.jpg)
