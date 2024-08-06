### Roster Details<br />
Team Name: Rebels<br />
Roster: casey, Flayy, innocent, kisserek, olimp<br />
Global Rank: [62](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [45]( ../standings_europe.md)<br />
<br />
Final Rank Value:  997.1<br />
<br />
Final Rank Value (997.1) = Starting Rank Value (991.1) + Head To Head Adjustments (6.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.413[<sup>1</sup>](#table2)
- Bounty Collected: 0.391[<sup>2</sup>](#table1)
- Opponent Network: 0.225[<sup>2</sup>](#table1)
- LAN Wins: 0.120[<sup>2</sup>](#table1)

The average of these factors is 0.287<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 991.1
- 400 + ( ( 0.287 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 991.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           45 |       12 | 2024-08-05 | SINNERS           | L   | 1.000      | -            | -                | -                | -         |   -16.66 | casey, Flayy, innocent, kisserek, olimp |
|           44 |      236 | 2024-07-30 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |   -19.60 | casey, Flayy, innocent, kisserek, olimp |
|           43 |      434 | 2024-07-24 | SAW               | W   | 1.000      | 0.500        | 0.104 (0.052)    | 0.516 (0.258)    | 0 (0.000) |    22.48 | casey, Flayy, innocent, kisserek, olimp |
|           42 |      445 | 2024-07-24 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -18.25 | casey, Flayy, innocent, kisserek, olimp |
|           41 |      488 | 2024-07-23 | Enterprise        | W   | 1.000      | 0.371        | 0.039 (0.015)    | 0.641 (0.237)    | 0 (0.000) |    11.88 | casey, Flayy, innocent, kisserek, olimp |
|           40 |      505 | 2024-07-22 | Insilio           | W   | 1.000      | 0.371        | -                | 0.539 (0.200)    | 0 (0.000) |    13.86 | casey, Flayy, innocent, kisserek, olimp |
|           39 |      606 | 2024-07-19 | B8                | L   | 1.000      | -            | -                | -                | -         |    -9.14 | casey, Flayy, innocent, kisserek, olimp |
|           38 |      671 | 2024-07-18 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.91 | casey, Flayy, innocent, kisserek, olimp |
|           37 |      732 | 2024-07-17 | 9INE              | W   | 1.000      | 0.500        | 0.022 (0.011)    | 0.523 (0.261)    | 0 (0.000) |    12.00 | casey, Flayy, innocent, kisserek, olimp |
|           36 |      820 | 2024-07-15 | brazylijski luz   | L   | 1.000      | -            | -                | -                | -         |   -22.96 | casey, Flayy, innocent, kisserek, olimp |
|           35 |      827 | 2024-07-15 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -7.88 | casey, Flayy, innocent, kisserek, olimp |
|           34 |      867 | 2024-07-12 | Enterprise        | W   | 1.000      | 0.371        | 0.039 (0.015)    | 0.641 (0.237)    | 0 (0.000) |    12.99 | casey, Flayy, innocent, kisserek, olimp |
|           33 |      904 | 2024-07-10 | Belarus           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.08 | casey, Flayy, innocent, kisserek, olimp |
|           32 |      916 | 2024-07-09 | 500               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.06 | casey, Flayy, innocent, kisserek, olimp |
|           31 |      952 | 2024-07-08 | Verdant           | W   | 1.000      | -            | -                | -                | -         |     9.83 | casey, Flayy, innocent, kisserek, olimp |
|           30 |     1141 | 2024-06-13 | Sampi             | L   | 0.841      | -            | -                | -                | -         |   -17.74 | casey, Flayy, innocent, kisserek, olimp |
|           29 |     1164 | 2024-06-12 | PERA              | L   | 0.835      | -            | -                | -                | -         |   -14.98 | casey, Flayy, innocent, kisserek, olimp |
|           28 |     1208 | 2024-06-10 | Permitta          | W   | 0.822      | 0.379        | -                | 0.919 (0.286)    | -         |    10.29 | casey, Flayy, innocent, kisserek, olimp |
|           27 |     1246 | 2024-06-09 | Rhyno             | L   | 0.815      | -            | -                | -                | -         |   -14.24 | casey, Flayy, kisserek, olimp, SZPERO   |
|           26 |     1371 | 2024-06-07 | BLEED             | W   | 0.802      | 0.500        | 0.126 (0.050)    | 0.538 (0.216)    | -         |    22.28 | casey, Flayy, innocent, kisserek, olimp |
|           25 |     1496 | 2024-06-05 | 9INE              | W   | 0.789      | 0.500        | -                | 0.523 (0.206)    | -         |     9.21 | casey, Flayy, innocent, kisserek, olimp |
|           24 |     1686 | 2024-05-30 | PERA              | W   | 0.749      | 0.379        | 0.048 (0.013)    | -                | -         |    10.38 | casey, Flayy, innocent, kisserek, olimp |
|           23 |     1723 | 2024-05-29 | UNiTY             | L   | 0.740      | -            | -                | -                | -         |   -13.83 | casey, Flayy, innocent, kisserek, olimp |
|           22 |     1810 | 2024-05-25 | kONO              | W   | 0.713      | -            | -                | -                | -         |     6.70 | casey, Flayy, innocent, kisserek, olimp |
|           21 |     1924 | 2024-05-21 | UNiTY             | L   | 0.686      | -            | -                | -                | -         |   -12.17 | casey, Flayy, innocent, kisserek, olimp |
|           20 |     1947 | 2024-05-20 | The Prodigies     | W   | 0.682      | -            | -                | -                | -         |     1.43 | casey, Flayy, innocent, kisserek, olimp |
|           19 |     2015 | 2024-05-18 | B8                | L   | 0.666      | -            | -                | -                | -         |    -7.04 | casey, Flayy, innocent, kisserek, olimp |
|           18 |     2043 | 2024-05-17 | Gaimin Gladiators | W   | 0.660      | -            | -                | -                | -         |    10.39 | casey, Flayy, innocent, kisserek, olimp |
|           17 |     2538 | 2024-04-27 | Aurora            | L   | 0.532      | -            | -                | -                | -         |    -0.52 | casey, Flayy, innocent, kisserek, olimp |
|           16 |     2588 | 2024-04-26 | MIBR              | W   | 0.519      | 0.500        | 0.208 (0.054)    | 0.633 (0.164)    | 1 (0.519) |    15.13 | casey, Flayy, innocent, kisserek, olimp |
|           15 |     2590 | 2024-04-25 | Rooster           | W   | 0.518      | -            | -                | -                | 1 (0.518) |     4.16 | casey, Flayy, innocent, kisserek, olimp |
|           14 |     2738 | 2024-04-19 | brazylijski luz   | L   | 0.475      | -            | -                | -                | -         |   -10.87 | casey, Flayy, innocent, kisserek, olimp |
|           13 |     2923 | 2024-04-13 | Monte             | L   | 0.434      | -            | -                | -                | -         |    -7.00 | casey, Flayy, innocent, kisserek, olimp |
|           12 |     3057 | 2024-04-09 | B8                | W   | 0.409      | 0.500        | 0.170 (0.035)    | 0.912 (0.186)    | -         |     7.68 | casey, Flayy, innocent, kisserek, olimp |
|           11 |     3199 | 2024-04-04 | ALTERNATE aTTaX   | W   | 0.374      | -            | -                | -                | -         |     5.54 | casey, Flayy, innocent, kisserek, olimp |
|           10 |     3249 | 2024-04-03 | SINNERS           | L   | 0.366      | -            | -                | -                | -         |    -3.42 | casey, Flayy, innocent, kisserek, olimp |
|            9 |     3330 | 2024-03-28 | ex-Sprout         | W   | 0.328      | -            | -                | -                | -         |     0.62 | casey, Flayy, innocent, kisserek, olimp |
|            8 |     3364 | 2024-03-27 | B8                | L   | 0.322      | -            | -                | -                | -         |    -3.70 | casey, Flayy, innocent, kisserek, olimp |
|            7 |     3373 | 2024-03-27 | Sashi             | W   | 0.322      | -            | -                | -                | -         |     7.09 | casey, Flayy, innocent, kisserek, olimp |
|            6 |     3403 | 2024-03-25 | Aurora            | L   | 0.308      | -            | -                | -                | -         |    -0.21 | casey, Flayy, innocent, kisserek, olimp |
|            5 |     3602 | 2024-03-14 | brazylijski luz   | L   | 0.236      | -            | -                | -                | -         |    -5.57 | casey, Flayy, kisserek, olimp, SZPERO   |
|            4 |     3870 | 2024-03-04 | BLEED             | L   | 0.169      | -            | -                | -                | -         |    -2.93 | casey, Flayy, kisserek, olimp, sNx      |
|            3 |     3904 | 2024-03-03 | Sangal            | W   | 0.161      | 0.500        | 0.219 (0.018)    | -                | -         |     3.62 | casey, Flayy, kisserek, olimp, sNx      |
|            2 |     3919 | 2024-03-02 | Aurora            | L   | 0.155      | -            | -                | -                | -         |    -0.10 | casey, Flayy, kisserek, olimp, sNx      |
|            1 |     3952 | 2024-02-29 | Sangal            | W   | 0.141      | 0.500        | 0.219 (0.015)    | -                | -         |     3.20 | casey, Flayy, kisserek, olimp, sNx      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,211.29)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-13 |      0.842 | $1,089.00      | $917.08         |
| 2024-06-09 |      0.815 | $2,000.00      | $1,629.31       |
| 2024-05-18 |      0.668 | $2,000.00      | $1,336.67       |
| 2024-04-28 |      0.533 | $10,000.00     | $5,328.24       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
