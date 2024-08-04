### Roster Details<br />
Team Name: Zero Tenacity<br />
Roster: aVN, brutmonster, Cjoffo, nEMANHA, simke<br />
Global Rank: [36](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [27]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1165.5<br />
<br />
Final Rank Value (1165.5) = Starting Rank Value (1100.4) + Head To Head Adjustments (65.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.537[<sup>1</sup>](#table2)
- Bounty Collected: 0.481[<sup>2</sup>](#table1)
- Opponent Network: 0.352[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.343<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1100.4
- 400 + ( ( 0.343 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1100.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|          102 |      129 | 2024-07-31 | KOI               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.80 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          101 |      180 | 2024-07-30 | Sashi             | W   | 1.000      | 0.500        | 0.184 (0.092)    | 0.962 (0.481)    | 0 (0.000) |    17.06 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          100 |      367 | 2024-07-24 | Insilio           | W   | 1.000      | 0.500        | -                | 0.561 (0.281)    | 0 (0.000) |     8.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           99 |      456 | 2024-07-21 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -17.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           98 |      483 | 2024-07-20 | B8                | W   | 1.000      | 0.500        | 0.165 (0.083)    | 0.912 (0.456)    | 0 (0.000) |    16.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           97 |      579 | 2024-07-18 | fnatic            | W   | 1.000      | 0.500        | 0.371 (0.185)    | 0.708 (0.354)    | 0 (0.000) |    27.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           96 |      693 | 2024-07-16 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.618 (0.309)    | 0 (0.000) |    13.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           95 |      717 | 2024-07-16 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.510 (0.255)    | 0 (0.000) |     6.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           94 |      963 | 2024-06-16 | FAVBET            | W   | 0.875      | -            | -                | -                | 0 (0.000) |     5.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           93 |      995 | 2024-06-15 | Nemiga            | L   | 0.869      | -            | -                | -                | -         |   -10.99 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           92 |     1036 | 2024-06-14 | RUBY              | W   | 0.862      | -            | -                | -                | 0 (0.000) |     7.30 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           91 |     1076 | 2024-06-13 | Monte             | L   | 0.854      | -            | -                | -                | -         |   -15.47 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           90 |     1101 | 2024-06-12 | 9INE              | W   | 0.849      | -            | -                | -                | 0 (0.000) |     1.13 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           89 |     1121 | 2024-06-11 | DMS               | W   | 0.842      | -            | -                | -                | -         |     7.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           88 |     1130 | 2024-06-11 | EYEBALLERS        | W   | 0.840      | -            | -                | -                | -         |     6.80 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           87 |     1207 | 2024-06-09 | HAVU              | W   | 0.827      | -            | -                | -                | -         |     3.13 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           86 |     1222 | 2024-06-09 | Nemiga            | L   | 0.826      | -            | -                | -                | -         |   -11.54 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           85 |     1241 | 2024-06-08 | Insilio           | L   | 0.822      | -            | -                | -                | -         |   -17.90 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           84 |     1260 | 2024-06-08 | Passion UA        | W   | 0.821      | 0.500        | 0.172 (0.071)    | 1.000 (0.411)    | -         |    11.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           83 |     1299 | 2024-06-07 | DMS               | W   | 0.816      | -            | -                | -                | -         |     7.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           82 |     1316 | 2024-06-07 | EYEBALLERS        | L   | 0.815      | -            | -                | -                | -         |   -19.32 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           81 |     1336 | 2024-06-07 | 5W                | L   | 0.813      | -            | -                | -                | -         |   -18.49 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           80 |     1360 | 2024-06-06 | FAVBET            | W   | 0.809      | -            | -                | -                | -         |     3.80 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           79 |     1386 | 2024-06-06 | Permitta          | L   | 0.808      | -            | -                | -                | -         |   -19.45 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           78 |     1405 | 2024-06-06 | GhoulsW           | W   | 0.806      | -            | -                | -                | -         |     0.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           77 |     1441 | 2024-06-05 | Aurora Young Blud | W   | 0.801      | -            | -                | -                | -         |     3.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           76 |     1480 | 2024-06-04 | CYBERSHOKE        | W   | 0.795      | -            | -                | -                | -         |     4.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           75 |     1490 | 2024-06-04 | Grannys Knockers  | W   | 0.794      | -            | -                | -                | -         |     3.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           74 |     1520 | 2024-06-03 | Johnny Speeds     | L   | 0.787      | -            | -                | -                | -         |    -8.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           73 |     1526 | 2024-06-02 | DMS               | W   | 0.782      | -            | -                | -                | -         |     7.93 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           72 |     1533 | 2024-06-02 | SAW               | W   | 0.781      | -            | -                | -                | -         |    15.35 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           71 |     1553 | 2024-06-01 | RUBY              | L   | 0.776      | -            | -                | -                | -         |   -17.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           70 |     1569 | 2024-06-01 | DMS               | W   | 0.775      | -            | -                | -                | -         |     6.91 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           69 |     1571 | 2024-06-01 | KOI               | W   | 0.774      | -            | -                | -                | -         |    10.01 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           68 |     1578 | 2024-06-01 | FURIA             | L   | 0.773      | -            | -                | -                | -         |    -1.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           67 |     1607 | 2024-05-31 | Passion UA        | W   | 0.767      | 0.435        | 0.172 (0.057)    | 1.000 (0.333)    | -         |    10.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           66 |     1615 | 2024-05-30 | ThunderFlash      | W   | 0.762      | -            | -                | -                | -         |     0.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           65 |     1628 | 2024-05-30 | Passion UA        | L   | 0.761      | -            | -                | -                | -         |   -13.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           64 |     1644 | 2024-05-29 | JANO              | W   | 0.756      | -            | -                | -                | -         |     1.93 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           63 |     1714 | 2024-05-26 | RUBY              | W   | 0.734      | -            | -                | -                | -         |     6.73 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           62 |     1727 | 2024-05-25 | ex-Guild Eagles   | W   | 0.729      | -            | -                | -                | -         |     4.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           61 |     1730 | 2024-05-25 | Serbia            | W   | 0.728      | -            | -                | -                | -         |     3.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           60 |     1740 | 2024-05-25 | Rhyno             | W   | 0.726      | -            | -                | -                | -         |     8.14 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           59 |     1745 | 2024-05-24 | ex-Guild Eagles   | L   | 0.722      | -            | -                | -                | -         |   -18.34 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           58 |     1748 | 2024-05-24 | The Suspect       | W   | 0.721      | -            | -                | -                | -         |     3.77 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           57 |     1764 | 2024-05-23 | 3DMAX             | L   | 0.714      | -            | -                | -                | -         |    -1.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           56 |     1771 | 2024-05-23 | brazylijski luz   | W   | 0.713      | -            | -                | -                | -         |     3.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           55 |     1804 | 2024-05-22 | Sangal            | L   | 0.708      | -            | -                | -                | -         |   -10.44 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           54 |     1814 | 2024-05-22 | Illuminar         | W   | 0.706      | -            | -                | -                | -         |     4.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           53 |     1848 | 2024-05-21 | BLEED             | W   | 0.701      | 0.500        | 0.126 (0.044)    | -                | -         |    18.22 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           52 |     1853 | 2024-05-21 | Verdant           | W   | 0.700      | -            | -                | -                | -         |     6.14 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           51 |     1876 | 2024-05-20 | Metizport         | W   | 0.696      | -            | -                | -                | -         |     8.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           50 |     1911 | 2024-05-19 | B8                | W   | 0.687      | 0.500        | 0.165 (0.057)    | 0.912 (0.313)    | -         |    13.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           49 |     1965 | 2024-05-17 | PARIVISION        | L   | 0.676      | -            | -                | -                | -         |   -10.49 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           48 |     1973 | 2024-05-17 | Endpoint          | W   | 0.674      | -            | -                | -                | -         |     6.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           47 |     2015 | 2024-05-16 | 1WIN              | L   | 0.667      | -            | -                | -                | -         |   -13.80 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           46 |     2022 | 2024-05-16 | kONO              | W   | 0.666      | -            | -                | -                | -         |     4.99 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           45 |     2064 | 2024-05-15 | 3DMAX             | W   | 0.661      | 0.500        | 0.506 (0.167)    | 1.000 (0.330)    | -         |    19.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           44 |     2124 | 2024-05-14 | Preasy            | W   | 0.654      | -            | -                | -                | -         |     3.77 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           43 |     2142 | 2024-05-13 | EYEBALLERS        | W   | 0.648      | -            | -                | -                | -         |     6.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           42 |     2170 | 2024-05-12 | Verdant           | W   | 0.640      | -            | -                | -                | -         |     7.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           41 |     2240 | 2024-05-09 | 9 Pandas          | L   | 0.621      | -            | -                | -                | -         |   -11.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           40 |     2295 | 2024-05-06 | Insilio           | W   | 0.602      | -            | -                | -                | -         |     6.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           39 |     2341 | 2024-05-03 | EYEBALLERS        | L   | 0.582      | -            | -                | -                | -         |   -12.76 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           38 |     2354 | 2024-05-03 | Metizport         | L   | 0.580      | -            | -                | -                | -         |   -12.01 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           37 |     2382 | 2024-05-02 | HAVU              | W   | 0.573      | -            | -                | -                | -         |     2.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           36 |     2404 | 2024-05-01 | KOI               | W   | 0.567      | -            | -                | -                | -         |     9.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           35 |     2417 | 2024-04-30 | Sangal            | L   | 0.561      | -            | -                | -                | -         |    -7.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           34 |     2429 | 2024-04-30 | B8                | W   | 0.560      | 0.435        | 0.165 (0.040)    | -                | -         |     8.14 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           33 |     2444 | 2024-04-29 | PARIVISION        | L   | 0.554      | -            | -                | -                | -         |    -8.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           32 |     2461 | 2024-04-28 | SINNERS           | W   | 0.547      | -            | -                | -                | -         |     8.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           31 |     2474 | 2024-04-27 | 500               | W   | 0.542      | -            | -                | -                | -         |     2.39 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           30 |     2494 | 2024-04-27 | SINNERS           | W   | 0.540      | -            | -                | -                | -         |     8.90 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           29 |     2518 | 2024-04-26 | Illuminar         | W   | 0.533      | -            | -                | -                | -         |     1.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           28 |     2540 | 2024-04-25 | EYEBALLERS        | L   | 0.527      | -            | -                | -                | -         |   -12.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           27 |     2563 | 2024-04-24 | ex-Guild Eagles   | L   | 0.520      | -            | -                | -                | -         |   -12.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           26 |     2579 | 2024-04-23 | Nemiga            | L   | 0.514      | -            | -                | -                | -         |    -6.31 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           25 |     2589 | 2024-04-22 | Grannys Knockers  | W   | 0.509      | -            | -                | -                | -         |     2.25 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           24 |     2595 | 2024-04-22 | Nexus             | W   | 0.507      | -            | -                | -                | -         |     3.71 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           23 |     2639 | 2024-04-20 | RUBY              | W   | 0.494      | -            | -                | -                | -         |     5.26 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           22 |     2669 | 2024-04-19 | PARIVISION        | W   | 0.489      | -            | -                | -                | -         |     7.76 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           21 |     2693 | 2024-04-19 | ALTERNATE aTTaX   | W   | 0.487      | -            | -                | -                | -         |     5.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           20 |     2752 | 2024-04-18 | B8                | L   | 0.480      | -            | -                | -                | -         |    -8.06 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           19 |     2774 | 2024-04-17 | B8                | W   | 0.474      | -            | -                | -                | -         |     7.11 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           18 |     2803 | 2024-04-16 | Sangal            | L   | 0.469      | -            | -                | -                | -         |    -5.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           17 |     2825 | 2024-04-15 | ALTERNATE aTTaX   | W   | 0.462      | -            | -                | -                | -         |     5.68 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           16 |     2875 | 2024-04-12 | JANO              | L   | 0.439      | -            | -                | -                | -         |   -12.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           15 |     2902 | 2024-04-11 | Alliance          | L   | 0.434      | -            | -                | -                | -         |   -10.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           14 |     3000 | 2024-04-09 | MOUZ NXT          | L   | 0.421      | -            | -                | -                | -         |    -7.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           13 |     3063 | 2024-04-07 | ex-Preasy         | L   | 0.407      | -            | -                | -                | -         |   -10.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           12 |     3232 | 2024-04-01 | Nemiga            | L   | 0.367      | -            | -                | -                | -         |    -4.99 | aVN, brutmonster, Cjoffo, kdaN, simke    |
|           11 |     3640 | 2024-03-10 | CYBERSHOKE        | L   | 0.222      | -            | -                | -                | -         |    -6.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           10 |     3652 | 2024-03-10 | ECLOT             | W   | 0.221      | -            | -                | -                | -         |     4.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            9 |     3671 | 2024-03-09 | Sangal            | W   | 0.214      | -            | -                | -                | -         |     3.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            8 |     3717 | 2024-03-07 | Nemiga            | L   | 0.202      | -            | -                | -                | -         |    -2.73 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            7 |     3752 | 2024-03-06 | AURA              | W   | 0.194      | -            | -                | -                | -         |     0.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            6 |     3783 | 2024-03-05 | AMKAL             | L   | 0.189      | -            | -                | -                | -         |    -2.62 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            5 |     3842 | 2024-03-03 | Secret            | W   | 0.173      | -            | -                | -                | -         |     0.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            4 |     3862 | 2024-03-02 | Secret            | W   | 0.167      | -            | -                | -                | -         |     0.22 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            3 |     3888 | 2024-02-29 | Young Ninjas      | W   | 0.154      | -            | -                | -                | -         |     0.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            2 |     4153 | 2024-02-17 | Sashi             | L   | 0.075      | -            | -                | -                | -         |    -0.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            1 |     4306 | 2024-02-10 | Sampi             | L   | 0.029      | -            | -                | -                | -         |    -0.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,460.14)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-10 |      0.836 | $2,000.00      | $1,671.39       |
| 2024-06-02 |      0.781 | $2,000.00      | $1,562.78       |
| 2024-05-22 |      0.708 | $25,000.00     | $17,701.39      |
| 2024-05-16 |      0.666 | $5,000.00      | $3,330.56       |
| 2024-05-04 |      0.588 | $2,000.00      | $1,176.67       |
| 2024-04-24 |      0.521 | $12,500.00     | $6,517.36       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
