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
- Bounty Collected: 0.756[<sup>2</sup>](#table1)
- Opponent Network: 0.370[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.781<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 2000.0
- 400 + ( ( 0.781 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 2000.0


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
|           40 |       52 | 2024-08-03 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.551 (0.320)    | 1 (1.000) |     3.42 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           39 |      143 | 2024-08-01 | FaZe              | W   | 1.000      | 0.581        | 0.632 (0.367)    | 0.399 (0.232)    | 1 (1.000) |     6.24 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           38 |      187 | 2024-07-31 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.551 (0.320)    | 1 (1.000) |     3.29 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           37 |      497 | 2024-07-21 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |   -16.15 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           36 |      542 | 2024-07-20 | Virtus.pro        | W   | 1.000      | 1.000        | 0.498 (0.498)    | 0.321 (0.321)    | 1 (1.000) |     5.81 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           35 |      609 | 2024-07-18 | Spirit            | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.458 (0.458)    | 1 (1.000) |    14.62 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           34 |      709 | 2024-07-17 | The MongolZ       | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.719 (0.719)    | 1 (1.000) |     9.15 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           33 |     1121 | 2024-06-13 | Vitality          | L   | 0.848      | -            | -                | -                | -         |   -16.97 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           32 |     1577 | 2024-06-02 | Vitality          | W   | 0.775      | 0.624        | 0.648 (0.313)    | -                | 1 (0.775) |     9.45 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           31 |     1599 | 2024-06-01 | 9z                | W   | 0.769      | 0.624        | 0.405 (0.194)    | 0.615 (0.295)    | 1 (0.769) |     1.67 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           30 |     1636 | 2024-05-31 | FaZe              | W   | 0.762      | 0.624        | 0.632 (0.301)    | -                | 1 (0.762) |     5.77 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           29 |     1686 | 2024-05-29 | Liquid            | W   | 0.749      | 0.624        | -                | 0.456 (0.213)    | 1 (0.749) |     3.17 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           28 |     1709 | 2024-05-28 | MOUZ              | W   | 0.743      | 0.624        | 1.000 (0.464)    | -                | -         |    10.24 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           27 |     1733 | 2024-05-27 | Vitality          | L   | 0.736      | -            | -                | -                | -         |   -13.76 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           26 |     1744 | 2024-05-27 | Falcons           | W   | 0.735      | -            | -                | -                | -         |     1.23 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           25 |     2283 | 2024-05-09 | MOUZ              | L   | 0.615      | -            | -                | -                | -         |   -11.92 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           24 |     2309 | 2024-05-08 | 3DMAX             | W   | 0.607      | 0.889        | 0.508 (0.274)    | 1.000 (0.540)    | -         |     2.54 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           23 |     2327 | 2024-05-07 | BIG               | W   | 0.600      | -            | -                | -                | -         |     0.50 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           22 |     2504 | 2024-04-28 | M80               | W   | 0.541      | 0.889        | -                | 0.584 (0.281)    | -         |     0.33 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           21 |     2539 | 2024-04-27 | Falcons           | W   | 0.533      | -            | -                | -                | -         |     0.77 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           20 |     2562 | 2024-04-26 | M80               | L   | 0.526      | -            | -                | -                | -         |   -16.29 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           19 |     2591 | 2024-04-25 | The MongolZ       | L   | 0.520      | -            | -                | -                | -         |    -9.47 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           18 |     2611 | 2024-04-24 | TYLOO             | W   | 0.513      | -            | -                | -                | -         |     0.02 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           17 |     2912 | 2024-04-13 | MOUZ              | L   | 0.438      | -            | -                | -                | -         |    -9.16 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           16 |     2925 | 2024-04-12 | Virtus.pro        | W   | 0.432      | -            | -                | -                | -         |     2.27 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           15 |     2995 | 2024-04-10 | HEROIC            | W   | 0.420      | -            | -                | -                | -         |     1.22 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           14 |     3055 | 2024-04-09 | Lynn Vision       | W   | 0.413      | -            | -                | -                | -         |     0.08 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           13 |     3086 | 2024-04-08 | Liquid            | L   | 0.406      | -            | -                | -                | -         |   -11.51 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           12 |     3095 | 2024-04-07 | 9z                | W   | 0.404      | -            | -                | -                | -         |     1.01 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           11 |     3287 | 2024-03-30 | Natus Vincere     | L   | 0.349      | -            | -                | -                | -         |    -5.83 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           10 |     3294 | 2024-03-29 | MOUZ              | W   | 0.342      | 1.000        | 1.000 (0.342)    | -                | -         |     3.39 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            9 |     3391 | 2024-03-24 | Virtus.pro        | W   | 0.307      | -            | -                | -                | -         |     1.59 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            8 |     3403 | 2024-03-23 | Gaimin Gladiators | W   | 0.301      | -            | -                | -                | -         |     0.04 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            7 |     3421 | 2024-03-22 | Cloud9            | L   | 0.293      | -            | -                | -                | -         |    -9.18 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            6 |     3431 | 2024-03-21 | Natus Vincere     | L   | 0.289      | -            | -                | -                | -         |    -4.86 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            5 |     3440 | 2024-03-21 | FURIA             | W   | 0.287      | -            | -                | -                | -         |     1.49 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            4 |     4260 | 2024-02-15 | FaZe              | W   | 0.053      | -            | -                | -                | -         |     0.24 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            3 |     4290 | 2024-02-14 | Eternal Fire      | W   | 0.048      | -            | -                | -                | -         |     0.23 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            2 |     4307 | 2024-02-14 | Into the Breach   | W   | 0.046      | -            | -                | -                | -         |     0.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            1 |     4372 | 2024-02-09 | FaZe              | L   | 0.014      | -            | -                | -                | -         |    -0.38 | HooXi, huNter-, m0NESY, nexa, NiKo    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($342,323.80)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $175,000.00    | $175,000.00     |
| 2024-06-16 |      0.867 | $10,000.00     | $8,669.44       |
| 2024-06-02 |      0.775 | $100,000.00    | $77,472.22      |
| 2024-05-12 |      0.634 | $32,000.00     | $20,284.44      |
| 2024-04-14 |      0.446 | $20,000.00     | $8,919.91       |
| 2024-03-31 |      0.355 | $80,000.00     | $28,377.78      |
| 2024-02-11 |      0.028 | $40,000.00     | $1,100.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
