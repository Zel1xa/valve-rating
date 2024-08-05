### Roster Details<br />
Team Name: LAG<br />
Roster: Experative, nicx, Nyyx, ogwizard, Weeza<br />
Global Rank: [141](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [37]( ../standings_americas.md)<br />
<br />
Final Rank Value:  754.6<br />
<br />
Final Rank Value (754.6) = Starting Rank Value (838.8) + Head To Head Adjustments (-84.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.343[<sup>1</sup>](#table2)
- Bounty Collected: 0.312[<sup>2</sup>](#table1)
- Opponent Network: 0.110[<sup>2</sup>](#table1)
- LAN Wins: 0.090[<sup>2</sup>](#table1)

The average of these factors is 0.214<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 838.8
- 400 + ( ( 0.214 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 838.8


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
|           55 |      157 | 2024-07-31 | E-Xolos LAZER    | L   | 1.000      | -            | -                | -                | -         |   -13.26 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           54 |      162 | 2024-07-31 | E-Xolos LAZER    | L   | 1.000      | -            | -                | -                | -         |   -14.46 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           53 |      253 | 2024-07-29 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -19.52 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           52 |      378 | 2024-07-25 | Detonate         | L   | 1.000      | -            | -                | -                | -         |   -26.01 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           51 |      404 | 2024-07-24 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | 0.131 (0.063)    | 0 (0.000) |     9.57 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           50 |      407 | 2024-07-24 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | 0.131 (0.063)    | 0 (0.000) |    10.33 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           49 |      527 | 2024-07-20 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -8.77 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           48 |      661 | 2024-07-17 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -16.36 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           47 |      668 | 2024-07-17 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -17.86 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           46 |      729 | 2024-07-16 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -17.99 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           45 |      735 | 2024-07-16 | Wildcard         | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.235 (0.112)    | 0 (0.000) |    13.31 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           44 |      776 | 2024-07-15 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.513 (0.245)    | 0 (0.000) |    20.24 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           43 |      780 | 2024-07-15 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.513 (0.245)    | 0 (0.000) |    21.89 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           42 |     1117 | 2024-06-13 | Mythic           | L   | 0.849      | -            | -                | -                | -         |   -13.69 | based, Experative, nicx, Nyyx, ogwizard |
|           41 |     1289 | 2024-06-08 | Homyno           | W   | 0.815      | 0.371        | 0.007 (0.002)    | -                | 0 (0.000) |     8.73 | based, Experative, nicx, Nyyx, ogwizard |
|           40 |     1344 | 2024-06-07 | Wildcard         | L   | 0.809      | -            | -                | -                | -         |    -8.69 | based, Experative, nicx, Nyyx, ogwizard |
|           39 |     1426 | 2024-06-06 | Vibe             | W   | 0.800      | -            | -                | -                | 0 (0.000) |     2.29 | based, Experative, nicx, Nyyx, ogwizard |
|           38 |     1468 | 2024-06-05 | NRG              | L   | 0.796      | -            | -                | -                | -         |   -10.09 | based, Experative, nicx, Nyyx, ogwizard |
|           37 |     1478 | 2024-06-05 | Limitless        | W   | 0.795      | -            | -                | -                | -         |    10.44 | based, Experative, nicx, Nyyx, ogwizard |
|           36 |     1520 | 2024-06-04 | Limitless        | W   | 0.789      | -            | -                | -                | -         |    11.11 | based, Experative, nicx, Nyyx, ogwizard |
|           35 |     1530 | 2024-06-04 | Retirement Home  | W   | 0.788      | -            | -                | -                | -         |     2.24 | based, Experative, nicx, Nyyx, ogwizard |
|           34 |     1835 | 2024-05-22 | Limitless        | W   | 0.702      | -            | -                | -                | -         |     5.56 | based, Experative, nicx, Nyyx, ogwizard |
|           33 |     1838 | 2024-05-22 | Limitless        | W   | 0.702      | -            | -                | -                | -         |     5.83 | based, Experative, nicx, Nyyx, ogwizard |
|           32 |     1843 | 2024-05-22 | Wildcard         | L   | 0.702      | -            | -                | -                | -         |    -7.58 | based, Experative, nicx, Nyyx, ogwizard |
|           31 |     2086 | 2024-05-15 | NRG              | L   | 0.656      | -            | -                | -                | -         |    -7.34 | based, Experative, nicx, Nyyx, ogwizard |
|           30 |     2093 | 2024-05-15 | NRG              | L   | 0.656      | -            | -                | -                | -         |    -7.74 | based, Experative, nicx, Nyyx, ogwizard |
|           29 |     2139 | 2024-05-14 | Limitless        | W   | 0.649      | -            | -                | -                | -         |     8.53 | based, Experative, nicx, Nyyx, ogwizard |
|           28 |     2145 | 2024-05-14 | Limitless        | L   | 0.649      | -            | -                | -                | -         |   -12.22 | based, Experative, nicx, Nyyx, ogwizard |
|           27 |     2280 | 2024-05-09 | M80              | L   | 0.616      | -            | -                | -                | -         |    -1.70 | based, Experative, nicx, Nyyx, ogwizard |
|           26 |     2285 | 2024-05-09 | M80              | L   | 0.616      | -            | -                | -                | -         |    -1.73 | based, Experative, nicx, Nyyx, ogwizard |
|           25 |     2300 | 2024-05-08 | Party Astronauts | L   | 0.609      | -            | -                | -                | -         |    -6.72 | based, Experative, nicx, Nyyx, ogwizard |
|           24 |     2305 | 2024-05-08 | Party Astronauts | L   | 0.609      | -            | -                | -                | -         |    -7.06 | based, Experative, nicx, Nyyx, ogwizard |
|           23 |     2967 | 2024-04-10 | Mythic           | W   | 0.422      | 0.477        | 0.010 (0.002)    | 0.293 (0.059)    | -         |     5.54 | based, Experative, nicx, Nyyx, ogwizard |
|           22 |     2972 | 2024-04-10 | Mythic           | W   | 0.422      | 0.477        | -                | 0.293 (0.059)    | -         |     5.74 | based, Experative, nicx, Nyyx, ogwizard |
|           21 |     3023 | 2024-04-09 | BOSS             | L   | 0.416      | -            | -                | -                | -         |    -7.07 | based, Experative, nicx, Nyyx, ogwizard |
|           20 |     3026 | 2024-04-09 | BOSS             | L   | 0.416      | -            | -                | -                | -         |    -7.33 | based, Experative, nicx, Nyyx, ogwizard |
|           19 |     3154 | 2024-04-04 | Nouns            | W   | 0.383      | 0.477        | 0.057 (0.010)    | 0.553 (0.101)    | -         |     7.35 | based, Experative, nicx, Nyyx, ogwizard |
|           18 |     3158 | 2024-04-04 | Nouns            | L   | 0.382      | -            | -                | -                | -         |    -4.77 | based, Experative, nicx, Nyyx, ogwizard |
|           17 |     3200 | 2024-04-03 | Elevate          | L   | 0.376      | -            | -                | -                | -         |    -3.60 | based, Experative, nicx, Nyyx, ogwizard |
|           16 |     3202 | 2024-04-03 | Elevate          | W   | 0.376      | 0.477        | 0.027 (0.005)    | 0.513 (0.092)    | -         |     8.40 | based, Experative, nicx, Nyyx, ogwizard |
|           15 |     3376 | 2024-03-26 | Wildcard         | L   | 0.323      | -            | -                | -                | -         |    -4.58 | based, Experative, nicx, Nyyx, ogwizard |
|           14 |     3381 | 2024-03-26 | Wildcard         | W   | 0.323      | 0.477        | 0.048 (0.007)    | 0.429 (0.066)    | -         |     5.70 | based, Experative, nicx, Nyyx, ogwizard |
|           13 |     3461 | 2024-03-20 | Phoenix          | L   | 0.282      | -            | -                | -                | -         |    -5.84 | based, Experative, nicx, Nyyx, ogwizard |
|           12 |     3463 | 2024-03-20 | Phoenix          | W   | 0.282      | -            | -                | -                | -         |     3.10 | based, Experative, nicx, Nyyx, ogwizard |
|           11 |     3506 | 2024-03-17 | Akimbo           | W   | 0.263      | -            | -                | -                | 1 (0.263) |     3.23 | based, Experative, nicx, Nyyx, ogwizard |
|           10 |     3508 | 2024-03-17 | Akimbo           | W   | 0.262      | -            | -                | -                | 1 (0.262) |     2.30 | based, Experative, nicx, Nyyx, ogwizard |
|            9 |     3518 | 2024-03-17 | WICKED           | W   | 0.261      | -            | -                | -                | 1 (0.261) |     1.65 | based, Experative, nicx, Nyyx, ogwizard |
|            8 |     3756 | 2024-03-07 | FLUFFY AIMERS    | W   | 0.196      | -            | -                | -                | -         |     2.48 | based, Experative, nicx, Nyyx, ogwizard |
|            7 |     3757 | 2024-03-07 | FLUFFY AIMERS    | L   | 0.196      | -            | -                | -                | -         |    -3.74 | based, Experative, nicx, Nyyx, ogwizard |
|            6 |     3784 | 2024-03-06 | MIGHT            | W   | 0.189      | -            | -                | -                | -         |     0.98 | based, Experative, nicx, Nyyx, ogwizard |
|            5 |     3785 | 2024-03-06 | MIGHT            | L   | 0.189      | -            | -                | -                | -         |    -5.02 | based, Experative, nicx, Nyyx, ogwizard |
|            4 |     3822 | 2024-03-05 | Take Flyte       | W   | 0.183      | -            | -                | -                | -         |     1.90 | based, Experative, nicx, Nyyx, ogwizard |
|            3 |     3824 | 2024-03-05 | Take Flyte       | W   | 0.182      | -            | -                | -                | -         |     1.92 | based, Experative, nicx, Nyyx, ogwizard |
|            2 |     4035 | 2024-02-24 | Limitless        | L   | 0.115      | -            | -                | -                | -         |    -2.66 | based, Experative, nicx, Nyyx, ogwizard |
|            1 |     4225 | 2024-02-16 | FLUFFY AIMERS    | L   | 0.062      | -            | -                | -                | -         |    -1.19 | based, Experative, nicx, Nyyx, ogwizard |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,911.11)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.822 | $3,000.00      | $2,465.83       |
| 2024-03-17 |      0.263 | $5,500.00      | $1,445.28       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
