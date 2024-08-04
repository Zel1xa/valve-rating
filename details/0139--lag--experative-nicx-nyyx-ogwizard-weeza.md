### Roster Details<br />
Team Name: LAG<br />
Roster: Experative, nicx, Nyyx, ogwizard, Weeza<br />
Global Rank: [139](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [37]( ../standings_americas.md)<br />
<br />
Final Rank Value:  755.1<br />
<br />
Final Rank Value (755.1) = Starting Rank Value (840.3) + Head To Head Adjustments (-85.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.343[<sup>1</sup>](#table2)
- Bounty Collected: 0.313[<sup>2</sup>](#table1)
- Opponent Network: 0.113[<sup>2</sup>](#table1)
- LAN Wins: 0.092[<sup>2</sup>](#table1)

The average of these factors is 0.215<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 840.3
- 400 + ( ( 0.215 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 840.3


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
|           55 |      132 | 2024-07-31 | E-Xolos LAZER    | L   | 1.000      | -            | -                | -                | -         |   -13.30 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           54 |      137 | 2024-07-31 | E-Xolos LAZER    | L   | 1.000      | -            | -                | -                | -         |   -14.51 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           53 |      228 | 2024-07-29 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -19.54 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           52 |      353 | 2024-07-25 | Detonate         | L   | 1.000      | -            | -                | -                | -         |   -26.03 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           51 |      379 | 2024-07-24 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | 0.134 (0.064)    | 0 (0.000) |     9.57 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           50 |      382 | 2024-07-24 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | 0.134 (0.064)    | 0 (0.000) |    10.33 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           49 |      502 | 2024-07-20 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -8.76 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           48 |      636 | 2024-07-17 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -16.37 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           47 |      643 | 2024-07-17 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -17.87 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           46 |      704 | 2024-07-16 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -18.02 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           45 |      710 | 2024-07-16 | Wildcard         | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.236 (0.113)    | 0 (0.000) |    13.28 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           44 |      751 | 2024-07-15 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.521 (0.248)    | 0 (0.000) |    20.23 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           43 |      755 | 2024-07-15 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.521 (0.248)    | 0 (0.000) |    21.89 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           42 |     1092 | 2024-06-13 | Mythic           | L   | 0.855      | -            | -                | -                | -         |   -13.81 | based, Experative, nicx, Nyyx, ogwizard |
|           41 |     1264 | 2024-06-08 | Homyno           | W   | 0.822      | 0.371        | 0.007 (0.002)    | -                | 0 (0.000) |     8.77 | based, Experative, nicx, Nyyx, ogwizard |
|           40 |     1319 | 2024-06-07 | Wildcard         | L   | 0.816      | -            | -                | -                | -         |    -8.74 | based, Experative, nicx, Nyyx, ogwizard |
|           39 |     1401 | 2024-06-06 | Vibe             | W   | 0.807      | -            | -                | -                | 0 (0.000) |     2.30 | based, Experative, nicx, Nyyx, ogwizard |
|           38 |     1443 | 2024-06-05 | NRG              | L   | 0.803      | -            | -                | -                | -         |   -10.19 | based, Experative, nicx, Nyyx, ogwizard |
|           37 |     1453 | 2024-06-05 | Limitless        | W   | 0.802      | -            | -                | -                | -         |    10.52 | based, Experative, nicx, Nyyx, ogwizard |
|           36 |     1495 | 2024-06-04 | Limitless        | W   | 0.796      | -            | -                | -                | -         |    11.21 | based, Experative, nicx, Nyyx, ogwizard |
|           35 |     1505 | 2024-06-04 | Retirement Home  | W   | 0.795      | -            | -                | -                | -         |     2.25 | based, Experative, nicx, Nyyx, ogwizard |
|           34 |     1810 | 2024-05-22 | Limitless        | W   | 0.709      | -            | -                | -                | -         |     5.59 | based, Experative, nicx, Nyyx, ogwizard |
|           33 |     1813 | 2024-05-22 | Limitless        | W   | 0.709      | -            | -                | -                | -         |     5.86 | based, Experative, nicx, Nyyx, ogwizard |
|           32 |     1818 | 2024-05-22 | Wildcard         | L   | 0.708      | -            | -                | -                | -         |    -7.63 | based, Experative, nicx, Nyyx, ogwizard |
|           31 |     2061 | 2024-05-15 | NRG              | L   | 0.663      | -            | -                | -                | -         |    -7.42 | based, Experative, nicx, Nyyx, ogwizard |
|           30 |     2068 | 2024-05-15 | NRG              | L   | 0.662      | -            | -                | -                | -         |    -7.83 | based, Experative, nicx, Nyyx, ogwizard |
|           29 |     2114 | 2024-05-14 | Limitless        | W   | 0.656      | -            | -                | -                | -         |     8.60 | based, Experative, nicx, Nyyx, ogwizard |
|           28 |     2120 | 2024-05-14 | Limitless        | L   | 0.656      | -            | -                | -                | -         |   -12.36 | based, Experative, nicx, Nyyx, ogwizard |
|           27 |     2255 | 2024-05-09 | M80              | L   | 0.623      | -            | -                | -                | -         |    -1.71 | based, Experative, nicx, Nyyx, ogwizard |
|           26 |     2260 | 2024-05-09 | M80              | L   | 0.622      | -            | -                | -                | -         |    -1.74 | based, Experative, nicx, Nyyx, ogwizard |
|           25 |     2275 | 2024-05-08 | Party Astronauts | L   | 0.616      | -            | -                | -                | -         |    -6.80 | based, Experative, nicx, Nyyx, ogwizard |
|           24 |     2280 | 2024-05-08 | Party Astronauts | L   | 0.616      | -            | -                | -                | -         |    -7.15 | based, Experative, nicx, Nyyx, ogwizard |
|           23 |     2942 | 2024-04-10 | Mythic           | W   | 0.429      | 0.477        | 0.010 (0.002)    | 0.299 (0.061)    | -         |     5.60 | based, Experative, nicx, Nyyx, ogwizard |
|           22 |     2947 | 2024-04-10 | Mythic           | W   | 0.429      | 0.477        | -                | 0.299 (0.061)    | -         |     5.81 | based, Experative, nicx, Nyyx, ogwizard |
|           21 |     2998 | 2024-04-09 | BOSS             | L   | 0.423      | -            | -                | -                | -         |    -7.18 | based, Experative, nicx, Nyyx, ogwizard |
|           20 |     3001 | 2024-04-09 | BOSS             | L   | 0.422      | -            | -                | -                | -         |    -7.45 | based, Experative, nicx, Nyyx, ogwizard |
|           19 |     3129 | 2024-04-04 | Nouns            | W   | 0.389      | 0.477        | 0.057 (0.011)    | 0.561 (0.104)    | -         |     7.48 | based, Experative, nicx, Nyyx, ogwizard |
|           18 |     3133 | 2024-04-04 | Nouns            | L   | 0.389      | -            | -                | -                | -         |    -4.86 | based, Experative, nicx, Nyyx, ogwizard |
|           17 |     3175 | 2024-04-03 | Elevate          | L   | 0.383      | -            | -                | -                | -         |    -3.67 | based, Experative, nicx, Nyyx, ogwizard |
|           16 |     3177 | 2024-04-03 | Elevate          | W   | 0.382      | 0.477        | 0.027 (0.005)    | 0.521 (0.095)    | -         |     8.55 | based, Experative, nicx, Nyyx, ogwizard |
|           15 |     3351 | 2024-03-26 | Wildcard         | L   | 0.330      | -            | -                | -                | -         |    -4.67 | based, Experative, nicx, Nyyx, ogwizard |
|           14 |     3356 | 2024-03-26 | Wildcard         | W   | 0.329      | 0.477        | 0.048 (0.008)    | 0.438 (0.069)    | -         |     5.82 | based, Experative, nicx, Nyyx, ogwizard |
|           13 |     3436 | 2024-03-20 | Phoenix          | L   | 0.289      | -            | -                | -                | -         |    -6.00 | based, Experative, nicx, Nyyx, ogwizard |
|           12 |     3438 | 2024-03-20 | Phoenix          | W   | 0.289      | -            | -                | -                | -         |     3.16 | based, Experative, nicx, Nyyx, ogwizard |
|           11 |     3481 | 2024-03-17 | Akimbo           | W   | 0.270      | -            | -                | -                | 1 (0.270) |     3.30 | based, Experative, nicx, Nyyx, ogwizard |
|           10 |     3483 | 2024-03-17 | Akimbo           | W   | 0.269      | -            | -                | -                | 1 (0.269) |     2.35 | based, Experative, nicx, Nyyx, ogwizard |
|            9 |     3493 | 2024-03-17 | WICKED           | W   | 0.267      | -            | -                | -                | 1 (0.267) |     1.68 | based, Experative, nicx, Nyyx, ogwizard |
|            8 |     3731 | 2024-03-07 | FLUFFY AIMERS    | W   | 0.203      | -            | -                | -                | -         |     2.57 | based, Experative, nicx, Nyyx, ogwizard |
|            7 |     3732 | 2024-03-07 | FLUFFY AIMERS    | L   | 0.203      | -            | -                | -                | -         |    -3.88 | based, Experative, nicx, Nyyx, ogwizard |
|            6 |     3759 | 2024-03-06 | MIGHT            | W   | 0.196      | -            | -                | -                | -         |     1.02 | based, Experative, nicx, Nyyx, ogwizard |
|            5 |     3760 | 2024-03-06 | MIGHT            | L   | 0.196      | -            | -                | -                | -         |    -5.20 | based, Experative, nicx, Nyyx, ogwizard |
|            4 |     3797 | 2024-03-05 | Take Flyte       | W   | 0.190      | -            | -                | -                | -         |     1.96 | based, Experative, nicx, Nyyx, ogwizard |
|            3 |     3799 | 2024-03-05 | Take Flyte       | W   | 0.189      | -            | -                | -                | -         |     1.98 | based, Experative, nicx, Nyyx, ogwizard |
|            2 |     4010 | 2024-02-24 | Limitless        | L   | 0.122      | -            | -                | -                | -         |    -2.82 | based, Experative, nicx, Nyyx, ogwizard |
|            1 |     4200 | 2024-02-16 | FLUFFY AIMERS    | L   | 0.069      | -            | -                | -                | -         |    -1.33 | based, Experative, nicx, Nyyx, ogwizard |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,969.16)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.829 | $3,000.00      | $2,486.32       |
| 2024-03-17 |      0.270 | $5,500.00      | $1,482.84       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
