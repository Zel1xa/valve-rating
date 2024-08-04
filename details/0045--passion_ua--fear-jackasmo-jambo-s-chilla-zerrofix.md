### Roster Details<br />
Team Name: Passion UA<br />
Roster: fear, jackasmo, jambo, s-chilla, zeRRoFIX<br />
Global Rank: [45](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [33]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1090.8<br />
<br />
Final Rank Value (1090.8) = Starting Rank Value (1089.6) + Head To Head Adjustments (1.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.567[<sup>1</sup>](#table2)
- Bounty Collected: 0.462[<sup>2</sup>](#table1)
- Opponent Network: 0.320[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.337<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1089.6
- 400 + ( ( 0.337 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1089.6


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
|           93 |       25 | 2024-08-03 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -8.64 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           92 |      101 | 2024-08-01 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.96 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           91 |      182 | 2024-07-30 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.26 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           90 |      217 | 2024-07-29 | Nexus             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.70 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           89 |      229 | 2024-07-29 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -27.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           88 |      271 | 2024-07-27 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -12.62 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           87 |      293 | 2024-07-26 | Gaimin Gladiators | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.94 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           86 |      312 | 2024-07-26 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.27 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           85 |      333 | 2024-07-25 | EYEBALLERS        | L   | 1.000      | -            | -                | -                | -         |   -26.71 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           84 |      351 | 2024-07-25 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.41 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           83 |      416 | 2024-07-23 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.96 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           82 |      438 | 2024-07-22 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.36 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           81 |      444 | 2024-07-22 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.00 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           80 |      464 | 2024-07-21 | Zero Tenacity     | W   | 1.000      | 0.500        | 0.137 (0.068)    | 1.000 (0.500)    | 0 (0.000) |    17.15 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           79 |      499 | 2024-07-20 | Ninjas in Pyjamas | W   | 1.000      | 0.500        | 0.255 (0.127)    | 0.553 (0.277)    | 0 (0.000) |    29.74 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           78 |      512 | 2024-07-20 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | -                | -         |     8.93 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           77 |      541 | 2024-07-19 | Nemiga            | W   | 1.000      | 0.500        | 0.317 (0.159)    | 0.695 (0.347)    | -         |    20.75 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           76 |      598 | 2024-07-18 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.122 (0.045)    | 0.902 (0.334)    | -         |    23.48 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           75 |      610 | 2024-07-18 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -23.46 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           74 |      666 | 2024-07-17 | Aurora Young Blud | W   | 1.000      | -            | -                | -                | -         |    10.08 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           73 |      726 | 2024-07-16 | Permitta          | W   | 1.000      | 0.371        | -                | 0.876 (0.325)    | -         |    11.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           72 |      751 | 2024-07-15 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -9.72 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           71 |      769 | 2024-07-15 | WOPA              | W   | 1.000      | -            | -                | -                | -         |     1.94 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           70 |      786 | 2024-07-14 | Preasy            | W   | 1.000      | -            | -                | -                | -         |     6.38 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           69 |      850 | 2024-07-10 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -18.56 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           68 |      868 | 2024-07-09 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           67 |      870 | 2024-07-09 | Insilio           | W   | 1.000      | -            | -                | -                | -         |    11.68 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           66 |      890 | 2024-07-08 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.83 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           65 |     1064 | 2024-06-14 | 3DMAX             | L   | 0.859      | -            | -                | -                | -         |    -3.10 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           64 |     1156 | 2024-06-10 | Space             | W   | 0.834      | -            | -                | -                | -         |     7.05 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           63 |     1268 | 2024-06-08 | Zero Tenacity     | L   | 0.821      | -            | -                | -                | -         |   -11.70 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           62 |     1330 | 2024-06-07 | Rare Atom         | W   | 0.814      | -            | -                | -                | -         |     3.02 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           61 |     1343 | 2024-06-07 | Aurora Young Blud | W   | 0.812      | -            | -                | -                | -         |     6.15 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           60 |     1414 | 2024-06-06 | Serbia            | W   | 0.805      | -            | -                | -                | -         |     5.30 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           59 |     1466 | 2024-06-05 | EYEBALLERS        | L   | 0.799      | -            | -                | -                | -         |   -19.03 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           58 |     1496 | 2024-06-04 | Illuminar         | W   | 0.794      | -            | -                | -                | -         |     5.03 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           57 |     1505 | 2024-06-04 | Serbia            | W   | 0.793      | -            | -                | -                | -         |     4.75 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           56 |     1554 | 2024-06-02 | UNiTY             | W   | 0.779      | -            | -                | -                | -         |     9.01 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           55 |     1615 | 2024-05-31 | Zero Tenacity     | L   | 0.767      | -            | -                | -                | -         |   -10.52 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           54 |     1636 | 2024-05-30 | Zero Tenacity     | W   | 0.760      | 0.371        | 0.137 (0.039)    | 1.000 (0.282)    | -         |    13.80 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           53 |     1665 | 2024-05-29 | Illuminar         | W   | 0.752      | -            | -                | -                | -         |     5.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           52 |     1736 | 2024-05-25 | Sampi             | W   | 0.727      | 0.435        | -                | 1.000 (0.316)    | -         |     7.59 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           51 |     1757 | 2024-05-24 | FURIA             | L   | 0.720      | -            | -                | -                | -         |    -0.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           50 |     1763 | 2024-05-24 | ECSTATIC          | W   | 0.719      | -            | -                | -                | -         |     0.61 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           49 |     1777 | 2024-05-23 | SINNERS           | W   | 0.712      | 0.435        | -                | 0.757 (0.234)    | -         |    11.46 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           48 |     1901 | 2024-05-20 | Permitta          | W   | 0.692      | 0.435        | -                | 0.876 (0.264)    | -         |     6.92 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           47 |     1913 | 2024-05-19 | Sashi             | L   | 0.687      | -            | -                | -                | -         |    -5.83 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           46 |     1924 | 2024-05-19 | ALTERNATE aTTaX   | W   | 0.686      | -            | -                | -                | -         |     8.16 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           45 |     1944 | 2024-05-18 | 9 Pandas          | L   | 0.681      | -            | -                | -                | -         |   -10.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           44 |     1987 | 2024-05-17 | Nexus             | W   | 0.673      | -            | -                | -                | -         |     4.53 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           43 |     2028 | 2024-05-16 | Sashi             | W   | 0.666      | 0.500        | 0.184 (0.061)    | 0.962 (0.320)    | -         |    15.77 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           42 |     2067 | 2024-05-15 | Endpoint          | L   | 0.660      | -            | -                | -                | -         |   -12.81 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           41 |     2121 | 2024-05-14 | SINNERS           | L   | 0.655      | -            | -                | -                | -         |   -10.15 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           40 |     2214 | 2024-05-11 | Preasy            | W   | 0.632      | -            | -                | -                | -         |     3.83 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           39 |     2378 | 2024-05-02 | Nemiga            | L   | 0.574      | -            | -                | -                | -         |    -5.98 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           38 |     2401 | 2024-05-01 | PARIVISION        | W   | 0.567      | -            | -                | -                | -         |    10.38 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           37 |     2438 | 2024-04-30 | 9 Pandas          | W   | 0.559      | -            | -                | -                | -         |     7.63 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           36 |     2465 | 2024-04-28 | ALTERNATE aTTaX   | L   | 0.548      | -            | -                | -                | -         |   -10.21 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           35 |     2515 | 2024-04-26 | 9 Pandas          | W   | 0.534      | -            | -                | -                | -         |     7.52 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           34 |     2516 | 2024-04-26 | 9 Pandas          | W   | 0.534      | -            | -                | -                | -         |     7.17 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           33 |     2552 | 2024-04-25 | Sashi             | L   | 0.526      | -            | -                | -                | -         |    -4.94 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           32 |     2567 | 2024-04-24 | Permitta          | L   | 0.520      | -            | -                | -                | -         |    -9.49 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           31 |     2596 | 2024-04-22 | B8                | L   | 0.508      | -            | -                | -                | -         |    -7.83 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           30 |     2637 | 2024-04-20 | Young Ninjas      | W   | 0.495      | -            | -                | -                | -         |     2.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           29 |     2659 | 2024-04-20 | Permitta          | L   | 0.492      | -            | -                | -                | -         |    -9.45 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           28 |     2693 | 2024-04-19 | ALTERNATE aTTaX   | L   | 0.487      | -            | -                | -                | -         |    -9.69 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           27 |     2750 | 2024-04-18 | Permitta          | W   | 0.480      | -            | -                | -                | -         |     5.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           26 |     2780 | 2024-04-17 | Sashi             | W   | 0.473      | 0.371        | 0.184 (0.032)    | -                | -         |     9.18 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           25 |     2814 | 2024-04-16 | 500               | L   | 0.468      | -            | -                | -                | -         |   -12.45 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           24 |     2853 | 2024-04-14 | SINNERS           | L   | 0.453      | -            | -                | -                | -         |    -5.77 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           23 |     2908 | 2024-04-11 | 3DMAX             | W   | 0.433      | 0.384        | 0.506 (0.084)    | -                | -         |    13.19 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           22 |     2956 | 2024-04-10 | Sashi             | W   | 0.426      | 0.371        | 0.184 (0.029)    | -                | -         |     8.55 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           21 |     3143 | 2024-04-04 | HAVU              | W   | 0.387      | -            | -                | -                | -         |     1.69 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           20 |     3214 | 2024-04-02 | BLEED             | L   | 0.374      | -            | -                | -                | -         |    -6.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           19 |     3243 | 2024-03-31 | FAVBET            | L   | 0.360      | -            | -                | -                | -         |    -9.32 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           18 |     3250 | 2024-03-30 | Lazer Cats        | W   | 0.353      | -            | -                | -                | -         |     0.62 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           17 |     3258 | 2024-03-29 | NAVI Junior       | L   | 0.347      | -            | -                | -                | -         |    -9.60 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           16 |     3277 | 2024-03-28 | GL Academy        | L   | 0.340      | -            | -                | -                | -         |    -9.23 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           15 |     3487 | 2024-03-17 | Sampi             | L   | 0.266      | -            | -                | -                | -         |    -6.00 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           14 |     3496 | 2024-03-16 | ex-Preasy         | L   | 0.260      | -            | -                | -                | -         |    -6.74 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           13 |     3549 | 2024-03-14 | Sampi             | W   | 0.247      | -            | -                | -                | -         |     2.10 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           12 |     3617 | 2024-03-12 | Alliance          | W   | 0.233      | -            | -                | -                | -         |     1.75 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           11 |     3639 | 2024-03-11 | MOUZ NXT          | L   | 0.227      | -            | -                | -                | -         |    -3.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           10 |     3659 | 2024-03-10 | MOUZ NXT          | W   | 0.220      | -            | -                | -                | -         |     3.19 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            9 |     3674 | 2024-03-09 | The Chosen Few    | L   | 0.214      | -            | -                | -                | -         |    -6.12 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            8 |     3699 | 2024-03-08 | Spirit Academy    | L   | 0.208      | -            | -                | -                | -         |    -6.23 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            7 |     3704 | 2024-03-08 | Entropiq          | W   | 0.206      | -            | -                | -                | -         |     0.32 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            6 |     3723 | 2024-03-07 | AURA              | W   | 0.201      | -            | -                | -                | -         |     0.23 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            5 |     3759 | 2024-03-06 | Permitta          | L   | 0.194      | -            | -                | -                | -         |    -4.18 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            4 |     3763 | 2024-03-06 | Fraud5            | W   | 0.193      | -            | -                | -                | -         |     0.48 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            3 |     3788 | 2024-03-05 | B8                | L   | 0.188      | -            | -                | -                | -         |    -3.06 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            2 |     3817 | 2024-03-04 | ALTERNATE aTTaX   | W   | 0.180      | -            | -                | -                | -         |     1.97 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            1 |     4350 | 2024-02-08 | BLEED             | L   | 0.013      | -            | -                | -                | -         |    -0.28 | jackasmo, jambo, marat2k, s-chilla, Zinchenko |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,864.35)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-25 |      1.000 | $11,000.00     | $11,000.00      |
| 2024-07-22 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-06 |      0.805 | $11,000.00     | $8,859.33       |
| 2024-05-03 |      0.581 | $12,500.00     | $7,258.39       |
| 2024-03-31 |      0.360 | $657.00        | $236.69         |
| 2024-03-30 |      0.353 | $1,000.00      | $353.17         |
| 2024-03-18 |      0.272 | $3,000.00      | $817.01         |
| 2024-03-11 |      0.227 | $1,500.00      | $339.76         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
