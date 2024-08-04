### Roster Details<br />
Team Name: Sampi<br />
Roster: fino, manguss, sAvana1, The eLiVe, ZEDKO<br />
Global Rank: [95](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [69]( ../standings_europe.md)<br />
<br />
Final Rank Value:  862.5<br />
<br />
Final Rank Value (862.5) = Starting Rank Value (886.4) + Head To Head Adjustments (-23.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.390[<sup>1</sup>](#table2)
- Bounty Collected: 0.375[<sup>2</sup>](#table1)
- Opponent Network: 0.186[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.238<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 886.4
- 400 + ( ( 0.238 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 886.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           93 |       94 | 2024-08-01 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -14.07 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           92 |      103 | 2024-08-01 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -16.76 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           91 |      133 | 2024-07-31 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -14.52 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           90 |      150 | 2024-07-31 | Illuminar         | L   | 1.000      | -            | -                | -                | -         |   -15.27 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           89 |      189 | 2024-07-30 | CYBERSHOKE        | W   | 1.000      | 0.426        | 0.039 (0.017)    | -                | 0 (0.000) |    17.06 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           88 |      200 | 2024-07-30 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.74 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           87 |      227 | 2024-07-29 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -14.67 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           86 |      248 | 2024-07-28 | CPH Wolves        | W   | 1.000      | 0.435        | -                | 0.364 (0.158)    | 0 (0.000) |    12.94 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           85 |      296 | 2024-07-26 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.522 (0.227)    | 0 (0.000) |    12.79 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           84 |      308 | 2024-07-26 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -1.35 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           83 |      378 | 2024-07-24 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -12.47 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           82 |      409 | 2024-07-23 | CPH Wolves        | W   | 1.000      | 0.435        | -                | 0.364 (0.158)    | 0 (0.000) |    13.70 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           81 |      448 | 2024-07-22 | INFINITE          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.36 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           80 |      460 | 2024-07-21 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.33 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           79 |      536 | 2024-07-19 | Metizport         | L   | 1.000      | -            | -                | -                | -         |   -12.58 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           78 |      584 | 2024-07-18 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -15.92 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           77 |      710 | 2024-07-16 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | 0.502 (0.218)    | 0 (0.000) |    15.29 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           76 |      721 | 2024-07-16 | Meteor            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.66 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           75 |      775 | 2024-07-14 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -15.93 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           74 |      779 | 2024-07-14 | Portugal          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.75 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           73 |      840 | 2024-07-10 | Hungary           | W   | 1.000      | -            | -                | -                | -         |    11.41 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           72 |      879 | 2024-07-08 | Austria           | W   | 1.000      | -            | -                | -                | -         |     1.93 | fino, M1key, MATYS, sAvana1, The eLiVe      |
|           71 |     1081 | 2024-06-13 | Rebels            | W   | 0.854      | 0.379        | 0.038 (0.012)    | 0.599 (0.194)    | -         |    18.19 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           70 |     1088 | 2024-06-13 | Sashi             | L   | 0.853      | -            | -                | -                | -         |    -3.52 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           69 |     1112 | 2024-06-12 | Enterprise        | L   | 0.847      | -            | -                | -                | -         |   -11.07 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           68 |     1131 | 2024-06-11 | Astralis Talent   | W   | 0.841      | -            | -                | -                | -         |     8.62 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           67 |     1141 | 2024-06-11 | Illuminar         | L   | 0.839      | -            | -                | -                | -         |   -12.48 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           66 |     1201 | 2024-06-09 | Aurora Young Blud | L   | 0.827      | -            | -                | -                | -         |   -14.58 | fino, manguss, sAvana1, The eLiVe, Verttzzz |
|           65 |     1270 | 2024-06-08 | MOUZ NXT          | L   | 0.821      | -            | -                | -                | -         |    -6.56 | fino, manguss, sAvana1, The eLiVe, Verttzzz |
|           64 |     1289 | 2024-06-08 | CYBERSHOKE        | L   | 0.819      | -            | -                | -                | -         |   -14.75 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           63 |     1391 | 2024-06-06 | Nemiga            | L   | 0.807      | -            | -                | -                | -         |    -6.50 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           62 |     1407 | 2024-06-06 | HAVU              | W   | 0.806      | -            | -                | -                | -         |     6.47 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           61 |     1450 | 2024-06-05 | NAVI Junior       | W   | 0.801      | -            | -                | -                | -         |     3.02 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           60 |     1487 | 2024-06-04 | INFINITE          | W   | 0.795      | -            | -                | -                | -         |     3.05 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           59 |     1507 | 2024-06-04 | DMS               | W   | 0.792      | 0.500        | -                | 0.446 (0.177)    | -         |    14.76 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           58 |     1531 | 2024-06-03 | Rare Atom         | W   | 0.785      | 0.435        | -                | 0.480 (0.164)    | -         |     6.03 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           57 |     1582 | 2024-06-01 | SINNERS           | L   | 0.773      | -            | -                | -                | -         |    -7.18 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           56 |     1603 | 2024-05-31 | ECLOT             | L   | 0.768      | -            | -                | -                | -         |    -5.10 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           55 |     1627 | 2024-05-30 | 3DMAX             | L   | 0.762      | -            | -                | -                | -         |    -0.64 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           54 |     1680 | 2024-05-28 | Enterprise        | L   | 0.747      | -            | -                | -                | -         |   -11.87 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           53 |     1683 | 2024-05-28 | Rhyno             | W   | 0.747      | 0.435        | 0.071 (0.023)    | -                | -         |    14.30 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           52 |     1718 | 2024-05-26 | SINNERS           | L   | 0.734      | -            | -                | -                | -         |    -7.48 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           51 |     1736 | 2024-05-25 | Passion UA        | L   | 0.727      | -            | -                | -                | -         |    -7.59 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           50 |     1767 | 2024-05-23 | GUN5              | W   | 0.715      | 0.435        | 0.073 (0.023)    | 0.570 (0.177)    | -         |    12.25 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           49 |     1802 | 2024-05-22 | VENI VIDI VICI    | W   | 0.709      | -            | -                | -                | -         |     1.24 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           48 |     1891 | 2024-05-20 | Illuminar         | W   | 0.694      | -            | -                | -                | -         |    10.99 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           47 |     1899 | 2024-05-20 | Verdant           | L   | 0.693      | -            | -                | -                | -         |   -10.54 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           46 |     1954 | 2024-05-18 | DMS               | L   | 0.680      | -            | -                | -                | -         |   -10.81 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           45 |     2017 | 2024-05-16 | MOUZ NXT          | L   | 0.667      | -            | -                | -                | -         |    -7.00 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           44 |     2025 | 2024-05-16 | B8                | L   | 0.666      | -            | -                | -                | -         |    -5.72 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           43 |     2153 | 2024-05-13 | Nexus             | W   | 0.646      | -            | -                | -                | -         |     7.01 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           42 |     2241 | 2024-05-09 | BLEED             | L   | 0.622      | -            | -                | -                | -         |    -6.22 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           41 |     2318 | 2024-05-05 | RUSH B            | W   | 0.594      | -            | -                | -                | -         |     8.05 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           40 |     2347 | 2024-05-04 | Endpoint          | L   | 0.586      | -            | -                | -                | -         |    -8.96 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           39 |     2379 | 2024-05-02 | Permitta          | W   | 0.574      | 0.435        | -                | 0.876 (0.219)    | -         |     9.36 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           38 |     2406 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.567      | -            | -                | -                | -         |    -7.63 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           37 |     2413 | 2024-05-01 | ENCE Academy      | W   | 0.566      | -            | -                | -                | -         |     4.14 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           36 |     2418 | 2024-04-30 | GL Academy        | W   | 0.562      | -            | -                | -                | -         |     5.02 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           35 |     2436 | 2024-04-30 | ALTERNATE aTTaX   | L   | 0.559      | -            | -                | -                | -         |    -7.75 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           34 |     2554 | 2024-04-25 | ECLOT             | L   | 0.525      | -            | -                | -                | -         |    -2.98 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           33 |     2573 | 2024-04-24 | Permitta          | W   | 0.519      | 0.371        | -                | 0.876 (0.168)    | -         |     9.29 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           32 |     2592 | 2024-04-23 | ECLOT             | L   | 0.512      | -            | -                | -                | -         |    -2.86 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           31 |     2628 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.499      | -            | -                | -                | -         |     8.67 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           30 |     2702 | 2024-04-19 | BLEED             | L   | 0.486      | -            | -                | -                | -         |    -5.62 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           29 |     2761 | 2024-04-18 | Permitta          | W   | 0.479      | -            | -                | -                | -         |     8.71 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           28 |     2783 | 2024-04-17 | NOM               | L   | 0.473      | -            | -                | -                | -         |   -13.28 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           27 |     2821 | 2024-04-16 | SAW               | W   | 0.466      | 0.384        | 0.105 (0.019)    | -                | -         |    11.96 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           26 |     2825 | 2024-04-16 | Secret            | W   | 0.465      | -            | -                | -                | -         |     1.75 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           25 |     2835 | 2024-04-15 | ENCE Academy      | L   | 0.460      | -            | -                | -                | -         |   -10.78 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           24 |     2870 | 2024-04-13 | BetBoom           | L   | 0.446      | -            | -                | -                | -         |    -0.84 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           23 |     2914 | 2024-04-11 | PGE Turow         | W   | 0.432      | -            | -                | -                | -         |     2.56 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           22 |     3087 | 2024-04-06 | Enterprise        | W   | 0.399      | -            | -                | -                | -         |     6.35 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           21 |     3193 | 2024-04-03 | Ninjas in Pyjamas | W   | 0.379      | 0.384        | 0.255 (0.037)    | -                | -         |    11.80 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           20 |     3315 | 2024-03-27 | B8                | L   | 0.335      | -            | -                | -                | -         |    -2.72 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           19 |     3456 | 2024-03-18 | ex-Preasy         | L   | 0.272      | -            | -                | -                | -         |    -5.45 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           18 |     3487 | 2024-03-17 | Passion UA        | W   | 0.266      | 0.371        | 0.172 (0.017)    | -                | -         |     6.00 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           17 |     3495 | 2024-03-16 | SINNERS           | L   | 0.260      | -            | -                | -                | -         |    -2.30 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           16 |     3498 | 2024-03-16 | MOUZ NXT          | W   | 0.259      | 0.371        | 0.139 (0.013)    | -                | -         |     5.59 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           15 |     3513 | 2024-03-15 | ECLOT             | L   | 0.254      | -            | -                | -                | -         |    -1.31 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           14 |     3519 | 2024-03-15 | Permitta          | W   | 0.252      | -            | -                | -                | -         |     4.75 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           13 |     3549 | 2024-03-14 | Passion UA        | L   | 0.247      | -            | -                | -                | -         |    -2.10 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           12 |     3619 | 2024-03-12 | MOUZ NXT          | W   | 0.232      | -            | -                | -                | -         |     5.13 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           11 |     3661 | 2024-03-10 | Sashi             | W   | 0.220      | 0.358        | 0.184 (0.014)    | -                | -         |     5.56 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           10 |     3687 | 2024-03-09 | Enterprise        | W   | 0.213      | -            | -                | -                | -         |     3.62 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            9 |     3772 | 2024-03-06 | AURA              | W   | 0.192      | -            | -                | -                | -         |     0.63 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            8 |     3818 | 2024-03-04 | Sangal            | L   | 0.180      | -            | -                | -                | -         |    -1.05 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            7 |     3872 | 2024-03-02 | Enterprise        | L   | 0.166      | -            | -                | -                | -         |    -2.38 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            6 |     3910 | 2024-02-28 | Sashi             | L   | 0.147      | -            | -                | -                | -         |    -0.86 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            5 |     3975 | 2024-02-25 | ECLOT             | L   | 0.126      | -            | -                | -                | -         |    -0.54 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            4 |     4021 | 2024-02-23 | Entropiq          | W   | 0.112      | -            | -                | -                | -         |     0.46 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            3 |     4063 | 2024-02-21 | Sashi             | L   | 0.100      | -            | -                | -                | -         |    -0.56 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            2 |     4167 | 2024-02-17 | Secret            | W   | 0.073      | -            | -                | -                | -         |     0.29 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            1 |     4314 | 2024-02-10 | Zero Tenacity     | W   | 0.028      | -            | -                | -                | -         |     0.68 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,870.82)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.855 | $3,268.00      | $2,794.22       |
| 2024-06-02 |      0.781 | $653.00        | $509.93         |
| 2024-05-18 |      0.681 | $1,000.00      | $681.23         |
| 2024-04-25 |      0.525 | $5,000.00      | $2,626.97       |
| 2024-04-14 |      0.453 | $1,600.00      | $725.52         |
| 2024-03-18 |      0.272 | $5,000.00      | $1,361.69       |
| 2024-03-17 |      0.268 | $639.00        | $171.27         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
