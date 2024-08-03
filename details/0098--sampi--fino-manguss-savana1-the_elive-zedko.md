### Roster Details<br />
Team Name: Sampi<br />
Roster: fino, manguss, sAvana1, The eLiVe, ZEDKO<br />
Global Rank: [98](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [72]( ../standings_europe.md)<br />
<br />
Final Rank Value:  855.2<br />
<br />
Final Rank Value (855.2) = Starting Rank Value (889.1) + Head To Head Adjustments (-33.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.391[<sup>1</sup>](#table2)
- Bounty Collected: 0.374[<sup>2</sup>](#table1)
- Opponent Network: 0.192[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.239<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 889.1
- 400 + ( ( 0.239 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 889.1


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
|           91 |       63 | 2024-08-01 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -19.87 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           90 |       70 | 2024-08-01 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -16.19 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           89 |      100 | 2024-07-31 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -14.80 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           88 |      117 | 2024-07-31 | Illuminar         | L   | 1.000      | -            | -                | -                | -         |   -15.13 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           87 |      155 | 2024-07-30 | CYBERSHOKE        | W   | 1.000      | 0.426        | 0.039 (0.017)    | -                | 0 (0.000) |    16.94 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           86 |      166 | 2024-07-30 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.76 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           85 |      194 | 2024-07-29 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -14.77 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           84 |      214 | 2024-07-28 | CPH Wolves        | W   | 1.000      | 0.435        | -                | 0.376 (0.163)    | 0 (0.000) |    13.03 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           83 |      262 | 2024-07-26 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.540 (0.235)    | 0 (0.000) |    12.90 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           82 |      274 | 2024-07-26 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -2.37 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           81 |      344 | 2024-07-24 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -12.42 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           80 |      375 | 2024-07-23 | CPH Wolves        | W   | 1.000      | 0.435        | -                | 0.376 (0.163)    | 0 (0.000) |    13.77 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           79 |      414 | 2024-07-22 | INFINITE          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.38 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           78 |      426 | 2024-07-21 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.36 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           77 |      502 | 2024-07-19 | Metizport         | L   | 1.000      | -            | -                | -                | -         |   -12.81 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           76 |      550 | 2024-07-18 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -15.98 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           75 |      673 | 2024-07-16 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | 0.520 (0.226)    | 0 (0.000) |    15.69 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           74 |      685 | 2024-07-16 | Meteor            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.72 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           73 |      737 | 2024-07-14 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -15.87 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           72 |      741 | 2024-07-14 | Portugal          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.81 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           71 |      798 | 2024-07-10 | Hungary           | W   | 1.000      | -            | -                | -                | -         |    11.50 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           70 |      837 | 2024-07-08 | Austria           | W   | 1.000      | -            | -                | -                | -         |     1.95 | fino, M1key, MATYS, sAvana1, The eLiVe      |
|           69 |     1019 | 2024-06-13 | Rebels            | W   | 0.860      | 0.379        | 0.038 (0.012)    | 0.605 (0.197)    | -         |    18.30 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           68 |     1026 | 2024-06-13 | Sashi             | L   | 0.859      | -            | -                | -                | -         |    -3.51 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           67 |     1049 | 2024-06-12 | Enterprise        | L   | 0.853      | -            | -                | -                | -         |   -11.03 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           66 |     1075 | 2024-06-11 | Illuminar         | L   | 0.844      | -            | -                | -                | -         |   -12.76 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           65 |     1134 | 2024-06-09 | Aurora Young Blud | L   | 0.833      | -            | -                | -                | -         |   -15.51 | fino, manguss, sAvana1, The eLiVe, Verttzzz |
|           64 |     1217 | 2024-06-08 | CYBERSHOKE        | L   | 0.824      | -            | -                | -                | -         |   -14.71 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           63 |     1319 | 2024-06-06 | Nemiga            | L   | 0.813      | -            | -                | -                | -         |    -6.57 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           62 |     1335 | 2024-06-06 | HAVU              | W   | 0.812      | -            | -                | -                | -         |     6.50 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           61 |     1378 | 2024-06-05 | NAVI Junior       | W   | 0.806      | -            | -                | -                | -         |     3.03 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           60 |     1415 | 2024-06-04 | INFINITE          | W   | 0.800      | -            | -                | -                | -         |     3.05 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           59 |     1434 | 2024-06-04 | DMS               | W   | 0.798      | 0.500        | -                | 0.462 (0.184)    | -         |    14.75 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           58 |     1458 | 2024-06-03 | Rare Atom         | W   | 0.791      | 0.435        | -                | 0.495 (0.170)    | -         |     5.95 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           57 |     1507 | 2024-06-01 | SINNERS           | L   | 0.779      | -            | -                | -                | -         |    -7.24 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           56 |     1528 | 2024-05-31 | ECLOT             | L   | 0.774      | -            | -                | -                | -         |    -5.15 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           55 |     1552 | 2024-05-30 | 3DMAX             | L   | 0.767      | -            | -                | -                | -         |    -0.68 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           54 |     1605 | 2024-05-28 | Enterprise        | L   | 0.753      | -            | -                | -                | -         |   -11.95 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           53 |     1608 | 2024-05-28 | Rhyno             | W   | 0.752      | 0.435        | 0.071 (0.023)    | -                | -         |    14.39 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           52 |     1642 | 2024-05-26 | SINNERS           | L   | 0.739      | -            | -                | -                | -         |    -7.55 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           51 |     1660 | 2024-05-25 | Passion UA        | L   | 0.733      | -            | -                | -                | -         |    -7.83 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           50 |     1691 | 2024-05-23 | GUN5              | W   | 0.720      | 0.435        | 0.073 (0.023)    | 0.588 (0.184)    | -         |    12.40 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           49 |     1726 | 2024-05-22 | VENI VIDI VICI    | W   | 0.714      | -            | -                | -                | -         |     1.24 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           48 |     1815 | 2024-05-20 | Illuminar         | W   | 0.699      | -            | -                | -                | -         |    11.10 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           47 |     1823 | 2024-05-20 | Verdant           | L   | 0.698      | -            | -                | -                | -         |   -10.66 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           46 |     1877 | 2024-05-18 | DMS               | L   | 0.685      | -            | -                | -                | -         |   -10.96 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           45 |     1940 | 2024-05-16 | MOUZ NXT          | L   | 0.673      | -            | -                | -                | -         |    -7.19 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           44 |     1948 | 2024-05-16 | B8                | L   | 0.671      | -            | -                | -                | -         |    -5.87 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           43 |     2076 | 2024-05-13 | Nexus             | W   | 0.652      | -            | -                | -                | -         |     7.05 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           42 |     2164 | 2024-05-09 | BLEED             | L   | 0.627      | -            | -                | -                | -         |    -6.32 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           41 |     2240 | 2024-05-05 | RUSH B            | W   | 0.600      | -            | -                | -                | -         |     7.78 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           40 |     2269 | 2024-05-04 | Endpoint          | L   | 0.591      | -            | -                | -                | -         |    -9.04 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           39 |     2301 | 2024-05-02 | Permitta          | W   | 0.579      | 0.435        | -                | 0.887 (0.223)    | -         |     9.39 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           38 |     2328 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.572      | -            | -                | -                | -         |    -7.75 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           37 |     2335 | 2024-05-01 | ENCE Academy      | W   | 0.571      | -            | -                | -                | -         |     4.29 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           36 |     2340 | 2024-04-30 | GL Academy        | W   | 0.567      | -            | -                | -                | -         |     5.03 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           35 |     2358 | 2024-04-30 | ALTERNATE aTTaX   | L   | 0.565      | -            | -                | -                | -         |    -7.87 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           34 |     2475 | 2024-04-25 | ECLOT             | L   | 0.531      | -            | -                | -                | -         |    -3.02 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           33 |     2494 | 2024-04-24 | Permitta          | W   | 0.524      | 0.371        | -                | 0.887 (0.172)    | -         |     9.35 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           32 |     2513 | 2024-04-23 | ECLOT             | L   | 0.518      | -            | -                | -                | -         |    -2.90 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           31 |     2549 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.504      | -            | -                | -                | -         |     8.72 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           30 |     2623 | 2024-04-19 | BLEED             | L   | 0.492      | -            | -                | -                | -         |    -5.73 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           29 |     2682 | 2024-04-18 | Permitta          | W   | 0.484      | -            | -                | -                | -         |     8.77 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           28 |     2704 | 2024-04-17 | NOM               | L   | 0.479      | -            | -                | -                | -         |   -13.45 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           27 |     2742 | 2024-04-16 | SAW               | W   | 0.472      | 0.384        | 0.106 (0.019)    | -                | -         |    12.09 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           26 |     2746 | 2024-04-16 | Secret            | W   | 0.471      | -            | -                | -                | -         |     1.75 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           25 |     2756 | 2024-04-15 | ENCE Academy      | L   | 0.466      | -            | -                | -                | -         |   -10.78 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           24 |     2791 | 2024-04-13 | BetBoom           | L   | 0.451      | -            | -                | -                | -         |    -0.86 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           23 |     2835 | 2024-04-11 | PGE Turow         | W   | 0.438      | -            | -                | -                | -         |     2.58 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           22 |     3008 | 2024-04-06 | Enterprise        | W   | 0.405      | -            | -                | -                | -         |     6.43 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           21 |     3114 | 2024-04-03 | Ninjas in Pyjamas | W   | 0.385      | 0.384        | 0.204 (0.030)    | -                | -         |    11.89 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           20 |     3234 | 2024-03-27 | B8                | L   | 0.340      | -            | -                | -                | -         |    -2.77 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           19 |     3372 | 2024-03-18 | ex-Preasy         | L   | 0.278      | -            | -                | -                | -         |    -5.58 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           18 |     3403 | 2024-03-17 | Passion UA        | W   | 0.271      | 0.371        | 0.172 (0.017)    | -                | -         |     6.09 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           17 |     3411 | 2024-03-16 | SINNERS           | L   | 0.266      | -            | -                | -                | -         |    -2.34 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           16 |     3414 | 2024-03-16 | MOUZ NXT          | W   | 0.264      | 0.371        | 0.139 (0.014)    | -                | -         |     5.61 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           15 |     3428 | 2024-03-15 | ECLOT             | L   | 0.259      | -            | -                | -                | -         |    -1.34 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           14 |     3434 | 2024-03-15 | Permitta          | W   | 0.258      | -            | -                | -                | -         |     4.84 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           13 |     3464 | 2024-03-14 | Passion UA        | L   | 0.252      | -            | -                | -                | -         |    -2.18 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           12 |     3532 | 2024-03-12 | MOUZ NXT          | W   | 0.238      | -            | -                | -                | -         |     5.17 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           11 |     3574 | 2024-03-10 | Sashi             | W   | 0.225      | 0.358        | 0.184 (0.015)    | -                | -         |     5.68 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           10 |     3600 | 2024-03-09 | Enterprise        | W   | 0.219      | -            | -                | -                | -         |     3.71 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            9 |     3685 | 2024-03-06 | AURA              | W   | 0.198      | -            | -                | -                | -         |     0.64 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            8 |     3731 | 2024-03-04 | Sangal            | L   | 0.185      | -            | -                | -                | -         |    -1.10 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            7 |     3785 | 2024-03-02 | Enterprise        | L   | 0.171      | -            | -                | -                | -         |    -2.45 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            6 |     3823 | 2024-02-28 | Sashi             | L   | 0.153      | -            | -                | -                | -         |    -0.91 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            5 |     3888 | 2024-02-25 | ECLOT             | L   | 0.131      | -            | -                | -                | -         |    -0.57 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            4 |     3934 | 2024-02-23 | Entropiq          | W   | 0.118      | -            | -                | -                | -         |     0.48 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            3 |     3976 | 2024-02-21 | Sashi             | L   | 0.105      | -            | -                | -                | -         |    -0.59 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            2 |     4079 | 2024-02-17 | Secret            | W   | 0.079      | -            | -                | -                | -         |     0.31 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            1 |     4226 | 2024-02-10 | Zero Tenacity     | W   | 0.033      | -            | -                | -                | -         |     0.81 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,964.96)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.861 | $3,268.00      | $2,812.14       |
| 2024-06-02 |      0.786 | $653.00        | $513.51         |
| 2024-05-18 |      0.687 | $1,000.00      | $686.71         |
| 2024-04-25 |      0.531 | $5,000.00      | $2,654.40       |
| 2024-04-14 |      0.459 | $1,600.00      | $734.30         |
| 2024-03-18 |      0.278 | $5,000.00      | $1,389.12       |
| 2024-03-17 |      0.274 | $639.00        | $174.78         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
