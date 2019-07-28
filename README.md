# Codefundo - Voting using AzureBlockchain
codefundo.io 2019 azure blockchains project

## Motivation

As the Voting system in our country has issues with its security and efficiency, We propose to present a voting system which is faster and reasonably more secure.

## System Model

Every voter is treated as a node and has a unique Voter and Biometric Id.
We would have a set of Servers running around the country. All these servers will have a unique private key and public keys.
We have small Verification centers set up all around with a small Biometric device with a system for casting votes. ( Are really small and can be large in number ie 1 for every 100 people or so and are very fast)

## Proposed Idea

My idea is to create a secure voting system using azure. Here every node (voter) will have an Voter ID number linked to their Aadhar card, which henceforth will be used to access the ledger ( file taking track of the votes ). 
The Servers set would be acting as Miners who make Hash of every unique ID.
Here 1 block will contain 1 vote.
Hence once a block is created, a unique encryption is done by the servers.
As a user comes to a Verification Center, He'll enter his City or District and put his fingers for identification. After identification his Unique ID will be created by the Servers and using the ID of the person, the Verification Center and the public keys of the servers, a new hash would be created leading to the formation of a new block.
The vote has to be put within 5 mins of generation of the unique Id after which it will collapse. After the casting of vote, a block would be created and by the servers added to the block chain. As unique ID collapses every 5 mins, only active IDs data block could be added to the chain and would be impossible to tamper with.
To confirm if the data set of voters is not tampered with, we send an OTP to every voter after the generation of his unique ID and this would be entered by the voter to confirm his vote to a party.
Now this new chain would be broadcasted to the server containing encypted blocks and could be checked by anyone who wants to find if every block has a unique characterstic as in all block chains (Bitcoins etc).
Hence this process can be easily verified by any person having the ledger.
