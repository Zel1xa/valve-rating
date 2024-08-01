### Roster Details<br />
Team Name: Apeks<br />
Roster: CacaNito, jkaem, nawwk, sense, STYKO<br />
Global Rank: [65](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [45]( ../standings_europe.md)<br />
<br />
Final Rank Value:  974.2<br />
<br />
Final Rank Value (974.2) = Starting Rank Value (917.1) + Head To Head Adjustments (57.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.396[<sup>1</sup>](#table2)
- Bounty Collected: 0.362[<sup>2</sup>](#table1)
- Opponent Network: 0.047[<sup>2</sup>](#table1)
- LAN Wins: 0.199[<sup>2</sup>](#table1)

The average of these factors is 0.251<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 917.1
- 400 + ( ( 0.251 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 917.1


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
|           38 |     2448 | 2024-04-27 | MIBR              | L   | 0.564      | -            | -                | -                | -         |    -1.26 | CacaNito, jkaem, nawwk, sense, STYKO |
|           37 |     2498 | 2024-04-25 | Aurora            | W   | 0.552      | 0.500        | 0.432 (0.119)    | 0.798 (0.220)    | 1 (0.552) |    16.97 | CacaNito, jkaem, nawwk, sense, STYKO |
|           36 |     2504 | 2024-04-25 | sunday school     | W   | 0.550      | -            | -                | -                | 1 (0.550) |     2.50 | CacaNito, jkaem, nawwk, sense, STYKO |
|           35 |     2695 | 2024-04-18 | ex-Sprout         | W   | 0.502      | -            | -                | -                | 0 (0.000) |     0.67 | CacaNito, jkaem, nawwk, sense, STYKO |
|           34 |     2699 | 2024-04-18 | BetBoom           | L   | 0.502      | -            | -                | -                | -         |    -1.11 | CacaNito, jkaem, nawwk, sense, STYKO |
|           33 |     2702 | 2024-04-18 | DMS               | W   | 0.501      | 0.143        | -                | 0.447 (0.032)    | 0 (0.000) |     7.08 | CacaNito, jkaem, nawwk, sense, STYKO |
|           32 |     2715 | 2024-04-18 | AMKAL             | W   | 0.501      | 0.143        | 0.132 (0.009)    | 0.482 (0.035)    | 0 (0.000) |    11.98 | CacaNito, jkaem, nawwk, sense, STYKO |
|           31 |     2884 | 2024-04-11 | Aurora            | L   | 0.454      | -            | -                | -                | -         |    -0.28 | CacaNito, jkaem, nawwk, sense, STYKO |
|           30 |     2923 | 2024-04-10 | AMKAL             | L   | 0.448      | -            | -                | -                | -         |    -3.69 | CacaNito, jkaem, nawwk, sense, STYKO |
|           29 |     2973 | 2024-04-09 | fnatic            | W   | 0.442      | 0.143        | 0.292 (0.018)    | 0.529 (0.033)    | 0 (0.000) |    12.78 | CacaNito, jkaem, nawwk, sense, STYKO |
|           28 |     2985 | 2024-04-09 | KOI               | W   | 0.441      | 0.143        | 0.040 (0.003)    | 0.313 (0.020)    | -         |     7.31 | CacaNito, jkaem, nawwk, sense, STYKO |
|           27 |     3007 | 2024-04-08 | fnatic            | L   | 0.435      | -            | -                | -                | -         |    -1.06 | CacaNito, jkaem, nawwk, sense, STYKO |
|           26 |     3019 | 2024-04-08 | GUN5              | W   | 0.434      | -            | -                | -                | -         |     0.70 | CacaNito, jkaem, nawwk, sense, STYKO |
|           25 |     3167 | 2024-04-03 | Monte             | L   | 0.400      | -            | -                | -                | -         |    -4.89 | CacaNito, jkaem, nawwk, sense, STYKO |
|           24 |     3199 | 2024-04-02 | Aurora            | L   | 0.395      | -            | -                | -                | -         |    -0.19 | CacaNito, jkaem, nawwk, sense, STYKO |
|           23 |     3207 | 2024-04-02 | B8                | W   | 0.394      | 0.143        | 0.168 (0.009)    | 0.878 (0.049)    | -         |     9.09 | CacaNito, jkaem, nawwk, sense, STYKO |
|           22 |     3232 | 2024-03-31 | B8                | L   | 0.380      | -            | -                | -                | -         |    -3.22 | CacaNito, jkaem, nawwk, sense, STYKO |
|           21 |     3264 | 2024-03-28 | 3DMAX             | L   | 0.361      | -            | -                | -                | -         |    -0.18 | CacaNito, jkaem, nawwk, sense, STYKO |
|           20 |     3334 | 2024-03-26 | FORZE             | L   | 0.347      | -            | -                | -                | -         |    -5.33 | CacaNito, jkaem, nawwk, sense, STYKO |
|           19 |     3434 | 2024-03-19 | Legacy            | L   | 0.301      | -            | -                | -                | -         |    -3.43 | CacaNito, jkaem, nawwk, sense, STYKO |
|           18 |     3447 | 2024-03-18 | Imperial          | L   | 0.293      | -            | -                | -                | -         |    -1.13 | CacaNito, jkaem, nawwk, sense, STYKO |
|           17 |     3460 | 2024-03-17 | AMKAL             | W   | 0.289      | 0.143        | 0.132 (0.005)    | 0.482 (0.020)    | 1 (0.289) |     6.96 | CacaNito, jkaem, nawwk, sense, STYKO |
|           16 |     3476 | 2024-03-17 | paiN              | L   | 0.287      | -            | -                | -                | -         |    -0.73 | CacaNito, jkaem, nawwk, sense, STYKO |
|           15 |     3612 | 2024-03-12 | Metizport         | L   | 0.254      | -            | -                | -                | -         |    -4.11 | CacaNito, jkaem, nawwk, sense, STYKO |
|           14 |     3621 | 2024-03-11 | Virtus.pro        | L   | 0.249      | -            | -                | -                | -         |    -0.09 | CacaNito, jkaem, nawwk, sense, STYKO |
|           13 |     3631 | 2024-03-11 | KOI               | W   | 0.247      | 0.143        | 0.040 (0.001)    | 0.313 (0.011)    | -         |     4.14 | CacaNito, jkaem, nawwk, sense, STYKO |
|           12 |     3725 | 2024-03-07 | Space             | W   | 0.221      | 0.500        | -                | 0.406 (0.045)    | -         |     2.51 | CacaNito, jkaem, nawwk, sense, STYKO |
|           11 |     3753 | 2024-03-06 | PARIVISION        | L   | 0.214      | -            | -                | -                | -         |    -1.89 | CacaNito, jkaem, nawwk, sense, STYKO |
|           10 |     4079 | 2024-02-21 | Gaimin Gladiators | W   | 0.120      | -            | -                | -                | 1 (0.120) |     2.21 | CacaNito, jkaem, nawwk, sense, STYKO |
|            9 |     4109 | 2024-02-20 | Monte             | W   | 0.113      | 0.143        | 0.062 (0.001)    | -                | 1 (0.113) |     2.25 | CacaNito, jkaem, nawwk, sense, STYKO |
|            8 |     4122 | 2024-02-19 | Cloud9            | L   | 0.109      | -            | -                | -                | -         |    -1.09 | CacaNito, jkaem, nawwk, sense, STYKO |
|            7 |     4132 | 2024-02-19 | OG                | W   | 0.107      | 0.143        | 0.143 (0.002)    | -                | 1 (0.107) |     2.06 | CacaNito, jkaem, nawwk, sense, STYKO |
|            6 |     4325 | 2024-02-11 | Metizport         | L   | 0.055      | -            | -                | -                | -         |    -0.91 | CacaNito, jkaem, nawwk, sense, STYKO |
|            5 |     4328 | 2024-02-11 | 3DMAX             | W   | 0.055      | 0.143        | 0.505 (0.004)    | 1.000 (0.008)    | -         |     1.70 | CacaNito, jkaem, nawwk, sense, STYKO |
|            4 |     4341 | 2024-02-10 | Metizport         | W   | 0.047      | -            | -                | -                | -         |     0.72 | CacaNito, jkaem, nawwk, sense, STYKO |
|            3 |     4344 | 2024-02-10 | ex-Anonymo        | W   | 0.047      | -            | -                | -                | -         |     0.13 | CacaNito, jkaem, nawwk, sense, STYKO |
|            2 |     4413 | 2024-02-04 | Natus Vincere     | L   | 0.008      | -            | -                | -                | -         |    -0.00 | CacaNito, jkaem, nawwk, sense, STYKO |
|            1 |     4434 | 2024-02-03 | Complexity        | L   | 0.002      | -            | -                | -                | -         |    -0.00 | CacaNito, jkaem, nawwk, sense, STYKO |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,709.04)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.848 | $500.00        | $423.85         |
| 2024-04-28 |      0.566 | $10,000.00     | $5,658.80       |
| 2024-03-20 |      0.308 | $10,000.00     | $3,081.94       |
| 2024-02-11 |      0.054 | $10,000.00     | $544.44         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
