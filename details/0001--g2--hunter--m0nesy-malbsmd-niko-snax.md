### Roster Details<br />
Team Name: G2<br />
Roster: huNter-, m0NESY, malbsMd, NiKo, Snax<br />
Global Rank: [1](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [1]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1963.9<br />
<br />
Final Rank Value (1963.9) = Starting Rank Value (2000.0) + Head To Head Adjustments (-36.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.757[<sup>2</sup>](#table1)
- Opponent Network: 0.373[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.782<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 2000.0
- 400 + ( ( 0.782 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 2000.0


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
|           41 |       34 | 2024-08-03 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.553 (0.321)    | 1 (1.000) |     3.41 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           40 |      125 | 2024-08-01 | FaZe              | W   | 1.000      | 0.581        | 0.638 (0.371)    | 0.402 (0.234)    | 1 (1.000) |     6.34 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           39 |      169 | 2024-07-31 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.553 (0.321)    | 1 (1.000) |     3.27 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           38 |      479 | 2024-07-21 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |   -16.12 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           37 |      524 | 2024-07-20 | Virtus.pro        | W   | 1.000      | 1.000        | 0.497 (0.497)    | 0.323 (0.323)    | 1 (1.000) |     5.86 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           36 |      591 | 2024-07-18 | Spirit            | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.460 (0.460)    | 1 (1.000) |    14.68 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           35 |      691 | 2024-07-17 | The MongolZ       | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.721 (0.721)    | 1 (1.000) |     9.07 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           34 |     1103 | 2024-06-13 | Vitality          | L   | 0.854      | -            | -                | -                | -         |   -17.04 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           33 |     1559 | 2024-06-02 | Vitality          | W   | 0.781      | 0.624        | 0.649 (0.316)    | -                | 1 (0.781) |     9.57 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           32 |     1581 | 2024-06-01 | 9z                | W   | 0.775      | 0.624        | 0.405 (0.196)    | 0.618 (0.299)    | 1 (0.775) |     1.69 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           31 |     1618 | 2024-05-31 | FaZe              | W   | 0.768      | 0.624        | 0.638 (0.306)    | -                | 1 (0.768) |     5.93 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           30 |     1668 | 2024-05-29 | Liquid            | W   | 0.755      | 0.624        | -                | 0.460 (0.217)    | 1 (0.755) |     3.21 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           29 |     1691 | 2024-05-28 | MOUZ              | W   | 0.749      | 0.624        | 1.000 (0.468)    | -                | -         |    10.37 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           28 |     1715 | 2024-05-27 | Vitality          | L   | 0.742      | -            | -                | -                | -         |   -13.81 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           27 |     1726 | 2024-05-27 | Falcons           | W   | 0.741      | -            | -                | -                | -         |     1.26 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           26 |     2265 | 2024-05-09 | MOUZ              | L   | 0.621      | -            | -                | -                | -         |   -12.01 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           25 |     2291 | 2024-05-08 | 3DMAX             | W   | 0.613      | 0.889        | 0.506 (0.276)    | 1.000 (0.545)    | -         |     2.54 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           24 |     2309 | 2024-05-07 | BIG               | W   | 0.606      | -            | -                | -                | -         |     0.51 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           23 |     2486 | 2024-04-28 | M80               | W   | 0.547      | 0.889        | -                | 0.587 (0.285)    | -         |     0.34 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           22 |     2521 | 2024-04-27 | Falcons           | W   | 0.539      | -            | -                | -                | -         |     0.79 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           21 |     2544 | 2024-04-26 | M80               | L   | 0.532      | -            | -                | -                | -         |   -16.47 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           20 |     2573 | 2024-04-25 | The MongolZ       | L   | 0.526      | -            | -                | -                | -         |    -9.63 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           19 |     2593 | 2024-04-24 | TYLOO             | W   | 0.519      | -            | -                | -                | -         |     0.02 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           18 |     2894 | 2024-04-13 | MOUZ              | L   | 0.444      | -            | -                | -                | -         |    -9.28 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           17 |     2907 | 2024-04-12 | Virtus.pro        | W   | 0.438      | -            | -                | -                | -         |     2.32 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           16 |     2977 | 2024-04-10 | HEROIC            | W   | 0.426      | -            | -                | -                | -         |     1.25 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           15 |     3037 | 2024-04-09 | Lynn Vision       | W   | 0.419      | -            | -                | -                | -         |     0.08 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           14 |     3068 | 2024-04-08 | Liquid            | L   | 0.412      | -            | -                | -                | -         |   -11.68 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           13 |     3077 | 2024-04-07 | 9z                | W   | 0.410      | -            | -                | -                | -         |     1.03 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           12 |     3269 | 2024-03-30 | Natus Vincere     | L   | 0.355      | -            | -                | -                | -         |    -5.92 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           11 |     3276 | 2024-03-29 | MOUZ              | W   | 0.348      | 1.000        | 1.000 (0.348)    | -                | -         |     3.45 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           10 |     3373 | 2024-03-24 | Virtus.pro        | W   | 0.313      | -            | -                | -                | -         |     1.64 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            9 |     3385 | 2024-03-23 | Gaimin Gladiators | W   | 0.307      | -            | -                | -                | -         |     0.04 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            8 |     3403 | 2024-03-22 | Cloud9            | L   | 0.299      | -            | -                | -                | -         |    -9.37 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            7 |     3413 | 2024-03-21 | Natus Vincere     | L   | 0.295      | -            | -                | -                | -         |    -4.95 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            6 |     3422 | 2024-03-21 | FURIA             | W   | 0.293      | -            | -                | -                | -         |     1.51 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            5 |     4242 | 2024-02-15 | FaZe              | W   | 0.059      | -            | -                | -                | -         |     0.28 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            4 |     4272 | 2024-02-14 | Eternal Fire      | W   | 0.054      | -            | -                | -                | -         |     0.27 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            3 |     4289 | 2024-02-14 | Into the Breach   | W   | 0.052      | -            | -                | -                | -         |     0.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            2 |     4354 | 2024-02-09 | FaZe              | L   | 0.020      | -            | -                | -                | -         |    -0.54 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            1 |     4382 | 2024-02-06 | HEROIC            | W   | 0.001      | -            | -                | -                | -         |     0.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($344,021.02)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $175,000.00    | $175,000.00     |
| 2024-06-16 |      0.873 | $10,000.00     | $8,729.63       |
| 2024-06-02 |      0.781 | $100,000.00    | $78,074.07      |
| 2024-05-12 |      0.640 | $32,000.00     | $20,477.04      |
| 2024-04-14 |      0.452 | $20,000.00     | $9,040.28       |
| 2024-03-31 |      0.361 | $80,000.00     | $28,859.26      |
| 2024-02-11 |      0.034 | $40,000.00     | $1,340.74       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
