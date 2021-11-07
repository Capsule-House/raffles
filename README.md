# Capsule House Raffle

This repository provides a history of the Capsule House 1/1 Seerlight Raffle system.

Raffles are held every other month, starting 11/2021. 
To qualify, you must have held a Capsule for at least 30 days. 
Each Capsule is equivalent to one entry.

# Implementation Details

Prior to the drawing, a list of all qualified addresses with their corresponding Capsule IDs will be posted here, as well as the list of capsule IDs.

On the day of the drawing, we will use `getRandomNumber` on https://etherscan.io/address/0x85f16125fadef90aa0b5373fb5b8b870883c60c0 to generate a Chainlink VRF random seed. For example, let's say there are five Capsules eligible for the raffle, with the ids:

```
17
52
283
591
5183
```

Let's say Chainlink returns `87314876641541055251095431619250856243264627284949971051498783260561907368646` as our random seed.

To get the index of the winner, we do `87314876641541055251095431619250856243264627284949971051498783260561907368646 % 5 = 1`

The capsule at index 1 is 52, so the owner of Capsule 52 wins at the time of the snapshot.

# Drawing History

**11/5/2021 - 2:00 PM PST** - Updated repository with snapshot for 1st Seerlight raffle. 

**11/7/2021 - 12:08 AM PST** - 

Seed for Raffle 1 drawn. https://etherscan.io/tx/0x1b4fe351a3b84211e732e72762c1f8032a3eac2f08302c93f094ee74c68da74a#eventlog

Seed value: 57636575605253221819287095294545447585433931493853993490071723742157202222281
Qualified capsule length: 7863
Index of winning capsule: 57636575605253221819287095294545447585433931493853993490071723742157202222281 % 7863 = 4420
Capsule ID at index 4420: 5497
Owner of Capsule 5497 at the time of the snapshot: 0x5338035c008ea8c4b850052bc8dad6a33dc2206c
