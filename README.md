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

**11/5/2021 - 2:00 PM PST** - Updated repository with snapshot for 1st Seerlight raffle. All Capsules held since 10/6/21, 12:00 AM PST are valid.

**11/7/2021 - 12:08 AM PST** - 

Seed for Raffle 1 drawn. https://etherscan.io/tx/0x1b4fe351a3b84211e732e72762c1f8032a3eac2f08302c93f094ee74c68da74a#eventlog

Seed value: 57636575605253221819287095294545447585433931493853993490071723742157202222281

Total number of qualified Capsules: 7863

Index of winning Capsule: 57636575605253221819287095294545447585433931493853993490071723742157202222281 % 7863 = 4420

Capsule ID at index 4420: 5497

Owner of Capsule 5497 at the time of the snapshot: 0x5338035c008ea8c4b850052bc8dad6a33dc2206c

**11/12/2021 - 12:13 PM PST** - Updated repository with snapshot for 2nd Seerlight raffle. All Capsules held since 10/13/21, 12:00 AM PST are valid.

**11/13/2021 - 12:37 AM PST** - Detected an error in the snapshot - we ran the 30 day filter on the 11/5 snapshot instead of the 11/12 snapshot. Updated accordingly.

**11/14/2021 - 10:22 PM PST** - 

Seed for Raffle 2 drawn. https://etherscan.io/tx/0xe966f177f109665caa1ce8cfe908f52acda099f961128e9d7fd75a59cf8d18a7#eventlog

Seed value: 37855899507775122208549778097242246594503825740719356452670356420104640869944

Total number of qualified Capsules: 8551

Index of winning Capsule: 37855899507775122208549778097242246594503825740719356452670356420104640869944 % 8551 = 2618

Capsule ID at index 2618: 3005

Owner of Capsule 5497 at the time of the snapshot: 0xdc0040f4b2445269681dbe0195309225b061f05f

**11/20/2021 - 12:13 PM PST** - Updated repository with snapshot for 3rd Seerlight raffle. All Capsules held since 10/20/21, 12:00 AM PST are valid.
