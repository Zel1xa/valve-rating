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
- Opponent Network: 0.365[<sup>2</sup>](#table1)
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
|           40 |       63 | 2024-08-03 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.544 (0.316)    | 1 (1.000) |     3.42 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           39 |      154 | 2024-08-01 | FaZe              | W   | 1.000      | 0.581        | 0.629 (0.365)    | 0.393 (0.228)    | 1 (1.000) |     6.19 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           38 |      198 | 2024-07-31 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | -                | 0.544 (0.316)    | 1 (1.000) |     3.28 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           37 |      508 | 2024-07-21 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |   -16.16 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           36 |      553 | 2024-07-20 | Virtus.pro        | W   | 1.000      | 1.000        | 0.498 (0.498)    | 0.316 (0.316)    | 1 (1.000) |     5.78 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           35 |      620 | 2024-07-18 | Spirit            | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.452 (0.452)    | 1 (1.000) |    14.60 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           34 |      720 | 2024-07-17 | The MongolZ       | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.710 (0.710)    | 1 (1.000) |     9.15 | huNter-, m0NESY, malbsMd, NiKo, Snax  |
|           33 |     1132 | 2024-06-13 | Vitality          | L   | 0.844      | -            | -                | -                | -         |   -16.93 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           32 |     1588 | 2024-06-02 | Vitality          | W   | 0.771      | 0.624        | 0.647 (0.312)    | -                | 1 (0.771) |     9.38 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           31 |     1610 | 2024-06-01 | 9z                | W   | 0.766      | 0.624        | 0.404 (0.193)    | 0.606 (0.289)    | 1 (0.766) |     1.65 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           30 |     1647 | 2024-05-31 | FaZe              | W   | 0.759      | 0.624        | 0.629 (0.298)    | -                | 1 (0.759) |     5.69 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           29 |     1697 | 2024-05-29 | Liquid            | W   | 0.746      | 0.624        | -                | 0.449 (0.209)    | 1 (0.746) |     3.14 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           28 |     1720 | 2024-05-28 | MOUZ              | W   | 0.740      | 0.624        | 1.000 (0.462)    | -                | -         |    10.15 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           27 |     1744 | 2024-05-27 | Vitality          | L   | 0.732      | -            | -                | -                | -         |   -13.74 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           26 |     1755 | 2024-05-27 | Falcons           | W   | 0.731      | -            | -                | -                | -         |     1.22 | huNter-, m0NESY, nexa, NiKo, Stewie2K |
|           25 |     2294 | 2024-05-09 | MOUZ              | L   | 0.611      | -            | -                | -                | -         |   -11.90 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           24 |     2320 | 2024-05-08 | 3DMAX             | W   | 0.604      | 0.889        | 0.509 (0.273)    | 1.000 (0.537)    | -         |     2.55 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           23 |     2338 | 2024-05-07 | BIG               | W   | 0.597      | -            | -                | -                | -         |     0.49 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           22 |     2515 | 2024-04-28 | M80               | W   | 0.538      | 0.889        | -                | 0.576 (0.276)    | -         |     0.33 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           21 |     2550 | 2024-04-27 | Falcons           | W   | 0.530      | -            | -                | -                | -         |     0.76 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           20 |     2573 | 2024-04-26 | M80               | L   | 0.523      | -            | -                | -                | -         |   -16.19 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           19 |     2602 | 2024-04-25 | The MongolZ       | L   | 0.516      | -            | -                | -                | -         |    -9.42 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           18 |     2622 | 2024-04-24 | TYLOO             | W   | 0.510      | -            | -                | -                | -         |     0.02 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           17 |     2923 | 2024-04-13 | MOUZ              | L   | 0.435      | -            | -                | -                | -         |    -9.12 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           16 |     2936 | 2024-04-12 | Virtus.pro        | W   | 0.428      | -            | -                | -                | -         |     2.24 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           15 |     3006 | 2024-04-10 | HEROIC            | W   | 0.416      | -            | -                | -                | -         |     1.20 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           14 |     3066 | 2024-04-09 | Lynn Vision       | W   | 0.410      | -            | -                | -                | -         |     0.07 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           13 |     3097 | 2024-04-08 | Liquid            | L   | 0.402      | -            | -                | -                | -         |   -11.42 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           12 |     3106 | 2024-04-07 | 9z                | W   | 0.401      | -            | -                | -                | -         |     0.99 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           11 |     3298 | 2024-03-30 | Natus Vincere     | L   | 0.345      | -            | -                | -                | -         |    -5.78 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|           10 |     3305 | 2024-03-29 | MOUZ              | W   | 0.338      | 1.000        | 1.000 (0.338)    | -                | -         |     3.34 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            9 |     3402 | 2024-03-24 | Virtus.pro        | W   | 0.304      | -            | -                | -                | -         |     1.56 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            8 |     3414 | 2024-03-23 | Gaimin Gladiators | W   | 0.297      | -            | -                | -                | -         |     0.04 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            7 |     3432 | 2024-03-22 | Cloud9            | L   | 0.290      | -            | -                | -                | -         |    -9.08 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            6 |     3442 | 2024-03-21 | Natus Vincere     | L   | 0.285      | -            | -                | -                | -         |    -4.80 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            5 |     3451 | 2024-03-21 | FURIA             | W   | 0.284      | -            | -                | -                | -         |     1.47 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            4 |     4271 | 2024-02-15 | FaZe              | W   | 0.050      | -            | -                | -                | -         |     0.23 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            3 |     4301 | 2024-02-14 | Eternal Fire      | W   | 0.045      | -            | -                | -                | -         |     0.22 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            2 |     4318 | 2024-02-14 | Into the Breach   | W   | 0.043      | -            | -                | -                | -         |     0.00 | HooXi, huNter-, m0NESY, nexa, NiKo    |
|            1 |     4383 | 2024-02-09 | FaZe              | L   | 0.011      | -            | -                | -                | -         |    -0.29 | HooXi, huNter-, m0NESY, nexa, NiKo    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($341,383.80)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $175,000.00    | $175,000.00     |
| 2024-06-16 |      0.864 | $10,000.00     | $8,636.11       |
| 2024-06-02 |      0.771 | $100,000.00    | $77,138.89      |
| 2024-05-12 |      0.631 | $32,000.00     | $20,177.78      |
| 2024-04-14 |      0.443 | $20,000.00     | $8,853.24       |
| 2024-03-31 |      0.351 | $80,000.00     | $28,111.11      |
| 2024-02-11 |      0.024 | $40,000.00     | $966.67         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
