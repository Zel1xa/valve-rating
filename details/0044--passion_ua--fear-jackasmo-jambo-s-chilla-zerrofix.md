### Roster Details<br />
Team Name: Passion UA<br />
Roster: fear, jackasmo, jambo, s-chilla, zeRRoFIX<br />
Global Rank: [44](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [32]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1099.6<br />
<br />
Final Rank Value (1099.6) = Starting Rank Value (1093.0) + Head To Head Adjustments (6.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.567[<sup>1</sup>](#table2)
- Bounty Collected: 0.466[<sup>2</sup>](#table1)
- Opponent Network: 0.314[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.337<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1093.0
- 400 + ( ( 0.337 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1093.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           97 |       10 | 2024-08-01 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.63 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           96 |       92 | 2024-07-30 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.36 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           95 |      127 | 2024-07-29 | Nexus             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.24 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           94 |      139 | 2024-07-29 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -27.77 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           93 |      181 | 2024-07-27 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -12.64 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           92 |      203 | 2024-07-26 | Gaimin Gladiators | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.37 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           91 |      222 | 2024-07-26 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.41 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           90 |      243 | 2024-07-25 | EYEBALLERS        | L   | 1.000      | -            | -                | -                | -         |   -26.66 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           89 |      261 | 2024-07-25 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.36 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           88 |      326 | 2024-07-23 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.08 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           87 |      349 | 2024-07-22 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -7.06 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           86 |      355 | 2024-07-22 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.81 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           85 |      376 | 2024-07-21 | Zero Tenacity     | W   | 1.000      | 0.500        | 0.139 (0.069)    | 1.000 (0.500)    | 0 (0.000) |    15.01 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           84 |      412 | 2024-07-20 | Ninjas in Pyjamas | W   | 1.000      | 0.500        | 0.207 (0.103)    | -                | 0 (0.000) |    28.58 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           83 |      425 | 2024-07-20 | RUBY              | W   | 1.000      | 0.435        | 0.097 (0.042)    | -                | -         |     8.81 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           82 |      448 | 2024-07-19 | Rebels            | W   | 1.000      | -            | -                | -                | -         |    12.49 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           81 |      456 | 2024-07-19 | Nemiga            | W   | 1.000      | 0.500        | 0.324 (0.162)    | 0.697 (0.349)    | -         |    20.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           80 |      517 | 2024-07-18 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.124 (0.046)    | 0.819 (0.303)    | -         |    23.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           79 |      526 | 2024-07-18 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -23.04 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           78 |      585 | 2024-07-17 | Aurora Young Blud | W   | 1.000      | -            | -                | -                | -         |    11.27 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           77 |      650 | 2024-07-16 | Permitta          | W   | 1.000      | 0.371        | -                | 0.801 (0.297)    | -         |    12.14 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           76 |      673 | 2024-07-15 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -9.50 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           75 |      695 | 2024-07-15 | WOPA              | W   | 1.000      | -            | -                | -                | -         |     2.04 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           74 |      713 | 2024-07-14 | Preasy            | W   | 1.000      | -            | -                | -                | -         |     6.75 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           73 |      777 | 2024-07-10 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -18.23 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           72 |      795 | 2024-07-09 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.54 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           71 |      797 | 2024-07-09 | Insilio           | W   | 1.000      | -            | -                | -                | -         |    12.23 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           70 |      817 | 2024-07-08 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.43 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           69 |      980 | 2024-06-14 | 3DMAX             | L   | 0.877      | -            | -                | -                | -         |    -3.08 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           68 |     1074 | 2024-06-10 | Space             | W   | 0.852      | -            | -                | -                | -         |     7.70 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           67 |     1188 | 2024-06-08 | Zero Tenacity     | L   | 0.839      | -            | -                | -                | -         |   -13.28 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           66 |     1257 | 2024-06-07 | Rare Atom         | W   | 0.832      | -            | -                | -                | -         |     2.57 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           65 |     1270 | 2024-06-07 | Aurora Young Blud | W   | 0.831      | -            | -                | -                | -         |     6.75 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           64 |     1344 | 2024-06-06 | Serbia            | W   | 0.824      | -            | -                | -                | -         |     5.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           63 |     1372 | 2024-06-05 | MOUZ NXT          | L   | 0.820      | -            | -                | -                | -         |   -10.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           62 |     1398 | 2024-06-05 | EYEBALLERS        | L   | 0.818      | -            | -                | -                | -         |   -19.42 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           61 |     1428 | 2024-06-04 | Illuminar         | W   | 0.812      | -            | -                | -                | -         |     5.67 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           60 |     1437 | 2024-06-04 | Serbia            | W   | 0.812      | -            | -                | -                | -         |     4.97 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           59 |     1487 | 2024-06-02 | UNiTY             | W   | 0.797      | -            | -                | -                | -         |     9.14 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           58 |     1548 | 2024-05-31 | Zero Tenacity     | L   | 0.785      | -            | -                | -                | -         |   -11.20 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           57 |     1569 | 2024-05-30 | Zero Tenacity     | W   | 0.779      | 0.371        | 0.139 (0.040)    | 1.000 (0.289)    | -         |    13.68 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           56 |     1598 | 2024-05-29 | Illuminar         | W   | 0.771      | -            | -                | -                | -         |     6.64 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           55 |     1671 | 2024-05-25 | Sampi             | W   | 0.746      | 0.435        | -                | 1.000 (0.324)    | -         |     7.70 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           54 |     1692 | 2024-05-24 | FURIA             | L   | 0.739      | -            | -                | -                | -         |    -0.85 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           53 |     1698 | 2024-05-24 | ECSTATIC          | W   | 0.737      | -            | -                | -                | -         |     0.63 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           52 |     1712 | 2024-05-23 | SINNERS           | W   | 0.731      | 0.435        | -                | 0.768 (0.244)    | -         |    11.77 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           51 |     1841 | 2024-05-20 | Sangal            | W   | 0.713      | 0.435        | 0.221 (0.068)    | 0.823 (0.255)    | -         |    14.10 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           50 |     1856 | 2024-05-20 | Permitta          | W   | 0.711      | 0.435        | -                | 0.801 (0.248)    | -         |     7.38 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           49 |     1861 | 2024-05-19 | Illuminar         | L   | 0.708      | -            | -                | -                | -         |   -13.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           48 |     1873 | 2024-05-19 | Sashi             | L   | 0.706      | -            | -                | -                | -         |    -5.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           47 |     1884 | 2024-05-19 | ALTERNATE aTTaX   | W   | 0.704      | -            | -                | -                | -         |     8.14 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           46 |     1904 | 2024-05-18 | 9 Pandas          | L   | 0.699      | -            | -                | -                | -         |   -10.80 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           45 |     1948 | 2024-05-17 | Nexus             | W   | 0.691      | -            | -                | -                | -         |     4.75 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           44 |     1989 | 2024-05-16 | Sashi             | W   | 0.684      | 0.500        | 0.186 (0.064)    | 0.970 (0.332)    | -         |    16.35 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           43 |     2028 | 2024-05-15 | Endpoint          | L   | 0.679      | -            | -                | -                | -         |   -12.65 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           42 |     2088 | 2024-05-14 | SINNERS           | L   | 0.673      | -            | -                | -                | -         |   -10.76 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           41 |     2184 | 2024-05-11 | Preasy            | W   | 0.651      | -            | -                | -                | -         |     4.03 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           40 |     2351 | 2024-05-02 | Nemiga            | L   | 0.593      | -            | -                | -                | -         |    -6.12 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           39 |     2375 | 2024-05-01 | PARIVISION        | W   | 0.586      | -            | -                | -                | -         |    11.01 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           38 |     2413 | 2024-04-30 | 9 Pandas          | W   | 0.578      | -            | -                | -                | -         |     8.18 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           37 |     2440 | 2024-04-28 | ALTERNATE aTTaX   | L   | 0.566      | -            | -                | -                | -         |   -10.45 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           36 |     2491 | 2024-04-26 | 9 Pandas          | W   | 0.552      | -            | -                | -                | -         |     7.71 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           35 |     2527 | 2024-04-25 | Sashi             | L   | 0.545      | -            | -                | -                | -         |    -5.07 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           34 |     2542 | 2024-04-24 | Permitta          | L   | 0.539      | -            | -                | -                | -         |    -9.84 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           33 |     2574 | 2024-04-22 | B8                | L   | 0.527      | -            | -                | -                | -         |    -8.07 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           32 |     2618 | 2024-04-20 | Young Ninjas      | W   | 0.513      | -            | -                | -                | -         |     3.09 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           31 |     2640 | 2024-04-20 | Permitta          | L   | 0.511      | -            | -                | -                | -         |   -10.07 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           30 |     2675 | 2024-04-19 | ALTERNATE aTTaX   | L   | 0.506      | -            | -                | -                | -         |   -10.16 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           29 |     2733 | 2024-04-18 | Permitta          | W   | 0.498      | -            | -                | -                | -         |     5.73 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           28 |     2764 | 2024-04-17 | Sashi             | W   | 0.492      | 0.371        | 0.186 (0.034)    | -                | -         |     9.48 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           27 |     2798 | 2024-04-16 | 500               | L   | 0.486      | -            | -                | -                | -         |   -12.68 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           26 |     2838 | 2024-04-14 | SINNERS           | L   | 0.471      | -            | -                | -                | -         |    -6.67 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           25 |     2894 | 2024-04-11 | 3DMAX             | W   | 0.452      | 0.384        | 0.505 (0.088)    | -                | -         |    13.74 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           24 |     2942 | 2024-04-10 | Sashi             | W   | 0.445      | -            | -                | -                | -         |     8.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           23 |     3130 | 2024-04-04 | HAVU              | W   | 0.405      | -            | -                | -                | -         |     1.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           22 |     3208 | 2024-04-02 | BLEED             | L   | 0.393      | -            | -                | -                | -         |    -7.20 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           21 |     3237 | 2024-03-31 | FAVBET            | L   | 0.379      | -            | -                | -                | -         |    -9.81 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           20 |     3244 | 2024-03-30 | Lazer Cats        | W   | 0.371      | -            | -                | -                | -         |     0.63 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           19 |     3252 | 2024-03-29 | NAVI Junior       | L   | 0.365      | -            | -                | -                | -         |   -10.14 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           18 |     3271 | 2024-03-28 | GL Academy        | L   | 0.358      | -            | -                | -                | -         |    -9.75 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           17 |     3486 | 2024-03-17 | Sampi             | L   | 0.284      | -            | -                | -                | -         |    -6.44 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           16 |     3495 | 2024-03-16 | ex-Preasy         | L   | 0.279      | -            | -                | -                | -         |    -7.20 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           15 |     3552 | 2024-03-14 | Sampi             | W   | 0.265      | -            | -                | -                | -         |     2.24 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           14 |     3621 | 2024-03-12 | Alliance          | W   | 0.252      | -            | -                | -                | -         |     1.85 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           13 |     3643 | 2024-03-11 | MOUZ NXT          | L   | 0.245      | -            | -                | -                | -         |    -4.12 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           12 |     3663 | 2024-03-10 | MOUZ NXT          | W   | 0.239      | -            | -                | -                | -         |     3.56 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           11 |     3679 | 2024-03-09 | The Chosen Few    | L   | 0.233      | -            | -                | -                | -         |    -6.66 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           10 |     3704 | 2024-03-08 | Spirit Academy    | L   | 0.226      | -            | -                | -                | -         |    -6.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            9 |     3709 | 2024-03-08 | Entropiq          | W   | 0.225      | -            | -                | -                | -         |     0.34 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            8 |     3728 | 2024-03-07 | AURA              | W   | 0.220      | -            | -                | -                | -         |     0.24 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            7 |     3765 | 2024-03-06 | Permitta          | L   | 0.212      | -            | -                | -                | -         |    -4.73 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            6 |     3767 | 2024-03-06 | Fraud5            | W   | 0.211      | -            | -                | -                | -         |     0.51 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            5 |     3797 | 2024-03-05 | B8                | L   | 0.207      | -            | -                | -                | -         |    -3.35 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            4 |     3800 | 2024-03-05 | fnatic            | W   | 0.207      | -            | -                | -                | -         |     5.31 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            3 |     3827 | 2024-03-04 | ALTERNATE aTTaX   | W   | 0.198      | -            | -                | -                | -         |     2.16 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            2 |     4036 | 2024-02-23 | ALTERNATE aTTaX   | W   | 0.131      | -            | -                | -                | -         |     1.53 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            1 |     4380 | 2024-02-08 | BLEED             | L   | 0.031      | -            | -                | -                | -         |    -0.67 | jackasmo, jambo, marat2k, s-chilla, Zinchenko |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($56,412.87)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-25 |      1.000 | $11,000.00     | $11,000.00      |
| 2024-07-22 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-06 |      0.824 | $11,000.00     | $9,062.78       |
| 2024-05-03 |      0.599 | $12,500.00     | $7,489.58       |
| 2024-03-31 |      0.379 | $657.00        | $248.84         |
| 2024-03-30 |      0.372 | $1,000.00      | $371.67         |
| 2024-03-18 |      0.291 | $3,000.00      | $872.50         |
| 2024-03-11 |      0.245 | $1,500.00      | $367.50         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
