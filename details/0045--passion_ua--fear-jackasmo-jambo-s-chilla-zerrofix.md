### Roster Details<br />
Team Name: Passion UA<br />
Roster: fear, jackasmo, jambo, s-chilla, zeRRoFIX<br />
Global Rank: [45](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [32]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1092.5<br />
<br />
Final Rank Value (1092.5) = Starting Rank Value (1091.9) + Head To Head Adjustments (0.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.567[<sup>1</sup>](#table2)
- Bounty Collected: 0.462[<sup>2</sup>](#table1)
- Opponent Network: 0.324[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.338<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1091.9
- 400 + ( ( 0.338 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1091.9


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
|           93 |       51 | 2024-08-03 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -8.62 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           92 |      129 | 2024-08-01 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           91 |      210 | 2024-07-30 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.22 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           90 |      245 | 2024-07-29 | Nexus             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.67 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           89 |      257 | 2024-07-29 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -27.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           88 |      299 | 2024-07-27 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -12.67 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           87 |      321 | 2024-07-26 | Gaimin Gladiators | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.92 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           86 |      340 | 2024-07-26 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.25 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           85 |      361 | 2024-07-25 | EYEBALLERS        | L   | 1.000      | -            | -                | -                | -         |   -26.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           84 |      379 | 2024-07-25 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.35 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           83 |      444 | 2024-07-23 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           82 |      466 | 2024-07-22 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.38 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           81 |      472 | 2024-07-22 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.63 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           80 |      492 | 2024-07-21 | Zero Tenacity     | W   | 1.000      | 0.500        | 0.137 (0.068)    | 1.000 (0.500)    | 0 (0.000) |    17.06 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           79 |      527 | 2024-07-20 | Ninjas in Pyjamas | W   | 1.000      | 0.500        | 0.254 (0.127)    | 0.553 (0.277)    | 0 (0.000) |    29.72 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           78 |      540 | 2024-07-20 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | -                | -         |     8.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           77 |      569 | 2024-07-19 | Nemiga            | W   | 1.000      | 0.500        | 0.317 (0.158)    | 0.733 (0.367)    | -         |    21.05 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           76 |      626 | 2024-07-18 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.122 (0.045)    | 0.942 (0.349)    | -         |    23.57 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           75 |      637 | 2024-07-18 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -23.53 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           74 |      693 | 2024-07-17 | Aurora Young Blud | W   | 1.000      | -            | -                | -                | -         |     9.99 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           73 |      754 | 2024-07-16 | Permitta          | W   | 1.000      | 0.371        | -                | 0.876 (0.325)    | -         |    11.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           72 |      776 | 2024-07-15 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -9.39 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           71 |      796 | 2024-07-15 | WOPA              | W   | 1.000      | -            | -                | -                | -         |     1.92 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           70 |      814 | 2024-07-14 | Preasy            | W   | 1.000      | -            | -                | -                | -         |     6.33 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           69 |      878 | 2024-07-10 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -18.63 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           68 |      896 | 2024-07-09 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.93 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           67 |      898 | 2024-07-09 | Insilio           | W   | 1.000      | -            | -                | -                | -         |    11.55 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           66 |      918 | 2024-07-08 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           65 |     1092 | 2024-06-14 | 3DMAX             | L   | 0.855      | -            | -                | -                | -         |    -3.09 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           64 |     1184 | 2024-06-10 | Space             | W   | 0.830      | -            | -                | -                | -         |     6.77 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           63 |     1296 | 2024-06-08 | Zero Tenacity     | L   | 0.817      | -            | -                | -                | -         |   -11.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           62 |     1358 | 2024-06-07 | Rare Atom         | W   | 0.810      | -            | -                | -                | -         |     2.92 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           61 |     1371 | 2024-06-07 | Aurora Young Blud | W   | 0.809      | -            | -                | -                | -         |     6.04 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           60 |     1442 | 2024-06-06 | Serbia            | W   | 0.802      | -            | -                | -                | -         |     5.19 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           59 |     1494 | 2024-06-05 | EYEBALLERS        | L   | 0.796      | -            | -                | -                | -         |   -19.14 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           58 |     1524 | 2024-06-04 | Illuminar         | W   | 0.790      | -            | -                | -                | -         |     4.95 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           57 |     1533 | 2024-06-04 | Serbia            | W   | 0.790      | -            | -                | -                | -         |     4.65 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           56 |     1582 | 2024-06-02 | UNiTY             | W   | 0.775      | -            | -                | -                | -         |     8.98 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           55 |     1643 | 2024-05-31 | Zero Tenacity     | L   | 0.763      | -            | -                | -                | -         |   -10.64 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           54 |     1664 | 2024-05-30 | Zero Tenacity     | W   | 0.757      | 0.371        | 0.137 (0.038)    | 1.000 (0.280)    | -         |    13.56 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           53 |     1693 | 2024-05-29 | Illuminar         | W   | 0.749      | -            | -                | -                | -         |     5.77 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           52 |     1764 | 2024-05-25 | Sampi             | W   | 0.724      | 0.435        | -                | 1.000 (0.315)    | -         |     7.44 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           51 |     1785 | 2024-05-24 | FURIA             | L   | 0.717      | -            | -                | -                | -         |    -0.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           50 |     1791 | 2024-05-24 | ECSTATIC          | W   | 0.715      | -            | -                | -                | -         |     0.59 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           49 |     1805 | 2024-05-23 | SINNERS           | W   | 0.709      | 0.435        | -                | 0.797 (0.245)    | -         |    12.34 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           48 |     1929 | 2024-05-20 | Permitta          | W   | 0.689      | 0.435        | -                | 0.876 (0.262)    | -         |     6.82 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           47 |     1941 | 2024-05-19 | Sashi             | L   | 0.684      | -            | -                | -                | -         |    -5.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           46 |     1952 | 2024-05-19 | ALTERNATE aTTaX   | W   | 0.682      | -            | -                | -                | -         |     8.06 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           45 |     1972 | 2024-05-18 | 9 Pandas          | L   | 0.677      | -            | -                | -                | -         |   -10.85 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           44 |     2015 | 2024-05-17 | Nexus             | W   | 0.669      | -            | -                | -                | -         |     4.42 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           43 |     2056 | 2024-05-16 | Sashi             | W   | 0.662      | 0.500        | 0.184 (0.061)    | 0.961 (0.318)    | -         |    15.61 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           42 |     2095 | 2024-05-15 | Endpoint          | L   | 0.657      | -            | -                | -                | -         |   -12.83 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           41 |     2149 | 2024-05-14 | SINNERS           | L   | 0.651      | -            | -                | -                | -         |    -9.12 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           40 |     2242 | 2024-05-11 | Preasy            | W   | 0.629      | -            | -                | -                | -         |     3.76 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           39 |     2406 | 2024-05-02 | Nemiga            | L   | 0.571      | -            | -                | -                | -         |    -5.66 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           38 |     2429 | 2024-05-01 | PARIVISION        | W   | 0.564      | -            | -                | -                | -         |    10.31 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           37 |     2466 | 2024-04-30 | 9 Pandas          | W   | 0.556      | -            | -                | -                | -         |     7.51 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           36 |     2493 | 2024-04-28 | ALTERNATE aTTaX   | L   | 0.544      | -            | -                | -                | -         |   -10.20 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           35 |     2543 | 2024-04-26 | 9 Pandas          | W   | 0.531      | -            | -                | -                | -         |     7.39 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           34 |     2544 | 2024-04-26 | 9 Pandas          | W   | 0.531      | -            | -                | -                | -         |     7.05 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           33 |     2580 | 2024-04-25 | Sashi             | L   | 0.523      | -            | -                | -                | -         |    -4.95 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           32 |     2595 | 2024-04-24 | Permitta          | L   | 0.517      | -            | -                | -                | -         |    -9.49 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           31 |     2624 | 2024-04-22 | B8                | L   | 0.505      | -            | -                | -                | -         |    -7.85 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           30 |     2665 | 2024-04-20 | Young Ninjas      | W   | 0.491      | -            | -                | -                | -         |     2.83 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           29 |     2687 | 2024-04-20 | Permitta          | L   | 0.489      | -            | -                | -                | -         |    -9.45 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           28 |     2721 | 2024-04-19 | ALTERNATE aTTaX   | L   | 0.484      | -            | -                | -                | -         |    -9.67 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           27 |     2778 | 2024-04-18 | Permitta          | W   | 0.476      | -            | -                | -                | -         |     5.68 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           26 |     2808 | 2024-04-17 | Sashi             | W   | 0.470      | 0.371        | 0.184 (0.032)    | -                | -         |     9.07 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           25 |     2842 | 2024-04-16 | 500               | L   | 0.464      | -            | -                | -                | -         |   -12.40 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           24 |     2881 | 2024-04-14 | SINNERS           | L   | 0.450      | -            | -                | -                | -         |    -4.84 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           23 |     2936 | 2024-04-11 | 3DMAX             | W   | 0.430      | 0.384        | 0.507 (0.084)    | -                | -         |    13.08 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           22 |     2984 | 2024-04-10 | Sashi             | W   | 0.423      | 0.371        | 0.184 (0.029)    | -                | -         |     8.45 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           21 |     3171 | 2024-04-04 | HAVU              | W   | 0.383      | -            | -                | -                | -         |     1.65 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           20 |     3242 | 2024-04-02 | BLEED             | L   | 0.371      | -            | -                | -                | -         |    -6.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           19 |     3271 | 2024-03-31 | FAVBET            | L   | 0.357      | -            | -                | -                | -         |    -9.25 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           18 |     3278 | 2024-03-30 | Lazer Cats        | W   | 0.350      | -            | -                | -                | -         |     0.60 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           17 |     3286 | 2024-03-29 | NAVI Junior       | L   | 0.343      | -            | -                | -                | -         |    -9.53 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           16 |     3305 | 2024-03-28 | GL Academy        | L   | 0.336      | -            | -                | -                | -         |    -9.15 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           15 |     3515 | 2024-03-17 | Sampi             | L   | 0.262      | -            | -                | -                | -         |    -5.94 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           14 |     3524 | 2024-03-16 | ex-Preasy         | L   | 0.257      | -            | -                | -                | -         |    -6.68 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           13 |     3577 | 2024-03-14 | Sampi             | W   | 0.243      | -            | -                | -                | -         |     2.05 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           12 |     3645 | 2024-03-12 | Alliance          | W   | 0.230      | -            | -                | -                | -         |     1.70 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           11 |     3667 | 2024-03-11 | MOUZ NXT          | L   | 0.223      | -            | -                | -                | -         |    -3.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           10 |     3687 | 2024-03-10 | MOUZ NXT          | W   | 0.217      | -            | -                | -                | -         |     3.11 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            9 |     3702 | 2024-03-09 | The Chosen Few    | L   | 0.211      | -            | -                | -                | -         |    -6.03 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            8 |     3727 | 2024-03-08 | Spirit Academy    | L   | 0.204      | -            | -                | -                | -         |    -6.13 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            7 |     3732 | 2024-03-08 | Entropiq          | W   | 0.203      | -            | -                | -                | -         |     0.31 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            6 |     3751 | 2024-03-07 | AURA              | W   | 0.198      | -            | -                | -                | -         |     0.22 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            5 |     3787 | 2024-03-06 | Permitta          | L   | 0.190      | -            | -                | -                | -         |    -4.12 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            4 |     3791 | 2024-03-06 | Fraud5            | W   | 0.189      | -            | -                | -                | -         |     0.46 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            3 |     3816 | 2024-03-05 | B8                | L   | 0.185      | -            | -                | -                | -         |    -3.02 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            2 |     3845 | 2024-03-04 | ALTERNATE aTTaX   | W   | 0.176      | -            | -                | -                | -         |     1.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            1 |     4378 | 2024-02-08 | BLEED             | L   | 0.009      | -            | -                | -                | -         |    -0.20 | jackasmo, jambo, marat2k, s-chilla, Zinchenko |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,762.06)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-25 |      1.000 | $11,000.00     | $11,000.00      |
| 2024-07-22 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-06 |      0.802 | $11,000.00     | $8,821.39       |
| 2024-05-03 |      0.577 | $12,500.00     | $7,215.28       |
| 2024-03-31 |      0.357 | $657.00        | $234.42         |
| 2024-03-30 |      0.350 | $1,000.00      | $349.72         |
| 2024-03-18 |      0.269 | $3,000.00      | $806.67         |
| 2024-03-11 |      0.223 | $1,500.00      | $334.58         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
