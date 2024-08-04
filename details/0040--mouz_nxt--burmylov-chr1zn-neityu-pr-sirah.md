### Roster Details<br />
Team Name: MOUZ NXT<br />
Roster: Burmylov, Chr1zN, Neityu, PR, sirah<br />
Global Rank: [40](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [29]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1117.8<br />
<br />
Final Rank Value (1117.8) = Starting Rank Value (1041.2) + Head To Head Adjustments (76.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.539[<sup>1</sup>](#table2)
- Bounty Collected: 0.456[<sup>2</sup>](#table1)
- Opponent Network: 0.261[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.314<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1041.2
- 400 + ( ( 0.314 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1041.2


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
|           89 |      204 | 2024-07-29 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.57 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           88 |      208 | 2024-07-29 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.58 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           87 |      263 | 2024-07-27 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.12 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           86 |      339 | 2024-07-25 | Aurora Young Blud | W   | 1.000      | 0.435        | -                | 0.419 (0.182)    | 0 (0.000) |     7.72 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           85 |      458 | 2024-07-21 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.24 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           84 |      498 | 2024-07-20 | BLEED             | W   | 1.000      | 0.500        | 0.126 (0.063)    | 0.516 (0.258)    | 0 (0.000) |    24.53 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           83 |      512 | 2024-07-19 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.036)    | 0.404 (0.202)    | 0 (0.000) |    11.95 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           82 |      565 | 2024-07-18 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -1.67 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           81 |      705 | 2024-07-16 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.036)    | 0.404 (0.202)    | 0 (0.000) |    12.40 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           80 |     1085 | 2024-06-13 | B8                | L   | 0.856      | -            | -                | -                | -         |   -11.23 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           79 |     1146 | 2024-06-10 | Endpoint          | L   | 0.837      | -            | -                | -                | -         |   -20.49 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           78 |     1182 | 2024-06-09 | GhoulsW           | W   | 0.831      | -            | -                | -                | 0 (0.000) |     0.53 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           77 |     1201 | 2024-06-09 | BLEED             | L   | 0.830      | -            | -                | -                | -         |    -4.84 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           76 |     1258 | 2024-06-08 | Sampi             | W   | 0.824      | 0.435        | -                | 1.000 (0.358)    | 0 (0.000) |     6.58 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           75 |     1270 | 2024-06-08 | ECLOT             | L   | 0.824      | -            | -                | -                | -         |   -11.21 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           74 |     1298 | 2024-06-07 | GamerLegion       | L   | 0.819      | -            | -                | -                | -         |   -10.38 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           73 |     1363 | 2024-06-06 | Rhyno             | W   | 0.812      | 0.500        | 0.071 (0.029)    | -                | 0 (0.000) |     8.54 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           72 |     1392 | 2024-06-06 | Entropiq          | W   | 0.810      | -            | -                | -                | 0 (0.000) |     0.48 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           71 |     1490 | 2024-06-04 | NAVI Junior       | W   | 0.797      | -            | -                | -                | -         |     1.16 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           70 |     1497 | 2024-06-04 | Aurora Young Blud | W   | 0.796      | -            | -                | -                | -         |     4.11 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           69 |     1535 | 2024-06-02 | FURIA             | L   | 0.784      | -            | -                | -                | -         |    -1.46 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           68 |     1569 | 2024-06-01 | AMKAL             | W   | 0.777      | 0.435        | 0.130 (0.044)    | -                | -         |    15.63 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           67 |     1628 | 2024-05-30 | Sangal            | W   | 0.763      | 0.435        | 0.219 (0.073)    | 0.862 (0.286)    | -         |    13.96 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           66 |     1669 | 2024-05-28 | RUBY              | W   | 0.751      | 0.435        | 0.095 (0.031)    | -                | -         |     7.96 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           65 |     1696 | 2024-05-27 | Nexus             | W   | 0.743      | -            | -                | -                | -         |     4.06 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           64 |     1704 | 2024-05-26 | 9 Pandas          | L   | 0.738      | -            | -                | -                | -         |   -11.69 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           63 |     1712 | 2024-05-26 | B8                | W   | 0.736      | 0.435        | 0.165 (0.053)    | 0.913 (0.292)    | -         |    15.16 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           62 |     1737 | 2024-05-25 | 3DMAX             | W   | 0.729      | 0.435        | 0.505 (0.160)    | 1.000 (0.317)    | -         |    21.77 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           61 |     1750 | 2024-05-24 | Illuminar         | W   | 0.723      | -            | -                | -                | -         |     6.51 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           60 |     1763 | 2024-05-23 | Rare Atom         | W   | 0.717      | -            | -                | -                | -         |     3.08 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           59 |     1803 | 2024-05-22 | Rhyno             | L   | 0.710      | -            | -                | -                | -         |   -12.71 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           58 |     1845 | 2024-05-21 | DMS               | L   | 0.704      | -            | -                | -                | -         |   -15.04 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           57 |     1914 | 2024-05-19 | BLEED             | L   | 0.689      | -            | -                | -                | -         |    -3.08 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           56 |     1980 | 2024-05-17 | DMS               | W   | 0.676      | -            | -                | -                | -         |     6.63 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           55 |     2005 | 2024-05-16 | Sampi             | W   | 0.671      | 0.435        | -                | 1.000 (0.292)    | -         |     7.04 | Chr1zN, Neityu, PR, sirah, TOBIZ       |
|           54 |     2068 | 2024-05-15 | BLEED             | L   | 0.663      | -            | -                | -                | -         |    -2.36 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           53 |     2121 | 2024-05-14 | B8                | L   | 0.656      | -            | -                | -                | -         |    -8.89 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           52 |     2145 | 2024-05-13 | Space             | W   | 0.649      | -            | -                | -                | -         |     4.66 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           51 |     2167 | 2024-05-12 | B8                | L   | 0.643      | -            | -                | -                | -         |    -9.59 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           50 |     2181 | 2024-05-11 | Endpoint          | W   | 0.639      | -            | -                | -                | -         |     7.15 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           49 |     2207 | 2024-05-10 | Aurora            | W   | 0.632      | 0.435        | 0.424 (0.117)    | 0.794 (0.218)    | -         |    19.05 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           48 |     2277 | 2024-05-07 | RUSH B            | W   | 0.611      | -            | -                | -                | -         |     5.25 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           47 |     2320 | 2024-05-05 | GL Academy        | W   | 0.596      | -            | -                | -                | -         |     3.47 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           46 |     2322 | 2024-05-04 | Enterprise        | L   | 0.592      | -            | -                | -                | -         |   -13.05 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           45 |     2341 | 2024-05-03 | Nemiga            | L   | 0.584      | -            | -                | -                | -         |    -6.14 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           44 |     2361 | 2024-05-02 | Endpoint          | L   | 0.579      | -            | -                | -                | -         |   -12.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           43 |     2374 | 2024-05-02 | ALTERNATE aTTaX   | W   | 0.577      | -            | -                | -                | -         |     7.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           42 |     2380 | 2024-05-02 | 9 Pandas          | L   | 0.576      | -            | -                | -                | -         |   -11.09 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           41 |     2395 | 2024-05-01 | BLEED             | W   | 0.570      | -            | -                | -                | -         |     9.76 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           40 |     2407 | 2024-04-30 | ECLOT             | W   | 0.565      | -            | -                | -                | -         |    12.39 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           39 |     2418 | 2024-04-30 | V1dar             | W   | 0.564      | -            | -                | -                | -         |     1.02 | Burmylov, Chr1zN, PR, sirah, TOBIZ     |
|           38 |     2430 | 2024-04-29 | Nemiga            | L   | 0.559      | -            | -                | -                | -         |    -6.26 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           37 |     2443 | 2024-04-29 | Grannys Knockers  | W   | 0.556      | -            | -                | -                | -         |     3.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           36 |     2471 | 2024-04-27 | ECLOT             | W   | 0.545      | -            | -                | -                | -         |    12.35 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           35 |     2542 | 2024-04-25 | Insilio           | L   | 0.529      | -            | -                | -                | -         |   -11.06 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           34 |     2553 | 2024-04-24 | PARIVISION        | L   | 0.524      | -            | -                | -                | -         |    -8.02 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           33 |     2587 | 2024-04-22 | EYEBALLERS        | W   | 0.511      | -            | -                | -                | -         |     4.73 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           32 |     2595 | 2024-04-22 | Nemiga            | L   | 0.509      | -            | -                | -                | -         |    -5.75 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           31 |     2604 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.504      | -            | -                | -                | -         |     5.83 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           30 |     2611 | 2024-04-21 | ECLOT             | L   | 0.503      | -            | -                | -                | -         |    -4.84 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           29 |     2632 | 2024-04-20 | BLEED             | L   | 0.498      | -            | -                | -                | -         |    -8.46 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           28 |     2730 | 2024-04-18 | Enterprise        | W   | 0.484      | -            | -                | -                | -         |     5.05 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           27 |     2740 | 2024-04-18 | ENCE Academy      | W   | 0.483      | -            | -                | -                | -         |     2.24 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           26 |     2789 | 2024-04-17 | JANO              | W   | 0.476      | -            | -                | -                | -         |     1.75 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           25 |     2803 | 2024-04-16 | GamerLegion       | L   | 0.471      | -            | -                | -                | -         |    -5.92 | Anlelele, Burmylov, Neityu, PR, sirah  |
|           24 |     2828 | 2024-04-15 | Alliance          | W   | 0.463      | -            | -                | -                | -         |     3.71 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           23 |     2868 | 2024-04-12 | Permitta          | L   | 0.443      | -            | -                | -                | -         |    -8.75 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           22 |     2995 | 2024-04-09 | Zero Tenacity     | W   | 0.424      | -            | -                | -                | -         |     7.26 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           21 |     3030 | 2024-04-08 | B8                | W   | 0.417      | -            | -                | -                | -         |     7.14 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           20 |     3154 | 2024-04-03 | PARIVISION        | W   | 0.385      | -            | -                | -                | -         |     7.16 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           19 |     3485 | 2024-03-16 | Sampi             | L   | 0.263      | -            | -                | -                | -         |    -5.67 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           18 |     3503 | 2024-03-15 | Entropiq          | W   | 0.257      | -            | -                | -                | -         |     0.54 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           17 |     3554 | 2024-03-13 | Permitta          | L   | 0.246      | -            | -                | -                | -         |    -4.70 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           16 |     3571 | 2024-03-13 | Alliance          | W   | 0.243      | -            | -                | -                | -         |     2.07 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           15 |     3598 | 2024-03-12 | AURA              | W   | 0.238      | -            | -                | -                | -         |     0.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           14 |     3605 | 2024-03-12 | Sampi             | L   | 0.236      | -            | -                | -                | -         |    -5.21 | Burmylov, Chr1zN, Neityu, sirah, xReal |
|           13 |     3625 | 2024-03-11 | Passion UA        | W   | 0.230      | -            | -                | -                | -         |     3.95 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           12 |     3627 | 2024-03-11 | NOM               | W   | 0.229      | -            | -                | -                | -         |     0.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           11 |     3633 | 2024-03-10 | V1dar             | W   | 0.225      | -            | -                | -                | -         |     0.37 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           10 |     3645 | 2024-03-10 | Passion UA        | L   | 0.224      | -            | -                | -                | -         |    -3.25 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            9 |     3649 | 2024-03-10 | ALTERNATE aTTaX   | W   | 0.223      | -            | -                | -                | -         |     2.97 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            8 |     3686 | 2024-03-08 | Fraud5            | W   | 0.211      | -            | -                | -                | -         |     0.67 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            7 |     3703 | 2024-03-07 | INGLORIOUS        | L   | 0.205      | -            | -                | -                | -         |    -6.12 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            6 |     3837 | 2024-03-03 | ex-Preasy         | W   | 0.176      | -            | -                | -                | -         |     1.04 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            5 |     3850 | 2024-03-02 | kONO              | W   | 0.171      | -            | -                | -                | -         |     1.14 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            4 |     3920 | 2024-02-27 | ECLOT             | L   | 0.144      | -            | -                | -                | -         |    -1.26 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            3 |     3935 | 2024-02-26 | BLEED             | W   | 0.137      | -            | -                | -                | -         |     1.66 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            2 |     3998 | 2024-02-24 | Sashi             | W   | 0.123      | -            | -                | -                | -         |     2.55 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            1 |     4060 | 2024-02-21 | Entropiq          | W   | 0.103      | -            | -                | -                | -         |     0.19 | Burmylov, Chr1zN, Neityu, PR, sirah    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($45,287.29)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-02 |      0.784 | $5,000.00      | $3,922.22       |
| 2024-05-26 |      0.738 | $10,000.00     | $7,380.56       |
| 2024-05-18 |      0.685 | $500.00        | $342.50         |
| 2024-05-12 |      0.645 | $5,000.00      | $3,224.65       |
| 2024-05-03 |      0.584 | $25,000.00     | $14,611.11      |
| 2024-03-18 |      0.276 | $1,000.00      | $276.11         |
| 2024-03-11 |      0.230 | $3,500.00      | $805.97         |
| 2024-02-28 |      0.149 | $1,500.00      | $224.17         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
