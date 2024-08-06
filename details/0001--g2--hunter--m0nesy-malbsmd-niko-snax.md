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
|           40 |       81 | 2024-08-03 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.531 (0.309)    | 1 (1.000) |     3.41 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           39 |      172 | 2024-08-01 | FaZe              | W   | 1.000      | 0.581        | 0.625 (0.363)    | 0.382 (0.222)    | 1 (1.000) |     6.13 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           38 |      216 | 2024-07-31 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.531 (0.309)    | 1 (1.000) |     3.27 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           37 |      526 | 2024-07-21 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |   -16.18 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           36 |      571 | 2024-07-20 | Virtus.pro        | W   | 1.000      | 1.000        | 0.499 (0.499)    | 0.308 (0.308)    | 1 (1.000) |     5.75 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           35 |      638 | 2024-07-18 | Spirit            | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.441 (0.441)    | 1 (1.000) |    14.57 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           34 |      738 | 2024-07-17 | The MongolZ       | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.694 (0.694)    | 1 (1.000) |     9.14 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           33 |     1150 | 2024-06-13 | Vitality          | L   | 0.840      | -            | -                | -                | -         |   -16.88 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           32 |     1606 | 2024-06-02 | Vitality          | W   | 0.767      | 0.624        | 0.647 (0.310)    | -                | 1 (0.767) |     9.31 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           31 |     1628 | 2024-06-01 | 9z                | W   | 0.762      | 0.624        | 0.404 (0.192)    | 0.591 (0.281)    | 1 (0.762) |     1.63 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           30 |     1665 | 2024-05-31 | FaZe              | W   | 0.755      | 0.624        | 0.625 (0.294)    | -                | 1 (0.755) |     5.59 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           29 |     1715 | 2024-05-29 | Liquid            | W   | 0.742      | 0.624        | -                | 0.437 (0.203)    | 1 (0.742) |     3.12 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           28 |     1738 | 2024-05-28 | MOUZ              | W   | 0.736      | 0.624        | 1.000 (0.459)    | -                | -         |    10.03 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           27 |     1762 | 2024-05-27 | Vitality          | L   | 0.729      | -            | -                | -                | -         |   -13.71 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           26 |     1773 | 2024-05-27 | Falcons           | W   | 0.727      | -            | -                | -                | -         |     1.20 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           25 |     2312 | 2024-05-09 | MOUZ              | L   | 0.607      | -            | -                | -                | -         |   -11.88 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           24 |     2338 | 2024-05-08 | 3DMAX             | W   | 0.600      | 0.889        | 0.510 (0.272)    | 1.000 (0.533)    | -         |     2.56 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           23 |     2356 | 2024-05-07 | BIG               | W   | 0.593      | -            | -                | -                | -         |     0.49 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           22 |     2533 | 2024-04-28 | M80               | W   | 0.534      | 0.889        | -                | 0.563 (0.267)    | -         |     0.32 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           21 |     2568 | 2024-04-27 | Falcons           | W   | 0.526      | -            | -                | -                | -         |     0.75 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           20 |     2591 | 2024-04-26 | M80               | L   | 0.519      | -            | -                | -                | -         |   -16.07 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           19 |     2620 | 2024-04-25 | The MongolZ       | L   | 0.512      | -            | -                | -                | -         |    -9.37 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           18 |     2640 | 2024-04-24 | TYLOO             | W   | 0.506      | -            | -                | -                | -         |     0.02 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           17 |     2941 | 2024-04-13 | MOUZ              | L   | 0.431      | -            | -                | -                | -         |    -9.07 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           16 |     2954 | 2024-04-12 | Virtus.pro        | W   | 0.424      | -            | -                | -                | -         |     2.20 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           15 |     3024 | 2024-04-10 | HEROIC            | W   | 0.412      | -            | -                | -                | -         |     1.17 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           14 |     3084 | 2024-04-09 | Lynn Vision       | W   | 0.406      | -            | -                | -                | -         |     0.08 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           13 |     3115 | 2024-04-08 | Liquid            | L   | 0.398      | -            | -                | -                | -         |   -11.31 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           12 |     3124 | 2024-04-07 | 9z                | W   | 0.397      | -            | -                | -                | -         |     0.97 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           11 |     3316 | 2024-03-30 | Natus Vincere     | L   | 0.341      | -            | -                | -                | -         |    -5.72 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           10 |     3323 | 2024-03-29 | MOUZ              | W   | 0.335      | 1.000        | 1.000 (0.335)    | -                | -         |     3.27 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            9 |     3420 | 2024-03-24 | Virtus.pro        | W   | 0.300      | -            | -                | -                | -         |     1.53 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            8 |     3432 | 2024-03-23 | Gaimin Gladiators | W   | 0.293      | -            | -                | -                | -         |     0.04 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            7 |     3450 | 2024-03-22 | Cloud9            | L   | 0.286      | -            | -                | -                | -         |    -8.96 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            6 |     3460 | 2024-03-21 | Natus Vincere     | L   | 0.281      | -            | -                | -                | -         |    -4.74 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            5 |     3469 | 2024-03-21 | FURIA             | W   | 0.280      | -            | -                | -                | -         |     1.44 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            4 |     4289 | 2024-02-15 | FaZe              | W   | 0.046      | -            | -                | -                | -         |     0.20 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            3 |     4319 | 2024-02-14 | Eternal Fire      | W   | 0.041      | -            | -                | -                | -         |     0.20 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            2 |     4336 | 2024-02-14 | Into the Breach   | W   | 0.039      | -            | -                | -                | -         |     0.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            1 |     4401 | 2024-02-09 | FaZe              | L   | 0.007      | -            | -                | -                | -         |    -0.18 | HooXi, huNter-, m0NESY, nexa, NiKo    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($340,287.13)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $175,000.00    | $175,000.00     |
| 2024-06-16 |      0.860 | $10,000.00     | $8,597.22       |
| 2024-06-02 |      0.767 | $100,000.00    | $76,750.00      |
| 2024-05-12 |      0.627 | $32,000.00     | $20,053.33      |
| 2024-04-14 |      0.439 | $20,000.00     | $8,775.46       |
| 2024-03-31 |      0.347 | $80,000.00     | $27,800.00      |
| 2024-02-11 |      0.020 | $40,000.00     | $811.11         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
