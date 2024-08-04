### Roster Details<br />
Team Name: MOUZ NXT<br />
Roster: Burmylov, Chr1zN, Neityu, PR, sirah<br />
Global Rank: [40](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [29]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1117.3<br />
<br />
Final Rank Value (1117.3) = Starting Rank Value (1040.9) + Head To Head Adjustments (76.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.539[<sup>1</sup>](#table2)
- Bounty Collected: 0.456[<sup>2</sup>](#table1)
- Opponent Network: 0.260[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.314<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1040.9
- 400 + ( ( 0.314 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1040.9


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
|           89 |      207 | 2024-07-29 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.59 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           88 |      211 | 2024-07-29 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.58 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           87 |      266 | 2024-07-27 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.11 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           86 |      342 | 2024-07-25 | Aurora Young Blud | W   | 1.000      | 0.435        | -                | 0.420 (0.182)    | 0 (0.000) |     7.74 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           85 |      461 | 2024-07-21 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.23 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           84 |      501 | 2024-07-20 | BLEED             | W   | 1.000      | 0.500        | 0.126 (0.063)    | 0.517 (0.258)    | 0 (0.000) |    24.56 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           83 |      515 | 2024-07-19 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.036)    | 0.404 (0.202)    | 0 (0.000) |    11.95 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           82 |      568 | 2024-07-18 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -1.67 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           81 |      708 | 2024-07-16 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.036)    | 0.404 (0.202)    | 0 (0.000) |    12.40 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           80 |     1089 | 2024-06-13 | B8                | L   | 0.853      | -            | -                | -                | -         |   -11.19 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           79 |     1150 | 2024-06-10 | Endpoint          | L   | 0.834      | -            | -                | -                | -         |   -20.40 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           78 |     1186 | 2024-06-09 | GhoulsW           | W   | 0.828      | -            | -                | -                | 0 (0.000) |     0.53 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           77 |     1205 | 2024-06-09 | BLEED             | L   | 0.827      | -            | -                | -                | -         |    -4.80 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           76 |     1262 | 2024-06-08 | Sampi             | W   | 0.821      | 0.435        | -                | 1.000 (0.357)    | 0 (0.000) |     6.57 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           75 |     1274 | 2024-06-08 | ECLOT             | L   | 0.821      | -            | -                | -                | -         |   -11.15 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           74 |     1302 | 2024-06-07 | GamerLegion       | L   | 0.816      | -            | -                | -                | -         |   -10.35 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           73 |     1367 | 2024-06-06 | Rhyno             | W   | 0.809      | 0.500        | 0.071 (0.029)    | -                | 0 (0.000) |     8.52 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           72 |     1396 | 2024-06-06 | Entropiq          | W   | 0.807      | -            | -                | -                | 0 (0.000) |     0.48 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           71 |     1494 | 2024-06-04 | NAVI Junior       | W   | 0.794      | -            | -                | -                | -         |     1.16 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           70 |     1501 | 2024-06-04 | Aurora Young Blud | W   | 0.793      | -            | -                | -                | -         |     4.11 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           69 |     1539 | 2024-06-02 | FURIA             | L   | 0.781      | -            | -                | -                | -         |    -1.45 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           68 |     1573 | 2024-06-01 | AMKAL             | W   | 0.774      | 0.435        | 0.130 (0.044)    | -                | -         |    15.57 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           67 |     1632 | 2024-05-30 | Sangal            | W   | 0.760      | 0.435        | 0.219 (0.072)    | 0.862 (0.284)    | -         |    13.93 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           66 |     1673 | 2024-05-28 | RUBY              | W   | 0.748      | 0.435        | 0.095 (0.031)    | -                | -         |     7.93 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           65 |     1700 | 2024-05-27 | Nexus             | W   | 0.740      | -            | -                | -                | -         |     4.05 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           64 |     1708 | 2024-05-26 | 9 Pandas          | L   | 0.735      | -            | -                | -                | -         |   -11.81 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           63 |     1716 | 2024-05-26 | B8                | W   | 0.733      | 0.435        | 0.165 (0.053)    | 0.912 (0.291)    | -         |    15.09 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           62 |     1741 | 2024-05-25 | 3DMAX             | W   | 0.726      | 0.435        | 0.506 (0.160)    | 1.000 (0.316)    | -         |    21.69 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           61 |     1754 | 2024-05-24 | Illuminar         | W   | 0.720      | -            | -                | -                | -         |     6.50 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           60 |     1767 | 2024-05-23 | Rare Atom         | W   | 0.714      | -            | -                | -                | -         |     3.08 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           59 |     1807 | 2024-05-22 | Rhyno             | L   | 0.707      | -            | -                | -                | -         |   -12.65 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           58 |     1849 | 2024-05-21 | DMS               | L   | 0.701      | -            | -                | -                | -         |   -14.97 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           57 |     1918 | 2024-05-19 | BLEED             | L   | 0.686      | -            | -                | -                | -         |    -3.06 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           56 |     1984 | 2024-05-17 | DMS               | W   | 0.673      | -            | -                | -                | -         |     6.61 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           55 |     2009 | 2024-05-16 | Sampi             | W   | 0.668      | 0.435        | -                | 1.000 (0.290)    | -         |     7.01 | Chr1zN, Neityu, PR, sirah, TOBIZ       |
|           54 |     2072 | 2024-05-15 | BLEED             | L   | 0.660      | -            | -                | -                | -         |    -2.35 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           53 |     2125 | 2024-05-14 | B8                | L   | 0.653      | -            | -                | -                | -         |    -8.85 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           52 |     2149 | 2024-05-13 | Space             | W   | 0.646      | -            | -                | -                | -         |     4.65 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           51 |     2171 | 2024-05-12 | B8                | L   | 0.640      | -            | -                | -                | -         |    -9.54 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           50 |     2185 | 2024-05-11 | Endpoint          | W   | 0.636      | -            | -                | -                | -         |     7.12 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           49 |     2211 | 2024-05-10 | Aurora            | W   | 0.629      | 0.435        | 0.424 (0.116)    | 0.793 (0.217)    | -         |    18.96 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           48 |     2281 | 2024-05-07 | RUSH B            | W   | 0.608      | -            | -                | -                | -         |     5.23 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           47 |     2324 | 2024-05-05 | GL Academy        | W   | 0.593      | -            | -                | -                | -         |     3.46 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           46 |     2326 | 2024-05-04 | Enterprise        | L   | 0.589      | -            | -                | -                | -         |   -12.98 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           45 |     2345 | 2024-05-03 | Nemiga            | L   | 0.581      | -            | -                | -                | -         |    -6.12 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           44 |     2365 | 2024-05-02 | Endpoint          | L   | 0.576      | -            | -                | -                | -         |   -12.13 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           43 |     2378 | 2024-05-02 | ALTERNATE aTTaX   | W   | 0.574      | -            | -                | -                | -         |     7.31 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           42 |     2384 | 2024-05-02 | 9 Pandas          | L   | 0.573      | -            | -                | -                | -         |   -11.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           41 |     2399 | 2024-05-01 | BLEED             | W   | 0.567      | -            | -                | -                | -         |     9.68 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           40 |     2411 | 2024-04-30 | ECLOT             | W   | 0.562      | -            | -                | -                | -         |    12.32 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           39 |     2422 | 2024-04-30 | V1dar             | W   | 0.561      | -            | -                | -                | -         |     1.01 | Burmylov, Chr1zN, PR, sirah, TOBIZ     |
|           38 |     2434 | 2024-04-29 | Nemiga            | L   | 0.556      | -            | -                | -                | -         |    -6.24 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           37 |     2447 | 2024-04-29 | Grannys Knockers  | W   | 0.553      | -            | -                | -                | -         |     3.18 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           36 |     2475 | 2024-04-27 | ECLOT             | W   | 0.542      | -            | -                | -                | -         |    12.28 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           35 |     2547 | 2024-04-25 | Insilio           | L   | 0.526      | -            | -                | -                | -         |   -11.01 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           34 |     2558 | 2024-04-24 | PARIVISION        | L   | 0.521      | -            | -                | -                | -         |    -7.96 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           33 |     2592 | 2024-04-22 | EYEBALLERS        | W   | 0.508      | -            | -                | -                | -         |     4.70 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           32 |     2600 | 2024-04-22 | Nemiga            | L   | 0.506      | -            | -                | -                | -         |    -5.72 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           31 |     2609 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.501      | -            | -                | -                | -         |     5.80 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           30 |     2616 | 2024-04-21 | ECLOT             | L   | 0.500      | -            | -                | -                | -         |    -4.81 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           29 |     2637 | 2024-04-20 | BLEED             | L   | 0.495      | -            | -                | -                | -         |    -8.43 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           28 |     2735 | 2024-04-18 | Enterprise        | W   | 0.481      | -            | -                | -                | -         |     5.02 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           27 |     2745 | 2024-04-18 | ENCE Academy      | W   | 0.480      | -            | -                | -                | -         |     2.22 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           26 |     2794 | 2024-04-17 | JANO              | W   | 0.472      | -            | -                | -                | -         |     1.75 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           25 |     2808 | 2024-04-16 | GamerLegion       | L   | 0.468      | -            | -                | -                | -         |    -5.89 | Anlelele, Burmylov, Neityu, PR, sirah  |
|           24 |     2833 | 2024-04-15 | Alliance          | W   | 0.460      | -            | -                | -                | -         |     3.68 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           23 |     2873 | 2024-04-12 | Permitta          | L   | 0.440      | -            | -                | -                | -         |    -8.69 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           22 |     3000 | 2024-04-09 | Zero Tenacity     | W   | 0.421      | -            | -                | -                | -         |     7.21 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           21 |     3035 | 2024-04-08 | B8                | W   | 0.414      | -            | -                | -                | -         |     7.08 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           20 |     3159 | 2024-04-03 | PARIVISION        | W   | 0.382      | -            | -                | -                | -         |     7.10 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           19 |     3490 | 2024-03-16 | Sampi             | L   | 0.260      | -            | -                | -                | -         |    -5.60 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           18 |     3508 | 2024-03-15 | Entropiq          | W   | 0.254      | -            | -                | -                | -         |     0.53 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           17 |     3559 | 2024-03-13 | Permitta          | L   | 0.243      | -            | -                | -                | -         |    -4.64 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           16 |     3577 | 2024-03-13 | Alliance          | W   | 0.240      | -            | -                | -                | -         |     2.04 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           15 |     3604 | 2024-03-12 | AURA              | W   | 0.235      | -            | -                | -                | -         |     0.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           14 |     3611 | 2024-03-12 | Sampi             | L   | 0.233      | -            | -                | -                | -         |    -5.15 | Burmylov, Chr1zN, Neityu, sirah, xReal |
|           13 |     3631 | 2024-03-11 | Passion UA        | W   | 0.227      | -            | -                | -                | -         |     3.90 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           12 |     3633 | 2024-03-11 | NOM               | W   | 0.226      | -            | -                | -                | -         |     0.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           11 |     3639 | 2024-03-10 | V1dar             | W   | 0.222      | -            | -                | -                | -         |     0.37 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           10 |     3651 | 2024-03-10 | Passion UA        | L   | 0.221      | -            | -                | -                | -         |    -3.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            9 |     3655 | 2024-03-10 | ALTERNATE aTTaX   | W   | 0.220      | -            | -                | -                | -         |     2.93 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            8 |     3692 | 2024-03-08 | Fraud5            | W   | 0.208      | -            | -                | -                | -         |     0.66 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            7 |     3709 | 2024-03-07 | INGLORIOUS        | L   | 0.202      | -            | -                | -                | -         |    -6.03 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            6 |     3843 | 2024-03-03 | ex-Preasy         | W   | 0.173      | -            | -                | -                | -         |     1.02 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            5 |     3856 | 2024-03-02 | kONO              | W   | 0.168      | -            | -                | -                | -         |     1.12 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            4 |     3926 | 2024-02-27 | ECLOT             | L   | 0.141      | -            | -                | -                | -         |    -1.23 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            3 |     3941 | 2024-02-26 | BLEED             | W   | 0.134      | -            | -                | -                | -         |     1.61 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            2 |     4004 | 2024-02-24 | Sashi             | W   | 0.120      | -            | -                | -                | -         |     2.49 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            1 |     4066 | 2024-02-21 | Entropiq          | W   | 0.100      | -            | -                | -                | -         |     0.19 | Burmylov, Chr1zN, Neityu, PR, sirah    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($45,129.93)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-02 |      0.781 | $5,000.00      | $3,906.94       |
| 2024-05-26 |      0.735 | $10,000.00     | $7,350.00       |
| 2024-05-18 |      0.682 | $500.00        | $340.97         |
| 2024-05-12 |      0.642 | $5,000.00      | $3,209.38       |
| 2024-05-03 |      0.581 | $25,000.00     | $14,534.72      |
| 2024-03-18 |      0.273 | $1,000.00      | $273.06         |
| 2024-03-11 |      0.227 | $3,500.00      | $795.28         |
| 2024-02-28 |      0.146 | $1,500.00      | $219.58         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
