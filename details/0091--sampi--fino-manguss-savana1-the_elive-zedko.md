### Roster Details<br />
Team Name: Sampi<br />
Roster: fino, manguss, sAvana1, The eLiVe, ZEDKO<br />
Global Rank: [91](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [66]( ../standings_europe.md)<br />
<br />
Final Rank Value:  893.6<br />
<br />
Final Rank Value (893.6) = Starting Rank Value (891.2) + Head To Head Adjustments (2.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.392[<sup>1</sup>](#table2)
- Bounty Collected: 0.379[<sup>2</sup>](#table1)
- Opponent Network: 0.182[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.238<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 891.2
- 400 + ( ( 0.238 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 891.2


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
|           93 |        8 | 2024-07-31 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -15.17 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           92 |       26 | 2024-07-31 | Illuminar         | L   | 1.000      | -            | -                | -                | -         |   -15.11 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           91 |       64 | 2024-07-30 | CYBERSHOKE        | W   | 1.000      | 0.426        | 0.039 (0.017)    | -                | 0 (0.000) |    17.13 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           90 |       75 | 2024-07-30 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.74 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           89 |      101 | 2024-07-29 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -14.56 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           88 |      123 | 2024-07-28 | CPH Wolves        | W   | 1.000      | 0.435        | -                | 0.359 (0.156)    | 0 (0.000) |    12.99 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           87 |      171 | 2024-07-26 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.523 (0.227)    | 0 (0.000) |    12.88 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           86 |      183 | 2024-07-26 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -1.28 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           85 |      253 | 2024-07-24 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -12.30 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           84 |      284 | 2024-07-23 | CPH Wolves        | W   | 1.000      | 0.435        | -                | 0.359 (0.156)    | 0 (0.000) |    13.81 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           83 |      324 | 2024-07-22 | INFINITE          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.40 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           82 |      335 | 2024-07-21 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.35 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           81 |      411 | 2024-07-19 | Metizport         | L   | 1.000      | -            | -                | -                | -         |   -12.58 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           80 |      459 | 2024-07-18 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -16.34 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           79 |      585 | 2024-07-16 | RUBY              | W   | 1.000      | 0.435        | 0.096 (0.042)    | 0.506 (0.220)    | 0 (0.000) |    15.42 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           78 |      600 | 2024-07-16 | Meteor            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.82 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           77 |      650 | 2024-07-14 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -15.92 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           76 |      654 | 2024-07-14 | Portugal          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.95 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           75 |      715 | 2024-07-10 | Hungary           | W   | 1.000      | -            | -                | -                | -         |    11.70 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           74 |      754 | 2024-07-08 | Austria           | W   | 1.000      | -            | -                | -                | -         |     1.94 | fino, M1key, MATYS, sAvana1, The eLiVe      |
|           73 |      956 | 2024-06-13 | Rebels            | W   | 0.879      | 0.379        | 0.040 (0.013)    | 0.596 (0.198)    | -         |    18.99 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           72 |      963 | 2024-06-13 | Sashi             | L   | 0.878      | -            | -                | -                | -         |    -3.45 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           71 |      987 | 2024-06-12 | Enterprise        | L   | 0.872      | -            | -                | -                | -         |   -11.24 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           70 |     1006 | 2024-06-11 | Astralis Talent   | W   | 0.865      | -            | -                | -                | -         |     9.10 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           69 |     1016 | 2024-06-11 | Illuminar         | L   | 0.863      | -            | -                | -                | -         |   -12.61 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           68 |     1076 | 2024-06-09 | Aurora Young Blud | L   | 0.852      | -            | -                | -                | -         |   -15.48 | fino, manguss, sAvana1, The eLiVe, Verttzzz |
|           67 |     1145 | 2024-06-08 | MOUZ NXT          | L   | 0.845      | -            | -                | -                | -         |    -6.68 | fino, manguss, sAvana1, The eLiVe, Verttzzz |
|           66 |     1164 | 2024-06-08 | CYBERSHOKE        | L   | 0.844      | -            | -                | -                | -         |   -15.06 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           65 |     1266 | 2024-06-06 | Nemiga            | L   | 0.832      | -            | -                | -                | -         |    -6.42 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           64 |     1282 | 2024-06-06 | HAVU              | W   | 0.831      | -            | -                | -                | -         |     6.85 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           63 |     1325 | 2024-06-05 | NAVI Junior       | W   | 0.825      | -            | -                | -                | -         |     3.16 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           62 |     1362 | 2024-06-04 | INFINITE          | W   | 0.819      | -            | -                | -                | -         |     3.18 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           61 |     1382 | 2024-06-04 | DMS               | W   | 0.817      | 0.500        | -                | 0.447 (0.183)    | -         |    15.50 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           60 |     1406 | 2024-06-03 | Rare Atom         | W   | 0.810      | -            | -                | -                | -         |     5.00 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           59 |     1457 | 2024-06-01 | SINNERS           | L   | 0.798      | -            | -                | -                | -         |    -7.95 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           58 |     1478 | 2024-05-31 | ECLOT             | L   | 0.793      | -            | -                | -                | -         |    -7.26 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           57 |     1502 | 2024-05-30 | 3DMAX             | L   | 0.786      | -            | -                | -                | -         |    -0.66 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           56 |     1555 | 2024-05-28 | Enterprise        | L   | 0.772      | -            | -                | -                | -         |   -12.17 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           55 |     1558 | 2024-05-28 | Rhyno             | W   | 0.771      | 0.435        | 0.072 (0.024)    | -                | -         |    15.06 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           54 |     1593 | 2024-05-26 | SINNERS           | L   | 0.759      | -            | -                | -                | -         |    -8.46 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           53 |     1611 | 2024-05-25 | Passion UA        | L   | 0.752      | -            | -                | -                | -         |    -7.97 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           52 |     1642 | 2024-05-23 | GUN5              | W   | 0.739      | 0.435        | 0.073 (0.024)    | 0.516 (0.166)    | -         |    12.53 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           51 |     1677 | 2024-05-22 | VENI VIDI VICI    | W   | 0.733      | -            | -                | -                | -         |     1.27 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           50 |     1766 | 2024-05-20 | Illuminar         | W   | 0.719      | -            | -                | -                | -         |    11.46 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           49 |     1774 | 2024-05-20 | Verdant           | L   | 0.717      | -            | -                | -                | -         |   -10.83 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           48 |     1829 | 2024-05-18 | DMS               | L   | 0.704      | -            | -                | -                | -         |   -11.09 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           47 |     1892 | 2024-05-16 | MOUZ NXT          | L   | 0.692      | -            | -                | -                | -         |    -7.27 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           46 |     1900 | 2024-05-16 | B8                | L   | 0.690      | -            | -                | -                | -         |    -5.82 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           45 |     2028 | 2024-05-13 | Nexus             | W   | 0.671      | -            | -                | -                | -         |     7.28 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           44 |     2116 | 2024-05-09 | BLEED             | L   | 0.646      | -            | -                | -                | -         |    -6.26 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           43 |     2193 | 2024-05-05 | RUSH B            | W   | 0.619      | -            | -                | -                | -         |     8.01 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           42 |     2222 | 2024-05-04 | Endpoint          | L   | 0.610      | -            | -                | -                | -         |    -9.25 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           41 |     2254 | 2024-05-02 | Permitta          | W   | 0.599      | 0.435        | -                | 0.799 (0.208)    | -         |     9.47 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           40 |     2281 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.591      | -            | -                | -                | -         |    -7.92 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           39 |     2288 | 2024-05-01 | ENCE Academy      | W   | 0.590      | -            | -                | -                | -         |     4.54 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           38 |     2293 | 2024-04-30 | GL Academy        | W   | 0.586      | -            | -                | -                | -         |     5.32 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           37 |     2311 | 2024-04-30 | ALTERNATE aTTaX   | L   | 0.584      | -            | -                | -                | -         |    -8.04 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           36 |     2429 | 2024-04-25 | ECLOT             | L   | 0.550      | -            | -                | -                | -         |    -4.64 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           35 |     2448 | 2024-04-24 | Permitta          | W   | 0.543      | 0.371        | -                | 0.799 (0.161)    | -         |     9.41 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           34 |     2467 | 2024-04-23 | ECLOT             | L   | 0.537      | -            | -                | -                | -         |    -4.53 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           33 |     2503 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.523      | -            | -                | -                | -         |     9.04 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           32 |     2577 | 2024-04-19 | BLEED             | L   | 0.511      | -            | -                | -                | -         |    -5.75 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           31 |     2636 | 2024-04-18 | Permitta          | W   | 0.503      | 0.371        | -                | 0.799 (0.149)    | -         |     8.79 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           30 |     2658 | 2024-04-17 | NOM               | L   | 0.498      | -            | -                | -                | -         |   -14.01 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           29 |     2696 | 2024-04-16 | SAW               | W   | 0.491      | 0.384        | 0.107 (0.020)    | -                | -         |    12.73 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           28 |     2700 | 2024-04-16 | Secret            | W   | 0.490      | -            | -                | -                | -         |     1.82 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           27 |     2710 | 2024-04-15 | ENCE Academy      | L   | 0.485      | -            | -                | -                | -         |   -11.13 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           26 |     2745 | 2024-04-13 | BetBoom           | L   | 0.470      | -            | -                | -                | -         |    -0.83 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           25 |     2789 | 2024-04-11 | PGE Turow         | W   | 0.457      | -            | -                | -                | -         |     2.70 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           24 |     2962 | 2024-04-06 | Enterprise        | W   | 0.424      | -            | -                | -                | -         |     6.74 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           23 |     3068 | 2024-04-03 | Ninjas in Pyjamas | W   | 0.404      | 0.384        | 0.256 (0.040)    | -                | -         |    12.53 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           22 |     3190 | 2024-03-27 | B8                | L   | 0.359      | -            | -                | -                | -         |    -2.85 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           21 |     3331 | 2024-03-18 | ex-Preasy         | L   | 0.297      | -            | -                | -                | -         |    -5.79 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           20 |     3362 | 2024-03-17 | Passion UA        | W   | 0.290      | 0.371        | 0.171 (0.018)    | -                | -         |     6.49 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           19 |     3370 | 2024-03-16 | SINNERS           | L   | 0.285      | -            | -                | -                | -         |    -3.05 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           18 |     3373 | 2024-03-16 | MOUZ NXT          | W   | 0.284      | 0.371        | 0.140 (0.015)    | -                | -         |     6.13 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           17 |     3388 | 2024-03-15 | ECLOT             | L   | 0.278      | -            | -                | -                | -         |    -2.32 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           16 |     3394 | 2024-03-15 | Permitta          | W   | 0.277      | -            | -                | -                | -         |     5.00 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           15 |     3424 | 2024-03-14 | Passion UA        | L   | 0.271      | -            | -                | -                | -         |    -2.37 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           14 |     3494 | 2024-03-12 | MOUZ NXT          | W   | 0.257      | -            | -                | -                | -         |     5.69 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           13 |     3536 | 2024-03-10 | Sashi             | W   | 0.244      | 0.358        | 0.185 (0.016)    | -                | -         |     6.19 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           12 |     3562 | 2024-03-09 | Enterprise        | W   | 0.238      | -            | -                | -                | -         |     4.05 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           11 |     3647 | 2024-03-06 | AURA              | W   | 0.217      | -            | -                | -                | -         |     0.72 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           10 |     3693 | 2024-03-04 | Sangal            | L   | 0.204      | -            | -                | -                | -         |    -1.26 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            9 |     3747 | 2024-03-02 | Enterprise        | L   | 0.190      | -            | -                | -                | -         |    -2.71 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            8 |     3785 | 2024-02-28 | Sashi             | L   | 0.172      | -            | -                | -                | -         |    -0.99 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            7 |     3850 | 2024-02-25 | ECLOT             | L   | 0.150      | -            | -                | -                | -         |    -1.09 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            6 |     3896 | 2024-02-23 | Entropiq          | W   | 0.137      | -            | -                | -                | -         |     0.56 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            5 |     3938 | 2024-02-21 | Sashi             | L   | 0.124      | -            | -                | -                | -         |    -0.68 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            4 |     4042 | 2024-02-17 | Secret            | W   | 0.098      | -            | -                | -                | -         |     0.38 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            3 |     4189 | 2024-02-10 | Zero Tenacity     | W   | 0.052      | -            | -                | -                | -         |     1.27 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO     |
|            2 |     4248 | 2024-02-05 | Imperial fe       | W   | 0.018      | -            | -                | -                | -         |     0.40 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO     |
|            1 |     4303 | 2024-02-03 | Sashi             | W   | 0.004      | -            | -                | -                | -         |     0.11 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,291.24)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.880 | $3,268.00      | $2,874.28       |
| 2024-06-02 |      0.805 | $653.00        | $525.93         |
| 2024-05-18 |      0.706 | $1,000.00      | $705.73         |
| 2024-04-25 |      0.550 | $5,000.00      | $2,749.47       |
| 2024-04-14 |      0.478 | $1,600.00      | $764.72         |
| 2024-03-18 |      0.297 | $5,000.00      | $1,484.19       |
| 2024-03-17 |      0.293 | $639.00        | $186.93         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
