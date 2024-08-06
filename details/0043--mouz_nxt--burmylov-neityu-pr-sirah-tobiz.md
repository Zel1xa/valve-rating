### Roster Details<br />
Team Name: MOUZ NXT<br />
Roster: Burmylov, Neityu, PR, sirah, TOBIZ<br />
Global Rank: [43](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [30]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1102.4<br />
<br />
Final Rank Value (1102.4) = Starting Rank Value (1045.2) + Head To Head Adjustments (57.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.538[<sup>1</sup>](#table2)
- Bounty Collected: 0.454[<sup>2</sup>](#table1)
- Opponent Network: 0.266[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.315<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1045.2
- 400 + ( ( 0.315 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1045.2


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
|           90 |       62 | 2024-08-03 | 1WIN              | L   | 1.000      | -            | -                | -                | -         |   -21.22 | Burmylov, Neityu, PR, sirah, TOBIZ     |
|           89 |      267 | 2024-07-29 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.47 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           88 |      270 | 2024-07-29 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.08 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           87 |      326 | 2024-07-27 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.16 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           86 |      401 | 2024-07-25 | Aurora Young Blud | W   | 1.000      | 0.435        | -                | 0.532 (0.231)    | 0 (0.000) |     8.72 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           85 |      521 | 2024-07-21 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.27 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           84 |      561 | 2024-07-20 | BLEED             | W   | 1.000      | 0.500        | 0.126 (0.063)    | 0.511 (0.255)    | 0 (0.000) |    24.62 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           83 |      575 | 2024-07-19 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.035)    | 0.437 (0.219)    | 0 (0.000) |    11.74 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           82 |      625 | 2024-07-18 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -1.61 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           81 |      767 | 2024-07-16 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.035)    | 0.437 (0.219)    | 0 (0.000) |    12.17 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           80 |     1149 | 2024-06-13 | B8                | L   | 0.842      | -            | -                | -                | -         |   -11.17 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           79 |     1210 | 2024-06-10 | Endpoint          | L   | 0.823      | -            | -                | -                | -         |   -20.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           78 |     1246 | 2024-06-09 | GhoulsW           | W   | 0.818      | -            | -                | -                | 0 (0.000) |     0.50 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           77 |     1265 | 2024-06-09 | BLEED             | L   | 0.816      | -            | -                | -                | -         |    -4.73 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           76 |     1322 | 2024-06-08 | Sampi             | W   | 0.810      | 0.435        | -                | 1.000 (0.352)    | 0 (0.000) |     6.53 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           75 |     1334 | 2024-06-08 | ECLOT             | L   | 0.810      | -            | -                | -                | -         |   -11.02 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           74 |     1362 | 2024-06-07 | GamerLegion       | L   | 0.805      | -            | -                | -                | -         |   -10.43 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           73 |     1427 | 2024-06-06 | Rhyno             | W   | 0.798      | 0.500        | 0.071 (0.028)    | -                | 0 (0.000) |     8.21 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           72 |     1456 | 2024-06-06 | Entropiq          | W   | 0.796      | -            | -                | -                | 0 (0.000) |     0.46 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           71 |     1554 | 2024-06-04 | NAVI Junior       | W   | 0.783      | -            | -                | -                | -         |     1.11 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           70 |     1561 | 2024-06-04 | Aurora Young Blud | W   | 0.782      | -            | -                | -                | -         |     4.93 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           69 |     1599 | 2024-06-02 | FURIA             | L   | 0.770      | -            | -                | -                | -         |    -1.41 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           68 |     1633 | 2024-06-01 | AMKAL             | W   | 0.763      | 0.435        | 0.130 (0.043)    | -                | -         |    15.16 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           67 |     1692 | 2024-05-30 | Sangal            | W   | 0.749      | 0.435        | 0.219 (0.071)    | 0.866 (0.282)    | -         |    13.81 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           66 |     1733 | 2024-05-28 | RUBY              | W   | 0.737      | 0.435        | 0.095 (0.030)    | -                | -         |     7.59 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           65 |     1760 | 2024-05-27 | Nexus             | W   | 0.729      | -            | -                | -                | -         |     3.93 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           64 |     1768 | 2024-05-26 | 9 Pandas          | L   | 0.724      | -            | -                | -                | -         |   -11.75 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           63 |     1776 | 2024-05-26 | B8                | W   | 0.723      | 0.435        | 0.164 (0.052)    | 0.934 (0.293)    | -         |    14.71 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           62 |     1801 | 2024-05-25 | 3DMAX             | W   | 0.715      | 0.435        | 0.509 (0.158)    | 1.000 (0.311)    | -         |    21.38 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           61 |     1814 | 2024-05-24 | Illuminar         | W   | 0.709      | -            | -                | -                | -         |     6.30 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           60 |     1827 | 2024-05-23 | Rare Atom         | W   | 0.703      | -            | -                | -                | -         |     5.59 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           59 |     1867 | 2024-05-22 | Rhyno             | L   | 0.696      | -            | -                | -                | -         |   -12.63 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           58 |     1909 | 2024-05-21 | DMS               | L   | 0.690      | -            | -                | -                | -         |   -14.76 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           57 |     1978 | 2024-05-19 | BLEED             | L   | 0.676      | -            | -                | -                | -         |    -2.98 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           56 |     2044 | 2024-05-17 | DMS               | W   | 0.662      | -            | -                | -                | -         |     6.51 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           55 |     2069 | 2024-05-16 | Sampi             | W   | 0.657      | 0.435        | -                | 1.000 (0.286)    | -         |     6.82 | Chr1zN, Neityu, PR, sirah, TOBIZ       |
|           54 |     2132 | 2024-05-15 | BLEED             | L   | 0.649      | -            | -                | -                | -         |    -2.29 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           53 |     2185 | 2024-05-14 | B8                | L   | 0.642      | -            | -                | -                | -         |    -8.78 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           52 |     2209 | 2024-05-13 | Space             | W   | 0.635      | -            | -                | -                | -         |     4.43 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           51 |     2231 | 2024-05-12 | B8                | L   | 0.629      | -            | -                | -                | -         |    -9.44 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           50 |     2245 | 2024-05-11 | Endpoint          | W   | 0.625      | -            | -                | -                | -         |     6.93 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           49 |     2271 | 2024-05-10 | Aurora            | W   | 0.618      | 0.435        | 0.421 (0.113)    | 0.777 (0.209)    | -         |    18.65 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           48 |     2341 | 2024-05-07 | RUSH B            | W   | 0.597      | -            | -                | -                | -         |     5.30 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           47 |     2384 | 2024-05-05 | GL Academy        | W   | 0.583      | -            | -                | -                | -         |     3.31 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           46 |     2386 | 2024-05-04 | Enterprise        | L   | 0.578      | -            | -                | -                | -         |   -12.79 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           45 |     2405 | 2024-05-03 | Nemiga            | L   | 0.571      | -            | -                | -                | -         |    -5.75 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           44 |     2425 | 2024-05-02 | Endpoint          | L   | 0.565      | -            | -                | -                | -         |   -11.97 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           43 |     2438 | 2024-05-02 | ALTERNATE aTTaX   | W   | 0.563      | -            | -                | -                | -         |     7.13 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           42 |     2444 | 2024-05-02 | 9 Pandas          | L   | 0.562      | -            | -                | -                | -         |   -11.07 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           41 |     2459 | 2024-05-01 | BLEED             | W   | 0.556      | -            | -                | -                | -         |     9.37 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           40 |     2471 | 2024-04-30 | ECLOT             | W   | 0.551      | -            | -                | -                | -         |    12.09 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           39 |     2482 | 2024-04-30 | V1dar             | W   | 0.550      | -            | -                | -                | -         |     0.97 | Burmylov, Chr1zN, PR, sirah, TOBIZ     |
|           38 |     2494 | 2024-04-29 | Nemiga            | L   | 0.545      | -            | -                | -                | -         |    -5.84 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           37 |     2507 | 2024-04-29 | Grannys Knockers  | W   | 0.542      | -            | -                | -                | -         |     3.06 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           36 |     2535 | 2024-04-27 | ECLOT             | W   | 0.531      | -            | -                | -                | -         |    12.02 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           35 |     2607 | 2024-04-25 | Insilio           | L   | 0.515      | -            | -                | -                | -         |   -10.81 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           34 |     2618 | 2024-04-24 | PARIVISION        | L   | 0.510      | -            | -                | -                | -         |    -7.73 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           33 |     2652 | 2024-04-22 | EYEBALLERS        | W   | 0.497      | -            | -                | -                | -         |     4.53 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           32 |     2660 | 2024-04-22 | Nemiga            | L   | 0.496      | -            | -                | -                | -         |    -5.33 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           31 |     2669 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.491      | -            | -                | -                | -         |     5.64 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           30 |     2676 | 2024-04-21 | ECLOT             | L   | 0.489      | -            | -                | -                | -         |    -4.71 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           29 |     2697 | 2024-04-20 | BLEED             | L   | 0.484      | -            | -                | -                | -         |    -8.37 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           28 |     2795 | 2024-04-18 | Enterprise        | W   | 0.471      | -            | -                | -                | -         |     4.86 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           27 |     2805 | 2024-04-18 | ENCE Academy      | W   | 0.469      | -            | -                | -                | -         |     2.12 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           26 |     2854 | 2024-04-17 | JANO              | W   | 0.462      | -            | -                | -                | -         |     1.68 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           25 |     2868 | 2024-04-16 | GamerLegion       | L   | 0.457      | -            | -                | -                | -         |    -5.85 | Anlelele, Burmylov, Neityu, PR, sirah  |
|           24 |     2893 | 2024-04-15 | Alliance          | W   | 0.449      | -            | -                | -                | -         |     3.54 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           23 |     2933 | 2024-04-12 | Permitta          | L   | 0.429      | -            | -                | -                | -         |    -8.32 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           22 |     3060 | 2024-04-09 | Zero Tenacity     | W   | 0.410      | -            | -                | -                | -         |     7.05 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           21 |     3095 | 2024-04-08 | B8                | W   | 0.403      | -            | -                | -                | -         |     6.81 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           20 |     3219 | 2024-04-03 | PARIVISION        | W   | 0.372      | -            | -                | -                | -         |     6.93 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           19 |     3550 | 2024-03-16 | Sampi             | L   | 0.249      | -            | -                | -                | -         |    -5.42 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           18 |     3568 | 2024-03-15 | Entropiq          | W   | 0.243      | -            | -                | -                | -         |     0.49 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           17 |     3619 | 2024-03-13 | Permitta          | L   | 0.232      | -            | -                | -                | -         |    -4.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           16 |     3637 | 2024-03-13 | Alliance          | W   | 0.230      | -            | -                | -                | -         |     1.92 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           15 |     3664 | 2024-03-12 | AURA              | W   | 0.224      | -            | -                | -                | -         |     0.30 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           14 |     3671 | 2024-03-12 | Sampi             | L   | 0.222      | -            | -                | -                | -         |    -4.95 | Burmylov, Chr1zN, Neityu, sirah, xReal |
|           13 |     3691 | 2024-03-11 | Passion UA        | W   | 0.216      | -            | -                | -                | -         |     3.76 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           12 |     3693 | 2024-03-11 | NOM               | W   | 0.216      | -            | -                | -                | -         |     0.31 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           11 |     3699 | 2024-03-10 | V1dar             | W   | 0.212      | -            | -                | -                | -         |     0.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           10 |     3711 | 2024-03-10 | Passion UA        | L   | 0.210      | -            | -                | -                | -         |    -3.00 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            9 |     3715 | 2024-03-10 | ALTERNATE aTTaX   | W   | 0.209      | -            | -                | -                | -         |     2.74 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            8 |     3752 | 2024-03-08 | Fraud5            | W   | 0.197      | -            | -                | -                | -         |     0.61 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            7 |     3769 | 2024-03-07 | INGLORIOUS        | L   | 0.192      | -            | -                | -                | -         |    -5.71 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            6 |     3903 | 2024-03-03 | ex-Preasy         | W   | 0.162      | -            | -                | -                | -         |     0.92 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            5 |     3916 | 2024-03-02 | kONO              | W   | 0.157      | -            | -                | -                | -         |     1.03 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            4 |     3986 | 2024-02-27 | ECLOT             | L   | 0.130      | -            | -                | -                | -         |    -1.15 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            3 |     4001 | 2024-02-26 | BLEED             | W   | 0.123      | -            | -                | -                | -         |     1.46 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            2 |     4064 | 2024-02-24 | Sashi             | W   | 0.109      | -            | -                | -                | -         |     2.25 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            1 |     4126 | 2024-02-21 | Entropiq          | W   | 0.089      | -            | -                | -                | -         |     0.16 | Burmylov, Chr1zN, Neityu, PR, sirah    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,572.01)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-02 |      0.771 | $5,000.00      | $3,852.78       |
| 2024-05-26 |      0.724 | $10,000.00     | $7,241.67       |
| 2024-05-18 |      0.671 | $500.00        | $335.56         |
| 2024-05-12 |      0.631 | $5,000.00      | $3,155.21       |
| 2024-05-03 |      0.571 | $25,000.00     | $14,263.89      |
| 2024-03-18 |      0.262 | $1,000.00      | $262.22         |
| 2024-03-11 |      0.216 | $3,500.00      | $757.36         |
| 2024-02-28 |      0.136 | $1,500.00      | $203.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
