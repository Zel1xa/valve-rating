### Roster Details<br />
Team Name: Zero Tenacity<br />
Roster: aVN, brutmonster, Cjoffo, nEMANHA, simke<br />
Global Rank: [37](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [28]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1142.8<br />
<br />
Final Rank Value (1142.8) = Starting Rank Value (1100.8) + Head To Head Adjustments (41.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.537[<sup>1</sup>](#table2)
- Bounty Collected: 0.477[<sup>2</sup>](#table1)
- Opponent Network: 0.357[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.343<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1100.8
- 400 + ( ( 0.343 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1100.8


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
|           99 |      104 | 2024-07-31 | KOI               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           98 |      154 | 2024-07-30 | Sashi             | W   | 1.000      | 0.500        | 0.184 (0.092)    | 0.998 (0.499)    | 0 (0.000) |    17.94 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           97 |      341 | 2024-07-24 | Insilio           | W   | 1.000      | 0.500        | -                | 0.581 (0.290)    | 0 (0.000) |     8.96 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           96 |      430 | 2024-07-21 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -16.73 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           95 |      457 | 2024-07-20 | B8                | W   | 1.000      | 0.500        | 0.166 (0.083)    | 0.945 (0.472)    | 0 (0.000) |    17.67 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           94 |      552 | 2024-07-18 | fnatic            | W   | 1.000      | 0.500        | 0.290 (0.145)    | 0.627 (0.313)    | 0 (0.000) |    24.76 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           93 |      665 | 2024-07-16 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.639 (0.319)    | 0 (0.000) |    14.11 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           92 |      686 | 2024-07-16 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.528 (0.264)    | 0 (0.000) |     7.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           91 |      923 | 2024-06-16 | FAVBET            | W   | 0.880      | -            | -                | -                | 0 (0.000) |     6.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           90 |      950 | 2024-06-15 | Nemiga            | L   | 0.873      | -            | -                | -                | -         |   -10.25 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           89 |     1022 | 2024-06-13 | Monte             | L   | 0.859      | -            | -                | -                | -         |   -15.27 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           88 |     1046 | 2024-06-12 | 9INE              | W   | 0.853      | -            | -                | -                | 0 (0.000) |     1.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           87 |     1072 | 2024-06-11 | EYEBALLERS        | W   | 0.845      | -            | -                | -                | 0 (0.000) |     7.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           86 |     1148 | 2024-06-09 | HAVU              | W   | 0.832      | -            | -                | -                | -         |     3.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           85 |     1163 | 2024-06-09 | Nemiga            | L   | 0.831      | -            | -                | -                | -         |   -11.30 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           84 |     1181 | 2024-06-08 | Insilio           | L   | 0.827      | -            | -                | -                | -         |   -17.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           83 |     1198 | 2024-06-08 | Passion UA        | W   | 0.826      | 0.500        | 0.172 (0.071)    | 1.000 (0.413)    | -         |    11.94 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           82 |     1237 | 2024-06-07 | DMS               | W   | 0.820      | -            | -                | -                | -         |     8.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           81 |     1252 | 2024-06-07 | EYEBALLERS        | L   | 0.819      | -            | -                | -                | -         |   -19.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           80 |     1272 | 2024-06-07 | 5W                | L   | 0.818      | -            | -                | -                | -         |   -18.30 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           79 |     1298 | 2024-06-06 | FAVBET            | W   | 0.814      | -            | -                | -                | -         |     4.01 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           78 |     1322 | 2024-06-06 | Permitta          | L   | 0.813      | -            | -                | -                | -         |   -19.31 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           77 |     1341 | 2024-06-06 | GhoulsW           | W   | 0.811      | -            | -                | -                | -         |     0.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           76 |     1377 | 2024-06-05 | Aurora Young Blud | W   | 0.806      | -            | -                | -                | -         |     4.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           75 |     1425 | 2024-06-04 | Grannys Knockers  | W   | 0.799      | -            | -                | -                | -         |     3.62 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           74 |     1455 | 2024-06-03 | Johnny Speeds     | L   | 0.792      | -            | -                | -                | -         |    -8.49 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           73 |     1461 | 2024-06-02 | DMS               | W   | 0.787      | -            | -                | -                | -         |     8.07 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           72 |     1466 | 2024-06-02 | SAW               | W   | 0.786      | -            | -                | -                | -         |    15.52 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           71 |     1487 | 2024-06-01 | RUBY              | L   | 0.781      | -            | -                | -                | -         |   -17.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           70 |     1502 | 2024-06-01 | DMS               | W   | 0.779      | -            | -                | -                | -         |     7.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           69 |     1504 | 2024-06-01 | KOI               | W   | 0.779      | -            | -                | -                | -         |     6.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           68 |     1511 | 2024-06-01 | FURIA             | L   | 0.778      | -            | -                | -                | -         |    -1.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           67 |     1540 | 2024-05-31 | Passion UA        | W   | 0.772      | 0.435        | 0.172 (0.058)    | 1.000 (0.335)    | -         |    10.52 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           66 |     1548 | 2024-05-30 | ThunderFlash      | W   | 0.767      | -            | -                | -                | -         |     0.47 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           65 |     1561 | 2024-05-30 | Passion UA        | L   | 0.766      | -            | -                | -                | -         |   -13.97 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           64 |     1577 | 2024-05-29 | JANO              | W   | 0.761      | -            | -                | -                | -         |     1.96 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           63 |     1646 | 2024-05-26 | RUBY              | W   | 0.739      | -            | -                | -                | -         |     6.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           62 |     1659 | 2024-05-25 | ex-Guild Eagles   | W   | 0.734      | -            | -                | -                | -         |     4.90 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           61 |     1662 | 2024-05-25 | Serbia            | W   | 0.733      | -            | -                | -                | -         |     3.34 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           60 |     1672 | 2024-05-25 | Rhyno             | W   | 0.731      | -            | -                | -                | -         |     8.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           59 |     1677 | 2024-05-24 | ex-Guild Eagles   | L   | 0.727      | -            | -                | -                | -         |   -18.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           58 |     1680 | 2024-05-24 | The Suspect       | W   | 0.726      | -            | -                | -                | -         |     3.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           57 |     1696 | 2024-05-23 | 3DMAX             | L   | 0.719      | -            | -                | -                | -         |    -1.65 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           56 |     1703 | 2024-05-23 | brazylijski luz   | W   | 0.718      | -            | -                | -                | -         |     4.07 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           55 |     1736 | 2024-05-22 | Sangal            | L   | 0.713      | -            | -                | -                | -         |   -11.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           54 |     1746 | 2024-05-22 | Illuminar         | W   | 0.711      | -            | -                | -                | -         |     4.72 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           53 |     1780 | 2024-05-21 | BLEED             | W   | 0.706      | 0.500        | 0.126 (0.045)    | -                | -         |    18.44 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           52 |     1785 | 2024-05-21 | Verdant           | W   | 0.705      | -            | -                | -                | -         |     6.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           51 |     1808 | 2024-05-20 | Metizport         | W   | 0.700      | -            | -                | -                | -         |     8.17 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           50 |     1842 | 2024-05-19 | B8                | W   | 0.692      | 0.500        | 0.166 (0.057)    | 0.945 (0.327)    | -         |    13.22 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           49 |     1896 | 2024-05-17 | PARIVISION        | L   | 0.680      | -            | -                | -                | -         |   -10.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           48 |     1904 | 2024-05-17 | Endpoint          | W   | 0.679      | -            | -                | -                | -         |     7.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           47 |     1946 | 2024-05-16 | 1WIN              | L   | 0.672      | -            | -                | -                | -         |   -13.76 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           46 |     1953 | 2024-05-16 | kONO              | W   | 0.671      | -            | -                | -                | -         |     5.08 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           45 |     1995 | 2024-05-15 | 3DMAX             | W   | 0.665      | 0.500        | 0.504 (0.168)    | 1.000 (0.333)    | -         |    19.95 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           44 |     2055 | 2024-05-14 | Preasy            | W   | 0.658      | -            | -                | -                | -         |     3.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           43 |     2073 | 2024-05-13 | EYEBALLERS        | W   | 0.653      | -            | -                | -                | -         |     6.39 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           42 |     2101 | 2024-05-12 | Verdant           | W   | 0.645      | -            | -                | -                | -         |     7.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           41 |     2171 | 2024-05-09 | 9 Pandas          | L   | 0.625      | -            | -                | -                | -         |   -11.08 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           40 |     2225 | 2024-05-06 | Insilio           | W   | 0.606      | -            | -                | -                | -         |     6.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           39 |     2271 | 2024-05-03 | EYEBALLERS        | L   | 0.587      | -            | -                | -                | -         |   -12.79 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           38 |     2284 | 2024-05-03 | Metizport         | L   | 0.585      | -            | -                | -                | -         |   -12.01 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           37 |     2312 | 2024-05-02 | HAVU              | W   | 0.578      | -            | -                | -                | -         |     2.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           36 |     2334 | 2024-05-01 | KOI               | W   | 0.572      | -            | -                | -                | -         |     6.17 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           35 |     2347 | 2024-04-30 | Sangal            | L   | 0.566      | -            | -                | -                | -         |    -7.30 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           34 |     2359 | 2024-04-30 | B8                | W   | 0.564      | 0.435        | 0.166 (0.041)    | -                | -         |     8.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           33 |     2374 | 2024-04-29 | PARIVISION        | L   | 0.559      | -            | -                | -                | -         |    -8.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           32 |     2391 | 2024-04-28 | SINNERS           | W   | 0.552      | -            | -                | -                | -         |     8.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           31 |     2404 | 2024-04-27 | 500               | W   | 0.547      | -            | -                | -                | -         |     2.43 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           30 |     2424 | 2024-04-27 | SINNERS           | W   | 0.544      | -            | -                | -                | -         |     9.06 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           29 |     2447 | 2024-04-26 | Illuminar         | W   | 0.538      | -            | -                | -                | -         |     1.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           28 |     2469 | 2024-04-25 | EYEBALLERS        | L   | 0.532      | -            | -                | -                | -         |   -12.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           27 |     2492 | 2024-04-24 | ex-Guild Eagles   | L   | 0.525      | -            | -                | -                | -         |   -12.62 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           26 |     2508 | 2024-04-23 | Nemiga            | L   | 0.519      | -            | -                | -                | -         |    -6.32 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           25 |     2518 | 2024-04-22 | Grannys Knockers  | W   | 0.513      | -            | -                | -                | -         |     2.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           24 |     2524 | 2024-04-22 | Nexus             | W   | 0.512      | -            | -                | -                | -         |     3.80 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           23 |     2568 | 2024-04-20 | RUBY              | W   | 0.499      | -            | -                | -                | -         |     5.37 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           22 |     2598 | 2024-04-19 | PARIVISION        | W   | 0.494      | -            | -                | -                | -         |     7.90 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           21 |     2622 | 2024-04-19 | ALTERNATE aTTaX   | W   | 0.492      | -            | -                | -                | -         |     5.67 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           20 |     2681 | 2024-04-18 | B8                | L   | 0.484      | -            | -                | -                | -         |    -8.11 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           19 |     2703 | 2024-04-17 | B8                | W   | 0.479      | -            | -                | -                | -         |     7.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           18 |     2732 | 2024-04-16 | Sangal            | L   | 0.473      | -            | -                | -                | -         |    -5.99 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           17 |     2754 | 2024-04-15 | ALTERNATE aTTaX   | W   | 0.467      | -            | -                | -                | -         |     5.77 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           16 |     2804 | 2024-04-12 | JANO              | L   | 0.444      | -            | -                | -                | -         |   -12.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           15 |     2831 | 2024-04-11 | Alliance          | L   | 0.439      | -            | -                | -                | -         |   -10.67 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           14 |     2929 | 2024-04-09 | MOUZ NXT          | L   | 0.426      | -            | -                | -                | -         |    -7.39 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           13 |     2992 | 2024-04-07 | ex-Preasy         | L   | 0.411      | -            | -                | -                | -         |   -10.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           12 |     3161 | 2024-04-01 | Nemiga            | L   | 0.371      | -            | -                | -                | -         |    -5.02 | aVN, brutmonster, Cjoffo, kdaN, simke    |
|           11 |     3561 | 2024-03-10 | CYBERSHOKE        | L   | 0.227      | -            | -                | -                | -         |    -6.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           10 |     3573 | 2024-03-10 | ECLOT             | W   | 0.226      | -            | -                | -                | -         |     4.73 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            9 |     3592 | 2024-03-09 | Sangal            | W   | 0.219      | -            | -                | -                | -         |     3.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            8 |     3638 | 2024-03-07 | Nemiga            | L   | 0.206      | -            | -                | -                | -         |    -2.78 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            7 |     3672 | 2024-03-06 | AURA              | W   | 0.199      | -            | -                | -                | -         |     0.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            6 |     3704 | 2024-03-05 | AMKAL             | L   | 0.193      | -            | -                | -                | -         |    -2.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            5 |     3763 | 2024-03-03 | Secret            | W   | 0.178      | -            | -                | -                | -         |     0.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            4 |     3783 | 2024-03-02 | Secret            | W   | 0.171      | -            | -                | -                | -         |     0.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            3 |     3809 | 2024-02-29 | Young Ninjas      | W   | 0.159      | -            | -                | -                | -         |     0.64 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            2 |     4073 | 2024-02-17 | Sashi             | L   | 0.079      | -            | -                | -                | -         |    -1.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            1 |     4226 | 2024-02-10 | Sampi             | L   | 0.033      | -            | -                | -                | -         |    -0.81 | aVN, brutmonster, Cjoffo, nEMANHA, simke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,691.41)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-10 |      0.840 | $2,000.00      | $1,680.93       |
| 2024-06-02 |      0.786 | $2,000.00      | $1,572.31       |
| 2024-05-22 |      0.713 | $25,000.00     | $17,820.60      |
| 2024-05-16 |      0.671 | $5,000.00      | $3,354.40       |
| 2024-05-04 |      0.593 | $2,000.00      | $1,186.20       |
| 2024-04-24 |      0.526 | $12,500.00     | $6,576.97       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
