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
- Opponent Network: 0.364[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.780<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 2000.0
- 400 + ( ( 0.780 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 2000.0


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
|           40 |       67 | 2024-08-03 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.543 (0.316)    | 1 (1.000) |     3.41 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           39 |      158 | 2024-08-01 | FaZe              | W   | 1.000      | 0.581        | 0.626 (0.364)    | 0.391 (0.227)    | 1 (1.000) |     6.14 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           38 |      202 | 2024-07-31 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.543 (0.316)    | 1 (1.000) |     3.27 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           37 |      512 | 2024-07-21 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |   -16.18 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           36 |      557 | 2024-07-20 | Virtus.pro        | W   | 1.000      | 1.000        | 0.498 (0.498)    | 0.316 (0.316)    | 1 (1.000) |     5.76 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           35 |      624 | 2024-07-18 | Spirit            | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.451 (0.451)    | 1 (1.000) |    14.57 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           34 |      724 | 2024-07-17 | The MongolZ       | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.709 (0.709)    | 1 (1.000) |     9.16 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           33 |     1136 | 2024-06-13 | Vitality          | L   | 0.842      | -            | -                | -                | -         |   -16.90 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           32 |     1592 | 2024-06-02 | Vitality          | W   | 0.769      | 0.624        | 0.647 (0.310)    | -                | 1 (0.769) |     9.34 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           31 |     1614 | 2024-06-01 | 9z                | W   | 0.763      | 0.624        | 0.404 (0.192)    | 0.604 (0.288)    | 1 (0.763) |     1.64 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           30 |     1651 | 2024-05-31 | FaZe              | W   | 0.756      | 0.624        | 0.626 (0.296)    | -                | 1 (0.756) |     5.62 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           29 |     1701 | 2024-05-29 | Liquid            | W   | 0.744      | 0.624        | -                | 0.448 (0.208)    | 1 (0.744) |     3.12 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           28 |     1724 | 2024-05-28 | MOUZ              | W   | 0.737      | 0.624        | 1.000 (0.460)    | -                | -         |    10.08 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           27 |     1748 | 2024-05-27 | Vitality          | L   | 0.730      | -            | -                | -                | -         |   -13.72 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           26 |     1759 | 2024-05-27 | Falcons           | W   | 0.729      | -            | -                | -                | -         |     1.21 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           25 |     2298 | 2024-05-09 | MOUZ              | L   | 0.609      | -            | -                | -                | -         |   -11.88 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           24 |     2324 | 2024-05-08 | 3DMAX             | W   | 0.601      | 0.889        | 0.509 (0.272)    | 1.000 (0.534)    | -         |     2.56 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           23 |     2342 | 2024-05-07 | BIG               | W   | 0.595      | -            | -                | -                | -         |     0.49 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           22 |     2519 | 2024-04-28 | M80               | W   | 0.535      | 0.889        | -                | 0.576 (0.274)    | -         |     0.32 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           21 |     2554 | 2024-04-27 | Falcons           | W   | 0.527      | -            | -                | -                | -         |     0.75 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           20 |     2577 | 2024-04-26 | M80               | L   | 0.520      | -            | -                | -                | -         |   -16.11 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           19 |     2606 | 2024-04-25 | The MongolZ       | L   | 0.514      | -            | -                | -                | -         |    -9.37 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           18 |     2626 | 2024-04-24 | TYLOO             | W   | 0.507      | -            | -                | -                | -         |     0.02 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           17 |     2927 | 2024-04-13 | MOUZ              | L   | 0.432      | -            | -                | -                | -         |    -9.09 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           16 |     2940 | 2024-04-12 | Virtus.pro        | W   | 0.426      | -            | -                | -                | -         |     2.21 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           15 |     3010 | 2024-04-10 | HEROIC            | W   | 0.414      | -            | -                | -                | -         |     1.18 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           14 |     3070 | 2024-04-09 | Lynn Vision       | W   | 0.407      | -            | -                | -                | -         |     0.07 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           13 |     3101 | 2024-04-08 | Liquid            | L   | 0.400      | -            | -                | -                | -         |   -11.35 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           12 |     3110 | 2024-04-07 | 9z                | W   | 0.398      | -            | -                | -                | -         |     0.98 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           11 |     3302 | 2024-03-30 | Natus Vincere     | L   | 0.343      | -            | -                | -                | -         |    -5.75 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           10 |     3309 | 2024-03-29 | MOUZ              | W   | 0.336      | 1.000        | 1.000 (0.336)    | -                | -         |     3.30 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            9 |     3406 | 2024-03-24 | Virtus.pro        | W   | 0.301      | -            | -                | -                | -         |     1.54 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            8 |     3418 | 2024-03-23 | Gaimin Gladiators | W   | 0.295      | -            | -                | -                | -         |     0.04 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            7 |     3436 | 2024-03-22 | Cloud9            | L   | 0.287      | -            | -                | -                | -         |    -9.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            6 |     3446 | 2024-03-21 | Natus Vincere     | L   | 0.283      | -            | -                | -                | -         |    -4.76 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            5 |     3455 | 2024-03-21 | FURIA             | W   | 0.281      | -            | -                | -                | -         |     1.45 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            4 |     4275 | 2024-02-15 | FaZe              | W   | 0.048      | -            | -                | -                | -         |     0.21 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            3 |     4305 | 2024-02-14 | Eternal Fire      | W   | 0.042      | -            | -                | -                | -         |     0.20 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            2 |     4322 | 2024-02-14 | Into the Breach   | W   | 0.041      | -            | -                | -                | -         |     0.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            1 |     4387 | 2024-02-09 | FaZe              | L   | 0.008      | -            | -                | -                | -         |    -0.22 | HooXi, huNter-, m0NESY, nexa, NiKo    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($340,678.80)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $175,000.00    | $175,000.00     |
| 2024-06-16 |      0.861 | $10,000.00     | $8,611.11       |
| 2024-06-02 |      0.769 | $100,000.00    | $76,888.89      |
| 2024-05-12 |      0.628 | $32,000.00     | $20,097.78      |
| 2024-04-14 |      0.440 | $20,000.00     | $8,803.24       |
| 2024-03-31 |      0.349 | $80,000.00     | $27,911.11      |
| 2024-02-11 |      0.022 | $40,000.00     | $866.67         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
