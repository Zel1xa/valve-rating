### Roster Details<br />
Team Name: Apeks<br />
Roster: CacaNito, jkaem, nawwk, sense, STYKO<br />
Global Rank: [68](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [48]( ../standings_europe.md)<br />
<br />
Final Rank Value:  959.7<br />
<br />
Final Rank Value (959.7) = Starting Rank Value (900.7) + Head To Head Adjustments (59.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.389[<sup>1</sup>](#table2)
- Bounty Collected: 0.360[<sup>2</sup>](#table1)
- Opponent Network: 0.046[<sup>2</sup>](#table1)
- LAN Wins: 0.183[<sup>2</sup>](#table1)

The average of these factors is 0.245<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 900.7
- 400 + ( ( 0.245 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 900.7


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
|           35 |     2503 | 2024-04-27 | MIBR              | L   | 0.543      | -            | -                | -                | -         |    -1.10 | CacaNito, jkaem, nawwk, sense, STYKO |
|           34 |     2553 | 2024-04-25 | Aurora            | W   | 0.530      | 0.500        | 0.423 (0.112)    | 0.793 (0.210)    | 1 (0.530) |    16.33 | CacaNito, jkaem, nawwk, sense, STYKO |
|           33 |     2559 | 2024-04-25 | sunday school     | W   | 0.529      | 0.500        | 0.003 (0.001)    | -                | 1 (0.529) |     2.51 | CacaNito, jkaem, nawwk, sense, STYKO |
|           32 |     2746 | 2024-04-18 | BetBoom           | L   | 0.481      | -            | -                | -                | -         |    -1.03 | CacaNito, jkaem, nawwk, sense, STYKO |
|           31 |     2749 | 2024-04-18 | DMS               | W   | 0.480      | 0.143        | -                | 0.446 (0.031)    | 0 (0.000) |     6.95 | CacaNito, jkaem, nawwk, sense, STYKO |
|           30 |     2762 | 2024-04-18 | AMKAL             | W   | 0.480      | 0.143        | 0.130 (0.009)    | 0.475 (0.033)    | 0 (0.000) |    11.59 | CacaNito, jkaem, nawwk, sense, STYKO |
|           29 |     2928 | 2024-04-11 | Aurora            | L   | 0.433      | -            | -                | -                | -         |    -0.25 | CacaNito, jkaem, nawwk, sense, STYKO |
|           28 |     2967 | 2024-04-10 | AMKAL             | L   | 0.427      | -            | -                | -                | -         |    -3.39 | CacaNito, jkaem, nawwk, sense, STYKO |
|           27 |     3017 | 2024-04-09 | fnatic            | W   | 0.421      | 0.143        | 0.371 (0.022)    | 0.708 (0.043)    | 0 (0.000) |    12.86 | CacaNito, jkaem, nawwk, sense, STYKO |
|           26 |     3029 | 2024-04-09 | KOI               | W   | 0.420      | 0.143        | 0.058 (0.003)    | 0.375 (0.022)    | 0 (0.000) |     9.47 | CacaNito, jkaem, nawwk, sense, STYKO |
|           25 |     3051 | 2024-04-08 | fnatic            | L   | 0.414      | -            | -                | -                | -         |    -0.35 | CacaNito, jkaem, nawwk, sense, STYKO |
|           24 |     3063 | 2024-04-08 | GUN5              | W   | 0.412      | -            | -                | -                | -         |     0.72 | CacaNito, jkaem, nawwk, sense, STYKO |
|           23 |     3205 | 2024-04-03 | Monte             | L   | 0.379      | -            | -                | -                | -         |    -4.67 | CacaNito, jkaem, nawwk, sense, STYKO |
|           22 |     3235 | 2024-04-02 | Aurora            | L   | 0.374      | -            | -                | -                | -         |    -0.18 | CacaNito, jkaem, nawwk, sense, STYKO |
|           21 |     3243 | 2024-04-02 | B8                | W   | 0.373      | 0.143        | 0.165 (0.009)    | 0.951 (0.051)    | -         |     8.68 | CacaNito, jkaem, nawwk, sense, STYKO |
|           20 |     3268 | 2024-03-31 | B8                | L   | 0.359      | -            | -                | -                | -         |    -2.97 | CacaNito, jkaem, nawwk, sense, STYKO |
|           19 |     3300 | 2024-03-28 | 3DMAX             | L   | 0.339      | -            | -                | -                | -         |    -0.16 | CacaNito, jkaem, nawwk, sense, STYKO |
|           18 |     3365 | 2024-03-26 | FORZE             | L   | 0.326      | -            | -                | -                | -         |    -4.94 | CacaNito, jkaem, nawwk, sense, STYKO |
|           17 |     3465 | 2024-03-19 | Legacy            | L   | 0.279      | -            | -                | -                | -         |    -3.11 | CacaNito, jkaem, nawwk, sense, STYKO |
|           16 |     3478 | 2024-03-18 | Imperial          | L   | 0.272      | -            | -                | -                | -         |    -1.03 | CacaNito, jkaem, nawwk, sense, STYKO |
|           15 |     3491 | 2024-03-17 | AMKAL             | W   | 0.267      | 0.143        | 0.130 (0.005)    | 0.475 (0.018)    | 1 (0.267) |     6.55 | CacaNito, jkaem, nawwk, sense, STYKO |
|           14 |     3507 | 2024-03-17 | paiN              | L   | 0.266      | -            | -                | -                | -         |    -0.48 | CacaNito, jkaem, nawwk, sense, STYKO |
|           13 |     3638 | 2024-03-12 | Metizport         | L   | 0.233      | -            | -                | -                | -         |    -4.26 | CacaNito, jkaem, nawwk, sense, STYKO |
|           12 |     3647 | 2024-03-11 | Virtus.pro        | L   | 0.227      | -            | -                | -                | -         |    -0.08 | CacaNito, jkaem, nawwk, sense, STYKO |
|           11 |     3657 | 2024-03-11 | KOI               | W   | 0.226      | 0.143        | 0.058 (0.002)    | 0.375 (0.012)    | -         |     5.24 | CacaNito, jkaem, nawwk, sense, STYKO |
|           10 |     3750 | 2024-03-07 | Space             | W   | 0.200      | 0.500        | -                | 0.406 (0.041)    | -         |     2.36 | CacaNito, jkaem, nawwk, sense, STYKO |
|            9 |     3778 | 2024-03-06 | PARIVISION        | L   | 0.193      | -            | -                | -                | -         |    -1.55 | CacaNito, jkaem, nawwk, sense, STYKO |
|            8 |     4088 | 2024-02-21 | Gaimin Gladiators | W   | 0.098      | 0.143        | -                | 0.350 (0.005)    | 1 (0.098) |     1.81 | CacaNito, jkaem, nawwk, sense, STYKO |
|            7 |     4119 | 2024-02-20 | Monte             | W   | 0.092      | -            | -                | -                | 1 (0.092) |     1.81 | CacaNito, jkaem, nawwk, sense, STYKO |
|            6 |     4132 | 2024-02-19 | Cloud9            | L   | 0.087      | -            | -                | -                | -         |    -0.88 | CacaNito, jkaem, nawwk, sense, STYKO |
|            5 |     4142 | 2024-02-19 | OG                | W   | 0.086      | 0.143        | 0.139 (0.002)    | -                | 1 (0.086) |     1.71 | CacaNito, jkaem, nawwk, sense, STYKO |
|            4 |     4327 | 2024-02-11 | Metizport         | L   | 0.034      | -            | -                | -                | -         |    -0.64 | CacaNito, jkaem, nawwk, sense, STYKO |
|            3 |     4329 | 2024-02-11 | 3DMAX             | W   | 0.033      | 0.143        | 0.506 (0.002)    | -                | -         |     1.04 | CacaNito, jkaem, nawwk, sense, STYKO |
|            2 |     4342 | 2024-02-10 | Metizport         | W   | 0.026      | -            | -                | -                | -         |     0.34 | CacaNito, jkaem, nawwk, sense, STYKO |
|            1 |     4345 | 2024-02-10 | ex-Anonymo        | W   | 0.026      | -            | -                | -                | -         |     0.05 | CacaNito, jkaem, nawwk, sense, STYKO |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,729.44)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.826 | $500.00        | $413.24         |
| 2024-04-28 |      0.545 | $10,000.00     | $5,446.53       |
| 2024-03-20 |      0.287 | $10,000.00     | $2,869.68       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
