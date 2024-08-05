### Roster Details<br />
Team Name: Zero Tenacity<br />
Roster: aVN, brutmonster, Cjoffo, nEMANHA, simke<br />
Global Rank: [34](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [25]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1170.3<br />
<br />
Final Rank Value (1170.3) = Starting Rank Value (1102.6) + Head To Head Adjustments (67.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.537[<sup>1</sup>](#table2)
- Bounty Collected: 0.481[<sup>2</sup>](#table1)
- Opponent Network: 0.355[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.343<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1102.6
- 400 + ( ( 0.343 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1102.6


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
|          103 |       25 | 2024-08-04 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.64 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          102 |      178 | 2024-07-31 | KOI               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.72 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          101 |      228 | 2024-07-30 | Sashi             | W   | 1.000      | 0.500        | 0.184 (0.092)    | 0.996 (0.498)    | 0 (0.000) |    17.11 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          100 |      416 | 2024-07-24 | Insilio           | W   | 1.000      | 0.500        | -                | 0.559 (0.280)    | 0 (0.000) |     8.38 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           99 |      505 | 2024-07-21 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -16.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           98 |      532 | 2024-07-20 | B8                | W   | 1.000      | 0.500        | 0.165 (0.082)    | 0.947 (0.474)    | 0 (0.000) |    16.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           97 |      627 | 2024-07-18 | fnatic            | W   | 1.000      | 0.500        | 0.371 (0.185)    | 0.706 (0.353)    | 0 (0.000) |    27.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           96 |      743 | 2024-07-16 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.618 (0.309)    | 0 (0.000) |    13.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           95 |      765 | 2024-07-16 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.507 (0.253)    | 0 (0.000) |     6.78 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           94 |     1012 | 2024-06-16 | FAVBET            | W   | 0.868      | -            | -                | -                | 0 (0.000) |     5.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           93 |     1044 | 2024-06-15 | Nemiga            | L   | 0.861      | -            | -                | -                | -         |   -10.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           92 |     1085 | 2024-06-14 | RUBY              | W   | 0.854      | -            | -                | -                | 0 (0.000) |     7.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           91 |     1125 | 2024-06-13 | Monte             | L   | 0.847      | -            | -                | -                | -         |   -15.29 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           90 |     1150 | 2024-06-12 | 9INE              | W   | 0.841      | -            | -                | -                | -         |     1.11 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           89 |     1170 | 2024-06-11 | DMS               | W   | 0.834      | -            | -                | -                | -         |     7.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           88 |     1179 | 2024-06-11 | EYEBALLERS        | W   | 0.833      | -            | -                | -                | -         |     6.65 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           87 |     1256 | 2024-06-09 | HAVU              | W   | 0.820      | -            | -                | -                | -         |     3.07 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           86 |     1271 | 2024-06-09 | Nemiga            | L   | 0.819      | -            | -                | -                | -         |   -10.96 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           85 |     1290 | 2024-06-08 | Insilio           | L   | 0.815      | -            | -                | -                | -         |   -17.72 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           84 |     1309 | 2024-06-08 | Passion UA        | W   | 0.814      | 0.500        | 0.173 (0.070)    | 1.000 (0.407)    | -         |    11.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           83 |     1348 | 2024-06-07 | DMS               | W   | 0.808      | -            | -                | -                | -         |     7.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           82 |     1365 | 2024-06-07 | EYEBALLERS        | L   | 0.807      | -            | -                | -                | -         |   -19.22 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           81 |     1385 | 2024-06-07 | 5W                | L   | 0.806      | -            | -                | -                | -         |   -18.36 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           80 |     1409 | 2024-06-06 | FAVBET            | W   | 0.802      | -            | -                | -                | -         |     3.79 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           79 |     1435 | 2024-06-06 | Permitta          | L   | 0.800      | -            | -                | -                | -         |   -19.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           78 |     1454 | 2024-06-06 | GhoulsW           | W   | 0.799      | -            | -                | -                | -         |     0.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           77 |     1490 | 2024-06-05 | Aurora Young Blud | W   | 0.794      | -            | -                | -                | -         |     4.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           76 |     1529 | 2024-06-04 | CYBERSHOKE        | W   | 0.788      | -            | -                | -                | -         |     4.59 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           75 |     1539 | 2024-06-04 | Grannys Knockers  | W   | 0.787      | -            | -                | -                | -         |     3.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           74 |     1569 | 2024-06-03 | Johnny Speeds     | L   | 0.780      | -            | -                | -                | -         |    -8.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           73 |     1575 | 2024-06-02 | DMS               | W   | 0.775      | -            | -                | -                | -         |     7.94 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           72 |     1582 | 2024-06-02 | SAW               | W   | 0.774      | -            | -                | -                | -         |    15.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           71 |     1602 | 2024-06-01 | RUBY              | L   | 0.768      | -            | -                | -                | -         |   -17.62 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           70 |     1618 | 2024-06-01 | DMS               | W   | 0.767      | -            | -                | -                | -         |     6.93 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           69 |     1620 | 2024-06-01 | KOI               | W   | 0.767      | -            | -                | -                | -         |     9.90 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           68 |     1627 | 2024-06-01 | FURIA             | L   | 0.766      | -            | -                | -                | -         |    -1.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           67 |     1656 | 2024-05-31 | Passion UA        | W   | 0.760      | 0.435        | 0.173 (0.057)    | 1.000 (0.330)    | -         |    10.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           66 |     1664 | 2024-05-30 | ThunderFlash      | W   | 0.755      | -            | -                | -                | -         |     0.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           65 |     1677 | 2024-05-30 | Passion UA        | L   | 0.754      | -            | -                | -                | -         |   -13.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           64 |     1693 | 2024-05-29 | JANO              | W   | 0.748      | -            | -                | -                | -         |     1.91 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           63 |     1763 | 2024-05-26 | RUBY              | W   | 0.726      | -            | -                | -                | -         |     6.57 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           62 |     1776 | 2024-05-25 | ex-Guild Eagles   | W   | 0.721      | -            | -                | -                | -         |     4.74 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           61 |     1779 | 2024-05-25 | Serbia            | W   | 0.721      | -            | -                | -                | -         |     3.25 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           60 |     1789 | 2024-05-25 | Rhyno             | W   | 0.719      | -            | -                | -                | -         |     8.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           59 |     1794 | 2024-05-24 | ex-Guild Eagles   | L   | 0.715      | -            | -                | -                | -         |   -18.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           58 |     1797 | 2024-05-24 | The Suspect       | W   | 0.714      | -            | -                | -                | -         |     3.79 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           57 |     1813 | 2024-05-23 | 3DMAX             | L   | 0.707      | -            | -                | -                | -         |    -1.53 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           56 |     1820 | 2024-05-23 | brazylijski luz   | W   | 0.705      | -            | -                | -                | -         |     3.96 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           55 |     1853 | 2024-05-22 | Sangal            | L   | 0.701      | -            | -                | -                | -         |   -10.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           54 |     1863 | 2024-05-22 | Illuminar         | W   | 0.699      | -            | -                | -                | -         |     4.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           53 |     1897 | 2024-05-21 | BLEED             | W   | 0.694      | 0.500        | 0.126 (0.044)    | -                | -         |    18.11 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           52 |     1902 | 2024-05-21 | Verdant           | W   | 0.693      | -            | -                | -                | -         |     6.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           51 |     1925 | 2024-05-20 | Metizport         | W   | 0.688      | -            | -                | -                | -         |     4.26 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           50 |     1960 | 2024-05-19 | B8                | W   | 0.680      | 0.500        | 0.165 (0.056)    | 0.947 (0.322)    | -         |    12.90 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           49 |     2014 | 2024-05-17 | PARIVISION        | L   | 0.668      | -            | -                | -                | -         |   -10.35 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           48 |     2022 | 2024-05-17 | Endpoint          | W   | 0.667      | -            | -                | -                | -         |     6.76 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           47 |     2064 | 2024-05-16 | 1WIN              | L   | 0.660      | -            | -                | -                | -         |   -12.99 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           46 |     2071 | 2024-05-16 | kONO              | W   | 0.659      | -            | -                | -                | -         |     4.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           45 |     2113 | 2024-05-15 | 3DMAX             | W   | 0.653      | 0.500        | 0.508 (0.166)    | 1.000 (0.327)    | -         |    19.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           44 |     2173 | 2024-05-14 | Preasy            | W   | 0.646      | -            | -                | -                | -         |     3.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           43 |     2191 | 2024-05-13 | EYEBALLERS        | W   | 0.640      | -            | -                | -                | -         |     6.01 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           42 |     2219 | 2024-05-12 | Verdant           | W   | 0.633      | -            | -                | -                | -         |     6.95 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           41 |     2289 | 2024-05-09 | 9 Pandas          | L   | 0.613      | -            | -                | -                | -         |   -11.13 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           40 |     2344 | 2024-05-06 | Insilio           | W   | 0.594      | -            | -                | -                | -         |     6.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           39 |     2390 | 2024-05-03 | EYEBALLERS        | L   | 0.575      | -            | -                | -                | -         |   -12.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           38 |     2403 | 2024-05-03 | Metizport         | L   | 0.573      | -            | -                | -                | -         |   -13.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           37 |     2431 | 2024-05-02 | HAVU              | W   | 0.566      | -            | -                | -                | -         |     2.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           36 |     2453 | 2024-05-01 | KOI               | W   | 0.559      | -            | -                | -                | -         |     8.96 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           35 |     2466 | 2024-04-30 | Sangal            | L   | 0.554      | -            | -                | -                | -         |    -7.07 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           34 |     2478 | 2024-04-30 | B8                | W   | 0.552      | 0.435        | 0.165 (0.040)    | -                | -         |     7.93 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           33 |     2493 | 2024-04-29 | PARIVISION        | L   | 0.546      | -            | -                | -                | -         |    -8.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           32 |     2510 | 2024-04-28 | SINNERS           | W   | 0.540      | -            | -                | -                | -         |     9.37 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           31 |     2523 | 2024-04-27 | 500               | W   | 0.535      | -            | -                | -                | -         |     2.30 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           30 |     2543 | 2024-04-27 | SINNERS           | W   | 0.532      | -            | -                | -                | -         |     9.73 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           29 |     2567 | 2024-04-26 | Illuminar         | W   | 0.526      | -            | -                | -                | -         |     1.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           28 |     2589 | 2024-04-25 | EYEBALLERS        | L   | 0.520      | -            | -                | -                | -         |   -12.01 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           27 |     2612 | 2024-04-24 | ex-Guild Eagles   | L   | 0.513      | -            | -                | -                | -         |   -12.45 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           26 |     2628 | 2024-04-23 | Nemiga            | L   | 0.506      | -            | -                | -                | -         |    -5.90 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           25 |     2638 | 2024-04-22 | Grannys Knockers  | W   | 0.501      | -            | -                | -                | -         |     2.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           24 |     2644 | 2024-04-22 | Nexus             | W   | 0.500      | -            | -                | -                | -         |     3.62 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           23 |     2688 | 2024-04-20 | RUBY              | W   | 0.487      | -            | -                | -                | -         |     5.02 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           22 |     2718 | 2024-04-19 | PARIVISION        | W   | 0.481      | -            | -                | -                | -         |     7.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           21 |     2742 | 2024-04-19 | ALTERNATE aTTaX   | W   | 0.479      | -            | -                | -                | -         |     5.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           20 |     2801 | 2024-04-18 | B8                | L   | 0.472      | -            | -                | -                | -         |    -8.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           19 |     2823 | 2024-04-17 | B8                | W   | 0.466      | -            | -                | -                | -         |     6.93 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           18 |     2852 | 2024-04-16 | Sangal            | L   | 0.461      | -            | -                | -                | -         |    -5.77 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           17 |     2874 | 2024-04-15 | ALTERNATE aTTaX   | W   | 0.454      | -            | -                | -                | -         |     5.53 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           16 |     2924 | 2024-04-12 | JANO              | L   | 0.432      | -            | -                | -                | -         |   -12.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           15 |     2951 | 2024-04-11 | Alliance          | L   | 0.427      | -            | -                | -                | -         |   -10.44 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           14 |     3049 | 2024-04-09 | MOUZ NXT          | L   | 0.414      | -            | -                | -                | -         |    -7.08 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           13 |     3112 | 2024-04-07 | ex-Preasy         | L   | 0.399      | -            | -                | -                | -         |   -10.45 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           12 |     3281 | 2024-04-01 | Nemiga            | L   | 0.359      | -            | -                | -                | -         |    -4.63 | aVN, brutmonster, Cjoffo, kdaN, simke    |
|           11 |     3689 | 2024-03-10 | CYBERSHOKE        | L   | 0.215      | -            | -                | -                | -         |    -6.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           10 |     3701 | 2024-03-10 | ECLOT             | W   | 0.213      | -            | -                | -                | -         |     4.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            9 |     3720 | 2024-03-09 | Sangal            | W   | 0.207      | -            | -                | -                | -         |     3.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            8 |     3766 | 2024-03-07 | Nemiga            | L   | 0.194      | -            | -                | -                | -         |    -2.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            7 |     3801 | 2024-03-06 | AURA              | W   | 0.187      | -            | -                | -                | -         |     0.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            6 |     3832 | 2024-03-05 | AMKAL             | L   | 0.181      | -            | -                | -                | -         |    -2.54 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            5 |     3891 | 2024-03-03 | Secret            | W   | 0.166      | -            | -                | -                | -         |     0.22 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            4 |     3911 | 2024-03-02 | Secret            | W   | 0.159      | -            | -                | -                | -         |     0.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            3 |     3937 | 2024-02-29 | Young Ninjas      | W   | 0.147      | -            | -                | -                | -         |     0.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            2 |     4202 | 2024-02-17 | Sashi             | L   | 0.067      | -            | -                | -                | -         |    -0.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            1 |     4355 | 2024-02-10 | Sampi             | L   | 0.021      | -            | -                | -                | -         |    -0.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,096.39)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-10 |      0.828 | $2,000.00      | $1,656.39       |
| 2024-06-02 |      0.774 | $2,000.00      | $1,547.78       |
| 2024-05-22 |      0.701 | $25,000.00     | $17,513.89      |
| 2024-05-16 |      0.659 | $5,000.00      | $3,293.06       |
| 2024-05-04 |      0.581 | $2,000.00      | $1,161.67       |
| 2024-04-24 |      0.514 | $12,500.00     | $6,423.61       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
