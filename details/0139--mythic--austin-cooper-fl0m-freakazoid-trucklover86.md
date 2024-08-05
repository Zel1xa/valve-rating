### Roster Details<br />
Team Name: Mythic<br />
Roster: Austin, Cooper, fl0m, freakazoid, Trucklover86<br />
Global Rank: [139](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [36]( ../standings_americas.md)<br />
<br />
Final Rank Value:  759.6<br />
<br />
Final Rank Value (759.6) = Starting Rank Value (790.5) + Head To Head Adjustments (-30.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.332[<sup>1</sup>](#table2)
- Bounty Collected: 0.320[<sup>2</sup>](#table1)
- Opponent Network: 0.111[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.191<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 790.5
- 400 + ( ( 0.191 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 790.5


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
|           54 |      157 | 2024-07-31 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | -                | 0.314 (0.150)    | 0 (0.000) |    14.69 | Austin, Cooper, fl0m, freakazoid, Trucklover86 |
|           53 |      159 | 2024-07-31 | FLUFFY AIMERS    | L   | 1.000      | -            | -                | -                | -         |   -16.92 | Austin, Cooper, fl0m, freakazoid, Trucklover86 |
|           52 |      656 | 2024-07-17 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -7.49 | Austin, Cooper, fl0m, freakazoid, Trucklover86 |
|           51 |      661 | 2024-07-17 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -7.99 | Austin, Cooper, fl0m, freakazoid, Trucklover86 |
|           50 |      717 | 2024-07-16 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -8.69 | Austin, Cooper, fl0m, freakazoid, Trucklover86 |
|           49 |      724 | 2024-07-16 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -9.34 | Austin, Cooper, fl0m, freakazoid, Trucklover86 |
|           48 |      769 | 2024-07-15 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -16.94 | Austin, Cooper, fl0m, freakazoid, Trucklover86 |
|           47 |     1033 | 2024-06-15 | Wildcard         | L   | 0.863      | -            | -                | -                | -         |    -8.64 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           46 |     1109 | 2024-06-13 | LAG              | W   | 0.850      | 0.371        | 0.012 (0.004)    | 0.351 (0.111)    | 0 (0.000) |    13.70 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           45 |     1395 | 2024-06-06 | Legacy           | L   | 0.803      | -            | -                | -                | -         |    -6.12 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           44 |     1462 | 2024-06-05 | Elevate          | L   | 0.797      | -            | -                | -                | -         |    -7.04 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           43 |     1515 | 2024-06-04 | BOSS             | W   | 0.790      | 0.477        | 0.014 (0.005)    | 0.331 (0.125)    | 0 (0.000) |    11.11 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           42 |     1524 | 2024-06-04 | Phoenix          | W   | 0.788      | 0.384        | -                | 0.281 (0.085)    | 0 (0.000) |    10.51 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           41 |     1842 | 2024-05-22 | M80              | L   | 0.702      | -            | -                | -                | -         |    -1.63 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           40 |     1916 | 2024-05-20 | Elevate          | W   | 0.689      | 0.384        | 0.027 (0.007)    | 0.519 (0.138)    | 0 (0.000) |    16.22 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           39 |     2076 | 2024-05-15 | Phoenix          | W   | 0.657      | 0.477        | -                | 0.281 (0.088)    | 0 (0.000) |     9.50 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           38 |     2082 | 2024-05-15 | Phoenix          | L   | 0.657      | -            | -                | -                | -         |   -11.45 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           37 |     2129 | 2024-05-14 | Party Astronauts | L   | 0.650      | -            | -                | -                | -         |    -6.95 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           36 |     2136 | 2024-05-14 | Party Astronauts | W   | 0.650      | 0.477        | 0.041 (0.013)    | 0.529 (0.164)    | 0 (0.000) |    13.89 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           35 |     2207 | 2024-05-12 | Phoenix          | L   | 0.635      | -            | -                | -                | -         |   -11.09 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           34 |     2224 | 2024-05-11 | Nouns            | W   | 0.630      | 0.270        | 0.057 (0.010)    | 0.560 (0.095)    | 0 (0.000) |    14.40 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           33 |     2225 | 2024-05-11 | Wildcard         | W   | 0.629      | 0.270        | 0.048 (0.008)    | -                | 0 (0.000) |    13.35 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           32 |     2597 | 2024-04-24 | BOSS             | W   | 0.517      | 0.477        | 0.014 (0.003)    | 0.331 (0.082)    | 0 (0.000) |     9.78 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           31 |     2598 | 2024-04-24 | BOSS             | L   | 0.517      | -            | -                | -                | -         |    -6.60 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           30 |     2870 | 2024-04-15 | NRG              | L   | 0.457      | -            | -                | -                | -         |    -5.18 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           29 |     2871 | 2024-04-15 | NRG              | L   | 0.456      | -            | -                | -                | -         |    -5.38 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           28 |     2926 | 2024-04-11 | Carpe Diem       | L   | 0.430      | -            | -                | -                | -         |    -8.96 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           27 |     2928 | 2024-04-11 | Carpe Diem       | W   | 0.430      | -            | -                | -                | -         |     4.65 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           26 |     2959 | 2024-04-10 | LAG              | L   | 0.424      | -            | -                | -                | -         |    -5.55 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           25 |     2964 | 2024-04-10 | LAG              | L   | 0.423      | -            | -                | -                | -         |    -5.75 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           24 |     3327 | 2024-03-27 | Wildcard         | L   | 0.330      | -            | -                | -                | -         |    -3.80 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           23 |     3333 | 2024-03-27 | Wildcard         | L   | 0.330      | -            | -                | -                | -         |    -3.90 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           22 |     3370 | 2024-03-26 | Limitless        | W   | 0.324      | -            | -                | -                | -         |     3.25 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           21 |     3375 | 2024-03-26 | Limitless        | L   | 0.324      | -            | -                | -                | -         |    -7.08 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           20 |     3451 | 2024-03-20 | Nouns            | W   | 0.284      | 0.477        | 0.057 (0.008)    | 0.560 (0.076)    | -         |     5.95 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           19 |     3454 | 2024-03-20 | Nouns            | L   | 0.283      | -            | -                | -                | -         |    -3.03 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           18 |     3472 | 2024-03-19 | M80              | W   | 0.277      | 0.477        | 0.064 (0.008)    | -                | -         |     2.49 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           17 |     3474 | 2024-03-19 | M80              | W   | 0.277      | 0.477        | 0.064 (0.008)    | -                | -         |     2.54 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           16 |     3564 | 2024-03-14 | Take Flyte       | W   | 0.244      | -            | -                | -                | -         |     2.98 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           15 |     3567 | 2024-03-14 | Take Flyte       | W   | 0.244      | -            | -                | -                | -         |     3.03 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           14 |     3600 | 2024-03-13 | Phoenix          | L   | 0.236      | -            | -                | -                | -         |    -4.25 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           13 |     3644 | 2024-03-12 | Wildcard         | W   | 0.230      | -            | -                | -                | -         |     4.55 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           12 |     3815 | 2024-03-05 | MIGHT            | L   | 0.184      | -            | -                | -                | -         |    -4.66 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           11 |     3817 | 2024-03-05 | MIGHT            | L   | 0.184      | -            | -                | -                | -         |    -4.70 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           10 |     4029 | 2024-02-24 | NRG              | L   | 0.116      | -            | -                | -                | -         |    -1.53 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            9 |     4120 | 2024-02-20 | Party Astronauts | L   | 0.089      | -            | -                | -                | -         |    -0.92 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            8 |     4144 | 2024-02-19 | Akimbo           | W   | 0.084      | -            | -                | -                | -         |     1.19 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            7 |     4145 | 2024-02-19 | NRG              | L   | 0.083      | -            | -                | -                | -         |    -1.10 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            6 |     4213 | 2024-02-16 | FLUFFY AIMERS    | W   | 0.063      | -            | -                | -                | -         |     0.89 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            5 |     4215 | 2024-02-16 | E-Xolos LAZER    | W   | 0.063      | -            | -                | -                | -         |     0.95 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            4 |     4271 | 2024-02-14 | FLUFFY AIMERS    | W   | 0.051      | -            | -                | -                | -         |     0.72 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            3 |     4273 | 2024-02-14 | FLUFFY AIMERS    | W   | 0.050      | -            | -                | -                | -         |     0.72 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            2 |     4311 | 2024-02-13 | Elevate          | W   | 0.044      | -            | -                | -                | -         |     1.06 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            1 |     4314 | 2024-02-13 | Elevate          | L   | 0.044      | -            | -                | -                | -         |    -0.32 | Cooper, fl0m, freakazoid, hate, Trucklover86   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,121.77)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.870 | $750.00        | $652.60         |
| 2024-06-09 |      0.823 | $3,000.00      | $2,469.17       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
