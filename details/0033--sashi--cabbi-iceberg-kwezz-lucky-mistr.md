### Roster Details<br />
Team Name: Sashi<br />
Roster: Cabbi, IceBerg, kwezz, Lucky, MistR<br />
Global Rank: [33](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [24]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1176.1<br />
<br />
Final Rank Value (1176.1) = Starting Rank Value (1161.0) + Head To Head Adjustments (15.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.577[<sup>1</sup>](#table2)
- Bounty Collected: 0.459[<sup>2</sup>](#table1)
- Opponent Network: 0.246[<sup>2</sup>](#table1)
- LAN Wins: 0.206[<sup>2</sup>](#table1)

The average of these factors is 0.372<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1161.0
- 400 + ( ( 0.372 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1161.0


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
|           92 |      110 | 2024-07-31 | Insilio           | W   | 1.000      | 0.500        | -                | 0.581 (0.290)    | 0 (0.000) |     6.82 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           91 |      141 | 2024-07-30 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.528 (0.264)    | 0 (0.000) |     3.17 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           90 |      154 | 2024-07-30 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -17.94 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           89 |      334 | 2024-07-24 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.639 (0.319)    | 0 (0.000) |     9.83 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           88 |      555 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |    -3.03 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           87 |      565 | 2024-07-18 | JiJieHao          | W   | 1.000      | 1.000        | 0.031 (0.031)    | -                | 1 (1.000) |     1.25 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           86 |      755 | 2024-07-13 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -22.64 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           85 |      764 | 2024-07-12 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.44 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           84 |      780 | 2024-07-11 | Endpoint          | W   | 1.000      | 0.358        | -                | 0.540 (0.193)    | 0 (0.000) |     4.77 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           83 |      804 | 2024-07-10 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -14.02 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           82 |      807 | 2024-07-10 | 9INE              | W   | 1.000      | 0.358        | -                | 0.553 (0.198)    | 0 (0.000) |     5.40 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           81 |      991 | 2024-06-14 | 3DMAX             | L   | 0.866      | -            | -                | -                | -         |    -6.17 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           80 |     1026 | 2024-06-13 | Sampi             | W   | 0.859      | -            | -                | -                | 0 (0.000) |     3.51 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           79 |     1042 | 2024-06-12 | CPH Wolves        | W   | 0.853      | -            | -                | -                | 0 (0.000) |     2.47 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           78 |     1050 | 2024-06-12 | Astralis Talent   | W   | 0.853      | -            | -                | -                | -         |     1.94 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           77 |     1297 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.814      | -            | -                | -                | -         |    -3.31 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           76 |     1334 | 2024-06-06 | HEROIC            | L   | 0.812      | -            | -                | -                | -         |    -3.30 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           75 |     1362 | 2024-06-05 | ENCE              | L   | 0.807      | -            | -                | -                | -         |    -8.79 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           74 |     1383 | 2024-06-05 | Astralis          | W   | 0.806      | 0.715        | 0.353 (0.204)    | 0.396 (0.228)    | 1 (0.806) |    23.98 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           73 |     1393 | 2024-06-05 | The MongolZ       | L   | 0.805      | -            | -                | -                | -         |    -0.48 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           72 |     1824 | 2024-05-20 | Monte             | L   | 0.698      | -            | -                | -                | -         |   -16.22 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           71 |     1836 | 2024-05-19 | Passion UA        | W   | 0.693      | 0.500        | 0.172 (0.060)    | 1.000 (0.346)    | -         |     5.71 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           70 |     1863 | 2024-05-18 | B8                | L   | 0.687      | -            | -                | -                | -         |   -12.91 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           69 |     1872 | 2024-05-18 | Monte             | W   | 0.686      | -            | -                | -                | -         |     5.41 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           68 |     1880 | 2024-05-18 | ALTERNATE aTTaX   | W   | 0.684      | 0.500        | -                | 0.580 (0.199)    | -         |     3.90 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           67 |     1911 | 2024-05-17 | ex-Guild Eagles   | W   | 0.678      | -            | -                | -                | -         |     2.40 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           66 |     1951 | 2024-05-16 | Passion UA        | L   | 0.671      | -            | -                | -                | -         |   -16.08 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           65 |     1998 | 2024-05-15 | Endpoint          | W   | 0.665      | -            | -                | -                | -         |     3.55 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           64 |     2170 | 2024-05-09 | 1WIN              | W   | 0.625      | -            | -                | -                | -         |     3.73 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           63 |     2192 | 2024-05-08 | Grannys Knockers  | W   | 0.619      | -            | -                | -                | -         |     1.69 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           62 |     2210 | 2024-05-07 | 9 Pandas          | W   | 0.612      | -            | -                | -                | -         |     4.59 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           61 |     2224 | 2024-05-06 | ALTERNATE aTTaX   | W   | 0.606      | -            | -                | -                | -         |     4.15 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           60 |     2238 | 2024-05-05 | Gaimin Gladiators | L   | 0.600      | -            | -                | -                | -         |   -14.42 | Cabbi, IceBerg, kwezz, Lucky, PR1mE   |
|           59 |     2246 | 2024-05-05 | Come on now dawg  | W   | 0.599      | -            | -                | -                | -         |     0.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           58 |     2298 | 2024-05-02 | fnatic            | W   | 0.580      | 0.384        | 0.290 (0.065)    | -                | -         |    12.49 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           57 |     2333 | 2024-05-01 | 3DMAX             | W   | 0.572      | 0.384        | 0.504 (0.111)    | 1.000 (0.220)    | -         |    16.46 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           56 |     2350 | 2024-04-30 | OG                | W   | 0.566      | 0.384        | 0.140 (0.030)    | -                | -         |     5.97 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           55 |     2375 | 2024-04-29 | 500               | W   | 0.558      | -            | -                | -                | -         |     1.31 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           54 |     2403 | 2024-04-27 | 777               | W   | 0.547      | -            | -                | -                | -         |     1.14 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           53 |     2407 | 2024-04-27 | JANO              | W   | 0.547      | -            | -                | -                | -         |     1.02 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           52 |     2473 | 2024-04-25 | Passion UA        | W   | 0.532      | 0.384        | 0.172 (0.035)    | 1.000 (0.204)    | -         |     4.86 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           51 |     2507 | 2024-04-23 | Gaimin Gladiators | W   | 0.519      | -            | -                | -                | -         |     5.20 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           50 |     2512 | 2024-04-23 | BLEED             | W   | 0.518      | -            | -                | -                | -         |     5.82 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           49 |     2563 | 2024-04-20 | Eternal Fire      | W   | 0.500      | 0.143        | 0.746 (0.053)    | -                | -         |    15.10 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           48 |     2570 | 2024-04-20 | Cloud9            | W   | 0.499      | -            | -                | -                | -         |     6.46 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           47 |     2609 | 2024-04-19 | Eternal Fire      | L   | 0.493      | -            | -                | -                | -         |    -0.60 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           46 |     2618 | 2024-04-19 | Cloud9            | W   | 0.492      | -            | -                | -                | -         |     6.35 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           45 |     2644 | 2024-04-18 | ex-Guild Eagles   | W   | 0.487      | -            | -                | -                | -         |     2.52 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           44 |     2648 | 2024-04-18 | RUBY              | W   | 0.487      | -            | -                | -                | -         |     4.16 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           43 |     2657 | 2024-04-18 | GamerLegion       | W   | 0.486      | -            | -                | -                | -         |     7.68 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           42 |     2701 | 2024-04-17 | Passion UA        | L   | 0.479      | -            | -                | -                | -         |    -9.42 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           41 |     2738 | 2024-04-16 | ex-Guild Eagles   | L   | 0.472      | -            | -                | -                | -         |   -12.71 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           40 |     2759 | 2024-04-15 | ex-Preasy         | W   | 0.465      | -            | -                | -                | -         |     2.17 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           39 |     2776 | 2024-04-14 | UNiTY             | W   | 0.458      | -            | -                | -                | -         |     3.88 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           38 |     2834 | 2024-04-11 | Enterprise        | W   | 0.438      | -            | -                | -                | -         |     3.26 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           37 |     2877 | 2024-04-10 | Passion UA        | L   | 0.432      | -            | -                | -                | -         |    -8.79 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           36 |     3010 | 2024-04-06 | UNiTY             | W   | 0.404      | -            | -                | -                | -         |     3.52 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           35 |     3067 | 2024-04-04 | UNiTY             | W   | 0.392      | -            | -                | -                | -         |     3.36 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           34 |     3151 | 2024-04-02 | Permitta          | W   | 0.378      | -            | -                | -                | -         |     3.29 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           33 |     3160 | 2024-04-01 | Nexus             | L   | 0.371      | -            | -                | -                | -         |    -9.78 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           32 |     3266 | 2024-03-25 | Nexus             | W   | 0.326      | -            | -                | -                | -         |     1.68 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           31 |     3288 | 2024-03-22 | Nemiga            | W   | 0.307      | 0.372        | 0.318 (0.036)    | -                | -         |     5.04 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           30 |     3353 | 2024-03-19 | RUBY              | W   | 0.287      | -            | -                | -                | -         |     2.25 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           29 |     3365 | 2024-03-18 | Insilio           | W   | 0.279      | -            | -                | -                | -         |     1.91 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           28 |     3432 | 2024-03-15 | ECLOT             | W   | 0.258      | -            | -                | -                | -         |     4.87 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           27 |     3505 | 2024-03-13 | BLEED             | L   | 0.245      | -            | -                | -                | -         |    -5.41 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           26 |     3551 | 2024-03-11 | Nemiga            | L   | 0.233      | -            | -                | -                | -         |    -3.45 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           25 |     3574 | 2024-03-10 | Sampi             | L   | 0.225      | -            | -                | -                | -         |    -5.68 | Cabbi, IceBerg, Kristou, Lucky, MistR |
|           24 |     3598 | 2024-03-09 | Permitta          | W   | 0.219      | -            | -                | -                | -         |     1.85 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           23 |     3619 | 2024-03-08 | ALTERNATE aTTaX   | L   | 0.211      | -            | -                | -                | -         |    -4.72 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           22 |     3629 | 2024-03-07 | Insilio           | W   | 0.207      | -            | -                | -                | -         |     1.32 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           21 |     3643 | 2024-03-07 | ex-sYnck          | W   | 0.206      | -            | -                | -                | -         |     0.17 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           20 |     3676 | 2024-03-06 | Alliance          | W   | 0.198      | -            | -                | -                | -         |     1.06 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           19 |     3709 | 2024-03-05 | Johnny Speeds     | L   | 0.193      | -            | -                | -                | -         |    -1.81 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           18 |     3718 | 2024-03-05 | ALTERNATE aTTaX   | L   | 0.191      | -            | -                | -                | -         |    -4.34 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           17 |     3734 | 2024-03-04 | Entropiq          | L   | 0.184      | -            | -                | -                | -         |    -5.61 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           16 |     3779 | 2024-03-02 | brazylijski luz   | W   | 0.172      | -            | -                | -                | -         |     0.64 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           15 |     3813 | 2024-02-29 | JANO              | W   | 0.158      | -            | -                | -                | -         |     0.34 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           14 |     3823 | 2024-02-28 | Sampi             | W   | 0.153      | -            | -                | -                | -         |     0.91 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           13 |     3838 | 2024-02-27 | V1dar             | L   | 0.147      | -            | -                | -                | -         |    -4.49 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           12 |     3879 | 2024-02-25 | Sangal            | L   | 0.134      | -            | -                | -                | -         |    -2.12 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           11 |     3885 | 2024-02-25 | PGE Turow         | L   | 0.132      | -            | -                | -                | -         |    -3.93 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           10 |     3925 | 2024-02-24 | MOUZ NXT          | L   | 0.124      | -            | -                | -                | -         |    -2.64 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            9 |     3976 | 2024-02-21 | Sampi             | W   | 0.105      | -            | -                | -                | -         |     0.59 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            8 |     4073 | 2024-02-17 | Zero Tenacity     | W   | 0.079      | -            | -                | -                | -         |     1.04 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            7 |     4221 | 2024-02-11 | ARCRED            | W   | 0.039      | -            | -                | -                | -         |     0.20 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            6 |     4223 | 2024-02-10 | Nemiga            | L   | 0.034      | -            | -                | -                | -         |    -0.55 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            5 |     4231 | 2024-02-10 | AMKAL             | W   | 0.033      | -            | -                | -                | -         |     0.50 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            4 |     4239 | 2024-02-09 | FORZE             | W   | 0.027      | -            | -                | -                | -         |     0.15 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            3 |     4246 | 2024-02-09 | Insilio           | W   | 0.026      | -            | -                | -                | -         |     0.15 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            2 |     4254 | 2024-02-08 | Nemiga            | L   | 0.020      | -            | -                | -                | -         |    -0.33 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            1 |     4258 | 2024-02-08 | FORZE             | W   | 0.019      | -            | -                | -                | -         |     0.11 | Cabbi, IceBerg, kwezz, Lucky, MistR   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($60,101.30)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.18) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-07-13 |      1.000 | $3,216.00      | $3,216.00       |
| 2024-06-12 |      0.853 | $9,365.00      | $7,992.55       |
| 2024-06-09 |      0.833 | $8,000.00      | $6,662.59       |
| 2024-05-18 |      0.687 | $5,000.00      | $3,433.56       |
| 2024-05-09 |      0.625 | $14,000.00     | $8,754.54       |
| 2024-05-02 |      0.580 | $12,500.00     | $7,247.11       |
| 2024-04-27 |      0.547 | $6,375.00      | $3,488.84       |
| 2024-04-06 |      0.404 | $5,000.00      | $2,021.06       |
| 2024-03-25 |      0.326 | $7,000.00      | $2,285.05       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
