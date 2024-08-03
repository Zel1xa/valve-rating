### Roster Details<br />
Team Name: Passion UA<br />
Roster: fear, jackasmo, jambo, s-chilla, zeRRoFIX<br />
Global Rank: [46](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [34]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1076.5<br />
<br />
Final Rank Value (1076.5) = Starting Rank Value (1090.2) + Head To Head Adjustments (-13.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.567[<sup>1</sup>](#table2)
- Bounty Collected: 0.459[<sup>2</sup>](#table1)
- Opponent Network: 0.323[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.337<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1090.2
- 400 + ( ( 0.337 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1090.2


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
|           91 |       12 | 2024-08-03 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -9.20 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           90 |       68 | 2024-08-01 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.38 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           89 |      148 | 2024-07-30 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.68 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           88 |      183 | 2024-07-29 | Nexus             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.71 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           87 |      195 | 2024-07-29 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -27.60 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           86 |      237 | 2024-07-27 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -12.32 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           85 |      259 | 2024-07-26 | Gaimin Gladiators | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.54 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           84 |      278 | 2024-07-26 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.61 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           83 |      299 | 2024-07-25 | EYEBALLERS        | L   | 1.000      | -            | -                | -                | -         |   -26.35 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           82 |      317 | 2024-07-25 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.05 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           81 |      383 | 2024-07-23 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.63 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           80 |      404 | 2024-07-22 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -6.69 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           79 |      410 | 2024-07-22 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.27 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           78 |      430 | 2024-07-21 | Zero Tenacity     | W   | 1.000      | 0.500        | 0.137 (0.069)    | 1.000 (0.500)    | 0 (0.000) |    16.73 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           77 |      465 | 2024-07-20 | Ninjas in Pyjamas | W   | 1.000      | 0.500        | 0.204 (0.102)    | 0.502 (0.251)    | 0 (0.000) |    29.49 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           76 |      478 | 2024-07-20 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | -                | -         |     9.61 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           75 |      507 | 2024-07-19 | Nemiga            | W   | 1.000      | 0.500        | 0.318 (0.159)    | 0.719 (0.360)    | -         |    21.20 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           74 |      564 | 2024-07-18 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.122 (0.045)    | 0.930 (0.345)    | -         |    23.85 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           73 |      573 | 2024-07-18 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -23.00 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           72 |      689 | 2024-07-16 | Permitta          | W   | 1.000      | 0.371        | -                | 0.887 (0.328)    | -         |    11.66 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           71 |      711 | 2024-07-15 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -9.64 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           70 |      731 | 2024-07-15 | WOPA              | W   | 1.000      | -            | -                | -                | -         |     1.97 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           69 |      747 | 2024-07-14 | Preasy            | W   | 1.000      | -            | -                | -                | -         |     6.49 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           68 |      808 | 2024-07-10 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -18.83 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           67 |      826 | 2024-07-09 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.67 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           66 |      828 | 2024-07-09 | Insilio           | W   | 1.000      | -            | -                | -                | -         |    11.83 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           65 |      848 | 2024-07-08 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.59 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           64 |     1002 | 2024-06-14 | 3DMAX             | L   | 0.864      | -            | -                | -                | -         |    -3.20 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           63 |     1090 | 2024-06-10 | Space             | W   | 0.839      | -            | -                | -                | -         |     7.63 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           62 |     1198 | 2024-06-08 | Zero Tenacity     | L   | 0.826      | -            | -                | -                | -         |   -11.94 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           61 |     1258 | 2024-06-07 | Rare Atom         | W   | 0.819      | -            | -                | -                | -         |     3.06 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           60 |     1271 | 2024-06-07 | Aurora Young Blud | W   | 0.818      | -            | -                | -                | -         |     5.84 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           59 |     1342 | 2024-06-06 | Serbia            | W   | 0.811      | -            | -                | -                | -         |     5.45 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           58 |     1394 | 2024-06-05 | EYEBALLERS        | L   | 0.804      | -            | -                | -                | -         |   -19.08 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           57 |     1423 | 2024-06-04 | Illuminar         | W   | 0.799      | -            | -                | -                | -         |     5.18 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           56 |     1432 | 2024-06-04 | Serbia            | W   | 0.799      | -            | -                | -                | -         |     4.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           55 |     1480 | 2024-06-02 | UNiTY             | W   | 0.784      | -            | -                | -                | -         |     9.23 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           54 |     1540 | 2024-05-31 | Zero Tenacity     | L   | 0.772      | -            | -                | -                | -         |   -10.52 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           53 |     1561 | 2024-05-30 | Zero Tenacity     | W   | 0.766      | 0.371        | 0.137 (0.039)    | 1.000 (0.284)    | -         |    13.97 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           52 |     1590 | 2024-05-29 | Illuminar         | W   | 0.758      | -            | -                | -                | -         |     6.08 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           51 |     1660 | 2024-05-25 | Sampi             | W   | 0.733      | 0.435        | -                | 1.000 (0.318)    | -         |     7.83 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           50 |     1681 | 2024-05-24 | FURIA             | L   | 0.726      | -            | -                | -                | -         |    -0.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           49 |     1687 | 2024-05-24 | ECSTATIC          | W   | 0.724      | -            | -                | -                | -         |     0.63 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           48 |     1701 | 2024-05-23 | SINNERS           | W   | 0.718      | 0.435        | -                | 0.784 (0.245)    | -         |    11.73 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           47 |     1825 | 2024-05-20 | Permitta          | W   | 0.698      | 0.435        | -                | 0.887 (0.269)    | -         |     7.10 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           46 |     1836 | 2024-05-19 | Sashi             | L   | 0.693      | -            | -                | -                | -         |    -5.71 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           45 |     1847 | 2024-05-19 | ALTERNATE aTTaX   | W   | 0.691      | -            | -                | -                | -         |     8.40 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           44 |     1867 | 2024-05-18 | 9 Pandas          | L   | 0.686      | -            | -                | -                | -         |   -10.61 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           43 |     1910 | 2024-05-17 | Nexus             | W   | 0.678      | -            | -                | -                | -         |     4.71 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           42 |     1951 | 2024-05-16 | Sashi             | W   | 0.671      | 0.500        | 0.184 (0.062)    | 0.998 (0.335)    | -         |    16.08 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           41 |     1990 | 2024-05-15 | Endpoint          | L   | 0.666      | -            | -                | -                | -         |   -12.67 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           40 |     2044 | 2024-05-14 | SINNERS           | L   | 0.660      | -            | -                | -                | -         |    -9.99 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           39 |     2137 | 2024-05-11 | Preasy            | W   | 0.638      | -            | -                | -                | -         |     4.00 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           38 |     2300 | 2024-05-02 | Nemiga            | L   | 0.579      | -            | -                | -                | -         |    -5.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           37 |     2323 | 2024-05-01 | PARIVISION        | W   | 0.573      | -            | -                | -                | -         |    10.65 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           36 |     2360 | 2024-04-30 | 9 Pandas          | W   | 0.564      | -            | -                | -                | -         |     8.00 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           35 |     2387 | 2024-04-28 | ALTERNATE aTTaX   | L   | 0.553      | -            | -                | -                | -         |   -10.11 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           34 |     2437 | 2024-04-26 | 9 Pandas          | W   | 0.539      | -            | -                | -                | -         |     7.55 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           33 |     2473 | 2024-04-25 | Sashi             | L   | 0.532      | -            | -                | -                | -         |    -4.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           32 |     2488 | 2024-04-24 | Permitta          | L   | 0.526      | -            | -                | -                | -         |    -9.56 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           31 |     2517 | 2024-04-22 | B8                | L   | 0.514      | -            | -                | -                | -         |    -7.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           30 |     2558 | 2024-04-20 | Young Ninjas      | W   | 0.500      | -            | -                | -                | -         |     2.98 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           29 |     2580 | 2024-04-20 | Permitta          | L   | 0.498      | -            | -                | -                | -         |    -9.53 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           28 |     2614 | 2024-04-19 | ALTERNATE aTTaX   | L   | 0.493      | -            | -                | -                | -         |    -9.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           27 |     2671 | 2024-04-18 | Permitta          | W   | 0.485      | -            | -                | -                | -         |     5.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           26 |     2701 | 2024-04-17 | Sashi             | W   | 0.479      | 0.371        | 0.184 (0.033)    | -                | -         |     9.42 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           25 |     2735 | 2024-04-16 | 500               | L   | 0.473      | -            | -                | -                | -         |   -12.57 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           24 |     2774 | 2024-04-14 | SINNERS           | L   | 0.458      | -            | -                | -                | -         |    -5.76 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           23 |     2829 | 2024-04-11 | 3DMAX             | W   | 0.439      | 0.384        | 0.504 (0.085)    | -                | -         |    13.35 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           22 |     2877 | 2024-04-10 | Sashi             | W   | 0.432      | 0.371        | 0.184 (0.029)    | -                | -         |     8.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           21 |     3064 | 2024-04-04 | HAVU              | W   | 0.392      | -            | -                | -                | -         |     1.73 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           20 |     3135 | 2024-04-02 | BLEED             | L   | 0.380      | -            | -                | -                | -         |    -6.94 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           19 |     3164 | 2024-03-31 | FAVBET            | L   | 0.366      | -            | -                | -                | -         |    -9.45 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           18 |     3171 | 2024-03-30 | Lazer Cats        | W   | 0.358      | -            | -                | -                | -         |     0.63 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           17 |     3179 | 2024-03-29 | NAVI Junior       | L   | 0.352      | -            | -                | -                | -         |    -9.75 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           16 |     3198 | 2024-03-28 | GL Academy        | L   | 0.345      | -            | -                | -                | -         |    -9.37 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           15 |     3403 | 2024-03-17 | Sampi             | L   | 0.271      | -            | -                | -                | -         |    -6.09 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           14 |     3412 | 2024-03-16 | ex-Preasy         | L   | 0.266      | -            | -                | -                | -         |    -6.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           13 |     3464 | 2024-03-14 | Sampi             | W   | 0.252      | -            | -                | -                | -         |     2.18 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           12 |     3530 | 2024-03-12 | Alliance          | W   | 0.239      | -            | -                | -                | -         |     1.81 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           11 |     3552 | 2024-03-11 | MOUZ NXT          | L   | 0.232      | -            | -                | -                | -         |    -4.06 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           10 |     3572 | 2024-03-10 | MOUZ NXT          | W   | 0.226      | -            | -                | -                | -         |     3.20 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            9 |     3587 | 2024-03-09 | The Chosen Few    | L   | 0.220      | -            | -                | -                | -         |    -6.28 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            8 |     3612 | 2024-03-08 | Spirit Academy    | L   | 0.213      | -            | -                | -                | -         |    -6.39 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            7 |     3617 | 2024-03-08 | Entropiq          | W   | 0.212      | -            | -                | -                | -         |     0.33 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            6 |     3636 | 2024-03-07 | AURA              | W   | 0.207      | -            | -                | -                | -         |     0.23 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            5 |     3673 | 2024-03-06 | Permitta          | L   | 0.199      | -            | -                | -                | -         |    -4.29 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            4 |     3675 | 2024-03-06 | Fraud5            | W   | 0.198      | -            | -                | -                | -         |     0.49 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            3 |     3701 | 2024-03-05 | B8                | L   | 0.194      | -            | -                | -                | -         |    -3.12 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            2 |     3730 | 2024-03-04 | ALTERNATE aTTaX   | W   | 0.185      | -            | -                | -                | -         |     2.03 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            1 |     4262 | 2024-02-08 | BLEED             | L   | 0.018      | -            | -                | -                | -         |    -0.39 | jackasmo, jambo, marat2k, s-chilla, Zinchenko |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($56,027.05)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-25 |      1.000 | $11,000.00     | $11,000.00      |
| 2024-07-22 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-06 |      0.811 | $11,000.00     | $8,919.68       |
| 2024-05-03 |      0.586 | $12,500.00     | $7,326.97       |
| 2024-03-31 |      0.366 | $657.00        | $240.29         |
| 2024-03-30 |      0.359 | $1,000.00      | $358.66         |
| 2024-03-18 |      0.278 | $3,000.00      | $833.47         |
| 2024-03-11 |      0.232 | $1,500.00      | $347.99         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
