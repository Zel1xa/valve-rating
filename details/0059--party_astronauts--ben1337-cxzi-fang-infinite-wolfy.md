### Roster Details<br />
Team Name: Party Astronauts<br />
Roster: ben1337, cxzi, FaNg, Infinite, WolfY<br />
Global Rank: [59](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [17]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1003.4<br />
<br />
Final Rank Value (1003.4) = Starting Rank Value (935.1) + Head To Head Adjustments (68.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.420[<sup>1</sup>](#table2)
- Bounty Collected: 0.366[<sup>2</sup>](#table1)
- Opponent Network: 0.190[<sup>2</sup>](#table1)
- LAN Wins: 0.064[<sup>2</sup>](#table1)

The average of these factors is 0.260<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 935.1
- 400 + ( ( 0.260 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 935.1


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
|           72 |       68 | 2024-07-30 | NRG           | W   | 1.000      | 0.477        | 0.020 (0.010)    | 0.519 (0.248)    | 0 (0.000) |    15.51 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           71 |       72 | 2024-07-30 | NRG           | W   | 1.000      | 0.477        | 0.020 (0.010)    | 0.519 (0.248)    | 0 (0.000) |    16.94 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           70 |      299 | 2024-07-23 | FLUFFY AIMERS | W   | 1.000      | 0.477        | -                | 0.305 (0.145)    | 0 (0.000) |     5.96 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           69 |      301 | 2024-07-23 | FLUFFY AIMERS | L   | 1.000      | -            | -                | -                | -         |   -26.09 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           68 |      389 | 2024-07-20 | Wildcard      | L   | 1.000      | -            | -                | -                | -         |   -15.68 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           67 |      532 | 2024-07-17 | Take Flyte    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.15 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           66 |      536 | 2024-07-17 | Take Flyte    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.41 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           65 |      598 | 2024-07-16 | Limitless     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.01 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           64 |      604 | 2024-07-16 | Limitless     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.36 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           63 |      943 | 2024-06-15 | Falcons       | L   | 0.884      | -            | -                | -                | -         |    -2.22 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           62 |      981 | 2024-06-14 | The MongolZ   | L   | 0.877      | -            | -                | -                | -         |    -0.17 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           61 |     1094 | 2024-06-09 | Legacy        | L   | 0.849      | -            | -                | -                | -         |   -11.30 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           60 |     1164 | 2024-06-08 | Wildcard      | W   | 0.841      | 0.384        | 0.055 (0.018)    | 0.501 (0.162)    | 0 (0.000) |    12.73 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           59 |     1182 | 2024-06-08 | NRG           | L   | 0.840      | -            | -                | -                | -         |   -16.03 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           58 |     1217 | 2024-06-07 | Nouns         | L   | 0.835      | -            | -                | -                | -         |   -13.73 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           57 |     1228 | 2024-06-07 | Legacy        | W   | 0.834      | 0.143        | 0.119 (0.014)    | -                | 0 (0.000) |    14.17 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           56 |     1235 | 2024-06-07 | NRG           | W   | 0.833      | 0.384        | -                | 0.519 (0.166)    | -         |    10.31 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           55 |     1248 | 2024-06-07 | Nouns         | W   | 0.833      | -            | -                | -                | -         |    13.60 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           54 |     1280 | 2024-06-06 | NRG           | W   | 0.829      | 0.477        | 0.020 (0.008)    | 0.519 (0.205)    | -         |    11.52 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           53 |     1300 | 2024-06-06 | E-Xolos LAZER | W   | 0.827      | -            | -                | -                | -         |     6.80 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           52 |     1352 | 2024-06-05 | Wildcard      | L   | 0.822      | -            | -                | -                | -         |   -12.44 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           51 |     1405 | 2024-06-04 | Elevate       | W   | 0.815      | 0.477        | 0.027 (0.011)    | 0.505 (0.196)    | -         |    14.22 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           50 |     1717 | 2024-05-22 | Nouns         | L   | 0.729      | -            | -                | -                | -         |   -11.46 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           49 |     1726 | 2024-05-22 | M80           | W   | 0.728      | 0.477        | 0.190 (0.066)    | 0.641 (0.223)    | -         |    19.55 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           48 |     1730 | 2024-05-22 | M80           | L   | 0.728      | -            | -                | -                | -         |    -3.24 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           47 |     1774 | 2024-05-21 | Limitless     | W   | 0.722      | -            | -                | -                | -         |     3.20 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           46 |     1777 | 2024-05-21 | Limitless     | W   | 0.722      | -            | -                | -                | -         |     3.31 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           45 |     1816 | 2024-05-20 | Akimbo        | W   | 0.716      | -            | -                | -                | -         |     6.23 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           44 |     1894 | 2024-05-18 | NRG           | L   | 0.700      | -            | -                | -                | -         |   -11.06 | ben1337, chop, cxzi, Infinite, WolfY |
|           43 |     1928 | 2024-05-17 | Legacy        | W   | 0.694      | 0.303        | 0.119 (0.025)    | -                | -         |    13.58 | ben1337, chop, cxzi, Infinite, WolfY |
|           42 |     1956 | 2024-05-16 | FLUFFY AIMERS | W   | 0.689      | -            | -                | -                | -         |     5.43 | ben1337, chop, cxzi, Infinite, WolfY |
|           41 |     1959 | 2024-05-16 | FLUFFY AIMERS | W   | 0.689      | -            | -                | -                | -         |     5.69 | ben1337, chop, cxzi, Infinite, WolfY |
|           40 |     2055 | 2024-05-14 | Mythic        | W   | 0.676      | -            | -                | -                | -         |     7.16 | ben1337, chop, cxzi, RUSH, WolfY     |
|           39 |     2062 | 2024-05-14 | Mythic        | L   | 0.675      | -            | -                | -                | -         |   -14.49 | ben1337, chop, cxzi, RUSH, WolfY     |
|           38 |     2158 | 2024-05-11 | BOSS          | L   | 0.654      | -            | -                | -                | -         |   -13.93 | ben1337, chop, cxzi, RUSH, WolfY     |
|           37 |     2162 | 2024-05-11 | Perseverance  | L   | 0.654      | -            | -                | -                | -         |   -16.01 | ben1337, chop, cxzi, RUSH, WolfY     |
|           36 |     2221 | 2024-05-08 | LAG           | W   | 0.636      | -            | -                | -                | -         |     7.21 | ben1337, chop, cxzi, RUSH, WolfY     |
|           35 |     2226 | 2024-05-08 | LAG           | W   | 0.635      | -            | -                | -                | -         |     7.60 | ben1337, chop, cxzi, RUSH, WolfY     |
|           34 |     2248 | 2024-05-07 | Elevate       | L   | 0.629      | -            | -                | -                | -         |    -9.20 | ben1337, chop, cxzi, RUSH, WolfY     |
|           33 |     2249 | 2024-05-07 | Elevate       | W   | 0.629      | 0.477        | 0.027 (0.008)    | 0.505 (0.152)    | -         |    10.86 | ben1337, chop, cxzi, RUSH, WolfY     |
|           32 |     2267 | 2024-05-06 | NRG           | L   | 0.622      | -            | -                | -                | -         |   -12.21 | ben1337, chop, cxzi, RUSH, WolfY     |
|           31 |     2268 | 2024-05-06 | NRG           | W   | 0.622      | 0.477        | -                | 0.519 (0.154)    | -         |     7.46 | ben1337, chop, cxzi, RUSH, WolfY     |
|           30 |     2339 | 2024-05-02 | Wildcard      | L   | 0.595      | -            | -                | -                | -         |   -10.40 | ben1337, chop, cxzi, RUSH, WolfY     |
|           29 |     2340 | 2024-05-02 | Wildcard      | W   | 0.595      | 0.477        | 0.055 (0.016)    | -                | -         |     8.49 | ben1337, chop, cxzi, RUSH, WolfY     |
|           28 |     2480 | 2024-04-27 | Aurora        | L   | 0.557      | -            | -                | -                | -         |    -0.42 | ben1337, chop, cxzi, RUSH, WolfY     |
|           27 |     2482 | 2024-04-26 | sunday school | W   | 0.556      | -            | -                | -                | 1 (0.556) |     2.56 | ben1337, chop, cxzi, RUSH, WolfY     |
|           26 |     2508 | 2024-04-25 | Aurora        | L   | 0.549      | -            | -                | -                | -         |    -0.37 | ben1337, chop, cxzi, RUSH, WolfY     |
|           25 |     2959 | 2024-04-09 | Take Flyte    | W   | 0.442      | -            | -                | -                | -         |     2.79 | ben1337, chop, cxzi, RUSH, WolfY     |
|           24 |     2965 | 2024-04-09 | Take Flyte    | W   | 0.442      | -            | -                | -                | -         |     2.86 | ben1337, chop, cxzi, RUSH, WolfY     |
|           23 |     3089 | 2024-04-04 | MIGHT         | W   | 0.409      | -            | -                | -                | -         |     1.19 | ben1337, chop, cxzi, RUSH, WolfY     |
|           22 |     3096 | 2024-04-04 | MIGHT         | W   | 0.409      | -            | -                | -                | -         |     1.20 | ben1337, chop, cxzi, RUSH, WolfY     |
|           21 |     3194 | 2024-04-02 | Perseverance  | W   | 0.396      | -            | -                | -                | -         |     2.95 | ben1337, chop, CLASIA, cxzi, WolfY   |
|           20 |     3197 | 2024-04-02 | Nouns         | L   | 0.394      | -            | -                | -                | -         |    -6.52 | ben1337, chop, CLASIA, cxzi, WolfY   |
|           19 |     3275 | 2024-03-27 | Carpe Diem    | W   | 0.356      | -            | -                | -                | -         |     2.10 | ben1337, chop, cxzi, RUSH, WolfY     |
|           18 |     3278 | 2024-03-27 | Carpe Diem    | W   | 0.356      | -            | -                | -                | -         |     2.14 | ben1337, chop, cxzi, RUSH, WolfY     |
|           17 |     3321 | 2024-03-26 | Nouns         | L   | 0.349      | -            | -                | -                | -         |    -5.86 | ben1337, chop, cxzi, RUSH, WolfY     |
|           16 |     3326 | 2024-03-26 | Nouns         | L   | 0.349      | -            | -                | -                | -         |    -6.04 | ben1337, chop, cxzi, RUSH, WolfY     |
|           15 |     3408 | 2024-03-20 | BOSS          | W   | 0.309      | -            | -                | -                | -         |     3.17 | ben1337, chop, cxzi, RUSH, WolfY     |
|           14 |     3410 | 2024-03-20 | BOSS          | W   | 0.309      | -            | -                | -                | -         |     3.24 | ben1337, chop, cxzi, RUSH, WolfY     |
|           13 |     3429 | 2024-03-19 | Perseverance  | W   | 0.303      | -            | -                | -                | -         |     2.26 | ben1337, chop, cxzi, RUSH, WolfY     |
|           12 |     3431 | 2024-03-19 | Perseverance  | W   | 0.302      | -            | -                | -                | -         |     2.30 | ben1337, chop, cxzi, RUSH, WolfY     |
|           11 |     3563 | 2024-03-13 | Carpe Diem    | W   | 0.261      | -            | -                | -                | -         |     1.61 | ben1337, chop, cxzi, RUSH, WolfY     |
|           10 |     3604 | 2024-03-12 | Elevate       | W   | 0.255      | -            | -                | -                | -         |     4.78 | ben1337, chop, cxzi, RUSH, WolfY     |
|            9 |     3995 | 2024-02-24 | Wildcard      | L   | 0.142      | -            | -                | -                | -         |    -2.37 | ben1337, chop, cxzi, Walco, WolfY    |
|            8 |     4001 | 2024-02-24 | ex-CatEvil    | W   | 0.141      | -            | -                | -                | -         |     0.21 | ben1337, chop, cxzi, Walco, WolfY    |
|            7 |     4041 | 2024-02-22 | Liquid        | L   | 0.129      | -            | -                | -                | -         |    -0.15 | ben1337, chop, cxzi, Walco, WolfY    |
|            6 |     4042 | 2024-02-22 | NRG           | W   | 0.128      | -            | -                | -                | -         |     1.58 | ben1337, chop, cxzi, Walco, WolfY    |
|            5 |     4048 | 2024-02-22 | Take Flyte    | W   | 0.128      | -            | -                | -                | -         |     0.91 | ben1337, chop, cxzi, Walco, WolfY    |
|            4 |     4097 | 2024-02-20 | NRG           | W   | 0.116      | -            | -                | -                | -         |     1.43 | ben1337, chop, cxzi, Walco, WolfY    |
|            3 |     4099 | 2024-02-20 | Mythic        | W   | 0.115      | -            | -                | -                | -         |     1.17 | ben1337, chop, cxzi, Walco, WolfY    |
|            2 |     4122 | 2024-02-19 | NRG           | L   | 0.109      | -            | -                | -                | -         |    -2.10 | ben1337, chop, cxzi, Walco, WolfY    |
|            1 |     4125 | 2024-02-19 | Akimbo        | W   | 0.108      | -            | -                | -                | -         |     0.95 | ben1337, chop, cxzi, Walco, WolfY    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,658.47)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.892 | $2,000.00      | $1,784.44       |
| 2024-06-09 |      0.849 | $5,000.00      | $4,243.06       |
| 2024-06-09 |      0.848 | $7,000.00      | $5,938.33       |
| 2024-04-28 |      0.564 | $3,000.00      | $1,692.64       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
