### Roster Details<br />
Team Name: Passion UA<br />
Roster: fear, jackasmo, jambo, s-chilla, zeRRoFIX<br />
Global Rank: [46](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [34]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1085.3<br />
<br />
Final Rank Value (1085.3) = Starting Rank Value (1088.5) + Head To Head Adjustments (-3.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.567[<sup>1</sup>](#table2)
- Bounty Collected: 0.460[<sup>2</sup>](#table1)
- Opponent Network: 0.321[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.337<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1088.5
- 400 + ( ( 0.337 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1088.5


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
|           92 |       14 | 2024-08-03 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -8.48 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           91 |       90 | 2024-08-01 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.09 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           90 |      171 | 2024-07-30 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.39 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           89 |      206 | 2024-07-29 | Nexus             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.82 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           88 |      218 | 2024-07-29 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -27.77 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           87 |      260 | 2024-07-27 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -12.52 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           86 |      282 | 2024-07-26 | Gaimin Gladiators | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.15 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           85 |      301 | 2024-07-26 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.36 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           84 |      322 | 2024-07-25 | EYEBALLERS        | L   | 1.000      | -            | -                | -                | -         |   -26.57 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           83 |      340 | 2024-07-25 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.63 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           82 |      405 | 2024-07-23 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.19 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           81 |      427 | 2024-07-22 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.24 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           80 |      433 | 2024-07-22 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.09 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           79 |      453 | 2024-07-21 | Zero Tenacity     | W   | 1.000      | 0.500        | 0.137 (0.069)    | 1.000 (0.500)    | 0 (0.000) |    17.27 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           78 |      488 | 2024-07-20 | Ninjas in Pyjamas | W   | 1.000      | 0.500        | 0.223 (0.111)    | 0.553 (0.277)    | 0 (0.000) |    29.68 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           77 |      501 | 2024-07-20 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | -                | -         |     9.04 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           76 |      530 | 2024-07-19 | Nemiga            | W   | 1.000      | 0.500        | 0.318 (0.159)    | 0.695 (0.348)    | -         |    20.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           75 |      587 | 2024-07-18 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.122 (0.045)    | 0.901 (0.334)    | -         |    23.59 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           74 |      599 | 2024-07-18 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -23.33 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           73 |      655 | 2024-07-17 | Aurora Young Blud | W   | 1.000      | -            | -                | -                | -         |     9.69 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           72 |      715 | 2024-07-16 | Permitta          | W   | 1.000      | 0.371        | -                | 0.876 (0.325)    | -         |    11.99 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           71 |      740 | 2024-07-15 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -9.60 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           70 |      758 | 2024-07-15 | WOPA              | W   | 1.000      | -            | -                | -                | -         |     1.98 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           69 |      775 | 2024-07-14 | Preasy            | W   | 1.000      | -            | -                | -                | -         |     6.47 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           68 |      838 | 2024-07-10 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -18.41 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           67 |      856 | 2024-07-09 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.74 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           66 |      858 | 2024-07-09 | Insilio           | W   | 1.000      | -            | -                | -                | -         |    11.80 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           65 |      878 | 2024-07-08 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.66 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           64 |     1052 | 2024-06-14 | 3DMAX             | L   | 0.863      | -            | -                | -                | -         |    -3.10 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           63 |     1144 | 2024-06-10 | Space             | W   | 0.838      | -            | -                | -                | -         |     7.24 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           62 |     1256 | 2024-06-08 | Zero Tenacity     | L   | 0.824      | -            | -                | -                | -         |   -11.61 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           61 |     1318 | 2024-06-07 | Rare Atom         | W   | 0.818      | -            | -                | -                | -         |     3.09 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           60 |     1331 | 2024-06-07 | Aurora Young Blud | W   | 0.816      | -            | -                | -                | -         |     5.82 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           59 |     1402 | 2024-06-06 | Serbia            | W   | 0.809      | -            | -                | -                | -         |     5.44 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           58 |     1454 | 2024-06-05 | EYEBALLERS        | L   | 0.803      | -            | -                | -                | -         |   -19.00 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           57 |     1484 | 2024-06-04 | Illuminar         | W   | 0.798      | -            | -                | -                | -         |     5.15 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           56 |     1493 | 2024-06-04 | Serbia            | W   | 0.797      | -            | -                | -                | -         |     4.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           55 |     1542 | 2024-06-02 | UNiTY             | W   | 0.782      | -            | -                | -                | -         |     9.22 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           54 |     1603 | 2024-05-31 | Zero Tenacity     | L   | 0.770      | -            | -                | -                | -         |   -10.40 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           53 |     1624 | 2024-05-30 | Zero Tenacity     | W   | 0.764      | 0.371        | 0.137 (0.039)    | 1.000 (0.283)    | -         |    14.04 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           52 |     1653 | 2024-05-29 | Illuminar         | W   | 0.756      | -            | -                | -                | -         |     6.04 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           51 |     1724 | 2024-05-25 | Sampi             | W   | 0.731      | 0.435        | -                | 1.000 (0.318)    | -         |     7.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           50 |     1745 | 2024-05-24 | FURIA             | L   | 0.724      | -            | -                | -                | -         |    -0.85 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           49 |     1751 | 2024-05-24 | ECSTATIC          | W   | 0.723      | -            | -                | -                | -         |     0.63 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           48 |     1765 | 2024-05-23 | SINNERS           | W   | 0.716      | 0.435        | -                | 0.758 (0.236)    | -         |    11.67 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           47 |     1889 | 2024-05-20 | Permitta          | W   | 0.696      | 0.435        | -                | 0.876 (0.265)    | -         |     7.09 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           46 |     1901 | 2024-05-19 | Sashi             | L   | 0.691      | -            | -                | -                | -         |    -5.74 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           45 |     1912 | 2024-05-19 | ALTERNATE aTTaX   | W   | 0.690      | -            | -                | -                | -         |     8.38 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           44 |     1932 | 2024-05-18 | 9 Pandas          | L   | 0.684      | -            | -                | -                | -         |   -10.47 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           43 |     1975 | 2024-05-17 | Nexus             | W   | 0.677      | -            | -                | -                | -         |     4.69 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           42 |     2016 | 2024-05-16 | Sashi             | W   | 0.669      | 0.500        | 0.184 (0.062)    | 0.964 (0.323)    | -         |    15.99 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           41 |     2055 | 2024-05-15 | Endpoint          | L   | 0.664      | -            | -                | -                | -         |   -12.67 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           40 |     2109 | 2024-05-14 | SINNERS           | L   | 0.658      | -            | -                | -                | -         |   -10.00 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           39 |     2202 | 2024-05-11 | Preasy            | W   | 0.636      | -            | -                | -                | -         |     3.98 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           38 |     2366 | 2024-05-02 | Nemiga            | L   | 0.578      | -            | -                | -                | -         |    -5.84 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           37 |     2389 | 2024-05-01 | PARIVISION        | W   | 0.571      | -            | -                | -                | -         |    10.64 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           36 |     2426 | 2024-04-30 | 9 Pandas          | W   | 0.563      | -            | -                | -                | -         |     8.05 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           35 |     2453 | 2024-04-28 | ALTERNATE aTTaX   | L   | 0.551      | -            | -                | -                | -         |   -10.08 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           34 |     2503 | 2024-04-26 | 9 Pandas          | W   | 0.538      | -            | -                | -                | -         |     7.60 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           33 |     2539 | 2024-04-25 | Sashi             | L   | 0.530      | -            | -                | -                | -         |    -4.97 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           32 |     2554 | 2024-04-24 | Permitta          | L   | 0.524      | -            | -                | -                | -         |    -9.52 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           31 |     2583 | 2024-04-22 | B8                | L   | 0.512      | -            | -                | -                | -         |    -7.85 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           30 |     2624 | 2024-04-20 | Young Ninjas      | W   | 0.499      | -            | -                | -                | -         |     2.97 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           29 |     2646 | 2024-04-20 | Permitta          | L   | 0.496      | -            | -                | -                | -         |    -9.49 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           28 |     2680 | 2024-04-19 | ALTERNATE aTTaX   | L   | 0.491      | -            | -                | -                | -         |    -9.74 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           27 |     2737 | 2024-04-18 | Permitta          | W   | 0.484      | -            | -                | -                | -         |     5.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           26 |     2767 | 2024-04-17 | Sashi             | W   | 0.477      | 0.371        | 0.184 (0.033)    | -                | -         |     9.24 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           25 |     2801 | 2024-04-16 | 500               | L   | 0.471      | -            | -                | -                | -         |   -12.52 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           24 |     2840 | 2024-04-14 | SINNERS           | L   | 0.457      | -            | -                | -                | -         |    -5.77 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           23 |     2895 | 2024-04-11 | 3DMAX             | W   | 0.437      | 0.384        | 0.505 (0.085)    | -                | -         |    13.30 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           22 |     2943 | 2024-04-10 | Sashi             | W   | 0.430      | 0.371        | 0.184 (0.029)    | -                | -         |     8.61 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           21 |     3130 | 2024-04-04 | HAVU              | W   | 0.391      | -            | -                | -                | -         |     1.72 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           20 |     3201 | 2024-04-02 | BLEED             | L   | 0.378      | -            | -                | -                | -         |    -6.92 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           19 |     3230 | 2024-03-31 | FAVBET            | L   | 0.364      | -            | -                | -                | -         |    -9.41 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           18 |     3237 | 2024-03-30 | Lazer Cats        | W   | 0.357      | -            | -                | -                | -         |     0.63 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           17 |     3245 | 2024-03-29 | NAVI Junior       | L   | 0.350      | -            | -                | -                | -         |    -9.70 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           16 |     3264 | 2024-03-28 | GL Academy        | L   | 0.344      | -            | -                | -                | -         |    -9.32 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           15 |     3474 | 2024-03-17 | Sampi             | L   | 0.269      | -            | -                | -                | -         |    -6.07 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           14 |     3483 | 2024-03-16 | ex-Preasy         | L   | 0.264      | -            | -                | -                | -         |    -6.81 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           13 |     3536 | 2024-03-14 | Sampi             | W   | 0.250      | -            | -                | -                | -         |     2.15 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           12 |     3603 | 2024-03-12 | Alliance          | W   | 0.237      | -            | -                | -                | -         |     1.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           11 |     3625 | 2024-03-11 | MOUZ NXT          | L   | 0.230      | -            | -                | -                | -         |    -3.95 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           10 |     3645 | 2024-03-10 | MOUZ NXT          | W   | 0.224      | -            | -                | -                | -         |     3.25 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            9 |     3660 | 2024-03-09 | The Chosen Few    | L   | 0.218      | -            | -                | -                | -         |    -6.22 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            8 |     3685 | 2024-03-08 | Spirit Academy    | L   | 0.211      | -            | -                | -                | -         |    -6.34 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            7 |     3690 | 2024-03-08 | Entropiq          | W   | 0.210      | -            | -                | -                | -         |     0.33 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            6 |     3709 | 2024-03-07 | AURA              | W   | 0.205      | -            | -                | -                | -         |     0.23 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            5 |     3745 | 2024-03-06 | Permitta          | L   | 0.198      | -            | -                | -                | -         |    -4.25 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            4 |     3749 | 2024-03-06 | Fraud5            | W   | 0.197      | -            | -                | -                | -         |     0.49 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            3 |     3774 | 2024-03-05 | B8                | L   | 0.192      | -            | -                | -                | -         |    -3.10 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            2 |     3803 | 2024-03-04 | ALTERNATE aTTaX   | W   | 0.184      | -            | -                | -                | -         |     2.02 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            1 |     4335 | 2024-02-08 | BLEED             | L   | 0.017      | -            | -                | -                | -         |    -0.35 | jackasmo, jambo, marat2k, s-chilla, Zinchenko |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,976.25)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-25 |      1.000 | $11,000.00     | $11,000.00      |
| 2024-07-22 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-06 |      0.809 | $11,000.00     | $8,900.83       |
| 2024-05-03 |      0.584 | $12,500.00     | $7,305.56       |
| 2024-03-31 |      0.364 | $657.00        | $239.17         |
| 2024-03-30 |      0.357 | $1,000.00      | $356.94         |
| 2024-03-18 |      0.276 | $3,000.00      | $828.33         |
| 2024-03-11 |      0.230 | $1,500.00      | $345.42         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
