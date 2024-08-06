### Roster Details<br />
Team Name: Passion UA<br />
Roster: fear, jackasmo, jambo, s-chilla, zeRRoFIX<br />
Global Rank: [47](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [34]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1100.0<br />
<br />
Final Rank Value (1100.0) = Starting Rank Value (1097.0) + Head To Head Adjustments (2.9)<br />

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
|           92 |       98 | 2024-08-03 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -8.38 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           91 |      176 | 2024-08-01 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           90 |      257 | 2024-07-30 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.15 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           89 |      292 | 2024-07-29 | Nexus             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.65 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           88 |      304 | 2024-07-29 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -27.95 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           87 |      346 | 2024-07-27 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -12.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           86 |      368 | 2024-07-26 | Gaimin Gladiators | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.62 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           85 |      387 | 2024-07-26 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.17 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           84 |      408 | 2024-07-25 | EYEBALLERS        | L   | 1.000      | -            | -                | -                | -         |   -26.82 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           83 |      426 | 2024-07-25 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.24 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           82 |      491 | 2024-07-23 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.77 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           81 |      513 | 2024-07-22 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.51 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           80 |      519 | 2024-07-22 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           79 |      539 | 2024-07-21 | Zero Tenacity     | W   | 1.000      | 0.500        | 0.143 (0.071)    | 1.000 (0.500)    | 0 (0.000) |    17.01 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           78 |      574 | 2024-07-20 | Ninjas in Pyjamas | W   | 1.000      | 0.500        | 0.253 (0.127)    | 0.531 (0.266)    | 0 (0.000) |    29.64 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           77 |      587 | 2024-07-20 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | -                | -         |     8.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           76 |      616 | 2024-07-19 | Nemiga            | W   | 1.000      | 0.500        | 0.314 (0.157)    | 0.704 (0.352)    | -         |    20.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           75 |      673 | 2024-07-18 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.122 (0.045)    | 1.000 (0.371)    | -         |    23.44 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           74 |      684 | 2024-07-18 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -23.74 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           73 |      740 | 2024-07-17 | Aurora Young Blud | W   | 1.000      | 0.500        | -                | 0.522 (0.261)    | -         |    11.39 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           72 |      801 | 2024-07-16 | Permitta          | W   | 1.000      | 0.371        | -                | 0.919 (0.340)    | -         |    12.10 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           71 |      823 | 2024-07-15 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -9.55 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           70 |      843 | 2024-07-15 | WOPA              | W   | 1.000      | -            | -                | -                | -         |     1.85 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           69 |      861 | 2024-07-14 | Preasy            | W   | 1.000      | -            | -                | -                | -         |     2.09 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           68 |      925 | 2024-07-10 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -18.44 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           67 |      943 | 2024-07-09 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.82 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           66 |      945 | 2024-07-09 | Insilio           | W   | 1.000      | -            | -                | -                | -         |    11.41 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           65 |      965 | 2024-07-08 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.76 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           64 |     1139 | 2024-06-14 | 3DMAX             | L   | 0.844      | -            | -                | -                | -         |    -3.08 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           63 |     1231 | 2024-06-10 | Space             | W   | 0.819      | -            | -                | -                | -         |     6.63 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           62 |     1343 | 2024-06-08 | Zero Tenacity     | L   | 0.806      | -            | -                | -                | -         |   -11.75 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           61 |     1405 | 2024-06-07 | Rare Atom         | W   | 0.799      | -            | -                | -                | -         |     5.29 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           60 |     1418 | 2024-06-07 | Aurora Young Blud | W   | 0.798      | -            | -                | -                | -         |     7.25 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           59 |     1489 | 2024-06-06 | Serbia            | W   | 0.791      | -            | -                | -                | -         |     5.04 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           58 |     1541 | 2024-06-05 | EYEBALLERS        | L   | 0.785      | -            | -                | -                | -         |   -18.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           57 |     1571 | 2024-06-04 | Illuminar         | W   | 0.779      | -            | -                | -                | -         |     4.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           56 |     1580 | 2024-06-04 | Serbia            | W   | 0.779      | -            | -                | -                | -         |     4.51 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           55 |     1629 | 2024-06-02 | UNiTY             | W   | 0.764      | -            | -                | -                | -         |     8.65 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           54 |     1690 | 2024-05-31 | Zero Tenacity     | L   | 0.752      | -            | -                | -                | -         |   -10.50 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           53 |     1711 | 2024-05-30 | Zero Tenacity     | W   | 0.746      | 0.371        | 0.143 (0.039)    | 1.000 (0.276)    | -         |    13.36 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           52 |     1740 | 2024-05-29 | Illuminar         | W   | 0.738      | -            | -                | -                | -         |     5.65 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           51 |     1811 | 2024-05-25 | Sampi             | W   | 0.713      | 0.435        | -                | 1.000 (0.310)    | -         |     7.17 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           50 |     1832 | 2024-05-24 | FURIA             | L   | 0.706      | -            | -                | -                | -         |    -0.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           49 |     1838 | 2024-05-24 | ECSTATIC          | W   | 0.704      | -            | -                | -                | -         |     1.26 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           48 |     1852 | 2024-05-23 | SINNERS           | W   | 0.698      | -            | -                | -                | -         |    12.15 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           47 |     1976 | 2024-05-20 | Permitta          | W   | 0.678      | 0.435        | -                | 0.919 (0.271)    | -         |     7.03 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           46 |     1988 | 2024-05-19 | Sashi             | L   | 0.673      | -            | -                | -                | -         |    -5.94 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           45 |     1999 | 2024-05-19 | ALTERNATE aTTaX   | W   | 0.672      | -            | -                | -                | -         |     7.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           44 |     2019 | 2024-05-18 | 9 Pandas          | L   | 0.666      | -            | -                | -                | -         |   -10.70 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           43 |     2062 | 2024-05-17 | Nexus             | W   | 0.658      | -            | -                | -                | -         |     4.33 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           42 |     2103 | 2024-05-16 | Sashi             | W   | 0.651      | 0.500        | 0.184 (0.060)    | 0.958 (0.312)    | -         |    15.19 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           41 |     2142 | 2024-05-15 | Endpoint          | L   | 0.646      | -            | -                | -                | -         |   -12.73 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           40 |     2196 | 2024-05-14 | SINNERS           | L   | 0.640      | -            | -                | -                | -         |    -8.97 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           39 |     2289 | 2024-05-11 | Preasy            | W   | 0.618      | -            | -                | -                | -         |     3.45 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           38 |     2453 | 2024-05-02 | Nemiga            | L   | 0.560      | -            | -                | -                | -         |    -5.72 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           37 |     2476 | 2024-05-01 | PARIVISION        | W   | 0.553      | -            | -                | -                | -         |    10.76 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           36 |     2513 | 2024-04-30 | 9 Pandas          | W   | 0.545      | -            | -                | -                | -         |     7.35 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           35 |     2540 | 2024-04-28 | ALTERNATE aTTaX   | L   | 0.533      | -            | -                | -                | -         |   -10.04 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           34 |     2590 | 2024-04-26 | 9 Pandas          | W   | 0.520      | -            | -                | -                | -         |     7.22 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           33 |     2591 | 2024-04-26 | 9 Pandas          | W   | 0.520      | -            | -                | -                | -         |     6.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           32 |     2627 | 2024-04-25 | Sashi             | L   | 0.512      | -            | -                | -                | -         |    -4.99 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           31 |     2642 | 2024-04-24 | Permitta          | L   | 0.506      | -            | -                | -                | -         |    -8.94 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           30 |     2671 | 2024-04-22 | B8                | L   | 0.494      | -            | -                | -                | -         |    -7.74 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           29 |     2712 | 2024-04-20 | Young Ninjas      | W   | 0.480      | -            | -                | -                | -         |     2.74 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           28 |     2734 | 2024-04-20 | Permitta          | L   | 0.478      | -            | -                | -                | -         |    -8.84 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           27 |     2768 | 2024-04-19 | ALTERNATE aTTaX   | L   | 0.473      | -            | -                | -                | -         |    -9.47 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           26 |     2825 | 2024-04-18 | Permitta          | W   | 0.465      | -            | -                | -                | -         |     5.96 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           25 |     2855 | 2024-04-17 | Sashi             | W   | 0.459      | 0.371        | 0.184 (0.031)    | -                | -         |     8.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           24 |     2889 | 2024-04-16 | 500               | L   | 0.453      | -            | -                | -                | -         |   -12.16 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           23 |     2928 | 2024-04-14 | SINNERS           | L   | 0.439      | -            | -                | -                | -         |    -4.74 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           22 |     2983 | 2024-04-11 | 3DMAX             | W   | 0.419      | 0.384        | 0.510 (0.082)    | -                | -         |    12.75 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           21 |     3031 | 2024-04-10 | Sashi             | W   | 0.412      | 0.371        | 0.184 (0.028)    | -                | -         |     8.15 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           20 |     3218 | 2024-04-04 | HAVU              | W   | 0.372      | -            | -                | -                | -         |     1.53 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           19 |     3289 | 2024-04-02 | BLEED             | L   | 0.360      | -            | -                | -                | -         |    -6.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           18 |     3318 | 2024-03-31 | FAVBET            | L   | 0.346      | -            | -                | -                | -         |    -9.01 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           17 |     3325 | 2024-03-30 | Lazer Cats        | W   | 0.339      | -            | -                | -                | -         |     0.56 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           16 |     3333 | 2024-03-29 | NAVI Junior       | L   | 0.332      | -            | -                | -                | -         |    -9.14 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           15 |     3352 | 2024-03-28 | GL Academy        | L   | 0.325      | -            | -                | -                | -         |    -8.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           14 |     3562 | 2024-03-17 | Sampi             | L   | 0.251      | -            | -                | -                | -         |    -5.75 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           13 |     3571 | 2024-03-16 | ex-Preasy         | L   | 0.246      | -            | -                | -                | -         |    -6.45 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           12 |     3624 | 2024-03-14 | Sampi             | W   | 0.232      | -            | -                | -                | -         |     1.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           11 |     3692 | 2024-03-12 | Alliance          | W   | 0.219      | -            | -                | -                | -         |     1.58 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           10 |     3714 | 2024-03-11 | MOUZ NXT          | L   | 0.212      | -            | -                | -                | -         |    -3.68 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            9 |     3734 | 2024-03-10 | MOUZ NXT          | W   | 0.206      | -            | -                | -                | -         |     2.94 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            8 |     3749 | 2024-03-09 | The Chosen Few    | L   | 0.200      | -            | -                | -                | -         |    -5.73 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            7 |     3774 | 2024-03-08 | Spirit Academy    | L   | 0.193      | -            | -                | -                | -         |    -5.81 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            6 |     3779 | 2024-03-08 | Entropiq          | W   | 0.192      | -            | -                | -                | -         |     0.28 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            5 |     3798 | 2024-03-07 | AURA              | W   | 0.187      | -            | -                | -                | -         |     0.19 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            4 |     3834 | 2024-03-06 | Permitta          | L   | 0.179      | -            | -                | -                | -         |    -3.68 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            3 |     3838 | 2024-03-06 | Fraud5            | W   | 0.178      | -            | -                | -                | -         |     0.42 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            2 |     3863 | 2024-03-05 | B8                | L   | 0.174      | -            | -                | -                | -         |    -2.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            1 |     3892 | 2024-03-04 | ALTERNATE aTTaX   | W   | 0.165      | -            | -                | -                | -         |     1.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,436.66)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-25 |      1.000 | $11,000.00     | $11,000.00      |
| 2024-07-22 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-06 |      0.791 | $11,000.00     | $8,700.69       |
| 2024-05-03 |      0.566 | $12,500.00     | $7,078.13       |
| 2024-03-31 |      0.346 | $657.00        | $227.21         |
| 2024-03-30 |      0.339 | $1,000.00      | $338.75         |
| 2024-03-18 |      0.258 | $3,000.00      | $773.75         |
| 2024-03-11 |      0.212 | $1,500.00      | $318.13         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
