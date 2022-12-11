# Assignment 2: Oracles

## Instructions 

The repository for assignment #2 will be released on Saturday morning (November 26), so you can get started on in over the weekend. The assignment is due on December 2 (Friday) at midnight. That gives you 1 week. 

Assignment #2 repo will have a PiggyBank contract for you to update. It will be a functioning contract that meets the requirements of assignment #1.

Please note: changes or new commits made to your assignment #1 repo after midnight on Friday November 25 will not be accepted.

Also note: your contract for assignment #1 may look different and that’s ok. Marks will be awarded for functional code and it is expected that implementation may vary.

The steps for assignment #2 are:

1.	Add a function to the PiggyBank contract (will be provided to you in assignment 2 repo) to get the value of the piggybank balance in USD (cents). So 100 = $1USD. Note you will have to use an oracle to complete this assignment. Chainlink has an oracle setup on Goerli that you can use. Assume 1GoerliETH = 1ETH (mainnet). Check out the chainlink tutorial from class on November 24 to find the contract information and the chainlink module to import if you need help with where to start. 
2.	Test your code, deploy your contract on Goerli, and again update your code with a comment near the top indicating your new and improved PiggyBank contract address. If you like, you can put any amount of Goerli in your deployed contract.
3.	Edit this file (README.md) to answer the questions below in your own words. 
4.	Make sure your updated code and README file are located on your main branch so I can mark. 

## Questions

Answer the following questions in 1-2 paragraphs in order to complete the assignment. 

### 1. Why are oracles necessary on the blockchain?

Oracles serves as a bridege for connecting smart contracts on blockchain to off chain data providers. Oracles works as lines of code that connect information in real world for contract. Basically, Oracles are a form of communication between the outside world and the blockchain world. As blockchains and smart contracts are closed systems where they act as rigid processes for connecting to external data sources. Oracles presents a way of securely providing off-chain data to blockchain network's on-chain environment.


### 2. How does Chainlink ensure oracle data is trustworthy? 

Chainlink is a secure and reliable standard of oracle network. It is an oracle network that feeds real-world data to blockchain-based smart contracts. On the blockchain, smart contracts are pre-specified agreements that evaluate data and execute automatically when certain conditions are met. LINK tokens are digital asset tokens that are used to pay for network services. Chainlink helps by providing an intriguing decentralized way to authenticate the data from oracles and the relevant output data of smart contracts. ChainLink analyzes the issues with centralized oracle feeds as a single point of failure and gives a solution through a “middleware” jeopardized of a decentralized oracle platform. Crucially, ChainLink identifies and authenticates data before it becomes a trigger for a smart contract. Chainlink provides various useful features:
1. secure connectivity 2. instant payments 3.High Interoperability 


### 3. Why might pseudorandom number generation using keccak256 create a vulnerability for a smart contract? 
A pseudorandom number generator (PRNG), also known as a deterministic random bit generator (DRBG), It is an algorithm for generating a sequence of numbers whose properties approximate the properties of sequences of random numbers. 
Vulnerability attack can occur when a contract sends ether to an unknown address. An attacker can carefully construct a contract at an external address which contains malicious code in the fallback function. When a contract sends ether to this address, it will invoke the malicious code. Typically the malicious code executes a function on the vulnerable contract, performing operations not expected by the developer. The name “re-entrancy” comes from the fact that the external malicious contract calls back a function on the vulnerable contract and “re-enters” code execution at an arbitrary location on the vulnerable contract. 


### 4. List four cases that would require the use of an oracle. 
Oracle database supports data types- 
1. XML- It is a standard way of identifying and describing data on the web. 
2. LOB- It is a type of data that allows you to store and manipulate large volumes of data. 
3. Oracle Text- It allows to do text search. 
4. Oracle InterMedia- to develop and implement traditional applications.
5. Spatial oracle- To store and manage location content. 


