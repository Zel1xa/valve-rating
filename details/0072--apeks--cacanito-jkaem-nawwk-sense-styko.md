### Roster Details<br />
Team Name: Apeks<br />
Roster: CacaNito, jkaem, nawwk, sense, STYKO<br />
Global Rank: [72](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [51]( ../standings_europe.md)<br />
<br />
Final Rank Value:  955.3<br />
<br />
Final Rank Value (955.3) = Starting Rank Value (897.6) + Head To Head Adjustments (57.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.388[<sup>1</sup>](#table2)
- Bounty Collected: 0.359[<sup>2</sup>](#table1)
- Opponent Network: 0.045[<sup>2</sup>](#table1)
- LAN Wins: 0.178[<sup>2</sup>](#table1)

The average of these factors is 0.243<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 897.6
- 400 + ( ( 0.243 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 897.6


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
|           35 |     2531 | 2024-04-27 | MIBR              | L   | 0.534      | -            | -                | -                | -         |    -1.08 | CacaNito, jkaem, nawwk, sense, STYKO |
|           34 |     2581 | 2024-04-25 | Aurora            | W   | 0.521      | 0.500        | 0.421 (0.110)    | 0.777 (0.203)    | 1 (0.521) |    16.07 | CacaNito, jkaem, nawwk, sense, STYKO |
|           33 |     2587 | 2024-04-25 | sunday school     | W   | 0.520      | 0.500        | 0.003 (0.001)    | -                | 1 (0.520) |     2.50 | CacaNito, jkaem, nawwk, sense, STYKO |
|           32 |     2774 | 2024-04-18 | BetBoom           | L   | 0.472      | -            | -                | -                | -         |    -1.00 | CacaNito, jkaem, nawwk, sense, STYKO |
|           31 |     2777 | 2024-04-18 | DMS               | W   | 0.471      | 0.143        | -                | 0.438 (0.029)    | 0 (0.000) |     6.90 | CacaNito, jkaem, nawwk, sense, STYKO |
|           30 |     2790 | 2024-04-18 | AMKAL             | W   | 0.471      | 0.143        | 0.130 (0.009)    | 0.464 (0.031)    | 0 (0.000) |    11.42 | CacaNito, jkaem, nawwk, sense, STYKO |
|           29 |     2956 | 2024-04-11 | Aurora            | L   | 0.424      | -            | -                | -                | -         |    -0.24 | CacaNito, jkaem, nawwk, sense, STYKO |
|           28 |     2995 | 2024-04-10 | AMKAL             | L   | 0.418      | -            | -                | -                | -         |    -3.27 | CacaNito, jkaem, nawwk, sense, STYKO |
|           27 |     3045 | 2024-04-09 | fnatic            | W   | 0.412      | 0.143        | 0.371 (0.022)    | 0.696 (0.041)    | 0 (0.000) |    12.59 | CacaNito, jkaem, nawwk, sense, STYKO |
|           26 |     3057 | 2024-04-09 | KOI               | W   | 0.411      | 0.143        | 0.058 (0.003)    | 0.366 (0.021)    | 0 (0.000) |     9.28 | CacaNito, jkaem, nawwk, sense, STYKO |
|           25 |     3079 | 2024-04-08 | fnatic            | L   | 0.405      | -            | -                | -                | -         |    -0.34 | CacaNito, jkaem, nawwk, sense, STYKO |
|           24 |     3091 | 2024-04-08 | GUN5              | W   | 0.403      | -            | -                | -                | -         |     0.72 | CacaNito, jkaem, nawwk, sense, STYKO |
|           23 |     3233 | 2024-04-03 | Monte             | L   | 0.370      | -            | -                | -                | -         |    -4.54 | CacaNito, jkaem, nawwk, sense, STYKO |
|           22 |     3263 | 2024-04-02 | Aurora            | L   | 0.365      | -            | -                | -                | -         |    -0.17 | CacaNito, jkaem, nawwk, sense, STYKO |
|           21 |     3271 | 2024-04-02 | B8                | W   | 0.363      | 0.143        | 0.164 (0.009)    | 0.934 (0.049)    | -         |     8.50 | CacaNito, jkaem, nawwk, sense, STYKO |
|           20 |     3296 | 2024-03-31 | B8                | L   | 0.350      | -            | -                | -                | -         |    -2.86 | CacaNito, jkaem, nawwk, sense, STYKO |
|           19 |     3328 | 2024-03-28 | 3DMAX             | L   | 0.330      | -            | -                | -                | -         |    -0.15 | CacaNito, jkaem, nawwk, sense, STYKO |
|           18 |     3393 | 2024-03-26 | FORZE             | L   | 0.317      | -            | -                | -                | -         |    -4.78 | CacaNito, jkaem, nawwk, sense, STYKO |
|           17 |     3493 | 2024-03-19 | Legacy            | L   | 0.270      | -            | -                | -                | -         |    -3.00 | CacaNito, jkaem, nawwk, sense, STYKO |
|           16 |     3506 | 2024-03-18 | Imperial          | L   | 0.263      | -            | -                | -                | -         |    -1.00 | CacaNito, jkaem, nawwk, sense, STYKO |
|           15 |     3519 | 2024-03-17 | AMKAL             | W   | 0.258      | 0.143        | 0.130 (0.005)    | 0.464 (0.017)    | 1 (0.258) |     6.35 | CacaNito, jkaem, nawwk, sense, STYKO |
|           14 |     3535 | 2024-03-17 | paiN              | L   | 0.257      | -            | -                | -                | -         |    -0.47 | CacaNito, jkaem, nawwk, sense, STYKO |
|           13 |     3666 | 2024-03-12 | Metizport         | L   | 0.224      | -            | -                | -                | -         |    -4.08 | CacaNito, jkaem, nawwk, sense, STYKO |
|           12 |     3675 | 2024-03-11 | Virtus.pro        | L   | 0.218      | -            | -                | -                | -         |    -0.08 | CacaNito, jkaem, nawwk, sense, STYKO |
|           11 |     3685 | 2024-03-11 | KOI               | W   | 0.217      | 0.143        | 0.058 (0.002)    | 0.366 (0.011)    | -         |     5.03 | CacaNito, jkaem, nawwk, sense, STYKO |
|           10 |     3778 | 2024-03-07 | Space             | W   | 0.191      | 0.500        | -                | 0.439 (0.042)    | -         |     2.28 | CacaNito, jkaem, nawwk, sense, STYKO |
|            9 |     3806 | 2024-03-06 | PARIVISION        | L   | 0.184      | -            | -                | -                | -         |    -1.42 | CacaNito, jkaem, nawwk, sense, STYKO |
|            8 |     4116 | 2024-02-21 | Gaimin Gladiators | W   | 0.089      | 0.143        | -                | 0.340 (0.004)    | 1 (0.089) |     1.65 | CacaNito, jkaem, nawwk, sense, STYKO |
|            7 |     4147 | 2024-02-20 | Monte             | W   | 0.083      | -            | -                | -                | 1 (0.083) |     1.63 | CacaNito, jkaem, nawwk, sense, STYKO |
|            6 |     4160 | 2024-02-19 | Cloud9            | L   | 0.078      | -            | -                | -                | -         |    -0.80 | CacaNito, jkaem, nawwk, sense, STYKO |
|            5 |     4170 | 2024-02-19 | OG                | W   | 0.077      | 0.143        | 0.137 (0.002)    | -                | 1 (0.077) |     1.53 | CacaNito, jkaem, nawwk, sense, STYKO |
|            4 |     4355 | 2024-02-11 | Metizport         | L   | 0.025      | -            | -                | -                | -         |    -0.47 | CacaNito, jkaem, nawwk, sense, STYKO |
|            3 |     4357 | 2024-02-11 | 3DMAX             | W   | 0.024      | 0.143        | 0.509 (0.002)    | -                | -         |     0.76 | CacaNito, jkaem, nawwk, sense, STYKO |
|            2 |     4370 | 2024-02-10 | Metizport         | W   | 0.017      | -            | -                | -                | -         |     0.22 | CacaNito, jkaem, nawwk, sense, STYKO |
|            1 |     4373 | 2024-02-10 | ex-Anonymo        | W   | 0.017      | -            | -                | -                | -         |     0.03 | CacaNito, jkaem, nawwk, sense, STYKO |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,543.90)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.817 | $500.00        | $408.72         |
| 2024-04-28 |      0.536 | $10,000.00     | $5,356.02       |
| 2024-03-20 |      0.278 | $10,000.00     | $2,779.17       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
