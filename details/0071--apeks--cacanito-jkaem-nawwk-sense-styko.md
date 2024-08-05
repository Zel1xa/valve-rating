### Roster Details<br />
Team Name: Apeks<br />
Roster: CacaNito, jkaem, nawwk, sense, STYKO<br />
Global Rank: [71](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [50]( ../standings_europe.md)<br />
<br />
Final Rank Value:  956.5<br />
<br />
Final Rank Value (956.5) = Starting Rank Value (898.5) + Head To Head Adjustments (58.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.389[<sup>1</sup>](#table2)
- Bounty Collected: 0.359[<sup>2</sup>](#table1)
- Opponent Network: 0.045[<sup>2</sup>](#table1)
- LAN Wins: 0.180[<sup>2</sup>](#table1)

The average of these factors is 0.243<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 898.5
- 400 + ( ( 0.243 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 898.5


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
|           35 |     2528 | 2024-04-27 | MIBR              | L   | 0.536      | -            | -                | -                | -         |    -1.08 | CacaNito, jkaem, nawwk, sense, STYKO |
|           34 |     2578 | 2024-04-25 | Aurora            | W   | 0.524      | 0.500        | 0.422 (0.110)    | 0.779 (0.204)    | 1 (0.524) |    16.14 | CacaNito, jkaem, nawwk, sense, STYKO |
|           33 |     2584 | 2024-04-25 | sunday school     | W   | 0.522      | 0.500        | 0.003 (0.001)    | -                | 1 (0.522) |     2.51 | CacaNito, jkaem, nawwk, sense, STYKO |
|           32 |     2771 | 2024-04-18 | BetBoom           | L   | 0.474      | -            | -                | -                | -         |    -1.01 | CacaNito, jkaem, nawwk, sense, STYKO |
|           31 |     2774 | 2024-04-18 | DMS               | W   | 0.473      | 0.143        | -                | 0.438 (0.030)    | 0 (0.000) |     6.91 | CacaNito, jkaem, nawwk, sense, STYKO |
|           30 |     2787 | 2024-04-18 | AMKAL             | W   | 0.473      | 0.143        | 0.130 (0.009)    | 0.465 (0.031)    | 0 (0.000) |    11.45 | CacaNito, jkaem, nawwk, sense, STYKO |
|           29 |     2953 | 2024-04-11 | Aurora            | L   | 0.426      | -            | -                | -                | -         |    -0.24 | CacaNito, jkaem, nawwk, sense, STYKO |
|           28 |     2992 | 2024-04-10 | AMKAL             | L   | 0.420      | -            | -                | -                | -         |    -3.31 | CacaNito, jkaem, nawwk, sense, STYKO |
|           27 |     3042 | 2024-04-09 | fnatic            | W   | 0.414      | 0.143        | 0.371 (0.022)    | 0.697 (0.041)    | 0 (0.000) |    12.66 | CacaNito, jkaem, nawwk, sense, STYKO |
|           26 |     3054 | 2024-04-09 | KOI               | W   | 0.413      | 0.143        | 0.058 (0.003)    | 0.367 (0.022)    | 0 (0.000) |     9.33 | CacaNito, jkaem, nawwk, sense, STYKO |
|           25 |     3076 | 2024-04-08 | fnatic            | L   | 0.407      | -            | -                | -                | -         |    -0.34 | CacaNito, jkaem, nawwk, sense, STYKO |
|           24 |     3088 | 2024-04-08 | GUN5              | W   | 0.406      | -            | -                | -                | -         |     0.72 | CacaNito, jkaem, nawwk, sense, STYKO |
|           23 |     3230 | 2024-04-03 | Monte             | L   | 0.372      | -            | -                | -                | -         |    -4.57 | CacaNito, jkaem, nawwk, sense, STYKO |
|           22 |     3260 | 2024-04-02 | Aurora            | L   | 0.367      | -            | -                | -                | -         |    -0.17 | CacaNito, jkaem, nawwk, sense, STYKO |
|           21 |     3268 | 2024-04-02 | B8                | W   | 0.366      | 0.143        | 0.165 (0.009)    | 0.935 (0.049)    | -         |     8.55 | CacaNito, jkaem, nawwk, sense, STYKO |
|           20 |     3293 | 2024-03-31 | B8                | L   | 0.352      | -            | -                | -                | -         |    -2.88 | CacaNito, jkaem, nawwk, sense, STYKO |
|           19 |     3325 | 2024-03-28 | 3DMAX             | L   | 0.333      | -            | -                | -                | -         |    -0.15 | CacaNito, jkaem, nawwk, sense, STYKO |
|           18 |     3390 | 2024-03-26 | FORZE             | L   | 0.319      | -            | -                | -                | -         |    -4.82 | CacaNito, jkaem, nawwk, sense, STYKO |
|           17 |     3490 | 2024-03-19 | Legacy            | L   | 0.273      | -            | -                | -                | -         |    -3.03 | CacaNito, jkaem, nawwk, sense, STYKO |
|           16 |     3503 | 2024-03-18 | Imperial          | L   | 0.265      | -            | -                | -                | -         |    -1.01 | CacaNito, jkaem, nawwk, sense, STYKO |
|           15 |     3516 | 2024-03-17 | AMKAL             | W   | 0.261      | 0.143        | 0.130 (0.005)    | 0.465 (0.017)    | 1 (0.261) |     6.39 | CacaNito, jkaem, nawwk, sense, STYKO |
|           14 |     3532 | 2024-03-17 | paiN              | L   | 0.259      | -            | -                | -                | -         |    -0.47 | CacaNito, jkaem, nawwk, sense, STYKO |
|           13 |     3663 | 2024-03-12 | Metizport         | L   | 0.226      | -            | -                | -                | -         |    -4.12 | CacaNito, jkaem, nawwk, sense, STYKO |
|           12 |     3672 | 2024-03-11 | Virtus.pro        | L   | 0.221      | -            | -                | -                | -         |    -0.08 | CacaNito, jkaem, nawwk, sense, STYKO |
|           11 |     3682 | 2024-03-11 | KOI               | W   | 0.219      | 0.143        | 0.058 (0.002)    | 0.367 (0.011)    | -         |     5.08 | CacaNito, jkaem, nawwk, sense, STYKO |
|           10 |     3775 | 2024-03-07 | Space             | W   | 0.193      | 0.500        | -                | 0.439 (0.042)    | -         |     2.29 | CacaNito, jkaem, nawwk, sense, STYKO |
|            9 |     3803 | 2024-03-06 | PARIVISION        | L   | 0.186      | -            | -                | -                | -         |    -1.44 | CacaNito, jkaem, nawwk, sense, STYKO |
|            8 |     4113 | 2024-02-21 | Gaimin Gladiators | W   | 0.092      | 0.143        | -                | 0.342 (0.004)    | 1 (0.092) |     1.69 | CacaNito, jkaem, nawwk, sense, STYKO |
|            7 |     4144 | 2024-02-20 | Monte             | W   | 0.085      | -            | -                | -                | 1 (0.085) |     1.68 | CacaNito, jkaem, nawwk, sense, STYKO |
|            6 |     4157 | 2024-02-19 | Cloud9            | L   | 0.080      | -            | -                | -                | -         |    -0.82 | CacaNito, jkaem, nawwk, sense, STYKO |
|            5 |     4167 | 2024-02-19 | OG                | W   | 0.079      | 0.143        | 0.138 (0.002)    | -                | 1 (0.079) |     1.57 | CacaNito, jkaem, nawwk, sense, STYKO |
|            4 |     4352 | 2024-02-11 | Metizport         | L   | 0.027      | -            | -                | -                | -         |    -0.51 | CacaNito, jkaem, nawwk, sense, STYKO |
|            3 |     4354 | 2024-02-11 | 3DMAX             | W   | 0.027      | 0.143        | 0.508 (0.002)    | -                | -         |     0.83 | CacaNito, jkaem, nawwk, sense, STYKO |
|            2 |     4367 | 2024-02-10 | Metizport         | W   | 0.019      | -            | -                | -                | -         |     0.25 | CacaNito, jkaem, nawwk, sense, STYKO |
|            1 |     4370 | 2024-02-10 | ex-Anonymo        | W   | 0.019      | -            | -                | -                | -         |     0.03 | CacaNito, jkaem, nawwk, sense, STYKO |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,589.46)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.820 | $500.00        | $409.83         |
| 2024-04-28 |      0.538 | $10,000.00     | $5,378.24       |
| 2024-03-20 |      0.280 | $10,000.00     | $2,801.39       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
