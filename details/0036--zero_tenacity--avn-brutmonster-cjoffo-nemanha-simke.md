### Roster Details<br />
Team Name: Zero Tenacity<br />
Roster: aVN, brutmonster, Cjoffo, nEMANHA, simke<br />
Global Rank: [36](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [27]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1165.6<br />
<br />
Final Rank Value (1165.6) = Starting Rank Value (1100.6) + Head To Head Adjustments (65.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.537[<sup>1</sup>](#table2)
- Bounty Collected: 0.482[<sup>2</sup>](#table1)
- Opponent Network: 0.353[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.343<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1100.6
- 400 + ( ( 0.343 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1100.6


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
|          102 |      126 | 2024-07-31 | KOI               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          101 |      177 | 2024-07-30 | Sashi             | W   | 1.000      | 0.500        | 0.184 (0.092)    | 0.964 (0.482)    | 0 (0.000) |    17.06 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          100 |      364 | 2024-07-24 | Insilio           | W   | 1.000      | 0.500        | -                | 0.561 (0.281)    | 0 (0.000) |     8.41 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           99 |      453 | 2024-07-21 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -17.27 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           98 |      480 | 2024-07-20 | B8                | W   | 1.000      | 0.500        | 0.165 (0.083)    | 0.913 (0.456)    | 0 (0.000) |    16.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           97 |      576 | 2024-07-18 | fnatic            | W   | 1.000      | 0.500        | 0.371 (0.185)    | 0.709 (0.354)    | 0 (0.000) |    27.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           96 |      690 | 2024-07-16 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.618 (0.309)    | 0 (0.000) |    13.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           95 |      714 | 2024-07-16 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.510 (0.255)    | 0 (0.000) |     6.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           94 |      959 | 2024-06-16 | FAVBET            | W   | 0.878      | -            | -                | -                | 0 (0.000) |     5.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           93 |      991 | 2024-06-15 | Nemiga            | L   | 0.872      | -            | -                | -                | -         |   -11.01 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           92 |     1032 | 2024-06-14 | RUBY              | W   | 0.865      | -            | -                | -                | 0 (0.000) |     7.33 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           91 |     1072 | 2024-06-13 | Monte             | L   | 0.858      | -            | -                | -                | -         |   -15.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           90 |     1097 | 2024-06-12 | 9INE              | W   | 0.852      | -            | -                | -                | 0 (0.000) |     1.14 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           89 |     1117 | 2024-06-11 | DMS               | W   | 0.845      | -            | -                | -                | -         |     7.91 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           88 |     1126 | 2024-06-11 | EYEBALLERS        | W   | 0.843      | -            | -                | -                | -         |     6.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           87 |     1203 | 2024-06-09 | HAVU              | W   | 0.830      | -            | -                | -                | -         |     3.15 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           86 |     1218 | 2024-06-09 | Nemiga            | L   | 0.829      | -            | -                | -                | -         |   -11.57 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           85 |     1237 | 2024-06-08 | Insilio           | L   | 0.825      | -            | -                | -                | -         |   -17.95 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           84 |     1256 | 2024-06-08 | Passion UA        | W   | 0.824      | 0.500        | 0.172 (0.071)    | 1.000 (0.412)    | -         |    11.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           83 |     1295 | 2024-06-07 | DMS               | W   | 0.819      | -            | -                | -                | -         |     7.91 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           82 |     1312 | 2024-06-07 | EYEBALLERS        | L   | 0.818      | -            | -                | -                | -         |   -19.38 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           81 |     1332 | 2024-06-07 | 5W                | L   | 0.816      | -            | -                | -                | -         |   -18.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           80 |     1356 | 2024-06-06 | FAVBET            | W   | 0.812      | -            | -                | -                | -         |     3.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           79 |     1382 | 2024-06-06 | Permitta          | L   | 0.811      | -            | -                | -                | -         |   -19.52 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           78 |     1401 | 2024-06-06 | GhoulsW           | W   | 0.809      | -            | -                | -                | -         |     0.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           77 |     1437 | 2024-06-05 | Aurora Young Blud | W   | 0.804      | -            | -                | -                | -         |     3.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           76 |     1476 | 2024-06-04 | CYBERSHOKE        | W   | 0.798      | -            | -                | -                | -         |     4.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           75 |     1486 | 2024-06-04 | Grannys Knockers  | W   | 0.797      | -            | -                | -                | -         |     3.52 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           74 |     1516 | 2024-06-03 | Johnny Speeds     | L   | 0.790      | -            | -                | -                | -         |    -8.67 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           73 |     1522 | 2024-06-02 | DMS               | W   | 0.785      | -            | -                | -                | -         |     7.96 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           72 |     1529 | 2024-06-02 | SAW               | W   | 0.784      | -            | -                | -                | -         |    15.45 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           71 |     1549 | 2024-06-01 | RUBY              | L   | 0.779      | -            | -                | -                | -         |   -17.75 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           70 |     1565 | 2024-06-01 | DMS               | W   | 0.778      | -            | -                | -                | -         |     6.94 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           69 |     1567 | 2024-06-01 | KOI               | W   | 0.777      | -            | -                | -                | -         |    10.08 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           68 |     1574 | 2024-06-01 | FURIA             | L   | 0.776      | -            | -                | -                | -         |    -1.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           67 |     1603 | 2024-05-31 | Passion UA        | W   | 0.770      | 0.435        | 0.172 (0.058)    | 1.000 (0.335)    | -         |    10.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           66 |     1611 | 2024-05-30 | ThunderFlash      | W   | 0.765      | -            | -                | -                | -         |     0.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           65 |     1624 | 2024-05-30 | Passion UA        | L   | 0.764      | -            | -                | -                | -         |   -14.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           64 |     1640 | 2024-05-29 | JANO              | W   | 0.759      | -            | -                | -                | -         |     1.93 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           63 |     1710 | 2024-05-26 | RUBY              | W   | 0.737      | -            | -                | -                | -         |     6.76 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           62 |     1723 | 2024-05-25 | ex-Guild Eagles   | W   | 0.732      | -            | -                | -                | -         |     4.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           61 |     1726 | 2024-05-25 | Serbia            | W   | 0.731      | -            | -                | -                | -         |     3.29 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           60 |     1736 | 2024-05-25 | Rhyno             | W   | 0.729      | -            | -                | -                | -         |     8.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           59 |     1741 | 2024-05-24 | ex-Guild Eagles   | L   | 0.725      | -            | -                | -                | -         |   -18.41 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           58 |     1744 | 2024-05-24 | The Suspect       | W   | 0.724      | -            | -                | -                | -         |     3.78 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           57 |     1760 | 2024-05-23 | 3DMAX             | L   | 0.718      | -            | -                | -                | -         |    -1.62 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           56 |     1767 | 2024-05-23 | brazylijski luz   | W   | 0.716      | -            | -                | -                | -         |     4.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           55 |     1800 | 2024-05-22 | Sangal            | L   | 0.711      | -            | -                | -                | -         |   -10.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           54 |     1810 | 2024-05-22 | Illuminar         | W   | 0.709      | -            | -                | -                | -         |     4.62 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           53 |     1844 | 2024-05-21 | BLEED             | W   | 0.704      | 0.500        | 0.126 (0.045)    | -                | -         |    18.29 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           52 |     1849 | 2024-05-21 | Verdant           | W   | 0.703      | -            | -                | -                | -         |     6.16 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           51 |     1872 | 2024-05-20 | Metizport         | W   | 0.699      | -            | -                | -                | -         |     8.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           50 |     1907 | 2024-05-19 | B8                | W   | 0.690      | 0.500        | 0.165 (0.057)    | 0.913 (0.315)    | -         |    13.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           49 |     1961 | 2024-05-17 | PARIVISION        | L   | 0.679      | -            | -                | -                | -         |   -10.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           48 |     1969 | 2024-05-17 | Endpoint          | W   | 0.677      | -            | -                | -                | -         |     6.92 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           47 |     2011 | 2024-05-16 | 1WIN              | L   | 0.670      | -            | -                | -                | -         |   -13.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           46 |     2018 | 2024-05-16 | kONO              | W   | 0.669      | -            | -                | -                | -         |     5.02 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           45 |     2060 | 2024-05-15 | 3DMAX             | W   | 0.664      | 0.500        | 0.505 (0.168)    | 1.000 (0.332)    | -         |    19.91 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           44 |     2120 | 2024-05-14 | Preasy            | W   | 0.657      | -            | -                | -                | -         |     3.79 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           43 |     2138 | 2024-05-13 | EYEBALLERS        | W   | 0.651      | -            | -                | -                | -         |     6.31 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           42 |     2166 | 2024-05-12 | Verdant           | W   | 0.643      | -            | -                | -                | -         |     7.13 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           41 |     2236 | 2024-05-09 | 9 Pandas          | L   | 0.624      | -            | -                | -                | -         |   -11.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           40 |     2291 | 2024-05-06 | Insilio           | W   | 0.605      | -            | -                | -                | -         |     6.75 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           39 |     2337 | 2024-05-03 | EYEBALLERS        | L   | 0.585      | -            | -                | -                | -         |   -12.81 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           38 |     2350 | 2024-05-03 | Metizport         | L   | 0.583      | -            | -                | -                | -         |   -12.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           37 |     2378 | 2024-05-02 | HAVU              | W   | 0.576      | -            | -                | -                | -         |     2.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           36 |     2400 | 2024-05-01 | KOI               | W   | 0.570      | -            | -                | -                | -         |     9.30 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           35 |     2413 | 2024-04-30 | Sangal            | L   | 0.564      | -            | -                | -                | -         |    -7.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           34 |     2425 | 2024-04-30 | B8                | W   | 0.563      | 0.435        | 0.165 (0.040)    | -                | -         |     8.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           33 |     2440 | 2024-04-29 | PARIVISION        | L   | 0.557      | -            | -                | -                | -         |    -8.26 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           32 |     2457 | 2024-04-28 | SINNERS           | W   | 0.551      | -            | -                | -                | -         |     8.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           31 |     2470 | 2024-04-27 | 500               | W   | 0.545      | -            | -                | -                | -         |     2.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           30 |     2490 | 2024-04-27 | SINNERS           | W   | 0.543      | -            | -                | -                | -         |     8.97 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           29 |     2513 | 2024-04-26 | Illuminar         | W   | 0.536      | -            | -                | -                | -         |     1.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           28 |     2535 | 2024-04-25 | EYEBALLERS        | L   | 0.530      | -            | -                | -                | -         |   -12.17 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           27 |     2558 | 2024-04-24 | ex-Guild Eagles   | L   | 0.523      | -            | -                | -                | -         |   -12.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           26 |     2574 | 2024-04-23 | Nemiga            | L   | 0.517      | -            | -                | -                | -         |    -6.33 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           25 |     2584 | 2024-04-22 | Grannys Knockers  | W   | 0.512      | -            | -                | -                | -         |     2.26 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           24 |     2590 | 2024-04-22 | Nexus             | W   | 0.510      | -            | -                | -                | -         |     3.74 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           23 |     2634 | 2024-04-20 | RUBY              | W   | 0.497      | -            | -                | -                | -         |     5.30 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           22 |     2664 | 2024-04-19 | PARIVISION        | W   | 0.492      | -            | -                | -                | -         |     7.81 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           21 |     2688 | 2024-04-19 | ALTERNATE aTTaX   | W   | 0.490      | -            | -                | -                | -         |     5.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           20 |     2747 | 2024-04-18 | B8                | L   | 0.483      | -            | -                | -                | -         |    -8.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           19 |     2769 | 2024-04-17 | B8                | W   | 0.477      | -            | -                | -                | -         |     7.17 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           18 |     2798 | 2024-04-16 | Sangal            | L   | 0.472      | -            | -                | -                | -         |    -5.93 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           17 |     2820 | 2024-04-15 | ALTERNATE aTTaX   | W   | 0.465      | -            | -                | -                | -         |     5.73 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           16 |     2870 | 2024-04-12 | JANO              | L   | 0.443      | -            | -                | -                | -         |   -12.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           15 |     2897 | 2024-04-11 | Alliance          | L   | 0.437      | -            | -                | -                | -         |   -10.65 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           14 |     2995 | 2024-04-09 | MOUZ NXT          | L   | 0.424      | -            | -                | -                | -         |    -7.26 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           13 |     3058 | 2024-04-07 | ex-Preasy         | L   | 0.410      | -            | -                | -                | -         |   -10.64 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           12 |     3227 | 2024-04-01 | Nemiga            | L   | 0.370      | -            | -                | -                | -         |    -5.02 | aVN, brutmonster, Cjoffo, kdaN, simke    |
|           11 |     3634 | 2024-03-10 | CYBERSHOKE        | L   | 0.225      | -            | -                | -                | -         |    -6.54 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           10 |     3646 | 2024-03-10 | ECLOT             | W   | 0.224      | -            | -                | -                | -         |     4.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            9 |     3665 | 2024-03-09 | Sangal            | W   | 0.217      | -            | -                | -                | -         |     3.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            8 |     3711 | 2024-03-07 | Nemiga            | L   | 0.205      | -            | -                | -                | -         |    -2.76 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            7 |     3746 | 2024-03-06 | AURA              | W   | 0.198      | -            | -                | -                | -         |     0.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            6 |     3777 | 2024-03-05 | AMKAL             | L   | 0.192      | -            | -                | -                | -         |    -2.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            5 |     3836 | 2024-03-03 | Secret            | W   | 0.176      | -            | -                | -                | -         |     0.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            4 |     3856 | 2024-03-02 | Secret            | W   | 0.170      | -            | -                | -                | -         |     0.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            3 |     3882 | 2024-02-29 | Young Ninjas      | W   | 0.157      | -            | -                | -                | -         |     0.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            2 |     4146 | 2024-02-17 | Sashi             | L   | 0.078      | -            | -                | -                | -         |    -1.02 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            1 |     4299 | 2024-02-10 | Sampi             | L   | 0.032      | -            | -                | -                | -         |    -0.77 | aVN, brutmonster, Cjoffo, nEMANHA, simke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,608.33)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-10 |      0.839 | $2,000.00      | $1,677.50       |
| 2024-06-02 |      0.784 | $2,000.00      | $1,568.89       |
| 2024-05-22 |      0.711 | $25,000.00     | $17,777.78      |
| 2024-05-16 |      0.669 | $5,000.00      | $3,345.83       |
| 2024-05-04 |      0.591 | $2,000.00      | $1,182.78       |
| 2024-04-24 |      0.524 | $12,500.00     | $6,555.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
