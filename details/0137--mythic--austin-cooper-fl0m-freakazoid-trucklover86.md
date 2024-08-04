### Roster Details<br />
Team Name: Mythic<br />
Roster: Austin, Cooper, fl0m, freakazoid, Trucklover86<br />
Global Rank: [137](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [36]( ../standings_americas.md)<br />
<br />
Final Rank Value:  759.6<br />
<br />
Final Rank Value (759.6) = Starting Rank Value (790.1) + Head To Head Adjustments (-30.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.332[<sup>1</sup>](#table2)
- Bounty Collected: 0.321[<sup>2</sup>](#table1)
- Opponent Network: 0.111[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.191<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 790.1
- 400 + ( ( 0.191 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 790.1


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
|           54 |      140 | 2024-07-31 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | -                | 0.275 (0.131)    | 0 (0.000) |    14.58 | Austin, Cooper, fl0m, freakazoid, Trucklover86 |
|           53 |      142 | 2024-07-31 | FLUFFY AIMERS    | L   | 1.000      | -            | -                | -                | -         |   -17.03 | Austin, Cooper, fl0m, freakazoid, Trucklover86 |
|           52 |      639 | 2024-07-17 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -7.49 | Austin, Cooper, fl0m, freakazoid, Trucklover86 |
|           51 |      644 | 2024-07-17 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -7.99 | Austin, Cooper, fl0m, freakazoid, Trucklover86 |
|           50 |      700 | 2024-07-16 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -8.69 | Austin, Cooper, fl0m, freakazoid, Trucklover86 |
|           49 |      707 | 2024-07-16 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -9.34 | Austin, Cooper, fl0m, freakazoid, Trucklover86 |
|           48 |      752 | 2024-07-15 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -16.94 | Austin, Cooper, fl0m, freakazoid, Trucklover86 |
|           47 |     1016 | 2024-06-15 | Wildcard         | L   | 0.869      | -            | -                | -                | -         |    -8.66 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           46 |     1092 | 2024-06-13 | LAG              | W   | 0.855      | 0.371        | 0.012 (0.004)    | 0.353 (0.112)    | 0 (0.000) |    13.81 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           45 |     1378 | 2024-06-06 | Legacy           | L   | 0.809      | -            | -                | -                | -         |    -6.13 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           44 |     1445 | 2024-06-05 | Elevate          | L   | 0.802      | -            | -                | -                | -         |    -7.08 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           43 |     1498 | 2024-06-04 | BOSS             | W   | 0.796      | 0.477        | 0.014 (0.005)    | 0.332 (0.126)    | 0 (0.000) |    11.20 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           42 |     1507 | 2024-06-04 | Phoenix          | W   | 0.794      | 0.384        | -                | 0.283 (0.086)    | 0 (0.000) |    10.57 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           41 |     1825 | 2024-05-22 | M80              | L   | 0.708      | -            | -                | -                | -         |    -1.64 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           40 |     1899 | 2024-05-20 | Elevate          | W   | 0.695      | 0.384        | 0.027 (0.007)    | 0.521 (0.139)    | 0 (0.000) |    16.36 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           39 |     2059 | 2024-05-15 | Phoenix          | W   | 0.663      | 0.477        | -                | 0.283 (0.089)    | 0 (0.000) |     9.58 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           38 |     2065 | 2024-05-15 | Phoenix          | L   | 0.662      | -            | -                | -                | -         |   -11.55 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           37 |     2112 | 2024-05-14 | Party Astronauts | L   | 0.656      | -            | -                | -                | -         |    -7.01 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           36 |     2119 | 2024-05-14 | Party Astronauts | W   | 0.656      | 0.477        | 0.041 (0.013)    | 0.531 (0.166)    | 0 (0.000) |    14.01 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           35 |     2190 | 2024-05-12 | Phoenix          | L   | 0.641      | -            | -                | -                | -         |   -11.19 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           34 |     2207 | 2024-05-11 | Nouns            | W   | 0.635      | 0.270        | 0.057 (0.010)    | 0.561 (0.096)    | 0 (0.000) |    14.55 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           33 |     2208 | 2024-05-11 | Wildcard         | W   | 0.635      | 0.270        | 0.048 (0.008)    | -                | 0 (0.000) |    13.51 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           32 |     2580 | 2024-04-24 | BOSS             | W   | 0.523      | 0.477        | 0.014 (0.004)    | 0.332 (0.083)    | 0 (0.000) |     9.92 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           31 |     2581 | 2024-04-24 | BOSS             | L   | 0.522      | -            | -                | -                | -         |    -6.64 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           30 |     2853 | 2024-04-15 | NRG              | L   | 0.462      | -            | -                | -                | -         |    -5.24 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           29 |     2854 | 2024-04-15 | NRG              | L   | 0.462      | -            | -                | -                | -         |    -5.45 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           28 |     2909 | 2024-04-11 | Carpe Diem       | L   | 0.436      | -            | -                | -                | -         |    -9.07 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           27 |     2911 | 2024-04-11 | Carpe Diem       | W   | 0.436      | -            | -                | -                | -         |     4.71 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           26 |     2942 | 2024-04-10 | LAG              | L   | 0.429      | -            | -                | -                | -         |    -5.60 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           25 |     2947 | 2024-04-10 | LAG              | L   | 0.429      | -            | -                | -                | -         |    -5.81 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           24 |     3310 | 2024-03-27 | Wildcard         | L   | 0.336      | -            | -                | -                | -         |    -3.85 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           23 |     3316 | 2024-03-27 | Wildcard         | L   | 0.335      | -            | -                | -                | -         |    -3.95 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           22 |     3353 | 2024-03-26 | Limitless        | W   | 0.330      | -            | -                | -                | -         |     3.30 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           21 |     3358 | 2024-03-26 | Limitless        | L   | 0.329      | -            | -                | -                | -         |    -7.21 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           20 |     3434 | 2024-03-20 | Nouns            | W   | 0.289      | 0.477        | 0.057 (0.008)    | 0.561 (0.077)    | -         |     6.07 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           19 |     3437 | 2024-03-20 | Nouns            | L   | 0.289      | -            | -                | -                | -         |    -3.08 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           18 |     3455 | 2024-03-19 | M80              | W   | 0.283      | 0.477        | 0.064 (0.009)    | -                | -         |     2.54 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           17 |     3457 | 2024-03-19 | M80              | W   | 0.283      | 0.477        | 0.064 (0.009)    | -                | -         |     2.59 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           16 |     3547 | 2024-03-14 | Take Flyte       | W   | 0.250      | -            | -                | -                | -         |     3.05 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           15 |     3550 | 2024-03-14 | Take Flyte       | W   | 0.249      | -            | -                | -                | -         |     3.11 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           14 |     3583 | 2024-03-13 | Phoenix          | L   | 0.242      | -            | -                | -                | -         |    -4.35 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           13 |     3627 | 2024-03-12 | Wildcard         | W   | 0.236      | -            | -                | -                | -         |     4.68 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           12 |     3798 | 2024-03-05 | MIGHT            | L   | 0.190      | -            | -                | -                | -         |    -4.80 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           11 |     3800 | 2024-03-05 | MIGHT            | L   | 0.189      | -            | -                | -                | -         |    -4.84 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|           10 |     4012 | 2024-02-24 | NRG              | L   | 0.122      | -            | -                | -                | -         |    -1.61 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            9 |     4103 | 2024-02-20 | Party Astronauts | L   | 0.095      | -            | -                | -                | -         |    -0.98 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            8 |     4127 | 2024-02-19 | Akimbo           | W   | 0.089      | -            | -                | -                | -         |     1.27 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            7 |     4128 | 2024-02-19 | NRG              | L   | 0.088      | -            | -                | -                | -         |    -1.18 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            6 |     4196 | 2024-02-16 | FLUFFY AIMERS    | W   | 0.069      | -            | -                | -                | -         |     0.98 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            5 |     4198 | 2024-02-16 | E-Xolos LAZER    | W   | 0.069      | -            | -                | -                | -         |     1.03 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            4 |     4254 | 2024-02-14 | FLUFFY AIMERS    | W   | 0.056      | -            | -                | -                | -         |     0.80 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            3 |     4256 | 2024-02-14 | FLUFFY AIMERS    | W   | 0.056      | -            | -                | -                | -         |     0.80 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            2 |     4294 | 2024-02-13 | Elevate          | W   | 0.050      | -            | -                | -                | -         |     1.20 | Cooper, fl0m, freakazoid, hate, Trucklover86   |
|            1 |     4297 | 2024-02-13 | Elevate          | L   | 0.049      | -            | -                | -                | -         |    -0.36 | Cooper, fl0m, freakazoid, hate, Trucklover86   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,143.21)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.876 | $750.00        | $656.89         |
| 2024-06-09 |      0.829 | $3,000.00      | $2,486.32       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
