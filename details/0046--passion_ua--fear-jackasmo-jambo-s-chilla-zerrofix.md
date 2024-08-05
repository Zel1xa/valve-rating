### Roster Details<br />
Team Name: Passion UA<br />
Roster: fear, jackasmo, jambo, s-chilla, zeRRoFIX<br />
Global Rank: [46](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [33]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1094.5<br />
<br />
Final Rank Value (1094.5) = Starting Rank Value (1092.7) + Head To Head Adjustments (1.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.567[<sup>1</sup>](#table2)
- Bounty Collected: 0.462[<sup>2</sup>](#table1)
- Opponent Network: 0.324[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.338<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1092.7
- 400 + ( ( 0.338 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1092.7


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
|           93 |       64 | 2024-08-03 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -8.65 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           92 |      142 | 2024-08-01 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           91 |      223 | 2024-07-30 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.21 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           90 |      258 | 2024-07-29 | Nexus             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.64 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           89 |      270 | 2024-07-29 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -27.93 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           88 |      312 | 2024-07-27 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -12.76 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           87 |      334 | 2024-07-26 | Gaimin Gladiators | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.80 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           86 |      353 | 2024-07-26 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.21 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           85 |      374 | 2024-07-25 | EYEBALLERS        | L   | 1.000      | -            | -                | -                | -         |   -26.84 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           84 |      392 | 2024-07-25 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.28 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           83 |      457 | 2024-07-23 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.83 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           82 |      479 | 2024-07-22 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.42 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           81 |      485 | 2024-07-22 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.58 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           80 |      505 | 2024-07-21 | Zero Tenacity     | W   | 1.000      | 0.500        | 0.137 (0.068)    | 1.000 (0.500)    | 0 (0.000) |    16.98 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           79 |      540 | 2024-07-20 | Ninjas in Pyjamas | W   | 1.000      | 0.500        | 0.254 (0.127)    | 0.551 (0.276)    | 0 (0.000) |    29.70 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           78 |      553 | 2024-07-20 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | -                | -         |     8.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           77 |      582 | 2024-07-19 | Nemiga            | W   | 1.000      | 0.500        | 0.316 (0.158)    | 0.731 (0.365)    | -         |    20.95 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           76 |      639 | 2024-07-18 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.122 (0.045)    | 0.940 (0.348)    | -         |    23.52 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           75 |      650 | 2024-07-18 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -23.59 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           74 |      706 | 2024-07-17 | Aurora Young Blud | W   | 1.000      | 0.500        | -                | 0.499 (0.249)    | -         |     9.92 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           73 |      767 | 2024-07-16 | Permitta          | W   | 1.000      | 0.371        | -                | 0.873 (0.324)    | -         |    11.67 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           72 |      789 | 2024-07-15 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -9.51 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           71 |      809 | 2024-07-15 | WOPA              | W   | 1.000      | -            | -                | -                | -         |     1.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           70 |      827 | 2024-07-14 | Preasy            | W   | 1.000      | -            | -                | -                | -         |     6.25 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           69 |      891 | 2024-07-10 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -18.76 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           68 |      909 | 2024-07-09 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.61 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           67 |      911 | 2024-07-09 | Insilio           | W   | 1.000      | -            | -                | -                | -         |    11.43 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           66 |      931 | 2024-07-08 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.54 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           65 |     1105 | 2024-06-14 | 3DMAX             | L   | 0.852      | -            | -                | -                | -         |    -3.08 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           64 |     1197 | 2024-06-10 | Space             | W   | 0.827      | -            | -                | -                | -         |     6.66 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           63 |     1309 | 2024-06-08 | Zero Tenacity     | L   | 0.814      | -            | -                | -                | -         |   -11.82 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           62 |     1371 | 2024-06-07 | Rare Atom         | W   | 0.807      | -            | -                | -                | -         |     5.34 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           61 |     1384 | 2024-06-07 | Aurora Young Blud | W   | 0.806      | -            | -                | -                | -         |     6.03 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           60 |     1455 | 2024-06-06 | Serbia            | W   | 0.799      | -            | -                | -                | -         |     5.16 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           59 |     1507 | 2024-06-05 | EYEBALLERS        | L   | 0.792      | -            | -                | -                | -         |   -19.07 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           58 |     1537 | 2024-06-04 | Illuminar         | W   | 0.787      | -            | -                | -                | -         |     4.94 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           57 |     1546 | 2024-06-04 | Serbia            | W   | 0.786      | -            | -                | -                | -         |     4.62 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           56 |     1595 | 2024-06-02 | UNiTY             | W   | 0.772      | -            | -                | -                | -         |     8.93 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           55 |     1656 | 2024-05-31 | Zero Tenacity     | L   | 0.760      | -            | -                | -                | -         |   -10.60 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           54 |     1677 | 2024-05-30 | Zero Tenacity     | W   | 0.754      | 0.371        | 0.137 (0.038)    | 1.000 (0.279)    | -         |    13.50 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           53 |     1706 | 2024-05-29 | Illuminar         | W   | 0.746      | -            | -                | -                | -         |     5.75 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           52 |     1777 | 2024-05-25 | Sampi             | W   | 0.721      | 0.435        | -                | 1.000 (0.313)    | -         |     7.38 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           51 |     1798 | 2024-05-24 | FURIA             | L   | 0.714      | -            | -                | -                | -         |    -0.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           50 |     1804 | 2024-05-24 | ECSTATIC          | W   | 0.712      | -            | -                | -                | -         |     0.59 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           49 |     1818 | 2024-05-23 | SINNERS           | W   | 0.706      | -            | -                | -                | -         |    12.27 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           48 |     1942 | 2024-05-20 | Permitta          | W   | 0.686      | 0.435        | -                | 0.873 (0.260)    | -         |     6.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           47 |     1954 | 2024-05-19 | Sashi             | L   | 0.681      | -            | -                | -                | -         |    -5.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           46 |     1965 | 2024-05-19 | ALTERNATE aTTaX   | W   | 0.679      | -            | -                | -                | -         |     8.00 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           45 |     1985 | 2024-05-18 | 9 Pandas          | L   | 0.674      | -            | -                | -                | -         |   -10.84 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           44 |     2028 | 2024-05-17 | Nexus             | W   | 0.666      | -            | -                | -                | -         |     4.39 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           43 |     2069 | 2024-05-16 | Sashi             | W   | 0.659      | 0.500        | 0.184 (0.061)    | 0.996 (0.328)    | -         |    15.51 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           42 |     2108 | 2024-05-15 | Endpoint          | L   | 0.654      | -            | -                | -                | -         |   -12.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           41 |     2162 | 2024-05-14 | SINNERS           | L   | 0.648      | -            | -                | -                | -         |    -9.09 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           40 |     2255 | 2024-05-11 | Preasy            | W   | 0.625      | -            | -                | -                | -         |     3.73 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           39 |     2419 | 2024-05-02 | Nemiga            | L   | 0.567      | -            | -                | -                | -         |    -5.66 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           38 |     2442 | 2024-05-01 | PARIVISION        | W   | 0.561      | -            | -                | -                | -         |    10.26 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           37 |     2479 | 2024-04-30 | 9 Pandas          | W   | 0.552      | -            | -                | -                | -         |     7.43 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           36 |     2506 | 2024-04-28 | ALTERNATE aTTaX   | L   | 0.541      | -            | -                | -                | -         |   -10.16 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           35 |     2556 | 2024-04-26 | 9 Pandas          | W   | 0.527      | -            | -                | -                | -         |     7.30 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           34 |     2557 | 2024-04-26 | 9 Pandas          | W   | 0.527      | -            | -                | -                | -         |     6.98 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           33 |     2593 | 2024-04-25 | Sashi             | L   | 0.519      | -            | -                | -                | -         |    -4.95 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           32 |     2608 | 2024-04-24 | Permitta          | L   | 0.514      | -            | -                | -                | -         |    -9.46 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           31 |     2637 | 2024-04-22 | B8                | L   | 0.501      | -            | -                | -                | -         |    -7.82 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           30 |     2678 | 2024-04-20 | Young Ninjas      | W   | 0.488      | -            | -                | -                | -         |     2.82 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           29 |     2700 | 2024-04-20 | Permitta          | L   | 0.485      | -            | -                | -                | -         |    -9.41 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           28 |     2734 | 2024-04-19 | ALTERNATE aTTaX   | L   | 0.480      | -            | -                | -                | -         |    -9.63 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           27 |     2791 | 2024-04-18 | Permitta          | W   | 0.473      | -            | -                | -                | -         |     5.62 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           26 |     2821 | 2024-04-17 | Sashi             | W   | 0.467      | 0.371        | 0.184 (0.032)    | -                | -         |     8.98 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           25 |     2855 | 2024-04-16 | 500               | L   | 0.461      | -            | -                | -                | -         |   -12.33 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           24 |     2894 | 2024-04-14 | SINNERS           | L   | 0.446      | -            | -                | -                | -         |    -4.84 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           23 |     2949 | 2024-04-11 | 3DMAX             | W   | 0.427      | 0.384        | 0.508 (0.083)    | -                | -         |    12.98 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           22 |     2997 | 2024-04-10 | Sashi             | W   | 0.419      | 0.371        | 0.184 (0.029)    | -                | -         |     8.36 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           21 |     3184 | 2024-04-04 | HAVU              | W   | 0.380      | -            | -                | -                | -         |     1.62 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           20 |     3255 | 2024-04-02 | BLEED             | L   | 0.367      | -            | -                | -                | -         |    -6.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           19 |     3284 | 2024-03-31 | FAVBET            | L   | 0.353      | -            | -                | -                | -         |    -9.17 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           18 |     3291 | 2024-03-30 | Lazer Cats        | W   | 0.346      | -            | -                | -                | -         |     0.59 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           17 |     3299 | 2024-03-29 | NAVI Junior       | L   | 0.340      | -            | -                | -                | -         |    -9.45 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           16 |     3318 | 2024-03-28 | GL Academy        | L   | 0.333      | -            | -                | -                | -         |    -9.07 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           15 |     3528 | 2024-03-17 | Sampi             | L   | 0.259      | -            | -                | -                | -         |    -5.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           14 |     3537 | 2024-03-16 | ex-Preasy         | L   | 0.253      | -            | -                | -                | -         |    -6.61 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           13 |     3590 | 2024-03-14 | Sampi             | W   | 0.240      | -            | -                | -                | -         |     2.01 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           12 |     3658 | 2024-03-12 | Alliance          | W   | 0.226      | -            | -                | -                | -         |     1.67 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           11 |     3680 | 2024-03-11 | MOUZ NXT          | L   | 0.220      | -            | -                | -                | -         |    -3.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           10 |     3700 | 2024-03-10 | MOUZ NXT          | W   | 0.213      | -            | -                | -                | -         |     3.08 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            9 |     3715 | 2024-03-09 | The Chosen Few    | L   | 0.207      | -            | -                | -                | -         |    -5.94 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            8 |     3740 | 2024-03-08 | Spirit Academy    | L   | 0.201      | -            | -                | -                | -         |    -6.03 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            7 |     3745 | 2024-03-08 | Entropiq          | W   | 0.200      | -            | -                | -                | -         |     0.30 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            6 |     3764 | 2024-03-07 | AURA              | W   | 0.195      | -            | -                | -                | -         |     0.21 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            5 |     3800 | 2024-03-06 | Permitta          | L   | 0.187      | -            | -                | -                | -         |    -4.05 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            4 |     3804 | 2024-03-06 | Fraud5            | W   | 0.186      | -            | -                | -                | -         |     0.45 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            3 |     3829 | 2024-03-05 | B8                | L   | 0.181      | -            | -                | -                | -         |    -2.97 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            2 |     3858 | 2024-03-04 | ALTERNATE aTTaX   | W   | 0.173      | -            | -                | -                | -         |     1.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            1 |     4391 | 2024-02-08 | BLEED             | L   | 0.006      | -            | -                | -                | -         |    -0.13 | jackasmo, jambo, marat2k, s-chilla, Zinchenko |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,663.20)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-25 |      1.000 | $11,000.00     | $11,000.00      |
| 2024-07-22 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-06 |      0.799 | $11,000.00     | $8,784.72       |
| 2024-05-03 |      0.574 | $12,500.00     | $7,173.61       |
| 2024-03-31 |      0.353 | $657.00        | $232.23         |
| 2024-03-30 |      0.346 | $1,000.00      | $346.39         |
| 2024-03-18 |      0.266 | $3,000.00      | $796.67         |
| 2024-03-11 |      0.220 | $1,500.00      | $329.58         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
