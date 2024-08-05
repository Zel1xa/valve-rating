### Roster Details<br />
Team Name: Sashi<br />
Roster: Cabbi, IceBerg, kwezz, Lucky, MistR<br />
Global Rank: [40](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [29]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1126.8<br />
<br />
Final Rank Value (1126.8) = Starting Rank Value (1160.2) + Head To Head Adjustments (-33.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.576[<sup>1</sup>](#table2)
- Bounty Collected: 0.463[<sup>2</sup>](#table1)
- Opponent Network: 0.238[<sup>2</sup>](#table1)
- LAN Wins: 0.206[<sup>2</sup>](#table1)

The average of these factors is 0.371<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1160.2
- 400 + ( ( 0.371 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1160.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           97 |        4 | 2024-08-05 | ECSTATIC          | L   | 1.000      | -            | -                | -                | -         |   -30.20 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           96 |        8 | 2024-08-05 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -23.11 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           95 |       14 | 2024-08-05 | ECSTATIC          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.89 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           94 |      194 | 2024-07-31 | Insilio           | W   | 1.000      | 0.500        | -                | 0.552 (0.276)    | 0 (0.000) |     6.84 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           93 |      225 | 2024-07-30 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.500 (0.250)    | 0 (0.000) |     3.32 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           92 |      237 | 2024-07-30 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -17.09 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           91 |      418 | 2024-07-24 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.611 (0.306)    | 0 (0.000) |    10.32 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           90 |      639 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |    -2.85 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           89 |      649 | 2024-07-18 | JiJieHao          | W   | 1.000      | 1.000        | 0.031 (0.031)    | -                | 1 (1.000) |     1.24 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           88 |      719 | 2024-07-17 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |    -0.62 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           87 |      846 | 2024-07-13 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -22.31 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           86 |      855 | 2024-07-12 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.44 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           85 |      872 | 2024-07-11 | Endpoint          | W   | 1.000      | 0.358        | -                | 0.514 (0.184)    | 0 (0.000) |     4.76 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           84 |      896 | 2024-07-10 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -13.77 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           83 |      899 | 2024-07-10 | 9INE              | W   | 1.000      | 0.358        | -                | 0.533 (0.191)    | 0 (0.000) |     5.38 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           82 |     1103 | 2024-06-14 | 3DMAX             | L   | 0.852      | -            | -                | -                | -         |    -5.73 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           81 |     1138 | 2024-06-13 | Sampi             | W   | 0.845      | -            | -                | -                | 0 (0.000) |     3.58 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           80 |     1155 | 2024-06-12 | CPH Wolves        | W   | 0.840      | -            | -                | -                | -         |     2.42 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           79 |     1164 | 2024-06-12 | Astralis Talent   | W   | 0.839      | -            | -                | -                | -         |     1.83 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           78 |     1420 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.800      | -            | -                | -                | -         |    -2.63 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           77 |     1456 | 2024-06-06 | HEROIC            | L   | 0.798      | -            | -                | -                | -         |    -3.14 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           76 |     1485 | 2024-06-05 | ENCE              | L   | 0.793      | -            | -                | -                | -         |    -7.89 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           75 |     1505 | 2024-06-05 | Astralis          | W   | 0.792      | 0.715        | 0.389 (0.221)    | 0.413 (0.234)    | 1 (0.792) |    23.78 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           74 |     1515 | 2024-06-05 | The MongolZ       | L   | 0.791      | -            | -                | -                | -         |    -0.46 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           73 |     1950 | 2024-05-20 | Monte             | L   | 0.684      | -            | -                | -                | -         |   -15.65 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           72 |     1963 | 2024-05-19 | Passion UA        | W   | 0.679      | 0.500        | 0.173 (0.059)    | 1.000 (0.340)    | -         |     5.92 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           71 |     1990 | 2024-05-18 | B8                | L   | 0.673      | -            | -                | -                | -         |   -12.56 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           70 |     1999 | 2024-05-18 | Monte             | W   | 0.672      | -            | -                | -                | -         |     5.56 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           69 |     2007 | 2024-05-18 | ALTERNATE aTTaX   | W   | 0.671      | 0.500        | -                | 0.550 (0.185)    | -         |     3.89 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           68 |     2038 | 2024-05-17 | ex-Guild Eagles   | W   | 0.664      | -            | -                | -                | -         |     2.34 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           67 |     2078 | 2024-05-16 | Passion UA        | L   | 0.657      | -            | -                | -                | -         |   -15.41 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           66 |     2125 | 2024-05-15 | Endpoint          | W   | 0.651      | -            | -                | -                | -         |     3.50 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           65 |     2297 | 2024-05-09 | 1WIN              | W   | 0.612      | -            | -                | -                | -         |     4.15 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           64 |     2320 | 2024-05-08 | Grannys Knockers  | W   | 0.605      | -            | -                | -                | -         |     1.66 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           63 |     2338 | 2024-05-07 | 9 Pandas          | W   | 0.598      | -            | -                | -                | -         |     4.48 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           62 |     2352 | 2024-05-06 | ALTERNATE aTTaX   | W   | 0.593      | -            | -                | -                | -         |     4.12 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           61 |     2366 | 2024-05-05 | Gaimin Gladiators | L   | 0.586      | -            | -                | -                | -         |   -14.13 | Cabbi, IceBerg, kwezz, Lucky, PR1mE   |
|           60 |     2374 | 2024-05-05 | Come on now dawg  | W   | 0.585      | -            | -                | -                | -         |     0.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           59 |     2426 | 2024-05-02 | fnatic            | W   | 0.566      | 0.384        | 0.371 (0.081)    | -                | -         |    15.21 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           58 |     2461 | 2024-05-01 | 3DMAX             | W   | 0.558      | 0.384        | 0.508 (0.109)    | 1.000 (0.214)    | -         |    16.20 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           57 |     2478 | 2024-04-30 | OG                | W   | 0.552      | 0.384        | 0.138 (0.029)    | -                | -         |     6.08 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           56 |     2503 | 2024-04-29 | 500               | W   | 0.545      | -            | -                | -                | -         |     1.30 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           55 |     2531 | 2024-04-27 | 777               | W   | 0.533      | -            | -                | -                | -         |     1.16 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           54 |     2535 | 2024-04-27 | JANO              | W   | 0.533      | -            | -                | -                | -         |     1.02 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           53 |     2602 | 2024-04-25 | Passion UA        | W   | 0.518      | 0.384        | 0.173 (0.034)    | 1.000 (0.199)    | -         |     5.00 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           52 |     2636 | 2024-04-23 | Gaimin Gladiators | W   | 0.505      | -            | -                | -                | -         |     5.03 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           51 |     2641 | 2024-04-23 | BLEED             | W   | 0.504      | -            | -                | -                | -         |     5.73 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           50 |     2692 | 2024-04-20 | Eternal Fire      | W   | 0.486      | 0.143        | 0.740 (0.051)    | -                | -         |    14.69 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           49 |     2699 | 2024-04-20 | Cloud9            | W   | 0.485      | -            | -                | -                | -         |     6.30 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           48 |     2738 | 2024-04-19 | Eternal Fire      | L   | 0.480      | -            | -                | -                | -         |    -0.58 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           47 |     2747 | 2024-04-19 | Cloud9            | W   | 0.479      | -            | -                | -                | -         |     6.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           46 |     2773 | 2024-04-18 | ex-Guild Eagles   | W   | 0.473      | -            | -                | -                | -         |     2.46 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           45 |     2777 | 2024-04-18 | RUBY              | W   | 0.473      | -            | -                | -                | -         |     3.99 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           44 |     2786 | 2024-04-18 | GamerLegion       | W   | 0.473      | -            | -                | -                | -         |     7.55 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           43 |     2830 | 2024-04-17 | Passion UA        | L   | 0.465      | -            | -                | -                | -         |    -8.90 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           42 |     2867 | 2024-04-16 | ex-Guild Eagles   | L   | 0.458      | -            | -                | -                | -         |   -12.34 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           41 |     2888 | 2024-04-15 | ex-Preasy         | W   | 0.452      | -            | -                | -                | -         |     2.10 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           40 |     2905 | 2024-04-14 | UNiTY             | W   | 0.444      | -            | -                | -                | -         |     3.89 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           39 |     2963 | 2024-04-11 | Enterprise        | W   | 0.424      | -            | -                | -                | -         |     3.21 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           38 |     3006 | 2024-04-10 | Passion UA        | L   | 0.418      | -            | -                | -                | -         |    -8.28 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           37 |     3139 | 2024-04-06 | UNiTY             | W   | 0.390      | -            | -                | -                | -         |     3.50 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           36 |     3196 | 2024-04-04 | UNiTY             | W   | 0.378      | -            | -                | -                | -         |     3.35 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           35 |     3280 | 2024-04-02 | Permitta          | W   | 0.364      | -            | -                | -                | -         |     3.42 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           34 |     3289 | 2024-04-01 | Nexus             | L   | 0.358      | -            | -                | -                | -         |    -9.39 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           33 |     3363 | 2024-03-27 | Rebels            | L   | 0.327      | -            | -                | -                | -         |    -7.20 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           32 |     3398 | 2024-03-25 | Nexus             | W   | 0.313      | -            | -                | -                | -         |     1.58 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           31 |     3422 | 2024-03-22 | Nemiga            | W   | 0.293      | 0.372        | 0.316 (0.034)    | -                | -         |     5.02 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           30 |     3487 | 2024-03-19 | RUBY              | W   | 0.273      | -            | -                | -                | -         |     2.06 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           29 |     3499 | 2024-03-18 | Insilio           | W   | 0.265      | -            | -                | -                | -         |     1.81 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           28 |     3567 | 2024-03-15 | ECLOT             | W   | 0.244      | -            | -                | -                | -         |     4.58 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           27 |     3641 | 2024-03-13 | BLEED             | L   | 0.231      | -            | -                | -                | -         |    -5.16 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           26 |     3688 | 2024-03-11 | Nemiga            | L   | 0.219      | -            | -                | -                | -         |    -3.09 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           25 |     3711 | 2024-03-10 | Sampi             | L   | 0.211      | -            | -                | -                | -         |    -5.36 | Cabbi, IceBerg, Kristou, Lucky, MistR |
|           24 |     3735 | 2024-03-09 | Permitta          | W   | 0.205      | -            | -                | -                | -         |     1.83 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           23 |     3756 | 2024-03-08 | ALTERNATE aTTaX   | L   | 0.197      | -            | -                | -                | -         |    -4.43 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           22 |     3766 | 2024-03-07 | Insilio           | W   | 0.194      | -            | -                | -                | -         |     1.23 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           21 |     3780 | 2024-03-07 | ex-sYnck          | W   | 0.192      | -            | -                | -                | -         |     0.16 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           20 |     3812 | 2024-03-06 | Alliance          | W   | 0.185      | -            | -                | -                | -         |     0.97 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           19 |     3846 | 2024-03-05 | Johnny Speeds     | L   | 0.180      | -            | -                | -                | -         |    -1.64 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           18 |     3855 | 2024-03-05 | ALTERNATE aTTaX   | L   | 0.178      | -            | -                | -                | -         |    -4.04 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           17 |     3871 | 2024-03-04 | Entropiq          | L   | 0.171      | -            | -                | -                | -         |    -5.20 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           16 |     3916 | 2024-03-02 | brazylijski luz   | W   | 0.158      | -            | -                | -                | -         |     0.59 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           15 |     3950 | 2024-02-29 | JANO              | W   | 0.144      | -            | -                | -                | -         |     0.31 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           14 |     3960 | 2024-02-28 | Sampi             | W   | 0.139      | -            | -                | -                | -         |     0.81 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           13 |     3975 | 2024-02-27 | V1dar             | L   | 0.133      | -            | -                | -                | -         |    -4.07 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           12 |     4016 | 2024-02-25 | Sangal            | L   | 0.120      | -            | -                | -                | -         |    -1.86 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           11 |     4022 | 2024-02-25 | PGE Turow         | L   | 0.118      | -            | -                | -                | -         |    -3.52 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           10 |     4062 | 2024-02-24 | MOUZ NXT          | L   | 0.111      | -            | -                | -                | -         |    -2.29 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            9 |     4113 | 2024-02-21 | Sampi             | W   | 0.092      | -            | -                | -                | -         |     0.51 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            8 |     4211 | 2024-02-17 | Zero Tenacity     | W   | 0.066      | -            | -                | -                | -         |     0.87 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            7 |     4359 | 2024-02-11 | ARCRED            | W   | 0.025      | -            | -                | -                | -         |     0.16 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            6 |     4361 | 2024-02-10 | Nemiga            | L   | 0.020      | -            | -                | -                | -         |    -0.31 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            5 |     4369 | 2024-02-10 | AMKAL             | W   | 0.019      | -            | -                | -                | -         |     0.28 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            4 |     4378 | 2024-02-09 | FORZE             | W   | 0.013      | -            | -                | -                | -         |     0.07 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            3 |     4384 | 2024-02-09 | Insilio           | W   | 0.012      | -            | -                | -                | -         |     0.07 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            2 |     4392 | 2024-02-08 | Nemiga            | L   | 0.007      | -            | -                | -                | -         |    -0.10 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            1 |     4396 | 2024-02-08 | FORZE             | W   | 0.006      | -            | -                | -                | -         |     0.03 | Cabbi, IceBerg, kwezz, Lucky, MistR   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($59,173.64)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.18) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-07-13 |      1.000 | $3,216.00      | $3,216.00       |
| 2024-06-12 |      0.840 | $9,365.00      | $7,863.35       |
| 2024-06-09 |      0.819 | $8,000.00      | $6,552.22       |
| 2024-05-18 |      0.673 | $5,000.00      | $3,364.58       |
| 2024-05-09 |      0.612 | $14,000.00     | $8,561.39       |
| 2024-05-02 |      0.566 | $12,500.00     | $7,074.65       |
| 2024-04-27 |      0.533 | $6,375.00      | $3,400.89       |
| 2024-04-06 |      0.390 | $5,000.00      | $1,952.08       |
| 2024-03-25 |      0.313 | $7,000.00      | $2,188.47       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
