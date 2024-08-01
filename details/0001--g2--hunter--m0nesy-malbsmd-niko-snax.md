### Roster Details<br />
Team Name: G2<br />
Roster: huNter-, m0NESY, malbsMd, NiKo, Snax<br />
Global Rank: [1](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [1]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1957.2<br />
<br />
Final Rank Value (1957.2) = Starting Rank Value (2000.0) + Head To Head Adjustments (-42.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.756[<sup>2</sup>](#table1)
- Opponent Network: 0.355[<sup>2</sup>](#table1)
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
|           42 |       11 | 2024-08-01 | FaZe              | W   | 1.000      | 0.581        | 0.637 (0.370)    | 0.408 (0.237)    | 1 (1.000) |     6.96 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           41 |       56 | 2024-07-31 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.447 (0.260)    | 1 (1.000) |     2.09 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           40 |      367 | 2024-07-21 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |   -15.67 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           39 |      414 | 2024-07-20 | Virtus.pro        | W   | 1.000      | 1.000        | 0.484 (0.484)    | 0.326 (0.326)    | 1 (1.000) |     5.93 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           38 |      487 | 2024-07-18 | Spirit            | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.423 (0.423)    | 1 (1.000) |    15.07 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           37 |      587 | 2024-07-17 | The MongolZ       | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.719 (0.719)    | 1 (1.000) |     9.06 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           36 |      996 | 2024-06-13 | Vitality          | L   | 0.873      | -            | -                | -                | -         |   -17.62 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           35 |     1469 | 2024-06-02 | Vitality          | W   | 0.800      | 0.624        | 0.590 (0.295)    | -                | 1 (0.800) |     9.60 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           34 |     1491 | 2024-06-01 | 9z                | W   | 0.794      | 0.624        | -                | 0.553 (0.274)    | 1 (0.794) |     0.47 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           33 |     1528 | 2024-05-31 | FaZe              | W   | 0.788      | 0.624        | 0.637 (0.313)    | 0.408 (0.200)    | 1 (0.788) |     6.67 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           32 |     1578 | 2024-05-29 | Liquid            | W   | 0.775      | 0.624        | -                | 0.467 (0.226)    | 1 (0.775) |     2.54 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           31 |     1601 | 2024-05-28 | MOUZ              | W   | 0.768      | 0.624        | 1.000 (0.480)    | -                | 1 (0.768) |    11.26 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           30 |     1625 | 2024-05-27 | Vitality          | L   | 0.761      | -            | -                | -                | -         |   -14.35 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           29 |     1636 | 2024-05-27 | Falcons           | W   | 0.760      | -            | -                | -                | -         |     1.44 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           28 |     2212 | 2024-05-09 | MOUZ              | L   | 0.640      | -            | -                | -                | -         |   -11.74 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           27 |     2240 | 2024-05-08 | 3DMAX             | W   | 0.632      | 0.889        | 0.505 (0.284)    | 1.000 (0.562)    | -         |     2.61 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           26 |     2258 | 2024-05-07 | BIG               | W   | 0.626      | -            | -                | -                | -         |     0.37 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           25 |     2438 | 2024-04-28 | M80               | W   | 0.567      | 0.889        | -                | 0.641 (0.323)    | -         |     0.38 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           24 |     2474 | 2024-04-27 | Falcons           | W   | 0.558      | -            | -                | -                | -         |     0.91 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           23 |     2497 | 2024-04-26 | M80               | L   | 0.552      | -            | -                | -                | -         |   -17.04 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           22 |     2525 | 2024-04-25 | The MongolZ       | L   | 0.545      | -            | -                | -                | -         |    -9.86 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           21 |     2545 | 2024-04-24 | TYLOO             | W   | 0.538      | -            | -                | -                | -         |     0.02 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           20 |     2856 | 2024-04-13 | MOUZ              | L   | 0.464      | -            | -                | -                | -         |    -9.22 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           19 |     2870 | 2024-04-12 | Virtus.pro        | W   | 0.457      | -            | -                | -                | -         |     2.54 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           18 |     2940 | 2024-04-10 | HEROIC            | W   | 0.445      | -            | -                | -                | -         |     1.35 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           17 |     3000 | 2024-04-09 | Lynn Vision       | W   | 0.438      | -            | -                | -                | -         |     0.06 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           16 |     3031 | 2024-04-08 | Liquid            | L   | 0.431      | -            | -                | -                | -         |   -12.62 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           15 |     3040 | 2024-04-07 | 9z                | W   | 0.430      | -            | -                | -                | -         |     0.13 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           14 |     3240 | 2024-03-30 | Natus Vincere     | L   | 0.374      | -            | -                | -                | -         |    -6.08 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           13 |     3247 | 2024-03-29 | MOUZ              | W   | 0.367      | 1.000        | 1.000 (0.367)    | -                | -         |     4.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           12 |     3349 | 2024-03-24 | Virtus.pro        | W   | 0.332      | 1.000        | 0.484 (0.161)    | -                | -         |     1.83 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           11 |     3361 | 2024-03-23 | Gaimin Gladiators | W   | 0.326      | -            | -                | -                | -         |     0.04 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           10 |     3379 | 2024-03-22 | Cloud9            | L   | 0.318      | -            | -                | -                | -         |    -9.97 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            9 |     3389 | 2024-03-21 | Natus Vincere     | L   | 0.314      | -            | -                | -                | -         |    -5.12 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            8 |     3398 | 2024-03-21 | FURIA             | W   | 0.313      | -            | -                | -                | -         |     1.73 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            7 |     4239 | 2024-02-15 | FaZe              | W   | 0.079      | -            | -                | -                | -         |     0.42 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            6 |     4269 | 2024-02-14 | Eternal Fire      | W   | 0.074      | -            | -                | -                | -         |     0.39 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            5 |     4286 | 2024-02-14 | Into the Breach   | W   | 0.072      | -            | -                | -                | -         |     0.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            4 |     4361 | 2024-02-09 | FaZe              | L   | 0.039      | -            | -                | -                | -         |    -1.03 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            3 |     4389 | 2024-02-06 | HEROIC            | W   | 0.020      | -            | -                | -                | -         |     0.05 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            2 |     4395 | 2024-02-06 | Monte             | W   | 0.018      | -            | -                | -                | -         |     0.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            1 |     4401 | 2024-02-05 | ENCE              | L   | 0.013      | -            | -                | -                | -         |    -0.39 | HooXi, huNter-, m0NESY, nexa, NiKo    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($326,952.13)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $175,000.00    | $175,000.00     |
| 2024-06-16 |      0.892 | $10,000.00     | $8,922.22       |
| 2024-06-02 |      0.800 | $100,000.00    | $80,000.00      |
| 2024-05-12 |      0.659 | $32,000.00     | $21,093.33      |
| 2024-04-14 |      0.471 | $20,000.00     | $9,425.46       |
| 2024-03-31 |      0.380 | $80,000.00     | $30,400.00      |
| 2024-02-11 |      0.053 | $40,000.00     | $2,111.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
