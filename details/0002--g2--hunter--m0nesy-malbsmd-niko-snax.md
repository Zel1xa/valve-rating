### Roster Details<br />
Team Name: G2<br />
Roster: huNter-, m0NESY, malbsMd, NiKo, Snax<br />
Global Rank: [2](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [2]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1956.5<br />
<br />
Final Rank Value (1956.5) = Starting Rank Value (2000.0) + Head To Head Adjustments (-43.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.752[<sup>2</sup>](#table1)
- Opponent Network: 0.351[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.776<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 2000.0
- 400 + ( ( 0.776 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 2000.0


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
|           42 |       21 | 2024-07-31 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.477 (0.277)    | 1 (1.000) |     2.94 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           41 |      331 | 2024-07-21 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |   -15.58 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           40 |      376 | 2024-07-20 | Virtus.pro        | W   | 1.000      | 1.000        | 0.494 (0.494)    | 0.327 (0.327)    | 1 (1.000) |     6.35 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           39 |      443 | 2024-07-18 | Spirit            | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.424 (0.424)    | 1 (1.000) |    15.29 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           38 |      543 | 2024-07-17 | The MongolZ       | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.719 (0.719)    | 1 (1.000) |     9.18 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           37 |      955 | 2024-06-13 | Vitality          | L   | 0.879      | -            | -                | -                | -         |   -17.26 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           36 |     1411 | 2024-06-02 | Vitality          | W   | 0.806      | 0.624        | 0.654 (0.329)    | 0.385 (0.194)    | 1 (0.806) |    10.14 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           35 |     1433 | 2024-06-01 | 9z                | W   | 0.800      | 0.624        | 0.408 (0.204)    | 0.625 (0.312)    | 1 (0.800) |     1.86 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           34 |     1470 | 2024-05-31 | FaZe              | W   | 0.794      | 0.624        | 0.663 (0.328)    | 0.410 (0.203)    | 1 (0.794) |     6.97 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           33 |     1520 | 2024-05-29 | Liquid            | W   | 0.781      | 0.624        | 0.387 (0.189)    | 0.430 (0.210)    | 1 (0.781) |     2.25 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           32 |     1543 | 2024-05-28 | MOUZ              | W   | 0.774      | 0.624        | 1.000 (0.483)    | -                | 1 (0.774) |    11.61 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           31 |     1567 | 2024-05-27 | Vitality          | L   | 0.767      | -            | -                | -                | -         |   -13.96 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           30 |     1578 | 2024-05-27 | Falcons           | W   | 0.766      | -            | -                | -                | 1 (0.766) |     1.56 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           29 |     2117 | 2024-05-09 | MOUZ              | L   | 0.646      | -            | -                | -                | -         |   -11.68 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           28 |     2143 | 2024-05-08 | 3DMAX             | W   | 0.638      | 0.889        | 0.499 (0.283)    | 1.000 (0.567)    | -         |     2.74 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           27 |     2161 | 2024-05-07 | BIG               | W   | 0.632      | -            | -                | -                | -         |     0.40 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           26 |     2338 | 2024-04-28 | M80               | W   | 0.573      | 0.889        | -                | 0.551 (0.281)    | -         |     0.39 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           25 |     2373 | 2024-04-27 | Falcons           | W   | 0.564      | -            | -                | -                | -         |     0.99 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           24 |     2396 | 2024-04-26 | M80               | L   | 0.558      | -            | -                | -                | -         |   -17.22 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           23 |     2425 | 2024-04-25 | The MongolZ       | L   | 0.551      | -            | -                | -                | -         |    -9.89 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           22 |     2445 | 2024-04-24 | TYLOO             | W   | 0.544      | -            | -                | -                | -         |     0.02 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           21 |     2746 | 2024-04-13 | MOUZ              | L   | 0.470      | -            | -                | -                | -         |    -9.21 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           20 |     2759 | 2024-04-12 | Virtus.pro        | W   | 0.463      | -            | -                | -                | -         |     2.79 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           19 |     2829 | 2024-04-10 | HEROIC            | W   | 0.451      | -            | -                | -                | -         |     1.52 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           18 |     2889 | 2024-04-09 | Lynn Vision       | W   | 0.444      | -            | -                | -                | -         |     0.06 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           17 |     2920 | 2024-04-08 | Liquid            | L   | 0.437      | -            | -                | -                | -         |   -13.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           16 |     2929 | 2024-04-07 | 9z                | W   | 0.436      | -            | -                | -                | -         |     1.21 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           15 |     3121 | 2024-03-30 | Natus Vincere     | L   | 0.380      | -            | -                | -                | -         |    -6.08 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           14 |     3128 | 2024-03-29 | MOUZ              | W   | 0.373      | 1.000        | 1.000 (0.373)    | -                | -         |     4.19 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           13 |     3225 | 2024-03-24 | Virtus.pro        | W   | 0.338      | -            | -                | -                | -         |     2.03 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           12 |     3237 | 2024-03-23 | Gaimin Gladiators | W   | 0.332      | -            | -                | -                | -         |     0.05 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           11 |     3255 | 2024-03-22 | Cloud9            | L   | 0.324      | -            | -                | -                | -         |   -10.15 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           10 |     3265 | 2024-03-21 | Natus Vincere     | L   | 0.320      | -            | -                | -                | -         |    -5.13 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            9 |     3274 | 2024-03-21 | FURIA             | W   | 0.319      | -            | -                | -                | -         |     1.83 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            8 |     4094 | 2024-02-15 | FaZe              | W   | 0.085      | -            | -                | -                | -         |     0.47 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            7 |     4124 | 2024-02-14 | Eternal Fire      | W   | 0.080      | -            | -                | -                | -         |     0.44 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            6 |     4141 | 2024-02-14 | Into the Breach   | W   | 0.078      | -            | -                | -                | -         |     0.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            5 |     4206 | 2024-02-09 | FaZe              | L   | 0.045      | -            | -                | -                | -         |    -1.18 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            4 |     4234 | 2024-02-06 | HEROIC            | W   | 0.026      | -            | -                | -                | -         |     0.08 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            3 |     4240 | 2024-02-06 | Monte             | W   | 0.024      | -            | -                | -                | -         |     0.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            2 |     4246 | 2024-02-05 | ENCE              | L   | 0.019      | -            | -                | -                | -         |    -0.56 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            1 |     4301 | 2024-02-03 | HEROIC            | W   | 0.004      | -            | -                | -                | -         |     0.01 | HooXi, huNter-, m0NESY, nexa, NiKo    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($351,145.44)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-31 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $175,000.00    | $175,000.00     |
| 2024-06-16 |      0.898 | $10,000.00     | $8,982.27       |
| 2024-06-02 |      0.806 | $100,000.00    | $80,600.46      |
| 2024-05-12 |      0.665 | $32,000.00     | $21,285.48      |
| 2024-04-14 |      0.477 | $20,000.00     | $9,545.56       |
| 2024-03-31 |      0.386 | $80,000.00     | $30,880.37      |
| 2024-02-11 |      0.059 | $40,000.00     | $2,351.30       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
