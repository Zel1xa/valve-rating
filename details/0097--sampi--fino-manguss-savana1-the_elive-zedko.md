### Roster Details<br />
Team Name: Sampi<br />
Roster: fino, manguss, sAvana1, The eLiVe, ZEDKO<br />
Global Rank: [97](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [70]( ../standings_europe.md)<br />
<br />
Final Rank Value:  860.9<br />
<br />
Final Rank Value (860.9) = Starting Rank Value (886.3) + Head To Head Adjustments (-25.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.390[<sup>1</sup>](#table2)
- Bounty Collected: 0.375[<sup>2</sup>](#table1)
- Opponent Network: 0.186[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.238<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 886.3
- 400 + ( ( 0.238 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 886.3


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
|           93 |      117 | 2024-08-01 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -14.35 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           92 |      127 | 2024-08-01 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -16.53 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           91 |      157 | 2024-07-31 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -14.46 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           90 |      175 | 2024-07-31 | Illuminar         | L   | 1.000      | -            | -                | -                | -         |   -15.16 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           89 |      213 | 2024-07-30 | CYBERSHOKE        | W   | 1.000      | 0.426        | 0.039 (0.017)    | -                | 0 (0.000) |    17.15 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           88 |      224 | 2024-07-30 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.23 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           87 |      250 | 2024-07-29 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -14.52 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           86 |      272 | 2024-07-28 | CPH Wolves        | W   | 1.000      | 0.435        | -                | 0.365 (0.158)    | 0 (0.000) |    13.10 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           85 |      320 | 2024-07-26 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.522 (0.227)    | 0 (0.000) |    12.80 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           84 |      332 | 2024-07-26 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -1.32 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           83 |      402 | 2024-07-24 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -12.31 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           82 |      433 | 2024-07-23 | CPH Wolves        | W   | 1.000      | 0.435        | -                | 0.365 (0.158)    | 0 (0.000) |    13.89 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           81 |      473 | 2024-07-22 | INFINITE          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.46 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           80 |      484 | 2024-07-21 | WOPA              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.41 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           79 |      560 | 2024-07-19 | Metizport         | L   | 1.000      | -            | -                | -                | -         |   -18.43 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           78 |      608 | 2024-07-18 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -15.98 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           77 |      734 | 2024-07-16 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | 0.501 (0.218)    | 0 (0.000) |    15.14 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           76 |      749 | 2024-07-16 | Meteor            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.71 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           75 |      799 | 2024-07-14 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -15.78 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           74 |      803 | 2024-07-14 | Portugal          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.70 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           73 |      864 | 2024-07-10 | Hungary           | W   | 1.000      | -            | -                | -                | -         |    11.33 | fino, M1key, sAvana1, T4gg3D, The eLiVe     |
|           72 |      903 | 2024-07-08 | Austria           | W   | 1.000      | -            | -                | -                | -         |     1.92 | fino, M1key, MATYS, sAvana1, The eLiVe      |
|           71 |     1105 | 2024-06-13 | Rebels            | W   | 0.853      | 0.379        | 0.038 (0.012)    | 0.600 (0.194)    | -         |    18.14 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           70 |     1112 | 2024-06-13 | Sashi             | L   | 0.852      | -            | -                | -                | -         |    -3.53 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           69 |     1136 | 2024-06-12 | Enterprise        | L   | 0.846      | -            | -                | -                | -         |   -11.07 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           68 |     1155 | 2024-06-11 | Astralis Talent   | W   | 0.840      | -            | -                | -                | -         |     8.55 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           67 |     1165 | 2024-06-11 | Illuminar         | L   | 0.838      | -            | -                | -                | -         |   -12.51 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           66 |     1225 | 2024-06-09 | Aurora Young Blud | L   | 0.826      | -            | -                | -                | -         |   -14.63 | fino, manguss, sAvana1, The eLiVe, Verttzzz |
|           65 |     1294 | 2024-06-08 | MOUZ NXT          | L   | 0.820      | -            | -                | -                | -         |    -6.58 | fino, manguss, sAvana1, The eLiVe, Verttzzz |
|           64 |     1313 | 2024-06-08 | CYBERSHOKE        | L   | 0.818      | -            | -                | -                | -         |   -14.79 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           63 |     1415 | 2024-06-06 | Nemiga            | L   | 0.806      | -            | -                | -                | -         |    -6.14 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           62 |     1431 | 2024-06-06 | HAVU              | W   | 0.805      | -            | -                | -                | -         |     6.42 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           61 |     1474 | 2024-06-05 | NAVI Junior       | W   | 0.800      | -            | -                | -                | -         |     2.98 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           60 |     1511 | 2024-06-04 | INFINITE          | W   | 0.794      | -            | -                | -                | -         |     3.02 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           59 |     1531 | 2024-06-04 | DMS               | W   | 0.791      | 0.500        | -                | 0.446 (0.176)    | -         |    14.70 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           58 |     1555 | 2024-06-03 | Rare Atom         | W   | 0.784      | 0.435        | -                | 0.480 (0.164)    | -         |     5.89 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           57 |     1606 | 2024-06-01 | SINNERS           | L   | 0.772      | -            | -                | -                | -         |    -6.47 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           56 |     1627 | 2024-05-31 | ECLOT             | L   | 0.767      | -            | -                | -                | -         |    -5.07 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           55 |     1651 | 2024-05-30 | 3DMAX             | L   | 0.760      | -            | -                | -                | -         |    -0.64 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           54 |     1704 | 2024-05-28 | Enterprise        | L   | 0.746      | -            | -                | -                | -         |   -11.87 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           53 |     1707 | 2024-05-28 | Rhyno             | W   | 0.745      | 0.435        | 0.071 (0.023)    | -                | -         |    14.23 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           52 |     1742 | 2024-05-26 | SINNERS           | L   | 0.733      | -            | -                | -                | -         |    -6.67 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           51 |     1760 | 2024-05-25 | Passion UA        | L   | 0.726      | -            | -                | -                | -         |    -7.48 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           50 |     1791 | 2024-05-23 | GUN5              | W   | 0.714      | 0.435        | 0.073 (0.023)    | 0.570 (0.177)    | -         |    12.23 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           49 |     1826 | 2024-05-22 | VENI VIDI VICI    | W   | 0.707      | -            | -                | -                | -         |     1.24 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           48 |     1915 | 2024-05-20 | Illuminar         | W   | 0.693      | -            | -                | -                | -         |    10.98 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           47 |     1923 | 2024-05-20 | Verdant           | L   | 0.692      | -            | -                | -                | -         |   -10.52 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           46 |     1978 | 2024-05-18 | DMS               | L   | 0.678      | -            | -                | -                | -         |   -10.79 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           45 |     2041 | 2024-05-16 | MOUZ NXT          | L   | 0.666      | -            | -                | -                | -         |    -6.96 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           44 |     2049 | 2024-05-16 | B8                | L   | 0.665      | -            | -                | -                | -         |    -5.70 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           43 |     2177 | 2024-05-13 | Nexus             | W   | 0.645      | -            | -                | -                | -         |     6.98 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           42 |     2265 | 2024-05-09 | BLEED             | L   | 0.621      | -            | -                | -                | -         |    -6.18 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           41 |     2342 | 2024-05-05 | RUSH B            | W   | 0.593      | -            | -                | -                | -         |     8.04 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           40 |     2371 | 2024-05-04 | Endpoint          | L   | 0.585      | -            | -                | -                | -         |    -8.94 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           39 |     2403 | 2024-05-02 | Permitta          | W   | 0.573      | 0.435        | -                | 0.876 (0.218)    | -         |     9.35 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           38 |     2430 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.565      | -            | -                | -                | -         |    -7.61 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           37 |     2437 | 2024-05-01 | ENCE Academy      | W   | 0.565      | -            | -                | -                | -         |     4.13 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           36 |     2442 | 2024-04-30 | GL Academy        | W   | 0.561      | -            | -                | -                | -         |     5.00 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           35 |     2460 | 2024-04-30 | ALTERNATE aTTaX   | L   | 0.558      | -            | -                | -                | -         |    -7.72 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           34 |     2578 | 2024-04-25 | ECLOT             | L   | 0.524      | -            | -                | -                | -         |    -2.95 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           33 |     2597 | 2024-04-24 | Permitta          | W   | 0.518      | 0.371        | -                | 0.876 (0.168)    | -         |     9.27 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           32 |     2616 | 2024-04-23 | ECLOT             | L   | 0.511      | -            | -                | -                | -         |    -2.83 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           31 |     2652 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.498      | -            | -                | -                | -         |     8.66 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           30 |     2726 | 2024-04-19 | BLEED             | L   | 0.485      | -            | -                | -                | -         |    -5.58 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           29 |     2785 | 2024-04-18 | Permitta          | W   | 0.478      | -            | -                | -                | -         |     8.69 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           28 |     2807 | 2024-04-17 | NOM               | L   | 0.472      | -            | -                | -                | -         |   -13.25 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           27 |     2845 | 2024-04-16 | SAW               | W   | 0.465      | 0.384        | 0.105 (0.019)    | -                | -         |    11.94 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           26 |     2849 | 2024-04-16 | Secret            | W   | 0.464      | -            | -                | -                | -         |     1.74 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           25 |     2859 | 2024-04-15 | ENCE Academy      | L   | 0.459      | -            | -                | -                | -         |   -10.76 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           24 |     2894 | 2024-04-13 | BetBoom           | L   | 0.445      | -            | -                | -                | -         |    -0.84 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           23 |     2938 | 2024-04-11 | PGE Turow         | W   | 0.431      | -            | -                | -                | -         |     2.55 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           22 |     3111 | 2024-04-06 | Enterprise        | W   | 0.398      | -            | -                | -                | -         |     6.34 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           21 |     3217 | 2024-04-03 | Ninjas in Pyjamas | W   | 0.378      | 0.384        | 0.254 (0.037)    | -                | -         |    11.77 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           20 |     3339 | 2024-03-27 | B8                | L   | 0.334      | -            | -                | -                | -         |    -2.71 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           19 |     3480 | 2024-03-18 | ex-Preasy         | L   | 0.271      | -            | -                | -                | -         |    -5.45 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           18 |     3511 | 2024-03-17 | Passion UA        | W   | 0.265      | 0.371        | 0.172 (0.017)    | -                | -         |     5.99 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           17 |     3519 | 2024-03-16 | SINNERS           | L   | 0.259      | -            | -                | -                | -         |    -1.80 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           16 |     3522 | 2024-03-16 | MOUZ NXT          | W   | 0.258      | 0.371        | 0.139 (0.013)    | -                | -         |     5.57 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           15 |     3537 | 2024-03-15 | ECLOT             | L   | 0.253      | -            | -                | -                | -         |    -1.30 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           14 |     3543 | 2024-03-15 | Permitta          | W   | 0.251      | -            | -                | -                | -         |     4.74 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           13 |     3573 | 2024-03-14 | Passion UA        | L   | 0.246      | -            | -                | -                | -         |    -2.07 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           12 |     3643 | 2024-03-12 | MOUZ NXT          | W   | 0.231      | -            | -                | -                | -         |     5.12 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           11 |     3685 | 2024-03-10 | Sashi             | W   | 0.218      | 0.358        | 0.184 (0.014)    | -                | -         |     5.53 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|           10 |     3711 | 2024-03-09 | Enterprise        | W   | 0.212      | -            | -                | -                | -         |     3.61 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            9 |     3796 | 2024-03-06 | AURA              | W   | 0.191      | -            | -                | -                | -         |     0.62 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            8 |     3842 | 2024-03-04 | Sangal            | L   | 0.178      | -            | -                | -                | -         |    -1.03 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            7 |     3896 | 2024-03-02 | Enterprise        | L   | 0.165      | -            | -                | -                | -         |    -2.35 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            6 |     3934 | 2024-02-28 | Sashi             | L   | 0.146      | -            | -                | -                | -         |    -0.86 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            5 |     3999 | 2024-02-25 | ECLOT             | L   | 0.125      | -            | -                | -                | -         |    -0.54 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            4 |     4045 | 2024-02-23 | Entropiq          | W   | 0.111      | -            | -                | -                | -         |     0.46 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            3 |     4087 | 2024-02-21 | Sashi             | L   | 0.099      | -            | -                | -                | -         |    -0.55 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            2 |     4191 | 2024-02-17 | Secret            | W   | 0.072      | -            | -                | -                | -         |     0.28 | fino, manguss, sAvana1, The eLiVe, ZEDKO    |
|            1 |     4338 | 2024-02-10 | Zero Tenacity     | W   | 0.027      | -            | -                | -                | -         |     0.65 | fino, sAvana1, T4gg3D, The eLiVe, ZEDKO     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,852.55)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.854 | $3,268.00      | $2,790.74       |
| 2024-06-02 |      0.780 | $653.00        | $509.23         |
| 2024-05-18 |      0.680 | $1,000.00      | $680.16         |
| 2024-04-25 |      0.524 | $5,000.00      | $2,621.64       |
| 2024-04-14 |      0.452 | $1,600.00      | $723.81         |
| 2024-03-18 |      0.271 | $5,000.00      | $1,356.37       |
| 2024-03-17 |      0.267 | $639.00        | $170.59         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
