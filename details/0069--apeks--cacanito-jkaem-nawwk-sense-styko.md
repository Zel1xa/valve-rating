### Roster Details<br />
Team Name: Apeks<br />
Roster: CacaNito, jkaem, nawwk, sense, STYKO<br />
Global Rank: [69](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [48]( ../standings_europe.md)<br />
<br />
Final Rank Value:  958.4<br />
<br />
Final Rank Value (958.4) = Starting Rank Value (899.7) + Head To Head Adjustments (58.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.389[<sup>1</sup>](#table2)
- Bounty Collected: 0.360[<sup>2</sup>](#table1)
- Opponent Network: 0.046[<sup>2</sup>](#table1)
- LAN Wins: 0.182[<sup>2</sup>](#table1)

The average of these factors is 0.244<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 899.7
- 400 + ( ( 0.244 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 899.7


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
|           35 |     2507 | 2024-04-27 | MIBR              | L   | 0.541      | -            | -                | -                | -         |    -1.09 | CacaNito, jkaem, nawwk, sense, STYKO |
|           34 |     2557 | 2024-04-25 | Aurora            | W   | 0.528      | 0.500        | 0.423 (0.112)    | 0.792 (0.209)    | 1 (0.528) |    16.26 | CacaNito, jkaem, nawwk, sense, STYKO |
|           33 |     2563 | 2024-04-25 | sunday school     | W   | 0.526      | 0.500        | 0.003 (0.001)    | -                | 1 (0.526) |     2.51 | CacaNito, jkaem, nawwk, sense, STYKO |
|           32 |     2750 | 2024-04-18 | BetBoom           | L   | 0.478      | -            | -                | -                | -         |    -1.02 | CacaNito, jkaem, nawwk, sense, STYKO |
|           31 |     2753 | 2024-04-18 | DMS               | W   | 0.478      | 0.143        | -                | 0.446 (0.030)    | 0 (0.000) |     6.94 | CacaNito, jkaem, nawwk, sense, STYKO |
|           30 |     2766 | 2024-04-18 | AMKAL             | W   | 0.477      | 0.143        | 0.130 (0.009)    | 0.474 (0.032)    | 0 (0.000) |    11.55 | CacaNito, jkaem, nawwk, sense, STYKO |
|           29 |     2932 | 2024-04-11 | Aurora            | L   | 0.431      | -            | -                | -                | -         |    -0.25 | CacaNito, jkaem, nawwk, sense, STYKO |
|           28 |     2971 | 2024-04-10 | AMKAL             | L   | 0.425      | -            | -                | -                | -         |    -3.36 | CacaNito, jkaem, nawwk, sense, STYKO |
|           27 |     3021 | 2024-04-09 | fnatic            | W   | 0.418      | 0.143        | 0.371 (0.022)    | 0.708 (0.042)    | 0 (0.000) |    12.79 | CacaNito, jkaem, nawwk, sense, STYKO |
|           26 |     3033 | 2024-04-09 | KOI               | W   | 0.417      | 0.143        | 0.058 (0.003)    | 0.374 (0.022)    | 0 (0.000) |     9.43 | CacaNito, jkaem, nawwk, sense, STYKO |
|           25 |     3055 | 2024-04-08 | fnatic            | L   | 0.411      | -            | -                | -                | -         |    -0.35 | CacaNito, jkaem, nawwk, sense, STYKO |
|           24 |     3067 | 2024-04-08 | GUN5              | W   | 0.410      | -            | -                | -                | -         |     0.72 | CacaNito, jkaem, nawwk, sense, STYKO |
|           23 |     3209 | 2024-04-03 | Monte             | L   | 0.377      | -            | -                | -                | -         |    -4.63 | CacaNito, jkaem, nawwk, sense, STYKO |
|           22 |     3239 | 2024-04-02 | Aurora            | L   | 0.371      | -            | -                | -                | -         |    -0.18 | CacaNito, jkaem, nawwk, sense, STYKO |
|           21 |     3247 | 2024-04-02 | B8                | W   | 0.370      | 0.143        | 0.165 (0.009)    | 0.951 (0.050)    | -         |     8.63 | CacaNito, jkaem, nawwk, sense, STYKO |
|           20 |     3272 | 2024-03-31 | B8                | L   | 0.357      | -            | -                | -                | -         |    -2.94 | CacaNito, jkaem, nawwk, sense, STYKO |
|           19 |     3304 | 2024-03-28 | 3DMAX             | L   | 0.337      | -            | -                | -                | -         |    -0.15 | CacaNito, jkaem, nawwk, sense, STYKO |
|           18 |     3369 | 2024-03-26 | FORZE             | L   | 0.323      | -            | -                | -                | -         |    -4.90 | CacaNito, jkaem, nawwk, sense, STYKO |
|           17 |     3469 | 2024-03-19 | Legacy            | L   | 0.277      | -            | -                | -                | -         |    -3.08 | CacaNito, jkaem, nawwk, sense, STYKO |
|           16 |     3482 | 2024-03-18 | Imperial          | L   | 0.270      | -            | -                | -                | -         |    -1.02 | CacaNito, jkaem, nawwk, sense, STYKO |
|           15 |     3495 | 2024-03-17 | AMKAL             | W   | 0.265      | 0.143        | 0.130 (0.005)    | 0.474 (0.018)    | 1 (0.265) |     6.50 | CacaNito, jkaem, nawwk, sense, STYKO |
|           14 |     3511 | 2024-03-17 | paiN              | L   | 0.263      | -            | -                | -                | -         |    -0.47 | CacaNito, jkaem, nawwk, sense, STYKO |
|           13 |     3642 | 2024-03-12 | Metizport         | L   | 0.230      | -            | -                | -                | -         |    -4.22 | CacaNito, jkaem, nawwk, sense, STYKO |
|           12 |     3651 | 2024-03-11 | Virtus.pro        | L   | 0.225      | -            | -                | -                | -         |    -0.08 | CacaNito, jkaem, nawwk, sense, STYKO |
|           11 |     3661 | 2024-03-11 | KOI               | W   | 0.224      | 0.143        | 0.058 (0.002)    | 0.374 (0.012)    | -         |     5.18 | CacaNito, jkaem, nawwk, sense, STYKO |
|           10 |     3754 | 2024-03-07 | Space             | W   | 0.198      | 0.500        | -                | 0.406 (0.040)    | -         |     2.34 | CacaNito, jkaem, nawwk, sense, STYKO |
|            9 |     3782 | 2024-03-06 | PARIVISION        | L   | 0.191      | -            | -                | -                | -         |    -1.52 | CacaNito, jkaem, nawwk, sense, STYKO |
|            8 |     4092 | 2024-02-21 | Gaimin Gladiators | W   | 0.096      | 0.143        | -                | 0.349 (0.005)    | 1 (0.096) |     1.77 | CacaNito, jkaem, nawwk, sense, STYKO |
|            7 |     4123 | 2024-02-20 | Monte             | W   | 0.089      | -            | -                | -                | 1 (0.089) |     1.76 | CacaNito, jkaem, nawwk, sense, STYKO |
|            6 |     4136 | 2024-02-19 | Cloud9            | L   | 0.085      | -            | -                | -                | -         |    -0.86 | CacaNito, jkaem, nawwk, sense, STYKO |
|            5 |     4146 | 2024-02-19 | OG                | W   | 0.083      | 0.143        | 0.138 (0.002)    | -                | 1 (0.083) |     1.66 | CacaNito, jkaem, nawwk, sense, STYKO |
|            4 |     4331 | 2024-02-11 | Metizport         | L   | 0.032      | -            | -                | -                | -         |    -0.59 | CacaNito, jkaem, nawwk, sense, STYKO |
|            3 |     4333 | 2024-02-11 | 3DMAX             | W   | 0.031      | 0.143        | 0.507 (0.002)    | -                | -         |     0.96 | CacaNito, jkaem, nawwk, sense, STYKO |
|            2 |     4346 | 2024-02-10 | Metizport         | W   | 0.024      | -            | -                | -                | -         |     0.31 | CacaNito, jkaem, nawwk, sense, STYKO |
|            1 |     4349 | 2024-02-10 | ex-Anonymo        | W   | 0.023      | -            | -                | -                | -         |     0.04 | CacaNito, jkaem, nawwk, sense, STYKO |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,680.57)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.824 | $500.00        | $412.05         |
| 2024-04-28 |      0.542 | $10,000.00     | $5,422.69       |
| 2024-03-20 |      0.285 | $10,000.00     | $2,845.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
