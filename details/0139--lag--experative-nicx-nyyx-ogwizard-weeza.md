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
Final Rank Value (755.2) = Starting Rank Value (840.4) + Head To Head Adjustments (-85.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.343[<sup>1</sup>](#table2)
- Bounty Collected: 0.313[<sup>2</sup>](#table1)
- Opponent Network: 0.113[<sup>2</sup>](#table1)
- LAN Wins: 0.092[<sup>2</sup>](#table1)

The average of these factors is 0.215<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 840.4
- 400 + ( ( 0.215 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 840.4


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
|           55 |      131 | 2024-07-31 | E-Xolos LAZER    | L   | 1.000      | -            | -                | -                | -         |   -13.30 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           54 |      136 | 2024-07-31 | E-Xolos LAZER    | L   | 1.000      | -            | -                | -                | -         |   -14.51 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           53 |      227 | 2024-07-29 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -19.54 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           52 |      352 | 2024-07-25 | Detonate         | L   | 1.000      | -            | -                | -                | -         |   -26.03 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           51 |      378 | 2024-07-24 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | 0.134 (0.064)    | 0 (0.000) |     9.57 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           50 |      381 | 2024-07-24 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | 0.134 (0.064)    | 0 (0.000) |    10.33 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           49 |      501 | 2024-07-20 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -8.76 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           48 |      635 | 2024-07-17 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -16.37 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           47 |      642 | 2024-07-17 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -17.87 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           46 |      703 | 2024-07-16 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -18.02 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           45 |      709 | 2024-07-16 | Wildcard         | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.236 (0.113)    | 0 (0.000) |    13.28 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           44 |      750 | 2024-07-15 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.521 (0.248)    | 0 (0.000) |    20.23 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           43 |      754 | 2024-07-15 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.521 (0.248)    | 0 (0.000) |    21.89 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           42 |     1091 | 2024-06-13 | Mythic           | L   | 0.856      | -            | -                | -                | -         |   -13.81 | based, Experative, nicx, Nyyx, ogwizard |
|           41 |     1263 | 2024-06-08 | Homyno           | W   | 0.822      | 0.371        | 0.007 (0.002)    | -                | 0 (0.000) |     8.77 | based, Experative, nicx, Nyyx, ogwizard |
|           40 |     1318 | 2024-06-07 | Wildcard         | L   | 0.816      | -            | -                | -                | -         |    -8.74 | based, Experative, nicx, Nyyx, ogwizard |
|           39 |     1400 | 2024-06-06 | Vibe             | W   | 0.807      | -            | -                | -                | 0 (0.000) |     2.30 | based, Experative, nicx, Nyyx, ogwizard |
|           38 |     1442 | 2024-06-05 | NRG              | L   | 0.803      | -            | -                | -                | -         |   -10.20 | based, Experative, nicx, Nyyx, ogwizard |
|           37 |     1452 | 2024-06-05 | Limitless        | W   | 0.802      | -            | -                | -                | -         |    10.53 | based, Experative, nicx, Nyyx, ogwizard |
|           36 |     1494 | 2024-06-04 | Limitless        | W   | 0.796      | -            | -                | -                | -         |    11.21 | based, Experative, nicx, Nyyx, ogwizard |
|           35 |     1504 | 2024-06-04 | Retirement Home  | W   | 0.795      | -            | -                | -                | -         |     2.25 | based, Experative, nicx, Nyyx, ogwizard |
|           34 |     1809 | 2024-05-22 | Limitless        | W   | 0.710      | -            | -                | -                | -         |     5.59 | based, Experative, nicx, Nyyx, ogwizard |
|           33 |     1812 | 2024-05-22 | Limitless        | W   | 0.709      | -            | -                | -                | -         |     5.86 | based, Experative, nicx, Nyyx, ogwizard |
|           32 |     1817 | 2024-05-22 | Wildcard         | L   | 0.709      | -            | -                | -                | -         |    -7.63 | based, Experative, nicx, Nyyx, ogwizard |
|           31 |     2060 | 2024-05-15 | NRG              | L   | 0.663      | -            | -                | -                | -         |    -7.42 | based, Experative, nicx, Nyyx, ogwizard |
|           30 |     2067 | 2024-05-15 | NRG              | L   | 0.663      | -            | -                | -                | -         |    -7.84 | based, Experative, nicx, Nyyx, ogwizard |
|           29 |     2113 | 2024-05-14 | Limitless        | W   | 0.656      | -            | -                | -                | -         |     8.61 | based, Experative, nicx, Nyyx, ogwizard |
|           28 |     2119 | 2024-05-14 | Limitless        | L   | 0.656      | -            | -                | -                | -         |   -12.37 | based, Experative, nicx, Nyyx, ogwizard |
|           27 |     2254 | 2024-05-09 | M80              | L   | 0.623      | -            | -                | -                | -         |    -1.71 | based, Experative, nicx, Nyyx, ogwizard |
|           26 |     2259 | 2024-05-09 | M80              | L   | 0.623      | -            | -                | -                | -         |    -1.74 | based, Experative, nicx, Nyyx, ogwizard |
|           25 |     2274 | 2024-05-08 | Party Astronauts | L   | 0.616      | -            | -                | -                | -         |    -6.80 | based, Experative, nicx, Nyyx, ogwizard |
|           24 |     2279 | 2024-05-08 | Party Astronauts | L   | 0.616      | -            | -                | -                | -         |    -7.15 | based, Experative, nicx, Nyyx, ogwizard |
|           23 |     2941 | 2024-04-10 | Mythic           | W   | 0.430      | 0.477        | 0.010 (0.002)    | 0.299 (0.061)    | -         |     5.61 | based, Experative, nicx, Nyyx, ogwizard |
|           22 |     2946 | 2024-04-10 | Mythic           | W   | 0.429      | 0.477        | -                | 0.299 (0.061)    | -         |     5.82 | based, Experative, nicx, Nyyx, ogwizard |
|           21 |     2997 | 2024-04-09 | BOSS             | L   | 0.423      | -            | -                | -                | -         |    -7.19 | based, Experative, nicx, Nyyx, ogwizard |
|           20 |     3000 | 2024-04-09 | BOSS             | L   | 0.423      | -            | -                | -                | -         |    -7.46 | based, Experative, nicx, Nyyx, ogwizard |
|           19 |     3128 | 2024-04-04 | Nouns            | W   | 0.390      | 0.477        | 0.057 (0.011)    | 0.561 (0.104)    | -         |     7.49 | based, Experative, nicx, Nyyx, ogwizard |
|           18 |     3132 | 2024-04-04 | Nouns            | L   | 0.389      | -            | -                | -                | -         |    -4.86 | based, Experative, nicx, Nyyx, ogwizard |
|           17 |     3174 | 2024-04-03 | Elevate          | L   | 0.383      | -            | -                | -                | -         |    -3.68 | based, Experative, nicx, Nyyx, ogwizard |
|           16 |     3176 | 2024-04-03 | Elevate          | W   | 0.383      | 0.477        | 0.027 (0.005)    | 0.521 (0.095)    | -         |     8.56 | based, Experative, nicx, Nyyx, ogwizard |
|           15 |     3350 | 2024-03-26 | Wildcard         | L   | 0.330      | -            | -                | -                | -         |    -4.68 | based, Experative, nicx, Nyyx, ogwizard |
|           14 |     3355 | 2024-03-26 | Wildcard         | W   | 0.330      | 0.477        | 0.048 (0.008)    | 0.438 (0.069)    | -         |     5.83 | based, Experative, nicx, Nyyx, ogwizard |
|           13 |     3435 | 2024-03-20 | Phoenix          | L   | 0.290      | -            | -                | -                | -         |    -6.00 | based, Experative, nicx, Nyyx, ogwizard |
|           12 |     3437 | 2024-03-20 | Phoenix          | W   | 0.289      | -            | -                | -                | -         |     3.16 | based, Experative, nicx, Nyyx, ogwizard |
|           11 |     3480 | 2024-03-17 | Akimbo           | W   | 0.270      | -            | -                | -                | 1 (0.270) |     3.30 | based, Experative, nicx, Nyyx, ogwizard |
|           10 |     3482 | 2024-03-17 | Akimbo           | W   | 0.269      | -            | -                | -                | 1 (0.269) |     2.35 | based, Experative, nicx, Nyyx, ogwizard |
|            9 |     3492 | 2024-03-17 | WICKED           | W   | 0.268      | -            | -                | -                | 1 (0.268) |     1.68 | based, Experative, nicx, Nyyx, ogwizard |
|            8 |     3730 | 2024-03-07 | FLUFFY AIMERS    | W   | 0.203      | -            | -                | -                | -         |     2.57 | based, Experative, nicx, Nyyx, ogwizard |
|            7 |     3731 | 2024-03-07 | FLUFFY AIMERS    | L   | 0.203      | -            | -                | -                | -         |    -3.88 | based, Experative, nicx, Nyyx, ogwizard |
|            6 |     3758 | 2024-03-06 | MIGHT            | W   | 0.197      | -            | -                | -                | -         |     1.02 | based, Experative, nicx, Nyyx, ogwizard |
|            5 |     3759 | 2024-03-06 | MIGHT            | L   | 0.196      | -            | -                | -                | -         |    -5.21 | based, Experative, nicx, Nyyx, ogwizard |
|            4 |     3796 | 2024-03-05 | Take Flyte       | W   | 0.190      | -            | -                | -                | -         |     1.96 | based, Experative, nicx, Nyyx, ogwizard |
|            3 |     3798 | 2024-03-05 | Take Flyte       | W   | 0.190      | -            | -                | -                | -         |     1.99 | based, Experative, nicx, Nyyx, ogwizard |
|            2 |     4009 | 2024-02-24 | Limitless        | L   | 0.122      | -            | -                | -                | -         |    -2.83 | based, Experative, nicx, Nyyx, ogwizard |
|            1 |     4199 | 2024-02-16 | FLUFFY AIMERS    | L   | 0.069      | -            | -                | -                | -         |    -1.33 | based, Experative, nicx, Nyyx, ogwizard |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,971.71)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.829 | $3,000.00      | $2,487.22       |
| 2024-03-17 |      0.270 | $5,500.00      | $1,484.49       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
