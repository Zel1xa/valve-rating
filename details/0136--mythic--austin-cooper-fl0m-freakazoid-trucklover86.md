### Roster Details<br />
Team Name: Mythic<br />
Roster: Austin, Cooper, fl0m, freakazoid, Trucklover86<br />
Global Rank: [136](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [35]( ../standings_americas.md)<br />
<br />
Final Rank Value:  760.1<br />
<br />
Final Rank Value (760.1) = Starting Rank Value (790.9) + Head To Head Adjustments (-30.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.332[<sup>1</sup>](#table2)
- Bounty Collected: 0.320[<sup>2</sup>](#table1)
- Opponent Network: 0.112[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.191<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 790.9
- 400 + ( ( 0.191 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 790.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           54 |      144 | 2024-07-31 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | -                | 0.314 (0.150)    | 0 (0.000) |    14.67 | Austin, Cooper, fl0m, freakazoid, Trucklover86 |
|           53 |      146 | 2024-07-31 | FLUFFY AIMERS    | L   | 1.000      | -            | -                | -                | -         |   -16.93 | Austin, Cooper, fl0m, freakazoid, Trucklover86 |
|           52 |      643 | 2024-07-17 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -7.48 | Austin, Cooper, fl0m, freakazoid, Trucklover86 |
|           51 |      648 | 2024-07-17 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -7.99 | Austin, Cooper, fl0m, freakazoid, Trucklover86 |
|           50 |      704 | 2024-07-16 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -8.70 | Austin, Cooper, fl0m, freakazoid, Trucklover86 |
|           49 |      711 | 2024-07-16 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -9.35 | Austin, Cooper, fl0m, freakazoid, Trucklover86 |
|           48 |      756 | 2024-07-15 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -16.95 | Austin, Cooper, fl0m, freakazoid, Trucklover86 |
|           47 |     1020 | 2024-06-15 | Wildcard         | L   | 0.866      | -            | -                | -                | -         |    -8.66 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           46 |     1096 | 2024-06-13 | LAG              | W   | 0.853      | 0.371        | 0.012 (0.004)    | 0.353 (0.112)    | 0 (0.000) |    13.75 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           45 |     1382 | 2024-06-06 | Legacy           | L   | 0.807      | -            | -                | -                | -         |    -6.13 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           44 |     1449 | 2024-06-05 | Elevate          | L   | 0.800      | -            | -                | -                | -         |    -7.07 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           43 |     1502 | 2024-06-04 | BOSS             | W   | 0.793      | 0.477        | 0.014 (0.005)    | 0.332 (0.126)    | 0 (0.000) |    11.15 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           42 |     1511 | 2024-06-04 | Phoenix          | W   | 0.792      | 0.384        | -                | 0.283 (0.086)    | 0 (0.000) |    10.55 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           41 |     1829 | 2024-05-22 | M80              | L   | 0.705      | -            | -                | -                | -         |    -1.64 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           40 |     1903 | 2024-05-20 | Elevate          | W   | 0.693      | 0.384        | 0.027 (0.007)    | 0.521 (0.139)    | 0 (0.000) |    16.29 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           39 |     2063 | 2024-05-15 | Phoenix          | W   | 0.660      | 0.477        | -                | 0.283 (0.089)    | 0 (0.000) |     9.55 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           38 |     2069 | 2024-05-15 | Phoenix          | L   | 0.660      | -            | -                | -                | -         |   -11.51 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           37 |     2116 | 2024-05-14 | Party Astronauts | L   | 0.654      | -            | -                | -                | -         |    -6.99 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           36 |     2123 | 2024-05-14 | Party Astronauts | W   | 0.653      | 0.477        | 0.041 (0.013)    | 0.531 (0.165)    | 0 (0.000) |    13.96 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           35 |     2194 | 2024-05-12 | Phoenix          | L   | 0.638      | -            | -                | -                | -         |   -11.15 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           34 |     2211 | 2024-05-11 | Nouns            | W   | 0.633      | 0.270        | 0.057 (0.010)    | 0.561 (0.096)    | 0 (0.000) |    14.48 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           33 |     2212 | 2024-05-11 | Wildcard         | W   | 0.633      | 0.270        | 0.048 (0.008)    | -                | 0 (0.000) |    13.44 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           32 |     2584 | 2024-04-24 | BOSS             | W   | 0.520      | 0.477        | 0.014 (0.003)    | 0.332 (0.082)    | 0 (0.000) |     9.86 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           31 |     2585 | 2024-04-24 | BOSS             | L   | 0.520      | -            | -                | -                | -         |    -6.64 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           30 |     2857 | 2024-04-15 | NRG              | L   | 0.460      | -            | -                | -                | -         |    -5.21 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           29 |     2858 | 2024-04-15 | NRG              | L   | 0.460      | -            | -                | -                | -         |    -5.41 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           28 |     2913 | 2024-04-11 | Carpe Diem       | L   | 0.434      | -            | -                | -                | -         |    -9.04 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           27 |     2915 | 2024-04-11 | Carpe Diem       | W   | 0.433      | -            | -                | -                | -         |     4.68 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           26 |     2946 | 2024-04-10 | LAG              | L   | 0.427      | -            | -                | -                | -         |    -5.59 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           25 |     2951 | 2024-04-10 | LAG              | L   | 0.427      | -            | -                | -                | -         |    -5.80 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           24 |     3314 | 2024-03-27 | Wildcard         | L   | 0.333      | -            | -                | -                | -         |    -3.83 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           23 |     3320 | 2024-03-27 | Wildcard         | L   | 0.333      | -            | -                | -                | -         |    -3.94 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           22 |     3357 | 2024-03-26 | Limitless        | W   | 0.327      | -            | -                | -                | -         |     3.27 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           21 |     3362 | 2024-03-26 | Limitless        | L   | 0.327      | -            | -                | -                | -         |    -7.16 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           20 |     3438 | 2024-03-20 | Nouns            | W   | 0.287      | 0.477        | 0.057 (0.008)    | 0.561 (0.077)    | -         |     6.01 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           19 |     3441 | 2024-03-20 | Nouns            | L   | 0.287      | -            | -                | -                | -         |    -3.06 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           18 |     3459 | 2024-03-19 | M80              | W   | 0.281      | 0.477        | 0.064 (0.009)    | -                | -         |     2.51 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           17 |     3461 | 2024-03-19 | M80              | W   | 0.280      | 0.477        | 0.064 (0.009)    | -                | -         |     2.56 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           16 |     3551 | 2024-03-14 | Take Flyte       | W   | 0.247      | -            | -                | -                | -         |     3.01 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           15 |     3554 | 2024-03-14 | Take Flyte       | W   | 0.247      | -            | -                | -                | -         |     3.07 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           14 |     3587 | 2024-03-13 | Phoenix          | L   | 0.239      | -            | -                | -                | -         |    -4.31 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           13 |     3631 | 2024-03-12 | Wildcard         | W   | 0.233      | -            | -                | -                | -         |     4.62 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           12 |     3802 | 2024-03-05 | MIGHT            | L   | 0.187      | -            | -                | -                | -         |    -4.74 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           11 |     3804 | 2024-03-05 | MIGHT            | L   | 0.187      | -            | -                | -                | -         |    -4.78 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           10 |     4016 | 2024-02-24 | NRG              | L   | 0.119      | -            | -                | -                | -         |    -1.58 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            9 |     4107 | 2024-02-20 | Party Astronauts | L   | 0.093      | -            | -                | -                | -         |    -0.95 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            8 |     4131 | 2024-02-19 | Akimbo           | W   | 0.087      | -            | -                | -                | -         |     1.24 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            7 |     4132 | 2024-02-19 | NRG              | L   | 0.086      | -            | -                | -                | -         |    -1.15 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            6 |     4200 | 2024-02-16 | FLUFFY AIMERS    | W   | 0.066      | -            | -                | -                | -         |     0.94 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            5 |     4202 | 2024-02-16 | E-Xolos LAZER    | W   | 0.066      | -            | -                | -                | -         |     0.99 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            4 |     4258 | 2024-02-14 | FLUFFY AIMERS    | W   | 0.054      | -            | -                | -                | -         |     0.77 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            3 |     4260 | 2024-02-14 | FLUFFY AIMERS    | W   | 0.054      | -            | -                | -                | -         |     0.77 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            2 |     4298 | 2024-02-13 | Elevate          | W   | 0.047      | -            | -                | -                | -         |     1.14 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            1 |     4301 | 2024-02-13 | Elevate          | L   | 0.047      | -            | -                | -                | -         |    -0.34 | Cooper, fl0m, freakazoid, hate, Trucklover86   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,134.27)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.873 | $750.00        | $655.10         |
| 2024-06-09 |      0.826 | $3,000.00      | $2,479.17       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
