### Roster Details<br />
Team Name: MOUZ NXT<br />
Roster: Burmylov, Neityu, PR, sirah, TOBIZ<br />
Global Rank: [44](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [32]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1107.9<br />
<br />
Final Rank Value (1107.9) = Starting Rank Value (1047.3) + Head To Head Adjustments (60.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.538[<sup>1</sup>](#table2)
- Bounty Collected: 0.457[<sup>2</sup>](#table1)
- Opponent Network: 0.263[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.315<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1047.3
- 400 + ( ( 0.315 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1047.3


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
|           90 |       84 | 2024-08-03 | 1WIN              | L   | 1.000      | -            | -                | -                | -         |   -21.31 | Burmylov, Neityu, PR, sirah, TOBIZ     |
|           89 |      289 | 2024-07-29 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.35 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           88 |      292 | 2024-07-29 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.04 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           87 |      348 | 2024-07-27 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.24 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           86 |      423 | 2024-07-25 | Aurora Young Blud | W   | 1.000      | 0.435        | -                | 0.522 (0.227)    | 0 (0.000) |     9.35 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           85 |      543 | 2024-07-21 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.35 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           84 |      583 | 2024-07-20 | BLEED             | W   | 1.000      | 0.500        | 0.125 (0.063)    | 0.538 (0.269)    | 0 (0.000) |    24.57 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           83 |      597 | 2024-07-19 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.035)    | 0.427 (0.214)    | 0 (0.000) |    11.71 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           82 |      647 | 2024-07-18 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -1.66 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           81 |      789 | 2024-07-16 | Rhyno             | W   | 1.000      | 0.500        | 0.071 (0.035)    | 0.427 (0.214)    | 0 (0.000) |    12.14 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           80 |     1171 | 2024-06-13 | B8                | L   | 0.838      | -            | -                | -                | -         |   -11.18 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           79 |     1232 | 2024-06-10 | Endpoint          | L   | 0.819      | -            | -                | -                | -         |   -20.04 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           78 |     1268 | 2024-06-09 | GhoulsW           | W   | 0.813      | -            | -                | -                | 0 (0.000) |     0.49 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           77 |     1287 | 2024-06-09 | BLEED             | L   | 0.812      | -            | -                | -                | -         |    -4.76 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           76 |     1344 | 2024-06-08 | Sampi             | W   | 0.806      | 0.435        | -                | 1.000 (0.350)    | 0 (0.000) |     6.49 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           75 |     1356 | 2024-06-08 | ECLOT             | L   | 0.805      | -            | -                | -                | -         |   -11.08 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           74 |     1384 | 2024-06-07 | GamerLegion       | L   | 0.800      | -            | -                | -                | -         |   -10.60 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           73 |     1449 | 2024-06-06 | Rhyno             | W   | 0.794      | 0.500        | 0.071 (0.028)    | -                | 0 (0.000) |     8.07 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           72 |     1478 | 2024-06-06 | Entropiq          | W   | 0.792      | -            | -                | -                | 0 (0.000) |     0.46 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           71 |     1576 | 2024-06-04 | NAVI Junior       | W   | 0.779      | -            | -                | -                | -         |     2.58 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           70 |     1583 | 2024-06-04 | Aurora Young Blud | W   | 0.778      | -            | -                | -                | -         |     5.68 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           69 |     1621 | 2024-06-02 | FURIA             | L   | 0.765      | -            | -                | -                | -         |    -1.43 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           68 |     1655 | 2024-06-01 | AMKAL             | W   | 0.759      | 0.435        | 0.130 (0.043)    | -                | -         |    15.04 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           67 |     1714 | 2024-05-30 | Sangal            | W   | 0.745      | 0.435        | 0.288 (0.093)    | 0.858 (0.278)    | -         |    14.27 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           66 |     1755 | 2024-05-28 | RUBY              | W   | 0.733      | 0.435        | 0.095 (0.030)    | -                | -         |     7.65 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           65 |     1782 | 2024-05-27 | Nexus             | W   | 0.725      | -            | -                | -                | -         |     3.94 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           64 |     1790 | 2024-05-26 | 9 Pandas          | L   | 0.720      | -            | -                | -                | -         |   -11.57 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           63 |     1798 | 2024-05-26 | B8                | W   | 0.718      | 0.435        | 0.170 (0.053)    | 0.912 (0.285)    | -         |    14.63 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           62 |     1823 | 2024-05-25 | 3DMAX             | W   | 0.711      | 0.435        | 0.510 (0.158)    | 1.000 (0.309)    | -         |    21.25 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           61 |     1836 | 2024-05-24 | Illuminar         | W   | 0.705      | -            | -                | -                | -         |     6.30 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           60 |     1849 | 2024-05-23 | Rare Atom         | W   | 0.699      | -            | -                | -                | -         |     5.65 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           59 |     1889 | 2024-05-22 | Rhyno             | L   | 0.692      | -            | -                | -                | -         |   -12.58 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           58 |     1931 | 2024-05-21 | DMS               | L   | 0.686      | -            | -                | -                | -         |   -14.69 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           57 |     2000 | 2024-05-19 | BLEED             | L   | 0.671      | -            | -                | -                | -         |    -2.99 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           56 |     2066 | 2024-05-17 | DMS               | W   | 0.658      | -            | -                | -                | -         |     6.44 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           55 |     2091 | 2024-05-16 | Sampi             | W   | 0.653      | 0.435        | -                | 1.000 (0.284)    | -         |     6.74 | Chr1zN, Neityu, PR, sirah, TOBIZ       |
|           54 |     2154 | 2024-05-15 | BLEED             | L   | 0.645      | -            | -                | -                | -         |    -2.30 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           53 |     2207 | 2024-05-14 | B8                | L   | 0.638      | -            | -                | -                | -         |    -8.71 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           52 |     2231 | 2024-05-13 | Space             | W   | 0.631      | -            | -                | -                | -         |     4.46 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           51 |     2253 | 2024-05-12 | B8                | L   | 0.625      | -            | -                | -                | -         |    -9.37 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           50 |     2267 | 2024-05-11 | Endpoint          | W   | 0.620      | -            | -                | -                | -         |     6.89 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           49 |     2293 | 2024-05-10 | Aurora            | W   | 0.614      | 0.435        | 0.420 (0.112)    | 0.758 (0.202)    | -         |    18.53 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           48 |     2363 | 2024-05-07 | RUSH B            | W   | 0.592      | -            | -                | -                | -         |     5.23 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           47 |     2406 | 2024-05-05 | GL Academy        | W   | 0.578      | -            | -                | -                | -         |     3.26 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           46 |     2408 | 2024-05-04 | Enterprise        | L   | 0.574      | -            | -                | -                | -         |   -12.72 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           45 |     2427 | 2024-05-03 | Nemiga            | L   | 0.566      | -            | -                | -                | -         |    -5.75 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           44 |     2447 | 2024-05-02 | Endpoint          | L   | 0.560      | -            | -                | -                | -         |   -11.89 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           43 |     2460 | 2024-05-02 | ALTERNATE aTTaX   | W   | 0.559      | -            | -                | -                | -         |     7.11 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           42 |     2466 | 2024-05-02 | 9 Pandas          | L   | 0.558      | -            | -                | -                | -         |   -10.87 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           41 |     2481 | 2024-05-01 | BLEED             | W   | 0.552      | -            | -                | -                | -         |     9.26 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           40 |     2493 | 2024-04-30 | ECLOT             | W   | 0.547      | -            | -                | -                | -         |    11.97 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           39 |     2504 | 2024-04-30 | V1dar             | W   | 0.545      | -            | -                | -                | -         |     0.94 | Burmylov, Chr1zN, PR, sirah, TOBIZ     |
|           38 |     2516 | 2024-04-29 | Nemiga            | L   | 0.540      | -            | -                | -                | -         |    -5.84 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           37 |     2529 | 2024-04-29 | Grannys Knockers  | W   | 0.538      | -            | -                | -                | -         |     3.00 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           36 |     2557 | 2024-04-27 | ECLOT             | W   | 0.527      | -            | -                | -                | -         |    11.89 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           35 |     2629 | 2024-04-25 | Insilio           | L   | 0.511      | -            | -                | -                | -         |   -10.73 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           34 |     2640 | 2024-04-24 | PARIVISION        | L   | 0.506      | -            | -                | -                | -         |    -6.96 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           33 |     2674 | 2024-04-22 | EYEBALLERS        | W   | 0.493      | -            | -                | -                | -         |     4.49 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           32 |     2682 | 2024-04-22 | Nemiga            | L   | 0.491      | -            | -                | -                | -         |    -5.33 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           31 |     2691 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.486      | -            | -                | -                | -         |     5.64 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           30 |     2698 | 2024-04-21 | ECLOT             | L   | 0.485      | -            | -                | -                | -         |    -4.68 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           29 |     2719 | 2024-04-20 | BLEED             | L   | 0.480      | -            | -                | -                | -         |    -8.33 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           28 |     2817 | 2024-04-18 | Enterprise        | W   | 0.466      | -            | -                | -                | -         |     4.79 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           27 |     2827 | 2024-04-18 | ENCE Academy      | W   | 0.465      | -            | -                | -                | -         |     2.07 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           26 |     2876 | 2024-04-17 | JANO              | W   | 0.457      | -            | -                | -                | -         |     1.65 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           25 |     2890 | 2024-04-16 | GamerLegion       | L   | 0.453      | -            | -                | -                | -         |    -5.88 | Anlelele, Burmylov, Neityu, PR, sirah  |
|           24 |     2915 | 2024-04-15 | Alliance          | W   | 0.445      | -            | -                | -                | -         |     3.47 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           23 |     2955 | 2024-04-12 | Permitta          | L   | 0.425      | -            | -                | -                | -         |    -7.99 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           22 |     3082 | 2024-04-09 | Zero Tenacity     | W   | 0.406      | -            | -                | -                | -         |     6.92 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           21 |     3117 | 2024-04-08 | B8                | W   | 0.399      | -            | -                | -                | -         |     6.75 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           20 |     3241 | 2024-04-03 | PARIVISION        | W   | 0.367      | -            | -                | -                | -         |     7.40 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           19 |     3572 | 2024-03-16 | Sampi             | L   | 0.245      | -            | -                | -                | -         |    -5.33 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           18 |     3590 | 2024-03-15 | Entropiq          | W   | 0.239      | -            | -                | -                | -         |     0.47 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           17 |     3641 | 2024-03-13 | Permitta          | L   | 0.228      | -            | -                | -                | -         |    -4.10 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           16 |     3659 | 2024-03-13 | Alliance          | W   | 0.225      | -            | -                | -                | -         |     1.87 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           15 |     3686 | 2024-03-12 | AURA              | W   | 0.220      | -            | -                | -                | -         |     0.29 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           14 |     3693 | 2024-03-12 | Sampi             | L   | 0.218      | -            | -                | -                | -         |    -4.86 | Burmylov, Chr1zN, Neityu, sirah, xReal |
|           13 |     3713 | 2024-03-11 | Passion UA        | W   | 0.212      | -            | -                | -                | -         |     3.68 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           12 |     3715 | 2024-03-11 | NOM               | W   | 0.211      | -            | -                | -                | -         |     0.30 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           11 |     3721 | 2024-03-10 | V1dar             | W   | 0.207      | -            | -                | -                | -         |     0.33 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           10 |     3733 | 2024-03-10 | Passion UA        | L   | 0.206      | -            | -                | -                | -         |    -2.94 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            9 |     3737 | 2024-03-10 | ALTERNATE aTTaX   | W   | 0.205      | -            | -                | -                | -         |     2.70 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            8 |     3774 | 2024-03-08 | Fraud5            | W   | 0.193      | -            | -                | -                | -         |     0.59 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            7 |     3791 | 2024-03-07 | INGLORIOUS        | L   | 0.187      | -            | -                | -                | -         |    -5.58 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            6 |     3925 | 2024-03-03 | ex-Preasy         | W   | 0.158      | -            | -                | -                | -         |     0.89 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            5 |     3938 | 2024-03-02 | kONO              | W   | 0.152      | -            | -                | -                | -         |     1.01 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            4 |     4008 | 2024-02-27 | ECLOT             | L   | 0.126      | -            | -                | -                | -         |    -1.12 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            3 |     4023 | 2024-02-26 | BLEED             | W   | 0.119      | -            | -                | -                | -         |     1.41 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            2 |     4086 | 2024-02-24 | Sashi             | W   | 0.105      | -            | -                | -                | -         |     2.16 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            1 |     4148 | 2024-02-21 | Entropiq          | W   | 0.085      | -            | -                | -                | -         |     0.15 | Burmylov, Chr1zN, Neityu, PR, sirah    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,350.28)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-02 |      0.766 | $5,000.00      | $3,831.25       |
| 2024-05-26 |      0.720 | $10,000.00     | $7,198.61       |
| 2024-05-18 |      0.667 | $500.00        | $333.40         |
| 2024-05-12 |      0.627 | $5,000.00      | $3,133.68       |
| 2024-05-03 |      0.566 | $25,000.00     | $14,156.25      |
| 2024-03-18 |      0.258 | $1,000.00      | $257.92         |
| 2024-03-11 |      0.212 | $3,500.00      | $742.29         |
| 2024-02-28 |      0.131 | $1,500.00      | $196.88         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
