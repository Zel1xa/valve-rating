### Roster Details<br />
Team Name: Sangal<br />
Roster: Chill, LNZ, SaMey, xfl0ud, yxngstxr<br />
Global Rank: [27](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [21]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1282.9<br />
<br />
Final Rank Value (1282.9) = Starting Rank Value (1159.8) + Head To Head Adjustments (123.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.603[<sup>1</sup>](#table2)
- Bounty Collected: 0.501[<sup>2</sup>](#table1)
- Opponent Network: 0.378[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.371<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1159.8
- 400 + ( ( 0.371 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1159.8


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
|           68 |       16 | 2024-08-05 | 1WIN              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.75 | Chill, LNZ, SaMey, xfl0ud, yxngstxr     |
|           67 |       72 | 2024-08-03 | Passion UA        | W   | 1.000      | 0.435        | 0.173 (0.075)    | 1.000 (0.435)    | 0 (0.000) |     8.62 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           66 |      241 | 2024-07-30 | SINNERS           | W   | 1.000      | 0.500        | -                | 0.809 (0.404)    | 0 (0.000) |     5.31 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           65 |      295 | 2024-07-28 | fnatic            | W   | 1.000      | 0.435        | 0.371 (0.161)    | 0.697 (0.303)    | 0 (0.000) |    23.68 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           64 |      311 | 2024-07-28 | Monte             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.73 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           63 |      333 | 2024-07-27 | B8                | W   | 1.000      | 0.435        | 0.165 (0.072)    | 0.935 (0.406)    | 0 (0.000) |    12.83 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           62 |      347 | 2024-07-26 | Permitta          | W   | 1.000      | 0.435        | -                | 0.863 (0.375)    | 0 (0.000) |     4.40 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           61 |      462 | 2024-07-23 | brazylijski luz   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.75 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           60 |      562 | 2024-07-20 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -6.98 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           59 |      691 | 2024-07-17 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -17.56 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           58 |      705 | 2024-07-17 | B8                | W   | 1.000      | 0.500        | 0.165 (0.082)    | 0.935 (0.468)    | 0 (0.000) |    13.47 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           57 |      799 | 2024-07-15 | RUSH B            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.33 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           56 |      816 | 2024-07-15 | Rebels            | W   | 1.000      | -            | -                | -                | -         |     7.87 | imoRR, jottAAA, SaMey, xfl0ud, yxngstxr |
|           55 |     1244 | 2024-06-09 | KOI               | W   | 0.820      | -            | -                | -                | -         |     8.41 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           54 |     1310 | 2024-06-08 | SINNERS           | W   | 0.813      | 0.500        | -                | 0.809 (0.329)    | -         |     7.15 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           53 |     1363 | 2024-06-07 | Aurora            | W   | 0.807      | 0.500        | 0.422 (0.170)    | 0.779 (0.314)    | -         |    22.07 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           52 |     1430 | 2024-06-06 | 3DMAX             | W   | 0.800      | 0.500        | 0.508 (0.203)    | 1.000 (0.400)    | -         |    22.15 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           51 |     1490 | 2024-06-05 | SAW               | W   | 0.793      | 0.500        | 0.105 (0.041)    | -                | -         |    13.59 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           50 |     1541 | 2024-06-04 | 9 Pandas          | W   | 0.787      | -            | -                | -                | -         |    10.23 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           49 |     1654 | 2024-05-31 | SAW               | L   | 0.760      | -            | -                | -                | -         |    -9.43 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           48 |     1657 | 2024-05-31 | FAVBET            | W   | 0.760      | -            | -                | -                | -         |     3.04 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           47 |     1661 | 2024-05-31 | fnatic            | L   | 0.759      | -            | -                | -                | -         |    -3.19 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           46 |     1689 | 2024-05-30 | MOUZ NXT          | L   | 0.751      | -            | -                | -                | -         |   -13.84 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           45 |     1861 | 2024-05-22 | Zero Tenacity     | W   | 0.699      | 0.500        | 0.143 (0.050)    | 1.000 (0.350)    | -         |    10.06 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           44 |     1908 | 2024-05-21 | Monte             | W   | 0.692      | -            | -                | -                | -         |     8.02 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           43 |     1943 | 2024-05-20 | PARIVISION        | W   | 0.685      | -            | -                | -                | -         |     9.70 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           42 |     1958 | 2024-05-19 | Ninjas in Pyjamas | W   | 0.680      | 0.500        | 0.254 (0.086)    | -                | -         |    19.92 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           41 |     1965 | 2024-05-19 | Endpoint          | W   | 0.679      | -            | -                | -                | -         |     6.16 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           40 |     2000 | 2024-05-18 | Rare Atom         | W   | 0.672      | -            | -                | -                | -         |     4.19 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           39 |     2042 | 2024-05-17 | Permitta          | W   | 0.664      | -            | -                | -                | -         |     5.35 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           38 |     2055 | 2024-05-16 | Ninjas in Pyjamas | L   | 0.660      | -            | -                | -                | -         |    -1.14 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           37 |     2122 | 2024-05-15 | Verdant           | L   | 0.652      | -            | -                | -                | -         |   -15.07 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           36 |     2185 | 2024-05-14 | DMS               | L   | 0.644      | -            | -                | -                | -         |   -15.32 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           35 |     2431 | 2024-05-02 | Metizport         | L   | 0.566      | -            | -                | -                | -         |   -14.14 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           34 |     2464 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.558      | -            | -                | -                | -         |   -12.72 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           33 |     2474 | 2024-04-30 | Zero Tenacity     | W   | 0.553      | -            | -                | -                | -         |     7.08 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           32 |     2506 | 2024-04-29 | SINNERS           | W   | 0.544      | -            | -                | -                | -         |     7.77 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           31 |     2513 | 2024-04-28 | 1WIN              | W   | 0.540      | -            | -                | -                | -         |     4.75 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           30 |     2537 | 2024-04-27 | PARIVISION        | L   | 0.533      | -            | -                | -                | -         |    -9.52 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           29 |     2571 | 2024-04-26 | Nemiga            | W   | 0.525      | 0.435        | 0.316 (0.072)    | -                | -         |     9.50 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           28 |     2643 | 2024-04-23 | Grannys Knockers  | W   | 0.504      | -            | -                | -                | -         |     1.74 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           27 |     2648 | 2024-04-22 | BLEED             | L   | 0.499      | -            | -                | -                | -         |    -9.56 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           26 |     2659 | 2024-04-22 | ex-Guild Eagles   | L   | 0.497      | -            | -                | -                | -         |   -13.22 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           25 |     2674 | 2024-04-21 | Alliance          | W   | 0.491      | -            | -                | -                | -         |     2.67 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           24 |     2693 | 2024-04-20 | brazylijski luz   | W   | 0.486      | -            | -                | -                | -         |     2.29 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           23 |     2709 | 2024-04-20 | JANO              | W   | 0.484      | -            | -                | -                | -         |     1.12 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           22 |     2728 | 2024-04-19 | TSM               | W   | 0.480      | -            | -                | -                | -         |     1.09 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           21 |     2740 | 2024-04-19 | Nemiga            | L   | 0.479      | -            | -                | -                | -         |    -7.04 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           20 |     2848 | 2024-04-17 | 9 Pandas          | W   | 0.464      | -            | -                | -                | -         |     4.41 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           19 |     2860 | 2024-04-16 | Zero Tenacity     | W   | 0.460      | -            | -                | -                | -         |     5.78 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           18 |     2881 | 2024-04-15 | B8                | W   | 0.454      | -            | -                | -                | -         |     5.55 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           17 |     2885 | 2024-04-15 | Aurora Young Blud | W   | 0.453      | -            | -                | -                | -         |     2.72 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           16 |     2926 | 2024-04-12 | Monte             | L   | 0.433      | -            | -                | -                | -         |    -9.48 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           15 |     3179 | 2024-04-04 | EYEBALLERS        | W   | 0.380      | -            | -                | -                | -         |     2.55 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           14 |     3262 | 2024-04-02 | 9 Pandas          | L   | 0.367      | -            | -                | -                | -         |    -7.91 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           13 |     3619 | 2024-03-13 | KOI               | L   | 0.234      | -            | -                | -                | -         |    -4.33 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           12 |     3728 | 2024-03-09 | Zero Tenacity     | L   | 0.206      | -            | -                | -                | -         |    -3.67 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           11 |     3777 | 2024-03-07 | 500               | L   | 0.193      | -            | -                | -                | -         |    -5.59 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           10 |     3797 | 2024-03-06 | TSM               | W   | 0.187      | -            | -                | -                | -         |     0.37 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            9 |     3867 | 2024-03-04 | Sampi             | W   | 0.172      | -            | -                | -                | -         |     0.98 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            8 |     3893 | 2024-03-03 | Rebels            | L   | 0.166      | -            | -                | -                | -         |    -3.73 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            7 |     3920 | 2024-03-02 | HAVU              | W   | 0.158      | -            | -                | -                | -         |     0.37 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            6 |     3941 | 2024-02-29 | Rebels            | L   | 0.146      | -            | -                | -                | -         |    -3.32 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            5 |     3962 | 2024-02-28 | Alliance          | L   | 0.138      | -            | -                | -                | -         |    -3.70 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            4 |     3969 | 2024-02-27 | 9INE              | W   | 0.134      | -            | -                | -                | -         |     0.12 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            3 |     4015 | 2024-02-25 | Sashi             | W   | 0.120      | -            | -                | -                | -         |     1.88 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            2 |     4191 | 2024-02-18 | 500               | W   | 0.071      | -            | -                | -                | -         |     0.16 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            1 |     4394 | 2024-02-08 | AURA              | L   | 0.006      | -            | -                | -                | -         |    -0.19 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($70,496.49)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $22,000.00     | $22,000.00      |
| 2024-06-09 |      0.820 | $16,500.00     | $13,524.27      |
| 2024-05-22 |      0.699 | $50,000.00     | $34,972.22      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
