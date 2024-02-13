# Module-20-Solidity-Challenge

In this module, I'll learn about smart contracts and how I can build them by using Solidity. Solidity is a programming language for implementing smart contracts on the Ethereum blockchain. Smart contracts are agreements that special computer programs, which can run on a blockchain, create.

A fintech startup company has recently hired you. This company is disrupting the finance industry with its own cross-border, Ethereum-compatibleblockchain that connects financial institutions. Currently, the team is building smart contracts to automate many of the institutions’ financialp rocesses and features, such as hosting joint savings accounts.
To automate the creation of joint savings accounts, I’ll create a Solidity smart contract that accepts two user addresses. These addresses will be able to control a joint savings account. My smart contract will use ether management functions to implement a financial institution’s requirementsfor providing the features of the joint savings account. These features will consist of the ability to deposit and withdraw funds from the account.

* Create a Joint Savings Account Contract in Solidity
* Compile and Deploy Your Contract in the JavaScript VM
* Interact with Your Deployed Smart Contract

## Instructions on how to use 

### Copy the contents of joint_savings.sol and upload to a Remix Online IDE workspace (https://remix.ethereum.org/)
* Upload joint_savings.sol to a workspace 
* Run the "Solidity compiler" (version 0.5.0+commit.1d4f565a) on the left-hand side window pane and select "Compile joint_savings.sol"
* Go to the "Deploy & run transactions"  section and select the "Remiux VM (Berlin) Environment, then press the orange "Deploy" button

## Interact with Your Deployed Smart Contract

Now that your contract is deployed, it’s time to test its functionality. 

To interact with your deployed smart contract, complete the following steps:
1. Use the setAccounts function to define the authorized Ethereum address that will be able to withdraw funds from your contract.

2. Test the deposit functionality of your smart contract by sending the following amounts of ether. After each transaction, use the contractBalance
function to verify that the funds were added to your contract:
Transaction 1: Send 1 ether as wei.
Transaction 2: Send 10 ether as wei.
Transaction 3: Send 5 ether.

Once you’ve successfully deposited funds into your contract, test the contract’s withdrawal functionality by withdrawing 5 ether into
accountOne and 10 ether into accountTwo
. After each transaction, use the contractBalance function to verify that the funds were withdrawn from yourcontract. Also, use the lastToWithdraw and lastWithdrawAmount functions to verify that the address and amount were correct.

# Deployed Contract
![1_deployed_contract](https://github.com/Chrisdeleon91/Module-20-Solidity-Challenge/assets/22796940/8cc49f05-348c-41c9-bf77-2da26c066c25)
# Set Accounts Function
![2_set_accounts_function](https://github.com/Chrisdeleon91/Module-20-Solidity-Challenge/assets/22796940/808c8cd3-62ab-4d6c-98a4-da234a81ff81)
# Deposit Function - Transaction 1: 1 ETH
![3_deposit_function_transaction_1_1_eth](https://github.com/Chrisdeleon91/Module-20-Solidity-Challenge/assets/22796940/d26efa0f-9ed1-4497-9cda-a4dbbcfdaab4)
# Contract Balance - Transaction 1: 1 ETH
![4_contract_balance_transaction_1](https://github.com/Chrisdeleon91/Module-20-Solidity-Challenge/assets/22796940/e4549713-b3c0-4023-9db3-440b673a1096)
# Deposit Function - Transaction 2: 10 ETH
![5_deposit_function_transcation_2_10_eth](https://github.com/Chrisdeleon91/Module-20-Solidity-Challenge/assets/22796940/83f9b25e-f2f4-4f70-a08a-bcd8577165b7)
# Contract Balance - Transaction 2: 10 ETH
![6_contract_balance_transaction_2](https://github.com/Chrisdeleon91/Module-20-Solidity-Challenge/assets/22796940/5dee464d-eb71-42b9-b33a-3db39e9b065d)
# Deposit Function - Transaction 3: 5 ETH
![7_deposit_function_transcation_3_5_eth](https://github.com/Chrisdeleon91/Module-20-Solidity-Challenge/assets/22796940/7e8a164f-b218-4490-9392-4cb59635300d)
# Contract Balance - Transaction 3: 5 ETH
![8_contract_balance_transaction_3](https://github.com/Chrisdeleon91/Module-20-Solidity-Challenge/assets/22796940/b3f437c2-ee89-46b7-a825-2b6697ab981f)
# Account 1: 5 ETH Withdrawal
![9_account_1_5_eth_withdrawal](https://github.com/Chrisdeleon91/Module-20-Solidity-Challenge/assets/22796940/1034e1fc-8018-47a9-a991-f4dba3f31c9c)
# Account 1: Contract Balance
![10_account_1_withdrawal_contract_balance](https://github.com/Chrisdeleon91/Module-20-Solidity-Challenge/assets/22796940/f2101a61-1aea-4c7a-a851-e3c2f51e8cb8)
# Account 2: 10 ETH Withdrawal
![11_account_2_10_eth_withdrawl](https://github.com/Chrisdeleon91/Module-20-Solidity-Challenge/assets/22796940/053742f3-d9ec-4fd9-baec-f52b22ac10d9)
# Account 2: Contract Balance
![12_account_2_withdrawal_contract_balance](https://github.com/Chrisdeleon91/Module-20-Solidity-Challenge/assets/22796940/b8e09a1f-0260-47cd-8acd-5b6cfba89911)
# Last to Withdraw Function
![13_last_to_withdraw](https://github.com/Chrisdeleon91/Module-20-Solidity-Challenge/assets/22796940/c62bae0e-a766-4ceb-a23b-4f3c60c94426)
# Last Withdraw Amount Function
![14_last_withdraw_amount](https://github.com/Chrisdeleon91/Module-20-Solidity-Challenge/assets/22796940/a7a075ef-7817-4d81-9b59-08eb61835df8)


 
![Picture](https://www.columbia.edu/content/themes/custom/columbia/assets/img/cu-header.svg)


