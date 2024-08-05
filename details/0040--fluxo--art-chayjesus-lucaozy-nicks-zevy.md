### Roster Details<br />
Team Name: Fluxo<br />
Roster: arT, chayJESUS, Lucaozy, nicks, zevy<br />
Global Rank: [40](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [10]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1132.3<br />
<br />
Final Rank Value (1132.3) = Starting Rank Value (1046.5) + Head To Head Adjustments (85.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.524[<sup>1</sup>](#table2)
- Bounty Collected: 0.450[<sup>2</sup>](#table1)
- Opponent Network: 0.290[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.316<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1046.5
- 400 + ( ( 0.316 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1046.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|          106 |       62 | 2024-08-02 | Legacy         | L   | 1.000      | -            | -                | -                | -         |   -17.48 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          105 |       79 | 2024-08-02 | MIBR           | L   | 1.000      | -            | -                | -                | -         |    -7.83 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          104 |      107 | 2024-08-01 | Intense        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.09 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          103 |      111 | 2024-08-01 | BESTIA         | W   | 1.000      | 0.371        | 0.095 (0.035)    | 0.802 (0.297)    | 0 (0.000) |     9.83 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          102 |      147 | 2024-07-31 | Hype           | W   | 1.000      | 0.450        | -                | 0.490 (0.221)    | 0 (0.000) |     5.65 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          101 |      151 | 2024-07-31 | Hype           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.96 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          100 |      200 | 2024-07-30 | Bounty Hunters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.48 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           99 |      240 | 2024-07-29 | Vikings KR     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.54 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           98 |      273 | 2024-07-28 | Intense        | L   | 1.000      | -            | -                | -                | -         |   -27.03 | arT, Lucaozy, nicks, vsm, zevy       |
|           97 |      315 | 2024-07-26 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -13.92 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           96 |      319 | 2024-07-26 | W7M            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.75 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           95 |      323 | 2024-07-26 | Solid          | L   | 1.000      | -            | -                | -                | -         |   -24.43 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           94 |      346 | 2024-07-25 | Hype           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.20 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           93 |      351 | 2024-07-25 | Imperium Nexus | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.41 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           92 |      389 | 2024-07-24 | RED Canids     | L   | 1.000      | -            | -                | -                | -         |   -15.47 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           91 |      392 | 2024-07-24 | Solid          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.42 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           90 |      422 | 2024-07-23 | BESTIA         | W   | 1.000      | -            | -                | -                | -         |     9.26 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           89 |      429 | 2024-07-23 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     3.41 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           88 |      432 | 2024-07-23 | Case           | L   | 1.000      | -            | -                | -                | -         |   -25.48 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           87 |      438 | 2024-07-23 | Solid          | W   | 1.000      | -            | -                | -                | -         |     5.02 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           86 |      462 | 2024-07-22 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |   -23.69 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           85 |      482 | 2024-07-21 | paiN           | W   | 1.000      | 0.384        | 0.326 (0.125)    | 0.868 (0.334)    | -         |    22.54 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           84 |      489 | 2024-07-21 | paiN           | L   | 1.000      | -            | -                | -                | -         |    -8.48 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           83 |      510 | 2024-07-20 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     7.59 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           82 |      523 | 2024-07-20 | ODDIK          | W   | 1.000      | -            | -                | -                | -         |     9.19 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           81 |      545 | 2024-07-19 | Vikings KR     | W   | 1.000      | -            | -                | -                | -         |     4.12 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           80 |      548 | 2024-07-19 | paiN           | L   | 1.000      | -            | -                | -                | -         |    -8.77 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           79 |      554 | 2024-07-19 | Case           | W   | 1.000      | -            | -                | -                | -         |     5.63 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           78 |      588 | 2024-07-18 | Sharks         | W   | 1.000      | 0.450        | -                | 0.566 (0.255)    | -         |     8.02 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           77 |      590 | 2024-07-18 | Sharks         | W   | 1.000      | 0.450        | -                | 0.566 (0.255)    | -         |     8.59 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           76 |      600 | 2024-07-18 | Galorys        | W   | 1.000      | -            | -                | -                | -         |     3.91 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           75 |      656 | 2024-07-17 | BESTIA         | W   | 1.000      | 0.450        | 0.095 (0.043)    | 0.802 (0.361)    | -         |     9.45 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           74 |      661 | 2024-07-17 | BESTIA         | W   | 1.000      | 0.450        | 0.095 (0.043)    | 0.802 (0.361)    | -         |    10.19 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           73 |      764 | 2024-07-15 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     3.70 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           72 |      769 | 2024-07-15 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     3.84 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           71 |      996 | 2024-06-16 | paiN           | W   | 0.871      | 0.450        | 0.326 (0.128)    | 0.868 (0.340)    | -         |    21.34 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           70 |     1024 | 2024-06-15 | inSanitY       | W   | 0.865      | -            | -                | -                | -         |     8.96 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           69 |     1060 | 2024-06-14 | Sharks         | W   | 0.859      | -            | -                | -                | -         |    11.59 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           68 |     1270 | 2024-06-08 | KRÜ            | W   | 0.819      | -            | -                | -                | -         |     6.34 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           67 |     1348 | 2024-06-07 | Bounty Hunters | W   | 0.811      | -            | -                | -                | -         |     6.74 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           66 |     1413 | 2024-06-06 | W7M            | W   | 0.804      | -            | -                | -                | -         |     4.22 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           65 |     1453 | 2024-06-05 | paiN           | L   | 0.799      | -            | -                | -                | -         |    -4.41 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           64 |     1505 | 2024-06-04 | 9z             | L   | 0.793      | -            | -                | -                | -         |    -2.43 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           63 |     1828 | 2024-05-22 | BESTIA         | L   | 0.705      | -            | -                | -                | -         |   -12.28 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           62 |     1831 | 2024-05-22 | BESTIA         | L   | 0.705      | -            | -                | -                | -         |   -13.05 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           61 |     1902 | 2024-05-20 | RED Canids     | W   | 0.693      | 0.450        | 0.077 (0.024)    | 0.758 (0.236)    | -         |    12.66 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           60 |     1905 | 2024-05-20 | RED Canids     | L   | 0.693      | -            | -                | -                | -         |    -9.25 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           59 |     1963 | 2024-05-18 | 9z             | L   | 0.678      | -            | -                | -                | -         |    -2.25 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           58 |     1997 | 2024-05-17 | Case           | W   | 0.672      | -            | -                | -                | -         |     5.51 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           57 |     2031 | 2024-05-16 | RED Canids     | L   | 0.666      | -            | -                | -                | -         |   -10.10 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           56 |     2076 | 2024-05-15 | Smoke          | W   | 0.659      | -            | -                | -                | -         |     2.07 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           55 |     2077 | 2024-05-15 | Smoke          | W   | 0.659      | -            | -                | -                | -         |     2.11 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           54 |     2091 | 2024-05-15 | Imperial       | L   | 0.658      | -            | -                | -                | -         |    -5.75 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           53 |     2141 | 2024-05-14 | Sharks         | W   | 0.652      | -            | -                | -                | -         |     7.21 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           52 |     2154 | 2024-05-14 | ODDIK          | W   | 0.651      | 0.384        | 0.099 (0.025)    | -                | -         |     6.93 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           51 |     2174 | 2024-05-13 | Hype           | W   | 0.644      | -            | -                | -                | -         |     4.60 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           50 |     2201 | 2024-05-12 | Vikings KR     | W   | 0.637      | -            | -                | -                | -         |     3.77 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           49 |     2261 | 2024-05-09 | paiN           | W   | 0.620      | 0.450        | 0.326 (0.091)    | 0.868 (0.242)    | -         |    16.62 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           48 |     2266 | 2024-05-09 | paiN           | L   | 0.620      | -            | -                | -                | -         |    -2.82 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           47 |     2740 | 2024-04-18 | paiN           | L   | 0.480      | -            | -                | -                | -         |    -2.15 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           46 |     2747 | 2024-04-18 | Imperial       | L   | 0.479      | -            | -                | -                | -         |    -3.61 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           45 |     2794 | 2024-04-17 | ODDIK          | W   | 0.473      | -            | -                | -                | -         |     5.04 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           44 |     2802 | 2024-04-17 | Solid          | W   | 0.472      | -            | -                | -                | -         |     3.84 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           43 |     2833 | 2024-04-16 | Hype           | W   | 0.466      | -            | -                | -                | -         |     3.77 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           42 |     2892 | 2024-04-13 | Galorys        | L   | 0.444      | -            | -                | -                | -         |   -10.02 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           41 |     2958 | 2024-04-10 | Imperial       | W   | 0.426      | 0.450        | 0.236 (0.045)    | -                | -         |    10.36 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           40 |     2961 | 2024-04-10 | Imperial       | L   | 0.426      | -            | -                | -                | -         |    -3.06 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           39 |     3011 | 2024-04-09 | ODDIK          | W   | 0.419      | -            | -                | -                | -         |     4.60 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           38 |     3016 | 2024-04-09 | ODDIK          | W   | 0.419      | -            | -                | -                | -         |     4.76 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           37 |     3052 | 2024-04-08 | ODDIK          | W   | 0.412      | -            | -                | -                | -         |     4.84 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           36 |     3102 | 2024-04-06 | BESTIA         | L   | 0.399      | -            | -                | -                | -         |    -7.61 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           35 |     3103 | 2024-04-06 | Solid          | W   | 0.399      | -            | -                | -                | -         |     3.53 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           34 |     3118 | 2024-04-05 | MIBR           | L   | 0.393      | -            | -                | -                | -         |    -1.60 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           33 |     3119 | 2024-04-05 | MIBR           | W   | 0.393      | 0.450        | 0.209 (0.037)    | -                | -         |    10.89 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           32 |     3146 | 2024-04-04 | Corinthians    | W   | 0.386      | -            | -                | -                | -         |     0.55 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           31 |     3152 | 2024-04-04 | Corinthians    | W   | 0.386      | -            | -                | -                | -         |     0.56 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           30 |     3166 | 2024-04-04 | RED Canids     | L   | 0.384      | -            | -                | -                | -         |    -5.36 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           29 |     3182 | 2024-04-03 | MIBR           | L   | 0.380      | -            | -                | -                | -         |    -1.46 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           28 |     3193 | 2024-04-03 | BESTIA         | W   | 0.378      | -            | -                | -                | -         |     5.10 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           27 |     3230 | 2024-04-02 | MIBR           | L   | 0.373      | -            | -                | -                | -         |    -1.42 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           26 |     3234 | 2024-04-02 | BESTIA         | W   | 0.372      | -            | -                | -                | -         |     5.12 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           25 |     3318 | 2024-03-27 | Galorys        | L   | 0.333      | -            | -                | -                | -         |    -7.43 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           24 |     3324 | 2024-03-27 | Galorys        | W   | 0.333      | -            | -                | -                | -         |     3.09 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           23 |     3593 | 2024-03-13 | Intense        | W   | 0.239      | -            | -                | -                | -         |     1.17 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           22 |     3607 | 2024-03-13 | Solid          | L   | 0.238      | -            | -                | -                | -         |    -5.37 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           21 |     3633 | 2024-03-12 | MIBR           | W   | 0.232      | -            | -                | -                | -         |     6.44 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           20 |     3665 | 2024-03-11 | Sharks         | W   | 0.224      | -            | -                | -                | -         |     2.80 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           19 |     3708 | 2024-03-09 | Corinthians    | W   | 0.210      | -            | -                | -                | -         |     0.31 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           18 |     3743 | 2024-03-07 | Case           | L   | 0.199      | -            | -                | -                | -         |    -4.20 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           17 |     3768 | 2024-03-06 | Solid          | L   | 0.193      | -            | -                | -                | -         |    -4.33 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           16 |     3769 | 2024-03-06 | Solid          | W   | 0.193      | -            | -                | -                | -         |     1.77 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           15 |     3835 | 2024-03-04 | Case           | W   | 0.180      | -            | -                | -                | -         |     1.93 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           14 |     3836 | 2024-03-04 | Case           | W   | 0.179      | -            | -                | -                | -         |     1.96 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           13 |     3993 | 2024-02-25 | Imperial       | W   | 0.125      | -            | -                | -                | -         |     3.04 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           12 |     4023 | 2024-02-24 | Sharks         | W   | 0.119      | -            | -                | -                | -         |     1.49 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           11 |     4073 | 2024-02-21 | W7M            | L   | 0.100      | -            | -                | -                | -         |    -2.40 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           10 |     4078 | 2024-02-21 | W7M            | W   | 0.099      | -            | -                | -                | -         |     0.75 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            9 |     4082 | 2024-02-21 | Solid          | W   | 0.098      | -            | -                | -                | -         |     0.94 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            8 |     4110 | 2024-02-20 | Solid          | L   | 0.092      | -            | -                | -                | -         |    -2.03 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            7 |     4207 | 2024-02-16 | 9z             | W   | 0.065      | -            | -                | -                | -         |     1.94 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            6 |     4234 | 2024-02-15 | Imperial       | L   | 0.059      | -            | -                | -                | -         |    -0.43 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            5 |     4236 | 2024-02-15 | W7M            | W   | 0.059      | -            | -                | -                | -         |     0.45 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            4 |     4241 | 2024-02-15 | Sharks         | W   | 0.058      | -            | -                | -                | -         |     0.73 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            3 |     4242 | 2024-02-15 | Sharks         | W   | 0.058      | -            | -                | -                | -         |     0.73 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            2 |     4265 | 2024-02-14 | Intense        | W   | 0.053      | -            | -                | -                | -         |     0.27 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            1 |     4330 | 2024-02-12 | Flamengo       | W   | 0.037      | -            | -                | -                | -         |     0.05 | chayJESUS, Lucaozy, PKL, vsm, zevy   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($40,020.37)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-07-22 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-16 |      0.871 | $30,000.00     | $26,141.67      |
| 2024-06-09 |      0.825 | $2,000.00      | $1,650.93       |
| 2024-05-19 |      0.685 | $2,000.00      | $1,369.44       |
| 2024-03-14 |      0.245 | $5,000.00      | $1,226.39       |
| 2024-02-25 |      0.125 | $25,000.00     | $3,131.94       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
