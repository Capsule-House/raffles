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

Owner of Capsule 3005 at the time of the snapshot: 0xdc0040f4b2445269681dbe0195309225b061f05f

**11/20/2021 - 12:13 PM PST** - Updated repository with snapshot for 3rd Seerlight raffle. All Capsules held since 10/20/21, 12:00 AM PST are valid.

**11/21/2021 - 8:09 PM PST** -

Seed for Raffle 3 drawn. https://etherscan.io/tx/0x671f0c5bb3c6e2d40864e3ed2a17a2b24428f77e8f00c97a4b898e683f612d55#eventlog

Seed value: 105539164226774516836555908199286429656650560883458093493927699866447208134298

Total number of qualified Capsules: 8916

Index of winning Capsule: 105539164226774516836555908199286429656650560883458093493927699866447208134298 % 8916 = 6707

Capsule ID at index 2618: 7511

Owner of Capsule 7511 at the time of the snapshot: 0x132cf1708ff7fac4cd5c03a0686cdd69106257d3

**11/29/2021 - 8:08 PM PST** -

Seed for Raffle 4 drawn. https://etherscan.io/tx/0xe8c01899988b89a144ee0411c32bbcfa9160942874b9b672f7f4311572b3ed28#eventlog

Seed value: 10301601744972363181272346695944750141938055496935636395433916559665116142956

Total number of qualified Capsules: 8971

Index of winning Capsule: 105539164226774516836555908199286429656650560883458093493927699866447208134298 % 8971 = 143

Capsule ID at index 2618: 189

Owner of Capsule 189 at the time of the snapshot: 0xa309e257db5c325e4b83510fcc950449447e6bda

**1/9/2022 - 8:12 PM PST** -

Seed for Raffle 5 drawn. https://etherscan.io/tx/0xdd5fbb169bacb614688a7877cc27537a81cbda82abe0ca9555466e854d9a1aea#eventlog

Seed value: 79466748032820420964008606343814198804442356197710291454033873502100874547993

Total number of qualified Capsules: 6684

Index of winning Capsule: 105539164226774516836555908199286429656650560883458093493927699866447208134298 % 8971 = 5477

Capsule ID at index 2618: 8216

Owner of Capsule 8216 at the time of the snapshot: 0x81c2eee2902eda6db28a448d8a814f221718ba2d

**1/17/2022 - 7:41 PM PST** -

Seed for Raffle 6 drawn. https://etherscan.io/tx/0xe58635a5530f183707b9acf8164ef743345a1770df64ebecbce1ca86be09137e#eventlog

Seed value: 61138888035696447048744209112226197028512717642936905300599484380908160123800

Total number of qualified Capsules: 6494

Index of winning Capsule: 61138888035696447048744209112226197028512717642936905300599484380908160123800 % 6494 = 2056

Capsule ID at index 2056: 3173

Owner of Capsule 3173 at the time of the snapshot: 0x087aaf213357b1372401de8b95dffb16e7137f29

**1/22/2022 - 6:42 PM PST** -

Seed for Raffle 7 drawn. https://etherscan.io/tx/0xd8fa74a4d5d8046193fab80d78d1789f1395064df24aa00e96adfc70fcb7b984#eventlog

Seed value: 107818196259955420853519022430069158586588194501639998378499359136311517344143

Total number of qualified Capsules: 6531

Index of winning Capsule: 107818196259955420853519022430069158586588194501639998378499359136311517344143 % 6531 = 112

Capsule ID at index 112: 213

Owner of Capsule 213 at the time of the snapshot: 0x7d4c4d5380Ca2F9C7A091bb622B80613da7Eae8C

**2/12/2022 - 7:12 PM PST** -

Raffle was supposed to be held on 1/29/22 but was delayed.

Seed for Raffle 8 drawn. https://etherscan.io/tx/0x4899484b0adfb09b6cb71531a9e531cdfc9a5b4c0f25e23b56379afca27db5db#eventlog

Seed value: 79357979646986496010954690382556190719352767717494598927108635236291756968363

Total number of qualified Capsules: 5912

Index of winning Capsule: 79357979646986496010954690382556190719352767717494598927108635236291756968363 % 5912 = 112

Capsule ID at index 1795: 

Owner of Capsule 3112 at the time of the snapshot: 0x2586181d6544b49060d48f8c1322339ed2876f16

**3/7/2022 - 7:11 PM PST** -

Seed for Raffle 9 drawn. https://etherscan.io/tx/0xb8faf3e4c4415e6aa6cf11384d321989e234ecfe094cf024ff4c5afc750ac0f6#eventlog

Seed value: 32746752177837087543883444700695230452459818956949868806891213089329781971181

Total number of qualified Capsules: 8302

Index of winning Capsule: 79357979646986496010954690382556190719352767717494598927108635236291756968363 % 5912 = 112

Capsule ID at index 4639: 5571

Owner of Capsule 5571 at the time of the snapshot: 0x3ecd8f1e39f6d1656de6f3d73f0c2aa7e2ae324e

**3/14/2022 - 7:18 PM PST** - 

Seed for Raffle 10 drawn. https://etherscan.io/tx/0xf9c0ca5864a7743a78397dd5bd7ff4ae54e342d9d93b015032b99feb731655c3#eventlog

Seed value: 24163365288513526629616846098977329481228841571168700439269660799759546074826

Total number of qualified Capsules: 8560

Index of winning Capsule: 79357979646986496010954690382556190719352767717494598927108635236291756968363 % 5912 = 4106

Capsule ID at index 4106: 4742

Owner of Capsule 4742 at the time of the snapshot: 0x960b1a74abe556689d1f1e793124f4f8ef27303b

**3/26/2022 - 3:10 PM PST** - 

Seed for Raffle 11 drawn. https://etherscan.io/tx/0xc0c990afb054b7ad2a40ffaad6691b64eb58091c485ea0fbb6ad05e3d06e0a4f#eventlog

Seed value: 252568798447180578805614314918111329216375590692886068807544307927966448269

Total number of qualified Capsules: 8742

Index of winning Capsule: 252568798447180578805614314918111329216375590692886068807544307927966448269 % 8742 = 433

Capsule ID at index 433: 503

Owner of Capsule 503 at the time of the snapshot: 0x24519bB072e7303fE40793a7627cD1DD08EAEECc

**3/26/2022 - 3:10 PM PST** - 

Seed for Raffle 12 drawn. https://etherscan.io/tx/0xce393fbb4abd385b3ca311b23b37479e2b048fbd45ba1464a9290e0d7cc7aa23#eventlog

Seed value: 62636494988781792158688506166880328040563742414274622435847674300236637261413

Total number of qualified Capsules: 8578

Index of winning Capsule: 62636494988781792158688506166880328040563742414274622435847674300236637261413 % 8578 = 4351

Capsule ID at index 4351: 5042

Owner of Capsule 5042 at the time of the snapshot: 0xB670Acb0C39aC590CDeBba50c9d0b7aeD56E40E5

**5/10/2022 - 12:53 AM PST** - 

Seed for Raffle 13 drawn. https://etherscan.io/tx/0xc89fa4a3bea803d93573adc0a9404a6b1e32773175eb92e1cca095b16261e57c#eventlog

Seed value: 63913340744413336683860231673377012074348012813629700712109603573008592233253

Total number of qualified Capsules: 9045

Index of winning Capsule: 63913340744413336683860231673377012074348012813629700712109603573008592233253 % 9045 = 3663

Capsule ID at index 3663: 4037

Owner of Capsule 5042 at the time of the snapshot: 0x244BeF5aF19D7969280706f37327D01f7cA28d81

**5/16/2022 - 8:05 PM PST** - 

Seed for Raffle 14 drawn. https://etherscan.io/tx/0xe31aece09cf13b94b340bc53a4810f1b75581be3826304e884ae25762fb29d54#eventlog

Seed value: 20863133366678648033717616419200870051163420438522388219529862160189283617898

Total number of qualified Capsules: 9055

Index of winning Capsule: 20863133366678648033717616419200870051163420438522388219529862160189283617898 % 9055 = 5098

Capsule ID at index 5098: 5653

Owner of Capsule 5653 at the time of the snapshot: 0xD188E577A7A722c0F8C91f486BD101FeE05C053F

**5/16/2022 - 8:05 PM PST** - 

Seed for Raffle 14 drawn. https://etherscan.io/tx/0xe31aece09cf13b94b340bc53a4810f1b75581be3826304e884ae25762fb29d54#eventlog

Seed value: 20863133366678648033717616419200870051163420438522388219529862160189283617898

Total number of qualified Capsules: 9055

Index of winning Capsule: 20863133366678648033717616419200870051163420438522388219529862160189283617898 % 9055 = 5098

Capsule ID at index 5098: 5653

Owner of Capsule 5653 at the time of the snapshot: 0xD188E577A7A722c0F8C91f486BD101FeE05C053F

**5/23/2022 - 8:10 PM PST** - 

Seed for Raffle 15 drawn. https://etherscan.io/tx/0x9f2fc4d30c7ddf293113b114ab6b7af177a7849aa5bd97d2be592460fefad038#eventlog

Seed value: 66152956194661475453425214293502848403905799550918628918444053575304084811770

Total number of qualified Capsules: 9153

Index of winning Capsule: 66152956194661475453425214293502848403905799550918628918444053575304084811770 % 9153 = 7218

Capsule ID at index 7218: 7881

Owner of Capsule 7881 at the time of the snapshot: 0xA14964479Ebf9cD336011ad80652b08CD83dFE3A

**5/29/2022 - 8:06 PM PST** - 

Seed for Raffle 16 drawn. https://etherscan.io/tx/0x6a96517dc4d28a7ad419399709d8115c0794859a916f1be8895147e053367080#eventlog

Seed value: 61518797059644417516239064390420666141515917910432328999409473563206723078030

Total number of qualified Capsules: 9252

Index of winning Capsule: 61518797059644417516239064390420666141515917910432328999409473563206723078030 % 9252 = 3942

Capsule ID at index 3942: 4266

Owner of Capsule 4266 at the time of the snapshot: 0x872671917d6CAe71672659621615136d31734A64

**7/6/2022 - 5:37 PM PST** - 

Seed for Raffle 17 drawn. https://etherscan.io/tx/0x8321603bae6a916822c1ed4717c931ce4903671daeb8ddfadc0cd989a15dd135#eventlog

Seed value: 108714238999979764388480188387761634606001521431748263470355131358331430853426

Total number of qualified Capsules: 9611

Index of winning Capsule: 108714238999979764388480188387761634606001521431748263470355131358331430853426 % 9611 = 2237

Capsule ID at index 2237: 2359

Owner of Capsule 2359 at the time of the snapshot: 0xa477803DB91cb844d67742427e3573a9E8D19993

**7/13/2022 - 5:36 PM PST** - 

Seed for Raffle 18 drawn. https://etherscan.io/tx/0x1fb9ecb4b740d97052365378b26ba0626b900d169ca59707ed77cad719f074f6#eventlog

Seed value: 32587636520309085382502140057702915504687166056293203466785779352891111241929

Total number of qualified Capsules: 9541

Index of winning Capsule: 32587636520309085382502140057702915504687166056293203466785779352891111241929 % 9541 = 5463

Capsule ID at index 5463: 5755

Owner of Capsule 5755 at the time of the snapshot: 0xD1E561F1C03797c65075912B2cb5F9214949beE8

**7/20/2022 - 3:08 PM PST** - 

Seed for Raffle 18 drawn. https://etherscan.io/tx/0xe8463cd7269ad8c69f69c4d9aba8b7612f873e019204467aa95c6f32cde202d4#eventlog

Seed value: 32587636520309085382502140057702915504687166056293203466785779352891111241929

Total number of qualified Capsules: 9595

Index of winning Capsule: 90118971566226856872599381946473899454029099473261037387556833311603989420930 % 9595 = 2505

Capsule ID at index 2505: 2627

Owner of Capsule 2627 at the time of the snapshot: 0x594c84B388a2eFf796287A326aCb3775B343C5Ef

**7/27/2022 - 5:42 PM PST** - 

Seed for Raffle 18 drawn. https://etherscan.io/tx/0x06012ce5a65bc19cc0be5cfb06d4cab25e80bf6d0fcb7034ed67b1767a305d9b#eventlog

Seed value: 36019664978232039333473778728341055088606593612878169319690839067601844096264

Total number of qualified Capsules: 9625  

Index of winning Capsule: 36019664978232039333473778728341055088606593612878169319690839067601844096264 % 9625 = 8139

Capsule ID at index 8139: 8453

Owner of Capsule 8453 at the time of the snapshot: 0xB0bDD53b627d7e61cFC5C13EF110e47e210fAc6f
