### Roster Details<br />
Team Name: Passion UA<br />
Roster: fear, jackasmo, jambo, s-chilla, zeRRoFIX<br />
Global Rank: [43](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [31]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1099.4<br />
<br />
Final Rank Value (1099.4) = Starting Rank Value (1094.0) + Head To Head Adjustments (5.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.567[<sup>1</sup>](#table2)
- Bounty Collected: 0.466[<sup>2</sup>](#table1)
- Opponent Network: 0.314[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.337<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1094.0
- 400 + ( ( 0.337 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1094.0


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
|           97 |        2 | 2024-08-01 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.66 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           96 |       85 | 2024-07-30 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.38 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           95 |      121 | 2024-07-29 | Nexus             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.26 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           94 |      133 | 2024-07-29 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -28.06 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           93 |      175 | 2024-07-27 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -12.61 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           92 |      197 | 2024-07-26 | Gaimin Gladiators | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.42 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           91 |      216 | 2024-07-26 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.42 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           90 |      237 | 2024-07-25 | EYEBALLERS        | L   | 1.000      | -            | -                | -                | -         |   -26.64 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           89 |      255 | 2024-07-25 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.39 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           88 |      320 | 2024-07-23 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.12 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           87 |      343 | 2024-07-22 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -7.06 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           86 |      349 | 2024-07-22 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.50 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           85 |      370 | 2024-07-21 | Zero Tenacity     | W   | 1.000      | 0.500        | 0.139 (0.069)    | 1.000 (0.500)    | 0 (0.000) |    15.03 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           84 |      406 | 2024-07-20 | Ninjas in Pyjamas | W   | 1.000      | 0.500        | 0.207 (0.104)    | -                | 0 (0.000) |    27.93 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           83 |      419 | 2024-07-20 | RUBY              | W   | 1.000      | 0.435        | 0.097 (0.042)    | -                | -         |     8.81 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           82 |      442 | 2024-07-19 | Rebels            | W   | 1.000      | -            | -                | -                | -         |    12.49 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           81 |      450 | 2024-07-19 | Nemiga            | W   | 1.000      | 0.500        | 0.324 (0.162)    | 0.697 (0.349)    | -         |    20.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           80 |      511 | 2024-07-18 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.124 (0.046)    | 0.818 (0.303)    | -         |    23.92 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           79 |      520 | 2024-07-18 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -23.05 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           78 |      579 | 2024-07-17 | Aurora Young Blud | W   | 1.000      | -            | -                | -                | -         |    11.24 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           77 |      644 | 2024-07-16 | Permitta          | W   | 1.000      | 0.371        | -                | 0.801 (0.297)    | -         |    12.17 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           76 |      667 | 2024-07-15 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -9.49 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           75 |      689 | 2024-07-15 | WOPA              | W   | 1.000      | -            | -                | -                | -         |     2.04 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           74 |      707 | 2024-07-14 | Preasy            | W   | 1.000      | -            | -                | -                | -         |     6.75 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           73 |      771 | 2024-07-10 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -18.20 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           72 |      789 | 2024-07-09 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.55 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           71 |      791 | 2024-07-09 | Insilio           | W   | 1.000      | -            | -                | -                | -         |    12.24 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           70 |      811 | 2024-07-08 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.44 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           69 |      974 | 2024-06-14 | 3DMAX             | L   | 0.879      | -            | -                | -                | -         |    -3.10 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           68 |     1068 | 2024-06-10 | Space             | W   | 0.854      | -            | -                | -                | -         |     7.71 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           67 |     1182 | 2024-06-08 | Zero Tenacity     | L   | 0.841      | -            | -                | -                | -         |   -13.32 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           66 |     1251 | 2024-06-07 | Rare Atom         | W   | 0.834      | -            | -                | -                | -         |     2.57 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           65 |     1264 | 2024-06-07 | Aurora Young Blud | W   | 0.833      | -            | -                | -                | -         |     6.74 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           64 |     1338 | 2024-06-06 | Serbia            | W   | 0.826      | -            | -                | -                | -         |     5.80 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           63 |     1366 | 2024-06-05 | MOUZ NXT          | L   | 0.821      | -            | -                | -                | -         |   -10.81 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           62 |     1392 | 2024-06-05 | EYEBALLERS        | L   | 0.819      | -            | -                | -                | -         |   -19.46 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           61 |     1422 | 2024-06-04 | Illuminar         | W   | 0.814      | -            | -                | -                | -         |     5.68 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           60 |     1431 | 2024-06-04 | Serbia            | W   | 0.813      | -            | -                | -                | -         |     4.98 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           59 |     1481 | 2024-06-02 | UNiTY             | W   | 0.799      | -            | -                | -                | -         |     9.16 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           58 |     1542 | 2024-05-31 | Zero Tenacity     | L   | 0.787      | -            | -                | -                | -         |   -11.24 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           57 |     1563 | 2024-05-30 | Zero Tenacity     | W   | 0.781      | 0.371        | 0.139 (0.040)    | 1.000 (0.289)    | -         |    13.69 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           56 |     1592 | 2024-05-29 | Illuminar         | W   | 0.772      | -            | -                | -                | -         |     6.66 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           55 |     1665 | 2024-05-25 | Sampi             | W   | 0.748      | 0.435        | -                | 1.000 (0.325)    | -         |     7.72 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           54 |     1686 | 2024-05-24 | FURIA             | L   | 0.741      | -            | -                | -                | -         |    -0.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           53 |     1692 | 2024-05-24 | ECSTATIC          | W   | 0.739      | -            | -                | -                | -         |     0.63 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           52 |     1706 | 2024-05-23 | SINNERS           | W   | 0.733      | 0.435        | -                | 0.768 (0.245)    | -         |    11.80 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           51 |     1835 | 2024-05-20 | Sangal            | W   | 0.714      | 0.435        | 0.221 (0.069)    | 0.823 (0.256)    | -         |    14.08 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           50 |     1850 | 2024-05-20 | Permitta          | W   | 0.713      | 0.435        | -                | 0.801 (0.248)    | -         |     7.43 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           49 |     1855 | 2024-05-19 | Illuminar         | L   | 0.709      | -            | -                | -                | -         |   -13.92 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           48 |     1867 | 2024-05-19 | Sashi             | L   | 0.708      | -            | -                | -                | -         |    -5.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           47 |     1878 | 2024-05-19 | ALTERNATE aTTaX   | W   | 0.706      | -            | -                | -                | -         |     8.16 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           46 |     1898 | 2024-05-18 | 9 Pandas          | L   | 0.701      | -            | -                | -                | -         |   -10.82 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           45 |     1942 | 2024-05-17 | Nexus             | W   | 0.693      | -            | -                | -                | -         |     4.76 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           44 |     1983 | 2024-05-16 | Sashi             | W   | 0.686      | 0.500        | 0.187 (0.064)    | 0.971 (0.333)    | -         |    16.40 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           43 |     2022 | 2024-05-15 | Endpoint          | L   | 0.681      | -            | -                | -                | -         |   -12.68 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           42 |     2082 | 2024-05-14 | SINNERS           | L   | 0.675      | -            | -                | -                | -         |   -10.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           41 |     2178 | 2024-05-11 | Preasy            | W   | 0.652      | -            | -                | -                | -         |     4.04 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           40 |     2345 | 2024-05-02 | Nemiga            | L   | 0.594      | -            | -                | -                | -         |    -6.12 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           39 |     2369 | 2024-05-01 | PARIVISION        | W   | 0.588      | -            | -                | -                | -         |    10.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           38 |     2407 | 2024-04-30 | 9 Pandas          | W   | 0.579      | -            | -                | -                | -         |     8.20 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           37 |     2434 | 2024-04-28 | ALTERNATE aTTaX   | L   | 0.568      | -            | -                | -                | -         |   -10.47 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           36 |     2485 | 2024-04-26 | 9 Pandas          | W   | 0.554      | -            | -                | -                | -         |     7.73 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           35 |     2521 | 2024-04-25 | Sashi             | L   | 0.546      | -            | -                | -                | -         |    -5.08 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           34 |     2536 | 2024-04-24 | Permitta          | L   | 0.540      | -            | -                | -                | -         |    -9.82 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           33 |     2568 | 2024-04-22 | B8                | L   | 0.528      | -            | -                | -                | -         |    -8.10 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           32 |     2612 | 2024-04-20 | Young Ninjas      | W   | 0.515      | -            | -                | -                | -         |     3.10 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           31 |     2634 | 2024-04-20 | Permitta          | L   | 0.512      | -            | -                | -                | -         |   -10.05 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           30 |     2669 | 2024-04-19 | ALTERNATE aTTaX   | L   | 0.507      | -            | -                | -                | -         |   -10.20 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           29 |     2727 | 2024-04-18 | Permitta          | W   | 0.500      | -            | -                | -                | -         |     5.80 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           28 |     2758 | 2024-04-17 | Sashi             | W   | 0.494      | 0.371        | 0.187 (0.034)    | -                | -         |     9.51 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           27 |     2792 | 2024-04-16 | 500               | L   | 0.488      | -            | -                | -                | -         |   -12.72 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           26 |     2832 | 2024-04-14 | SINNERS           | L   | 0.473      | -            | -                | -                | -         |    -6.69 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           25 |     2888 | 2024-04-11 | 3DMAX             | W   | 0.454      | 0.384        | 0.505 (0.088)    | -                | -         |    13.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           24 |     2936 | 2024-04-10 | Sashi             | W   | 0.446      | -            | -                | -                | -         |     8.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           23 |     3124 | 2024-04-04 | HAVU              | W   | 0.407      | -            | -                | -                | -         |     1.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           22 |     3202 | 2024-04-02 | BLEED             | L   | 0.394      | -            | -                | -                | -         |    -7.22 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           21 |     3231 | 2024-03-31 | FAVBET            | L   | 0.380      | -            | -                | -                | -         |    -9.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           20 |     3238 | 2024-03-30 | Lazer Cats        | W   | 0.373      | -            | -                | -                | -         |     0.63 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           19 |     3246 | 2024-03-29 | NAVI Junior       | L   | 0.367      | -            | -                | -                | -         |   -10.18 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           18 |     3265 | 2024-03-28 | GL Academy        | L   | 0.360      | -            | -                | -                | -         |    -9.80 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           17 |     3480 | 2024-03-17 | Sampi             | L   | 0.286      | -            | -                | -                | -         |    -6.47 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           16 |     3489 | 2024-03-16 | ex-Preasy         | L   | 0.280      | -            | -                | -                | -         |    -7.24 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           15 |     3546 | 2024-03-14 | Sampi             | W   | 0.267      | -            | -                | -                | -         |     2.26 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           14 |     3615 | 2024-03-12 | Alliance          | W   | 0.253      | -            | -                | -                | -         |     1.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           13 |     3637 | 2024-03-11 | MOUZ NXT          | L   | 0.247      | -            | -                | -                | -         |    -4.14 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           12 |     3657 | 2024-03-10 | MOUZ NXT          | W   | 0.240      | -            | -                | -                | -         |     3.58 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           11 |     3673 | 2024-03-09 | The Chosen Few    | L   | 0.234      | -            | -                | -                | -         |    -6.71 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           10 |     3698 | 2024-03-08 | Spirit Academy    | L   | 0.228      | -            | -                | -                | -         |    -6.84 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            9 |     3703 | 2024-03-08 | Entropiq          | W   | 0.227      | -            | -                | -                | -         |     0.34 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            8 |     3722 | 2024-03-07 | AURA              | W   | 0.221      | -            | -                | -                | -         |     0.24 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            7 |     3759 | 2024-03-06 | Permitta          | L   | 0.214      | -            | -                | -                | -         |    -4.74 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            6 |     3761 | 2024-03-06 | Fraud5            | W   | 0.213      | -            | -                | -                | -         |     0.52 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            5 |     3791 | 2024-03-05 | B8                | L   | 0.208      | -            | -                | -                | -         |    -3.38 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            4 |     3794 | 2024-03-05 | fnatic            | W   | 0.208      | -            | -                | -                | -         |     5.35 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            3 |     3821 | 2024-03-04 | ALTERNATE aTTaX   | W   | 0.200      | -            | -                | -                | -         |     2.17 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            2 |     4030 | 2024-02-23 | ALTERNATE aTTaX   | W   | 0.133      | -            | -                | -                | -         |     1.55 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            1 |     4374 | 2024-02-08 | BLEED             | L   | 0.033      | -            | -                | -                | -         |    -0.70 | jackasmo, jambo, marat2k, s-chilla, Zinchenko |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($56,462.29)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-25 |      1.000 | $11,000.00     | $11,000.00      |
| 2024-07-22 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-06 |      0.826 | $11,000.00     | $9,081.11       |
| 2024-05-03 |      0.601 | $12,500.00     | $7,510.42       |
| 2024-03-31 |      0.380 | $657.00        | $249.93         |
| 2024-03-30 |      0.373 | $1,000.00      | $373.33         |
| 2024-03-18 |      0.292 | $3,000.00      | $877.50         |
| 2024-03-11 |      0.247 | $1,500.00      | $370.00         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
