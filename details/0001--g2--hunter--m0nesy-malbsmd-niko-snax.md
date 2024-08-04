### Roster Details<br />
Team Name: G2<br />
Roster: huNter-, m0NESY, malbsMd, NiKo, Snax<br />
Global Rank: [1](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [1]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1963.5<br />
<br />
Final Rank Value (1963.5) = Starting Rank Value (2000.0) + Head To Head Adjustments (-36.5)<br />

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
|           41 |       13 | 2024-08-03 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.553 (0.321)    | 1 (1.000) |     3.42 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           40 |      102 | 2024-08-01 | FaZe              | W   | 1.000      | 0.581        | 0.639 (0.371)    | 0.402 (0.234)    | 1 (1.000) |     6.32 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           39 |      146 | 2024-07-31 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.553 (0.321)    | 1 (1.000) |     3.28 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           38 |      456 | 2024-07-21 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |   -16.18 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           37 |      501 | 2024-07-20 | Virtus.pro        | W   | 1.000      | 1.000        | 0.497 (0.497)    | 0.323 (0.323)    | 1 (1.000) |     5.83 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           36 |      568 | 2024-07-18 | Spirit            | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.460 (0.460)    | 1 (1.000) |    14.63 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           35 |      668 | 2024-07-17 | The MongolZ       | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.721 (0.721)    | 1 (1.000) |     9.07 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           34 |     1080 | 2024-06-13 | Vitality          | L   | 0.854      | -            | -                | -                | -         |   -17.05 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           33 |     1536 | 2024-06-02 | Vitality          | W   | 0.782      | 0.624        | 0.649 (0.317)    | -                | 1 (0.782) |     9.59 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           32 |     1558 | 2024-06-01 | 9z                | W   | 0.776      | 0.624        | 0.405 (0.196)    | 0.618 (0.299)    | 1 (0.776) |     1.70 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           31 |     1595 | 2024-05-31 | FaZe              | W   | 0.769      | 0.624        | 0.639 (0.307)    | -                | 1 (0.769) |     5.91 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           30 |     1645 | 2024-05-29 | Liquid            | W   | 0.756      | 0.624        | -                | 0.460 (0.217)    | 1 (0.756) |     3.18 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           29 |     1668 | 2024-05-28 | MOUZ              | W   | 0.750      | 0.624        | 1.000 (0.468)    | -                | -         |    10.36 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           28 |     1692 | 2024-05-27 | Vitality          | L   | 0.743      | -            | -                | -                | -         |   -13.82 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           27 |     1703 | 2024-05-27 | Falcons           | W   | 0.741      | -            | -                | -                | -         |     1.27 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           26 |     2242 | 2024-05-09 | MOUZ              | L   | 0.621      | -            | -                | -                | -         |   -12.03 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           25 |     2268 | 2024-05-08 | 3DMAX             | W   | 0.614      | 0.889        | 0.506 (0.276)    | 1.000 (0.546)    | -         |     2.53 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           24 |     2286 | 2024-05-07 | BIG               | W   | 0.607      | -            | -                | -                | -         |     0.51 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           23 |     2463 | 2024-04-28 | M80               | W   | 0.548      | 0.889        | -                | 0.587 (0.286)    | -         |     0.34 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           22 |     2498 | 2024-04-27 | Falcons           | W   | 0.540      | -            | -                | -                | -         |     0.79 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           21 |     2521 | 2024-04-26 | M80               | L   | 0.533      | -            | -                | -                | -         |   -16.49 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           20 |     2550 | 2024-04-25 | The MongolZ       | L   | 0.526      | -            | -                | -                | -         |    -9.64 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           19 |     2570 | 2024-04-24 | TYLOO             | W   | 0.520      | -            | -                | -                | -         |     0.02 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           18 |     2871 | 2024-04-13 | MOUZ              | L   | 0.445      | -            | -                | -                | -         |    -9.30 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           17 |     2884 | 2024-04-12 | Virtus.pro        | W   | 0.438      | -            | -                | -                | -         |     2.32 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           16 |     2954 | 2024-04-10 | HEROIC            | W   | 0.426      | -            | -                | -                | -         |     1.24 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           15 |     3014 | 2024-04-09 | Lynn Vision       | W   | 0.420      | -            | -                | -                | -         |     0.08 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           14 |     3045 | 2024-04-08 | Liquid            | L   | 0.412      | -            | -                | -                | -         |   -11.72 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           13 |     3054 | 2024-04-07 | 9z                | W   | 0.411      | -            | -                | -                | -         |     1.03 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           12 |     3246 | 2024-03-30 | Natus Vincere     | L   | 0.355      | -            | -                | -                | -         |    -5.97 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           11 |     3253 | 2024-03-29 | MOUZ              | W   | 0.349      | 1.000        | 1.000 (0.349)    | -                | -         |     3.46 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           10 |     3350 | 2024-03-24 | Virtus.pro        | W   | 0.314      | -            | -                | -                | -         |     1.64 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            9 |     3362 | 2024-03-23 | Gaimin Gladiators | W   | 0.307      | -            | -                | -                | -         |     0.04 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            8 |     3380 | 2024-03-22 | Cloud9            | L   | 0.300      | -            | -                | -                | -         |    -9.40 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            7 |     3390 | 2024-03-21 | Natus Vincere     | L   | 0.295      | -            | -                | -                | -         |    -4.99 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            6 |     3399 | 2024-03-21 | FURIA             | W   | 0.294      | -            | -                | -                | -         |     1.51 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            5 |     4219 | 2024-02-15 | FaZe              | W   | 0.060      | -            | -                | -                | -         |     0.28 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            4 |     4249 | 2024-02-14 | Eternal Fire      | W   | 0.055      | -            | -                | -                | -         |     0.27 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            3 |     4266 | 2024-02-14 | Into the Breach   | W   | 0.053      | -            | -                | -                | -         |     0.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            2 |     4331 | 2024-02-09 | FaZe              | L   | 0.021      | -            | -                | -                | -         |    -0.56 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            1 |     4359 | 2024-02-06 | HEROIC            | W   | 0.002      | -            | -                | -                | -         |     0.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($344,236.44)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $175,000.00    | $175,000.00     |
| 2024-06-16 |      0.874 | $10,000.00     | $8,737.27       |
| 2024-06-02 |      0.782 | $100,000.00    | $78,150.46      |
| 2024-05-12 |      0.641 | $32,000.00     | $20,501.48      |
| 2024-04-14 |      0.453 | $20,000.00     | $9,055.56       |
| 2024-03-31 |      0.362 | $80,000.00     | $28,920.37      |
| 2024-02-11 |      0.034 | $40,000.00     | $1,371.30       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
