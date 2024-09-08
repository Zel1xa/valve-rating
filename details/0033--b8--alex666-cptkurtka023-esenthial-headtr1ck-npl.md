### Roster Details<br />
Team Name: B8<br />
Roster: alex666, cptkurtka023, esenthial, headtr1ck, npl<br />
Global Rank: [33](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [25]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1142.7<br />
<br />
Final Rank Value (1142.7) = Starting Rank Value (1065.6) + Head To Head Adjustments (77.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.570[<sup>1</sup>](#table2)
- Bounty Collected: 0.451[<sup>2</sup>](#table1)
- Opponent Network: 0.355[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.344<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1065.6
- 400 + ( ( 0.344 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 1065.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|          111 |        0 | 2024-09-08 | Zero Tenacity   | W   | 1.000      | 0.435        | 0.163 (0.071)    | 1.000 (0.435)    | 0 (0.000) |    12.87 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|          110 |       19 | 2024-09-07 | BLEED           | W   | 1.000      | 0.435        | 0.101 (0.044)    | -                | 0 (0.000) |    11.87 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|          109 |       38 | 2024-09-06 | 9 Pandas        | L   | 1.000      | -            | -                | -                | -         |   -14.42 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|          108 |       69 | 2024-09-05 | SINNERS         | W   | 1.000      | 0.500        | 0.081 (0.041)    | 1.000 (0.500)    | 0 (0.000) |    13.37 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|          107 |       92 | 2024-09-05 | 9INE            | W   | 1.000      | 0.435        | -                | 0.707 (0.307)    | 0 (0.000) |     9.63 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|          106 |      155 | 2024-09-03 | TSM             | L   | 1.000      | -            | -                | -                | -         |   -18.32 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|          105 |      188 | 2024-09-02 | BLEED           | W   | 1.000      | 0.384        | 0.101 (0.039)    | -                | 0 (0.000) |    12.03 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|          104 |      288 | 2024-08-29 | Revenant        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.95 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|          103 |      314 | 2024-08-28 | ALTERNATE aTTaX | L   | 1.000      | -            | -                | -                | -         |   -22.44 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|          102 |      321 | 2024-08-28 | SINNERS         | W   | 1.000      | 0.435        | 0.081 (0.035)    | 1.000 (0.435)    | 0 (0.000) |    17.34 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|          101 |      368 | 2024-08-27 | Endpoint        | W   | 1.000      | 0.435        | -                | 0.723 (0.314)    | 0 (0.000) |     9.63 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|          100 |      390 | 2024-08-27 | 9INE            | L   | 1.000      | -            | -                | -                | -         |   -22.17 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           99 |      444 | 2024-08-26 | HEROIC          | L   | 1.000      | -            | -                | -                | -         |    -6.97 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           98 |      461 | 2024-08-26 | Eternal Fire    | L   | 1.000      | -            | -                | -                | -         |    -1.05 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           97 |      507 | 2024-08-25 | Revenant        | W   | 1.000      | 0.435        | -                | 0.666 (0.289)    | 0 (0.000) |     8.05 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           96 |      548 | 2024-08-23 | Monte           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.57 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           95 |      568 | 2024-08-23 | Rhyno           | W   | 1.000      | -            | -                | -                | -         |     2.70 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           94 |      594 | 2024-08-22 | PARIVISION      | L   | 1.000      | -            | -                | -                | -         |   -15.69 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           93 |      619 | 2024-08-21 | Enterprise      | W   | 1.000      | -            | -                | -                | -         |     6.91 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           92 |      660 | 2024-08-21 | SINNERS         | L   | 1.000      | -            | -                | -                | -         |   -17.34 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           91 |      684 | 2024-08-20 | RUSH B          | W   | 1.000      | -            | -                | -                | -         |     7.42 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           90 |      708 | 2024-08-19 | Monte           | W   | 1.000      | -            | -                | -                | -         |    10.91 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           89 |      710 | 2024-08-19 | Sashi           | W   | 1.000      | -            | -                | -                | -         |    15.06 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           88 |      717 | 2024-08-19 | AMKAL           | W   | 1.000      | -            | -                | -                | -         |    13.65 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           87 |      760 | 2024-08-17 | GenOne          | W   | 1.000      | -            | -                | -                | -         |     1.31 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           86 |      765 | 2024-08-17 | Lazer Cats      | W   | 1.000      | -            | -                | -                | -         |     1.24 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           85 |      810 | 2024-08-15 | OG              | L   | 1.000      | -            | -                | -                | -         |   -20.26 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           84 |      812 | 2024-08-15 | Spirit Academy  | W   | 1.000      | -            | -                | -                | -         |     4.86 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           83 |      824 | 2024-08-15 | BLEED           | W   | 1.000      | -            | -                | -                | -         |    17.97 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           82 |      869 | 2024-08-13 | KOI             | W   | 1.000      | -            | -                | -                | -         |    10.24 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           81 |      920 | 2024-08-12 | SINNERS         | L   | 1.000      | -            | -                | -                | -         |   -19.35 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           80 |      982 | 2024-08-10 | Nemiga          | L   | 1.000      | -            | -                | -                | -         |   -12.76 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           79 |     1009 | 2024-08-09 | TALON           | W   | 1.000      | -            | -                | -                | -         |     1.81 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           78 |     1058 | 2024-08-07 | Nemiga          | L   | 0.988      | -            | -                | -                | -         |   -14.55 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           77 |     1081 | 2024-08-07 | 9INE            | W   | 0.986      | 0.426        | -                | 0.707 (0.297)    | -         |     8.14 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           76 |     1138 | 2024-08-05 | Permitta        | L   | 0.975      | -            | -                | -                | -         |   -22.36 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           75 |     1165 | 2024-08-04 | BC.Game         | W   | 0.968      | -            | -                | -                | -         |     7.92 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           74 |     1234 | 2024-08-02 | Space           | W   | 0.954      | -            | -                | -                | -         |     4.39 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           73 |     1316 | 2024-07-31 | Qiang           | W   | 0.941      | -            | -                | -                | -         |     6.92 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           72 |     1369 | 2024-07-30 | ARCRED          | W   | 0.934      | -            | -                | -                | -         |     8.16 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           71 |     1472 | 2024-07-27 | Sangal          | L   | 0.912      | -            | -                | -                | -         |    -7.48 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           70 |     1520 | 2024-07-25 | SINNERS         | W   | 0.902      | 0.435        | 0.081 (0.032)    | 1.000 (0.392)    | -         |     9.95 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           69 |     1679 | 2024-07-20 | Zero Tenacity   | L   | 0.868      | -            | -                | -                | -         |   -14.27 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           68 |     1734 | 2024-07-19 | Rebels          | W   | 0.859      | 0.500        | -                | 0.656 (0.282)    | -         |     7.72 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           67 |     1764 | 2024-07-18 | Aurora          | L   | 0.855      | -            | -                | -                | -         |    -5.93 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           66 |     1844 | 2024-07-17 | Sangal          | L   | 0.847      | -            | -                | -                | -         |    -6.91 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           65 |     1949 | 2024-07-15 | 9INE            | W   | 0.834      | 0.500        | -                | 0.707 (0.295)    | -         |     5.93 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           64 |     2164 | 2024-06-16 | 3DMAX           | W   | 0.641      | 0.435        | 0.509 (0.142)    | -                | -         |    18.62 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           63 |     2174 | 2024-06-16 | Monte           | W   | 0.639      | -            | -                | -                | -         |     7.76 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           62 |     2208 | 2024-06-15 | Illuminar       | W   | 0.633      | -            | -                | -                | -         |     4.66 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           61 |     2288 | 2024-06-13 | MOUZ NXT        | W   | 0.619      | -            | -                | -                | -         |     8.08 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           60 |     2308 | 2024-06-12 | BLEED           | L   | 0.613      | -            | -                | -                | -         |    -6.52 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           59 |     2405 | 2024-06-09 | AMKAL           | L   | 0.593      | -            | -                | -                | -         |    -8.21 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           58 |     2513 | 2024-06-07 | Verdant         | W   | 0.581      | -            | -                | -                | -         |     3.95 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           57 |     2514 | 2024-06-07 | Qiang           | W   | 0.581      | -            | -                | -                | -         |     4.68 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           56 |     2530 | 2024-06-07 | Verdant         | L   | 0.580      | -            | -                | -                | -         |   -14.54 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           55 |     2823 | 2024-05-30 | SINNERS         | L   | 0.527      | -            | -                | -                | -         |    -8.47 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           54 |     2915 | 2024-05-26 | MOUZ NXT        | L   | 0.499      | -            | -                | -                | -         |   -10.26 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           53 |     2923 | 2024-05-25 | RUBY            | W   | 0.495      | -            | -                | -                | -         |     3.62 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           52 |     2930 | 2024-05-25 | BetBoom         | W   | 0.494      | 0.435        | 0.229 (0.049)    | -                | -         |    10.51 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           51 |     2945 | 2024-05-24 | Alliance        | W   | 0.488      | -            | -                | -                | -         |     2.79 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           50 |     2965 | 2024-05-23 | DMS             | W   | 0.480      | -            | -                | -                | -         |     3.56 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           49 |     3043 | 2024-05-21 | Rhyno           | W   | 0.468      | -            | -                | -                | -         |     3.37 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           48 |     3083 | 2024-05-20 | EYEBALLERS      | W   | 0.460      | -            | -                | -                | -         |     2.55 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           47 |     3110 | 2024-05-19 | Zero Tenacity   | L   | 0.453      | -            | -                | -                | -         |    -8.06 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           46 |     3131 | 2024-05-18 | Sashi           | W   | 0.448      | -            | -                | -                | -         |     7.54 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           45 |     3146 | 2024-05-18 | Rebels          | W   | 0.446      | -            | -                | -                | -         |     4.19 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           44 |     3177 | 2024-05-17 | 3DMAX           | W   | 0.440      | 0.500        | 0.509 (0.112)    | -                | -         |    13.38 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           43 |     3204 | 2024-05-16 | DMS             | W   | 0.434      | -            | -                | -                | -         |     3.45 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           42 |     3216 | 2024-05-16 | Sampi           | W   | 0.432      | -            | -                | -                | -         |     3.98 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           41 |     3250 | 2024-05-15 | PARIVISION      | L   | 0.428      | -            | -                | -                | -         |    -6.90 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           40 |     3318 | 2024-05-14 | Verdant         | W   | 0.420      | -            | -                | -                | -         |     3.02 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           39 |     3324 | 2024-05-14 | MOUZ NXT        | W   | 0.419      | -            | -                | -                | -         |     5.30 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           38 |     3362 | 2024-05-12 | BetBoom         | W   | 0.408      | 0.435        | 0.229 (0.041)    | -                | -         |     9.29 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           37 |     3370 | 2024-05-12 | MOUZ NXT        | W   | 0.406      | -            | -                | -                | -         |     5.42 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           36 |     3404 | 2024-05-11 | BLEED           | W   | 0.399      | -            | -                | -                | -         |     4.08 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           35 |     3440 | 2024-05-09 | KOI             | W   | 0.386      | -            | -                | -                | -         |     4.46 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           34 |     3497 | 2024-05-06 | Enterprise      | W   | 0.367      | -            | -                | -                | -         |     3.11 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           33 |     3533 | 2024-05-04 | GL Academy      | W   | 0.353      | -            | -                | -                | -         |     1.38 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           32 |     3582 | 2024-05-02 | Permitta        | W   | 0.339      | -            | -                | -                | -         |     3.82 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           31 |     3587 | 2024-05-01 | Nemiga          | L   | 0.335      | -            | -                | -                | -         |    -3.52 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           30 |     3591 | 2024-05-01 | NewBALLS        | W   | 0.334      | -            | -                | -                | -         |     0.49 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           29 |     3607 | 2024-05-01 | SINNERS         | W   | 0.332      | -            | -                | -                | -         |     6.36 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           28 |     3623 | 2024-04-30 | Alliance        | W   | 0.326      | -            | -                | -                | -         |     2.68 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           27 |     3628 | 2024-04-30 | Zero Tenacity   | L   | 0.326      | -            | -                | -                | -         |    -4.90 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           26 |     3653 | 2024-04-28 | BLEED           | L   | 0.315      | -            | -                | -                | -         |    -6.69 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           25 |     3701 | 2024-04-26 | Alliance        | W   | 0.301      | -            | -                | -                | -         |     2.28 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           24 |     3773 | 2024-04-23 | BLEED           | L   | 0.281      | -            | -                | -                | -         |    -6.19 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           23 |     3787 | 2024-04-22 | Passion UA      | W   | 0.275      | -            | -                | -                | -         |     4.00 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           22 |     3793 | 2024-04-22 | Alliance        | L   | 0.273      | -            | -                | -                | -         |    -6.60 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           21 |     3812 | 2024-04-21 | PARIVISION      | W   | 0.266      | -            | -                | -                | -         |     4.37 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           20 |     3890 | 2024-04-19 | HAVU            | W   | 0.253      | -            | -                | -                | -         |     0.52 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           19 |     3951 | 2024-04-18 | Zero Tenacity   | W   | 0.246      | -            | -                | -                | -         |     3.97 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           18 |     3973 | 2024-04-17 | Zero Tenacity   | L   | 0.240      | -            | -                | -                | -         |    -3.74 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           17 |     4013 | 2024-04-16 | AMKAL           | L   | 0.233      | -            | -                | -                | -         |    -3.13 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           16 |     4023 | 2024-04-15 | Sangal          | L   | 0.228      | -            | -                | -                | -         |    -1.34 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           15 |     4144 | 2024-04-10 | Nexus           | L   | 0.193      | -            | -                | -                | -         |    -4.87 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           14 |     4188 | 2024-04-09 | Rebels          | L   | 0.188      | -            | -                | -                | -         |    -3.99 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           13 |     4234 | 2024-04-08 | MOUZ NXT        | L   | 0.180      | -            | -                | -                | -         |    -3.45 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           12 |     4403 | 2024-04-02 | Metizport       | L   | 0.141      | -            | -                | -                | -         |    -3.80 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           11 |     4410 | 2024-04-02 | Apeks           | L   | 0.140      | -            | -                | -                | -         |    -3.75 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           10 |     4435 | 2024-03-31 | Apeks           | W   | 0.127      | -            | -                | -                | -         |     0.61 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            9 |     4448 | 2024-03-29 | Space           | L   | 0.114      | -            | -                | -                | -         |    -2.93 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            8 |     4495 | 2024-03-27 | Rebels          | W   | 0.102      | -            | -                | -                | -         |     0.99 | baz, cptkurtka023, esenthial, npl, OWNER         |
|            7 |     4506 | 2024-03-27 | Sampi           | W   | 0.101      | -            | -                | -                | -         |     0.91 | baz, cptkurtka023, esenthial, npl, OWNER         |
|            6 |     4538 | 2024-03-25 | FORZE           | W   | 0.087      | -            | -                | -                | -         |     0.49 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            5 |     4599 | 2024-03-21 | BetBoom         | L   | 0.059      | -            | -                | -                | -         |    -0.54 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            4 |     4636 | 2024-03-19 | ex-Sprout       | W   | 0.046      | -            | -                | -                | -         |     0.03 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            3 |     4703 | 2024-03-15 | 3DMAX           | L   | 0.021      | -            | -                | -                | -         |    -0.02 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            2 |     4797 | 2024-03-12 | Metizport       | L   | 0.002      | -            | -                | -                | -         |    -0.04 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            1 |     4804 | 2024-03-12 | ENCE            | W   | 0.000      | -            | -                | -                | -         |     0.01 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($53,335.17)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.18) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-28 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-08-11 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-08-06 |      0.981 | $2,000.00      | $1,961.94       |
| 2024-07-28 |      0.921 | $2,000.00      | $1,841.94       |
| 2024-06-16 |      0.641 | $22,000.00     | $14,098.33      |
| 2024-06-09 |      0.594 | $1,500.00      | $891.15         |
| 2024-05-26 |      0.501 | $5,000.00      | $2,504.17       |
| 2024-05-18 |      0.448 | $10,000.00     | $4,477.78       |
| 2024-05-12 |      0.408 | $22,000.00     | $8,969.58       |
| 2024-04-24 |      0.287 | $12,500.00     | $3,590.28       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
