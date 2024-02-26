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
* Go to the "Deploy & run transactions"  section and select the "Remiux VM (Berlin)" Environment, then press the orange "Deploy" button

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
![1_deployed_contract](https://github.com/Chrisdeleon91/Module-20-Solidity-Challenge/assets/22796940/75a46261-431e-4da1-b0b8-b650d5193651)
# Set Accounts Function
![2_set_accounts_function](https://github.com/Chrisdeleon91/Module-20-Solidity-Challenge/assets/22796940/36d53179-020c-4fb2-8342-7ca947fe0b12)
# Deposit Function - Transaction 1: 1 ETH
![3_deposit_function_transaction_1_1_eth](https://github.com/Chrisdeleon91/Module-20-Solidity-Challenge/assets/22796940/444e35d8-e128-4316-b7a0-d48390067d07)
# Contract Balance - Transaction 1: 1 ETH
![4_contract_balance_transaction_1](https://github.com/Chrisdeleon91/Module-20-Solidity-Challenge/assets/22796940/7b63caac-eee2-450a-a0ed-268cf5529e92)
# Deposit Function - Transaction 2: 10 ETH
![5_deposit_function_transcation_2_10_eth](https://github.com/Chrisdeleon91/Module-20-Solidity-Challenge/assets/22796940/c82dc81b-cf07-41db-874c-03fdf135845d)
# Contract Balance - Transaction 2: 10 ETH
![6_contract_balance_transaction_2](https://github.com/Chrisdeleon91/Module-20-Solidity-Challenge/assets/22796940/b3059003-1acd-43a1-9b15-c9eae1be887c)
# Deposit Function - Transaction 3: 5 ETH
![7_deposit_function_transcation_3_5_eth](https://github.com/Chrisdeleon91/Module-20-Solidity-Challenge/assets/22796940/4d4a435c-3bd6-44c4-825b-773d3e2b234b)
# Contract Balance - Transaction 3: 5 ETH
![8_contract_balance_transaction_3](https://github.com/Chrisdeleon91/Module-20-Solidity-Challenge/assets/22796940/d94c8cb3-0483-4f31-b580-39748ae9842b)
# Account 1: 5 ETH Withdrawal
![9_account_1_5_eth_withdrawal](https://github.com/Chrisdeleon91/Module-20-Solidity-Challenge/assets/22796940/b3320c6c-808c-4435-97e5-e10f9739f3ed)
# Account 1: Contract Balance
![10_account_1_withdrawal_contract_balance](https://github.com/Chrisdeleon91/Module-20-Solidity-Challenge/assets/22796940/cf362466-1821-4ab2-926e-640d7e41bef5)
# Account 2: 10 ETH Withdrawal
![11_account_2_10_eth_withdrawl](https://github.com/Chrisdeleon91/Module-20-Solidity-Challenge/assets/22796940/2aa9cefd-2f09-45a8-a90d-8b17900b6d99)
# Account 2: Contract Balance
![12_account_2_withdrawal_contract_balance](https://github.com/Chrisdeleon91/Module-20-Solidity-Challenge/assets/22796940/a3237dc7-7c73-42f7-98f5-9c767483abd2)
# Last to Withdraw Function
![13_last_to_withdraw](https://github.com/Chrisdeleon91/Module-20-Solidity-Challenge/assets/22796940/a2799d33-b8ff-4975-9db6-07d2c5471f25)
# Last Withdraw Amount Function
![14_last_withdraw_amount](https://github.com/Chrisdeleon91/Module-20-Solidity-Challenge/assets/22796940/eefc81f0-554c-4274-b7ae-aff3e8c8da94)

![Picture](https://www.columbia.edu/content/themes/custom/columbia/assets/img/cu-header.svg)


