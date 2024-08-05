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
- Opponent Network: 0.366[<sup>2</sup>](#table1)
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
|           40 |       61 | 2024-08-03 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.544 (0.316)    | 1 (1.000) |     3.42 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           39 |      152 | 2024-08-01 | FaZe              | W   | 1.000      | 0.581        | 0.630 (0.366)    | 0.393 (0.229)    | 1 (1.000) |     6.22 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           38 |      196 | 2024-07-31 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.544 (0.316)    | 1 (1.000) |     3.28 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           37 |      506 | 2024-07-21 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |   -16.16 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           36 |      551 | 2024-07-20 | Virtus.pro        | W   | 1.000      | 1.000        | 0.498 (0.498)    | 0.317 (0.317)    | 1 (1.000) |     5.80 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           35 |      618 | 2024-07-18 | Spirit            | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.452 (0.452)    | 1 (1.000) |    14.61 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           34 |      718 | 2024-07-17 | The MongolZ       | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.710 (0.710)    | 1 (1.000) |     9.14 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           33 |     1130 | 2024-06-13 | Vitality          | L   | 0.846      | -            | -                | -                | -         |   -16.95 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           32 |     1586 | 2024-06-02 | Vitality          | W   | 0.773      | 0.624        | 0.648 (0.313)    | -                | 1 (0.773) |     9.42 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           31 |     1608 | 2024-06-01 | 9z                | W   | 0.767      | 0.624        | 0.404 (0.194)    | 0.607 (0.291)    | 1 (0.767) |     1.66 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           30 |     1645 | 2024-05-31 | FaZe              | W   | 0.761      | 0.624        | 0.630 (0.299)    | -                | 1 (0.761) |     5.73 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           29 |     1695 | 2024-05-29 | Liquid            | W   | 0.748      | 0.624        | -                | 0.450 (0.210)    | 1 (0.748) |     3.16 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           28 |     1718 | 2024-05-28 | MOUZ              | W   | 0.742      | 0.624        | 1.000 (0.463)    | -                | -         |    10.20 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           27 |     1742 | 2024-05-27 | Vitality          | L   | 0.734      | -            | -                | -                | -         |   -13.75 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           26 |     1753 | 2024-05-27 | Falcons           | W   | 0.733      | -            | -                | -                | -         |     1.23 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           25 |     2292 | 2024-05-09 | MOUZ              | L   | 0.613      | -            | -                | -                | -         |   -11.92 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           24 |     2318 | 2024-05-08 | 3DMAX             | W   | 0.605      | 0.889        | 0.508 (0.274)    | 1.000 (0.538)    | -         |     2.55 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           23 |     2336 | 2024-05-07 | BIG               | W   | 0.599      | -            | -                | -                | -         |     0.50 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           22 |     2513 | 2024-04-28 | M80               | W   | 0.540      | 0.889        | -                | 0.577 (0.277)    | -         |     0.33 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           21 |     2548 | 2024-04-27 | Falcons           | W   | 0.531      | -            | -                | -                | -         |     0.77 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           20 |     2571 | 2024-04-26 | M80               | L   | 0.525      | -            | -                | -                | -         |   -16.24 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           19 |     2600 | 2024-04-25 | The MongolZ       | L   | 0.518      | -            | -                | -                | -         |    -9.46 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           18 |     2620 | 2024-04-24 | TYLOO             | W   | 0.511      | -            | -                | -                | -         |     0.02 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           17 |     2921 | 2024-04-13 | MOUZ              | L   | 0.437      | -            | -                | -                | -         |    -9.15 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           16 |     2934 | 2024-04-12 | Virtus.pro        | W   | 0.430      | -            | -                | -                | -         |     2.25 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           15 |     3004 | 2024-04-10 | HEROIC            | W   | 0.418      | -            | -                | -                | -         |     1.21 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           14 |     3064 | 2024-04-09 | Lynn Vision       | W   | 0.411      | -            | -                | -                | -         |     0.08 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           13 |     3095 | 2024-04-08 | Liquid            | L   | 0.404      | -            | -                | -                | -         |   -11.47 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           12 |     3104 | 2024-04-07 | 9z                | W   | 0.403      | -            | -                | -                | -         |     1.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           11 |     3296 | 2024-03-30 | Natus Vincere     | L   | 0.347      | -            | -                | -                | -         |    -5.81 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           10 |     3303 | 2024-03-29 | MOUZ              | W   | 0.340      | 1.000        | 1.000 (0.340)    | -                | -         |     3.36 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            9 |     3400 | 2024-03-24 | Virtus.pro        | W   | 0.305      | -            | -                | -                | -         |     1.58 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            8 |     3412 | 2024-03-23 | Gaimin Gladiators | W   | 0.299      | -            | -                | -                | -         |     0.04 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            7 |     3430 | 2024-03-22 | Cloud9            | L   | 0.292      | -            | -                | -                | -         |    -9.14 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            6 |     3440 | 2024-03-21 | Natus Vincere     | L   | 0.287      | -            | -                | -                | -         |    -4.83 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            5 |     3449 | 2024-03-21 | FURIA             | W   | 0.286      | -            | -                | -                | -         |     1.48 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            4 |     4269 | 2024-02-15 | FaZe              | W   | 0.052      | -            | -                | -                | -         |     0.23 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            3 |     4299 | 2024-02-14 | Eternal Fire      | W   | 0.047      | -            | -                | -                | -         |     0.23 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            2 |     4316 | 2024-02-14 | Into the Breach   | W   | 0.045      | -            | -                | -                | -         |     0.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            1 |     4381 | 2024-02-09 | FaZe              | L   | 0.012      | -            | -                | -                | -         |    -0.34 | HooXi, huNter-, m0NESY, nexa, NiKo    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($341,892.96)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $175,000.00    | $175,000.00     |
| 2024-06-16 |      0.865 | $10,000.00     | $8,654.17       |
| 2024-06-02 |      0.773 | $100,000.00    | $77,319.44      |
| 2024-05-12 |      0.632 | $32,000.00     | $20,235.56      |
| 2024-04-14 |      0.444 | $20,000.00     | $8,889.35       |
| 2024-03-31 |      0.353 | $80,000.00     | $28,255.56      |
| 2024-02-11 |      0.026 | $40,000.00     | $1,038.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
