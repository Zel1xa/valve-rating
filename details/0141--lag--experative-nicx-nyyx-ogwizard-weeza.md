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
Final Rank Value (754.6) = Starting Rank Value (838.7) + Head To Head Adjustments (-84.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.343[<sup>1</sup>](#table2)
- Bounty Collected: 0.312[<sup>2</sup>](#table1)
- Opponent Network: 0.110[<sup>2</sup>](#table1)
- LAN Wins: 0.090[<sup>2</sup>](#table1)

The average of these factors is 0.214<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 838.7
- 400 + ( ( 0.214 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 838.7


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
|           55 |      158 | 2024-07-31 | E-Xolos LAZER    | L   | 1.000      | -            | -                | -                | -         |   -13.26 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           54 |      163 | 2024-07-31 | E-Xolos LAZER    | L   | 1.000      | -            | -                | -                | -         |   -14.46 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           53 |      254 | 2024-07-29 | Revenge Nation   | L   | 1.000      | -            | -                | -                | -         |   -19.52 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           52 |      379 | 2024-07-25 | Detonate         | L   | 1.000      | -            | -                | -                | -         |   -26.01 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           51 |      405 | 2024-07-24 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | 0.131 (0.063)    | 0 (0.000) |     9.57 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           50 |      408 | 2024-07-24 | Limitless        | W   | 1.000      | 0.477        | 0.005 (0.002)    | 0.131 (0.063)    | 0 (0.000) |    10.33 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           49 |      528 | 2024-07-20 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -8.77 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           48 |      662 | 2024-07-17 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -16.36 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           47 |      669 | 2024-07-17 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -17.86 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           46 |      730 | 2024-07-16 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -17.99 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           45 |      736 | 2024-07-16 | Wildcard         | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.235 (0.112)    | 0 (0.000) |    13.31 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           44 |      777 | 2024-07-15 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.513 (0.245)    | 0 (0.000) |    20.24 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           43 |      781 | 2024-07-15 | Elevate          | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.513 (0.245)    | 0 (0.000) |    21.89 | Experative, nicx, Nyyx, ogwizard, Weeza |
|           42 |     1118 | 2024-06-13 | Mythic           | L   | 0.848      | -            | -                | -                | -         |   -13.68 | based, Experative, nicx, Nyyx, ogwizard |
|           41 |     1290 | 2024-06-08 | Homyno           | W   | 0.815      | 0.371        | 0.007 (0.002)    | -                | 0 (0.000) |     8.72 | based, Experative, nicx, Nyyx, ogwizard |
|           40 |     1345 | 2024-06-07 | Wildcard         | L   | 0.808      | -            | -                | -                | -         |    -8.68 | based, Experative, nicx, Nyyx, ogwizard |
|           39 |     1427 | 2024-06-06 | Vibe             | W   | 0.800      | -            | -                | -                | 0 (0.000) |     2.29 | based, Experative, nicx, Nyyx, ogwizard |
|           38 |     1469 | 2024-06-05 | NRG              | L   | 0.795      | -            | -                | -                | -         |   -10.09 | based, Experative, nicx, Nyyx, ogwizard |
|           37 |     1479 | 2024-06-05 | Limitless        | W   | 0.794      | -            | -                | -                | -         |    10.44 | based, Experative, nicx, Nyyx, ogwizard |
|           36 |     1521 | 2024-06-04 | Limitless        | W   | 0.789      | -            | -                | -                | -         |    11.11 | based, Experative, nicx, Nyyx, ogwizard |
|           35 |     1531 | 2024-06-04 | Retirement Home  | W   | 0.788      | -            | -                | -                | -         |     2.24 | based, Experative, nicx, Nyyx, ogwizard |
|           34 |     1836 | 2024-05-22 | Limitless        | W   | 0.702      | -            | -                | -                | -         |     5.56 | based, Experative, nicx, Nyyx, ogwizard |
|           33 |     1839 | 2024-05-22 | Limitless        | W   | 0.702      | -            | -                | -                | -         |     5.83 | based, Experative, nicx, Nyyx, ogwizard |
|           32 |     1844 | 2024-05-22 | Wildcard         | L   | 0.701      | -            | -                | -                | -         |    -7.58 | based, Experative, nicx, Nyyx, ogwizard |
|           31 |     2087 | 2024-05-15 | NRG              | L   | 0.655      | -            | -                | -                | -         |    -7.33 | based, Experative, nicx, Nyyx, ogwizard |
|           30 |     2094 | 2024-05-15 | NRG              | L   | 0.655      | -            | -                | -                | -         |    -7.74 | based, Experative, nicx, Nyyx, ogwizard |
|           29 |     2140 | 2024-05-14 | Limitless        | W   | 0.649      | -            | -                | -                | -         |     8.52 | based, Experative, nicx, Nyyx, ogwizard |
|           28 |     2146 | 2024-05-14 | Limitless        | L   | 0.648      | -            | -                | -                | -         |   -12.21 | based, Experative, nicx, Nyyx, ogwizard |
|           27 |     2281 | 2024-05-09 | M80              | L   | 0.615      | -            | -                | -                | -         |    -1.70 | based, Experative, nicx, Nyyx, ogwizard |
|           26 |     2286 | 2024-05-09 | M80              | L   | 0.615      | -            | -                | -                | -         |    -1.73 | based, Experative, nicx, Nyyx, ogwizard |
|           25 |     2301 | 2024-05-08 | Party Astronauts | L   | 0.609      | -            | -                | -                | -         |    -6.71 | based, Experative, nicx, Nyyx, ogwizard |
|           24 |     2306 | 2024-05-08 | Party Astronauts | L   | 0.608      | -            | -                | -                | -         |    -7.05 | based, Experative, nicx, Nyyx, ogwizard |
|           23 |     2968 | 2024-04-10 | Mythic           | W   | 0.422      | 0.477        | 0.010 (0.002)    | 0.293 (0.059)    | -         |     5.53 | based, Experative, nicx, Nyyx, ogwizard |
|           22 |     2973 | 2024-04-10 | Mythic           | W   | 0.422      | 0.477        | -                | 0.293 (0.059)    | -         |     5.74 | based, Experative, nicx, Nyyx, ogwizard |
|           21 |     3024 | 2024-04-09 | BOSS             | L   | 0.415      | -            | -                | -                | -         |    -7.06 | based, Experative, nicx, Nyyx, ogwizard |
|           20 |     3027 | 2024-04-09 | BOSS             | L   | 0.415      | -            | -                | -                | -         |    -7.32 | based, Experative, nicx, Nyyx, ogwizard |
|           19 |     3155 | 2024-04-04 | Nouns            | W   | 0.382      | 0.477        | 0.057 (0.010)    | 0.553 (0.101)    | -         |     7.34 | based, Experative, nicx, Nyyx, ogwizard |
|           18 |     3159 | 2024-04-04 | Nouns            | L   | 0.382      | -            | -                | -                | -         |    -4.77 | based, Experative, nicx, Nyyx, ogwizard |
|           17 |     3201 | 2024-04-03 | Elevate          | L   | 0.375      | -            | -                | -                | -         |    -3.59 | based, Experative, nicx, Nyyx, ogwizard |
|           16 |     3203 | 2024-04-03 | Elevate          | W   | 0.375      | 0.477        | 0.027 (0.005)    | 0.513 (0.092)    | -         |     8.40 | based, Experative, nicx, Nyyx, ogwizard |
|           15 |     3377 | 2024-03-26 | Wildcard         | L   | 0.322      | -            | -                | -                | -         |    -4.58 | based, Experative, nicx, Nyyx, ogwizard |
|           14 |     3382 | 2024-03-26 | Wildcard         | W   | 0.322      | 0.477        | 0.048 (0.007)    | 0.429 (0.066)    | -         |     5.69 | based, Experative, nicx, Nyyx, ogwizard |
|           13 |     3462 | 2024-03-20 | Phoenix          | L   | 0.282      | -            | -                | -                | -         |    -5.83 | based, Experative, nicx, Nyyx, ogwizard |
|           12 |     3464 | 2024-03-20 | Phoenix          | W   | 0.282      | -            | -                | -                | -         |     3.10 | based, Experative, nicx, Nyyx, ogwizard |
|           11 |     3507 | 2024-03-17 | Akimbo           | W   | 0.262      | -            | -                | -                | 1 (0.262) |     3.23 | based, Experative, nicx, Nyyx, ogwizard |
|           10 |     3509 | 2024-03-17 | Akimbo           | W   | 0.261      | -            | -                | -                | 1 (0.261) |     2.30 | based, Experative, nicx, Nyyx, ogwizard |
|            9 |     3519 | 2024-03-17 | WICKED           | W   | 0.260      | -            | -                | -                | 1 (0.260) |     1.64 | based, Experative, nicx, Nyyx, ogwizard |
|            8 |     3757 | 2024-03-07 | FLUFFY AIMERS    | W   | 0.196      | -            | -                | -                | -         |     2.48 | based, Experative, nicx, Nyyx, ogwizard |
|            7 |     3758 | 2024-03-07 | FLUFFY AIMERS    | L   | 0.195      | -            | -                | -                | -         |    -3.73 | based, Experative, nicx, Nyyx, ogwizard |
|            6 |     3785 | 2024-03-06 | MIGHT            | W   | 0.189      | -            | -                | -                | -         |     0.98 | based, Experative, nicx, Nyyx, ogwizard |
|            5 |     3786 | 2024-03-06 | MIGHT            | L   | 0.189      | -            | -                | -                | -         |    -5.00 | based, Experative, nicx, Nyyx, ogwizard |
|            4 |     3823 | 2024-03-05 | Take Flyte       | W   | 0.182      | -            | -                | -                | -         |     1.89 | based, Experative, nicx, Nyyx, ogwizard |
|            3 |     3825 | 2024-03-05 | Take Flyte       | W   | 0.182      | -            | -                | -                | -         |     1.91 | based, Experative, nicx, Nyyx, ogwizard |
|            2 |     4036 | 2024-02-24 | Limitless        | L   | 0.115      | -            | -                | -                | -         |    -2.65 | based, Experative, nicx, Nyyx, ogwizard |
|            1 |     4226 | 2024-02-16 | FLUFFY AIMERS    | L   | 0.061      | -            | -                | -                | -         |    -1.18 | based, Experative, nicx, Nyyx, ogwizard |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,907.57)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.822 | $3,000.00      | $2,464.58       |
| 2024-03-17 |      0.262 | $5,500.00      | $1,442.99       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
