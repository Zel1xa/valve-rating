### Roster Details<br />
Team Name: G2<br />
Roster: huNter-, m0NESY, malbsMd, NiKo, Snax<br />
Global Rank: [1](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [1]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1956.7<br />
<br />
Final Rank Value (1956.7) = Starting Rank Value (2000.0) + Head To Head Adjustments (-43.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.756[<sup>2</sup>](#table1)
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
|           42 |        0 | 2024-08-03 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.502 (0.292)    | 1 (1.000) |     2.98 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           41 |       69 | 2024-08-01 | FaZe              | W   | 1.000      | 0.581        | 0.644 (0.374)    | 0.418 (0.243)    | 1 (1.000) |     6.58 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           40 |      113 | 2024-07-31 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.502 (0.292)    | 1 (1.000) |     2.82 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           39 |      422 | 2024-07-21 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |   -15.89 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           38 |      467 | 2024-07-20 | Virtus.pro        | W   | 1.000      | 1.000        | 0.496 (0.496)    | 0.335 (0.335)    | 1 (1.000) |     5.87 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           37 |      534 | 2024-07-18 | Spirit            | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.477 (0.477)    | 1 (1.000) |    15.11 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           36 |      632 | 2024-07-17 | The MongolZ       | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.745 (0.745)    | 1 (1.000) |     9.22 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           35 |     1018 | 2024-06-13 | Vitality          | L   | 0.860      | -            | -                | -                | -         |   -16.94 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           34 |     1463 | 2024-06-02 | Vitality          | W   | 0.787      | 0.624        | 0.650 (0.319)    | -                | 1 (0.787) |     9.88 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           33 |     1484 | 2024-06-01 | 9z                | W   | 0.781      | 0.624        | -                | 0.528 (0.257)    | 1 (0.781) |     0.52 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           32 |     1520 | 2024-05-31 | FaZe              | W   | 0.775      | 0.624        | 0.644 (0.311)    | -                | 1 (0.775) |     6.20 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           31 |     1570 | 2024-05-29 | Liquid            | W   | 0.762      | 0.624        | -                | 0.478 (0.227)    | 1 (0.762) |     2.36 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           30 |     1593 | 2024-05-28 | MOUZ              | W   | 0.755      | 0.624        | 1.000 (0.471)    | -                | -         |     9.15 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           29 |     1617 | 2024-05-27 | Vitality          | L   | 0.748      | -            | -                | -                | -         |   -13.74 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           28 |     1628 | 2024-05-27 | Falcons           | W   | 0.747      | -            | -                | -                | -         |     1.35 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           27 |     2165 | 2024-05-09 | MOUZ              | L   | 0.627      | -            | -                | -                | -         |   -13.38 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           26 |     2190 | 2024-05-08 | 3DMAX             | W   | 0.619      | 0.889        | 0.504 (0.278)    | 1.000 (0.551)    | -         |     2.50 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           25 |     2208 | 2024-05-07 | BIG               | W   | 0.613      | -            | -                | -                | -         |     0.54 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           24 |     2385 | 2024-04-28 | M80               | W   | 0.554      | 0.889        | -                | 0.608 (0.299)    | -         |     0.35 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           23 |     2420 | 2024-04-27 | Falcons           | W   | 0.545      | -            | -                | -                | -         |     0.85 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           22 |     2443 | 2024-04-26 | M80               | L   | 0.539      | -            | -                | -                | -         |   -16.66 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           21 |     2471 | 2024-04-25 | The MongolZ       | L   | 0.532      | -            | -                | -                | -         |    -9.65 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           20 |     2491 | 2024-04-24 | TYLOO             | W   | 0.525      | -            | -                | -                | -         |     0.02 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           19 |     2792 | 2024-04-13 | MOUZ              | L   | 0.451      | -            | -                | -                | -         |   -10.30 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           18 |     2805 | 2024-04-12 | Virtus.pro        | W   | 0.444      | -            | -                | -                | -         |     2.38 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           17 |     2875 | 2024-04-10 | HEROIC            | W   | 0.432      | -            | -                | -                | -         |     1.25 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           16 |     2935 | 2024-04-09 | Lynn Vision       | W   | 0.425      | -            | -                | -                | -         |     0.06 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           15 |     2966 | 2024-04-08 | Liquid            | L   | 0.418      | -            | -                | -                | -         |   -12.32 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           14 |     2975 | 2024-04-07 | 9z                | W   | 0.417      | -            | -                | -                | -         |     0.18 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           13 |     3167 | 2024-03-30 | Natus Vincere     | L   | 0.361      | -            | -                | -                | -         |    -5.98 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           12 |     3174 | 2024-03-29 | MOUZ              | W   | 0.354      | 1.000        | 1.000 (0.354)    | -                | -         |     2.80 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           11 |     3268 | 2024-03-24 | Virtus.pro        | W   | 0.319      | 1.000        | 0.496 (0.158)    | -                | -         |     1.68 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           10 |     3279 | 2024-03-23 | Gaimin Gladiators | W   | 0.313      | -            | -                | -                | -         |     0.04 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            9 |     3296 | 2024-03-22 | Cloud9            | L   | 0.305      | -            | -                | -                | -         |    -9.57 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            8 |     3306 | 2024-03-21 | Natus Vincere     | L   | 0.301      | -            | -                | -                | -         |    -5.02 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            7 |     3315 | 2024-03-21 | FURIA             | W   | 0.300      | -            | -                | -                | -         |     1.54 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            6 |     4131 | 2024-02-15 | FaZe              | W   | 0.066      | -            | -                | -                | -         |     0.32 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            5 |     4161 | 2024-02-14 | Eternal Fire      | W   | 0.061      | -            | -                | -                | -         |     0.30 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            4 |     4178 | 2024-02-14 | Into the Breach   | W   | 0.059      | -            | -                | -                | -         |     0.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            3 |     4243 | 2024-02-09 | FaZe              | L   | 0.026      | -            | -                | -                | -         |    -0.70 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            2 |     4271 | 2024-02-06 | HEROIC            | W   | 0.007      | -            | -                | -                | -         |     0.02 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            1 |     4277 | 2024-02-06 | Monte             | W   | 0.005      | -            | -                | -                | -         |     0.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($345,783.52)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $175,000.00    | $175,000.00     |
| 2024-06-16 |      0.879 | $10,000.00     | $8,792.13       |
| 2024-06-02 |      0.787 | $100,000.00    | $78,699.07      |
| 2024-05-12 |      0.646 | $32,000.00     | $20,677.04      |
| 2024-04-14 |      0.458 | $20,000.00     | $9,165.28       |
| 2024-03-31 |      0.367 | $80,000.00     | $29,359.26      |
| 2024-02-11 |      0.040 | $40,000.00     | $1,590.74       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
