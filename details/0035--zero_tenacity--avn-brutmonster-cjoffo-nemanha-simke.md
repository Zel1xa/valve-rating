### Roster Details<br />
Team Name: Zero Tenacity<br />
Roster: aVN, brutmonster, Cjoffo, nEMANHA, simke<br />
Global Rank: [35](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [26]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1171.5<br />
<br />
Final Rank Value (1171.5) = Starting Rank Value (1106.7) + Head To Head Adjustments (64.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.537[<sup>1</sup>](#table2)
- Bounty Collected: 0.483[<sup>2</sup>](#table1)
- Opponent Network: 0.350[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.343<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1106.7
- 400 + ( ( 0.343 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1106.7


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
|          104 |       12 | 2024-07-31 | KOI               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          103 |       62 | 2024-07-30 | Sashi             | W   | 1.000      | 0.500        | 0.185 (0.093)    | 0.973 (0.486)    | 0 (0.000) |    17.22 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          102 |      250 | 2024-07-24 | Insilio           | W   | 1.000      | 0.500        | -                | 0.554 (0.277)    | 0 (0.000) |     8.43 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          101 |      339 | 2024-07-21 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -17.33 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          100 |      366 | 2024-07-20 | B8                | W   | 1.000      | 0.500        | 0.167 (0.083)    | 0.879 (0.440)    | 0 (0.000) |    16.96 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           99 |      461 | 2024-07-18 | fnatic            | W   | 1.000      | 0.500        | 0.371 (0.185)    | 0.633 (0.316)    | 0 (0.000) |    27.39 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           98 |      577 | 2024-07-16 | Monte             | W   | 1.000      | 0.500        | -                | 0.613 (0.306)    | 0 (0.000) |    13.67 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           97 |      599 | 2024-07-16 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.513 (0.257)    | 0 (0.000) |     6.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           96 |      846 | 2024-06-16 | FAVBET            | W   | 0.899      | -            | -                | -                | 0 (0.000) |     5.81 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           95 |      878 | 2024-06-15 | Nemiga            | L   | 0.892      | -            | -                | -                | -         |   -11.08 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           94 |      919 | 2024-06-14 | RUBY              | W   | 0.886      | -            | -                | -                | 0 (0.000) |     7.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           93 |      959 | 2024-06-13 | Monte             | L   | 0.878      | -            | -                | -                | -         |   -15.80 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           92 |      984 | 2024-06-12 | 9INE              | W   | 0.872      | -            | -                | -                | 0 (0.000) |     1.14 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           91 |     1004 | 2024-06-11 | DMS               | W   | 0.866      | -            | -                | -                | -         |     8.13 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           90 |     1013 | 2024-06-11 | EYEBALLERS        | W   | 0.864      | -            | -                | -                | -         |     6.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           89 |     1090 | 2024-06-09 | HAVU              | W   | 0.851      | -            | -                | -                | -         |     3.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           88 |     1105 | 2024-06-09 | Nemiga            | L   | 0.850      | -            | -                | -                | -         |   -11.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           87 |     1124 | 2024-06-08 | Insilio           | L   | 0.846      | -            | -                | -                | -         |   -18.34 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           86 |     1143 | 2024-06-08 | Passion UA        | W   | 0.845      | 0.500        | 0.171 (0.072)    | 1.000 (0.423)    | -         |    11.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           85 |     1182 | 2024-06-07 | DMS               | W   | 0.839      | -            | -                | -                | -         |     8.15 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           84 |     1199 | 2024-06-07 | EYEBALLERS        | L   | 0.839      | -            | -                | -                | -         |   -19.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           83 |     1219 | 2024-06-07 | 5W                | L   | 0.837      | -            | -                | -                | -         |   -18.97 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           82 |     1243 | 2024-06-06 | FAVBET            | W   | 0.833      | -            | -                | -                | -         |     3.94 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           81 |     1269 | 2024-06-06 | Permitta          | L   | 0.832      | -            | -                | -                | -         |   -20.27 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           80 |     1288 | 2024-06-06 | GhoulsW           | W   | 0.830      | -            | -                | -                | -         |     0.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           79 |     1324 | 2024-06-05 | Aurora Young Blud | W   | 0.825      | -            | -                | -                | -         |     3.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           78 |     1363 | 2024-06-04 | CYBERSHOKE        | W   | 0.819      | -            | -                | -                | -         |     4.67 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           77 |     1373 | 2024-06-04 | Grannys Knockers  | W   | 0.818      | -            | -                | -                | -         |     3.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           76 |     1403 | 2024-06-03 | Johnny Speeds     | L   | 0.811      | -            | -                | -                | -         |    -8.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           75 |     1409 | 2024-06-02 | DMS               | W   | 0.806      | -            | -                | -                | -         |     8.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           74 |     1416 | 2024-06-02 | SAW               | W   | 0.805      | -            | -                | -                | -         |    16.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           73 |     1436 | 2024-06-01 | RUBY              | L   | 0.800      | -            | -                | -                | -         |   -18.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           72 |     1452 | 2024-06-01 | DMS               | W   | 0.798      | -            | -                | -                | -         |     7.17 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           71 |     1454 | 2024-06-01 | KOI               | W   | 0.798      | -            | -                | -                | -         |    10.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           70 |     1461 | 2024-06-01 | FURIA             | L   | 0.797      | -            | -                | -                | -         |    -1.49 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           69 |     1490 | 2024-05-31 | Passion UA        | W   | 0.791      | 0.435        | 0.171 (0.059)    | 1.000 (0.344)    | -         |    10.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           68 |     1498 | 2024-05-30 | ThunderFlash      | W   | 0.786      | -            | -                | -                | -         |     0.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           67 |     1511 | 2024-05-30 | Passion UA        | L   | 0.785      | -            | -                | -                | -         |   -14.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           66 |     1527 | 2024-05-29 | JANO              | W   | 0.780      | -            | -                | -                | -         |     1.97 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           65 |     1597 | 2024-05-26 | RUBY              | W   | 0.758      | -            | -                | -                | -         |     7.01 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           64 |     1610 | 2024-05-25 | ex-Guild Eagles   | W   | 0.753      | -            | -                | -                | -         |     5.14 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           63 |     1613 | 2024-05-25 | Serbia            | W   | 0.752      | -            | -                | -                | -         |     3.39 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           62 |     1623 | 2024-05-25 | Rhyno             | W   | 0.750      | -            | -                | -                | -         |     8.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           61 |     1628 | 2024-05-24 | ex-Guild Eagles   | L   | 0.746      | -            | -                | -                | -         |   -18.79 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           60 |     1631 | 2024-05-24 | Kosovo            | W   | 0.745      | -            | -                | -                | -         |     3.95 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           59 |     1647 | 2024-05-23 | 3DMAX             | L   | 0.738      | -            | -                | -                | -         |    -1.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           58 |     1654 | 2024-05-23 | brazylijski luz   | W   | 0.737      | -            | -                | -                | -         |     4.17 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           57 |     1687 | 2024-05-22 | Sangal            | L   | 0.732      | -            | -                | -                | -         |   -11.03 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           56 |     1697 | 2024-05-22 | Illuminar         | W   | 0.730      | -            | -                | -                | -         |     4.76 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           55 |     1731 | 2024-05-21 | BLEED             | W   | 0.725      | 0.500        | 0.127 (0.046)    | -                | -         |    18.96 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           54 |     1736 | 2024-05-21 | Verdant           | W   | 0.724      | -            | -                | -                | -         |     6.39 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           53 |     1759 | 2024-05-20 | Metizport         | W   | 0.719      | -            | -                | -                | -         |     8.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           52 |     1794 | 2024-05-19 | B8                | W   | 0.711      | 0.500        | 0.167 (0.059)    | 0.879 (0.313)    | -         |    13.76 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           51 |     1848 | 2024-05-17 | PARIVISION        | L   | 0.699      | -            | -                | -                | -         |   -11.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           50 |     1856 | 2024-05-17 | Endpoint          | W   | 0.698      | -            | -                | -                | -         |     7.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           49 |     1898 | 2024-05-16 | 1WIN              | L   | 0.691      | -            | -                | -                | -         |   -14.25 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           48 |     1905 | 2024-05-16 | kONO              | W   | 0.690      | -            | -                | -                | -         |     5.26 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           47 |     1947 | 2024-05-15 | 3DMAX             | W   | 0.684      | 0.500        | 0.499 (0.171)    | 1.000 (0.342)    | -         |    20.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           46 |     2007 | 2024-05-14 | Preasy            | W   | 0.677      | -            | -                | -                | -         |     3.95 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           45 |     2025 | 2024-05-13 | EYEBALLERS        | W   | 0.672      | -            | -                | -                | -         |     6.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           44 |     2053 | 2024-05-12 | Verdant           | W   | 0.664      | -            | -                | -                | -         |     7.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           43 |     2123 | 2024-05-09 | 9 Pandas          | L   | 0.644      | -            | -                | -                | -         |   -11.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           42 |     2178 | 2024-05-06 | Insilio           | W   | 0.625      | -            | -                | -                | -         |     7.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           41 |     2224 | 2024-05-03 | EYEBALLERS        | L   | 0.606      | -            | -                | -                | -         |   -13.17 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           40 |     2237 | 2024-05-03 | Metizport         | L   | 0.604      | -            | -                | -                | -         |   -12.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           39 |     2265 | 2024-05-02 | HAVU              | W   | 0.597      | -            | -                | -                | -         |     2.32 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           38 |     2287 | 2024-05-01 | KOI               | W   | 0.591      | -            | -                | -                | -         |    10.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           37 |     2300 | 2024-04-30 | Sangal            | L   | 0.585      | -            | -                | -                | -         |    -7.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           36 |     2312 | 2024-04-30 | B8                | W   | 0.584      | 0.435        | 0.167 (0.042)    | -                | -         |     8.64 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           35 |     2327 | 2024-04-29 | PARIVISION        | L   | 0.578      | -            | -                | -                | -         |    -8.71 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           34 |     2344 | 2024-04-28 | SINNERS           | W   | 0.571      | -            | -                | -                | -         |     8.03 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           33 |     2357 | 2024-04-27 | 500               | W   | 0.566      | -            | -                | -                | -         |     2.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           32 |     2377 | 2024-04-27 | SINNERS           | W   | 0.564      | -            | -                | -                | -         |     8.39 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           31 |     2401 | 2024-04-26 | Illuminar         | W   | 0.557      | -            | -                | -                | -         |     1.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           30 |     2423 | 2024-04-25 | EYEBALLERS        | L   | 0.551      | -            | -                | -                | -         |   -12.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           29 |     2446 | 2024-04-24 | ex-Guild Eagles   | L   | 0.544      | -            | -                | -                | -         |   -12.90 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           28 |     2462 | 2024-04-23 | Nemiga            | L   | 0.538      | -            | -                | -                | -         |    -6.32 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           27 |     2472 | 2024-04-22 | Grannys Knockers  | W   | 0.532      | -            | -                | -                | -         |     2.38 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           26 |     2478 | 2024-04-22 | Nexus             | W   | 0.531      | -            | -                | -                | -         |     3.94 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           25 |     2522 | 2024-04-20 | RUBY              | W   | 0.518      | -            | -                | -                | -         |     5.62 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           24 |     2552 | 2024-04-19 | PARIVISION        | W   | 0.513      | -            | -                | -                | -         |     7.94 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           23 |     2576 | 2024-04-19 | ALTERNATE aTTaX   | W   | 0.511      | -            | -                | -                | -         |     5.92 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           22 |     2635 | 2024-04-18 | B8                | L   | 0.504      | -            | -                | -                | -         |    -8.33 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           21 |     2657 | 2024-04-17 | B8                | W   | 0.498      | 0.500        | 0.167 (0.042)    | -                | -         |     7.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           20 |     2686 | 2024-04-16 | Sangal            | L   | 0.492      | -            | -                | -                | -         |    -6.35 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           19 |     2708 | 2024-04-15 | ALTERNATE aTTaX   | W   | 0.486      | -            | -                | -                | -         |     6.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           18 |     2758 | 2024-04-12 | JANO              | L   | 0.463      | -            | -                | -                | -         |   -13.08 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           17 |     2785 | 2024-04-11 | Alliance          | L   | 0.458      | -            | -                | -                | -         |   -11.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           16 |     2883 | 2024-04-09 | MOUZ NXT          | L   | 0.445      | -            | -                | -                | -         |    -7.52 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           15 |     2946 | 2024-04-07 | ex-Preasy         | L   | 0.430      | -            | -                | -                | -         |   -11.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           14 |     3115 | 2024-04-01 | Nemiga            | L   | 0.390      | -            | -                | -                | -         |    -5.11 | aVN, brutmonster, Cjoffo, kdaN, simke    |
|           13 |     3523 | 2024-03-10 | CYBERSHOKE        | L   | 0.246      | -            | -                | -                | -         |    -7.14 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           12 |     3535 | 2024-03-10 | ECLOT             | W   | 0.245      | -            | -                | -                | -         |     3.97 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           11 |     3554 | 2024-03-09 | Sangal            | W   | 0.238      | -            | -                | -                | -         |     4.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           10 |     3600 | 2024-03-07 | Nemiga            | L   | 0.225      | -            | -                | -                | -         |    -2.94 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            9 |     3635 | 2024-03-06 | AURA              | W   | 0.218      | -            | -                | -                | -         |     0.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            8 |     3666 | 2024-03-05 | AMKAL             | L   | 0.212      | -            | -                | -                | -         |    -2.91 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            7 |     3725 | 2024-03-03 | Secret            | W   | 0.197      | -            | -                | -                | -         |     0.26 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            6 |     3745 | 2024-03-02 | Secret            | W   | 0.190      | -            | -                | -                | -         |     0.25 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            5 |     3771 | 2024-02-29 | Young Ninjas      | W   | 0.178      | -            | -                | -                | -         |     0.73 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            4 |     4036 | 2024-02-17 | Sashi             | L   | 0.098      | -            | -                | -                | -         |    -1.26 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            3 |     4189 | 2024-02-10 | Sampi             | L   | 0.052      | -            | -                | -                | -         |    -1.27 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            2 |     4270 | 2024-02-04 | 500               | L   | 0.011      | -            | -                | -                | -         |    -0.32 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            1 |     4283 | 2024-02-03 | The Chosen Few    | W   | 0.006      | -            | -                | -                | -         |     0.02 | aVN, brutmonster, Cjoffo, nEMANHA, simke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($45,613.59)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-10 |      0.859 | $2,000.00      | $1,718.95       |
| 2024-06-02 |      0.805 | $2,000.00      | $1,610.34       |
| 2024-05-22 |      0.732 | $25,000.00     | $18,295.95      |
| 2024-05-16 |      0.690 | $5,000.00      | $3,449.47       |
| 2024-05-04 |      0.612 | $2,000.00      | $1,224.23       |
| 2024-04-24 |      0.545 | $12,500.00     | $6,814.64       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
