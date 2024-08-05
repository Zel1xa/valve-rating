### Roster Details<br />
Team Name: LAG<br />
Roster: Experative, nicx, Nyyx, ogwizard, Weeza<br />
Global Rank: [139](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [37]( ../standings_americas.md)<br />
<br />
Final Rank Value:  755.2<br />
<br />
Final Rank Value (755.2) = Starting Rank Value (839.9) + Head To Head Adjustments (-84.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.343[<sup>1</sup>](#table2)
- Bounty Collected: 0.313[<sup>2</sup>](#table1)
- Opponent Network: 0.112[<sup>2</sup>](#table1)
- LAN Wins: 0.092[<sup>2</sup>](#table1)

The average of these factors is 0.215<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 839.9
- 400 + ( ( 0.215 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 839.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           55 |      136 | 2024-07-31 | E-Xolos LAZER    | L   | 1.000      | -            | -                | -                | -         |   -13.27 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           54 |      141 | 2024-07-31 | E-Xolos LAZER    | L   | 1.000      | -            | -                | -                | -         |   -14.47 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           53 |      232 | 2024-07-29 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -19.55 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           52 |      357 | 2024-07-25 | Detonate         | L   | 1.000      | -            | -                | -                | -         |   -26.03 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           51 |      383 | 2024-07-24 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | 0.134 (0.064)    | 0 (0.000) |     9.57 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           50 |      386 | 2024-07-24 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | 0.134 (0.064)    | 0 (0.000) |    10.33 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           49 |      506 | 2024-07-20 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -8.76 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           48 |      640 | 2024-07-17 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -16.36 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           47 |      647 | 2024-07-17 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -17.86 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           46 |      708 | 2024-07-16 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -18.01 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           45 |      714 | 2024-07-16 | Wildcard         | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.237 (0.113)    | 0 (0.000) |    13.29 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           44 |      755 | 2024-07-15 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.521 (0.248)    | 0 (0.000) |    20.24 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           43 |      759 | 2024-07-15 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.521 (0.248)    | 0 (0.000) |    21.89 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           42 |     1096 | 2024-06-13 | Mythic           | L   | 0.853      | -            | -                | -                | -         |   -13.75 | based, Experative, nicx, Nyyx, ogwizard |
|           41 |     1268 | 2024-06-08 | Homyno           | W   | 0.820      | 0.371        | 0.007 (0.002)    | -                | 0 (0.000) |     8.75 | based, Experative, nicx, Nyyx, ogwizard |
|           40 |     1323 | 2024-06-07 | Wildcard         | L   | 0.813      | -            | -                | -                | -         |    -8.72 | based, Experative, nicx, Nyyx, ogwizard |
|           39 |     1405 | 2024-06-06 | Vibe             | W   | 0.805      | -            | -                | -                | 0 (0.000) |     2.30 | based, Experative, nicx, Nyyx, ogwizard |
|           38 |     1447 | 2024-06-05 | NRG              | L   | 0.800      | -            | -                | -                | -         |   -10.14 | based, Experative, nicx, Nyyx, ogwizard |
|           37 |     1457 | 2024-06-05 | Limitless        | W   | 0.799      | -            | -                | -                | -         |    10.49 | based, Experative, nicx, Nyyx, ogwizard |
|           36 |     1499 | 2024-06-04 | Limitless        | W   | 0.794      | -            | -                | -                | -         |    11.17 | based, Experative, nicx, Nyyx, ogwizard |
|           35 |     1509 | 2024-06-04 | Retirement Home  | W   | 0.793      | -            | -                | -                | -         |     2.24 | based, Experative, nicx, Nyyx, ogwizard |
|           34 |     1814 | 2024-05-22 | Limitless        | W   | 0.707      | -            | -                | -                | -         |     5.58 | based, Experative, nicx, Nyyx, ogwizard |
|           33 |     1817 | 2024-05-22 | Limitless        | W   | 0.707      | -            | -                | -                | -         |     5.85 | based, Experative, nicx, Nyyx, ogwizard |
|           32 |     1822 | 2024-05-22 | Wildcard         | L   | 0.706      | -            | -                | -                | -         |    -7.61 | based, Experative, nicx, Nyyx, ogwizard |
|           31 |     2065 | 2024-05-15 | NRG              | L   | 0.660      | -            | -                | -                | -         |    -7.38 | based, Experative, nicx, Nyyx, ogwizard |
|           30 |     2072 | 2024-05-15 | NRG              | L   | 0.660      | -            | -                | -                | -         |    -7.79 | based, Experative, nicx, Nyyx, ogwizard |
|           29 |     2118 | 2024-05-14 | Limitless        | W   | 0.654      | -            | -                | -                | -         |     8.57 | based, Experative, nicx, Nyyx, ogwizard |
|           28 |     2124 | 2024-05-14 | Limitless        | L   | 0.653      | -            | -                | -                | -         |   -12.31 | based, Experative, nicx, Nyyx, ogwizard |
|           27 |     2259 | 2024-05-09 | M80              | L   | 0.620      | -            | -                | -                | -         |    -1.70 | based, Experative, nicx, Nyyx, ogwizard |
|           26 |     2264 | 2024-05-09 | M80              | L   | 0.620      | -            | -                | -                | -         |    -1.73 | based, Experative, nicx, Nyyx, ogwizard |
|           25 |     2279 | 2024-05-08 | Party Astronauts | L   | 0.614      | -            | -                | -                | -         |    -6.76 | based, Experative, nicx, Nyyx, ogwizard |
|           24 |     2284 | 2024-05-08 | Party Astronauts | L   | 0.613      | -            | -                | -                | -         |    -7.10 | based, Experative, nicx, Nyyx, ogwizard |
|           23 |     2946 | 2024-04-10 | Mythic           | W   | 0.427      | 0.477        | 0.010 (0.002)    | 0.299 (0.061)    | -         |     5.59 | based, Experative, nicx, Nyyx, ogwizard |
|           22 |     2951 | 2024-04-10 | Mythic           | W   | 0.427      | 0.477        | -                | 0.299 (0.061)    | -         |     5.80 | based, Experative, nicx, Nyyx, ogwizard |
|           21 |     3002 | 2024-04-09 | BOSS             | L   | 0.420      | -            | -                | -                | -         |    -7.14 | based, Experative, nicx, Nyyx, ogwizard |
|           20 |     3005 | 2024-04-09 | BOSS             | L   | 0.420      | -            | -                | -                | -         |    -7.41 | based, Experative, nicx, Nyyx, ogwizard |
|           19 |     3133 | 2024-04-04 | Nouns            | W   | 0.387      | 0.477        | 0.057 (0.011)    | 0.561 (0.104)    | -         |     7.44 | based, Experative, nicx, Nyyx, ogwizard |
|           18 |     3137 | 2024-04-04 | Nouns            | L   | 0.387      | -            | -                | -                | -         |    -4.83 | based, Experative, nicx, Nyyx, ogwizard |
|           17 |     3179 | 2024-04-03 | Elevate          | L   | 0.380      | -            | -                | -                | -         |    -3.65 | based, Experative, nicx, Nyyx, ogwizard |
|           16 |     3181 | 2024-04-03 | Elevate          | W   | 0.380      | 0.477        | 0.027 (0.005)    | 0.521 (0.094)    | -         |     8.50 | based, Experative, nicx, Nyyx, ogwizard |
|           15 |     3355 | 2024-03-26 | Wildcard         | L   | 0.327      | -            | -                | -                | -         |    -4.64 | based, Experative, nicx, Nyyx, ogwizard |
|           14 |     3360 | 2024-03-26 | Wildcard         | W   | 0.327      | 0.477        | 0.048 (0.007)    | 0.437 (0.068)    | -         |     5.78 | based, Experative, nicx, Nyyx, ogwizard |
|           13 |     3440 | 2024-03-20 | Phoenix          | L   | 0.287      | -            | -                | -                | -         |    -5.93 | based, Experative, nicx, Nyyx, ogwizard |
|           12 |     3442 | 2024-03-20 | Phoenix          | W   | 0.287      | -            | -                | -                | -         |     3.14 | based, Experative, nicx, Nyyx, ogwizard |
|           11 |     3485 | 2024-03-17 | Akimbo           | W   | 0.267      | -            | -                | -                | 1 (0.267) |     3.28 | based, Experative, nicx, Nyyx, ogwizard |
|           10 |     3487 | 2024-03-17 | Akimbo           | W   | 0.266      | -            | -                | -                | 1 (0.266) |     2.33 | based, Experative, nicx, Nyyx, ogwizard |
|            9 |     3497 | 2024-03-17 | WICKED           | W   | 0.265      | -            | -                | -                | 1 (0.265) |     1.66 | based, Experative, nicx, Nyyx, ogwizard |
|            8 |     3735 | 2024-03-07 | FLUFFY AIMERS    | W   | 0.201      | -            | -                | -                | -         |     2.54 | based, Experative, nicx, Nyyx, ogwizard |
|            7 |     3736 | 2024-03-07 | FLUFFY AIMERS    | L   | 0.200      | -            | -                | -                | -         |    -3.83 | based, Experative, nicx, Nyyx, ogwizard |
|            6 |     3763 | 2024-03-06 | MIGHT            | W   | 0.194      | -            | -                | -                | -         |     1.01 | based, Experative, nicx, Nyyx, ogwizard |
|            5 |     3764 | 2024-03-06 | MIGHT            | L   | 0.194      | -            | -                | -                | -         |    -5.13 | based, Experative, nicx, Nyyx, ogwizard |
|            4 |     3801 | 2024-03-05 | Take Flyte       | W   | 0.187      | -            | -                | -                | -         |     1.94 | based, Experative, nicx, Nyyx, ogwizard |
|            3 |     3803 | 2024-03-05 | Take Flyte       | W   | 0.187      | -            | -                | -                | -         |     1.96 | based, Experative, nicx, Nyyx, ogwizard |
|            2 |     4014 | 2024-02-24 | Limitless        | L   | 0.119      | -            | -                | -                | -         |    -2.77 | based, Experative, nicx, Nyyx, ogwizard |
|            1 |     4204 | 2024-02-16 | FLUFFY AIMERS    | L   | 0.066      | -            | -                | -                | -         |    -1.28 | based, Experative, nicx, Nyyx, ogwizard |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,948.89)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.826 | $3,000.00      | $2,479.17       |
| 2024-03-17 |      0.267 | $5,500.00      | $1,469.72       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
