### Roster Details<br />
Team Name: Passion UA<br />
Roster: fear, jackasmo, jambo, s-chilla, zeRRoFIX<br />
Global Rank: [47](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [34]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1098.5<br />
<br />
Final Rank Value (1098.5) = Starting Rank Value (1097.0) + Head To Head Adjustments (1.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.568[<sup>1</sup>](#table2)
- Bounty Collected: 0.462[<sup>2</sup>](#table1)
- Opponent Network: 0.326[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.339<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1097.0
- 400 + ( ( 0.339 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1097.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           92 |       91 | 2024-08-03 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -8.65 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           91 |      169 | 2024-08-01 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           90 |      250 | 2024-07-30 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.17 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           89 |      285 | 2024-07-29 | Nexus             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.66 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           88 |      297 | 2024-07-29 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -27.93 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           87 |      339 | 2024-07-27 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -12.97 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           86 |      361 | 2024-07-26 | Gaimin Gladiators | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.64 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           85 |      380 | 2024-07-26 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.18 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           84 |      401 | 2024-07-25 | EYEBALLERS        | L   | 1.000      | -            | -                | -                | -         |   -26.81 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           83 |      419 | 2024-07-25 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.26 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           82 |      484 | 2024-07-23 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.80 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           81 |      506 | 2024-07-22 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.52 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           80 |      512 | 2024-07-22 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.94 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           79 |      532 | 2024-07-21 | Zero Tenacity     | W   | 1.000      | 0.500        | 0.143 (0.071)    | 1.000 (0.500)    | 0 (0.000) |    16.98 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           78 |      567 | 2024-07-20 | Ninjas in Pyjamas | W   | 1.000      | 0.500        | 0.253 (0.127)    | 0.531 (0.266)    | 0 (0.000) |    29.65 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           77 |      580 | 2024-07-20 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | -                | -         |     8.92 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           76 |      609 | 2024-07-19 | Nemiga            | W   | 1.000      | 0.500        | 0.314 (0.157)    | 0.704 (0.352)    | -         |    20.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           75 |      666 | 2024-07-18 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.122 (0.045)    | 1.000 (0.371)    | -         |    23.47 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           74 |      677 | 2024-07-18 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -23.71 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           73 |      733 | 2024-07-17 | Aurora Young Blud | W   | 1.000      | 0.500        | -                | 0.521 (0.261)    | -         |    11.42 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           72 |      794 | 2024-07-16 | Permitta          | W   | 1.000      | 0.371        | -                | 0.919 (0.340)    | -         |    12.10 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           71 |      816 | 2024-07-15 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -9.56 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           70 |      836 | 2024-07-15 | WOPA              | W   | 1.000      | -            | -                | -                | -         |     1.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           69 |      854 | 2024-07-14 | Preasy            | W   | 1.000      | -            | -                | -                | -         |     2.11 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           68 |      918 | 2024-07-10 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -18.45 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           67 |      936 | 2024-07-09 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           66 |      938 | 2024-07-09 | Insilio           | W   | 1.000      | -            | -                | -                | -         |    11.45 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           65 |      958 | 2024-07-08 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.73 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           64 |     1132 | 2024-06-14 | 3DMAX             | L   | 0.845      | -            | -                | -                | -         |    -3.08 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           63 |     1224 | 2024-06-10 | Space             | W   | 0.820      | -            | -                | -                | -         |     6.66 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           62 |     1336 | 2024-06-08 | Zero Tenacity     | L   | 0.807      | -            | -                | -                | -         |   -11.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           61 |     1398 | 2024-06-07 | Rare Atom         | W   | 0.800      | -            | -                | -                | -         |     5.31 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           60 |     1411 | 2024-06-07 | Aurora Young Blud | W   | 0.799      | -            | -                | -                | -         |     7.29 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           59 |     1482 | 2024-06-06 | Serbia            | W   | 0.792      | -            | -                | -                | -         |     5.08 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           58 |     1534 | 2024-06-05 | EYEBALLERS        | L   | 0.785      | -            | -                | -                | -         |   -18.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           57 |     1564 | 2024-06-04 | Illuminar         | W   | 0.780      | -            | -                | -                | -         |     4.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           56 |     1573 | 2024-06-04 | Serbia            | W   | 0.779      | -            | -                | -                | -         |     4.55 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           55 |     1622 | 2024-06-02 | UNiTY             | W   | 0.765      | -            | -                | -                | -         |     8.70 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           54 |     1683 | 2024-05-31 | Zero Tenacity     | L   | 0.753      | -            | -                | -                | -         |   -10.55 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           53 |     1704 | 2024-05-30 | Zero Tenacity     | W   | 0.747      | 0.371        | 0.143 (0.040)    | 1.000 (0.277)    | -         |    13.33 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           52 |     1733 | 2024-05-29 | Illuminar         | W   | 0.739      | -            | -                | -                | -         |     5.68 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           51 |     1804 | 2024-05-25 | Sampi             | W   | 0.714      | 0.435        | -                | 1.000 (0.310)    | -         |     7.19 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           50 |     1825 | 2024-05-24 | FURIA             | L   | 0.707      | -            | -                | -                | -         |    -0.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           49 |     1831 | 2024-05-24 | ECSTATIC          | W   | 0.705      | -            | -                | -                | -         |     1.27 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           48 |     1845 | 2024-05-23 | SINNERS           | W   | 0.699      | -            | -                | -                | -         |    12.17 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           47 |     1969 | 2024-05-20 | Permitta          | W   | 0.679      | 0.435        | -                | 0.919 (0.271)    | -         |     7.05 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           46 |     1981 | 2024-05-19 | Sashi             | L   | 0.674      | -            | -                | -                | -         |    -5.92 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           45 |     1992 | 2024-05-19 | ALTERNATE aTTaX   | W   | 0.672      | -            | -                | -                | -         |     7.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           44 |     2012 | 2024-05-18 | 9 Pandas          | L   | 0.667      | -            | -                | -                | -         |   -10.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           43 |     2055 | 2024-05-17 | Nexus             | W   | 0.659      | -            | -                | -                | -         |     4.34 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           42 |     2096 | 2024-05-16 | Sashi             | W   | 0.652      | 0.500        | 0.184 (0.060)    | 0.958 (0.312)    | -         |    15.23 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           41 |     2135 | 2024-05-15 | Endpoint          | L   | 0.647      | -            | -                | -                | -         |   -12.74 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           40 |     2189 | 2024-05-14 | SINNERS           | L   | 0.641      | -            | -                | -                | -         |    -8.97 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           39 |     2282 | 2024-05-11 | Preasy            | W   | 0.618      | -            | -                | -                | -         |     3.48 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           38 |     2446 | 2024-05-02 | Nemiga            | L   | 0.560      | -            | -                | -                | -         |    -5.73 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           37 |     2469 | 2024-05-01 | PARIVISION        | W   | 0.554      | -            | -                | -                | -         |    10.13 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           36 |     2506 | 2024-04-30 | 9 Pandas          | W   | 0.545      | -            | -                | -                | -         |     7.18 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           35 |     2533 | 2024-04-28 | ALTERNATE aTTaX   | L   | 0.534      | -            | -                | -                | -         |   -10.09 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           34 |     2583 | 2024-04-26 | 9 Pandas          | W   | 0.520      | -            | -                | -                | -         |     7.04 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           33 |     2584 | 2024-04-26 | 9 Pandas          | W   | 0.520      | -            | -                | -                | -         |     6.73 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           32 |     2620 | 2024-04-25 | Sashi             | L   | 0.512      | -            | -                | -                | -         |    -4.99 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           31 |     2635 | 2024-04-24 | Permitta          | L   | 0.507      | -            | -                | -                | -         |    -8.96 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           30 |     2664 | 2024-04-22 | B8                | L   | 0.494      | -            | -                | -                | -         |    -7.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           29 |     2705 | 2024-04-20 | Young Ninjas      | W   | 0.481      | -            | -                | -                | -         |     2.75 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           28 |     2727 | 2024-04-20 | Permitta          | L   | 0.478      | -            | -                | -                | -         |    -8.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           27 |     2761 | 2024-04-19 | ALTERNATE aTTaX   | L   | 0.473      | -            | -                | -                | -         |    -9.53 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           26 |     2818 | 2024-04-18 | Permitta          | W   | 0.466      | -            | -                | -                | -         |     5.96 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           25 |     2848 | 2024-04-17 | Sashi             | W   | 0.460      | 0.371        | 0.184 (0.031)    | -                | -         |     8.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           24 |     2882 | 2024-04-16 | 500               | L   | 0.454      | -            | -                | -                | -         |   -12.20 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           23 |     2921 | 2024-04-14 | SINNERS           | L   | 0.439      | -            | -                | -                | -         |    -4.75 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           22 |     2976 | 2024-04-11 | 3DMAX             | W   | 0.420      | 0.384        | 0.510 (0.082)    | -                | -         |    12.77 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           21 |     3024 | 2024-04-10 | Sashi             | W   | 0.412      | 0.371        | 0.184 (0.028)    | -                | -         |     8.16 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           20 |     3211 | 2024-04-04 | HAVU              | W   | 0.373      | -            | -                | -                | -         |     1.54 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           19 |     3282 | 2024-04-02 | BLEED             | L   | 0.360      | -            | -                | -                | -         |    -6.83 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           18 |     3311 | 2024-03-31 | FAVBET            | L   | 0.346      | -            | -                | -                | -         |    -9.02 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           17 |     3318 | 2024-03-30 | Lazer Cats        | W   | 0.339      | -            | -                | -                | -         |     0.56 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           16 |     3326 | 2024-03-29 | NAVI Junior       | L   | 0.333      | -            | -                | -                | -         |    -9.16 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           15 |     3345 | 2024-03-28 | GL Academy        | L   | 0.326      | -            | -                | -                | -         |    -8.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           14 |     3555 | 2024-03-17 | Sampi             | L   | 0.252      | -            | -                | -                | -         |    -5.76 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           13 |     3564 | 2024-03-16 | ex-Preasy         | L   | 0.246      | -            | -                | -                | -         |    -6.46 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           12 |     3617 | 2024-03-14 | Sampi             | W   | 0.233      | -            | -                | -                | -         |     1.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           11 |     3685 | 2024-03-12 | Alliance          | W   | 0.219      | -            | -                | -                | -         |     1.58 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           10 |     3707 | 2024-03-11 | MOUZ NXT          | L   | 0.213      | -            | -                | -                | -         |    -3.71 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            9 |     3727 | 2024-03-10 | MOUZ NXT          | W   | 0.206      | -            | -                | -                | -         |     2.94 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            8 |     3742 | 2024-03-09 | The Chosen Few    | L   | 0.200      | -            | -                | -                | -         |    -5.75 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            7 |     3767 | 2024-03-08 | Spirit Academy    | L   | 0.194      | -            | -                | -                | -         |    -5.83 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            6 |     3772 | 2024-03-08 | Entropiq          | W   | 0.193      | -            | -                | -                | -         |     0.28 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            5 |     3791 | 2024-03-07 | AURA              | W   | 0.188      | -            | -                | -                | -         |     0.19 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            4 |     3827 | 2024-03-06 | Permitta          | L   | 0.180      | -            | -                | -                | -         |    -3.69 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            3 |     3831 | 2024-03-06 | Fraud5            | W   | 0.179      | -            | -                | -                | -         |     0.43 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            2 |     3856 | 2024-03-05 | B8                | L   | 0.174      | -            | -                | -                | -         |    -2.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            1 |     3885 | 2024-03-04 | ALTERNATE aTTaX   | W   | 0.166      | -            | -                | -                | -         |     1.77 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,454.51)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-25 |      1.000 | $11,000.00     | $11,000.00      |
| 2024-07-22 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-06 |      0.792 | $11,000.00     | $8,707.31       |
| 2024-05-03 |      0.567 | $12,500.00     | $7,085.65       |
| 2024-03-31 |      0.346 | $657.00        | $227.61         |
| 2024-03-30 |      0.339 | $1,000.00      | $339.35         |
| 2024-03-18 |      0.259 | $3,000.00      | $775.56         |
| 2024-03-11 |      0.213 | $1,500.00      | $319.03         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
