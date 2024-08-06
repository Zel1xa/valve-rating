### Roster Details<br />
Team Name: Mythic<br />
Roster: Austin, Cooper, fl0m, freakazoid, Trucklover86<br />
Global Rank: [138](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [36]( ../standings_americas.md)<br />
<br />
Final Rank Value:  758.8<br />
<br />
Final Rank Value (758.8) = Starting Rank Value (790.0) + Head To Head Adjustments (-31.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.332[<sup>1</sup>](#table2)
- Bounty Collected: 0.319[<sup>2</sup>](#table1)
- Opponent Network: 0.107[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.190<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 790.0
- 400 + ( ( 0.190 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 790.0


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
|           54 |      178 | 2024-07-31 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | -                | 0.304 (0.145)    | 0 (0.000) |    14.71 | Austin, Cooper, fl0m, freakazoid, Trucklover86 |
|           53 |      180 | 2024-07-31 | FLUFFY AIMERS    | L   | 1.000      | -            | -                | -                | -         |   -16.89 | Austin, Cooper, fl0m, freakazoid, Trucklover86 |
|           52 |      677 | 2024-07-17 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -7.50 | Austin, Cooper, fl0m, freakazoid, Trucklover86 |
|           51 |      682 | 2024-07-17 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -8.01 | Austin, Cooper, fl0m, freakazoid, Trucklover86 |
|           50 |      738 | 2024-07-16 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -8.70 | Austin, Cooper, fl0m, freakazoid, Trucklover86 |
|           49 |      745 | 2024-07-16 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -9.35 | Austin, Cooper, fl0m, freakazoid, Trucklover86 |
|           48 |      790 | 2024-07-15 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -16.89 | Austin, Cooper, fl0m, freakazoid, Trucklover86 |
|           47 |     1054 | 2024-06-15 | Wildcard         | L   | 0.856      | -            | -                | -                | -         |    -8.59 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           46 |     1130 | 2024-06-13 | LAG              | W   | 0.843      | 0.371        | 0.012 (0.004)    | 0.376 (0.117)    | 0 (0.000) |    13.60 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           45 |     1416 | 2024-06-06 | Legacy           | L   | 0.797      | -            | -                | -                | -         |    -6.12 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           44 |     1483 | 2024-06-05 | Elevate          | L   | 0.790      | -            | -                | -                | -         |    -6.99 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           43 |     1536 | 2024-06-04 | BOSS             | W   | 0.784      | 0.477        | 0.014 (0.005)    | 0.319 (0.119)    | 0 (0.000) |    11.06 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           42 |     1545 | 2024-06-04 | Phoenix          | W   | 0.782      | 0.384        | -                | 0.270 (0.081)    | 0 (0.000) |    10.43 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           41 |     1863 | 2024-05-22 | M80              | L   | 0.695      | -            | -                | -                | -         |    -1.63 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           40 |     1937 | 2024-05-20 | Elevate          | W   | 0.683      | 0.384        | 0.027 (0.007)    | 0.501 (0.132)    | 0 (0.000) |    16.06 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           39 |     2097 | 2024-05-15 | Phoenix          | W   | 0.650      | 0.477        | -                | 0.270 (0.084)    | 0 (0.000) |     9.41 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           38 |     2103 | 2024-05-15 | Phoenix          | L   | 0.650      | -            | -                | -                | -         |   -11.34 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           37 |     2150 | 2024-05-14 | Party Astronauts | L   | 0.644      | -            | -                | -                | -         |    -6.91 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           36 |     2157 | 2024-05-14 | Party Astronauts | W   | 0.644      | 0.477        | 0.041 (0.013)    | 0.510 (0.157)    | 0 (0.000) |    13.72 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           35 |     2228 | 2024-05-12 | Phoenix          | L   | 0.629      | -            | -                | -                | -         |   -10.98 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           34 |     2245 | 2024-05-11 | Nouns            | W   | 0.623      | 0.270        | 0.057 (0.010)    | 0.541 (0.091)    | 0 (0.000) |    14.22 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           33 |     2246 | 2024-05-11 | Wildcard         | W   | 0.623      | 0.270        | 0.048 (0.008)    | -                | 0 (0.000) |    13.20 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           32 |     2618 | 2024-04-24 | BOSS             | W   | 0.511      | 0.477        | 0.014 (0.003)    | 0.319 (0.078)    | 0 (0.000) |     9.67 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           31 |     2619 | 2024-04-24 | BOSS             | L   | 0.510      | -            | -                | -                | -         |    -6.51 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           30 |     2891 | 2024-04-15 | NRG              | L   | 0.450      | -            | -                | -                | -         |    -5.12 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           29 |     2892 | 2024-04-15 | NRG              | L   | 0.450      | -            | -                | -                | -         |    -5.31 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           28 |     2947 | 2024-04-11 | Carpe Diem       | L   | 0.424      | -            | -                | -                | -         |    -8.81 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           27 |     2949 | 2024-04-11 | Carpe Diem       | W   | 0.424      | -            | -                | -                | -         |     4.60 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           26 |     2980 | 2024-04-10 | LAG              | L   | 0.417      | -            | -                | -                | -         |    -5.48 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           25 |     2985 | 2024-04-10 | LAG              | L   | 0.417      | -            | -                | -                | -         |    -5.68 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           24 |     3348 | 2024-03-27 | Wildcard         | L   | 0.323      | -            | -                | -                | -         |    -3.73 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           23 |     3354 | 2024-03-27 | Wildcard         | L   | 0.323      | -            | -                | -                | -         |    -3.83 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           22 |     3391 | 2024-03-26 | Limitless        | W   | 0.317      | -            | -                | -                | -         |     3.20 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           21 |     3396 | 2024-03-26 | Limitless        | L   | 0.317      | -            | -                | -                | -         |    -6.92 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           20 |     3472 | 2024-03-20 | Nouns            | W   | 0.277      | 0.477        | 0.057 (0.008)    | 0.541 (0.071)    | -         |     5.80 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           19 |     3475 | 2024-03-20 | Nouns            | L   | 0.277      | -            | -                | -                | -         |    -2.97 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           18 |     3493 | 2024-03-19 | M80              | W   | 0.271      | 0.477        | 0.064 (0.008)    | -                | -         |     2.45 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           17 |     3495 | 2024-03-19 | M80              | W   | 0.270      | 0.477        | 0.064 (0.008)    | -                | -         |     2.49 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           16 |     3585 | 2024-03-14 | Take Flyte       | W   | 0.237      | -            | -                | -                | -         |     2.91 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           15 |     3588 | 2024-03-14 | Take Flyte       | W   | 0.237      | -            | -                | -                | -         |     2.96 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           14 |     3621 | 2024-03-13 | Phoenix          | L   | 0.229      | -            | -                | -                | -         |    -4.13 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           13 |     3665 | 2024-03-12 | Wildcard         | W   | 0.223      | -            | -                | -                | -         |     4.42 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           12 |     3836 | 2024-03-05 | MIGHT            | L   | 0.177      | -            | -                | -                | -         |    -4.49 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           11 |     3838 | 2024-03-05 | MIGHT            | L   | 0.177      | -            | -                | -                | -         |    -4.53 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           10 |     4050 | 2024-02-24 | NRG              | L   | 0.110      | -            | -                | -                | -         |    -1.45 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            9 |     4141 | 2024-02-20 | Party Astronauts | L   | 0.083      | -            | -                | -                | -         |    -0.85 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            8 |     4165 | 2024-02-19 | Akimbo           | W   | 0.077      | -            | -                | -                | -         |     1.10 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            7 |     4166 | 2024-02-19 | NRG              | L   | 0.076      | -            | -                | -                | -         |    -1.01 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            6 |     4234 | 2024-02-16 | FLUFFY AIMERS    | W   | 0.057      | -            | -                | -                | -         |     0.80 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            5 |     4236 | 2024-02-16 | E-Xolos LAZER    | W   | 0.056      | -            | -                | -                | -         |     0.85 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            4 |     4292 | 2024-02-14 | FLUFFY AIMERS    | W   | 0.044      | -            | -                | -                | -         |     0.63 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            3 |     4294 | 2024-02-14 | FLUFFY AIMERS    | W   | 0.044      | -            | -                | -                | -         |     0.63 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            2 |     4332 | 2024-02-13 | Elevate          | W   | 0.038      | -            | -                | -                | -         |     0.91 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            1 |     4335 | 2024-02-13 | Elevate          | L   | 0.037      | -            | -                | -                | -         |    -0.27 | Cooper, fl0m, freakazoid, hate, Trucklover86   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,097.47)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.864 | $750.00        | $647.74         |
| 2024-06-09 |      0.817 | $3,000.00      | $2,449.72       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
