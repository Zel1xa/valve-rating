### Roster Details<br />
Team Name: Passion UA<br />
Roster: fear, jackasmo, jambo, s-chilla, zeRRoFIX<br />
Global Rank: [47](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [34]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1094.8<br />
<br />
Final Rank Value (1094.8) = Starting Rank Value (1096.2) + Head To Head Adjustments (-1.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.567[<sup>1</sup>](#table2)
- Bounty Collected: 0.462[<sup>2</sup>](#table1)
- Opponent Network: 0.328[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.339<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1096.2
- 400 + ( ( 0.339 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1096.2


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
|           93 |       75 | 2024-08-03 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -8.63 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           92 |      153 | 2024-08-01 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           91 |      234 | 2024-07-30 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.21 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           90 |      269 | 2024-07-29 | Nexus             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.66 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           89 |      281 | 2024-07-29 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -27.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           88 |      323 | 2024-07-27 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -12.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           87 |      345 | 2024-07-26 | Gaimin Gladiators | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           86 |      364 | 2024-07-26 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.21 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           85 |      385 | 2024-07-25 | EYEBALLERS        | L   | 1.000      | -            | -                | -                | -         |   -26.81 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           84 |      403 | 2024-07-25 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.30 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           83 |      468 | 2024-07-23 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.85 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           82 |      490 | 2024-07-22 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.43 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           81 |      496 | 2024-07-22 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.63 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           80 |      516 | 2024-07-21 | Zero Tenacity     | W   | 1.000      | 0.500        | 0.143 (0.071)    | 1.000 (0.500)    | 0 (0.000) |    17.00 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           79 |      551 | 2024-07-20 | Ninjas in Pyjamas | W   | 1.000      | 0.500        | 0.254 (0.127)    | 0.544 (0.272)    | 0 (0.000) |    29.70 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           78 |      564 | 2024-07-20 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | -                | -         |     8.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           77 |      593 | 2024-07-19 | Nemiga            | W   | 1.000      | 0.500        | 0.315 (0.158)    | 0.721 (0.360)    | -         |    20.99 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           76 |      650 | 2024-07-18 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.122 (0.045)    | 1.000 (0.371)    | -         |    23.51 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           75 |      661 | 2024-07-18 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -23.59 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           74 |      717 | 2024-07-17 | Aurora Young Blud | W   | 1.000      | 0.500        | -                | 0.532 (0.266)    | -         |    10.58 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           73 |      778 | 2024-07-16 | Permitta          | W   | 1.000      | 0.371        | -                | 0.901 (0.334)    | -         |    11.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           72 |      800 | 2024-07-15 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -9.47 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           71 |      820 | 2024-07-15 | WOPA              | W   | 1.000      | -            | -                | -                | -         |     1.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           70 |      838 | 2024-07-14 | Preasy            | W   | 1.000      | -            | -                | -                | -         |     2.14 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           69 |      902 | 2024-07-10 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -18.69 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           68 |      920 | 2024-07-09 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.68 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           67 |      922 | 2024-07-09 | Insilio           | W   | 1.000      | -            | -                | -                | -         |    11.45 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           66 |      942 | 2024-07-08 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.61 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           65 |     1116 | 2024-06-14 | 3DMAX             | L   | 0.849      | -            | -                | -                | -         |    -3.08 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           64 |     1208 | 2024-06-10 | Space             | W   | 0.824      | -            | -                | -                | -         |     6.55 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           63 |     1320 | 2024-06-08 | Zero Tenacity     | L   | 0.811      | -            | -                | -                | -         |   -11.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           62 |     1382 | 2024-06-07 | Rare Atom         | W   | 0.804      | -            | -                | -                | -         |     5.26 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           61 |     1395 | 2024-06-07 | Aurora Young Blud | W   | 0.802      | -            | -                | -                | -         |     6.49 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           60 |     1466 | 2024-06-06 | Serbia            | W   | 0.795      | -            | -                | -                | -         |     5.08 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           59 |     1518 | 2024-06-05 | EYEBALLERS        | L   | 0.789      | -            | -                | -                | -         |   -19.04 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           58 |     1548 | 2024-06-04 | Illuminar         | W   | 0.784      | -            | -                | -                | -         |     4.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           57 |     1557 | 2024-06-04 | Serbia            | W   | 0.783      | -            | -                | -                | -         |     4.54 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           56 |     1606 | 2024-06-02 | UNiTY             | W   | 0.769      | -            | -                | -                | -         |     8.82 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           55 |     1667 | 2024-05-31 | Zero Tenacity     | L   | 0.756      | -            | -                | -                | -         |   -10.67 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           54 |     1688 | 2024-05-30 | Zero Tenacity     | W   | 0.750      | 0.371        | 0.143 (0.040)    | 1.000 (0.278)    | -         |    13.31 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           53 |     1717 | 2024-05-29 | Illuminar         | W   | 0.742      | -            | -                | -                | -         |     5.66 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           52 |     1788 | 2024-05-25 | Sampi             | W   | 0.717      | 0.435        | -                | 1.000 (0.312)    | -         |     7.25 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           51 |     1809 | 2024-05-24 | FURIA             | L   | 0.710      | -            | -                | -                | -         |    -0.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           50 |     1815 | 2024-05-24 | ECSTATIC          | W   | 0.709      | -            | -                | -                | -         |     1.29 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           49 |     1829 | 2024-05-23 | SINNERS           | W   | 0.702      | -            | -                | -                | -         |    12.26 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           48 |     1953 | 2024-05-20 | Permitta          | W   | 0.682      | 0.435        | -                | 0.901 (0.267)    | -         |     6.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           47 |     1965 | 2024-05-19 | Sashi             | L   | 0.677      | -            | -                | -                | -         |    -5.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           46 |     1976 | 2024-05-19 | ALTERNATE aTTaX   | W   | 0.676      | -            | -                | -                | -         |     7.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           45 |     1996 | 2024-05-18 | 9 Pandas          | L   | 0.671      | -            | -                | -                | -         |   -10.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           44 |     2039 | 2024-05-17 | Nexus             | W   | 0.663      | -            | -                | -                | -         |     4.33 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           43 |     2080 | 2024-05-16 | Sashi             | W   | 0.656      | 0.500        | 0.184 (0.060)    | 0.982 (0.322)    | -         |    15.35 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           42 |     2119 | 2024-05-15 | Endpoint          | L   | 0.650      | -            | -                | -                | -         |   -12.81 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           41 |     2173 | 2024-05-14 | SINNERS           | L   | 0.644      | -            | -                | -                | -         |    -9.00 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           40 |     2266 | 2024-05-11 | Preasy            | W   | 0.622      | -            | -                | -                | -         |     3.53 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           39 |     2430 | 2024-05-02 | Nemiga            | L   | 0.564      | -            | -                | -                | -         |    -5.71 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           38 |     2453 | 2024-05-01 | PARIVISION        | W   | 0.557      | -            | -                | -                | -         |    10.18 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           37 |     2490 | 2024-04-30 | 9 Pandas          | W   | 0.549      | -            | -                | -                | -         |     7.29 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           36 |     2517 | 2024-04-28 | ALTERNATE aTTaX   | L   | 0.537      | -            | -                | -                | -         |   -10.16 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           35 |     2567 | 2024-04-26 | 9 Pandas          | W   | 0.524      | -            | -                | -                | -         |     7.15 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           34 |     2568 | 2024-04-26 | 9 Pandas          | W   | 0.524      | -            | -                | -                | -         |     6.83 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           33 |     2604 | 2024-04-25 | Sashi             | L   | 0.516      | -            | -                | -                | -         |    -5.00 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           32 |     2619 | 2024-04-24 | Permitta          | L   | 0.510      | -            | -                | -                | -         |    -9.26 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           31 |     2648 | 2024-04-22 | B8                | L   | 0.498      | -            | -                | -                | -         |    -7.85 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           30 |     2689 | 2024-04-20 | Young Ninjas      | W   | 0.485      | -            | -                | -                | -         |     2.81 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           29 |     2711 | 2024-04-20 | Permitta          | L   | 0.482      | -            | -                | -                | -         |    -9.19 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           28 |     2745 | 2024-04-19 | ALTERNATE aTTaX   | L   | 0.477      | -            | -                | -                | -         |    -9.62 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           27 |     2802 | 2024-04-18 | Permitta          | W   | 0.470      | -            | -                | -                | -         |     5.74 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           26 |     2832 | 2024-04-17 | Sashi             | W   | 0.463      | 0.371        | 0.184 (0.032)    | -                | -         |     8.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           25 |     2866 | 2024-04-16 | 500               | L   | 0.458      | -            | -                | -                | -         |   -12.28 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           24 |     2905 | 2024-04-14 | SINNERS           | L   | 0.443      | -            | -                | -                | -         |    -4.77 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           23 |     2960 | 2024-04-11 | 3DMAX             | W   | 0.423      | 0.384        | 0.509 (0.083)    | -                | -         |    12.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           22 |     3008 | 2024-04-10 | Sashi             | W   | 0.416      | 0.371        | 0.184 (0.028)    | -                | -         |     8.24 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           21 |     3195 | 2024-04-04 | HAVU              | W   | 0.377      | -            | -                | -                | -         |     1.57 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           20 |     3266 | 2024-04-02 | BLEED             | L   | 0.364      | -            | -                | -                | -         |    -6.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           19 |     3295 | 2024-03-31 | FAVBET            | L   | 0.350      | -            | -                | -                | -         |    -9.12 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           18 |     3302 | 2024-03-30 | Lazer Cats        | W   | 0.343      | -            | -                | -                | -         |     0.57 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           17 |     3310 | 2024-03-29 | NAVI Junior       | L   | 0.336      | -            | -                | -                | -         |    -9.38 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           16 |     3329 | 2024-03-28 | GL Academy        | L   | 0.330      | -            | -                | -                | -         |    -9.01 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           15 |     3539 | 2024-03-17 | Sampi             | L   | 0.256      | -            | -                | -                | -         |    -5.84 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           14 |     3548 | 2024-03-16 | ex-Preasy         | L   | 0.250      | -            | -                | -                | -         |    -6.55 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           13 |     3601 | 2024-03-14 | Sampi             | W   | 0.236      | -            | -                | -                | -         |     1.95 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           12 |     3669 | 2024-03-12 | Alliance          | W   | 0.223      | -            | -                | -                | -         |     1.62 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           11 |     3691 | 2024-03-11 | MOUZ NXT          | L   | 0.216      | -            | -                | -                | -         |    -3.76 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           10 |     3711 | 2024-03-10 | MOUZ NXT          | W   | 0.210      | -            | -                | -                | -         |     3.00 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            9 |     3726 | 2024-03-09 | The Chosen Few    | L   | 0.204      | -            | -                | -                | -         |    -5.85 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            8 |     3751 | 2024-03-08 | Spirit Academy    | L   | 0.198      | -            | -                | -                | -         |    -5.94 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            7 |     3756 | 2024-03-08 | Entropiq          | W   | 0.196      | -            | -                | -                | -         |     0.29 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            6 |     3775 | 2024-03-07 | AURA              | W   | 0.191      | -            | -                | -                | -         |     0.20 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            5 |     3811 | 2024-03-06 | Permitta          | L   | 0.184      | -            | -                | -                | -         |    -3.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            4 |     3815 | 2024-03-06 | Fraud5            | W   | 0.183      | -            | -                | -                | -         |     0.44 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            3 |     3840 | 2024-03-05 | B8                | L   | 0.178      | -            | -                | -                | -         |    -2.94 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            2 |     3869 | 2024-03-04 | ALTERNATE aTTaX   | W   | 0.170      | -            | -                | -                | -         |     1.81 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            1 |     4402 | 2024-02-08 | BLEED             | L   | 0.003      | -            | -                | -                | -         |    -0.06 | jackasmo, jambo, marat2k, s-chilla, Zinchenko |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,564.35)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-25 |      1.000 | $11,000.00     | $11,000.00      |
| 2024-07-22 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-06 |      0.795 | $11,000.00     | $8,748.06       |
| 2024-05-03 |      0.571 | $12,500.00     | $7,131.94       |
| 2024-03-31 |      0.350 | $657.00        | $230.04         |
| 2024-03-30 |      0.343 | $1,000.00      | $343.06         |
| 2024-03-18 |      0.262 | $3,000.00      | $786.67         |
| 2024-03-11 |      0.216 | $1,500.00      | $324.58         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
