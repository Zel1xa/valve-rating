### Roster Details<br />
Team Name: Sangal<br />
Roster: jottAAA, LNZ, SaMey, xfl0ud, yxngstxr<br />
Global Rank: [18](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [14]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1383.6<br />
<br />
Final Rank Value (1383.6) = Starting Rank Value (1316.2) + Head To Head Adjustments (67.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.623[<sup>1</sup>](#table2)
- Bounty Collected: 0.546[<sup>2</sup>](#table1)
- Opponent Network: 0.413[<sup>2</sup>](#table1)
- LAN Wins: 0.312[<sup>2</sup>](#table1)

The average of these factors is 0.473<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1316.2
- 400 + ( ( 0.473 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 1316.2


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
|           69 |       24 | 2024-09-07 | FlyQuest          | W   | 1.000      | 0.889        | 0.109 (0.097)    | -                | 1 (1.000) |     4.51 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           68 |       45 | 2024-09-06 | FaZe              | L   | 1.000      | -            | -                | -                | -         |    -4.52 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           67 |       73 | 2024-09-05 | HEROIC            | W   | 1.000      | 0.889        | 0.205 (0.182)    | 0.412 (0.366)    | 1 (1.000) |    15.48 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           66 |      120 | 2024-09-04 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -3.35 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           65 |      154 | 2024-09-03 | FaZe              | W   | 1.000      | 0.889        | 0.587 (0.522)    | 0.494 (0.439)    | 1 (1.000) |    27.63 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           64 |      588 | 2024-08-22 | BLEED             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.77 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           63 |      639 | 2024-08-21 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.29 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           62 |      671 | 2024-08-21 | 1WIN              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.58 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           61 |      827 | 2024-08-15 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |   -20.96 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           60 |      919 | 2024-08-12 | Zero Tenacity     | W   | 1.000      | 0.500        | 0.163 (0.082)    | 1.000 (0.500)    | 0 (0.000) |     4.69 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           59 |     1069 | 2024-08-07 | Rebels            | W   | 0.987      | 0.500        | -                | 0.656 (0.324)    | 0 (0.000) |     2.65 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           58 |     1113 | 2024-08-06 | PARIVISION        | W   | 0.981      | -            | -                | -                | 0 (0.000) |     6.08 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           57 |     1121 | 2024-08-06 | Permitta          | W   | 0.980      | 0.435        | -                | 0.968 (0.412)    | 0 (0.000) |     3.38 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           56 |     1155 | 2024-08-05 | 1WIN              | W   | 0.972      | -            | -                | -                | -         |     3.58 | Chill, LNZ, SaMey, xfl0ud, yxngstxr     |
|           55 |     1211 | 2024-08-03 | Passion UA        | W   | 0.960      | 0.435        | -                | 1.000 (0.417)    | -         |     6.05 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           54 |     1381 | 2024-07-30 | SINNERS           | W   | 0.933      | 0.500        | -                | 1.000 (0.467)    | -         |     4.12 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           53 |     1434 | 2024-07-28 | fnatic            | W   | 0.921      | 0.435        | 0.294 (0.117)    | -                | -         |    15.52 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           52 |     1450 | 2024-07-28 | Monte             | W   | 0.919      | -            | -                | -                | -         |     4.17 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           51 |     1472 | 2024-07-27 | B8                | W   | 0.912      | 0.435        | 0.176 (0.070)    | 1.000 (0.396)    | -         |     7.48 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           50 |     1486 | 2024-07-26 | Permitta          | W   | 0.907      | 0.435        | -                | 0.968 (0.382)    | -         |     2.72 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           49 |     1601 | 2024-07-23 | Apogee            | W   | 0.887      | -            | -                | -                | -         |     1.57 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           48 |     1701 | 2024-07-20 | fnatic            | L   | 0.866      | -            | -                | -                | -         |   -13.45 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           47 |     1830 | 2024-07-17 | SAW               | L   | 0.848      | -            | -                | -                | -         |    -9.41 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           46 |     1844 | 2024-07-17 | B8                | W   | 0.847      | 0.500        | 0.176 (0.074)    | 1.000 (0.424)    | -         |     6.91 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           45 |     1941 | 2024-07-15 | RUSH B            | W   | 0.835      | -            | -                | -                | -         |     2.48 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           44 |     1958 | 2024-07-15 | Rebels            | W   | 0.832      | -            | -                | -                | -         |     3.25 | imoRR, jottAAA, SaMey, xfl0ud, yxngstxr |
|           43 |     2386 | 2024-06-09 | KOI               | W   | 0.594      | -            | -                | -                | -         |     2.47 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           42 |     2452 | 2024-06-08 | SINNERS           | W   | 0.588      | -            | -                | -                | -         |     3.62 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           41 |     2505 | 2024-06-07 | Aurora            | W   | 0.581      | 0.500        | 0.290 (0.084)    | -                | -         |    11.14 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           40 |     2572 | 2024-06-06 | 3DMAX             | W   | 0.574      | 0.500        | 0.509 (0.146)    | -                | -         |    15.77 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           39 |     2632 | 2024-06-05 | SAW               | W   | 0.568      | 0.500        | 0.330 (0.094)    | -                | -         |    13.51 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           38 |     2683 | 2024-06-04 | 9 Pandas          | W   | 0.561      | -            | -                | -                | -         |     4.46 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           37 |     2796 | 2024-05-31 | SAW               | L   | 0.534      | -            | -                | -                | -         |    -3.47 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           36 |     2799 | 2024-05-31 | FAVBET            | W   | 0.534      | -            | -                | -                | -         |     1.23 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           35 |     2803 | 2024-05-31 | fnatic            | L   | 0.533      | -            | -                | -                | -         |    -7.60 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           34 |     2831 | 2024-05-30 | MOUZ NXT          | L   | 0.526      | -            | -                | -                | -         |   -13.32 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           33 |     3003 | 2024-05-22 | Zero Tenacity     | W   | 0.474      | -            | -                | -                | -         |     3.81 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           32 |     3050 | 2024-05-21 | Monte             | W   | 0.466      | -            | -                | -                | -         |     2.53 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           31 |     3085 | 2024-05-20 | PARIVISION        | W   | 0.460      | -            | -                | -                | -         |     3.72 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           30 |     3100 | 2024-05-19 | Ninjas in Pyjamas | W   | 0.455      | -            | -                | -                | -         |     9.76 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           29 |     3107 | 2024-05-19 | Endpoint          | W   | 0.453      | -            | -                | -                | -         |     2.97 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           28 |     3142 | 2024-05-18 | Rare Atom         | W   | 0.446      | -            | -                | -                | -         |     1.24 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           27 |     3184 | 2024-05-17 | Permitta          | W   | 0.439      | -            | -                | -                | -         |     1.71 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           26 |     3197 | 2024-05-16 | Ninjas in Pyjamas | L   | 0.435      | -            | -                | -                | -         |    -4.09 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           25 |     3264 | 2024-05-15 | Verdant           | L   | 0.426      | -            | -                | -                | -         |   -12.17 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           24 |     3327 | 2024-05-14 | DMS               | L   | 0.419      | -            | -                | -                | -         |   -11.94 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           23 |     3573 | 2024-05-02 | Metizport         | L   | 0.340      | -            | -                | -                | -         |   -10.17 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           22 |     3606 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.332      | -            | -                | -                | -         |    -8.57 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           21 |     3616 | 2024-04-30 | Zero Tenacity     | W   | 0.327      | -            | -                | -                | -         |     2.14 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           20 |     3648 | 2024-04-29 | SINNERS           | W   | 0.319      | -            | -                | -                | -         |     2.71 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           19 |     3655 | 2024-04-28 | 1WIN              | W   | 0.314      | -            | -                | -                | -         |     0.97 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           18 |     3679 | 2024-04-27 | PARIVISION        | L   | 0.307      | -            | -                | -                | -         |    -7.55 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           17 |     3713 | 2024-04-26 | Nemiga            | W   | 0.300      | -            | -                | -                | -         |     3.13 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           16 |     3785 | 2024-04-23 | Grannys Knockers  | W   | 0.279      | -            | -                | -                | -         |     0.31 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           15 |     3790 | 2024-04-22 | BLEED             | L   | 0.274      | -            | -                | -                | -         |    -7.85 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           14 |     3801 | 2024-04-22 | ex-Guild Eagles   | L   | 0.272      | -            | -                | -                | -         |    -8.21 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           13 |     3816 | 2024-04-21 | Alliance          | W   | 0.266      | -            | -                | -                | -         |     0.55 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           12 |     3835 | 2024-04-20 | Apogee            | W   | 0.261      | -            | -                | -                | -         |     0.36 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           11 |     3851 | 2024-04-20 | JANO              | W   | 0.259      | -            | -                | -                | -         |     0.20 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           10 |     3870 | 2024-04-19 | TSM               | W   | 0.255      | -            | -                | -                | -         |     0.18 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|            9 |     3882 | 2024-04-19 | Nemiga            | L   | 0.254      | -            | -                | -                | -         |    -5.59 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|            8 |     3990 | 2024-04-17 | 9 Pandas          | W   | 0.239      | -            | -                | -                | -         |     1.25 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|            7 |     4002 | 2024-04-16 | Zero Tenacity     | W   | 0.234      | -            | -                | -                | -         |     1.37 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|            6 |     4023 | 2024-04-15 | B8                | W   | 0.228      | -            | -                | -                | -         |     1.34 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|            5 |     4027 | 2024-04-15 | Aurora Young Blud | W   | 0.227      | -            | -                | -                | -         |     0.70 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|            4 |     4068 | 2024-04-12 | Monte             | L   | 0.207      | -            | -                | -                | -         |    -5.81 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|            3 |     4321 | 2024-04-04 | EYEBALLERS        | W   | 0.155      | -            | -                | -                | -         |     0.27 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|            2 |     4404 | 2024-04-02 | 9 Pandas          | L   | 0.141      | -            | -                | -                | -         |    -3.71 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|            1 |     4761 | 2024-03-13 | KOI               | L   | 0.008      | -            | -                | -                | -         |    -0.23 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($75,339.83)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.25) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-06 |      0.981 | $22,000.00     | $21,581.39      |
| 2024-07-28 |      0.921 | $22,000.00     | $20,261.39      |
| 2024-06-09 |      0.594 | $16,500.00     | $9,802.60       |
| 2024-05-22 |      0.474 | $50,000.00     | $23,694.44      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
