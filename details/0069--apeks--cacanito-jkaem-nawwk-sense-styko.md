### Roster Details<br />
Team Name: Apeks<br />
Roster: CacaNito, jkaem, nawwk, sense, STYKO<br />
Global Rank: [69](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [48]( ../standings_europe.md)<br />
<br />
Final Rank Value:  956.8<br />
<br />
Final Rank Value (956.8) = Starting Rank Value (898.6) + Head To Head Adjustments (58.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.389[<sup>1</sup>](#table2)
- Bounty Collected: 0.359[<sup>2</sup>](#table1)
- Opponent Network: 0.046[<sup>2</sup>](#table1)
- LAN Wins: 0.180[<sup>2</sup>](#table1)

The average of these factors is 0.244<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 898.6
- 400 + ( ( 0.244 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 898.6


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
|           35 |     2520 | 2024-04-27 | MIBR              | L   | 0.537      | -            | -                | -                | -         |    -1.08 | CacaNito, jkaem, nawwk, sense, STYKO |
|           34 |     2570 | 2024-04-25 | Aurora            | W   | 0.525      | 0.500        | 0.422 (0.111)    | 0.788 (0.207)    | 1 (0.525) |    16.16 | CacaNito, jkaem, nawwk, sense, STYKO |
|           33 |     2576 | 2024-04-25 | sunday school     | W   | 0.523      | 0.500        | 0.003 (0.001)    | -                | 1 (0.523) |     2.51 | CacaNito, jkaem, nawwk, sense, STYKO |
|           32 |     2763 | 2024-04-18 | BetBoom           | L   | 0.475      | -            | -                | -                | -         |    -1.01 | CacaNito, jkaem, nawwk, sense, STYKO |
|           31 |     2766 | 2024-04-18 | DMS               | W   | 0.475      | 0.143        | -                | 0.444 (0.030)    | 0 (0.000) |     6.93 | CacaNito, jkaem, nawwk, sense, STYKO |
|           30 |     2779 | 2024-04-18 | AMKAL             | W   | 0.474      | 0.143        | 0.130 (0.009)    | 0.472 (0.032)    | 0 (0.000) |    11.48 | CacaNito, jkaem, nawwk, sense, STYKO |
|           29 |     2945 | 2024-04-11 | Aurora            | L   | 0.427      | -            | -                | -                | -         |    -0.24 | CacaNito, jkaem, nawwk, sense, STYKO |
|           28 |     2984 | 2024-04-10 | AMKAL             | L   | 0.421      | -            | -                | -                | -         |    -3.31 | CacaNito, jkaem, nawwk, sense, STYKO |
|           27 |     3034 | 2024-04-09 | fnatic            | W   | 0.415      | 0.143        | 0.371 (0.022)    | 0.706 (0.042)    | 0 (0.000) |    12.70 | CacaNito, jkaem, nawwk, sense, STYKO |
|           26 |     3046 | 2024-04-09 | KOI               | W   | 0.414      | 0.143        | 0.058 (0.003)    | 0.372 (0.022)    | 0 (0.000) |     9.35 | CacaNito, jkaem, nawwk, sense, STYKO |
|           25 |     3068 | 2024-04-08 | fnatic            | L   | 0.408      | -            | -                | -                | -         |    -0.34 | CacaNito, jkaem, nawwk, sense, STYKO |
|           24 |     3080 | 2024-04-08 | GUN5              | W   | 0.407      | -            | -                | -                | -         |     0.72 | CacaNito, jkaem, nawwk, sense, STYKO |
|           23 |     3222 | 2024-04-03 | Monte             | L   | 0.373      | -            | -                | -                | -         |    -4.59 | CacaNito, jkaem, nawwk, sense, STYKO |
|           22 |     3252 | 2024-04-02 | Aurora            | L   | 0.368      | -            | -                | -                | -         |    -0.17 | CacaNito, jkaem, nawwk, sense, STYKO |
|           21 |     3260 | 2024-04-02 | B8                | W   | 0.367      | 0.143        | 0.165 (0.009)    | 0.947 (0.050)    | -         |     8.57 | CacaNito, jkaem, nawwk, sense, STYKO |
|           20 |     3285 | 2024-03-31 | B8                | L   | 0.353      | -            | -                | -                | -         |    -2.90 | CacaNito, jkaem, nawwk, sense, STYKO |
|           19 |     3317 | 2024-03-28 | 3DMAX             | L   | 0.334      | -            | -                | -                | -         |    -0.15 | CacaNito, jkaem, nawwk, sense, STYKO |
|           18 |     3382 | 2024-03-26 | FORZE             | L   | 0.320      | -            | -                | -                | -         |    -4.84 | CacaNito, jkaem, nawwk, sense, STYKO |
|           17 |     3482 | 2024-03-19 | Legacy            | L   | 0.274      | -            | -                | -                | -         |    -3.04 | CacaNito, jkaem, nawwk, sense, STYKO |
|           16 |     3495 | 2024-03-18 | Imperial          | L   | 0.266      | -            | -                | -                | -         |    -1.01 | CacaNito, jkaem, nawwk, sense, STYKO |
|           15 |     3508 | 2024-03-17 | AMKAL             | W   | 0.262      | 0.143        | 0.130 (0.005)    | 0.472 (0.018)    | 1 (0.262) |     6.42 | CacaNito, jkaem, nawwk, sense, STYKO |
|           14 |     3524 | 2024-03-17 | paiN              | L   | 0.260      | -            | -                | -                | -         |    -0.47 | CacaNito, jkaem, nawwk, sense, STYKO |
|           13 |     3655 | 2024-03-12 | Metizport         | L   | 0.227      | -            | -                | -                | -         |    -4.15 | CacaNito, jkaem, nawwk, sense, STYKO |
|           12 |     3664 | 2024-03-11 | Virtus.pro        | L   | 0.222      | -            | -                | -                | -         |    -0.08 | CacaNito, jkaem, nawwk, sense, STYKO |
|           11 |     3674 | 2024-03-11 | KOI               | W   | 0.220      | 0.143        | 0.058 (0.002)    | 0.372 (0.012)    | -         |     5.11 | CacaNito, jkaem, nawwk, sense, STYKO |
|           10 |     3767 | 2024-03-07 | Space             | W   | 0.194      | 0.500        | -                | 0.445 (0.043)    | -         |     2.31 | CacaNito, jkaem, nawwk, sense, STYKO |
|            9 |     3795 | 2024-03-06 | PARIVISION        | L   | 0.188      | -            | -                | -                | -         |    -1.47 | CacaNito, jkaem, nawwk, sense, STYKO |
|            8 |     4105 | 2024-02-21 | Gaimin Gladiators | W   | 0.093      | 0.143        | -                | 0.346 (0.005)    | 1 (0.093) |     1.71 | CacaNito, jkaem, nawwk, sense, STYKO |
|            7 |     4136 | 2024-02-20 | Monte             | W   | 0.086      | -            | -                | -                | 1 (0.086) |     1.70 | CacaNito, jkaem, nawwk, sense, STYKO |
|            6 |     4149 | 2024-02-19 | Cloud9            | L   | 0.082      | -            | -                | -                | -         |    -0.83 | CacaNito, jkaem, nawwk, sense, STYKO |
|            5 |     4159 | 2024-02-19 | OG                | W   | 0.080      | 0.143        | 0.138 (0.002)    | -                | 1 (0.080) |     1.59 | CacaNito, jkaem, nawwk, sense, STYKO |
|            4 |     4344 | 2024-02-11 | Metizport         | L   | 0.028      | -            | -                | -                | -         |    -0.53 | CacaNito, jkaem, nawwk, sense, STYKO |
|            3 |     4346 | 2024-02-11 | 3DMAX             | W   | 0.028      | 0.143        | 0.508 (0.002)    | -                | -         |     0.86 | CacaNito, jkaem, nawwk, sense, STYKO |
|            2 |     4359 | 2024-02-10 | Metizport         | W   | 0.021      | -            | -                | -                | -         |     0.26 | CacaNito, jkaem, nawwk, sense, STYKO |
|            1 |     4362 | 2024-02-10 | ex-Anonymo        | W   | 0.020      | -            | -                | -                | -         |     0.04 | CacaNito, jkaem, nawwk, sense, STYKO |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,612.23)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.821 | $500.00        | $410.38         |
| 2024-04-28 |      0.539 | $10,000.00     | $5,389.35       |
| 2024-03-20 |      0.281 | $10,000.00     | $2,812.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
