### Roster Details<br />
Team Name: Apeks<br />
Roster: CacaNito, jkaem, nawwk, sense, STYKO<br />
Global Rank: [66](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [46]( ../standings_europe.md)<br />
<br />
Final Rank Value:  962.8<br />
<br />
Final Rank Value (962.8) = Starting Rank Value (902.6) + Head To Head Adjustments (60.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.390[<sup>1</sup>](#table2)
- Bounty Collected: 0.361[<sup>2</sup>](#table1)
- Opponent Network: 0.047[<sup>2</sup>](#table1)
- LAN Wins: 0.186[<sup>2</sup>](#table1)

The average of these factors is 0.246<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 902.6
- 400 + ( ( 0.246 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 902.6


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
|           35 |     2467 | 2024-04-27 | MIBR              | L   | 0.548      | -            | -                | -                | -         |    -1.11 | CacaNito, jkaem, nawwk, sense, STYKO |
|           34 |     2516 | 2024-04-25 | Aurora            | W   | 0.535      | 0.500        | 0.424 (0.114)    | 0.794 (0.213)    | 1 (0.535) |    16.47 | CacaNito, jkaem, nawwk, sense, STYKO |
|           33 |     2522 | 2024-04-25 | sunday school     | W   | 0.534      | 0.500        | 0.003 (0.001)    | -                | 1 (0.534) |     2.50 | CacaNito, jkaem, nawwk, sense, STYKO |
|           32 |     2709 | 2024-04-18 | BetBoom           | L   | 0.485      | -            | -                | -                | -         |    -1.05 | CacaNito, jkaem, nawwk, sense, STYKO |
|           31 |     2712 | 2024-04-18 | DMS               | W   | 0.485      | 0.143        | -                | 0.446 (0.031)    | 0 (0.000) |     6.95 | CacaNito, jkaem, nawwk, sense, STYKO |
|           30 |     2725 | 2024-04-18 | AMKAL             | W   | 0.485      | 0.143        | 0.130 (0.009)    | 0.477 (0.033)    | 0 (0.000) |    11.67 | CacaNito, jkaem, nawwk, sense, STYKO |
|           29 |     2891 | 2024-04-11 | Aurora            | L   | 0.438      | -            | -                | -                | -         |    -0.26 | CacaNito, jkaem, nawwk, sense, STYKO |
|           28 |     2930 | 2024-04-10 | AMKAL             | L   | 0.432      | -            | -                | -                | -         |    -3.47 | CacaNito, jkaem, nawwk, sense, STYKO |
|           27 |     2980 | 2024-04-09 | fnatic            | W   | 0.425      | 0.143        | 0.371 (0.023)    | 0.709 (0.043)    | 0 (0.000) |    13.00 | CacaNito, jkaem, nawwk, sense, STYKO |
|           26 |     2992 | 2024-04-09 | KOI               | W   | 0.424      | 0.143        | 0.059 (0.004)    | 0.376 (0.023)    | 0 (0.000) |     9.54 | CacaNito, jkaem, nawwk, sense, STYKO |
|           25 |     3014 | 2024-04-08 | fnatic            | L   | 0.419      | -            | -                | -                | -         |    -0.36 | CacaNito, jkaem, nawwk, sense, STYKO |
|           24 |     3026 | 2024-04-08 | GUN5              | W   | 0.417      | -            | -                | -                | -         |     0.72 | CacaNito, jkaem, nawwk, sense, STYKO |
|           23 |     3168 | 2024-04-03 | Monte             | L   | 0.384      | -            | -                | -                | -         |    -4.72 | CacaNito, jkaem, nawwk, sense, STYKO |
|           22 |     3198 | 2024-04-02 | Aurora            | L   | 0.378      | -            | -                | -                | -         |    -0.19 | CacaNito, jkaem, nawwk, sense, STYKO |
|           21 |     3206 | 2024-04-02 | B8                | W   | 0.377      | 0.143        | 0.165 (0.009)    | 0.913 (0.049)    | -         |     8.76 | CacaNito, jkaem, nawwk, sense, STYKO |
|           20 |     3231 | 2024-03-31 | B8                | L   | 0.364      | -            | -                | -                | -         |    -3.04 | CacaNito, jkaem, nawwk, sense, STYKO |
|           19 |     3263 | 2024-03-28 | 3DMAX             | L   | 0.344      | -            | -                | -                | -         |    -0.17 | CacaNito, jkaem, nawwk, sense, STYKO |
|           18 |     3328 | 2024-03-26 | FORZE             | L   | 0.331      | -            | -                | -                | -         |    -5.03 | CacaNito, jkaem, nawwk, sense, STYKO |
|           17 |     3428 | 2024-03-19 | Legacy            | L   | 0.284      | -            | -                | -                | -         |    -3.20 | CacaNito, jkaem, nawwk, sense, STYKO |
|           16 |     3441 | 2024-03-18 | Imperial          | L   | 0.277      | -            | -                | -                | -         |    -1.05 | CacaNito, jkaem, nawwk, sense, STYKO |
|           15 |     3454 | 2024-03-17 | AMKAL             | W   | 0.272      | 0.143        | 0.130 (0.005)    | 0.477 (0.019)    | 1 (0.272) |     6.64 | CacaNito, jkaem, nawwk, sense, STYKO |
|           14 |     3470 | 2024-03-17 | paiN              | L   | 0.271      | -            | -                | -                | -         |    -0.49 | CacaNito, jkaem, nawwk, sense, STYKO |
|           13 |     3600 | 2024-03-12 | Metizport         | L   | 0.238      | -            | -                | -                | -         |    -3.71 | CacaNito, jkaem, nawwk, sense, STYKO |
|           12 |     3609 | 2024-03-11 | Virtus.pro        | L   | 0.232      | -            | -                | -                | -         |    -0.09 | CacaNito, jkaem, nawwk, sense, STYKO |
|           11 |     3619 | 2024-03-11 | KOI               | W   | 0.231      | 0.143        | 0.059 (0.002)    | 0.376 (0.012)    | -         |     5.34 | CacaNito, jkaem, nawwk, sense, STYKO |
|           10 |     3712 | 2024-03-07 | Space             | W   | 0.205      | 0.500        | -                | 0.406 (0.042)    | -         |     2.42 | CacaNito, jkaem, nawwk, sense, STYKO |
|            9 |     3740 | 2024-03-06 | PARIVISION        | L   | 0.198      | -            | -                | -                | -         |    -1.62 | CacaNito, jkaem, nawwk, sense, STYKO |
|            8 |     4050 | 2024-02-21 | Gaimin Gladiators | W   | 0.103      | -            | -                | -                | 1 (0.103) |     1.90 | CacaNito, jkaem, nawwk, sense, STYKO |
|            7 |     4081 | 2024-02-20 | Monte             | W   | 0.097      | -            | -                | -                | 1 (0.097) |     1.91 | CacaNito, jkaem, nawwk, sense, STYKO |
|            6 |     4094 | 2024-02-19 | Cloud9            | L   | 0.092      | -            | -                | -                | -         |    -0.95 | CacaNito, jkaem, nawwk, sense, STYKO |
|            5 |     4104 | 2024-02-19 | OG                | W   | 0.090      | 0.143        | 0.140 (0.002)    | -                | 1 (0.090) |     1.79 | CacaNito, jkaem, nawwk, sense, STYKO |
|            4 |     4288 | 2024-02-11 | Metizport         | L   | 0.039      | -            | -                | -                | -         |    -0.62 | CacaNito, jkaem, nawwk, sense, STYKO |
|            3 |     4290 | 2024-02-11 | 3DMAX             | W   | 0.038      | 0.143        | 0.505 (0.003)    | 1.000 (0.005)    | -         |     1.19 | CacaNito, jkaem, nawwk, sense, STYKO |
|            2 |     4303 | 2024-02-10 | Metizport         | W   | 0.031      | -            | -                | -                | -         |     0.49 | CacaNito, jkaem, nawwk, sense, STYKO |
|            1 |     4306 | 2024-02-10 | ex-Anonymo        | W   | 0.031      | -            | -                | -                | -         |     0.05 | CacaNito, jkaem, nawwk, sense, STYKO |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,828.62)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.831 | $500.00        | $415.66         |
| 2024-04-28 |      0.549 | $10,000.00     | $5,494.91       |
| 2024-03-20 |      0.292 | $10,000.00     | $2,918.06       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
