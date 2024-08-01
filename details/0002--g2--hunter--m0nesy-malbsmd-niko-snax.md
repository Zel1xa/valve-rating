### Roster Details<br />
Team Name: G2<br />
Roster: huNter-, m0NESY, malbsMd, NiKo, Snax<br />
Global Rank: [2](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [2]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1956.5<br />
<br />
Final Rank Value (1956.5) = Starting Rank Value (2000.0) + Head To Head Adjustments (-43.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.756[<sup>2</sup>](#table1)
- Opponent Network: 0.352[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.777<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 2000.0
- 400 + ( ( 0.777 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 2000.0


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
|           43 |        3 | 2024-08-01 | FaZe              | W   | 1.000      | 0.581        | 0.638 (0.371)    | 0.408 (0.237)    | 1 (1.000) |     7.03 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           42 |       49 | 2024-07-31 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.409 (0.237)    | 1 (1.000) |     1.71 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           41 |      361 | 2024-07-21 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |   -15.58 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           40 |      408 | 2024-07-20 | Virtus.pro        | W   | 1.000      | 1.000        | 0.483 (0.483)    | 0.326 (0.326)    | 1 (1.000) |     5.97 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           39 |      481 | 2024-07-18 | Spirit            | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.424 (0.424)    | 1 (1.000) |    15.19 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           38 |      581 | 2024-07-17 | The MongolZ       | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.719 (0.719)    | 1 (1.000) |     9.03 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           37 |      990 | 2024-06-13 | Vitality          | L   | 0.874      | -            | -                | -                | -         |   -17.57 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           36 |     1463 | 2024-06-02 | Vitality          | W   | 0.802      | 0.624        | 0.591 (0.296)    | -                | 1 (0.802) |     9.71 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           35 |     1485 | 2024-06-01 | 9z                | W   | 0.796      | 0.624        | -                | 0.554 (0.275)    | 1 (0.796) |     0.47 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           34 |     1522 | 2024-05-31 | FaZe              | W   | 0.789      | 0.624        | 0.638 (0.314)    | 0.408 (0.201)    | 1 (0.789) |     6.75 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           33 |     1572 | 2024-05-29 | Liquid            | W   | 0.776      | 0.624        | -                | 0.429 (0.208)    | 1 (0.776) |     1.97 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           32 |     1595 | 2024-05-28 | MOUZ              | W   | 0.770      | 0.624        | 1.000 (0.481)    | -                | 1 (0.770) |    11.31 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           31 |     1619 | 2024-05-27 | Vitality          | L   | 0.763      | -            | -                | -                | -         |   -14.31 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           30 |     1630 | 2024-05-27 | Falcons           | W   | 0.762      | -            | -                | -                | -         |     1.46 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           29 |     2206 | 2024-05-09 | MOUZ              | L   | 0.642      | -            | -                | -                | -         |   -11.75 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           28 |     2234 | 2024-05-08 | 3DMAX             | W   | 0.634      | 0.889        | 0.505 (0.285)    | 1.000 (0.564)    | -         |     2.63 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           27 |     2252 | 2024-05-07 | BIG               | W   | 0.627      | -            | -                | -                | -         |     0.38 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           26 |     2432 | 2024-04-28 | M80               | W   | 0.568      | 0.889        | -                | 0.641 (0.324)    | -         |     0.39 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           25 |     2468 | 2024-04-27 | Falcons           | W   | 0.560      | -            | -                | -                | -         |     0.93 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           24 |     2491 | 2024-04-26 | M80               | L   | 0.553      | -            | -                | -                | -         |   -17.09 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           23 |     2519 | 2024-04-25 | The MongolZ       | L   | 0.547      | -            | -                | -                | -         |    -9.89 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           22 |     2539 | 2024-04-24 | TYLOO             | W   | 0.540      | -            | -                | -                | -         |     0.02 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           21 |     2850 | 2024-04-13 | MOUZ              | L   | 0.465      | -            | -                | -                | -         |    -9.23 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           20 |     2864 | 2024-04-12 | Virtus.pro        | W   | 0.459      | -            | -                | -                | -         |     2.57 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           19 |     2934 | 2024-04-10 | HEROIC            | W   | 0.447      | -            | -                | -                | -         |     1.36 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           18 |     2994 | 2024-04-09 | Lynn Vision       | W   | 0.440      | -            | -                | -                | -         |     0.06 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           17 |     3025 | 2024-04-08 | Liquid            | L   | 0.433      | -            | -                | -                | -         |   -12.96 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           16 |     3034 | 2024-04-07 | 9z                | W   | 0.431      | -            | -                | -                | -         |     0.13 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           15 |     3234 | 2024-03-30 | Natus Vincere     | L   | 0.376      | -            | -                | -                | -         |    -6.07 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           14 |     3241 | 2024-03-29 | MOUZ              | W   | 0.369      | 1.000        | 1.000 (0.369)    | -                | -         |     4.04 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           13 |     3343 | 2024-03-24 | Virtus.pro        | W   | 0.334      | 1.000        | 0.483 (0.161)    | -                | -         |     1.85 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           12 |     3355 | 2024-03-23 | Gaimin Gladiators | W   | 0.328      | -            | -                | -                | -         |     0.05 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           11 |     3373 | 2024-03-22 | Cloud9            | L   | 0.320      | -            | -                | -                | -         |   -10.02 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           10 |     3383 | 2024-03-21 | Natus Vincere     | L   | 0.316      | -            | -                | -                | -         |    -5.12 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            9 |     3392 | 2024-03-21 | FURIA             | W   | 0.314      | -            | -                | -                | -         |     1.74 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            8 |     4233 | 2024-02-15 | FaZe              | W   | 0.080      | -            | -                | -                | -         |     0.43 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            7 |     4263 | 2024-02-14 | Eternal Fire      | W   | 0.075      | -            | -                | -                | -         |     0.40 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            6 |     4280 | 2024-02-14 | Into the Breach   | W   | 0.073      | -            | -                | -                | -         |     0.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            5 |     4355 | 2024-02-09 | FaZe              | L   | 0.041      | -            | -                | -                | -         |    -1.07 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            4 |     4383 | 2024-02-06 | HEROIC            | W   | 0.022      | -            | -                | -                | -         |     0.06 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            3 |     4389 | 2024-02-06 | Monte             | W   | 0.020      | -            | -                | -                | -         |     0.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            2 |     4395 | 2024-02-05 | ENCE              | L   | 0.015      | -            | -                | -                | -         |    -0.44 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            1 |     4450 | 2024-02-03 | HEROIC            | W   | 0.000      | -            | -                | -                | -         |     0.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($327,422.13)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $175,000.00    | $175,000.00     |
| 2024-06-16 |      0.894 | $10,000.00     | $8,938.89       |
| 2024-06-02 |      0.802 | $100,000.00    | $80,166.67      |
| 2024-05-12 |      0.661 | $32,000.00     | $21,146.67      |
| 2024-04-14 |      0.473 | $20,000.00     | $9,458.80       |
| 2024-03-31 |      0.382 | $80,000.00     | $30,533.33      |
| 2024-02-11 |      0.054 | $40,000.00     | $2,177.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
