### Roster Details<br />
Team Name: Passion UA<br />
Roster: fear, jackasmo, jambo, s-chilla, zeRRoFIX<br />
Global Rank: [47](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [34]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1094.1<br />
<br />
Final Rank Value (1094.1) = Starting Rank Value (1094.9) + Head To Head Adjustments (-0.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.567[<sup>1</sup>](#table2)
- Bounty Collected: 0.462[<sup>2</sup>](#table1)
- Opponent Network: 0.326[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.339<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1094.9
- 400 + ( ( 0.339 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1094.9


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
|           93 |       72 | 2024-08-03 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -8.62 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           92 |      150 | 2024-08-01 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           91 |      231 | 2024-07-30 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.23 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           90 |      266 | 2024-07-29 | Nexus             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.66 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           89 |      278 | 2024-07-29 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -27.92 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           88 |      320 | 2024-07-27 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -12.73 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           87 |      342 | 2024-07-26 | Gaimin Gladiators | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.83 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           86 |      361 | 2024-07-26 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.22 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           85 |      382 | 2024-07-25 | EYEBALLERS        | L   | 1.000      | -            | -                | -                | -         |   -26.80 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           84 |      400 | 2024-07-25 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.32 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           83 |      465 | 2024-07-23 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           82 |      487 | 2024-07-22 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.41 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           81 |      493 | 2024-07-22 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.65 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           80 |      513 | 2024-07-21 | Zero Tenacity     | W   | 1.000      | 0.500        | 0.143 (0.071)    | 1.000 (0.500)    | 0 (0.000) |    17.03 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           79 |      548 | 2024-07-20 | Ninjas in Pyjamas | W   | 1.000      | 0.500        | 0.254 (0.127)    | 0.544 (0.272)    | 0 (0.000) |    29.71 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           78 |      561 | 2024-07-20 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | -                | -         |     8.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           77 |      590 | 2024-07-19 | Nemiga            | W   | 1.000      | 0.500        | 0.316 (0.158)    | 0.722 (0.361)    | -         |    21.03 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           76 |      647 | 2024-07-18 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.122 (0.045)    | 1.000 (0.371)    | -         |    23.53 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           75 |      658 | 2024-07-18 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -23.56 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           74 |      714 | 2024-07-17 | Aurora Young Blud | W   | 1.000      | 0.500        | -                | 0.532 (0.266)    | -         |    10.62 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           73 |      775 | 2024-07-16 | Permitta          | W   | 1.000      | 0.371        | -                | 0.863 (0.320)    | -         |    11.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           72 |      797 | 2024-07-15 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -9.42 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           71 |      817 | 2024-07-15 | WOPA              | W   | 1.000      | -            | -                | -                | -         |     1.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           70 |      835 | 2024-07-14 | Preasy            | W   | 1.000      | -            | -                | -                | -         |     2.15 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           69 |      899 | 2024-07-10 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -18.82 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           68 |      917 | 2024-07-09 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.65 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           67 |      919 | 2024-07-09 | Insilio           | W   | 1.000      | -            | -                | -                | -         |    11.46 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           66 |      939 | 2024-07-08 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.58 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           65 |     1113 | 2024-06-14 | 3DMAX             | L   | 0.851      | -            | -                | -                | -         |    -3.10 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           64 |     1205 | 2024-06-10 | Space             | W   | 0.826      | -            | -                | -                | -         |     6.58 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           63 |     1317 | 2024-06-08 | Zero Tenacity     | L   | 0.813      | -            | -                | -                | -         |   -11.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           62 |     1379 | 2024-06-07 | Rare Atom         | W   | 0.806      | -            | -                | -                | -         |     5.29 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           61 |     1392 | 2024-06-07 | Aurora Young Blud | W   | 0.804      | -            | -                | -                | -         |     6.54 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           60 |     1463 | 2024-06-06 | Serbia            | W   | 0.797      | -            | -                | -                | -         |     5.11 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           59 |     1515 | 2024-06-05 | EYEBALLERS        | L   | 0.791      | -            | -                | -                | -         |   -19.08 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           58 |     1545 | 2024-06-04 | Illuminar         | W   | 0.786      | -            | -                | -                | -         |     4.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           57 |     1554 | 2024-06-04 | Serbia            | W   | 0.785      | -            | -                | -                | -         |     4.57 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           56 |     1603 | 2024-06-02 | UNiTY             | W   | 0.771      | -            | -                | -                | -         |     8.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           55 |     1664 | 2024-05-31 | Zero Tenacity     | L   | 0.759      | -            | -                | -                | -         |   -10.66 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           54 |     1685 | 2024-05-30 | Zero Tenacity     | W   | 0.752      | 0.371        | 0.143 (0.040)    | 1.000 (0.279)    | -         |    13.40 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           53 |     1714 | 2024-05-29 | Illuminar         | W   | 0.744      | -            | -                | -                | -         |     5.71 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           52 |     1785 | 2024-05-25 | Sampi             | W   | 0.719      | 0.435        | -                | 1.000 (0.313)    | -         |     7.30 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           51 |     1806 | 2024-05-24 | FURIA             | L   | 0.713      | -            | -                | -                | -         |    -0.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           50 |     1812 | 2024-05-24 | ECSTATIC          | W   | 0.711      | -            | -                | -                | -         |     1.30 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           49 |     1826 | 2024-05-23 | SINNERS           | W   | 0.704      | -            | -                | -                | -         |    12.34 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           48 |     1950 | 2024-05-20 | Permitta          | W   | 0.684      | 0.435        | -                | 0.863 (0.257)    | -         |     6.76 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           47 |     1962 | 2024-05-19 | Sashi             | L   | 0.680      | -            | -                | -                | -         |    -5.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           46 |     1973 | 2024-05-19 | ALTERNATE aTTaX   | W   | 0.678      | -            | -                | -                | -         |     7.97 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           45 |     1993 | 2024-05-18 | 9 Pandas          | L   | 0.673      | -            | -                | -                | -         |   -10.84 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           44 |     2036 | 2024-05-17 | Nexus             | W   | 0.665      | -            | -                | -                | -         |     4.36 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           43 |     2077 | 2024-05-16 | Sashi             | W   | 0.658      | 0.500        | 0.184 (0.060)    | 0.983 (0.323)    | -         |    15.44 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           42 |     2116 | 2024-05-15 | Endpoint          | L   | 0.653      | -            | -                | -                | -         |   -12.81 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           41 |     2170 | 2024-05-14 | SINNERS           | L   | 0.647      | -            | -                | -                | -         |    -8.99 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           40 |     2263 | 2024-05-11 | Preasy            | W   | 0.624      | -            | -                | -                | -         |     3.57 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           39 |     2427 | 2024-05-02 | Nemiga            | L   | 0.566      | -            | -                | -                | -         |    -5.68 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           38 |     2450 | 2024-05-01 | PARIVISION        | W   | 0.559      | -            | -                | -                | -         |    10.26 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           37 |     2487 | 2024-04-30 | 9 Pandas          | W   | 0.551      | -            | -                | -                | -         |     7.38 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           36 |     2514 | 2024-04-28 | ALTERNATE aTTaX   | L   | 0.540      | -            | -                | -                | -         |   -10.17 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           35 |     2564 | 2024-04-26 | 9 Pandas          | W   | 0.526      | -            | -                | -                | -         |     7.24 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           34 |     2565 | 2024-04-26 | 9 Pandas          | W   | 0.526      | -            | -                | -                | -         |     6.92 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           33 |     2601 | 2024-04-25 | Sashi             | L   | 0.518      | -            | -                | -                | -         |    -4.98 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           32 |     2616 | 2024-04-24 | Permitta          | L   | 0.512      | -            | -                | -                | -         |    -9.48 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           31 |     2645 | 2024-04-22 | B8                | L   | 0.500      | -            | -                | -                | -         |    -7.84 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           30 |     2686 | 2024-04-20 | Young Ninjas      | W   | 0.487      | -            | -                | -                | -         |     2.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           29 |     2708 | 2024-04-20 | Permitta          | L   | 0.484      | -            | -                | -                | -         |    -9.42 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           28 |     2742 | 2024-04-19 | ALTERNATE aTTaX   | L   | 0.479      | -            | -                | -                | -         |    -9.63 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           27 |     2799 | 2024-04-18 | Permitta          | W   | 0.472      | -            | -                | -                | -         |     5.58 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           26 |     2829 | 2024-04-17 | Sashi             | W   | 0.466      | 0.371        | 0.184 (0.032)    | -                | -         |     8.93 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           25 |     2863 | 2024-04-16 | 500               | L   | 0.460      | -            | -                | -                | -         |   -12.32 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           24 |     2902 | 2024-04-14 | SINNERS           | L   | 0.445      | -            | -                | -                | -         |    -4.76 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           23 |     2957 | 2024-04-11 | 3DMAX             | W   | 0.426      | 0.384        | 0.508 (0.083)    | -                | -         |    12.95 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           22 |     3005 | 2024-04-10 | Sashi             | W   | 0.418      | 0.371        | 0.184 (0.028)    | -                | -         |     8.30 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           21 |     3192 | 2024-04-04 | HAVU              | W   | 0.379      | -            | -                | -                | -         |     1.59 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           20 |     3263 | 2024-04-02 | BLEED             | L   | 0.366      | -            | -                | -                | -         |    -6.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           19 |     3292 | 2024-03-31 | FAVBET            | L   | 0.352      | -            | -                | -                | -         |    -9.16 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           18 |     3299 | 2024-03-30 | Lazer Cats        | W   | 0.345      | -            | -                | -                | -         |     0.58 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           17 |     3307 | 2024-03-29 | NAVI Junior       | L   | 0.339      | -            | -                | -                | -         |    -9.43 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           16 |     3326 | 2024-03-28 | GL Academy        | L   | 0.332      | -            | -                | -                | -         |    -9.06 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           15 |     3536 | 2024-03-17 | Sampi             | L   | 0.258      | -            | -                | -                | -         |    -5.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           14 |     3545 | 2024-03-16 | ex-Preasy         | L   | 0.252      | -            | -                | -                | -         |    -6.59 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           13 |     3598 | 2024-03-14 | Sampi             | W   | 0.239      | -            | -                | -                | -         |     1.97 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           12 |     3666 | 2024-03-12 | Alliance          | W   | 0.225      | -            | -                | -                | -         |     1.65 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           11 |     3688 | 2024-03-11 | MOUZ NXT          | L   | 0.219      | -            | -                | -                | -         |    -3.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           10 |     3708 | 2024-03-10 | MOUZ NXT          | W   | 0.212      | -            | -                | -                | -         |     3.05 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            9 |     3723 | 2024-03-09 | The Chosen Few    | L   | 0.206      | -            | -                | -                | -         |    -5.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            8 |     3748 | 2024-03-08 | Spirit Academy    | L   | 0.200      | -            | -                | -                | -         |    -6.00 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            7 |     3753 | 2024-03-08 | Entropiq          | W   | 0.198      | -            | -                | -                | -         |     0.29 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            6 |     3772 | 2024-03-07 | AURA              | W   | 0.193      | -            | -                | -                | -         |     0.21 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            5 |     3808 | 2024-03-06 | Permitta          | L   | 0.186      | -            | -                | -                | -         |    -4.04 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            4 |     3812 | 2024-03-06 | Fraud5            | W   | 0.185      | -            | -                | -                | -         |     0.45 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            3 |     3837 | 2024-03-05 | B8                | L   | 0.180      | -            | -                | -                | -         |    -2.96 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            2 |     3866 | 2024-03-04 | ALTERNATE aTTaX   | W   | 0.172      | -            | -                | -                | -         |     1.84 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            1 |     4399 | 2024-02-08 | BLEED             | L   | 0.005      | -            | -                | -                | -         |    -0.11 | jackasmo, jambo, marat2k, s-chilla, Zinchenko |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,630.25)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-25 |      1.000 | $11,000.00     | $11,000.00      |
| 2024-07-22 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-06 |      0.797 | $11,000.00     | $8,772.50       |
| 2024-05-03 |      0.573 | $12,500.00     | $7,159.72       |
| 2024-03-31 |      0.352 | $657.00        | $231.50         |
| 2024-03-30 |      0.345 | $1,000.00      | $345.28         |
| 2024-03-18 |      0.264 | $3,000.00      | $793.33         |
| 2024-03-11 |      0.219 | $1,500.00      | $327.92         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
