### Roster Details<br />
Team Name: KOI<br />
Roster: adamS, dav1g, JUST, mopoz, stadodo<br />
Global Rank: [49](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [36]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1084.3<br />
<br />
Final Rank Value (1084.3) = Starting Rank Value (1080.6) + Head To Head Adjustments (3.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.447[<sup>1</sup>](#table2)
- Bounty Collected: 0.438[<sup>2</sup>](#table1)
- Opponent Network: 0.226[<sup>2</sup>](#table1)
- LAN Wins: 0.212[<sup>2</sup>](#table1)

The average of these factors is 0.331<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1080.6
- 400 + ( ( 0.331 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1080.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           45 |      205 | 2024-07-31 | Zero Tenacity   | L   | 1.000      | -            | -                | -                | -         |   -12.49 | adamS, dav1g, JUST, mopoz, stadodo |
|           44 |      367 | 2024-07-26 | EYEBALLERS      | W   | 1.000      | 0.500        | -                | 0.488 (0.244)    | 0 (0.000) |     5.86 | adamS, dav1g, JUST, mopoz, stadodo |
|           43 |      642 | 2024-07-18 | Monte           | L   | 1.000      | -            | -                | -                | -         |   -17.95 | adamS, dav1g, JUST, mopoz, stadodo |
|           42 |      776 | 2024-07-16 | Insilio         | W   | 1.000      | 0.500        | 0.023 (0.011)    | 0.539 (0.270)    | 0 (0.000) |    10.27 | adamS, dav1g, JUST, mopoz, stadodo |
|           41 |     1042 | 2024-06-16 | 9z              | L   | 0.860      | -            | -                | -                | -         |    -3.22 | adamS, dav1g, JUST, mopoz, stadodo |
|           40 |     1092 | 2024-06-14 | RED Canids      | W   | 0.850      | 0.548        | 0.076 (0.036)    | 0.732 (0.341)    | 1 (0.850) |    16.11 | adamS, dav1g, JUST, mopoz, stadodo |
|           39 |     1097 | 2024-06-14 | Imperial        | W   | 0.849      | 0.548        | 0.233 (0.108)    | 0.658 (0.306)    | 1 (0.849) |    20.34 | adamS, dav1g, JUST, mopoz, stadodo |
|           38 |     1263 | 2024-06-09 | Sangal          | L   | 0.814      | -            | -                | -                | -         |    -8.17 | adamS, dav1g, JUST, mopoz, stadodo |
|           37 |     1451 | 2024-06-06 | SINNERS         | W   | 0.794      | 0.500        | 0.037 (0.015)    | 0.790 (0.314)    | 0 (0.000) |    11.11 | adamS, dav1g, JUST, mopoz, stadodo |
|           36 |     1512 | 2024-06-05 | 3DMAX           | W   | 0.787      | 0.500        | 0.510 (0.201)    | 1.000 (0.394)    | 0 (0.000) |    23.30 | adamS, dav1g, JUST, mopoz, stadodo |
|           35 |     1641 | 2024-06-01 | ENCE            | L   | 0.760      | -            | -                | -                | -         |    -3.21 | adamS, dav1g, JUST, mopoz, stadodo |
|           34 |     1647 | 2024-06-01 | Zero Tenacity   | L   | 0.760      | -            | -                | -                | -         |    -9.61 | adamS, dav1g, JUST, mopoz, stadodo |
|           33 |     2317 | 2024-05-09 | B8              | L   | 0.605      | -            | -                | -                | -         |    -9.57 | adamS, dav1g, JUST, mopoz, stadodo |
|           32 |     2480 | 2024-05-01 | Zero Tenacity   | L   | 0.552      | -            | -                | -                | -         |    -8.73 | adamS, dav1g, JUST, mopoz, stadodo |
|           31 |     2796 | 2024-04-18 | ex-Guild Eagles | L   | 0.467      | -            | -                | -                | -         |   -11.79 | adamS, dav1g, JUST, mopoz, stadodo |
|           30 |     2807 | 2024-04-18 | fnatic          | W   | 0.467      | 0.143        | 0.371 (0.025)    | -                | 0 (0.000) |    13.67 | adamS, dav1g, JUST, mopoz, stadodo |
|           29 |     2881 | 2024-04-16 | BLEED           | L   | 0.454      | -            | -                | -                | -         |    -8.68 | adamS, dav1g, JUST, mopoz, stadodo |
|           28 |     3012 | 2024-04-10 | RUSH B          | W   | 0.414      | 0.500        | -                | 0.371 (0.077)    | -         |     3.21 | adamS, dav1g, JUST, mopoz, stadodo |
|           27 |     3067 | 2024-04-09 | Aurora          | W   | 0.408      | 0.500        | 0.420 (0.086)    | 0.758 (0.155)    | -         |    12.41 | adamS, dav1g, JUST, mopoz, stadodo |
|           26 |     3073 | 2024-04-09 | Apeks           | L   | 0.407      | -            | -                | -                | -         |    -9.18 | adamS, dav1g, JUST, mopoz, stadodo |
|           25 |     3100 | 2024-04-08 | GUN5            | W   | 0.400      | -            | -                | -                | -         |     0.29 | adamS, dav1g, JUST, mopoz, stadodo |
|           24 |     3101 | 2024-04-08 | fnatic          | L   | 0.400      | -            | -                | -                | -         |    -0.83 | adamS, dav1g, JUST, mopoz, stadodo |
|           23 |     3204 | 2024-04-04 | NOM             | W   | 0.374      | -            | -                | -                | -         |     0.47 | adamS, dav1g, JUST, mopoz, stadodo |
|           22 |     3238 | 2024-04-03 | 9INE            | W   | 0.368      | -            | -                | -                | -         |     0.52 | adamS, dav1g, JUST, mopoz, stadodo |
|           21 |     3276 | 2024-04-02 | TSM             | W   | 0.361      | -            | -                | -                | -         |     1.14 | adamS, dav1g, JUST, mopoz, stadodo |
|           20 |     3343 | 2024-03-28 | EYEBALLERS      | L   | 0.327      | -            | -                | -                | -         |    -7.51 | adamS, dav1g, JUST, mopoz, stadodo |
|           19 |     3515 | 2024-03-18 | FURIA           | L   | 0.261      | -            | -                | -                | -         |    -0.23 | adamS, dav1g, JUST, mopoz, stadodo |
|           18 |     3530 | 2024-03-17 | ENCE            | L   | 0.255      | -            | -                | -                | -         |    -0.82 | adamS, dav1g, JUST, mopoz, stadodo |
|           17 |     3546 | 2024-03-17 | SAW             | L   | 0.254      | -            | -                | -                | -         |    -2.99 | adamS, dav1g, JUST, mopoz, stadodo |
|           16 |     3638 | 2024-03-13 | Sangal          | W   | 0.228      | 0.500        | 0.219 (0.025)    | 0.846 (0.096)    | -         |     4.31 | adamS, dav1g, JUST, mopoz, stadodo |
|           15 |     3692 | 2024-03-11 | B8              | L   | 0.215      | -            | -                | -                | -         |    -3.32 | adamS, dav1g, JUST, mopoz, stadodo |
|           14 |     3701 | 2024-03-11 | Apeks           | L   | 0.213      | -            | -                | -                | -         |    -4.94 | adamS, dav1g, JUST, mopoz, stadodo |
|           13 |     3813 | 2024-03-06 | 9 Pandas        | W   | 0.181      | 0.500        | 0.081 (0.007)    | 0.700 (0.063)    | -         |     2.18 | adamS, dav1g, JUST, mopoz, stadodo |
|           12 |     3849 | 2024-03-05 | FORZE           | W   | 0.175      | -            | -                | -                | -         |     1.51 | adamS, dav1g, JUST, mopoz, stadodo |
|           11 |     3855 | 2024-03-05 | Nemiga          | W   | 0.174      | 0.143        | 0.314 (0.008)    | -                | -         |     3.44 | adamS, dav1g, JUST, mopoz, stadodo |
|           10 |     3863 | 2024-03-05 | ex-Sprout       | W   | 0.174      | -            | -                | -                | -         |     0.21 | adamS, dav1g, JUST, mopoz, stadodo |
|            9 |     3903 | 2024-03-03 | The Chosen Few  | L   | 0.161      | -            | -                | -                | -         |    -4.61 | adamS, dav1g, JUST, mopoz, stadodo |
|            8 |     3958 | 2024-02-29 | Aurora          | L   | 0.141      | -            | -                | -                | -         |    -0.15 | adamS, dav1g, JUST, mopoz, stadodo |
|            7 |     3962 | 2024-02-29 | HAVU            | W   | 0.140      | -            | -                | -                | -         |     0.47 | adamS, dav1g, JUST, mopoz, stadodo |
|            6 |     3971 | 2024-02-28 | FORZE           | L   | 0.134      | -            | -                | -                | -         |    -3.16 | adamS, dav1g, JUST, mopoz, stadodo |
|            5 |     3975 | 2024-02-28 | kONO            | W   | 0.133      | -            | -                | -                | -         |     0.76 | adamS, dav1g, JUST, mopoz, stadodo |
|            4 |     4266 | 2024-02-16 | fnatic          | W   | 0.052      | -            | -                | -                | 1 (0.052) |     1.54 | adamS, dav1g, JUST, mopoz, stadodo |
|            3 |     4290 | 2024-02-15 | 9 Pandas        | W   | 0.046      | -            | -                | -                | 1 (0.046) |     0.55 | adamS, dav1g, JUST, mopoz, stadodo |
|            2 |     4319 | 2024-02-14 | 3DMAX           | W   | 0.041      | -            | -                | -                | 1 (0.041) |     1.25 | adamS, dav1g, JUST, mopoz, stadodo |
|            1 |     4333 | 2024-02-14 | Natus Vincere   | L   | 0.039      | -            | -                | -                | -         |    -0.01 | adamS, dav1g, JUST, mopoz, stadodo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,545.00)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.863 | $7,000.00      | $6,038.15       |
| 2024-06-09 |      0.814 | $12,000.00     | $9,764.72       |
| 2024-03-20 |      0.274 | $10,000.00     | $2,742.13       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
