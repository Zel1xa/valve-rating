### Roster Details<br />
Team Name: Passion UA<br />
Roster: fear, jackasmo, jambo, s-chilla, zeRRoFIX<br />
Global Rank: [46](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [33]( ../standings_europe.md)<br />
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
|           93 |       46 | 2024-08-03 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -8.64 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           92 |      124 | 2024-08-01 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           91 |      205 | 2024-07-30 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.22 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           90 |      240 | 2024-07-29 | Nexus             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.67 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           89 |      252 | 2024-07-29 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -27.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           88 |      294 | 2024-07-27 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -12.64 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           87 |      316 | 2024-07-26 | Gaimin Gladiators | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.95 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           86 |      335 | 2024-07-26 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.25 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           85 |      356 | 2024-07-25 | EYEBALLERS        | L   | 1.000      | -            | -                | -                | -         |   -26.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           84 |      374 | 2024-07-25 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.35 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           83 |      439 | 2024-07-23 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           82 |      461 | 2024-07-22 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.38 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           81 |      467 | 2024-07-22 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.62 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           80 |      487 | 2024-07-21 | Zero Tenacity     | W   | 1.000      | 0.500        | 0.137 (0.068)    | 1.000 (0.500)    | 0 (0.000) |    17.05 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           79 |      522 | 2024-07-20 | Ninjas in Pyjamas | W   | 1.000      | 0.500        | 0.255 (0.127)    | 0.553 (0.277)    | 0 (0.000) |    29.71 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           78 |      535 | 2024-07-20 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | -                | -         |     8.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           77 |      564 | 2024-07-19 | Nemiga            | W   | 1.000      | 0.500        | 0.317 (0.159)    | 0.734 (0.367)    | -         |    21.05 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           76 |      621 | 2024-07-18 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.122 (0.045)    | 0.941 (0.349)    | -         |    23.57 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           75 |      632 | 2024-07-18 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -23.53 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           74 |      688 | 2024-07-17 | Aurora Young Blud | W   | 1.000      | -            | -                | -                | -         |    10.00 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           73 |      749 | 2024-07-16 | Permitta          | W   | 1.000      | 0.371        | -                | 0.876 (0.325)    | -         |    11.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           72 |      771 | 2024-07-15 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -9.39 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           71 |      791 | 2024-07-15 | WOPA              | W   | 1.000      | -            | -                | -                | -         |     1.92 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           70 |      809 | 2024-07-14 | Preasy            | W   | 1.000      | -            | -                | -                | -         |     6.33 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           69 |      873 | 2024-07-10 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -18.62 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           68 |      891 | 2024-07-09 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.95 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           67 |      893 | 2024-07-09 | Insilio           | W   | 1.000      | -            | -                | -                | -         |    11.58 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           66 |      913 | 2024-07-08 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           65 |     1087 | 2024-06-14 | 3DMAX             | L   | 0.858      | -            | -                | -                | -         |    -3.12 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           64 |     1179 | 2024-06-10 | Space             | W   | 0.833      | -            | -                | -                | -         |     6.80 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           63 |     1291 | 2024-06-08 | Zero Tenacity     | L   | 0.820      | -            | -                | -                | -         |   -11.83 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           62 |     1353 | 2024-06-07 | Rare Atom         | W   | 0.813      | -            | -                | -                | -         |     2.94 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           61 |     1366 | 2024-06-07 | Aurora Young Blud | W   | 0.812      | -            | -                | -                | -         |     6.06 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           60 |     1437 | 2024-06-06 | Serbia            | W   | 0.805      | -            | -                | -                | -         |     5.22 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           59 |     1489 | 2024-06-05 | EYEBALLERS        | L   | 0.798      | -            | -                | -                | -         |   -19.20 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           58 |     1519 | 2024-06-04 | Illuminar         | W   | 0.793      | -            | -                | -                | -         |     4.97 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           57 |     1528 | 2024-06-04 | Serbia            | W   | 0.792      | -            | -                | -                | -         |     4.67 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           56 |     1577 | 2024-06-02 | UNiTY             | W   | 0.778      | -            | -                | -                | -         |     9.03 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           55 |     1638 | 2024-05-31 | Zero Tenacity     | L   | 0.766      | -            | -                | -                | -         |   -10.69 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           54 |     1659 | 2024-05-30 | Zero Tenacity     | W   | 0.760      | 0.371        | 0.137 (0.039)    | 1.000 (0.281)    | -         |    13.60 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           53 |     1688 | 2024-05-29 | Illuminar         | W   | 0.752      | -            | -                | -                | -         |     5.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           52 |     1759 | 2024-05-25 | Sampi             | W   | 0.727      | 0.435        | -                | 1.000 (0.316)    | -         |     7.48 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           51 |     1780 | 2024-05-24 | FURIA             | L   | 0.720      | -            | -                | -                | -         |    -0.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           50 |     1786 | 2024-05-24 | ECSTATIC          | W   | 0.718      | -            | -                | -                | -         |     0.60 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           49 |     1800 | 2024-05-23 | SINNERS           | W   | 0.712      | 0.435        | -                | 0.797 (0.246)    | -         |    12.38 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           48 |     1924 | 2024-05-20 | Permitta          | W   | 0.692      | 0.435        | -                | 0.876 (0.263)    | -         |     6.85 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           47 |     1936 | 2024-05-19 | Sashi             | L   | 0.687      | -            | -                | -                | -         |    -5.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           46 |     1947 | 2024-05-19 | ALTERNATE aTTaX   | W   | 0.685      | -            | -                | -                | -         |     8.10 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           45 |     1967 | 2024-05-18 | 9 Pandas          | L   | 0.680      | -            | -                | -                | -         |   -10.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           44 |     2010 | 2024-05-17 | Nexus             | W   | 0.672      | -            | -                | -                | -         |     4.45 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           43 |     2051 | 2024-05-16 | Sashi             | W   | 0.665      | 0.500        | 0.184 (0.061)    | 0.962 (0.320)    | -         |    15.69 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           42 |     2090 | 2024-05-15 | Endpoint          | L   | 0.660      | -            | -                | -                | -         |   -12.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           41 |     2144 | 2024-05-14 | SINNERS           | L   | 0.654      | -            | -                | -                | -         |    -9.16 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           40 |     2237 | 2024-05-11 | Preasy            | W   | 0.631      | -            | -                | -                | -         |     3.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           39 |     2401 | 2024-05-02 | Nemiga            | L   | 0.573      | -            | -                | -                | -         |    -5.67 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           38 |     2424 | 2024-05-01 | PARIVISION        | W   | 0.567      | -            | -                | -                | -         |    10.35 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           37 |     2461 | 2024-04-30 | 9 Pandas          | W   | 0.558      | -            | -                | -                | -         |     7.57 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           36 |     2488 | 2024-04-28 | ALTERNATE aTTaX   | L   | 0.547      | -            | -                | -                | -         |   -10.24 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           35 |     2538 | 2024-04-26 | 9 Pandas          | W   | 0.533      | -            | -                | -                | -         |     7.45 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           34 |     2539 | 2024-04-26 | 9 Pandas          | W   | 0.533      | -            | -                | -                | -         |     7.11 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           33 |     2575 | 2024-04-25 | Sashi             | L   | 0.525      | -            | -                | -                | -         |    -4.97 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           32 |     2590 | 2024-04-24 | Permitta          | L   | 0.520      | -            | -                | -                | -         |    -9.53 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           31 |     2619 | 2024-04-22 | B8                | L   | 0.507      | -            | -                | -                | -         |    -7.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           30 |     2660 | 2024-04-20 | Young Ninjas      | W   | 0.494      | -            | -                | -                | -         |     2.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           29 |     2682 | 2024-04-20 | Permitta          | L   | 0.491      | -            | -                | -                | -         |    -9.48 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           28 |     2716 | 2024-04-19 | ALTERNATE aTTaX   | L   | 0.486      | -            | -                | -                | -         |    -9.72 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           27 |     2773 | 2024-04-18 | Permitta          | W   | 0.479      | -            | -                | -                | -         |     5.73 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           26 |     2803 | 2024-04-17 | Sashi             | W   | 0.473      | 0.371        | 0.184 (0.032)    | -                | -         |     9.12 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           25 |     2837 | 2024-04-16 | 500               | L   | 0.467      | -            | -                | -                | -         |   -12.46 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           24 |     2876 | 2024-04-14 | SINNERS           | L   | 0.452      | -            | -                | -                | -         |    -4.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           23 |     2931 | 2024-04-11 | 3DMAX             | W   | 0.433      | 0.384        | 0.506 (0.084)    | -                | -         |    13.16 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           22 |     2979 | 2024-04-10 | Sashi             | W   | 0.425      | 0.371        | 0.184 (0.029)    | -                | -         |     8.51 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           21 |     3166 | 2024-04-04 | HAVU              | W   | 0.386      | -            | -                | -                | -         |     1.67 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           20 |     3237 | 2024-04-02 | BLEED             | L   | 0.373      | -            | -                | -                | -         |    -6.92 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           19 |     3266 | 2024-03-31 | FAVBET            | L   | 0.359      | -            | -                | -                | -         |    -9.32 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           18 |     3273 | 2024-03-30 | Lazer Cats        | W   | 0.352      | -            | -                | -                | -         |     0.61 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           17 |     3281 | 2024-03-29 | NAVI Junior       | L   | 0.346      | -            | -                | -                | -         |    -9.60 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           16 |     3300 | 2024-03-28 | GL Academy        | L   | 0.339      | -            | -                | -                | -         |    -9.22 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           15 |     3510 | 2024-03-17 | Sampi             | L   | 0.265      | -            | -                | -                | -         |    -6.00 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           14 |     3519 | 2024-03-16 | ex-Preasy         | L   | 0.259      | -            | -                | -                | -         |    -6.74 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           13 |     3572 | 2024-03-14 | Sampi             | W   | 0.246      | -            | -                | -                | -         |     2.08 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           12 |     3640 | 2024-03-12 | Alliance          | W   | 0.232      | -            | -                | -                | -         |     1.73 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           11 |     3662 | 2024-03-11 | MOUZ NXT          | L   | 0.226      | -            | -                | -                | -         |    -3.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           10 |     3682 | 2024-03-10 | MOUZ NXT          | W   | 0.219      | -            | -                | -                | -         |     3.15 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            9 |     3697 | 2024-03-09 | The Chosen Few    | L   | 0.214      | -            | -                | -                | -         |    -6.11 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            8 |     3722 | 2024-03-08 | Spirit Academy    | L   | 0.207      | -            | -                | -                | -         |    -6.21 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            7 |     3727 | 2024-03-08 | Entropiq          | W   | 0.206      | -            | -                | -                | -         |     0.31 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            6 |     3746 | 2024-03-07 | AURA              | W   | 0.201      | -            | -                | -                | -         |     0.22 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            5 |     3782 | 2024-03-06 | Permitta          | L   | 0.193      | -            | -                | -                | -         |    -4.17 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            4 |     3786 | 2024-03-06 | Fraud5            | W   | 0.192      | -            | -                | -                | -         |     0.47 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            3 |     3811 | 2024-03-05 | B8                | L   | 0.187      | -            | -                | -                | -         |    -3.06 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            2 |     3840 | 2024-03-04 | ALTERNATE aTTaX   | W   | 0.179      | -            | -                | -                | -         |     1.94 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            1 |     4373 | 2024-02-08 | BLEED             | L   | 0.012      | -            | -                | -                | -         |    -0.26 | jackasmo, jambo, marat2k, s-chilla, Zinchenko |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,841.69)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-25 |      1.000 | $11,000.00     | $11,000.00      |
| 2024-07-22 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-06 |      0.805 | $11,000.00     | $8,850.93       |
| 2024-05-03 |      0.580 | $12,500.00     | $7,248.84       |
| 2024-03-31 |      0.359 | $657.00        | $236.19         |
| 2024-03-30 |      0.352 | $1,000.00      | $352.41         |
| 2024-03-18 |      0.272 | $3,000.00      | $814.72         |
| 2024-03-11 |      0.226 | $1,500.00      | $338.61         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
