### Roster Details<br />
Team Name: Passion UA<br />
Roster: fear, jackasmo, jambo, s-chilla, zeRRoFIX<br />
Global Rank: [46](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [33]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1092.6<br />
<br />
Final Rank Value (1092.6) = Starting Rank Value (1091.9) + Head To Head Adjustments (0.7)<br />

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
|           93 |       47 | 2024-08-03 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -8.62 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           92 |      125 | 2024-08-01 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           91 |      206 | 2024-07-30 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.22 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           90 |      241 | 2024-07-29 | Nexus             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.67 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           89 |      253 | 2024-07-29 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -27.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           88 |      295 | 2024-07-27 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -12.64 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           87 |      317 | 2024-07-26 | Gaimin Gladiators | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.95 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           86 |      336 | 2024-07-26 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.24 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           85 |      357 | 2024-07-25 | EYEBALLERS        | L   | 1.000      | -            | -                | -                | -         |   -26.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           84 |      375 | 2024-07-25 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.34 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           83 |      440 | 2024-07-23 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           82 |      462 | 2024-07-22 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.38 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           81 |      468 | 2024-07-22 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.62 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           80 |      488 | 2024-07-21 | Zero Tenacity     | W   | 1.000      | 0.500        | 0.137 (0.068)    | 1.000 (0.500)    | 0 (0.000) |    17.06 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           79 |      523 | 2024-07-20 | Ninjas in Pyjamas | W   | 1.000      | 0.500        | 0.254 (0.127)    | 0.553 (0.277)    | 0 (0.000) |    29.71 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           78 |      536 | 2024-07-20 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | -                | -         |     8.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           77 |      565 | 2024-07-19 | Nemiga            | W   | 1.000      | 0.500        | 0.317 (0.159)    | 0.734 (0.367)    | -         |    21.06 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           76 |      622 | 2024-07-18 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.122 (0.045)    | 0.941 (0.349)    | -         |    23.57 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           75 |      633 | 2024-07-18 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -23.53 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           74 |      689 | 2024-07-17 | Aurora Young Blud | W   | 1.000      | -            | -                | -                | -         |    10.00 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           73 |      750 | 2024-07-16 | Permitta          | W   | 1.000      | 0.371        | -                | 0.876 (0.325)    | -         |    11.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           72 |      772 | 2024-07-15 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -9.38 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           71 |      792 | 2024-07-15 | WOPA              | W   | 1.000      | -            | -                | -                | -         |     1.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           70 |      810 | 2024-07-14 | Preasy            | W   | 1.000      | -            | -                | -                | -         |     6.33 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           69 |      874 | 2024-07-10 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -18.62 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           68 |      892 | 2024-07-09 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.95 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           67 |      894 | 2024-07-09 | Insilio           | W   | 1.000      | -            | -                | -                | -         |    11.57 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           66 |      914 | 2024-07-08 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           65 |     1088 | 2024-06-14 | 3DMAX             | L   | 0.858      | -            | -                | -                | -         |    -3.12 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           64 |     1180 | 2024-06-10 | Space             | W   | 0.833      | -            | -                | -                | -         |     6.80 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           63 |     1292 | 2024-06-08 | Zero Tenacity     | L   | 0.820      | -            | -                | -                | -         |   -11.81 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           62 |     1354 | 2024-06-07 | Rare Atom         | W   | 0.813      | -            | -                | -                | -         |     2.93 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           61 |     1367 | 2024-06-07 | Aurora Young Blud | W   | 0.811      | -            | -                | -                | -         |     6.06 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           60 |     1438 | 2024-06-06 | Serbia            | W   | 0.804      | -            | -                | -                | -         |     5.22 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           59 |     1490 | 2024-06-05 | EYEBALLERS        | L   | 0.798      | -            | -                | -                | -         |   -19.19 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           58 |     1520 | 2024-06-04 | Illuminar         | W   | 0.793      | -            | -                | -                | -         |     4.96 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           57 |     1529 | 2024-06-04 | Serbia            | W   | 0.792      | -            | -                | -                | -         |     4.67 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           56 |     1578 | 2024-06-02 | UNiTY             | W   | 0.778      | -            | -                | -                | -         |     9.02 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           55 |     1639 | 2024-05-31 | Zero Tenacity     | L   | 0.765      | -            | -                | -                | -         |   -10.66 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           54 |     1660 | 2024-05-30 | Zero Tenacity     | W   | 0.759      | 0.371        | 0.137 (0.039)    | 1.000 (0.281)    | -         |    13.61 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           53 |     1689 | 2024-05-29 | Illuminar         | W   | 0.751      | -            | -                | -                | -         |     5.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           52 |     1760 | 2024-05-25 | Sampi             | W   | 0.726      | 0.435        | -                | 1.000 (0.316)    | -         |     7.48 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           51 |     1781 | 2024-05-24 | FURIA             | L   | 0.719      | -            | -                | -                | -         |    -0.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           50 |     1787 | 2024-05-24 | ECSTATIC          | W   | 0.718      | -            | -                | -                | -         |     0.59 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           49 |     1801 | 2024-05-23 | SINNERS           | W   | 0.711      | 0.435        | -                | 0.797 (0.246)    | -         |    12.38 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           48 |     1925 | 2024-05-20 | Permitta          | W   | 0.691      | 0.435        | -                | 0.876 (0.263)    | -         |     6.84 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           47 |     1937 | 2024-05-19 | Sashi             | L   | 0.686      | -            | -                | -                | -         |    -5.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           46 |     1948 | 2024-05-19 | ALTERNATE aTTaX   | W   | 0.685      | -            | -                | -                | -         |     8.10 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           45 |     1968 | 2024-05-18 | 9 Pandas          | L   | 0.680      | -            | -                | -                | -         |   -10.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           44 |     2011 | 2024-05-17 | Nexus             | W   | 0.672      | -            | -                | -                | -         |     4.45 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           43 |     2052 | 2024-05-16 | Sashi             | W   | 0.665      | 0.500        | 0.184 (0.061)    | 0.962 (0.320)    | -         |    15.68 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           42 |     2091 | 2024-05-15 | Endpoint          | L   | 0.659      | -            | -                | -                | -         |   -12.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           41 |     2145 | 2024-05-14 | SINNERS           | L   | 0.653      | -            | -                | -                | -         |    -9.14 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           40 |     2238 | 2024-05-11 | Preasy            | W   | 0.631      | -            | -                | -                | -         |     3.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           39 |     2402 | 2024-05-02 | Nemiga            | L   | 0.573      | -            | -                | -                | -         |    -5.66 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           38 |     2425 | 2024-05-01 | PARIVISION        | W   | 0.566      | -            | -                | -                | -         |    10.36 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           37 |     2462 | 2024-04-30 | 9 Pandas          | W   | 0.558      | -            | -                | -                | -         |     7.57 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           36 |     2489 | 2024-04-28 | ALTERNATE aTTaX   | L   | 0.546      | -            | -                | -                | -         |   -10.23 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           35 |     2539 | 2024-04-26 | 9 Pandas          | W   | 0.533      | -            | -                | -                | -         |     7.45 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           34 |     2540 | 2024-04-26 | 9 Pandas          | W   | 0.533      | -            | -                | -                | -         |     7.11 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           33 |     2576 | 2024-04-25 | Sashi             | L   | 0.525      | -            | -                | -                | -         |    -4.96 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           32 |     2591 | 2024-04-24 | Permitta          | L   | 0.519      | -            | -                | -                | -         |    -9.52 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           31 |     2620 | 2024-04-22 | B8                | L   | 0.507      | -            | -                | -                | -         |    -7.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           30 |     2661 | 2024-04-20 | Young Ninjas      | W   | 0.494      | -            | -                | -                | -         |     2.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           29 |     2683 | 2024-04-20 | Permitta          | L   | 0.491      | -            | -                | -                | -         |    -9.48 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           28 |     2717 | 2024-04-19 | ALTERNATE aTTaX   | L   | 0.486      | -            | -                | -                | -         |    -9.71 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           27 |     2774 | 2024-04-18 | Permitta          | W   | 0.479      | -            | -                | -                | -         |     5.72 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           26 |     2804 | 2024-04-17 | Sashi             | W   | 0.472      | 0.371        | 0.184 (0.032)    | -                | -         |     9.12 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           25 |     2838 | 2024-04-16 | 500               | L   | 0.467      | -            | -                | -                | -         |   -12.45 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           24 |     2877 | 2024-04-14 | SINNERS           | L   | 0.452      | -            | -                | -                | -         |    -4.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           23 |     2932 | 2024-04-11 | 3DMAX             | W   | 0.432      | 0.384        | 0.506 (0.084)    | -                | -         |    13.15 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           22 |     2980 | 2024-04-10 | Sashi             | W   | 0.425      | 0.371        | 0.184 (0.029)    | -                | -         |     8.50 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           21 |     3167 | 2024-04-04 | HAVU              | W   | 0.386      | -            | -                | -                | -         |     1.66 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           20 |     3238 | 2024-04-02 | BLEED             | L   | 0.373      | -            | -                | -                | -         |    -6.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           19 |     3267 | 2024-03-31 | FAVBET            | L   | 0.359      | -            | -                | -                | -         |    -9.31 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           18 |     3274 | 2024-03-30 | Lazer Cats        | W   | 0.352      | -            | -                | -                | -         |     0.61 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           17 |     3282 | 2024-03-29 | NAVI Junior       | L   | 0.345      | -            | -                | -                | -         |    -9.59 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           16 |     3301 | 2024-03-28 | GL Academy        | L   | 0.339      | -            | -                | -                | -         |    -9.22 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           15 |     3511 | 2024-03-17 | Sampi             | L   | 0.265      | -            | -                | -                | -         |    -5.99 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           14 |     3520 | 2024-03-16 | ex-Preasy         | L   | 0.259      | -            | -                | -                | -         |    -6.73 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           13 |     3573 | 2024-03-14 | Sampi             | W   | 0.246      | -            | -                | -                | -         |     2.07 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           12 |     3641 | 2024-03-12 | Alliance          | W   | 0.232      | -            | -                | -                | -         |     1.73 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           11 |     3663 | 2024-03-11 | MOUZ NXT          | L   | 0.225      | -            | -                | -                | -         |    -3.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           10 |     3683 | 2024-03-10 | MOUZ NXT          | W   | 0.219      | -            | -                | -                | -         |     3.15 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            9 |     3698 | 2024-03-09 | The Chosen Few    | L   | 0.213      | -            | -                | -                | -         |    -6.10 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            8 |     3723 | 2024-03-08 | Spirit Academy    | L   | 0.207      | -            | -                | -                | -         |    -6.20 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            7 |     3728 | 2024-03-08 | Entropiq          | W   | 0.205      | -            | -                | -                | -         |     0.31 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            6 |     3747 | 2024-03-07 | AURA              | W   | 0.200      | -            | -                | -                | -         |     0.22 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            5 |     3783 | 2024-03-06 | Permitta          | L   | 0.193      | -            | -                | -                | -         |    -4.17 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            4 |     3787 | 2024-03-06 | Fraud5            | W   | 0.192      | -            | -                | -                | -         |     0.47 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            3 |     3812 | 2024-03-05 | B8                | L   | 0.187      | -            | -                | -                | -         |    -3.05 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            2 |     3841 | 2024-03-04 | ALTERNATE aTTaX   | W   | 0.179      | -            | -                | -                | -         |     1.94 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            1 |     4374 | 2024-02-08 | BLEED             | L   | 0.012      | -            | -                | -                | -         |    -0.25 | jackasmo, jambo, marat2k, s-chilla, Zinchenko |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,832.77)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-25 |      1.000 | $11,000.00     | $11,000.00      |
| 2024-07-22 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-06 |      0.804 | $11,000.00     | $8,847.62       |
| 2024-05-03 |      0.580 | $12,500.00     | $7,245.08       |
| 2024-03-31 |      0.359 | $657.00        | $235.99         |
| 2024-03-30 |      0.352 | $1,000.00      | $352.11         |
| 2024-03-18 |      0.271 | $3,000.00      | $813.82         |
| 2024-03-11 |      0.225 | $1,500.00      | $338.16         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
