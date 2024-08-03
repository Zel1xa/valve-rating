### Roster Details<br />
Team Name: Party Astronauts<br />
Roster: ben1337, cxzi, FaNg, Infinite, WolfY<br />
Global Rank: [59](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [16]( ../standings_americas.md)<br />
<br />
Final Rank Value:  992.1<br />
<br />
Final Rank Value (992.1) = Starting Rank Value (929.6) + Head To Head Adjustments (62.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.419[<sup>1</sup>](#table2)
- Bounty Collected: 0.365[<sup>2</sup>](#table1)
- Opponent Network: 0.189[<sup>2</sup>](#table1)
- LAN Wins: 0.062[<sup>2</sup>](#table1)

The average of these factors is 0.259<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 929.6
- 400 + ( ( 0.259 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 929.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           70 |      124 | 2024-07-30 | NRG           | W   | 1.000      | 0.477        | 0.020 (0.010)    | 0.538 (0.257)    | 0 (0.000) |    15.51 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           69 |      128 | 2024-07-30 | NRG           | W   | 1.000      | 0.477        | 0.020 (0.010)    | 0.538 (0.257)    | 0 (0.000) |    16.95 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           68 |      355 | 2024-07-23 | FLUFFY AIMERS | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.23 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           67 |      357 | 2024-07-23 | FLUFFY AIMERS | L   | 1.000      | -            | -                | -                | -         |   -25.83 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           66 |      443 | 2024-07-20 | Wildcard      | L   | 1.000      | -            | -                | -                | -         |   -15.59 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           65 |      579 | 2024-07-17 | Take Flyte    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.33 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           64 |      583 | 2024-07-17 | Take Flyte    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.61 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           63 |      642 | 2024-07-16 | Limitless     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.19 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           62 |      648 | 2024-07-16 | Limitless     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.56 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           61 |      966 | 2024-06-15 | Falcons       | L   | 0.871      | -            | -                | -                | -         |    -2.16 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           60 |     1003 | 2024-06-14 | The MongolZ   | L   | 0.864      | -            | -                | -                | -         |    -0.15 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           59 |     1110 | 2024-06-09 | Legacy        | L   | 0.836      | -            | -                | -                | -         |   -11.91 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           58 |     1176 | 2024-06-08 | Wildcard      | W   | 0.828      | 0.384        | 0.055 (0.017)    | 0.519 (0.165)    | 0 (0.000) |    12.60 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           57 |     1193 | 2024-06-08 | NRG           | L   | 0.827      | -            | -                | -                | -         |   -15.79 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           56 |     1222 | 2024-06-07 | Nouns         | L   | 0.822      | -            | -                | -                | -         |   -13.64 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           55 |     1230 | 2024-06-07 | Legacy        | W   | 0.821      | 0.143        | 0.122 (0.014)    | -                | 0 (0.000) |    13.98 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           54 |     1235 | 2024-06-07 | NRG           | W   | 0.820      | 0.384        | -                | 0.538 (0.170)    | -         |    10.15 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           53 |     1249 | 2024-06-07 | Nouns         | W   | 0.820      | -            | -                | -                | -         |    13.28 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           52 |     1280 | 2024-06-06 | NRG           | W   | 0.816      | 0.477        | 0.020 (0.008)    | 0.538 (0.209)    | -         |    11.32 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           51 |     1299 | 2024-06-06 | E-Xolos LAZER | W   | 0.814      | -            | -                | -                | -         |     6.90 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           50 |     1350 | 2024-06-05 | Wildcard      | L   | 0.809      | -            | -                | -                | -         |   -12.18 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           49 |     1401 | 2024-06-04 | Elevate       | W   | 0.802      | 0.477        | 0.027 (0.010)    | 0.485 (0.186)    | -         |    13.16 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           48 |     1706 | 2024-05-22 | Nouns         | L   | 0.716      | -            | -                | -                | -         |   -11.36 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           47 |     1715 | 2024-05-22 | M80           | W   | 0.715      | 0.477        | 0.188 (0.064)    | 0.608 (0.207)    | -         |    19.11 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           46 |     1719 | 2024-05-22 | M80           | L   | 0.715      | -            | -                | -                | -         |    -3.27 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           45 |     1753 | 2024-05-21 | Limitless     | W   | 0.709      | -            | -                | -                | -         |     3.25 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           44 |     1756 | 2024-05-21 | Limitless     | W   | 0.709      | -            | -                | -                | -         |     3.36 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           43 |     1789 | 2024-05-20 | Akimbo        | W   | 0.703      | -            | -                | -                | -         |     6.23 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           42 |     1857 | 2024-05-18 | NRG           | L   | 0.687      | -            | -                | -                | -         |   -10.73 | ben1337, chop, cxzi, Infinite, WolfY |
|           41 |     1890 | 2024-05-17 | Legacy        | W   | 0.681      | 0.303        | 0.122 (0.025)    | -                | -         |    13.31 | ben1337, chop, cxzi, Infinite, WolfY |
|           40 |     1918 | 2024-05-16 | FLUFFY AIMERS | W   | 0.676      | -            | -                | -                | -         |     5.48 | ben1337, chop, cxzi, Infinite, WolfY |
|           39 |     1921 | 2024-05-16 | FLUFFY AIMERS | W   | 0.676      | -            | -                | -                | -         |     5.74 | ben1337, chop, cxzi, Infinite, WolfY |
|           38 |     2011 | 2024-05-14 | Mythic        | W   | 0.662      | -            | -                | -                | -         |     7.16 | ben1337, chop, cxzi, RUSH, WolfY     |
|           37 |     2018 | 2024-05-14 | Mythic        | L   | 0.662      | -            | -                | -                | -         |   -14.07 | ben1337, chop, cxzi, RUSH, WolfY     |
|           36 |     2111 | 2024-05-11 | BOSS          | L   | 0.641      | -            | -                | -                | -         |   -13.60 | ben1337, chop, cxzi, RUSH, WolfY     |
|           35 |     2115 | 2024-05-11 | Perseverance  | L   | 0.641      | -            | -                | -                | -         |   -15.53 | ben1337, chop, cxzi, RUSH, WolfY     |
|           34 |     2174 | 2024-05-08 | LAG           | W   | 0.623      | -            | -                | -                | -         |     7.31 | ben1337, chop, cxzi, RUSH, WolfY     |
|           33 |     2198 | 2024-05-07 | Elevate       | L   | 0.616      | -            | -                | -                | -         |   -10.24 | ben1337, chop, cxzi, RUSH, WolfY     |
|           32 |     2199 | 2024-05-07 | Elevate       | W   | 0.616      | 0.477        | 0.027 (0.008)    | 0.485 (0.142)    | -         |     9.34 | ben1337, chop, cxzi, RUSH, WolfY     |
|           31 |     2217 | 2024-05-06 | NRG           | L   | 0.609      | -            | -                | -                | -         |   -12.01 | ben1337, chop, cxzi, RUSH, WolfY     |
|           30 |     2218 | 2024-05-06 | NRG           | W   | 0.609      | 0.477        | -                | 0.538 (0.156)    | -         |     7.25 | ben1337, chop, cxzi, RUSH, WolfY     |
|           29 |     2289 | 2024-05-02 | Wildcard      | L   | 0.582      | -            | -                | -                | -         |   -10.36 | ben1337, chop, cxzi, RUSH, WolfY     |
|           28 |     2290 | 2024-05-02 | Wildcard      | W   | 0.582      | 0.477        | 0.055 (0.015)    | 0.519 (0.144)    | -         |     8.12 | ben1337, chop, cxzi, RUSH, WolfY     |
|           27 |     2426 | 2024-04-27 | Aurora        | L   | 0.544      | -            | -                | -                | -         |    -0.42 | ben1337, chop, cxzi, RUSH, WolfY     |
|           26 |     2428 | 2024-04-26 | sunday school | W   | 0.543      | -            | -                | -                | 1 (0.543) |     2.47 | ben1337, chop, cxzi, RUSH, WolfY     |
|           25 |     2454 | 2024-04-25 | Aurora        | L   | 0.536      | -            | -                | -                | -         |    -0.37 | ben1337, chop, cxzi, RUSH, WolfY     |
|           24 |     2894 | 2024-04-09 | Take Flyte    | W   | 0.429      | -            | -                | -                | -         |     2.70 | ben1337, chop, cxzi, RUSH, WolfY     |
|           23 |     2900 | 2024-04-09 | Take Flyte    | W   | 0.429      | -            | -                | -                | -         |     2.76 | ben1337, chop, cxzi, RUSH, WolfY     |
|           22 |     3024 | 2024-04-04 | MIGHT         | W   | 0.396      | -            | -                | -                | -         |     1.14 | ben1337, chop, cxzi, RUSH, WolfY     |
|           21 |     3031 | 2024-04-04 | MIGHT         | W   | 0.396      | -            | -                | -                | -         |     1.16 | ben1337, chop, cxzi, RUSH, WolfY     |
|           20 |     3121 | 2024-04-02 | Perseverance  | W   | 0.383      | -            | -                | -                | -         |     2.83 | ben1337, chop, CLASIA, cxzi, WolfY   |
|           19 |     3124 | 2024-04-02 | Nouns         | L   | 0.381      | -            | -                | -                | -         |    -6.48 | ben1337, chop, CLASIA, cxzi, WolfY   |
|           18 |     3202 | 2024-03-27 | Carpe Diem    | W   | 0.343      | -            | -                | -                | -         |     2.02 | ben1337, chop, cxzi, RUSH, WolfY     |
|           17 |     3205 | 2024-03-27 | Carpe Diem    | W   | 0.343      | -            | -                | -                | -         |     2.05 | ben1337, chop, cxzi, RUSH, WolfY     |
|           16 |     3245 | 2024-03-26 | Nouns         | L   | 0.336      | -            | -                | -                | -         |    -5.80 | ben1337, chop, cxzi, RUSH, WolfY     |
|           15 |     3325 | 2024-03-20 | BOSS          | W   | 0.296      | -            | -                | -                | -         |     3.00 | ben1337, chop, cxzi, RUSH, WolfY     |
|           14 |     3327 | 2024-03-20 | BOSS          | W   | 0.296      | -            | -                | -                | -         |     3.06 | ben1337, chop, cxzi, RUSH, WolfY     |
|           13 |     3346 | 2024-03-19 | Perseverance  | W   | 0.290      | -            | -                | -                | -         |     2.20 | ben1337, chop, cxzi, RUSH, WolfY     |
|           12 |     3348 | 2024-03-19 | Perseverance  | W   | 0.289      | -            | -                | -                | -         |     2.23 | ben1337, chop, cxzi, RUSH, WolfY     |
|           11 |     3475 | 2024-03-13 | Carpe Diem    | W   | 0.248      | -            | -                | -                | -         |     1.55 | ben1337, chop, cxzi, RUSH, WolfY     |
|           10 |     3515 | 2024-03-12 | Elevate       | W   | 0.242      | -            | -                | -                | -         |     3.96 | ben1337, chop, cxzi, RUSH, WolfY     |
|            9 |     3894 | 2024-02-24 | Wildcard      | L   | 0.129      | -            | -                | -                | -         |    -2.15 | ben1337, chop, cxzi, Walco, WolfY    |
|            8 |     3900 | 2024-02-24 | ex-CatEvil    | W   | 0.128      | -            | -                | -                | -         |     0.20 | ben1337, chop, cxzi, Walco, WolfY    |
|            7 |     3936 | 2024-02-22 | Liquid        | L   | 0.116      | -            | -                | -                | -         |    -0.14 | ben1337, chop, cxzi, Walco, WolfY    |
|            6 |     3937 | 2024-02-22 | NRG           | W   | 0.115      | -            | -                | -                | -         |     1.43 | ben1337, chop, cxzi, Walco, WolfY    |
|            5 |     3943 | 2024-02-22 | Take Flyte    | W   | 0.115      | -            | -                | -                | -         |     0.82 | ben1337, chop, cxzi, Walco, WolfY    |
|            4 |     3990 | 2024-02-20 | NRG           | W   | 0.103      | -            | -                | -                | -         |     1.28 | ben1337, chop, cxzi, Walco, WolfY    |
|            3 |     3992 | 2024-02-20 | Mythic        | W   | 0.102      | -            | -                | -                | -         |     1.03 | ben1337, chop, cxzi, Walco, WolfY    |
|            2 |     4015 | 2024-02-19 | NRG           | L   | 0.096      | -            | -                | -                | -         |    -1.84 | ben1337, chop, cxzi, Walco, WolfY    |
|            1 |     4018 | 2024-02-19 | Akimbo        | W   | 0.095      | -            | -                | -                | -         |     0.83 | ben1337, chop, cxzi, Walco, WolfY    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,437.31)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.879 | $2,000.00      | $1,758.43       |
| 2024-06-09 |      0.836 | $5,000.00      | $4,178.01       |
| 2024-06-09 |      0.835 | $7,000.00      | $5,847.27       |
| 2024-04-28 |      0.551 | $3,000.00      | $1,653.61       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
