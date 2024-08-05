### Roster Details<br />
Team Name: G2<br />
Roster: huNter-, m0NESY, malbsMd, NiKo, Snax<br />
Global Rank: [1](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [1]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1964.0<br />
<br />
Final Rank Value (1964.0) = Starting Rank Value (2000.0) + Head To Head Adjustments (-36.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.757[<sup>2</sup>](#table1)
- Opponent Network: 0.372[<sup>2</sup>](#table1)
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
|           40 |       39 | 2024-08-03 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.553 (0.321)    | 1 (1.000) |     3.41 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           39 |      130 | 2024-08-01 | FaZe              | W   | 1.000      | 0.581        | 0.635 (0.369)    | 0.401 (0.233)    | 1 (1.000) |     6.30 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           38 |      174 | 2024-07-31 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.553 (0.321)    | 1 (1.000) |     3.28 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           37 |      484 | 2024-07-21 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |   -16.13 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           36 |      529 | 2024-07-20 | Virtus.pro        | W   | 1.000      | 1.000        | 0.497 (0.497)    | 0.323 (0.323)    | 1 (1.000) |     5.84 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           35 |      596 | 2024-07-18 | Spirit            | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.460 (0.460)    | 1 (1.000) |    14.66 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           34 |      696 | 2024-07-17 | The MongolZ       | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.721 (0.721)    | 1 (1.000) |     9.12 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           33 |     1108 | 2024-06-13 | Vitality          | L   | 0.851      | -            | -                | -                | -         |   -17.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           32 |     1564 | 2024-06-02 | Vitality          | W   | 0.778      | 0.624        | 0.648 (0.315)    | -                | 1 (0.778) |     9.52 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           31 |     1586 | 2024-06-01 | 9z                | W   | 0.772      | 0.624        | 0.405 (0.195)    | 0.617 (0.298)    | 1 (0.772) |     1.68 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           30 |     1623 | 2024-05-31 | FaZe              | W   | 0.766      | 0.624        | 0.635 (0.304)    | -                | 1 (0.766) |     5.86 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           29 |     1673 | 2024-05-29 | Liquid            | W   | 0.753      | 0.624        | -                | 0.459 (0.216)    | 1 (0.753) |     3.20 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           28 |     1696 | 2024-05-28 | MOUZ              | W   | 0.746      | 0.624        | 1.000 (0.466)    | -                | -         |    10.30 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           27 |     1720 | 2024-05-27 | Vitality          | L   | 0.739      | -            | -                | -                | -         |   -13.79 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           26 |     1731 | 2024-05-27 | Falcons           | W   | 0.738      | -            | -                | -                | -         |     1.25 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           25 |     2270 | 2024-05-09 | MOUZ              | L   | 0.618      | -            | -                | -                | -         |   -11.99 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           24 |     2296 | 2024-05-08 | 3DMAX             | W   | 0.610      | 0.889        | 0.507 (0.275)    | 1.000 (0.543)    | -         |     2.53 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           23 |     2314 | 2024-05-07 | BIG               | W   | 0.604      | -            | -                | -                | -         |     0.50 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           22 |     2491 | 2024-04-28 | M80               | W   | 0.545      | 0.889        | -                | 0.587 (0.284)    | -         |     0.33 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           21 |     2526 | 2024-04-27 | Falcons           | W   | 0.536      | -            | -                | -                | -         |     0.78 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           20 |     2549 | 2024-04-26 | M80               | L   | 0.530      | -            | -                | -                | -         |   -16.39 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           19 |     2578 | 2024-04-25 | The MongolZ       | L   | 0.523      | -            | -                | -                | -         |    -9.55 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           18 |     2598 | 2024-04-24 | TYLOO             | W   | 0.516      | -            | -                | -                | -         |     0.02 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           17 |     2899 | 2024-04-13 | MOUZ              | L   | 0.442      | -            | -                | -                | -         |    -9.24 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           16 |     2912 | 2024-04-12 | Virtus.pro        | W   | 0.435      | -            | -                | -                | -         |     2.30 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           15 |     2982 | 2024-04-10 | HEROIC            | W   | 0.423      | -            | -                | -                | -         |     1.23 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           14 |     3042 | 2024-04-09 | Lynn Vision       | W   | 0.416      | -            | -                | -                | -         |     0.07 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           13 |     3073 | 2024-04-08 | Liquid            | L   | 0.409      | -            | -                | -                | -         |   -11.60 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           12 |     3082 | 2024-04-07 | 9z                | W   | 0.408      | -            | -                | -                | -         |     1.02 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           11 |     3274 | 2024-03-30 | Natus Vincere     | L   | 0.352      | -            | -                | -                | -         |    -5.88 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           10 |     3281 | 2024-03-29 | MOUZ              | W   | 0.345      | 1.000        | 1.000 (0.345)    | -                | -         |     3.41 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            9 |     3378 | 2024-03-24 | Virtus.pro        | W   | 0.310      | -            | -                | -                | -         |     1.62 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            8 |     3390 | 2024-03-23 | Gaimin Gladiators | W   | 0.304      | -            | -                | -                | -         |     0.04 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            7 |     3408 | 2024-03-22 | Cloud9            | L   | 0.296      | -            | -                | -                | -         |    -9.29 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            6 |     3418 | 2024-03-21 | Natus Vincere     | L   | 0.292      | -            | -                | -                | -         |    -4.91 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            5 |     3427 | 2024-03-21 | FURIA             | W   | 0.291      | -            | -                | -                | -         |     1.50 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            4 |     4247 | 2024-02-15 | FaZe              | W   | 0.057      | -            | -                | -                | -         |     0.26 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            3 |     4277 | 2024-02-14 | Eternal Fire      | W   | 0.052      | -            | -                | -                | -         |     0.25 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            2 |     4294 | 2024-02-14 | Into the Breach   | W   | 0.050      | -            | -                | -                | -         |     0.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            1 |     4359 | 2024-02-09 | FaZe              | L   | 0.017      | -            | -                | -                | -         |    -0.47 | HooXi, huNter-, m0NESY, nexa, NiKo    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($343,263.80)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $175,000.00    | $175,000.00     |
| 2024-06-16 |      0.870 | $10,000.00     | $8,702.78       |
| 2024-06-02 |      0.778 | $100,000.00    | $77,805.56      |
| 2024-05-12 |      0.637 | $32,000.00     | $20,391.11      |
| 2024-04-14 |      0.449 | $20,000.00     | $8,986.57       |
| 2024-03-31 |      0.358 | $80,000.00     | $28,644.44      |
| 2024-02-11 |      0.031 | $40,000.00     | $1,233.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
