### Roster Details<br />
Team Name: Passion UA<br />
Roster: fear, jackasmo, jambo, s-chilla, zeRRoFIX<br />
Global Rank: [47](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [34]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1095.2<br />
<br />
Final Rank Value (1095.2) = Starting Rank Value (1097.6) + Head To Head Adjustments (-2.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.568[<sup>1</sup>](#table2)
- Bounty Collected: 0.462[<sup>2</sup>](#table1)
- Opponent Network: 0.330[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.340<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1097.6
- 400 + ( ( 0.340 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1097.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           93 |       79 | 2024-08-03 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -8.64 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           92 |      157 | 2024-08-01 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           91 |      238 | 2024-07-30 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.21 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           90 |      273 | 2024-07-29 | Nexus             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.67 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           89 |      285 | 2024-07-29 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -27.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           88 |      327 | 2024-07-27 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -12.83 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           87 |      349 | 2024-07-26 | Gaimin Gladiators | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.76 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           86 |      368 | 2024-07-26 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.20 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           85 |      389 | 2024-07-25 | EYEBALLERS        | L   | 1.000      | -            | -                | -                | -         |   -26.81 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           84 |      407 | 2024-07-25 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.29 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           83 |      472 | 2024-07-23 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.84 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           82 |      494 | 2024-07-22 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.44 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           81 |      500 | 2024-07-22 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.62 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           80 |      520 | 2024-07-21 | Zero Tenacity     | W   | 1.000      | 0.500        | 0.143 (0.071)    | 1.000 (0.500)    | 0 (0.000) |    16.99 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           79 |      555 | 2024-07-20 | Ninjas in Pyjamas | W   | 1.000      | 0.500        | 0.254 (0.127)    | 0.543 (0.272)    | 0 (0.000) |    29.69 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           78 |      568 | 2024-07-20 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | -                | -         |     8.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           77 |      597 | 2024-07-19 | Nemiga            | W   | 1.000      | 0.500        | 0.315 (0.157)    | 0.720 (0.360)    | -         |    20.96 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           76 |      654 | 2024-07-18 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.122 (0.045)    | 1.000 (0.371)    | -         |    23.51 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           75 |      665 | 2024-07-18 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -23.60 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           74 |      721 | 2024-07-17 | Aurora Young Blud | W   | 1.000      | 0.500        | -                | 0.533 (0.266)    | -         |    10.56 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           73 |      782 | 2024-07-16 | Permitta          | W   | 1.000      | 0.371        | -                | 0.940 (0.348)    | -         |    11.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           72 |      804 | 2024-07-15 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -9.50 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           71 |      824 | 2024-07-15 | WOPA              | W   | 1.000      | -            | -                | -                | -         |     1.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           70 |      842 | 2024-07-14 | Preasy            | W   | 1.000      | -            | -                | -                | -         |     2.14 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           69 |      906 | 2024-07-10 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -18.71 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           68 |      924 | 2024-07-09 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.69 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           67 |      926 | 2024-07-09 | Insilio           | W   | 1.000      | -            | -                | -                | -         |    11.44 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           66 |      946 | 2024-07-08 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.62 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           65 |     1120 | 2024-06-14 | 3DMAX             | L   | 0.846      | -            | -                | -                | -         |    -3.05 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           64 |     1212 | 2024-06-10 | Space             | W   | 0.821      | -            | -                | -                | -         |     6.52 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           63 |     1324 | 2024-06-08 | Zero Tenacity     | L   | 0.808      | -            | -                | -                | -         |   -11.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           62 |     1386 | 2024-06-07 | Rare Atom         | W   | 0.801      | -            | -                | -                | -         |     5.23 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           61 |     1399 | 2024-06-07 | Aurora Young Blud | W   | 0.800      | -            | -                | -                | -         |     6.46 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           60 |     1470 | 2024-06-06 | Serbia            | W   | 0.793      | -            | -                | -                | -         |     5.05 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           59 |     1522 | 2024-06-05 | EYEBALLERS        | L   | 0.786      | -            | -                | -                | -         |   -18.99 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           58 |     1552 | 2024-06-04 | Illuminar         | W   | 0.781      | -            | -                | -                | -         |     4.85 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           57 |     1561 | 2024-06-04 | Serbia            | W   | 0.780      | -            | -                | -                | -         |     4.52 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           56 |     1610 | 2024-06-02 | UNiTY             | W   | 0.766      | -            | -                | -                | -         |     8.76 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           55 |     1671 | 2024-05-31 | Zero Tenacity     | L   | 0.754      | -            | -                | -                | -         |   -10.66 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           54 |     1692 | 2024-05-30 | Zero Tenacity     | W   | 0.748      | 0.371        | 0.143 (0.040)    | 1.000 (0.277)    | -         |    13.24 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           53 |     1721 | 2024-05-29 | Illuminar         | W   | 0.740      | -            | -                | -                | -         |     5.63 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           52 |     1792 | 2024-05-25 | Sampi             | W   | 0.715      | 0.435        | -                | 1.000 (0.311)    | -         |     7.21 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           51 |     1813 | 2024-05-24 | FURIA             | L   | 0.708      | -            | -                | -                | -         |    -0.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           50 |     1819 | 2024-05-24 | ECSTATIC          | W   | 0.706      | -            | -                | -                | -         |     1.28 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           49 |     1833 | 2024-05-23 | SINNERS           | W   | 0.700      | -            | -                | -                | -         |    12.19 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           48 |     1957 | 2024-05-20 | Permitta          | W   | 0.680      | 0.435        | -                | 0.940 (0.278)    | -         |     6.84 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           47 |     1969 | 2024-05-19 | Sashi             | L   | 0.675      | -            | -                | -                | -         |    -5.92 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           46 |     1980 | 2024-05-19 | ALTERNATE aTTaX   | W   | 0.673      | -            | -                | -                | -         |     7.85 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           45 |     2000 | 2024-05-18 | 9 Pandas          | L   | 0.668      | -            | -                | -                | -         |   -10.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           44 |     2043 | 2024-05-17 | Nexus             | W   | 0.660      | -            | -                | -                | -         |     4.30 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           43 |     2084 | 2024-05-16 | Sashi             | W   | 0.653      | 0.500        | 0.184 (0.060)    | 0.980 (0.320)    | -         |    15.27 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           42 |     2123 | 2024-05-15 | Endpoint          | L   | 0.648      | -            | -                | -                | -         |   -12.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           41 |     2177 | 2024-05-14 | SINNERS           | L   | 0.642      | -            | -                | -                | -         |    -8.99 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           40 |     2270 | 2024-05-11 | Preasy            | W   | 0.619      | -            | -                | -                | -         |     3.50 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           39 |     2434 | 2024-05-02 | Nemiga            | L   | 0.561      | -            | -                | -                | -         |    -5.72 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           38 |     2457 | 2024-05-01 | PARIVISION        | W   | 0.555      | -            | -                | -                | -         |    10.13 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           37 |     2494 | 2024-04-30 | 9 Pandas          | W   | 0.546      | -            | -                | -                | -         |     7.21 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           36 |     2521 | 2024-04-28 | ALTERNATE aTTaX   | L   | 0.535      | -            | -                | -                | -         |   -10.15 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           35 |     2571 | 2024-04-26 | 9 Pandas          | W   | 0.521      | -            | -                | -                | -         |     7.06 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           34 |     2572 | 2024-04-26 | 9 Pandas          | W   | 0.521      | -            | -                | -                | -         |     6.75 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           33 |     2608 | 2024-04-25 | Sashi             | L   | 0.514      | -            | -                | -                | -         |    -5.00 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           32 |     2623 | 2024-04-24 | Permitta          | L   | 0.508      | -            | -                | -                | -         |    -9.25 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           31 |     2652 | 2024-04-22 | B8                | L   | 0.496      | -            | -                | -                | -         |    -7.84 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           30 |     2693 | 2024-04-20 | Young Ninjas      | W   | 0.482      | -            | -                | -                | -         |     2.77 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           29 |     2715 | 2024-04-20 | Permitta          | L   | 0.479      | -            | -                | -                | -         |    -9.17 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           28 |     2749 | 2024-04-19 | ALTERNATE aTTaX   | L   | 0.474      | -            | -                | -                | -         |    -9.60 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           27 |     2806 | 2024-04-18 | Permitta          | W   | 0.467      | -            | -                | -                | -         |     5.68 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           26 |     2836 | 2024-04-17 | Sashi             | W   | 0.461      | 0.371        | 0.184 (0.031)    | -                | -         |     8.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           25 |     2870 | 2024-04-16 | 500               | L   | 0.455      | -            | -                | -                | -         |   -12.24 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           24 |     2909 | 2024-04-14 | SINNERS           | L   | 0.440      | -            | -                | -                | -         |    -4.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           23 |     2964 | 2024-04-11 | 3DMAX             | W   | 0.421      | 0.384        | 0.509 (0.082)    | -                | -         |    12.80 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           22 |     3012 | 2024-04-10 | Sashi             | W   | 0.414      | 0.371        | 0.184 (0.028)    | -                | -         |     8.16 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           21 |     3199 | 2024-04-04 | HAVU              | W   | 0.374      | -            | -                | -                | -         |     1.54 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           20 |     3270 | 2024-04-02 | BLEED             | L   | 0.362      | -            | -                | -                | -         |    -6.85 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           19 |     3299 | 2024-03-31 | FAVBET            | L   | 0.348      | -            | -                | -                | -         |    -9.07 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           18 |     3306 | 2024-03-30 | Lazer Cats        | W   | 0.340      | -            | -                | -                | -         |     0.57 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           17 |     3314 | 2024-03-29 | NAVI Junior       | L   | 0.334      | -            | -                | -                | -         |    -9.32 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           16 |     3333 | 2024-03-28 | GL Academy        | L   | 0.327      | -            | -                | -                | -         |    -8.95 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           15 |     3543 | 2024-03-17 | Sampi             | L   | 0.253      | -            | -                | -                | -         |    -5.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           14 |     3552 | 2024-03-16 | ex-Preasy         | L   | 0.247      | -            | -                | -                | -         |    -6.50 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           13 |     3605 | 2024-03-14 | Sampi             | W   | 0.234      | -            | -                | -                | -         |     1.92 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           12 |     3673 | 2024-03-12 | Alliance          | W   | 0.221      | -            | -                | -                | -         |     1.58 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           11 |     3695 | 2024-03-11 | MOUZ NXT          | L   | 0.214      | -            | -                | -                | -         |    -3.73 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           10 |     3715 | 2024-03-10 | MOUZ NXT          | W   | 0.207      | -            | -                | -                | -         |     2.96 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            9 |     3730 | 2024-03-09 | The Chosen Few    | L   | 0.202      | -            | -                | -                | -         |    -5.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            8 |     3755 | 2024-03-08 | Spirit Academy    | L   | 0.195      | -            | -                | -                | -         |    -5.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            7 |     3760 | 2024-03-08 | Entropiq          | W   | 0.194      | -            | -                | -                | -         |     0.28 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            6 |     3779 | 2024-03-07 | AURA              | W   | 0.189      | -            | -                | -                | -         |     0.20 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            5 |     3815 | 2024-03-06 | Permitta          | L   | 0.181      | -            | -                | -                | -         |    -3.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            4 |     3819 | 2024-03-06 | Fraud5            | W   | 0.180      | -            | -                | -                | -         |     0.43 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            3 |     3844 | 2024-03-05 | B8                | L   | 0.176      | -            | -                | -                | -         |    -2.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            2 |     3873 | 2024-03-04 | ALTERNATE aTTaX   | W   | 0.167      | -            | -                | -                | -         |     1.77 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            1 |     4406 | 2024-02-08 | BLEED             | L   | 0.000      | -            | -                | -                | -         |    -0.01 | jackasmo, jambo, marat2k, s-chilla, Zinchenko |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,490.20)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-25 |      1.000 | $11,000.00     | $11,000.00      |
| 2024-07-22 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-06 |      0.793 | $11,000.00     | $8,720.56       |
| 2024-05-03 |      0.568 | $12,500.00     | $7,100.69       |
| 2024-03-31 |      0.348 | $657.00        | $228.40         |
| 2024-03-30 |      0.341 | $1,000.00      | $340.56         |
| 2024-03-18 |      0.260 | $3,000.00      | $779.17         |
| 2024-03-11 |      0.214 | $1,500.00      | $320.83         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />