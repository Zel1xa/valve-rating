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
- Bounty Collected: 0.758[<sup>2</sup>](#table1)
- Opponent Network: 0.374[<sup>2</sup>](#table1)
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
|           42 |        2 | 2024-08-03 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.553 (0.321)    | 1 (1.000) |     3.30 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           41 |       91 | 2024-08-01 | FaZe              | W   | 1.000      | 0.581        | 0.643 (0.373)    | 0.403 (0.234)    | 1 (1.000) |     6.34 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           40 |      135 | 2024-07-31 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.553 (0.321)    | 1 (1.000) |     3.16 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           39 |      445 | 2024-07-21 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |   -16.17 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           38 |      490 | 2024-07-20 | Virtus.pro        | W   | 1.000      | 1.000        | 0.496 (0.496)    | 0.324 (0.324)    | 1 (1.000) |     5.82 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           37 |      557 | 2024-07-18 | Spirit            | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.461 (0.461)    | 1 (1.000) |    14.72 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           36 |      657 | 2024-07-17 | The MongolZ       | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.720 (0.720)    | 1 (1.000) |     8.98 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           35 |     1068 | 2024-06-13 | Vitality          | L   | 0.858      | -            | -                | -                | -         |   -17.19 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           34 |     1524 | 2024-06-02 | Vitality          | W   | 0.785      | 0.624        | 0.649 (0.318)    | -                | 1 (0.785) |     9.56 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           33 |     1546 | 2024-06-01 | 9z                | W   | 0.780      | 0.624        | 0.406 (0.198)    | 0.619 (0.301)    | 1 (0.780) |     1.70 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           32 |     1583 | 2024-05-31 | FaZe              | W   | 0.773      | 0.624        | 0.643 (0.310)    | -                | 1 (0.773) |     5.95 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           31 |     1633 | 2024-05-29 | Liquid            | W   | 0.760      | 0.624        | -                | 0.461 (0.219)    | 1 (0.760) |     2.32 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           30 |     1656 | 2024-05-28 | MOUZ              | W   | 0.754      | 0.624        | 1.000 (0.470)    | -                | -         |    10.40 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           29 |     1680 | 2024-05-27 | Vitality          | L   | 0.746      | -            | -                | -                | -         |   -13.99 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           28 |     1691 | 2024-05-27 | Falcons           | W   | 0.745      | -            | -                | -                | -         |     1.29 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           27 |     2230 | 2024-05-09 | MOUZ              | L   | 0.625      | -            | -                | -                | -         |   -12.12 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           26 |     2256 | 2024-05-08 | 3DMAX             | W   | 0.618      | 0.889        | 0.505 (0.277)    | 1.000 (0.549)    | -         |     2.53 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           25 |     2274 | 2024-05-07 | BIG               | W   | 0.611      | -            | -                | -                | -         |     0.52 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           24 |     2451 | 2024-04-28 | M80               | W   | 0.552      | 0.889        | -                | 0.587 (0.288)    | -         |     0.34 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           23 |     2486 | 2024-04-27 | Falcons           | W   | 0.543      | -            | -                | -                | -         |     0.81 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           22 |     2508 | 2024-04-26 | M80               | L   | 0.537      | -            | -                | -                | -         |   -16.61 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           21 |     2537 | 2024-04-25 | The MongolZ       | L   | 0.530      | -            | -                | -                | -         |    -9.75 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           20 |     2557 | 2024-04-24 | TYLOO             | W   | 0.523      | -            | -                | -                | -         |     0.02 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           19 |     2858 | 2024-04-13 | MOUZ              | L   | 0.449      | -            | -                | -                | -         |    -9.38 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           18 |     2871 | 2024-04-12 | Virtus.pro        | W   | 0.442      | -            | -                | -                | -         |     2.33 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           17 |     2941 | 2024-04-10 | HEROIC            | W   | 0.430      | -            | -                | -                | -         |     1.25 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           16 |     3001 | 2024-04-09 | Lynn Vision       | W   | 0.423      | -            | -                | -                | -         |     0.06 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           15 |     3032 | 2024-04-08 | Liquid            | L   | 0.416      | -            | -                | -                | -         |   -12.30 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           14 |     3041 | 2024-04-07 | 9z                | W   | 0.415      | -            | -                | -                | -         |     1.04 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           13 |     3233 | 2024-03-30 | Natus Vincere     | L   | 0.359      | -            | -                | -                | -         |    -6.04 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           12 |     3240 | 2024-03-29 | MOUZ              | W   | 0.352      | 1.000        | 1.000 (0.352)    | -                | -         |     3.50 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           11 |     3337 | 2024-03-24 | Virtus.pro        | W   | 0.317      | -            | -                | -                | -         |     1.65 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           10 |     3349 | 2024-03-23 | Gaimin Gladiators | W   | 0.311      | -            | -                | -                | -         |     0.04 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            9 |     3367 | 2024-03-22 | Cloud9            | L   | 0.304      | -            | -                | -                | -         |    -9.51 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            8 |     3377 | 2024-03-21 | Natus Vincere     | L   | 0.299      | -            | -                | -                | -         |    -5.07 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            7 |     3386 | 2024-03-21 | FURIA             | W   | 0.298      | -            | -                | -                | -         |     1.52 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            6 |     4204 | 2024-02-15 | FaZe              | W   | 0.064      | -            | -                | -                | -         |     0.30 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            5 |     4234 | 2024-02-14 | Eternal Fire      | W   | 0.059      | -            | -                | -                | -         |     0.29 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            4 |     4251 | 2024-02-14 | Into the Breach   | W   | 0.057      | -            | -                | -                | -         |     0.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            3 |     4316 | 2024-02-09 | FaZe              | L   | 0.025      | -            | -                | -                | -         |    -0.66 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            2 |     4344 | 2024-02-06 | HEROIC            | W   | 0.005      | -            | -                | -                | -         |     0.01 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            1 |     4350 | 2024-02-06 | Monte             | W   | 0.004      | -            | -                | -                | -         |     0.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($345,300.46)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $175,000.00    | $175,000.00     |
| 2024-06-16 |      0.877 | $10,000.00     | $8,775.00       |
| 2024-06-02 |      0.785 | $100,000.00    | $78,527.78      |
| 2024-05-12 |      0.644 | $32,000.00     | $20,622.22      |
| 2024-04-14 |      0.457 | $20,000.00     | $9,131.02       |
| 2024-03-31 |      0.365 | $80,000.00     | $29,222.22      |
| 2024-02-11 |      0.038 | $40,000.00     | $1,522.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
