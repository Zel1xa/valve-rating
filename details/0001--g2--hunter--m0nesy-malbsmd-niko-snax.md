### Roster Details<br />
Team Name: G2<br />
Roster: huNter-, m0NESY, malbsMd, NiKo, Snax<br />
Global Rank: [1](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [1]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1964.3<br />
<br />
Final Rank Value (1964.3) = Starting Rank Value (2000.0) + Head To Head Adjustments (-35.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.754[<sup>2</sup>](#table1)
- Opponent Network: 0.357[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.778<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 2000.0
- 400 + ( ( 0.778 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 2000.0


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
|           40 |       74 | 2024-08-03 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.531 (0.309)    | 1 (1.000) |     3.41 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           39 |      165 | 2024-08-01 | FaZe              | W   | 1.000      | 0.581        | 0.625 (0.363)    | 0.383 (0.222)    | 1 (1.000) |     6.14 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           38 |      209 | 2024-07-31 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.531 (0.309)    | 1 (1.000) |     3.27 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           37 |      519 | 2024-07-21 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |   -16.18 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           36 |      564 | 2024-07-20 | Virtus.pro        | W   | 1.000      | 1.000        | 0.498 (0.498)    | 0.309 (0.309)    | 1 (1.000) |     5.75 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           35 |      631 | 2024-07-18 | Spirit            | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.441 (0.441)    | 1 (1.000) |    14.58 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           34 |      731 | 2024-07-17 | The MongolZ       | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.694 (0.694)    | 1 (1.000) |     9.13 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           33 |     1143 | 2024-06-13 | Vitality          | L   | 0.841      | -            | -                | -                | -         |   -16.89 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           32 |     1599 | 2024-06-02 | Vitality          | W   | 0.768      | 0.624        | 0.647 (0.310)    | -                | 1 (0.768) |     9.32 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           31 |     1621 | 2024-06-01 | 9z                | W   | 0.762      | 0.624        | 0.404 (0.192)    | 0.591 (0.281)    | 1 (0.762) |     1.64 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           30 |     1658 | 2024-05-31 | FaZe              | W   | 0.756      | 0.624        | 0.625 (0.295)    | -                | 1 (0.756) |     5.61 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           29 |     1708 | 2024-05-29 | Liquid            | W   | 0.743      | 0.624        | -                | 0.437 (0.203)    | 1 (0.743) |     3.12 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           28 |     1731 | 2024-05-28 | MOUZ              | W   | 0.737      | 0.624        | 1.000 (0.460)    | -                | -         |    10.05 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           27 |     1755 | 2024-05-27 | Vitality          | L   | 0.729      | -            | -                | -                | -         |   -13.71 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           26 |     1766 | 2024-05-27 | Falcons           | W   | 0.728      | -            | -                | -                | -         |     1.21 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           25 |     2305 | 2024-05-09 | MOUZ              | L   | 0.608      | -            | -                | -                | -         |   -11.89 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           24 |     2331 | 2024-05-08 | 3DMAX             | W   | 0.601      | 0.889        | 0.510 (0.272)    | 1.000 (0.534)    | -         |     2.56 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           23 |     2349 | 2024-05-07 | BIG               | W   | 0.594      | -            | -                | -                | -         |     0.49 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           22 |     2526 | 2024-04-28 | M80               | W   | 0.535      | 0.889        | -                | 0.563 (0.268)    | -         |     0.32 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           21 |     2561 | 2024-04-27 | Falcons           | W   | 0.526      | -            | -                | -                | -         |     0.75 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           20 |     2584 | 2024-04-26 | M80               | L   | 0.520      | -            | -                | -                | -         |   -16.09 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           19 |     2613 | 2024-04-25 | The MongolZ       | L   | 0.513      | -            | -                | -                | -         |    -9.38 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           18 |     2633 | 2024-04-24 | TYLOO             | W   | 0.506      | -            | -                | -                | -         |     0.02 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           17 |     2934 | 2024-04-13 | MOUZ              | L   | 0.432      | -            | -                | -                | -         |    -9.08 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           16 |     2947 | 2024-04-12 | Virtus.pro        | W   | 0.425      | -            | -                | -                | -         |     2.21 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           15 |     3017 | 2024-04-10 | HEROIC            | W   | 0.413      | -            | -                | -                | -         |     1.17 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           14 |     3077 | 2024-04-09 | Lynn Vision       | W   | 0.406      | -            | -                | -                | -         |     0.07 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           13 |     3108 | 2024-04-08 | Liquid            | L   | 0.399      | -            | -                | -                | -         |   -11.33 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           12 |     3117 | 2024-04-07 | 9z                | W   | 0.398      | -            | -                | -                | -         |     0.98 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           11 |     3309 | 2024-03-30 | Natus Vincere     | L   | 0.342      | -            | -                | -                | -         |    -5.74 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           10 |     3316 | 2024-03-29 | MOUZ              | W   | 0.335      | 1.000        | 1.000 (0.335)    | -                | -         |     3.28 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            9 |     3413 | 2024-03-24 | Virtus.pro        | W   | 0.300      | -            | -                | -                | -         |     1.54 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            8 |     3425 | 2024-03-23 | Gaimin Gladiators | W   | 0.294      | -            | -                | -                | -         |     0.04 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            7 |     3443 | 2024-03-22 | Cloud9            | L   | 0.287      | -            | -                | -                | -         |    -8.98 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            6 |     3453 | 2024-03-21 | Natus Vincere     | L   | 0.282      | -            | -                | -                | -         |    -4.76 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            5 |     3462 | 2024-03-21 | FURIA             | W   | 0.281      | -            | -                | -                | -         |     1.44 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            4 |     4282 | 2024-02-15 | FaZe              | W   | 0.047      | -            | -                | -                | -         |     0.21 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            3 |     4312 | 2024-02-14 | Eternal Fire      | W   | 0.042      | -            | -                | -                | -         |     0.20 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            2 |     4329 | 2024-02-14 | Into the Breach   | W   | 0.040      | -            | -                | -                | -         |     0.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            1 |     4394 | 2024-02-09 | FaZe              | L   | 0.007      | -            | -                | -                | -         |    -0.20 | HooXi, huNter-, m0NESY, nexa, NiKo    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($340,496.02)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $175,000.00    | $175,000.00     |
| 2024-06-16 |      0.860 | $10,000.00     | $8,604.63       |
| 2024-06-02 |      0.768 | $100,000.00    | $76,824.07      |
| 2024-05-12 |      0.627 | $32,000.00     | $20,077.04      |
| 2024-04-14 |      0.440 | $20,000.00     | $8,790.28       |
| 2024-03-31 |      0.348 | $80,000.00     | $27,859.26      |
| 2024-02-11 |      0.021 | $40,000.00     | $840.74         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
