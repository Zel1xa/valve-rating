### Roster Details<br />
Team Name: MOUZ NXT<br />
Roster: Burmylov, Neityu, PR, sirah, TOBIZ<br />
Global Rank: [43](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [31]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1106.1<br />
<br />
Final Rank Value (1106.1) = Starting Rank Value (1045.5) + Head To Head Adjustments (60.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.538[<sup>1</sup>](#table2)
- Bounty Collected: 0.454[<sup>2</sup>](#table1)
- Opponent Network: 0.263[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.314<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1045.5
- 400 + ( ( 0.314 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1045.5


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
|           90 |       78 | 2024-08-03 | 1WIN              | L   | 1.000      | -            | -                | -                | -         |   -21.29 | Burmylov, Neityu, PR, sirah, TOBIZ     |
|           89 |      283 | 2024-07-29 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.39 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           88 |      286 | 2024-07-29 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.05 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           87 |      342 | 2024-07-27 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.24 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           86 |      417 | 2024-07-25 | Aurora Young Blud | W   | 1.000      | 0.435        | -                | 0.521 (0.227)    | 0 (0.000) |     9.40 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           85 |      537 | 2024-07-21 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.35 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           84 |      577 | 2024-07-20 | BLEED             | W   | 1.000      | 0.500        | 0.126 (0.063)    | 0.538 (0.269)    | 0 (0.000) |    24.59 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           83 |      591 | 2024-07-19 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.035)    | 0.427 (0.214)    | 0 (0.000) |    11.76 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           82 |      641 | 2024-07-18 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -1.65 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           81 |      783 | 2024-07-16 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.035)    | 0.427 (0.214)    | 0 (0.000) |    12.19 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           80 |     1165 | 2024-06-13 | B8                | L   | 0.838      | -            | -                | -                | -         |   -11.18 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           79 |     1226 | 2024-06-10 | Endpoint          | L   | 0.820      | -            | -                | -                | -         |   -20.04 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           78 |     1262 | 2024-06-09 | GhoulsW           | W   | 0.814      | -            | -                | -                | 0 (0.000) |     0.49 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           77 |     1281 | 2024-06-09 | BLEED             | L   | 0.813      | -            | -                | -                | -         |    -4.74 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           76 |     1338 | 2024-06-08 | Sampi             | W   | 0.807      | 0.435        | -                | 1.000 (0.351)    | 0 (0.000) |     6.53 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           75 |     1350 | 2024-06-08 | ECLOT             | L   | 0.806      | -            | -                | -                | -         |   -11.03 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           74 |     1378 | 2024-06-07 | GamerLegion       | L   | 0.801      | -            | -                | -                | -         |   -10.53 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           73 |     1443 | 2024-06-06 | Rhyno             | W   | 0.794      | 0.500        | 0.071 (0.028)    | -                | 0 (0.000) |     8.12 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           72 |     1472 | 2024-06-06 | Entropiq          | W   | 0.793      | -            | -                | -                | 0 (0.000) |     0.46 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           71 |     1570 | 2024-06-04 | NAVI Junior       | W   | 0.779      | -            | -                | -                | -         |     2.61 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           70 |     1577 | 2024-06-04 | Aurora Young Blud | W   | 0.778      | -            | -                | -                | -         |     5.73 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           69 |     1615 | 2024-06-02 | FURIA             | L   | 0.766      | -            | -                | -                | -         |    -1.42 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           68 |     1649 | 2024-06-01 | AMKAL             | W   | 0.759      | 0.435        | 0.130 (0.043)    | -                | -         |    15.11 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           67 |     1708 | 2024-05-30 | Sangal            | W   | 0.745      | 0.435        | 0.219 (0.071)    | 0.846 (0.274)    | -         |    13.87 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           66 |     1749 | 2024-05-28 | RUBY              | W   | 0.734      | 0.435        | 0.095 (0.030)    | -                | -         |     7.71 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           65 |     1776 | 2024-05-27 | Nexus             | W   | 0.725      | -            | -                | -                | -         |     3.96 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           64 |     1784 | 2024-05-26 | 9 Pandas          | L   | 0.720      | -            | -                | -                | -         |   -11.72 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           63 |     1792 | 2024-05-26 | B8                | W   | 0.719      | 0.435        | 0.170 (0.053)    | 0.912 (0.285)    | -         |    14.65 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           62 |     1817 | 2024-05-25 | 3DMAX             | W   | 0.712      | 0.435        | 0.510 (0.158)    | 1.000 (0.309)    | -         |    21.27 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           61 |     1830 | 2024-05-24 | Illuminar         | W   | 0.705      | -            | -                | -                | -         |     6.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           60 |     1843 | 2024-05-23 | Rare Atom         | W   | 0.699      | -            | -                | -                | -         |     5.68 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           59 |     1883 | 2024-05-22 | Rhyno             | L   | 0.693      | -            | -                | -                | -         |   -12.55 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           58 |     1925 | 2024-05-21 | DMS               | L   | 0.686      | -            | -                | -                | -         |   -14.71 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           57 |     1994 | 2024-05-19 | BLEED             | L   | 0.672      | -            | -                | -                | -         |    -2.98 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           56 |     2060 | 2024-05-17 | DMS               | W   | 0.659      | -            | -                | -                | -         |     6.44 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           55 |     2085 | 2024-05-16 | Sampi             | W   | 0.653      | 0.435        | -                | 1.000 (0.284)    | -         |     6.78 | Chr1zN, Neityu, PR, sirah, TOBIZ       |
|           54 |     2148 | 2024-05-15 | BLEED             | L   | 0.645      | -            | -                | -                | -         |    -2.29 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           53 |     2201 | 2024-05-14 | B8                | L   | 0.639      | -            | -                | -                | -         |    -8.70 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           52 |     2225 | 2024-05-13 | Space             | W   | 0.632      | -            | -                | -                | -         |     4.50 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           51 |     2247 | 2024-05-12 | B8                | L   | 0.625      | -            | -                | -                | -         |    -9.35 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           50 |     2261 | 2024-05-11 | Endpoint          | W   | 0.621      | -            | -                | -                | -         |     6.92 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           49 |     2287 | 2024-05-10 | Aurora            | W   | 0.614      | 0.435        | 0.420 (0.112)    | 0.758 (0.203)    | -         |    18.55 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           48 |     2357 | 2024-05-07 | RUSH B            | W   | 0.593      | -            | -                | -                | -         |     5.25 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           47 |     2400 | 2024-05-05 | GL Academy        | W   | 0.579      | -            | -                | -                | -         |     3.30 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           46 |     2402 | 2024-05-04 | Enterprise        | L   | 0.574      | -            | -                | -                | -         |   -12.69 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           45 |     2421 | 2024-05-03 | Nemiga            | L   | 0.567      | -            | -                | -                | -         |    -5.74 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           44 |     2441 | 2024-05-02 | Endpoint          | L   | 0.561      | -            | -                | -                | -         |   -11.87 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           43 |     2454 | 2024-05-02 | ALTERNATE aTTaX   | W   | 0.559      | -            | -                | -                | -         |     7.12 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           42 |     2460 | 2024-05-02 | 9 Pandas          | L   | 0.558      | -            | -                | -                | -         |   -11.02 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           41 |     2475 | 2024-05-01 | BLEED             | W   | 0.553      | -            | -                | -                | -         |     9.28 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           40 |     2487 | 2024-04-30 | ECLOT             | W   | 0.548      | -            | -                | -                | -         |    12.03 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           39 |     2498 | 2024-04-30 | V1dar             | W   | 0.546      | -            | -                | -                | -         |     0.96 | Burmylov, Chr1zN, PR, sirah, TOBIZ     |
|           38 |     2510 | 2024-04-29 | Nemiga            | L   | 0.541      | -            | -                | -                | -         |    -5.84 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           37 |     2523 | 2024-04-29 | Grannys Knockers  | W   | 0.539      | -            | -                | -                | -         |     3.03 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           36 |     2551 | 2024-04-27 | ECLOT             | W   | 0.528      | -            | -                | -                | -         |    11.95 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           35 |     2623 | 2024-04-25 | Insilio           | L   | 0.512      | -            | -                | -                | -         |   -10.70 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           34 |     2634 | 2024-04-24 | PARIVISION        | L   | 0.507      | -            | -                | -                | -         |    -7.62 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           33 |     2668 | 2024-04-22 | EYEBALLERS        | W   | 0.493      | -            | -                | -                | -         |     4.52 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           32 |     2676 | 2024-04-22 | Nemiga            | L   | 0.492      | -            | -                | -                | -         |    -5.32 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           31 |     2685 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.487      | -            | -                | -                | -         |     5.64 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           30 |     2692 | 2024-04-21 | ECLOT             | L   | 0.486      | -            | -                | -                | -         |    -4.65 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           29 |     2713 | 2024-04-20 | BLEED             | L   | 0.480      | -            | -                | -                | -         |    -8.33 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           28 |     2811 | 2024-04-18 | Enterprise        | W   | 0.467      | -            | -                | -                | -         |     4.83 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           27 |     2821 | 2024-04-18 | ENCE Academy      | W   | 0.466      | -            | -                | -                | -         |     2.09 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           26 |     2870 | 2024-04-17 | JANO              | W   | 0.458      | -            | -                | -                | -         |     1.67 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           25 |     2884 | 2024-04-16 | GamerLegion       | L   | 0.453      | -            | -                | -                | -         |    -5.84 | Anlelele, Burmylov, Neityu, PR, sirah  |
|           24 |     2909 | 2024-04-15 | Alliance          | W   | 0.445      | -            | -                | -                | -         |     3.50 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           23 |     2949 | 2024-04-12 | Permitta          | L   | 0.426      | -            | -                | -                | -         |    -7.96 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           22 |     3076 | 2024-04-09 | Zero Tenacity     | W   | 0.407      | -            | -                | -                | -         |     6.97 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           21 |     3111 | 2024-04-08 | B8                | W   | 0.399      | -            | -                | -                | -         |     6.79 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           20 |     3235 | 2024-04-03 | PARIVISION        | W   | 0.368      | -            | -                | -                | -         |     6.90 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           19 |     3566 | 2024-03-16 | Sampi             | L   | 0.245      | -            | -                | -                | -         |    -5.33 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           18 |     3584 | 2024-03-15 | Entropiq          | W   | 0.240      | -            | -                | -                | -         |     0.48 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           17 |     3635 | 2024-03-13 | Permitta          | L   | 0.228      | -            | -                | -                | -         |    -4.09 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           16 |     3653 | 2024-03-13 | Alliance          | W   | 0.226      | -            | -                | -                | -         |     1.89 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           15 |     3680 | 2024-03-12 | AURA              | W   | 0.220      | -            | -                | -                | -         |     0.30 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           14 |     3687 | 2024-03-12 | Sampi             | L   | 0.219      | -            | -                | -                | -         |    -4.86 | Burmylov, Chr1zN, Neityu, sirah, xReal |
|           13 |     3707 | 2024-03-11 | Passion UA        | W   | 0.213      | -            | -                | -                | -         |     3.71 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           12 |     3709 | 2024-03-11 | NOM               | W   | 0.212      | -            | -                | -                | -         |     0.31 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           11 |     3715 | 2024-03-10 | V1dar             | W   | 0.208      | -            | -                | -                | -         |     0.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           10 |     3727 | 2024-03-10 | Passion UA        | L   | 0.206      | -            | -                | -                | -         |    -2.94 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            9 |     3731 | 2024-03-10 | ALTERNATE aTTaX   | W   | 0.205      | -            | -                | -                | -         |     2.70 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            8 |     3768 | 2024-03-08 | Fraud5            | W   | 0.194      | -            | -                | -                | -         |     0.60 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            7 |     3785 | 2024-03-07 | INGLORIOUS        | L   | 0.188      | -            | -                | -                | -         |    -5.60 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            6 |     3919 | 2024-03-03 | ex-Preasy         | W   | 0.159      | -            | -                | -                | -         |     0.90 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            5 |     3932 | 2024-03-02 | kONO              | W   | 0.153      | -            | -                | -                | -         |     1.02 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            4 |     4002 | 2024-02-27 | ECLOT             | L   | 0.126      | -            | -                | -                | -         |    -1.12 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            3 |     4017 | 2024-02-26 | BLEED             | W   | 0.120      | -            | -                | -                | -         |     1.41 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            2 |     4080 | 2024-02-24 | Sashi             | W   | 0.105      | -            | -                | -                | -         |     2.18 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            1 |     4142 | 2024-02-21 | Entropiq          | W   | 0.085      | -            | -                | -                | -         |     0.15 | Burmylov, Chr1zN, Neityu, PR, sirah    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,381.27)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-02 |      0.767 | $5,000.00      | $3,834.26       |
| 2024-05-26 |      0.720 | $10,000.00     | $7,204.63       |
| 2024-05-18 |      0.667 | $500.00        | $333.70         |
| 2024-05-12 |      0.627 | $5,000.00      | $3,136.69       |
| 2024-05-03 |      0.567 | $25,000.00     | $14,171.30      |
| 2024-03-18 |      0.259 | $1,000.00      | $258.52         |
| 2024-03-11 |      0.213 | $3,500.00      | $744.40         |
| 2024-02-28 |      0.132 | $1,500.00      | $197.78         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
