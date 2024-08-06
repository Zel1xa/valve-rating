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
- Bounty Collected: 0.755[<sup>2</sup>](#table1)
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
|           40 |       71 | 2024-08-03 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.531 (0.309)    | 1 (1.000) |     3.41 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           39 |      162 | 2024-08-01 | FaZe              | W   | 1.000      | 0.581        | 0.626 (0.364)    | 0.383 (0.222)    | 1 (1.000) |     6.15 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           38 |      206 | 2024-07-31 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.531 (0.309)    | 1 (1.000) |     3.27 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           37 |      516 | 2024-07-21 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |   -16.18 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           36 |      561 | 2024-07-20 | Virtus.pro        | W   | 1.000      | 1.000        | 0.498 (0.498)    | 0.309 (0.309)    | 1 (1.000) |     5.76 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           35 |      628 | 2024-07-18 | Spirit            | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.441 (0.441)    | 1 (1.000) |    14.59 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           34 |      728 | 2024-07-17 | The MongolZ       | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.694 (0.694)    | 1 (1.000) |     9.13 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           33 |     1140 | 2024-06-13 | Vitality          | L   | 0.841      | -            | -                | -                | -         |   -16.89 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           32 |     1596 | 2024-06-02 | Vitality          | W   | 0.769      | 0.624        | 0.647 (0.310)    | -                | 1 (0.769) |     9.33 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           31 |     1618 | 2024-06-01 | 9z                | W   | 0.763      | 0.624        | 0.404 (0.192)    | 0.591 (0.281)    | 1 (0.763) |     1.64 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           30 |     1655 | 2024-05-31 | FaZe              | W   | 0.756      | 0.624        | 0.626 (0.295)    | -                | 1 (0.756) |     5.62 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           29 |     1705 | 2024-05-29 | Liquid            | W   | 0.743      | 0.624        | -                | 0.438 (0.203)    | 1 (0.743) |     3.13 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           28 |     1728 | 2024-05-28 | MOUZ              | W   | 0.737      | 0.624        | 1.000 (0.460)    | -                | -         |    10.06 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           27 |     1752 | 2024-05-27 | Vitality          | L   | 0.730      | -            | -                | -                | -         |   -13.72 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           26 |     1763 | 2024-05-27 | Falcons           | W   | 0.728      | -            | -                | -                | -         |     1.21 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           25 |     2302 | 2024-05-09 | MOUZ              | L   | 0.608      | -            | -                | -                | -         |   -11.89 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           24 |     2328 | 2024-05-08 | 3DMAX             | W   | 0.601      | 0.889        | 0.510 (0.272)    | 1.000 (0.534)    | -         |     2.56 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           23 |     2346 | 2024-05-07 | BIG               | W   | 0.594      | -            | -                | -                | -         |     0.49 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           22 |     2523 | 2024-04-28 | M80               | W   | 0.535      | 0.889        | -                | 0.563 (0.268)    | -         |     0.32 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           21 |     2558 | 2024-04-27 | Falcons           | W   | 0.527      | -            | -                | -                | -         |     0.75 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           20 |     2581 | 2024-04-26 | M80               | L   | 0.520      | -            | -                | -                | -         |   -16.10 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           19 |     2610 | 2024-04-25 | The MongolZ       | L   | 0.513      | -            | -                | -                | -         |    -9.39 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           18 |     2630 | 2024-04-24 | TYLOO             | W   | 0.507      | -            | -                | -                | -         |     0.02 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           17 |     2931 | 2024-04-13 | MOUZ              | L   | 0.432      | -            | -                | -                | -         |    -9.09 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           16 |     2944 | 2024-04-12 | Virtus.pro        | W   | 0.426      | -            | -                | -                | -         |     2.21 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           15 |     3014 | 2024-04-10 | HEROIC            | W   | 0.413      | -            | -                | -                | -         |     1.18 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           14 |     3074 | 2024-04-09 | Lynn Vision       | W   | 0.407      | -            | -                | -                | -         |     0.07 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           13 |     3105 | 2024-04-08 | Liquid            | L   | 0.399      | -            | -                | -                | -         |   -11.34 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           12 |     3114 | 2024-04-07 | 9z                | W   | 0.398      | -            | -                | -                | -         |     0.98 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           11 |     3306 | 2024-03-30 | Natus Vincere     | L   | 0.342      | -            | -                | -                | -         |    -5.74 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           10 |     3313 | 2024-03-29 | MOUZ              | W   | 0.336      | 1.000        | 1.000 (0.336)    | -                | -         |     3.29 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            9 |     3410 | 2024-03-24 | Virtus.pro        | W   | 0.301      | -            | -                | -                | -         |     1.54 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            8 |     3422 | 2024-03-23 | Gaimin Gladiators | W   | 0.295      | -            | -                | -                | -         |     0.04 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            7 |     3440 | 2024-03-22 | Cloud9            | L   | 0.287      | -            | -                | -                | -         |    -8.99 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            6 |     3450 | 2024-03-21 | Natus Vincere     | L   | 0.283      | -            | -                | -                | -         |    -4.76 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            5 |     3459 | 2024-03-21 | FURIA             | W   | 0.281      | -            | -                | -                | -         |     1.44 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            4 |     4279 | 2024-02-15 | FaZe              | W   | 0.047      | -            | -                | -                | -         |     0.21 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            3 |     4309 | 2024-02-14 | Eternal Fire      | W   | 0.042      | -            | -                | -                | -         |     0.20 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            2 |     4326 | 2024-02-14 | Into the Breach   | W   | 0.040      | -            | -                | -                | -         |     0.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            1 |     4391 | 2024-02-09 | FaZe              | L   | 0.008      | -            | -                | -                | -         |    -0.21 | HooXi, huNter-, m0NESY, nexa, NiKo    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($340,600.46)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $175,000.00    | $175,000.00     |
| 2024-06-16 |      0.861 | $10,000.00     | $8,608.33       |
| 2024-06-02 |      0.769 | $100,000.00    | $76,861.11      |
| 2024-05-12 |      0.628 | $32,000.00     | $20,088.89      |
| 2024-04-14 |      0.440 | $20,000.00     | $8,797.69       |
| 2024-03-31 |      0.349 | $80,000.00     | $27,888.89      |
| 2024-02-11 |      0.021 | $40,000.00     | $855.56         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
