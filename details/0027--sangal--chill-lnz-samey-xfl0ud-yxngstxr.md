### Roster Details<br />
Team Name: Sangal<br />
Roster: Chill, LNZ, SaMey, xfl0ud, yxngstxr<br />
Global Rank: [27](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [21]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1284.2<br />
<br />
Final Rank Value (1284.2) = Starting Rank Value (1161.3) + Head To Head Adjustments (122.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.603[<sup>1</sup>](#table2)
- Bounty Collected: 0.501[<sup>2</sup>](#table1)
- Opponent Network: 0.380[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.371<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1161.3
- 400 + ( ( 0.371 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1161.3


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
|           68 |       23 | 2024-08-05 | 1WIN              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.77 | Chill, LNZ, SaMey, xfl0ud, yxngstxr     |
|           67 |       79 | 2024-08-03 | Passion UA        | W   | 1.000      | 0.435        | 0.173 (0.075)    | 1.000 (0.435)    | 0 (0.000) |     8.64 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           66 |      248 | 2024-07-30 | SINNERS           | W   | 1.000      | 0.500        | -                | 0.808 (0.404)    | 0 (0.000) |     5.31 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           65 |      302 | 2024-07-28 | fnatic            | W   | 1.000      | 0.435        | 0.371 (0.161)    | 0.695 (0.302)    | 0 (0.000) |    23.64 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           64 |      318 | 2024-07-28 | Monte             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.73 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           63 |      340 | 2024-07-27 | B8                | W   | 1.000      | 0.435        | 0.164 (0.071)    | 0.933 (0.405)    | 0 (0.000) |    12.80 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           62 |      354 | 2024-07-26 | Permitta          | W   | 1.000      | 0.435        | -                | 0.940 (0.408)    | 0 (0.000) |     4.57 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           61 |      469 | 2024-07-23 | brazylijski luz   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.72 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           60 |      569 | 2024-07-20 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -7.01 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           59 |      698 | 2024-07-17 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -17.66 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           58 |      712 | 2024-07-17 | B8                | W   | 1.000      | 0.500        | 0.164 (0.082)    | 0.933 (0.466)    | 0 (0.000) |    13.43 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           57 |      806 | 2024-07-15 | RUSH B            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.29 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           56 |      823 | 2024-07-15 | Rebels            | W   | 1.000      | -            | -                | -                | -         |     7.86 | imoRR, jottAAA, SaMey, xfl0ud, yxngstxr |
|           55 |     1251 | 2024-06-09 | KOI               | W   | 0.815      | -            | -                | -                | -         |     8.29 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           54 |     1317 | 2024-06-08 | SINNERS           | W   | 0.809      | 0.500        | -                | 0.808 (0.327)    | -         |     7.09 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           53 |     1370 | 2024-06-07 | Aurora            | W   | 0.802      | 0.500        | 0.421 (0.169)    | 0.776 (0.311)    | -         |    21.95 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           52 |     1437 | 2024-06-06 | 3DMAX             | W   | 0.795      | 0.500        | 0.509 (0.203)    | 1.000 (0.398)    | -         |    22.05 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           51 |     1497 | 2024-06-05 | SAW               | W   | 0.789      | 0.500        | 0.104 (0.041)    | -                | -         |    13.38 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           50 |     1548 | 2024-06-04 | 9 Pandas          | W   | 0.782      | -            | -                | -                | -         |    10.09 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           49 |     1661 | 2024-05-31 | SAW               | L   | 0.755      | -            | -                | -                | -         |    -9.52 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           48 |     1664 | 2024-05-31 | FAVBET            | W   | 0.755      | -            | -                | -                | -         |     3.00 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           47 |     1668 | 2024-05-31 | fnatic            | L   | 0.754      | -            | -                | -                | -         |    -3.21 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           46 |     1696 | 2024-05-30 | MOUZ NXT          | L   | 0.746      | -            | -                | -                | -         |   -13.80 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           45 |     1868 | 2024-05-22 | Zero Tenacity     | W   | 0.695      | 0.500        | 0.143 (0.050)    | 1.000 (0.347)    | -         |    10.07 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           44 |     1915 | 2024-05-21 | Monte             | W   | 0.687      | -            | -                | -                | -         |     7.92 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           43 |     1950 | 2024-05-20 | PARIVISION        | W   | 0.681      | -            | -                | -                | -         |     9.62 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           42 |     1965 | 2024-05-19 | Ninjas in Pyjamas | W   | 0.676      | 0.500        | 0.254 (0.086)    | -                | -         |    19.77 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           41 |     1972 | 2024-05-19 | Endpoint          | W   | 0.674      | -            | -                | -                | -         |     6.08 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           40 |     2007 | 2024-05-18 | Rare Atom         | W   | 0.667      | -            | -                | -                | -         |     4.20 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           39 |     2049 | 2024-05-17 | Permitta          | W   | 0.659      | -            | -                | -                | -         |     5.43 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           38 |     2062 | 2024-05-16 | Ninjas in Pyjamas | L   | 0.656      | -            | -                | -                | -         |    -1.15 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           37 |     2129 | 2024-05-15 | Verdant           | L   | 0.647      | -            | -                | -                | -         |   -15.01 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           36 |     2192 | 2024-05-14 | DMS               | L   | 0.639      | -            | -                | -                | -         |   -15.27 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           35 |     2438 | 2024-05-02 | Metizport         | L   | 0.561      | -            | -                | -                | -         |   -13.17 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           34 |     2471 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.553      | -            | -                | -                | -         |   -12.63 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           33 |     2481 | 2024-04-30 | Zero Tenacity     | W   | 0.548      | -            | -                | -                | -         |     7.00 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           32 |     2513 | 2024-04-29 | SINNERS           | W   | 0.540      | -            | -                | -                | -         |     7.67 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           31 |     2520 | 2024-04-28 | 1WIN              | W   | 0.535      | -            | -                | -                | -         |     4.72 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           30 |     2544 | 2024-04-27 | PARIVISION        | L   | 0.528      | -            | -                | -                | -         |    -9.43 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           29 |     2578 | 2024-04-26 | Nemiga            | W   | 0.520      | 0.435        | 0.315 (0.071)    | -                | -         |     9.35 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           28 |     2650 | 2024-04-23 | Grannys Knockers  | W   | 0.499      | -            | -                | -                | -         |     1.71 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           27 |     2655 | 2024-04-22 | BLEED             | L   | 0.495      | -            | -                | -                | -         |    -9.53 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           26 |     2666 | 2024-04-22 | ex-Guild Eagles   | L   | 0.493      | -            | -                | -                | -         |   -13.10 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           25 |     2681 | 2024-04-21 | Alliance          | W   | 0.486      | -            | -                | -                | -         |     2.62 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           24 |     2700 | 2024-04-20 | brazylijski luz   | W   | 0.482      | -            | -                | -                | -         |     2.24 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           23 |     2716 | 2024-04-20 | JANO              | W   | 0.479      | -            | -                | -                | -         |     1.10 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           22 |     2735 | 2024-04-19 | TSM               | W   | 0.476      | -            | -                | -                | -         |     1.06 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           21 |     2747 | 2024-04-19 | Nemiga            | L   | 0.475      | -            | -                | -                | -         |    -7.04 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           20 |     2855 | 2024-04-17 | 9 Pandas          | W   | 0.460      | -            | -                | -                | -         |     4.31 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           19 |     2867 | 2024-04-16 | Zero Tenacity     | W   | 0.455      | -            | -                | -                | -         |     5.69 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           18 |     2888 | 2024-04-15 | B8                | W   | 0.449      | -            | -                | -                | -         |     5.47 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           17 |     2892 | 2024-04-15 | Aurora Young Blud | W   | 0.448      | -            | -                | -                | -         |     2.67 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           16 |     2933 | 2024-04-12 | Monte             | L   | 0.428      | -            | -                | -                | -         |    -9.41 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           15 |     3186 | 2024-04-04 | EYEBALLERS        | W   | 0.376      | -            | -                | -                | -         |     2.50 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           14 |     3269 | 2024-04-02 | 9 Pandas          | L   | 0.362      | -            | -                | -                | -         |    -7.87 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           13 |     3626 | 2024-03-13 | KOI               | L   | 0.229      | -            | -                | -                | -         |    -4.28 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           12 |     3735 | 2024-03-09 | Zero Tenacity     | L   | 0.201      | -            | -                | -                | -         |    -3.60 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           11 |     3784 | 2024-03-07 | 500               | L   | 0.188      | -            | -                | -                | -         |    -5.46 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           10 |     3804 | 2024-03-06 | TSM               | W   | 0.182      | -            | -                | -                | -         |     0.36 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            9 |     3874 | 2024-03-04 | Sampi             | W   | 0.167      | -            | -                | -                | -         |     0.95 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            8 |     3900 | 2024-03-03 | Rebels            | L   | 0.162      | -            | -                | -                | -         |    -3.63 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            7 |     3927 | 2024-03-02 | HAVU              | W   | 0.153      | -            | -                | -                | -         |     0.35 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            6 |     3948 | 2024-02-29 | Rebels            | L   | 0.142      | -            | -                | -                | -         |    -3.21 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            5 |     3969 | 2024-02-28 | Alliance          | L   | 0.134      | -            | -                | -                | -         |    -3.58 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            4 |     3976 | 2024-02-27 | 9INE              | W   | 0.129      | -            | -                | -                | -         |     0.11 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            3 |     4022 | 2024-02-25 | Sashi             | W   | 0.116      | -            | -                | -                | -         |     1.79 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            2 |     4198 | 2024-02-18 | 500               | W   | 0.067      | -            | -                | -                | -         |     0.15 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            1 |     4401 | 2024-02-08 | AURA              | L   | 0.001      | -            | -                | -                | -         |    -0.04 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($70,182.47)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $22,000.00     | $22,000.00      |
| 2024-06-09 |      0.815 | $16,500.00     | $13,446.35      |
| 2024-05-22 |      0.695 | $50,000.00     | $34,736.11      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
