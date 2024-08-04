### Roster Details<br />
Team Name: G2<br />
Roster: huNter-, m0NESY, malbsMd, NiKo, Snax<br />
Global Rank: [1](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [1]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1961.0<br />
<br />
Final Rank Value (1961.0) = Starting Rank Value (2000.0) + Head To Head Adjustments (-39.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.757[<sup>2</sup>](#table1)
- Opponent Network: 0.373[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.783<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 2000.0
- 400 + ( ( 0.783 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 2000.0


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
|           42 |        5 | 2024-08-03 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.553 (0.321)    | 1 (1.000) |     3.30 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           41 |       94 | 2024-08-01 | FaZe              | W   | 1.000      | 0.581        | 0.640 (0.372)    | 0.402 (0.234)    | 1 (1.000) |     6.29 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           40 |      138 | 2024-07-31 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.553 (0.321)    | 1 (1.000) |     3.16 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           39 |      448 | 2024-07-21 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |   -16.18 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           38 |      493 | 2024-07-20 | Virtus.pro        | W   | 1.000      | 1.000        | 0.497 (0.497)    | 0.323 (0.323)    | 1 (1.000) |     5.80 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           37 |      560 | 2024-07-18 | Spirit            | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.460 (0.460)    | 1 (1.000) |    14.69 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           36 |      660 | 2024-07-17 | The MongolZ       | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.721 (0.721)    | 1 (1.000) |     8.99 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           35 |     1072 | 2024-06-13 | Vitality          | L   | 0.855      | -            | -                | -                | -         |   -17.16 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           34 |     1528 | 2024-06-02 | Vitality          | W   | 0.782      | 0.624        | 0.649 (0.317)    | -                | 1 (0.782) |     9.50 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           33 |     1550 | 2024-06-01 | 9z                | W   | 0.776      | 0.624        | 0.406 (0.197)    | 0.619 (0.300)    | 1 (0.776) |     1.69 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           32 |     1587 | 2024-05-31 | FaZe              | W   | 0.770      | 0.624        | 0.640 (0.307)    | -                | 1 (0.770) |     5.87 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           31 |     1637 | 2024-05-29 | Liquid            | W   | 0.757      | 0.624        | -                | 0.460 (0.217)    | 1 (0.757) |     2.30 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           30 |     1660 | 2024-05-28 | MOUZ              | W   | 0.751      | 0.624        | 1.000 (0.469)    | -                | -         |    10.32 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           29 |     1684 | 2024-05-27 | Vitality          | L   | 0.743      | -            | -                | -                | -         |   -13.97 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           28 |     1695 | 2024-05-27 | Falcons           | W   | 0.742      | -            | -                | -                | -         |     1.27 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           27 |     2234 | 2024-05-09 | MOUZ              | L   | 0.622      | -            | -                | -                | -         |   -12.10 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           26 |     2260 | 2024-05-08 | 3DMAX             | W   | 0.615      | 0.889        | 0.506 (0.276)    | 1.000 (0.546)    | -         |     2.53 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           25 |     2278 | 2024-05-07 | BIG               | W   | 0.608      | -            | -                | -                | -         |     0.51 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           24 |     2455 | 2024-04-28 | M80               | W   | 0.549      | 0.889        | -                | 0.587 (0.286)    | -         |     0.34 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           23 |     2490 | 2024-04-27 | Falcons           | W   | 0.540      | -            | -                | -                | -         |     0.80 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           22 |     2513 | 2024-04-26 | M80               | L   | 0.534      | -            | -                | -                | -         |   -16.52 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           21 |     2542 | 2024-04-25 | The MongolZ       | L   | 0.527      | -            | -                | -                | -         |    -9.69 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           20 |     2562 | 2024-04-24 | TYLOO             | W   | 0.520      | -            | -                | -                | -         |     0.02 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           19 |     2863 | 2024-04-13 | MOUZ              | L   | 0.446      | -            | -                | -                | -         |    -9.33 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           18 |     2876 | 2024-04-12 | Virtus.pro        | W   | 0.439      | -            | -                | -                | -         |     2.30 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           17 |     2946 | 2024-04-10 | HEROIC            | W   | 0.427      | -            | -                | -                | -         |     1.23 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           16 |     3006 | 2024-04-09 | Lynn Vision       | W   | 0.420      | -            | -                | -                | -         |     0.06 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           15 |     3037 | 2024-04-08 | Liquid            | L   | 0.413      | -            | -                | -                | -         |   -12.21 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           14 |     3046 | 2024-04-07 | 9z                | W   | 0.412      | -            | -                | -                | -         |     1.03 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           13 |     3238 | 2024-03-30 | Natus Vincere     | L   | 0.356      | -            | -                | -                | -         |    -6.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           12 |     3245 | 2024-03-29 | MOUZ              | W   | 0.349      | 1.000        | 1.000 (0.349)    | -                | -         |     3.45 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           11 |     3342 | 2024-03-24 | Virtus.pro        | W   | 0.314      | -            | -                | -                | -         |     1.63 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           10 |     3354 | 2024-03-23 | Gaimin Gladiators | W   | 0.308      | -            | -                | -                | -         |     0.04 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            9 |     3372 | 2024-03-22 | Cloud9            | L   | 0.301      | -            | -                | -                | -         |    -9.42 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            8 |     3382 | 2024-03-21 | Natus Vincere     | L   | 0.296      | -            | -                | -                | -         |    -5.02 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            7 |     3391 | 2024-03-21 | FURIA             | W   | 0.295      | -            | -                | -                | -         |     1.50 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            6 |     4211 | 2024-02-15 | FaZe              | W   | 0.061      | -            | -                | -                | -         |     0.28 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            5 |     4241 | 2024-02-14 | Eternal Fire      | W   | 0.056      | -            | -                | -                | -         |     0.27 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            4 |     4258 | 2024-02-14 | Into the Breach   | W   | 0.054      | -            | -                | -                | -         |     0.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            3 |     4323 | 2024-02-09 | FaZe              | L   | 0.021      | -            | -                | -                | -         |    -0.58 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            2 |     4351 | 2024-02-06 | HEROIC            | W   | 0.002      | -            | -                | -                | -         |     0.01 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            1 |     4357 | 2024-02-06 | Monte             | W   | 0.001      | -            | -                | -                | -         |     0.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($344,438.80)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $175,000.00    | $175,000.00     |
| 2024-06-16 |      0.874 | $10,000.00     | $8,744.44       |
| 2024-06-02 |      0.782 | $100,000.00    | $78,222.22      |
| 2024-05-12 |      0.641 | $32,000.00     | $20,524.44      |
| 2024-04-14 |      0.453 | $20,000.00     | $9,069.91       |
| 2024-03-31 |      0.362 | $80,000.00     | $28,977.78      |
| 2024-02-11 |      0.035 | $40,000.00     | $1,400.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
