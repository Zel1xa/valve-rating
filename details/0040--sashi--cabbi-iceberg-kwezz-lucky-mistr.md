### Roster Details<br />
Team Name: Sashi<br />
Roster: Cabbi, IceBerg, kwezz, Lucky, MistR<br />
Global Rank: [40](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [29]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1128.7<br />
<br />
Final Rank Value (1128.7) = Starting Rank Value (1160.4) + Head To Head Adjustments (-31.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.576[<sup>1</sup>](#table2)
- Bounty Collected: 0.462[<sup>2</sup>](#table1)
- Opponent Network: 0.234[<sup>2</sup>](#table1)
- LAN Wins: 0.206[<sup>2</sup>](#table1)

The average of these factors is 0.370<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1160.4
- 400 + ( ( 0.370 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1160.4


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
|           96 |       29 | 2024-08-05 | ECSTATIC          | L   | 1.000      | -            | -                | -                | -         |   -30.22 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           95 |       33 | 2024-08-05 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -23.08 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           94 |       39 | 2024-08-05 | ECSTATIC          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.88 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           93 |      219 | 2024-07-31 | Insilio           | W   | 1.000      | 0.500        | -                | 0.539 (0.270)    | 0 (0.000) |     7.03 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           92 |      250 | 2024-07-30 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.488 (0.244)    | 0 (0.000) |     3.38 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           91 |      263 | 2024-07-30 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -16.93 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           90 |      443 | 2024-07-24 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.598 (0.299)    | 0 (0.000) |    10.38 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           89 |      664 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |    -2.87 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           88 |      674 | 2024-07-18 | JiJieHao          | W   | 1.000      | 1.000        | 0.031 (0.031)    | -                | 1 (1.000) |     1.24 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           87 |      744 | 2024-07-17 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |    -0.63 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           86 |      871 | 2024-07-13 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -22.30 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           85 |      880 | 2024-07-12 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.44 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           84 |      897 | 2024-07-11 | Endpoint          | W   | 1.000      | 0.358        | -                | 0.540 (0.193)    | 0 (0.000) |     4.88 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           83 |      921 | 2024-07-10 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -13.68 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           82 |      924 | 2024-07-10 | 9INE              | W   | 1.000      | 0.358        | -                | 0.523 (0.187)    | 0 (0.000) |     5.42 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           81 |     1128 | 2024-06-14 | 3DMAX             | L   | 0.846      | -            | -                | -                | -         |    -5.58 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           80 |     1163 | 2024-06-13 | Sampi             | W   | 0.839      | -            | -                | -                | 0 (0.000) |     3.63 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           79 |     1180 | 2024-06-12 | CPH Wolves        | W   | 0.834      | -            | -                | -                | -         |     2.40 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           78 |     1189 | 2024-06-12 | Astralis Talent   | W   | 0.833      | -            | -                | -                | -         |     1.82 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           77 |     1445 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.794      | -            | -                | -                | -         |    -2.63 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           76 |     1481 | 2024-06-06 | HEROIC            | L   | 0.792      | -            | -                | -                | -         |    -3.17 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           75 |     1510 | 2024-06-05 | ENCE              | L   | 0.787      | -            | -                | -                | -         |    -7.77 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           74 |     1530 | 2024-06-05 | Astralis          | W   | 0.786      | 0.715        | 0.389 (0.218)    | 0.403 (0.226)    | 1 (0.786) |    23.58 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           73 |     1540 | 2024-06-05 | The MongolZ       | L   | 0.785      | -            | -                | -                | -         |    -0.46 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           72 |     1975 | 2024-05-20 | Monte             | L   | 0.678      | -            | -                | -                | -         |   -15.52 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           71 |     1988 | 2024-05-19 | Passion UA        | W   | 0.673      | 0.500        | 0.173 (0.058)    | 1.000 (0.337)    | -         |     5.94 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           70 |     2015 | 2024-05-18 | B8                | L   | 0.667      | -            | -                | -                | -         |   -12.38 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           69 |     2024 | 2024-05-18 | Monte             | W   | 0.666      | -            | -                | -                | -         |     5.51 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           68 |     2032 | 2024-05-18 | ALTERNATE aTTaX   | W   | 0.665      | 0.500        | -                | 0.537 (0.178)    | -         |     3.93 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           67 |     2063 | 2024-05-17 | ex-Guild Eagles   | W   | 0.658      | -            | -                | -                | -         |     2.36 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           66 |     2103 | 2024-05-16 | Passion UA        | L   | 0.651      | -            | -                | -                | -         |   -15.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           65 |     2150 | 2024-05-15 | Endpoint          | W   | 0.645      | -            | -                | -                | -         |     3.51 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           64 |     2322 | 2024-05-09 | 1WIN              | W   | 0.605      | -            | -                | -                | -         |     4.13 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           63 |     2345 | 2024-05-08 | Grannys Knockers  | W   | 0.599      | -            | -                | -                | -         |     1.64 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           62 |     2363 | 2024-05-07 | 9 Pandas          | W   | 0.592      | -            | -                | -                | -         |     4.56 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           61 |     2377 | 2024-05-06 | ALTERNATE aTTaX   | W   | 0.587      | -            | -                | -                | -         |     4.14 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           60 |     2391 | 2024-05-05 | Gaimin Gladiators | L   | 0.580      | -            | -                | -                | -         |   -14.03 | Cabbi, IceBerg, kwezz, Lucky, PR1mE   |
|           59 |     2399 | 2024-05-05 | Come on now dawg  | W   | 0.579      | -            | -                | -                | -         |     0.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           58 |     2451 | 2024-05-02 | fnatic            | W   | 0.560      | 0.384        | 0.371 (0.080)    | -                | -         |    15.05 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           57 |     2486 | 2024-05-01 | 3DMAX             | W   | 0.552      | 0.384        | 0.510 (0.108)    | 1.000 (0.212)    | -         |    16.04 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           56 |     2503 | 2024-04-30 | OG                | W   | 0.546      | 0.384        | 0.137 (0.029)    | -                | -         |     5.94 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           55 |     2528 | 2024-04-29 | 500               | W   | 0.538      | -            | -                | -                | -         |     1.29 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           54 |     2556 | 2024-04-27 | 777               | W   | 0.527      | -            | -                | -                | -         |     1.15 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           53 |     2560 | 2024-04-27 | JANO              | W   | 0.527      | -            | -                | -                | -         |     1.01 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           52 |     2627 | 2024-04-25 | Passion UA        | W   | 0.512      | 0.384        | 0.173 (0.034)    | 1.000 (0.197)    | -         |     4.99 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           51 |     2661 | 2024-04-23 | Gaimin Gladiators | W   | 0.499      | -            | -                | -                | -         |     4.90 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           50 |     2666 | 2024-04-23 | BLEED             | W   | 0.498      | -            | -                | -                | -         |     5.64 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           49 |     2717 | 2024-04-20 | Eternal Fire      | W   | 0.480      | 0.143        | 0.738 (0.051)    | -                | -         |    14.50 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           48 |     2724 | 2024-04-20 | Cloud9            | W   | 0.479      | -            | -                | -                | -         |     6.10 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           47 |     2763 | 2024-04-19 | Eternal Fire      | L   | 0.474      | -            | -                | -                | -         |    -0.58 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           46 |     2772 | 2024-04-19 | Cloud9            | W   | 0.472      | -            | -                | -                | -         |     5.98 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           45 |     2798 | 2024-04-18 | ex-Guild Eagles   | W   | 0.467      | -            | -                | -                | -         |     2.45 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           44 |     2802 | 2024-04-18 | RUBY              | W   | 0.467      | -            | -                | -                | -         |     4.03 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           43 |     2811 | 2024-04-18 | GamerLegion       | W   | 0.467      | -            | -                | -                | -         |     7.38 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           42 |     2855 | 2024-04-17 | Passion UA        | L   | 0.459      | -            | -                | -                | -         |    -8.78 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           41 |     2892 | 2024-04-16 | ex-Guild Eagles   | L   | 0.452      | -            | -                | -                | -         |   -12.15 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           40 |     2913 | 2024-04-15 | ex-Preasy         | W   | 0.445      | -            | -                | -                | -         |     2.04 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           39 |     2930 | 2024-04-14 | UNiTY             | W   | 0.438      | -            | -                | -                | -         |     3.79 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           38 |     2988 | 2024-04-11 | Enterprise        | W   | 0.418      | -            | -                | -                | -         |     3.15 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           37 |     3031 | 2024-04-10 | Passion UA        | L   | 0.412      | -            | -                | -                | -         |    -8.15 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           36 |     3164 | 2024-04-06 | UNiTY             | W   | 0.384      | -            | -                | -                | -         |     3.40 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           35 |     3221 | 2024-04-04 | UNiTY             | W   | 0.372      | -            | -                | -                | -         |     3.25 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           34 |     3305 | 2024-04-02 | Permitta          | W   | 0.358      | -            | -                | -                | -         |     3.57 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           33 |     3314 | 2024-04-01 | Nexus             | L   | 0.352      | -            | -                | -                | -         |    -9.21 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           32 |     3388 | 2024-03-27 | Rebels            | L   | 0.320      | -            | -                | -                | -         |    -7.06 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           31 |     3423 | 2024-03-25 | Nexus             | W   | 0.307      | -            | -                | -                | -         |     1.57 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           30 |     3447 | 2024-03-22 | Nemiga            | W   | 0.287      | 0.372        | 0.314 (0.034)    | -                | -         |     4.89 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           29 |     3512 | 2024-03-19 | RUBY              | W   | 0.267      | -            | -                | -                | -         |     2.07 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           28 |     3524 | 2024-03-18 | Insilio           | W   | 0.259      | -            | -                | -                | -         |     1.77 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           27 |     3592 | 2024-03-15 | ECLOT             | W   | 0.238      | -            | -                | -                | -         |     4.46 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           26 |     3666 | 2024-03-13 | BLEED             | L   | 0.225      | -            | -                | -                | -         |    -5.03 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           25 |     3713 | 2024-03-11 | Nemiga            | L   | 0.213      | -            | -                | -                | -         |    -3.03 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           24 |     3736 | 2024-03-10 | Sampi             | L   | 0.205      | -            | -                | -                | -         |    -5.21 | Cabbi, IceBerg, Kristou, Lucky, MistR |
|           23 |     3760 | 2024-03-09 | Permitta          | W   | 0.199      | -            | -                | -                | -         |     1.90 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           22 |     3781 | 2024-03-08 | ALTERNATE aTTaX   | L   | 0.191      | -            | -                | -                | -         |    -4.27 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           21 |     3791 | 2024-03-07 | Insilio           | W   | 0.188      | -            | -                | -                | -         |     1.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           20 |     3805 | 2024-03-07 | ex-sYnck          | W   | 0.186      | -            | -                | -                | -         |     0.15 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           19 |     3837 | 2024-03-06 | Alliance          | W   | 0.178      | -            | -                | -                | -         |     0.93 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           18 |     3871 | 2024-03-05 | Johnny Speeds     | L   | 0.173      | -            | -                | -                | -         |    -1.57 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           17 |     3880 | 2024-03-05 | ALTERNATE aTTaX   | L   | 0.172      | -            | -                | -                | -         |    -3.88 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           16 |     3896 | 2024-03-04 | Entropiq          | L   | 0.165      | -            | -                | -                | -         |    -5.01 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           15 |     3941 | 2024-03-02 | brazylijski luz   | W   | 0.152      | -            | -                | -                | -         |     0.57 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           14 |     3975 | 2024-02-29 | JANO              | W   | 0.138      | -            | -                | -                | -         |     0.29 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           13 |     3985 | 2024-02-28 | Sampi             | W   | 0.133      | -            | -                | -                | -         |     0.77 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           12 |     4000 | 2024-02-27 | V1dar             | L   | 0.127      | -            | -                | -                | -         |    -3.88 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           11 |     4041 | 2024-02-25 | Sangal            | L   | 0.114      | -            | -                | -                | -         |    -1.62 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           10 |     4047 | 2024-02-25 | PGE Turow         | L   | 0.112      | -            | -                | -                | -         |    -3.34 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            9 |     4087 | 2024-02-24 | MOUZ NXT          | L   | 0.105      | -            | -                | -                | -         |    -2.16 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            8 |     4138 | 2024-02-21 | Sampi             | W   | 0.085      | -            | -                | -                | -         |     0.48 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            7 |     4236 | 2024-02-17 | Zero Tenacity     | W   | 0.059      | -            | -                | -                | -         |     0.79 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            6 |     4384 | 2024-02-11 | ARCRED            | W   | 0.019      | -            | -                | -                | -         |     0.12 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            5 |     4386 | 2024-02-10 | Nemiga            | L   | 0.014      | -            | -                | -                | -         |    -0.22 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            4 |     4394 | 2024-02-10 | AMKAL             | W   | 0.013      | -            | -                | -                | -         |     0.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            3 |     4403 | 2024-02-09 | FORZE             | W   | 0.007      | -            | -                | -                | -         |     0.04 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            2 |     4409 | 2024-02-09 | Insilio           | W   | 0.006      | -            | -                | -                | -         |     0.04 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            1 |     4417 | 2024-02-08 | Nemiga            | L   | 0.001      | -            | -                | -                | -         |    -0.01 | Cabbi, IceBerg, kwezz, Lucky, MistR   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($58,762.73)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.18) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-07-13 |      1.000 | $3,216.00      | $3,216.00       |
| 2024-06-12 |      0.834 | $9,365.00      | $7,806.12       |
| 2024-06-09 |      0.813 | $8,000.00      | $6,503.33       |
| 2024-05-18 |      0.667 | $5,000.00      | $3,334.03       |
| 2024-05-09 |      0.605 | $14,000.00     | $8,475.83       |
| 2024-05-02 |      0.560 | $12,500.00     | $6,998.26       |
| 2024-04-27 |      0.527 | $6,375.00      | $3,361.93       |
| 2024-04-06 |      0.384 | $5,000.00      | $1,921.53       |
| 2024-03-25 |      0.307 | $7,000.00      | $2,145.69       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
