### Roster Details<br />
Team Name: Apeks<br />
Roster: CacaNito, jkaem, nawwk, sense, STYKO<br />
Global Rank: [66](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [46]( ../standings_europe.md)<br />
<br />
Final Rank Value:  958.7<br />
<br />
Final Rank Value (958.7) = Starting Rank Value (902.9) + Head To Head Adjustments (55.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.390[<sup>1</sup>](#table2)
- Bounty Collected: 0.359[<sup>2</sup>](#table1)
- Opponent Network: 0.047[<sup>2</sup>](#table1)
- LAN Wins: 0.187[<sup>2</sup>](#table1)

The average of these factors is 0.246<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 902.9
- 400 + ( ( 0.246 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 902.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |     2401 | 2024-04-27 | MIBR              | L   | 0.549      | -            | -                | -                | -         |    -1.12 | CacaNito, jkaem, nawwk, sense, STYKO |
|           34 |     2450 | 2024-04-25 | Aurora            | W   | 0.537      | 0.500        | 0.425 (0.114)    | 0.809 (0.217)    | 1 (0.537) |    16.54 | CacaNito, jkaem, nawwk, sense, STYKO |
|           33 |     2456 | 2024-04-25 | sunday school     | W   | 0.535      | 0.500        | 0.003 (0.001)    | -                | 1 (0.535) |     2.57 | CacaNito, jkaem, nawwk, sense, STYKO |
|           32 |     2643 | 2024-04-18 | BetBoom           | L   | 0.487      | -            | -                | -                | -         |    -1.04 | CacaNito, jkaem, nawwk, sense, STYKO |
|           31 |     2646 | 2024-04-18 | DMS               | W   | 0.487      | 0.143        | -                | 0.462 (0.032)    | 0 (0.000) |     7.08 | CacaNito, jkaem, nawwk, sense, STYKO |
|           30 |     2659 | 2024-04-18 | AMKAL             | W   | 0.486      | 0.143        | 0.130 (0.009)    | 0.494 (0.034)    | 0 (0.000) |    11.82 | CacaNito, jkaem, nawwk, sense, STYKO |
|           29 |     2825 | 2024-04-11 | Aurora            | L   | 0.440      | -            | -                | -                | -         |    -0.25 | CacaNito, jkaem, nawwk, sense, STYKO |
|           28 |     2864 | 2024-04-10 | AMKAL             | L   | 0.434      | -            | -                | -                | -         |    -3.38 | CacaNito, jkaem, nawwk, sense, STYKO |
|           27 |     2914 | 2024-04-09 | fnatic            | W   | 0.427      | 0.143        | 0.290 (0.018)    | 0.627 (0.038)    | 0 (0.000) |    12.39 | CacaNito, jkaem, nawwk, sense, STYKO |
|           26 |     2926 | 2024-04-09 | KOI               | W   | 0.426      | 0.143        | 0.040 (0.002)    | 0.319 (0.019)    | 0 (0.000) |     7.19 | CacaNito, jkaem, nawwk, sense, STYKO |
|           25 |     2948 | 2024-04-08 | fnatic            | L   | 0.420      | -            | -                | -                | -         |    -0.99 | CacaNito, jkaem, nawwk, sense, STYKO |
|           24 |     2960 | 2024-04-08 | GUN5              | W   | 0.419      | -            | -                | -                | -         |     0.73 | CacaNito, jkaem, nawwk, sense, STYKO |
|           23 |     3102 | 2024-04-03 | Monte             | L   | 0.386      | -            | -                | -                | -         |    -4.69 | CacaNito, jkaem, nawwk, sense, STYKO |
|           22 |     3132 | 2024-04-02 | Aurora            | L   | 0.380      | -            | -                | -                | -         |    -0.18 | CacaNito, jkaem, nawwk, sense, STYKO |
|           21 |     3140 | 2024-04-02 | B8                | W   | 0.379      | 0.143        | 0.166 (0.009)    | 0.945 (0.051)    | -         |     8.83 | CacaNito, jkaem, nawwk, sense, STYKO |
|           20 |     3165 | 2024-03-31 | B8                | L   | 0.366      | -            | -                | -                | -         |    -3.02 | CacaNito, jkaem, nawwk, sense, STYKO |
|           19 |     3197 | 2024-03-28 | 3DMAX             | L   | 0.346      | -            | -                | -                | -         |    -0.17 | CacaNito, jkaem, nawwk, sense, STYKO |
|           18 |     3259 | 2024-03-26 | FORZE             | L   | 0.332      | -            | -                | -                | -         |    -5.04 | CacaNito, jkaem, nawwk, sense, STYKO |
|           17 |     3357 | 2024-03-19 | Legacy            | L   | 0.286      | -            | -                | -                | -         |    -3.23 | CacaNito, jkaem, nawwk, sense, STYKO |
|           16 |     3370 | 2024-03-18 | Imperial          | L   | 0.279      | -            | -                | -                | -         |    -1.21 | CacaNito, jkaem, nawwk, sense, STYKO |
|           15 |     3383 | 2024-03-17 | AMKAL             | W   | 0.274      | 0.143        | 0.130 (0.005)    | 0.494 (0.019)    | 1 (0.274) |     6.72 | CacaNito, jkaem, nawwk, sense, STYKO |
|           14 |     3399 | 2024-03-17 | paiN              | L   | 0.272      | -            | -                | -                | -         |    -0.63 | CacaNito, jkaem, nawwk, sense, STYKO |
|           13 |     3527 | 2024-03-12 | Metizport         | L   | 0.239      | -            | -                | -                | -         |    -3.73 | CacaNito, jkaem, nawwk, sense, STYKO |
|           12 |     3536 | 2024-03-11 | Virtus.pro        | L   | 0.234      | -            | -                | -                | -         |    -0.09 | CacaNito, jkaem, nawwk, sense, STYKO |
|           11 |     3546 | 2024-03-11 | KOI               | W   | 0.233      | 0.143        | 0.040 (0.001)    | 0.319 (0.011)    | -         |     3.97 | CacaNito, jkaem, nawwk, sense, STYKO |
|           10 |     3639 | 2024-03-07 | Space             | W   | 0.206      | 0.500        | -                | 0.420 (0.043)    | -         |     2.47 | CacaNito, jkaem, nawwk, sense, STYKO |
|            9 |     3667 | 2024-03-06 | PARIVISION        | L   | 0.200      | -            | -                | -                | -         |    -1.61 | CacaNito, jkaem, nawwk, sense, STYKO |
|            8 |     3978 | 2024-02-21 | Gaimin Gladiators | W   | 0.105      | -            | -                | -                | 1 (0.105) |     1.95 | CacaNito, jkaem, nawwk, sense, STYKO |
|            7 |     4008 | 2024-02-20 | Monte             | W   | 0.098      | -            | -                | -                | 1 (0.098) |     1.95 | CacaNito, jkaem, nawwk, sense, STYKO |
|            6 |     4021 | 2024-02-19 | Cloud9            | L   | 0.094      | -            | -                | -                | -         |    -0.96 | CacaNito, jkaem, nawwk, sense, STYKO |
|            5 |     4031 | 2024-02-19 | OG                | W   | 0.092      | 0.143        | 0.140 (0.002)    | -                | 1 (0.092) |     1.80 | CacaNito, jkaem, nawwk, sense, STYKO |
|            4 |     4215 | 2024-02-11 | Metizport         | L   | 0.041      | -            | -                | -                | -         |    -0.64 | CacaNito, jkaem, nawwk, sense, STYKO |
|            3 |     4217 | 2024-02-11 | 3DMAX             | W   | 0.040      | 0.143        | 0.504 (0.003)    | 1.000 (0.006)    | -         |     1.24 | CacaNito, jkaem, nawwk, sense, STYKO |
|            2 |     4230 | 2024-02-10 | Metizport         | W   | 0.033      | -            | -                | -                | -         |     0.52 | CacaNito, jkaem, nawwk, sense, STYKO |
|            1 |     4233 | 2024-02-10 | ex-Anonymo        | W   | 0.032      | -            | -                | -                | -         |     0.06 | CacaNito, jkaem, nawwk, sense, STYKO |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,863.74)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.833 | $500.00        | $416.52         |
| 2024-04-28 |      0.551 | $10,000.00     | $5,512.04       |
| 2024-03-20 |      0.294 | $10,000.00     | $2,935.19       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
