### Roster Details<br />
Team Name: Sampi<br />
Roster: fino, manguss, sAvana1, The eLiVe, ZEDKO<br />
Global Rank: [97](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [70]( ../standings_europe.md)<br />
<br />
Final Rank Value:  860.8<br />
<br />
Final Rank Value (860.8) = Starting Rank Value (886.1) + Head To Head Adjustments (-25.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.390[<sup>1</sup>](#table2)
- Bounty Collected: 0.375[<sup>2</sup>](#table1)
- Opponent Network: 0.186[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.238<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 886.1
- 400 + ( ( 0.238 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 886.1


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
|           93 |      121 | 2024-08-01 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -14.35 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           92 |      131 | 2024-08-01 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -16.53 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           91 |      161 | 2024-07-31 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -14.46 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           90 |      180 | 2024-07-31 | Illuminar         | L   | 1.000      | -            | -                | -                | -         |   -15.16 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           89 |      217 | 2024-07-30 | CYBERSHOKE        | W   | 1.000      | 0.426        | 0.039 (0.017)    | -                | 0 (0.000) |    17.15 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           88 |      228 | 2024-07-30 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.23 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           87 |      255 | 2024-07-29 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -14.52 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           86 |      276 | 2024-07-28 | CPH Wolves        | W   | 1.000      | 0.435        | -                | 0.365 (0.159)    | 0 (0.000) |    13.11 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           85 |      324 | 2024-07-26 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.522 (0.227)    | 0 (0.000) |    12.80 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           84 |      336 | 2024-07-26 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -1.32 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           83 |      406 | 2024-07-24 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -12.30 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           82 |      437 | 2024-07-23 | CPH Wolves        | W   | 1.000      | 0.435        | -                | 0.365 (0.159)    | 0 (0.000) |    13.90 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           81 |      477 | 2024-07-22 | INFINITE          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.47 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           80 |      488 | 2024-07-21 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.42 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           79 |      564 | 2024-07-19 | Metizport         | L   | 1.000      | -            | -                | -                | -         |   -18.43 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           78 |      612 | 2024-07-18 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -15.98 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           77 |      738 | 2024-07-16 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | 0.501 (0.218)    | 0 (0.000) |    15.14 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           76 |      753 | 2024-07-16 | Meteor            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.71 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           75 |      803 | 2024-07-14 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -15.77 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           74 |      807 | 2024-07-14 | Portugal          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.69 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           73 |      868 | 2024-07-10 | Hungary           | W   | 1.000      | -            | -                | -                | -         |    11.34 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           72 |      907 | 2024-07-08 | Austria           | W   | 1.000      | -            | -                | -                | -         |     1.92 | fino, M1key, MATYS, sAvana1, The eLiVe      |
|           71 |     1109 | 2024-06-13 | Rebels            | W   | 0.851      | 0.379        | 0.038 (0.012)    | 0.600 (0.193)    | -         |    18.08 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           70 |     1116 | 2024-06-13 | Sashi             | L   | 0.850      | -            | -                | -                | -         |    -3.52 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           69 |     1140 | 2024-06-12 | Enterprise        | L   | 0.844      | -            | -                | -                | -         |   -11.05 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           68 |     1159 | 2024-06-11 | Astralis Talent   | W   | 0.837      | -            | -                | -                | -         |     8.53 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           67 |     1169 | 2024-06-11 | Illuminar         | L   | 0.835      | -            | -                | -                | -         |   -12.48 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           66 |     1229 | 2024-06-09 | Aurora Young Blud | L   | 0.824      | -            | -                | -                | -         |   -14.58 | fino, manguss, sAvana1, The eLiVe, Verttzzz |
|           65 |     1298 | 2024-06-08 | MOUZ NXT          | L   | 0.817      | -            | -                | -                | -         |    -6.56 | fino, manguss, sAvana1, The eLiVe, Verttzzz |
|           64 |     1317 | 2024-06-08 | CYBERSHOKE        | L   | 0.816      | -            | -                | -                | -         |   -14.73 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           63 |     1419 | 2024-06-06 | Nemiga            | L   | 0.804      | -            | -                | -                | -         |    -6.13 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           62 |     1435 | 2024-06-06 | HAVU              | W   | 0.803      | -            | -                | -                | -         |     6.40 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           61 |     1478 | 2024-06-05 | NAVI Junior       | W   | 0.797      | -            | -                | -                | -         |     2.98 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           60 |     1515 | 2024-06-04 | INFINITE          | W   | 0.791      | -            | -                | -                | -         |     3.02 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           59 |     1535 | 2024-06-04 | DMS               | W   | 0.789      | 0.500        | -                | 0.446 (0.176)    | -         |    14.66 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           58 |     1559 | 2024-06-03 | Rare Atom         | W   | 0.782      | 0.435        | -                | 0.481 (0.163)    | -         |     5.88 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           57 |     1610 | 2024-06-01 | SINNERS           | L   | 0.770      | -            | -                | -                | -         |    -6.45 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           56 |     1631 | 2024-05-31 | ECLOT             | L   | 0.765      | -            | -                | -                | -         |    -5.05 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           55 |     1655 | 2024-05-30 | 3DMAX             | L   | 0.758      | -            | -                | -                | -         |    -0.63 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           54 |     1708 | 2024-05-28 | Enterprise        | L   | 0.744      | -            | -                | -                | -         |   -11.83 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           53 |     1711 | 2024-05-28 | Rhyno             | W   | 0.743      | 0.435        | 0.071 (0.023)    | -                | -         |    14.19 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           52 |     1746 | 2024-05-26 | SINNERS           | L   | 0.731      | -            | -                | -                | -         |    -6.64 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           51 |     1764 | 2024-05-25 | Passion UA        | L   | 0.724      | -            | -                | -                | -         |    -7.44 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           50 |     1795 | 2024-05-23 | GUN5              | W   | 0.711      | 0.435        | 0.073 (0.022)    | 0.570 (0.176)    | -         |    12.20 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           49 |     1830 | 2024-05-22 | VENI VIDI VICI    | W   | 0.705      | -            | -                | -                | -         |     1.24 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           48 |     1919 | 2024-05-20 | Illuminar         | W   | 0.691      | -            | -                | -                | -         |    10.95 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           47 |     1927 | 2024-05-20 | Verdant           | L   | 0.689      | -            | -                | -                | -         |   -10.47 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           46 |     1982 | 2024-05-18 | DMS               | L   | 0.676      | -            | -                | -                | -         |   -10.74 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           45 |     2045 | 2024-05-16 | MOUZ NXT          | L   | 0.664      | -            | -                | -                | -         |    -6.93 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           44 |     2053 | 2024-05-16 | B8                | L   | 0.662      | -            | -                | -                | -         |    -5.67 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           43 |     2181 | 2024-05-13 | Nexus             | W   | 0.643      | -            | -                | -                | -         |     6.97 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           42 |     2269 | 2024-05-09 | BLEED             | L   | 0.618      | -            | -                | -                | -         |    -6.17 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           41 |     2346 | 2024-05-05 | RUSH B            | W   | 0.591      | -            | -                | -                | -         |     8.01 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           40 |     2375 | 2024-05-04 | Endpoint          | L   | 0.582      | -            | -                | -                | -         |    -8.91 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           39 |     2407 | 2024-05-02 | Permitta          | W   | 0.571      | 0.435        | -                | 0.876 (0.217)    | -         |     9.32 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           38 |     2434 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.563      | -            | -                | -                | -         |    -7.57 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           37 |     2441 | 2024-05-01 | ENCE Academy      | W   | 0.562      | -            | -                | -                | -         |     4.12 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           36 |     2446 | 2024-04-30 | GL Academy        | W   | 0.558      | -            | -                | -                | -         |     4.98 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           35 |     2464 | 2024-04-30 | ALTERNATE aTTaX   | L   | 0.556      | -            | -                | -                | -         |    -7.69 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           34 |     2582 | 2024-04-25 | ECLOT             | L   | 0.522      | -            | -                | -                | -         |    -2.93 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           33 |     2601 | 2024-04-24 | Permitta          | W   | 0.515      | 0.371        | -                | 0.876 (0.167)    | -         |     9.23 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           32 |     2620 | 2024-04-23 | ECLOT             | L   | 0.509      | -            | -                | -                | -         |    -2.81 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           31 |     2656 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.495      | -            | -                | -                | -         |     8.62 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           30 |     2730 | 2024-04-19 | BLEED             | L   | 0.483      | -            | -                | -                | -         |    -5.57 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           29 |     2789 | 2024-04-18 | Permitta          | W   | 0.475      | -            | -                | -                | -         |     8.65 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           28 |     2811 | 2024-04-17 | NOM               | L   | 0.470      | -            | -                | -                | -         |   -13.18 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           27 |     2849 | 2024-04-16 | SAW               | W   | 0.463      | 0.384        | 0.105 (0.019)    | -                | -         |    11.87 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           26 |     2853 | 2024-04-16 | Secret            | W   | 0.462      | -            | -                | -                | -         |     1.73 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           25 |     2863 | 2024-04-15 | ENCE Academy      | L   | 0.457      | -            | -                | -                | -         |   -10.71 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           24 |     2898 | 2024-04-13 | BetBoom           | L   | 0.443      | -            | -                | -                | -         |    -0.83 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           23 |     2942 | 2024-04-11 | PGE Turow         | W   | 0.429      | -            | -                | -                | -         |     2.54 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           22 |     3115 | 2024-04-06 | Enterprise        | W   | 0.396      | -            | -                | -                | -         |     6.30 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           21 |     3221 | 2024-04-03 | Ninjas in Pyjamas | W   | 0.376      | 0.384        | 0.254 (0.037)    | -                | -         |    11.69 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           20 |     3343 | 2024-03-27 | B8                | L   | 0.331      | -            | -                | -                | -         |    -2.69 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           19 |     3484 | 2024-03-18 | ex-Preasy         | L   | 0.269      | -            | -                | -                | -         |    -5.41 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           18 |     3515 | 2024-03-17 | Passion UA        | W   | 0.262      | 0.371        | 0.172 (0.017)    | -                | -         |     5.94 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           17 |     3523 | 2024-03-16 | SINNERS           | L   | 0.257      | -            | -                | -                | -         |    -1.79 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           16 |     3526 | 2024-03-16 | MOUZ NXT          | W   | 0.256      | 0.371        | 0.139 (0.013)    | -                | -         |     5.52 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           15 |     3541 | 2024-03-15 | ECLOT             | L   | 0.250      | -            | -                | -                | -         |    -1.29 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           14 |     3547 | 2024-03-15 | Permitta          | W   | 0.249      | -            | -                | -                | -         |     4.70 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           13 |     3577 | 2024-03-14 | Passion UA        | L   | 0.243      | -            | -                | -                | -         |    -2.05 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           12 |     3647 | 2024-03-12 | MOUZ NXT          | W   | 0.229      | -            | -                | -                | -         |     5.06 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           11 |     3689 | 2024-03-10 | Sashi             | W   | 0.216      | 0.358        | 0.184 (0.014)    | -                | -         |     5.48 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           10 |     3715 | 2024-03-09 | Enterprise        | W   | 0.210      | -            | -                | -                | -         |     3.57 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            9 |     3800 | 2024-03-06 | AURA              | W   | 0.189      | -            | -                | -                | -         |     0.61 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            8 |     3846 | 2024-03-04 | Sangal            | L   | 0.176      | -            | -                | -                | -         |    -1.01 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            7 |     3900 | 2024-03-02 | Enterprise        | L   | 0.162      | -            | -                | -                | -         |    -2.32 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            6 |     3938 | 2024-02-28 | Sashi             | L   | 0.144      | -            | -                | -                | -         |    -0.84 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            5 |     4003 | 2024-02-25 | ECLOT             | L   | 0.122      | -            | -                | -                | -         |    -0.53 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            4 |     4049 | 2024-02-23 | Entropiq          | W   | 0.109      | -            | -                | -                | -         |     0.45 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            3 |     4091 | 2024-02-21 | Sashi             | L   | 0.096      | -            | -                | -                | -         |    -0.54 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            2 |     4195 | 2024-02-17 | Secret            | W   | 0.070      | -            | -                | -                | -         |     0.27 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            1 |     4342 | 2024-02-10 | Zero Tenacity     | W   | 0.024      | -            | -                | -                | -         |     0.59 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,811.63)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.852 | $3,268.00      | $2,782.94       |
| 2024-06-02 |      0.777 | $653.00        | $507.68         |
| 2024-05-18 |      0.678 | $1,000.00      | $677.78         |
| 2024-04-25 |      0.522 | $5,000.00      | $2,609.72       |
| 2024-04-14 |      0.450 | $1,600.00      | $720.00         |
| 2024-03-18 |      0.269 | $5,000.00      | $1,344.44       |
| 2024-03-17 |      0.265 | $639.00        | $169.07         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
