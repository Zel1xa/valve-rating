### Roster Details<br />
Team Name: MOUZ NXT<br />
Roster: Burmylov, Neityu, PR, sirah, TOBIZ<br />
Global Rank: [43](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [30]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1102.5<br />
<br />
Final Rank Value (1102.5) = Starting Rank Value (1046.0) + Head To Head Adjustments (56.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.538[<sup>1</sup>](#table2)
- Bounty Collected: 0.454[<sup>2</sup>](#table1)
- Opponent Network: 0.267[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.315<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1046.0
- 400 + ( ( 0.315 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1046.0


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
|           90 |       66 | 2024-08-03 | 1WIN              | L   | 1.000      | -            | -                | -                | -         |   -21.20 | Burmylov, Neityu, PR, sirah, TOBIZ     |
|           89 |      271 | 2024-07-29 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.47 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           88 |      274 | 2024-07-29 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.07 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           87 |      330 | 2024-07-27 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.17 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           86 |      405 | 2024-07-25 | Aurora Young Blud | W   | 1.000      | 0.435        | -                | 0.533 (0.232)    | 0 (0.000) |     8.72 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           85 |      525 | 2024-07-21 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.28 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           84 |      565 | 2024-07-20 | BLEED             | W   | 1.000      | 0.500        | 0.126 (0.063)    | 0.550 (0.275)    | 0 (0.000) |    24.63 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           83 |      579 | 2024-07-19 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.035)    | 0.437 (0.218)    | 0 (0.000) |    11.72 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           82 |      629 | 2024-07-18 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -1.62 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           81 |      771 | 2024-07-16 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.035)    | 0.437 (0.218)    | 0 (0.000) |    12.15 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           80 |     1153 | 2024-06-13 | B8                | L   | 0.839      | -            | -                | -                | -         |   -11.15 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           79 |     1214 | 2024-06-10 | Endpoint          | L   | 0.821      | -            | -                | -                | -         |   -20.13 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           78 |     1250 | 2024-06-09 | GhoulsW           | W   | 0.815      | -            | -                | -                | 0 (0.000) |     0.50 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           77 |     1269 | 2024-06-09 | BLEED             | L   | 0.814      | -            | -                | -                | -         |    -4.71 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           76 |     1326 | 2024-06-08 | Sampi             | W   | 0.808      | 0.435        | -                | 1.000 (0.351)    | 0 (0.000) |     6.51 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           75 |     1338 | 2024-06-08 | ECLOT             | L   | 0.807      | -            | -                | -                | -         |   -10.99 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           74 |     1366 | 2024-06-07 | GamerLegion       | L   | 0.802      | -            | -                | -                | -         |   -10.42 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           73 |     1431 | 2024-06-06 | Rhyno             | W   | 0.796      | 0.500        | 0.071 (0.028)    | -                | 0 (0.000) |     8.17 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           72 |     1460 | 2024-06-06 | Entropiq          | W   | 0.794      | -            | -                | -                | 0 (0.000) |     0.46 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           71 |     1558 | 2024-06-04 | NAVI Junior       | W   | 0.781      | -            | -                | -                | -         |     1.11 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           70 |     1565 | 2024-06-04 | Aurora Young Blud | W   | 0.779      | -            | -                | -                | -         |     4.91 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           69 |     1603 | 2024-06-02 | FURIA             | L   | 0.767      | -            | -                | -                | -         |    -1.41 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           68 |     1637 | 2024-06-01 | AMKAL             | W   | 0.761      | 0.435        | 0.130 (0.043)    | -                | -         |    15.11 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           67 |     1696 | 2024-05-30 | Sangal            | W   | 0.746      | 0.435        | 0.219 (0.071)    | 0.865 (0.281)    | -         |    13.78 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           66 |     1737 | 2024-05-28 | RUBY              | W   | 0.735      | 0.435        | 0.095 (0.030)    | -                | -         |     7.56 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           65 |     1764 | 2024-05-27 | Nexus             | W   | 0.726      | -            | -                | -                | -         |     3.92 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           64 |     1772 | 2024-05-26 | 9 Pandas          | L   | 0.722      | -            | -                | -                | -         |   -11.74 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           63 |     1780 | 2024-05-26 | B8                | W   | 0.720      | 0.435        | 0.164 (0.051)    | 0.933 (0.292)    | -         |    14.64 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           62 |     1805 | 2024-05-25 | 3DMAX             | W   | 0.713      | 0.435        | 0.509 (0.158)    | 1.000 (0.310)    | -         |    21.31 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           61 |     1818 | 2024-05-24 | Illuminar         | W   | 0.706      | -            | -                | -                | -         |     6.27 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           60 |     1831 | 2024-05-23 | Rare Atom         | W   | 0.700      | -            | -                | -                | -         |     5.56 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           59 |     1871 | 2024-05-22 | Rhyno             | L   | 0.694      | -            | -                | -                | -         |   -12.60 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           58 |     1913 | 2024-05-21 | DMS               | L   | 0.687      | -            | -                | -                | -         |   -14.71 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           57 |     1982 | 2024-05-19 | BLEED             | L   | 0.673      | -            | -                | -                | -         |    -2.97 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           56 |     2048 | 2024-05-17 | DMS               | W   | 0.660      | -            | -                | -                | -         |     6.47 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           55 |     2073 | 2024-05-16 | Sampi             | W   | 0.655      | 0.435        | -                | 1.000 (0.285)    | -         |     6.79 | Chr1zN, Neityu, PR, sirah, TOBIZ       |
|           54 |     2136 | 2024-05-15 | BLEED             | L   | 0.646      | -            | -                | -                | -         |    -2.29 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           53 |     2189 | 2024-05-14 | B8                | L   | 0.640      | -            | -                | -                | -         |    -8.76 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           52 |     2213 | 2024-05-13 | Space             | W   | 0.633      | -            | -                | -                | -         |     4.42 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           51 |     2235 | 2024-05-12 | B8                | L   | 0.627      | -            | -                | -                | -         |    -9.42 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           50 |     2249 | 2024-05-11 | Endpoint          | W   | 0.622      | -            | -                | -                | -         |     6.90 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           49 |     2275 | 2024-05-10 | Aurora            | W   | 0.616      | 0.435        | 0.421 (0.113)    | 0.776 (0.208)    | -         |    18.58 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           48 |     2345 | 2024-05-07 | RUSH B            | W   | 0.594      | -            | -                | -                | -         |     5.27 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           47 |     2388 | 2024-05-05 | GL Academy        | W   | 0.580      | -            | -                | -                | -         |     3.29 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           46 |     2390 | 2024-05-04 | Enterprise        | L   | 0.576      | -            | -                | -                | -         |   -12.72 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           45 |     2409 | 2024-05-03 | Nemiga            | L   | 0.568      | -            | -                | -                | -         |    -5.75 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           44 |     2429 | 2024-05-02 | Endpoint          | L   | 0.562      | -            | -                | -                | -         |   -11.92 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           43 |     2442 | 2024-05-02 | ALTERNATE aTTaX   | W   | 0.561      | -            | -                | -                | -         |     7.08 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           42 |     2448 | 2024-05-02 | 9 Pandas          | L   | 0.559      | -            | -                | -                | -         |   -11.05 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           41 |     2463 | 2024-05-01 | BLEED             | W   | 0.554      | -            | -                | -                | -         |     9.30 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           40 |     2475 | 2024-04-30 | ECLOT             | W   | 0.549      | -            | -                | -                | -         |    12.02 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           39 |     2486 | 2024-04-30 | V1dar             | W   | 0.547      | -            | -                | -                | -         |     0.96 | Burmylov, Chr1zN, PR, sirah, TOBIZ     |
|           38 |     2498 | 2024-04-29 | Nemiga            | L   | 0.542      | -            | -                | -                | -         |    -5.84 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           37 |     2511 | 2024-04-29 | Grannys Knockers  | W   | 0.540      | -            | -                | -                | -         |     3.04 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           36 |     2539 | 2024-04-27 | ECLOT             | W   | 0.529      | -            | -                | -                | -         |    11.95 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           35 |     2611 | 2024-04-25 | Insilio           | L   | 0.513      | -            | -                | -                | -         |   -10.75 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           34 |     2622 | 2024-04-24 | PARIVISION        | L   | 0.508      | -            | -                | -                | -         |    -7.68 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           33 |     2656 | 2024-04-22 | EYEBALLERS        | W   | 0.494      | -            | -                | -                | -         |     4.50 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           32 |     2664 | 2024-04-22 | Nemiga            | L   | 0.493      | -            | -                | -                | -         |    -5.33 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           31 |     2673 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.488      | -            | -                | -                | -         |     5.61 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           30 |     2680 | 2024-04-21 | ECLOT             | L   | 0.487      | -            | -                | -                | -         |    -4.70 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           29 |     2701 | 2024-04-20 | BLEED             | L   | 0.481      | -            | -                | -                | -         |    -8.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           28 |     2799 | 2024-04-18 | Enterprise        | W   | 0.468      | -            | -                | -                | -         |     4.84 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           27 |     2809 | 2024-04-18 | ENCE Academy      | W   | 0.467      | -            | -                | -                | -         |     2.10 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           26 |     2858 | 2024-04-17 | JANO              | W   | 0.459      | -            | -                | -                | -         |     1.67 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           25 |     2872 | 2024-04-16 | GamerLegion       | L   | 0.454      | -            | -                | -                | -         |    -5.85 | Anlelele, Burmylov, Neityu, PR, sirah  |
|           24 |     2897 | 2024-04-15 | Alliance          | W   | 0.446      | -            | -                | -                | -         |     3.50 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           23 |     2937 | 2024-04-12 | Permitta          | L   | 0.427      | -            | -                | -                | -         |    -8.28 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           22 |     3064 | 2024-04-09 | Zero Tenacity     | W   | 0.408      | -            | -                | -                | -         |     7.00 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           21 |     3099 | 2024-04-08 | B8                | W   | 0.401      | -            | -                | -                | -         |     6.75 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           20 |     3223 | 2024-04-03 | PARIVISION        | W   | 0.369      | -            | -                | -                | -         |     6.89 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           19 |     3554 | 2024-03-16 | Sampi             | L   | 0.246      | -            | -                | -                | -         |    -5.36 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           18 |     3572 | 2024-03-15 | Entropiq          | W   | 0.241      | -            | -                | -                | -         |     0.48 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           17 |     3623 | 2024-03-13 | Permitta          | L   | 0.229      | -            | -                | -                | -         |    -4.30 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           16 |     3641 | 2024-03-13 | Alliance          | W   | 0.227      | -            | -                | -                | -         |     1.89 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           15 |     3668 | 2024-03-12 | AURA              | W   | 0.221      | -            | -                | -                | -         |     0.30 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           14 |     3675 | 2024-03-12 | Sampi             | L   | 0.220      | -            | -                | -                | -         |    -4.89 | Burmylov, Chr1zN, Neityu, sirah, xReal |
|           13 |     3695 | 2024-03-11 | Passion UA        | W   | 0.214      | -            | -                | -                | -         |     3.73 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           12 |     3697 | 2024-03-11 | NOM               | W   | 0.213      | -            | -                | -                | -         |     0.31 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           11 |     3703 | 2024-03-10 | V1dar             | W   | 0.209      | -            | -                | -                | -         |     0.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           10 |     3715 | 2024-03-10 | Passion UA        | L   | 0.207      | -            | -                | -                | -         |    -2.96 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            9 |     3719 | 2024-03-10 | ALTERNATE aTTaX   | W   | 0.207      | -            | -                | -                | -         |     2.70 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            8 |     3756 | 2024-03-08 | Fraud5            | W   | 0.195      | -            | -                | -                | -         |     0.60 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            7 |     3773 | 2024-03-07 | INGLORIOUS        | L   | 0.189      | -            | -                | -                | -         |    -5.63 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            6 |     3907 | 2024-03-03 | ex-Preasy         | W   | 0.160      | -            | -                | -                | -         |     0.90 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            5 |     3920 | 2024-03-02 | kONO              | W   | 0.154      | -            | -                | -                | -         |     1.03 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            4 |     3990 | 2024-02-27 | ECLOT             | L   | 0.128      | -            | -                | -                | -         |    -1.14 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            3 |     4005 | 2024-02-26 | BLEED             | W   | 0.121      | -            | -                | -                | -         |     1.43 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            2 |     4068 | 2024-02-24 | Sashi             | W   | 0.106      | -            | -                | -                | -         |     2.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            1 |     4130 | 2024-02-21 | Entropiq          | W   | 0.086      | -            | -                | -                | -         |     0.16 | Burmylov, Chr1zN, Neityu, PR, sirah    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,443.26)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-02 |      0.768 | $5,000.00      | $3,840.28       |
| 2024-05-26 |      0.722 | $10,000.00     | $7,216.67       |
| 2024-05-18 |      0.669 | $500.00        | $334.31         |
| 2024-05-12 |      0.629 | $5,000.00      | $3,142.71       |
| 2024-05-03 |      0.568 | $25,000.00     | $14,201.39      |
| 2024-03-18 |      0.260 | $1,000.00      | $259.72         |
| 2024-03-11 |      0.214 | $3,500.00      | $748.61         |
| 2024-02-28 |      0.133 | $1,500.00      | $199.58         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
