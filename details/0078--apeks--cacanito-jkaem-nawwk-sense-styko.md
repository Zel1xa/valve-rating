### Roster Details<br />
Team Name: Apeks<br />
Roster: CacaNito, jkaem, nawwk, sense, STYKO<br />
Global Rank: [78](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [55]( ../standings_europe.md)<br />
<br />
Final Rank Value:  954.4<br />
<br />
Final Rank Value (954.4) = Starting Rank Value (896.5) + Head To Head Adjustments (57.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.388[<sup>1</sup>](#table2)
- Bounty Collected: 0.358[<sup>2</sup>](#table1)
- Opponent Network: 0.043[<sup>2</sup>](#table1)
- LAN Wins: 0.176[<sup>2</sup>](#table1)

The average of these factors is 0.241<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 896.5
- 400 + ( ( 0.241 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 896.5


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
|           35 |     2550 | 2024-04-27 | MIBR              | L   | 0.530      | -            | -                | -                | -         |    -1.08 | CacaNito, jkaem, nawwk, sense, STYKO |
|           34 |     2600 | 2024-04-25 | Aurora            | W   | 0.517      | 0.500        | 0.420 (0.109)    | 0.758 (0.196)    | 1 (0.517) |    15.95 | CacaNito, jkaem, nawwk, sense, STYKO |
|           33 |     2606 | 2024-04-25 | sunday school     | W   | 0.516      | 0.500        | 0.003 (0.001)    | -                | 1 (0.516) |     2.49 | CacaNito, jkaem, nawwk, sense, STYKO |
|           32 |     2793 | 2024-04-18 | BetBoom           | L   | 0.467      | -            | -                | -                | -         |    -1.00 | CacaNito, jkaem, nawwk, sense, STYKO |
|           31 |     2796 | 2024-04-18 | DMS               | W   | 0.467      | 0.143        | -                | 0.428 (0.029)    | 0 (0.000) |     6.84 | CacaNito, jkaem, nawwk, sense, STYKO |
|           30 |     2809 | 2024-04-18 | AMKAL             | W   | 0.467      | 0.143        | 0.130 (0.009)    | 0.452 (0.030)    | 0 (0.000) |    11.36 | CacaNito, jkaem, nawwk, sense, STYKO |
|           29 |     2975 | 2024-04-11 | Aurora            | L   | 0.420      | -            | -                | -                | -         |    -0.23 | CacaNito, jkaem, nawwk, sense, STYKO |
|           28 |     3014 | 2024-04-10 | AMKAL             | L   | 0.414      | -            | -                | -                | -         |    -3.20 | CacaNito, jkaem, nawwk, sense, STYKO |
|           27 |     3064 | 2024-04-09 | fnatic            | W   | 0.407      | 0.143        | 0.371 (0.022)    | 0.680 (0.040)    | 0 (0.000) |    12.47 | CacaNito, jkaem, nawwk, sense, STYKO |
|           26 |     3076 | 2024-04-09 | KOI               | W   | 0.406      | 0.143        | 0.058 (0.003)    | 0.356 (0.021)    | 0 (0.000) |     9.17 | CacaNito, jkaem, nawwk, sense, STYKO |
|           25 |     3098 | 2024-04-08 | fnatic            | L   | 0.401      | -            | -                | -                | -         |    -0.33 | CacaNito, jkaem, nawwk, sense, STYKO |
|           24 |     3110 | 2024-04-08 | GUN5              | W   | 0.399      | -            | -                | -                | -         |     0.71 | CacaNito, jkaem, nawwk, sense, STYKO |
|           23 |     3252 | 2024-04-03 | Monte             | L   | 0.366      | -            | -                | -                | -         |    -4.50 | CacaNito, jkaem, nawwk, sense, STYKO |
|           22 |     3282 | 2024-04-02 | Aurora            | L   | 0.360      | -            | -                | -                | -         |    -0.16 | CacaNito, jkaem, nawwk, sense, STYKO |
|           21 |     3290 | 2024-04-02 | B8                | W   | 0.359      | 0.143        | 0.170 (0.009)    | 0.912 (0.047)    | -         |     8.44 | CacaNito, jkaem, nawwk, sense, STYKO |
|           20 |     3315 | 2024-03-31 | B8                | L   | 0.346      | -            | -                | -                | -         |    -2.79 | CacaNito, jkaem, nawwk, sense, STYKO |
|           19 |     3347 | 2024-03-28 | 3DMAX             | L   | 0.326      | -            | -                | -                | -         |    -0.14 | CacaNito, jkaem, nawwk, sense, STYKO |
|           18 |     3412 | 2024-03-26 | FORZE             | L   | 0.313      | -            | -                | -                | -         |    -4.71 | CacaNito, jkaem, nawwk, sense, STYKO |
|           17 |     3512 | 2024-03-19 | Legacy            | L   | 0.266      | -            | -                | -                | -         |    -2.97 | CacaNito, jkaem, nawwk, sense, STYKO |
|           16 |     3525 | 2024-03-18 | Imperial          | L   | 0.259      | -            | -                | -                | -         |    -1.00 | CacaNito, jkaem, nawwk, sense, STYKO |
|           15 |     3538 | 2024-03-17 | AMKAL             | W   | 0.254      | 0.143        | 0.130 (0.005)    | 0.452 (0.016)    | 1 (0.254) |     6.27 | CacaNito, jkaem, nawwk, sense, STYKO |
|           14 |     3554 | 2024-03-17 | paiN              | L   | 0.253      | -            | -                | -                | -         |    -0.47 | CacaNito, jkaem, nawwk, sense, STYKO |
|           13 |     3685 | 2024-03-12 | Metizport         | L   | 0.220      | -            | -                | -                | -         |    -3.35 | CacaNito, jkaem, nawwk, sense, STYKO |
|           12 |     3694 | 2024-03-11 | Virtus.pro        | L   | 0.214      | -            | -                | -                | -         |    -0.08 | CacaNito, jkaem, nawwk, sense, STYKO |
|           11 |     3704 | 2024-03-11 | KOI               | W   | 0.213      | 0.143        | 0.058 (0.002)    | 0.356 (0.011)    | -         |     4.93 | CacaNito, jkaem, nawwk, sense, STYKO |
|           10 |     3797 | 2024-03-07 | Space             | W   | 0.187      | 0.500        | -                | 0.429 (0.040)    | -         |     2.29 | CacaNito, jkaem, nawwk, sense, STYKO |
|            9 |     3825 | 2024-03-06 | PARIVISION        | L   | 0.180      | -            | -                | -                | -         |    -1.36 | CacaNito, jkaem, nawwk, sense, STYKO |
|            8 |     4135 | 2024-02-21 | Gaimin Gladiators | W   | 0.085      | 0.143        | -                | 0.331 (0.004)    | 1 (0.085) |     1.57 | CacaNito, jkaem, nawwk, sense, STYKO |
|            7 |     4166 | 2024-02-20 | Monte             | W   | 0.079      | -            | -                | -                | 1 (0.079) |     1.55 | CacaNito, jkaem, nawwk, sense, STYKO |
|            6 |     4179 | 2024-02-19 | Cloud9            | L   | 0.074      | -            | -                | -                | -         |    -0.76 | CacaNito, jkaem, nawwk, sense, STYKO |
|            5 |     4189 | 2024-02-19 | OG                | W   | 0.072      | 0.143        | 0.137 (0.001)    | -                | 1 (0.072) |     1.44 | CacaNito, jkaem, nawwk, sense, STYKO |
|            4 |     4374 | 2024-02-11 | Metizport         | L   | 0.021      | -            | -                | -                | -         |    -0.32 | CacaNito, jkaem, nawwk, sense, STYKO |
|            3 |     4376 | 2024-02-11 | 3DMAX             | W   | 0.020      | 0.143        | 0.510 (0.001)    | -                | -         |     0.63 | CacaNito, jkaem, nawwk, sense, STYKO |
|            2 |     4389 | 2024-02-10 | Metizport         | W   | 0.013      | -            | -                | -                | -         |     0.21 | CacaNito, jkaem, nawwk, sense, STYKO |
|            1 |     4392 | 2024-02-10 | ex-Anonymo        | W   | 0.013      | -            | -                | -                | -         |     0.02 | CacaNito, jkaem, nawwk, sense, STYKO |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,458.48)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.813 | $500.00        | $406.63         |
| 2024-04-28 |      0.531 | $10,000.00     | $5,314.35       |
| 2024-03-20 |      0.274 | $10,000.00     | $2,737.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
