### Roster Details<br />
Team Name: Party Astronauts<br />
Roster: ben1337, cxzi, FaNg, Infinite, WolfY<br />
Global Rank: [59](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [17]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1004.2<br />
<br />
Final Rank Value (1004.2) = Starting Rank Value (935.9) + Head To Head Adjustments (68.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.420[<sup>1</sup>](#table2)
- Bounty Collected: 0.366[<sup>2</sup>](#table1)
- Opponent Network: 0.190[<sup>2</sup>](#table1)
- LAN Wins: 0.064[<sup>2</sup>](#table1)

The average of these factors is 0.260<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 935.9
- 400 + ( ( 0.260 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 935.9


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
|           72 |       61 | 2024-07-30 | NRG           | W   | 1.000      | 0.477        | 0.020 (0.010)    | 0.519 (0.248)    | 0 (0.000) |    15.51 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           71 |       65 | 2024-07-30 | NRG           | W   | 1.000      | 0.477        | 0.020 (0.010)    | 0.519 (0.248)    | 0 (0.000) |    16.94 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           70 |      293 | 2024-07-23 | FLUFFY AIMERS | W   | 1.000      | 0.477        | -                | 0.305 (0.145)    | 0 (0.000) |     5.96 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           69 |      295 | 2024-07-23 | FLUFFY AIMERS | L   | 1.000      | -            | -                | -                | -         |   -26.10 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           68 |      383 | 2024-07-20 | Wildcard      | L   | 1.000      | -            | -                | -                | -         |   -15.68 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           67 |      526 | 2024-07-17 | Take Flyte    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.15 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           66 |      530 | 2024-07-17 | Take Flyte    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.41 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           65 |      592 | 2024-07-16 | Limitless     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.01 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           64 |      598 | 2024-07-16 | Limitless     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.35 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           63 |      937 | 2024-06-15 | Falcons       | L   | 0.886      | -            | -                | -                | -         |    -2.23 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           62 |      975 | 2024-06-14 | The MongolZ   | L   | 0.879      | -            | -                | -                | -         |    -0.17 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           61 |     1088 | 2024-06-09 | Legacy        | L   | 0.850      | -            | -                | -                | -         |   -11.32 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           60 |     1158 | 2024-06-08 | Wildcard      | W   | 0.843      | 0.384        | 0.055 (0.018)    | 0.501 (0.162)    | 0 (0.000) |    12.75 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           59 |     1176 | 2024-06-08 | NRG           | L   | 0.841      | -            | -                | -                | -         |   -16.06 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           58 |     1211 | 2024-06-07 | Nouns         | L   | 0.837      | -            | -                | -                | -         |   -13.76 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           57 |     1222 | 2024-06-07 | Legacy        | W   | 0.836      | 0.143        | 0.119 (0.014)    | -                | 0 (0.000) |    14.20 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           56 |     1229 | 2024-06-07 | NRG           | W   | 0.835      | 0.384        | -                | 0.519 (0.167)    | -         |    10.33 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           55 |     1242 | 2024-06-07 | Nouns         | W   | 0.835      | -            | -                | -                | -         |    13.62 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           54 |     1274 | 2024-06-06 | NRG           | W   | 0.830      | 0.477        | 0.020 (0.008)    | 0.519 (0.206)    | -         |    11.54 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           53 |     1294 | 2024-06-06 | E-Xolos LAZER | W   | 0.828      | -            | -                | -                | -         |     6.80 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           52 |     1346 | 2024-06-05 | Wildcard      | L   | 0.824      | -            | -                | -                | -         |   -12.46 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           51 |     1399 | 2024-06-04 | Elevate       | W   | 0.817      | 0.477        | 0.027 (0.011)    | 0.505 (0.197)    | -         |    14.25 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           50 |     1711 | 2024-05-22 | Nouns         | L   | 0.731      | -            | -                | -                | -         |   -11.48 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           49 |     1720 | 2024-05-22 | M80           | W   | 0.730      | 0.477        | 0.190 (0.066)    | 0.641 (0.223)    | -         |    19.58 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           48 |     1724 | 2024-05-22 | M80           | L   | 0.730      | -            | -                | -                | -         |    -3.26 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           47 |     1768 | 2024-05-21 | Limitless     | W   | 0.724      | -            | -                | -                | -         |     3.21 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           46 |     1771 | 2024-05-21 | Limitless     | W   | 0.724      | -            | -                | -                | -         |     3.31 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           45 |     1810 | 2024-05-20 | Akimbo        | W   | 0.717      | -            | -                | -                | -         |     6.24 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           44 |     1888 | 2024-05-18 | NRG           | L   | 0.702      | -            | -                | -                | -         |   -11.09 | ben1337, chop, cxzi, Infinite, WolfY |
|           43 |     1922 | 2024-05-17 | Legacy        | W   | 0.696      | 0.303        | 0.119 (0.025)    | -                | -         |    13.62 | ben1337, chop, cxzi, Infinite, WolfY |
|           42 |     1950 | 2024-05-16 | FLUFFY AIMERS | W   | 0.691      | -            | -                | -                | -         |     5.44 | ben1337, chop, cxzi, Infinite, WolfY |
|           41 |     1953 | 2024-05-16 | FLUFFY AIMERS | W   | 0.690      | -            | -                | -                | -         |     5.70 | ben1337, chop, cxzi, Infinite, WolfY |
|           40 |     2049 | 2024-05-14 | Mythic        | W   | 0.677      | -            | -                | -                | -         |     7.17 | ben1337, chop, cxzi, RUSH, WolfY     |
|           39 |     2056 | 2024-05-14 | Mythic        | L   | 0.677      | -            | -                | -                | -         |   -14.53 | ben1337, chop, cxzi, RUSH, WolfY     |
|           38 |     2152 | 2024-05-11 | BOSS          | L   | 0.656      | -            | -                | -                | -         |   -13.97 | ben1337, chop, cxzi, RUSH, WolfY     |
|           37 |     2156 | 2024-05-11 | Perseverance  | L   | 0.655      | -            | -                | -                | -         |   -16.05 | ben1337, chop, cxzi, RUSH, WolfY     |
|           36 |     2215 | 2024-05-08 | LAG           | W   | 0.637      | -            | -                | -                | -         |     7.23 | ben1337, chop, cxzi, RUSH, WolfY     |
|           35 |     2220 | 2024-05-08 | LAG           | W   | 0.637      | -            | -                | -                | -         |     7.62 | ben1337, chop, cxzi, RUSH, WolfY     |
|           34 |     2242 | 2024-05-07 | Elevate       | L   | 0.631      | -            | -                | -                | -         |    -9.23 | ben1337, chop, cxzi, RUSH, WolfY     |
|           33 |     2243 | 2024-05-07 | Elevate       | W   | 0.631      | 0.477        | 0.027 (0.008)    | 0.505 (0.152)    | -         |    10.89 | ben1337, chop, cxzi, RUSH, WolfY     |
|           32 |     2261 | 2024-05-06 | NRG           | L   | 0.624      | -            | -                | -                | -         |   -12.25 | ben1337, chop, cxzi, RUSH, WolfY     |
|           31 |     2262 | 2024-05-06 | NRG           | W   | 0.624      | 0.477        | -                | 0.519 (0.154)    | -         |     7.47 | ben1337, chop, cxzi, RUSH, WolfY     |
|           30 |     2333 | 2024-05-02 | Wildcard      | L   | 0.597      | -            | -                | -                | -         |   -10.43 | ben1337, chop, cxzi, RUSH, WolfY     |
|           29 |     2334 | 2024-05-02 | Wildcard      | W   | 0.597      | 0.477        | 0.055 (0.016)    | -                | -         |     8.52 | ben1337, chop, cxzi, RUSH, WolfY     |
|           28 |     2474 | 2024-04-27 | Aurora        | L   | 0.559      | -            | -                | -                | -         |    -0.42 | ben1337, chop, cxzi, RUSH, WolfY     |
|           27 |     2476 | 2024-04-26 | sunday school | W   | 0.557      | -            | -                | -                | 1 (0.557) |     2.56 | ben1337, chop, cxzi, RUSH, WolfY     |
|           26 |     2502 | 2024-04-25 | Aurora        | L   | 0.550      | -            | -                | -                | -         |    -0.38 | ben1337, chop, cxzi, RUSH, WolfY     |
|           25 |     2953 | 2024-04-09 | Take Flyte    | W   | 0.444      | -            | -                | -                | -         |     2.80 | ben1337, chop, cxzi, RUSH, WolfY     |
|           24 |     2959 | 2024-04-09 | Take Flyte    | W   | 0.444      | -            | -                | -                | -         |     2.87 | ben1337, chop, cxzi, RUSH, WolfY     |
|           23 |     3083 | 2024-04-04 | MIGHT         | W   | 0.411      | -            | -                | -                | -         |     1.19 | ben1337, chop, cxzi, RUSH, WolfY     |
|           22 |     3090 | 2024-04-04 | MIGHT         | W   | 0.410      | -            | -                | -                | -         |     1.21 | ben1337, chop, cxzi, RUSH, WolfY     |
|           21 |     3188 | 2024-04-02 | Perseverance  | W   | 0.397      | -            | -                | -                | -         |     2.96 | ben1337, chop, CLASIA, cxzi, WolfY   |
|           20 |     3191 | 2024-04-02 | Nouns         | L   | 0.396      | -            | -                | -                | -         |    -6.55 | ben1337, chop, CLASIA, cxzi, WolfY   |
|           19 |     3269 | 2024-03-27 | Carpe Diem    | W   | 0.357      | -            | -                | -                | -         |     2.11 | ben1337, chop, cxzi, RUSH, WolfY     |
|           18 |     3272 | 2024-03-27 | Carpe Diem    | W   | 0.357      | -            | -                | -                | -         |     2.15 | ben1337, chop, cxzi, RUSH, WolfY     |
|           17 |     3315 | 2024-03-26 | Nouns         | L   | 0.351      | -            | -                | -                | -         |    -5.89 | ben1337, chop, cxzi, RUSH, WolfY     |
|           16 |     3320 | 2024-03-26 | Nouns         | L   | 0.351      | -            | -                | -                | -         |    -6.07 | ben1337, chop, cxzi, RUSH, WolfY     |
|           15 |     3402 | 2024-03-20 | BOSS          | W   | 0.311      | -            | -                | -                | -         |     3.18 | ben1337, chop, cxzi, RUSH, WolfY     |
|           14 |     3404 | 2024-03-20 | BOSS          | W   | 0.311      | -            | -                | -                | -         |     3.26 | ben1337, chop, cxzi, RUSH, WolfY     |
|           13 |     3423 | 2024-03-19 | Perseverance  | W   | 0.304      | -            | -                | -                | -         |     2.27 | ben1337, chop, cxzi, RUSH, WolfY     |
|           12 |     3425 | 2024-03-19 | Perseverance  | W   | 0.304      | -            | -                | -                | -         |     2.31 | ben1337, chop, cxzi, RUSH, WolfY     |
|           11 |     3557 | 2024-03-13 | Carpe Diem    | W   | 0.263      | -            | -                | -                | -         |     1.62 | ben1337, chop, cxzi, RUSH, WolfY     |
|           10 |     3598 | 2024-03-12 | Elevate       | W   | 0.257      | -            | -                | -                | -         |     4.81 | ben1337, chop, cxzi, RUSH, WolfY     |
|            9 |     3989 | 2024-02-24 | Wildcard      | L   | 0.143      | -            | -                | -                | -         |    -2.40 | ben1337, chop, cxzi, Walco, WolfY    |
|            8 |     3995 | 2024-02-24 | ex-CatEvil    | W   | 0.143      | -            | -                | -                | -         |     0.21 | ben1337, chop, cxzi, Walco, WolfY    |
|            7 |     4035 | 2024-02-22 | Liquid        | L   | 0.130      | -            | -                | -                | -         |    -0.22 | ben1337, chop, cxzi, Walco, WolfY    |
|            6 |     4036 | 2024-02-22 | NRG           | W   | 0.130      | -            | -                | -                | -         |     1.60 | ben1337, chop, cxzi, Walco, WolfY    |
|            5 |     4042 | 2024-02-22 | Take Flyte    | W   | 0.130      | -            | -                | -                | -         |     0.92 | ben1337, chop, cxzi, Walco, WolfY    |
|            4 |     4091 | 2024-02-20 | NRG           | W   | 0.117      | -            | -                | -                | -         |     1.45 | ben1337, chop, cxzi, Walco, WolfY    |
|            3 |     4093 | 2024-02-20 | Mythic        | W   | 0.116      | -            | -                | -                | -         |     1.18 | ben1337, chop, cxzi, Walco, WolfY    |
|            2 |     4116 | 2024-02-19 | NRG           | L   | 0.111      | -            | -                | -                | -         |    -2.13 | ben1337, chop, cxzi, Walco, WolfY    |
|            1 |     4119 | 2024-02-19 | Akimbo        | W   | 0.110      | -            | -                | -                | -         |     0.96 | ben1337, chop, cxzi, Walco, WolfY    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,686.81)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.894 | $2,000.00      | $1,787.78       |
| 2024-06-09 |      0.850 | $5,000.00      | $4,251.39       |
| 2024-06-09 |      0.850 | $7,000.00      | $5,950.00       |
| 2024-04-28 |      0.566 | $3,000.00      | $1,697.64       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
