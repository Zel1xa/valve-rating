### Roster Details<br />
Team Name: MOUZ NXT<br />
Roster: Burmylov, Chr1zN, Neityu, PR, sirah<br />
Global Rank: [42](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [30]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1106.9<br />
<br />
Final Rank Value (1106.9) = Starting Rank Value (1034.2) + Head To Head Adjustments (72.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.539[<sup>1</sup>](#table2)
- Bounty Collected: 0.456[<sup>2</sup>](#table1)
- Opponent Network: 0.245[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.310<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1034.2
- 400 + ( ( 0.310 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1034.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           88 |      181 | 2024-07-29 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.86 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           87 |      185 | 2024-07-29 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.62 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           86 |      240 | 2024-07-27 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -6.40 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           85 |      315 | 2024-07-25 | Aurora Young Blud | W   | 1.000      | 0.435        | -                | 0.433 (0.188)    | 0 (0.000) |     8.38 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           84 |      435 | 2024-07-21 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -6.80 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           83 |      475 | 2024-07-20 | BLEED             | W   | 1.000      | 0.500        | 0.126 (0.063)    | 0.534 (0.267)    | 0 (0.000) |    24.83 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           82 |      489 | 2024-07-19 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.036)    | 0.418 (0.209)    | 0 (0.000) |    12.26 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           81 |      539 | 2024-07-18 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -1.85 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           80 |      679 | 2024-07-16 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.036)    | 0.418 (0.209)    | 0 (0.000) |    12.76 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           79 |     1035 | 2024-06-13 | B8                | L   | 0.858      | -            | -                | -                | -         |   -11.00 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           78 |     1092 | 2024-06-10 | Endpoint          | L   | 0.839      | -            | -                | -                | -         |   -20.27 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           77 |     1126 | 2024-06-09 | GhoulsW           | W   | 0.833      | -            | -                | -                | 0 (0.000) |     0.55 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           76 |     1146 | 2024-06-09 | BLEED             | L   | 0.832      | -            | -                | -                | -         |    -4.58 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           75 |     1210 | 2024-06-08 | ECLOT             | L   | 0.825      | -            | -                | -                | -         |   -11.10 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           74 |     1238 | 2024-06-07 | GamerLegion       | L   | 0.820      | -            | -                | -                | -         |   -10.45 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           73 |     1303 | 2024-06-06 | Rhyno             | W   | 0.814      | 0.500        | 0.071 (0.029)    | -                | 0 (0.000) |     8.65 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           72 |     1332 | 2024-06-06 | Entropiq          | W   | 0.812      | -            | -                | -                | 0 (0.000) |     0.49 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           71 |     1429 | 2024-06-04 | NAVI Junior       | W   | 0.799      | -            | -                | -                | 0 (0.000) |     1.18 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           70 |     1436 | 2024-06-04 | Aurora Young Blud | W   | 0.798      | -            | -                | -                | -         |     4.19 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           69 |     1473 | 2024-06-02 | FURIA             | L   | 0.785      | -            | -                | -                | -         |    -1.48 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           68 |     1506 | 2024-06-01 | AMKAL             | W   | 0.779      | 0.435        | 0.130 (0.044)    | -                | -         |    15.67 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           67 |     1565 | 2024-05-30 | Sangal            | W   | 0.764      | 0.435        | 0.219 (0.073)    | 0.823 (0.273)    | -         |    13.39 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           66 |     1606 | 2024-05-28 | RUBY              | W   | 0.753      | 0.435        | 0.095 (0.031)    | 0.520 (0.170)    | -         |     8.09 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           65 |     1633 | 2024-05-27 | Nexus             | W   | 0.744      | -            | -                | -                | -         |     4.13 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           64 |     1641 | 2024-05-26 | 9 Pandas          | L   | 0.740      | -            | -                | -                | -         |   -11.71 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           63 |     1648 | 2024-05-26 | B8                | W   | 0.738      | 0.435        | 0.166 (0.053)    | 0.945 (0.303)    | -         |    15.21 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           62 |     1673 | 2024-05-25 | 3DMAX             | W   | 0.731      | 0.435        | 0.504 (0.160)    | 1.000 (0.318)    | -         |    21.80 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           61 |     1686 | 2024-05-24 | Illuminar         | W   | 0.724      | -            | -                | -                | -         |     6.64 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           60 |     1699 | 2024-05-23 | Rare Atom         | W   | 0.718      | -            | -                | -                | -         |     3.10 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           59 |     1739 | 2024-05-22 | Rhyno             | L   | 0.712      | -            | -                | -                | -         |   -12.64 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           58 |     1781 | 2024-05-21 | DMS               | L   | 0.705      | -            | -                | -                | -         |   -15.02 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           57 |     1849 | 2024-05-19 | BLEED             | L   | 0.691      | -            | -                | -                | -         |    -2.99 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           56 |     1915 | 2024-05-17 | DMS               | W   | 0.678      | -            | -                | -                | -         |     6.71 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           55 |     1940 | 2024-05-16 | Sampi             | W   | 0.673      | 0.435        | -                | 1.000 (0.292)    | -         |     7.19 | Chr1zN, Neityu, PR, sirah, TOBIZ       |
|           54 |     2003 | 2024-05-15 | BLEED             | L   | 0.664      | -            | -                | -                | -         |    -2.28 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           53 |     2056 | 2024-05-14 | B8                | L   | 0.658      | -            | -                | -                | -         |    -8.90 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           52 |     2080 | 2024-05-13 | Space             | W   | 0.651      | -            | -                | -                | -         |     4.80 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           51 |     2102 | 2024-05-12 | B8                | L   | 0.645      | -            | -                | -                | -         |    -9.60 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           50 |     2116 | 2024-05-11 | Endpoint          | W   | 0.640      | -            | -                | -                | -         |     7.31 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           49 |     2142 | 2024-05-10 | Aurora            | W   | 0.634      | 0.435        | 0.425 (0.117)    | 0.809 (0.223)    | -         |    19.13 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           48 |     2211 | 2024-05-07 | RUSH B            | W   | 0.612      | -            | -                | -                | -         |     5.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           47 |     2254 | 2024-05-05 | GL Academy        | W   | 0.598      | -            | -                | -                | -         |     3.54 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           46 |     2256 | 2024-05-04 | Enterprise        | L   | 0.594      | -            | -                | -                | -         |   -12.98 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           45 |     2275 | 2024-05-03 | Nemiga            | L   | 0.586      | -            | -                | -                | -         |    -6.06 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           44 |     2295 | 2024-05-02 | Endpoint          | L   | 0.580      | -            | -                | -                | -         |   -12.09 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           43 |     2308 | 2024-05-02 | ALTERNATE aTTaX   | W   | 0.579      | -            | -                | -                | -         |     7.48 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           42 |     2314 | 2024-05-02 | 9 Pandas          | L   | 0.578      | -            | -                | -                | -         |   -11.08 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           41 |     2329 | 2024-05-01 | BLEED             | W   | 0.572      | -            | -                | -                | -         |     9.88 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           40 |     2341 | 2024-04-30 | ECLOT             | W   | 0.567      | -            | -                | -                | -         |    12.56 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           39 |     2352 | 2024-04-30 | V1dar             | W   | 0.565      | -            | -                | -                | -         |     1.05 | Burmylov, Chr1zN, PR, sirah, TOBIZ     |
|           38 |     2364 | 2024-04-29 | Nemiga            | L   | 0.560      | -            | -                | -                | -         |    -6.17 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           37 |     2377 | 2024-04-29 | Grannys Knockers  | W   | 0.558      | -            | -                | -                | -         |     3.28 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           36 |     2405 | 2024-04-27 | ECLOT             | W   | 0.547      | -            | -                | -                | -         |    12.52 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           35 |     2476 | 2024-04-25 | Insilio           | L   | 0.531      | -            | -                | -                | -         |   -10.95 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           34 |     2487 | 2024-04-24 | PARIVISION        | L   | 0.526      | -            | -                | -                | -         |    -7.88 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           33 |     2521 | 2024-04-22 | EYEBALLERS        | W   | 0.513      | -            | -                | -                | -         |     4.82 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           32 |     2529 | 2024-04-22 | Nemiga            | L   | 0.511      | -            | -                | -                | -         |    -5.64 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           31 |     2538 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.506      | -            | -                | -                | -         |     5.97 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           30 |     2545 | 2024-04-21 | ECLOT             | L   | 0.505      | -            | -                | -                | -         |    -4.71 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           29 |     2566 | 2024-04-20 | BLEED             | L   | 0.499      | -            | -                | -                | -         |    -8.40 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           28 |     2664 | 2024-04-18 | Enterprise        | W   | 0.486      | -            | -                | -                | -         |     5.21 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           27 |     2674 | 2024-04-18 | ENCE Academy      | W   | 0.485      | -            | -                | -                | -         |     2.42 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           26 |     2723 | 2024-04-17 | JANO              | W   | 0.477      | -            | -                | -                | -         |     1.81 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           25 |     2737 | 2024-04-16 | GamerLegion       | L   | 0.472      | -            | -                | -                | -         |    -5.86 | Anlelele, Burmylov, Neityu, PR, sirah  |
|           24 |     2762 | 2024-04-15 | Alliance          | W   | 0.464      | -            | -                | -                | -         |     3.84 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           23 |     2802 | 2024-04-12 | Permitta          | L   | 0.445      | -            | -                | -                | -         |    -8.67 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           22 |     2929 | 2024-04-09 | Zero Tenacity     | W   | 0.426      | -            | -                | -                | -         |     7.39 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           21 |     2964 | 2024-04-08 | B8                | W   | 0.419      | -            | -                | -                | -         |     7.30 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           20 |     3088 | 2024-04-03 | PARIVISION        | W   | 0.387      | -            | -                | -                | -         |     7.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           19 |     3414 | 2024-03-16 | Sampi             | L   | 0.264      | -            | -                | -                | -         |    -5.61 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           18 |     3431 | 2024-03-15 | Entropiq          | W   | 0.259      | -            | -                | -                | -         |     0.56 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           17 |     3482 | 2024-03-13 | Permitta          | L   | 0.247      | -            | -                | -                | -         |    -4.66 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           16 |     3499 | 2024-03-13 | Alliance          | W   | 0.245      | -            | -                | -                | -         |     2.16 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           15 |     3525 | 2024-03-12 | AURA              | W   | 0.239      | -            | -                | -                | -         |     0.36 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           14 |     3532 | 2024-03-12 | Sampi             | L   | 0.238      | -            | -                | -                | -         |    -5.17 | Burmylov, Chr1zN, Neityu, sirah, xReal |
|           13 |     3552 | 2024-03-11 | Passion UA        | W   | 0.232      | -            | -                | -                | -         |     4.06 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           12 |     3554 | 2024-03-11 | NOM               | W   | 0.231      | -            | -                | -                | -         |     0.35 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           11 |     3560 | 2024-03-10 | V1dar             | W   | 0.227      | -            | -                | -                | -         |     0.39 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           10 |     3572 | 2024-03-10 | Passion UA        | L   | 0.226      | -            | -                | -                | -         |    -3.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            9 |     3576 | 2024-03-10 | ALTERNATE aTTaX   | W   | 0.225      | -            | -                | -                | -         |     3.06 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            8 |     3613 | 2024-03-08 | Fraud5            | W   | 0.213      | -            | -                | -                | -         |     0.70 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            7 |     3630 | 2024-03-07 | INGLORIOUS        | L   | 0.207      | -            | -                | -                | -         |    -6.15 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            6 |     3764 | 2024-03-03 | ex-Preasy         | W   | 0.178      | -            | -                | -                | -         |     1.08 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            5 |     3777 | 2024-03-02 | kONO              | W   | 0.172      | -            | -                | -                | -         |     1.19 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            4 |     3847 | 2024-02-27 | ECLOT             | L   | 0.146      | -            | -                | -                | -         |    -1.22 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            3 |     3862 | 2024-02-26 | BLEED             | W   | 0.139      | -            | -                | -                | -         |     1.73 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            2 |     3925 | 2024-02-24 | Sashi             | W   | 0.124      | -            | -                | -                | -         |     2.64 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            1 |     3987 | 2024-02-21 | Entropiq          | W   | 0.104      | -            | -                | -                | -         |     0.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($45,375.51)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-02 |      0.786 | $5,000.00      | $3,930.79       |
| 2024-05-26 |      0.740 | $10,000.00     | $7,397.69       |
| 2024-05-18 |      0.687 | $500.00        | $343.36         |
| 2024-05-12 |      0.647 | $5,000.00      | $3,233.22       |
| 2024-05-03 |      0.586 | $25,000.00     | $14,653.94      |
| 2024-03-18 |      0.278 | $1,000.00      | $277.82         |
| 2024-03-11 |      0.232 | $3,500.00      | $811.97         |
| 2024-02-28 |      0.151 | $1,500.00      | $226.74         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
