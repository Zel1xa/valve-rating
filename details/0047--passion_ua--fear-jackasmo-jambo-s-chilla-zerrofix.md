### Roster Details<br />
Team Name: Passion UA<br />
Roster: fear, jackasmo, jambo, s-chilla, zeRRoFIX<br />
Global Rank: [47](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [34]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1094.9<br />
<br />
Final Rank Value (1094.9) = Starting Rank Value (1096.2) + Head To Head Adjustments (-1.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.567[<sup>1</sup>](#table2)
- Bounty Collected: 0.462[<sup>2</sup>](#table1)
- Opponent Network: 0.329[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.340<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1096.2
- 400 + ( ( 0.340 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1096.2


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
|           93 |       73 | 2024-08-03 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -8.63 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           92 |      151 | 2024-08-01 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           91 |      232 | 2024-07-30 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.21 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           90 |      267 | 2024-07-29 | Nexus             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.66 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           89 |      279 | 2024-07-29 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -27.92 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           88 |      321 | 2024-07-27 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -12.77 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           87 |      343 | 2024-07-26 | Gaimin Gladiators | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.81 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           86 |      362 | 2024-07-26 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.21 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           85 |      383 | 2024-07-25 | EYEBALLERS        | L   | 1.000      | -            | -                | -                | -         |   -26.80 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           84 |      401 | 2024-07-25 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.30 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           83 |      466 | 2024-07-23 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.85 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           82 |      488 | 2024-07-22 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.43 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           81 |      494 | 2024-07-22 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.62 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           80 |      514 | 2024-07-21 | Zero Tenacity     | W   | 1.000      | 0.500        | 0.143 (0.071)    | 1.000 (0.500)    | 0 (0.000) |    17.00 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           79 |      549 | 2024-07-20 | Ninjas in Pyjamas | W   | 1.000      | 0.500        | 0.254 (0.127)    | 0.544 (0.272)    | 0 (0.000) |    29.70 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           78 |      562 | 2024-07-20 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | -                | -         |     8.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           77 |      591 | 2024-07-19 | Nemiga            | W   | 1.000      | 0.500        | 0.316 (0.158)    | 0.722 (0.361)    | -         |    21.00 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           76 |      648 | 2024-07-18 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.122 (0.045)    | 1.000 (0.371)    | -         |    23.51 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           75 |      659 | 2024-07-18 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -23.59 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           74 |      715 | 2024-07-17 | Aurora Young Blud | W   | 1.000      | 0.500        | -                | 0.532 (0.266)    | -         |    10.58 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           73 |      776 | 2024-07-16 | Permitta          | W   | 1.000      | 0.371        | -                | 0.902 (0.334)    | -         |    11.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           72 |      798 | 2024-07-15 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -9.46 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           71 |      818 | 2024-07-15 | WOPA              | W   | 1.000      | -            | -                | -                | -         |     1.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           70 |      836 | 2024-07-14 | Preasy            | W   | 1.000      | -            | -                | -                | -         |     2.14 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           69 |      900 | 2024-07-10 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -18.69 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           68 |      918 | 2024-07-09 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.69 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           67 |      920 | 2024-07-09 | Insilio           | W   | 1.000      | -            | -                | -                | -         |    11.47 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           66 |      940 | 2024-07-08 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.62 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           65 |     1114 | 2024-06-14 | 3DMAX             | L   | 0.850      | -            | -                | -                | -         |    -3.10 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           64 |     1206 | 2024-06-10 | Space             | W   | 0.826      | -            | -                | -                | -         |     6.57 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           63 |     1318 | 2024-06-08 | Zero Tenacity     | L   | 0.812      | -            | -                | -                | -         |   -11.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           62 |     1380 | 2024-06-07 | Rare Atom         | W   | 0.805      | -            | -                | -                | -         |     5.27 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           61 |     1393 | 2024-06-07 | Aurora Young Blud | W   | 0.804      | -            | -                | -                | -         |     6.50 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           60 |     1464 | 2024-06-06 | Serbia            | W   | 0.797      | -            | -                | -                | -         |     5.10 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           59 |     1516 | 2024-06-05 | EYEBALLERS        | L   | 0.791      | -            | -                | -                | -         |   -19.08 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           58 |     1546 | 2024-06-04 | Illuminar         | W   | 0.786      | -            | -                | -                | -         |     4.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           57 |     1555 | 2024-06-04 | Serbia            | W   | 0.785      | -            | -                | -                | -         |     4.56 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           56 |     1604 | 2024-06-02 | UNiTY             | W   | 0.770      | -            | -                | -                | -         |     8.85 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           55 |     1665 | 2024-05-31 | Zero Tenacity     | L   | 0.758      | -            | -                | -                | -         |   -10.69 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           54 |     1686 | 2024-05-30 | Zero Tenacity     | W   | 0.752      | 0.371        | 0.143 (0.040)    | 1.000 (0.279)    | -         |    13.35 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           53 |     1715 | 2024-05-29 | Illuminar         | W   | 0.744      | -            | -                | -                | -         |     5.67 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           52 |     1786 | 2024-05-25 | Sampi             | W   | 0.719      | 0.435        | -                | 1.000 (0.312)    | -         |     7.28 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           51 |     1807 | 2024-05-24 | FURIA             | L   | 0.712      | -            | -                | -                | -         |    -0.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           50 |     1813 | 2024-05-24 | ECSTATIC          | W   | 0.710      | -            | -                | -                | -         |     1.29 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           49 |     1827 | 2024-05-23 | SINNERS           | W   | 0.704      | -            | -                | -                | -         |    12.29 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           48 |     1951 | 2024-05-20 | Permitta          | W   | 0.684      | 0.435        | -                | 0.902 (0.268)    | -         |     6.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           47 |     1963 | 2024-05-19 | Sashi             | L   | 0.679      | -            | -                | -                | -         |    -5.92 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           46 |     1974 | 2024-05-19 | ALTERNATE aTTaX   | W   | 0.678      | -            | -                | -                | -         |     7.94 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           45 |     1994 | 2024-05-18 | 9 Pandas          | L   | 0.672      | -            | -                | -                | -         |   -10.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           44 |     2037 | 2024-05-17 | Nexus             | W   | 0.665      | -            | -                | -                | -         |     4.34 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           43 |     2078 | 2024-05-16 | Sashi             | W   | 0.657      | 0.500        | 0.184 (0.060)    | 0.983 (0.323)    | -         |    15.41 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           42 |     2117 | 2024-05-15 | Endpoint          | L   | 0.652      | -            | -                | -                | -         |   -12.83 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           41 |     2171 | 2024-05-14 | SINNERS           | L   | 0.646      | -            | -                | -                | -         |    -9.02 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           40 |     2264 | 2024-05-11 | Preasy            | W   | 0.624      | -            | -                | -                | -         |     3.54 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           39 |     2428 | 2024-05-02 | Nemiga            | L   | 0.566      | -            | -                | -                | -         |    -5.71 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           38 |     2451 | 2024-05-01 | PARIVISION        | W   | 0.559      | -            | -                | -                | -         |    10.22 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           37 |     2488 | 2024-04-30 | 9 Pandas          | W   | 0.551      | -            | -                | -                | -         |     7.33 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           36 |     2515 | 2024-04-28 | ALTERNATE aTTaX   | L   | 0.539      | -            | -                | -                | -         |   -10.19 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           35 |     2565 | 2024-04-26 | 9 Pandas          | W   | 0.526      | -            | -                | -                | -         |     7.19 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           34 |     2566 | 2024-04-26 | 9 Pandas          | W   | 0.526      | -            | -                | -                | -         |     6.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           33 |     2602 | 2024-04-25 | Sashi             | L   | 0.518      | -            | -                | -                | -         |    -5.00 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           32 |     2617 | 2024-04-24 | Permitta          | L   | 0.512      | -            | -                | -                | -         |    -9.28 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           31 |     2646 | 2024-04-22 | B8                | L   | 0.500      | -            | -                | -                | -         |    -7.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           30 |     2687 | 2024-04-20 | Young Ninjas      | W   | 0.487      | -            | -                | -                | -         |     2.83 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           29 |     2709 | 2024-04-20 | Permitta          | L   | 0.484      | -            | -                | -                | -         |    -9.21 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           28 |     2743 | 2024-04-19 | ALTERNATE aTTaX   | L   | 0.479      | -            | -                | -                | -         |    -9.65 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           27 |     2800 | 2024-04-18 | Permitta          | W   | 0.472      | -            | -                | -                | -         |     5.77 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           26 |     2830 | 2024-04-17 | Sashi             | W   | 0.465      | 0.371        | 0.184 (0.032)    | -                | -         |     8.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           25 |     2864 | 2024-04-16 | 500               | L   | 0.459      | -            | -                | -                | -         |   -12.32 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           24 |     2903 | 2024-04-14 | SINNERS           | L   | 0.445      | -            | -                | -                | -         |    -4.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           23 |     2958 | 2024-04-11 | 3DMAX             | W   | 0.425      | 0.384        | 0.508 (0.083)    | -                | -         |    12.93 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           22 |     3006 | 2024-04-10 | Sashi             | W   | 0.418      | 0.371        | 0.184 (0.028)    | -                | -         |     8.28 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           21 |     3193 | 2024-04-04 | HAVU              | W   | 0.378      | -            | -                | -                | -         |     1.58 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           20 |     3264 | 2024-04-02 | BLEED             | L   | 0.366      | -            | -                | -                | -         |    -6.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           19 |     3293 | 2024-03-31 | FAVBET            | L   | 0.352      | -            | -                | -                | -         |    -9.16 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           18 |     3300 | 2024-03-30 | Lazer Cats        | W   | 0.345      | -            | -                | -                | -         |     0.58 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           17 |     3308 | 2024-03-29 | NAVI Junior       | L   | 0.338      | -            | -                | -                | -         |    -9.43 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           16 |     3327 | 2024-03-28 | GL Academy        | L   | 0.332      | -            | -                | -                | -         |    -9.06 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           15 |     3537 | 2024-03-17 | Sampi             | L   | 0.257      | -            | -                | -                | -         |    -5.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           14 |     3546 | 2024-03-16 | ex-Preasy         | L   | 0.252      | -            | -                | -                | -         |    -6.59 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           13 |     3599 | 2024-03-14 | Sampi             | W   | 0.238      | -            | -                | -                | -         |     1.97 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           12 |     3667 | 2024-03-12 | Alliance          | W   | 0.225      | -            | -                | -                | -         |     1.63 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           11 |     3689 | 2024-03-11 | MOUZ NXT          | L   | 0.218      | -            | -                | -                | -         |    -3.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           10 |     3709 | 2024-03-10 | MOUZ NXT          | W   | 0.212      | -            | -                | -                | -         |     3.03 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            9 |     3724 | 2024-03-09 | The Chosen Few    | L   | 0.206      | -            | -                | -                | -         |    -5.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            8 |     3749 | 2024-03-08 | Spirit Academy    | L   | 0.199      | -            | -                | -                | -         |    -5.99 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            7 |     3754 | 2024-03-08 | Entropiq          | W   | 0.198      | -            | -                | -                | -         |     0.29 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            6 |     3773 | 2024-03-07 | AURA              | W   | 0.193      | -            | -                | -                | -         |     0.20 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            5 |     3809 | 2024-03-06 | Permitta          | L   | 0.185      | -            | -                | -                | -         |    -3.94 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            4 |     3813 | 2024-03-06 | Fraud5            | W   | 0.185      | -            | -                | -                | -         |     0.44 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            3 |     3838 | 2024-03-05 | B8                | L   | 0.180      | -            | -                | -                | -         |    -2.97 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            2 |     3867 | 2024-03-04 | ALTERNATE aTTaX   | W   | 0.171      | -            | -                | -                | -         |     1.83 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            1 |     4400 | 2024-02-08 | BLEED             | L   | 0.005      | -            | -                | -                | -         |    -0.10 | jackasmo, jambo, marat2k, s-chilla, Zinchenko |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,617.89)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-25 |      1.000 | $11,000.00     | $11,000.00      |
| 2024-07-22 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-06 |      0.797 | $11,000.00     | $8,767.92       |
| 2024-05-03 |      0.572 | $12,500.00     | $7,154.51       |
| 2024-03-31 |      0.352 | $657.00        | $231.23         |
| 2024-03-30 |      0.345 | $1,000.00      | $344.86         |
| 2024-03-18 |      0.264 | $3,000.00      | $792.08         |
| 2024-03-11 |      0.218 | $1,500.00      | $327.29         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
