### Roster Details<br />
Team Name: Zero Tenacity<br />
Roster: aVN, brutmonster, Cjoffo, nEMANHA, simke<br />
Global Rank: [35](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [26]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1148.7<br />
<br />
Final Rank Value (1148.7) = Starting Rank Value (1104.6) + Head To Head Adjustments (44.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.542[<sup>1</sup>](#table2)
- Bounty Collected: 0.481[<sup>2</sup>](#table1)
- Opponent Network: 0.352[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.344<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1104.6
- 400 + ( ( 0.344 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1104.6


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
|          104 |        3 | 2024-08-05 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -22.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          103 |       34 | 2024-08-04 | Into the Breach   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.64 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          102 |      187 | 2024-07-31 | KOI               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.68 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          101 |      237 | 2024-07-30 | Sashi             | W   | 1.000      | 0.500        | 0.184 (0.092)    | 0.983 (0.491)    | 0 (0.000) |    17.09 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          100 |      425 | 2024-07-24 | Insilio           | W   | 1.000      | 0.500        | -                | 0.552 (0.276)    | 0 (0.000) |     8.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           99 |      514 | 2024-07-21 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -17.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           98 |      541 | 2024-07-20 | B8                | W   | 1.000      | 0.500        | 0.165 (0.082)    | 0.935 (0.468)    | 0 (0.000) |    16.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           97 |      636 | 2024-07-18 | fnatic            | W   | 1.000      | 0.500        | 0.371 (0.185)    | 0.697 (0.348)    | 0 (0.000) |    27.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           96 |      752 | 2024-07-16 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.611 (0.306)    | 0 (0.000) |    13.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           95 |      774 | 2024-07-16 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.500 (0.250)    | 0 (0.000) |     6.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           94 |     1021 | 2024-06-16 | FAVBET            | W   | 0.866      | -            | -                | -                | 0 (0.000) |     5.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           93 |     1053 | 2024-06-15 | Nemiga            | L   | 0.860      | -            | -                | -                | -         |   -10.49 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           92 |     1094 | 2024-06-14 | RUBY              | W   | 0.853      | -            | -                | -                | 0 (0.000) |     7.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           91 |     1134 | 2024-06-13 | Monte             | L   | 0.845      | -            | -                | -                | -         |   -15.29 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           90 |     1159 | 2024-06-12 | 9INE              | W   | 0.840      | -            | -                | -                | -         |     1.11 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           89 |     1179 | 2024-06-11 | DMS               | W   | 0.833      | -            | -                | -                | -         |     7.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           88 |     1188 | 2024-06-11 | EYEBALLERS        | W   | 0.831      | -            | -                | -                | -         |     6.65 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           87 |     1265 | 2024-06-09 | HAVU              | W   | 0.818      | -            | -                | -                | -         |     3.06 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           86 |     1280 | 2024-06-09 | Nemiga            | L   | 0.817      | -            | -                | -                | -         |   -10.95 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           85 |     1299 | 2024-06-08 | Insilio           | L   | 0.813      | -            | -                | -                | -         |   -17.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           84 |     1318 | 2024-06-08 | Passion UA        | W   | 0.812      | 0.500        | 0.173 (0.070)    | 1.000 (0.406)    | -         |    11.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           83 |     1357 | 2024-06-07 | DMS               | W   | 0.807      | -            | -                | -                | -         |     7.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           82 |     1374 | 2024-06-07 | EYEBALLERS        | L   | 0.806      | -            | -                | -                | -         |   -19.17 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           81 |     1394 | 2024-06-07 | 5W                | L   | 0.804      | -            | -                | -                | -         |   -18.33 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           80 |     1418 | 2024-06-06 | FAVBET            | W   | 0.800      | -            | -                | -                | -         |     3.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           79 |     1444 | 2024-06-06 | Permitta          | L   | 0.799      | -            | -                | -                | -         |   -19.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           78 |     1463 | 2024-06-06 | GhoulsW           | W   | 0.797      | -            | -                | -                | -         |     0.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           77 |     1499 | 2024-06-05 | Aurora Young Blud | W   | 0.792      | -            | -                | -                | -         |     4.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           76 |     1538 | 2024-06-04 | CYBERSHOKE        | W   | 0.786      | -            | -                | -                | -         |     4.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           75 |     1548 | 2024-06-04 | Grannys Knockers  | W   | 0.785      | -            | -                | -                | -         |     3.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           74 |     1578 | 2024-06-03 | Johnny Speeds     | L   | 0.778      | -            | -                | -                | -         |    -8.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           73 |     1584 | 2024-06-02 | DMS               | W   | 0.773      | -            | -                | -                | -         |     7.92 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           72 |     1591 | 2024-06-02 | SAW               | W   | 0.772      | -            | -                | -                | -         |    15.14 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           71 |     1611 | 2024-06-01 | RUBY              | L   | 0.767      | -            | -                | -                | -         |   -17.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           70 |     1627 | 2024-06-01 | DMS               | W   | 0.765      | -            | -                | -                | -         |     6.92 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           69 |     1629 | 2024-06-01 | KOI               | W   | 0.765      | -            | -                | -                | -         |     9.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           68 |     1636 | 2024-06-01 | FURIA             | L   | 0.764      | -            | -                | -                | -         |    -1.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           67 |     1665 | 2024-05-31 | Passion UA        | W   | 0.758      | 0.435        | 0.173 (0.057)    | 1.000 (0.330)    | -         |    10.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           66 |     1673 | 2024-05-30 | ThunderFlash      | W   | 0.753      | -            | -                | -                | -         |     0.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           65 |     1686 | 2024-05-30 | Passion UA        | L   | 0.752      | -            | -                | -                | -         |   -13.35 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           64 |     1702 | 2024-05-29 | JANO              | W   | 0.747      | -            | -                | -                | -         |     1.92 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           63 |     1772 | 2024-05-26 | RUBY              | W   | 0.725      | -            | -                | -                | -         |     6.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           62 |     1785 | 2024-05-25 | ex-Guild Eagles   | W   | 0.720      | -            | -                | -                | -         |     4.74 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           61 |     1788 | 2024-05-25 | Serbia            | W   | 0.719      | -            | -                | -                | -         |     3.25 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           60 |     1798 | 2024-05-25 | Rhyno             | W   | 0.717      | -            | -                | -                | -         |     8.02 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           59 |     1803 | 2024-05-24 | ex-Guild Eagles   | L   | 0.713      | -            | -                | -                | -         |   -18.15 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           58 |     1806 | 2024-05-24 | The Suspect       | W   | 0.712      | -            | -                | -                | -         |     3.79 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           57 |     1822 | 2024-05-23 | 3DMAX             | L   | 0.705      | -            | -                | -                | -         |    -1.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           56 |     1829 | 2024-05-23 | brazylijski luz   | W   | 0.704      | -            | -                | -                | -         |     3.96 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           55 |     1862 | 2024-05-22 | Sangal            | L   | 0.699      | -            | -                | -                | -         |   -10.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           54 |     1872 | 2024-05-22 | Illuminar         | W   | 0.697      | -            | -                | -                | -         |     4.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           53 |     1906 | 2024-05-21 | BLEED             | W   | 0.692      | 0.500        | 0.126 (0.044)    | -                | -         |    18.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           52 |     1911 | 2024-05-21 | Verdant           | W   | 0.691      | -            | -                | -                | -         |     6.13 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           51 |     1934 | 2024-05-20 | Metizport         | W   | 0.687      | -            | -                | -                | -         |     4.26 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           50 |     1969 | 2024-05-19 | B8                | W   | 0.678      | 0.500        | 0.165 (0.056)    | 0.935 (0.317)    | -         |    12.90 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           49 |     2023 | 2024-05-17 | PARIVISION        | L   | 0.667      | -            | -                | -                | -         |   -10.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           48 |     2031 | 2024-05-17 | Endpoint          | W   | 0.665      | -            | -                | -                | -         |     6.78 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           47 |     2073 | 2024-05-16 | 1WIN              | L   | 0.658      | -            | -                | -                | -         |   -12.91 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           46 |     2080 | 2024-05-16 | kONO              | W   | 0.657      | -            | -                | -                | -         |     4.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           45 |     2122 | 2024-05-15 | 3DMAX             | W   | 0.652      | 0.500        | 0.508 (0.166)    | 1.000 (0.326)    | -         |    19.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           44 |     2182 | 2024-05-14 | Preasy            | W   | 0.645      | -            | -                | -                | -         |     1.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           43 |     2200 | 2024-05-13 | EYEBALLERS        | W   | 0.639      | -            | -                | -                | -         |     5.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           42 |     2228 | 2024-05-12 | Verdant           | W   | 0.631      | -            | -                | -                | -         |     6.90 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           41 |     2298 | 2024-05-09 | 9 Pandas          | L   | 0.612      | -            | -                | -                | -         |   -11.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           40 |     2353 | 2024-05-06 | Insilio           | W   | 0.593      | -            | -                | -                | -         |     6.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           39 |     2399 | 2024-05-03 | EYEBALLERS        | L   | 0.573      | -            | -                | -                | -         |   -12.67 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           38 |     2412 | 2024-05-03 | Metizport         | L   | 0.571      | -            | -                | -                | -         |   -13.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           37 |     2440 | 2024-05-02 | HAVU              | W   | 0.564      | -            | -                | -                | -         |     2.08 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           36 |     2462 | 2024-05-01 | KOI               | W   | 0.558      | -            | -                | -                | -         |     8.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           35 |     2475 | 2024-04-30 | Sangal            | L   | 0.552      | -            | -                | -                | -         |    -7.06 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           34 |     2487 | 2024-04-30 | B8                | W   | 0.551      | 0.435        | 0.165 (0.039)    | -                | -         |     7.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           33 |     2502 | 2024-04-29 | PARIVISION        | L   | 0.545      | -            | -                | -                | -         |    -8.07 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           32 |     2519 | 2024-04-28 | SINNERS           | W   | 0.538      | -            | -                | -                | -         |     9.43 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           31 |     2532 | 2024-04-27 | 500               | W   | 0.533      | -            | -                | -                | -         |     2.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           30 |     2552 | 2024-04-27 | SINNERS           | W   | 0.531      | -            | -                | -                | -         |     9.79 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           29 |     2576 | 2024-04-26 | Illuminar         | W   | 0.524      | -            | -                | -                | -         |     0.99 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           28 |     2598 | 2024-04-25 | EYEBALLERS        | L   | 0.518      | -            | -                | -                | -         |   -11.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           27 |     2621 | 2024-04-24 | ex-Guild Eagles   | L   | 0.511      | -            | -                | -                | -         |   -12.44 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           26 |     2637 | 2024-04-23 | Nemiga            | L   | 0.505      | -            | -                | -                | -         |    -5.93 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           25 |     2647 | 2024-04-22 | Grannys Knockers  | W   | 0.500      | -            | -                | -                | -         |     2.16 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           24 |     2653 | 2024-04-22 | Nexus             | W   | 0.498      | -            | -                | -                | -         |     3.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           23 |     2697 | 2024-04-20 | RUBY              | W   | 0.485      | -            | -                | -                | -         |     4.99 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           22 |     2727 | 2024-04-19 | PARIVISION        | W   | 0.480      | -            | -                | -                | -         |     7.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           21 |     2751 | 2024-04-19 | ALTERNATE aTTaX   | W   | 0.478      | -            | -                | -                | -         |     5.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           20 |     2810 | 2024-04-18 | B8                | L   | 0.471      | -            | -                | -                | -         |    -8.01 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           19 |     2832 | 2024-04-17 | B8                | W   | 0.465      | -            | -                | -                | -         |     6.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           18 |     2861 | 2024-04-16 | Sangal            | L   | 0.460      | -            | -                | -                | -         |    -5.76 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           17 |     2883 | 2024-04-15 | ALTERNATE aTTaX   | W   | 0.453      | -            | -                | -                | -         |     5.47 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           16 |     2933 | 2024-04-12 | JANO              | L   | 0.430      | -            | -                | -                | -         |   -12.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           15 |     2960 | 2024-04-11 | Alliance          | L   | 0.425      | -            | -                | -                | -         |   -10.43 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           14 |     3058 | 2024-04-09 | MOUZ NXT          | L   | 0.412      | -            | -                | -                | -         |    -7.08 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           13 |     3121 | 2024-04-07 | ex-Preasy         | L   | 0.398      | -            | -                | -                | -         |   -10.43 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           12 |     3290 | 2024-04-01 | Nemiga            | L   | 0.357      | -            | -                | -                | -         |    -4.64 | aVN, brutmonster, Cjoffo, kdaN, simke    |
|           11 |     3698 | 2024-03-10 | CYBERSHOKE        | L   | 0.213      | -            | -                | -                | -         |    -6.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           10 |     3710 | 2024-03-10 | ECLOT             | W   | 0.212      | -            | -                | -                | -         |     4.38 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            9 |     3729 | 2024-03-09 | Sangal            | W   | 0.205      | -            | -                | -                | -         |     3.67 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            8 |     3775 | 2024-03-07 | Nemiga            | L   | 0.193      | -            | -                | -                | -         |    -2.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            7 |     3810 | 2024-03-06 | AURA              | W   | 0.185      | -            | -                | -                | -         |     0.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            6 |     3841 | 2024-03-05 | AMKAL             | L   | 0.180      | -            | -                | -                | -         |    -2.54 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            5 |     3900 | 2024-03-03 | Secret            | W   | 0.164      | -            | -                | -                | -         |     0.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            4 |     3920 | 2024-03-02 | Secret            | W   | 0.158      | -            | -                | -                | -         |     0.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            3 |     3946 | 2024-02-29 | Young Ninjas      | W   | 0.145      | -            | -                | -                | -         |     0.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            2 |     4211 | 2024-02-17 | Sashi             | L   | 0.066      | -            | -                | -                | -         |    -0.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            1 |     4364 | 2024-02-10 | Sampi             | L   | 0.020      | -            | -                | -                | -         |    -0.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($46,022.29)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-05 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-10 |      0.827 | $2,000.00      | $1,653.33       |
| 2024-06-02 |      0.772 | $2,000.00      | $1,544.72       |
| 2024-05-22 |      0.699 | $25,000.00     | $17,475.69      |
| 2024-05-16 |      0.657 | $5,000.00      | $3,285.42       |
| 2024-05-04 |      0.579 | $2,000.00      | $1,158.61       |
| 2024-04-24 |      0.512 | $12,500.00     | $6,404.51       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
