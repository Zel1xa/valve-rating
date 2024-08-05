### Roster Details<br />
Team Name: Vitality<br />
Roster: apEX, flameZ, mezii, Spinx, ZywOo<br />
Global Rank: [5](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [5]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1854.2<br />
<br />
Final Rank Value (1854.2) = Starting Rank Value (1852.8) + Head To Head Adjustments (1.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.841[<sup>1</sup>](#table2)
- Bounty Collected: 0.701[<sup>2</sup>](#table1)
- Opponent Network: 0.296[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.710<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1852.8
- 400 + ( ( 0.710 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1852.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           31 |       60 | 2024-08-03 | Astralis     | W   | 1.000      | 0.581        | 0.390 (0.226)    | 0.419 (0.243)    | 1 (1.000) |     9.51 | apEX, flameZ, mezii, Spinx, ZywOo |
|           30 |      224 | 2024-07-30 | Astralis     | W   | 1.000      | 0.581        | 0.390 (0.226)    | 0.419 (0.243)    | 1 (1.000) |    10.03 | apEX, flameZ, mezii, Spinx, ZywOo |
|           29 |      257 | 2024-07-29 | GamerLegion  | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.68 | apEX, flameZ, mezii, Spinx, ZywOo |
|           28 |      584 | 2024-07-19 | Virtus.pro   | L   | 1.000      | -            | -                | -                | -         |   -22.18 | apEX, flameZ, mezii, Spinx, ZywOo |
|           27 |      700 | 2024-07-17 | M80          | W   | 1.000      | 1.000        | -                | 0.584 (0.584)    | 1 (1.000) |     0.97 | apEX, flameZ, mezii, Spinx, ZywOo |
|           26 |     1048 | 2024-06-15 | Spirit       | L   | 0.861      | -            | -                | -                | -         |   -11.57 | apEX, flameZ, mezii, Spinx, ZywOo |
|           25 |     1088 | 2024-06-14 | FaZe         | W   | 0.854      | 0.729        | 0.632 (0.393)    | 0.399 (0.248)    | 1 (0.854) |     8.42 | apEX, flameZ, mezii, Spinx, ZywOo |
|           24 |     1121 | 2024-06-13 | G2           | W   | 0.848      | 0.729        | 1.000 (0.618)    | 0.496 (0.306)    | 1 (0.848) |    16.97 | apEX, flameZ, mezii, Spinx, ZywOo |
|           23 |     1152 | 2024-06-12 | Virtus.pro   | L   | 0.841      | -            | -                | -                | -         |   -20.05 | apEX, flameZ, mezii, Spinx, ZywOo |
|           22 |     1577 | 2024-06-02 | G2           | L   | 0.775      | -            | -                | -                | -         |    -9.45 | apEX, flameZ, mezii, Spinx, ZywOo |
|           21 |     1606 | 2024-06-01 | Spirit       | W   | 0.768      | 0.624        | 1.000 (0.479)    | -                | 1 (0.768) |    13.79 | apEX, flameZ, mezii, Spinx, ZywOo |
|           20 |     1641 | 2024-05-31 | HEROIC       | W   | 0.761      | -            | -                | -                | 1 (0.761) |     4.19 | apEX, flameZ, mezii, Spinx, ZywOo |
|           19 |     1689 | 2024-05-29 | 9z           | L   | 0.749      | -            | -                | -                | -         |   -21.32 | apEX, flameZ, mezii, Spinx, ZywOo |
|           18 |     1733 | 2024-05-27 | G2           | W   | 0.736      | 0.624        | 1.000 (0.459)    | 0.496 (0.228)    | 1 (0.736) |    13.76 | apEX, flameZ, mezii, Spinx, ZywOo |
|           17 |     1743 | 2024-05-27 | Monte        | W   | 0.735      | 0.624        | -                | 0.618 (0.283)    | 1 (0.735) |     0.22 | apEX, flameZ, mezii, Spinx, ZywOo |
|           16 |     2213 | 2024-05-12 | MOUZ         | L   | 0.634      | -            | -                | -                | -         |    -9.69 | apEX, flameZ, mezii, Spinx, ZywOo |
|           15 |     2245 | 2024-05-11 | Astralis     | W   | 0.627      | 0.889        | 0.390 (0.217)    | 0.419 (0.233)    | -         |     6.82 | apEX, flameZ, mezii, Spinx, ZywOo |
|           14 |     2262 | 2024-05-10 | FaZe         | W   | 0.621      | 0.889        | 0.632 (0.349)    | -                | -         |     6.58 | apEX, flameZ, mezii, Spinx, ZywOo |
|           13 |     2514 | 2024-04-28 | The MongolZ  | W   | 0.540      | 0.889        | 1.000 (0.480)    | 0.719 (0.345)    | -         |    10.07 | apEX, flameZ, mezii, Spinx, ZywOo |
|           12 |     2587 | 2024-04-25 | BetBoom      | W   | 0.520      | 0.889        | -                | 0.536 (0.248)    | -         |     1.24 | apEX, flameZ, mezii, Spinx, ZywOo |
|           11 |     2624 | 2024-04-23 | Sharks       | W   | 0.507      | -            | -                | -                | -         |     0.04 | apEX, flameZ, mezii, Spinx, ZywOo |
|           10 |     3288 | 2024-03-30 | FaZe         | L   | 0.347      | -            | -                | -                | -         |    -7.77 | apEX, flameZ, mezii, Spinx, ZywOo |
|            9 |     3315 | 2024-03-28 | Cloud9       | W   | 0.334      | -            | -                | -                | -         |     0.13 | apEX, flameZ, mezii, Spinx, ZywOo |
|            8 |     3402 | 2024-03-23 | Complexity   | W   | 0.301      | -            | -                | -                | -         |     2.32 | apEX, flameZ, mezii, Spinx, ZywOo |
|            7 |     3419 | 2024-03-22 | Imperial     | W   | 0.293      | -            | -                | -                | -         |     0.34 | apEX, flameZ, mezii, Spinx, ZywOo |
|            6 |     3438 | 2024-03-21 | The MongolZ  | W   | 0.288      | 1.000        | 1.000 (0.288)    | -                | -         |     5.63 | apEX, flameZ, mezii, Spinx, ZywOo |
|            5 |     3445 | 2024-03-21 | Eternal Fire | L   | 0.287      | -            | -                | -                | -         |    -6.33 | apEX, flameZ, mezii, Spinx, ZywOo |
|            4 |     4101 | 2024-02-21 | ENCE         | W   | 0.094      | -            | -                | -                | -         |     0.32 | apEX, flameZ, mezii, Spinx, ZywOo |
|            3 |     4131 | 2024-02-20 | Cloud9       | L   | 0.087      | -            | -                | -                | -         |    -2.71 | apEX, flameZ, mezii, Spinx, ZywOo |
|            2 |     4148 | 2024-02-19 | HEROIC       | W   | 0.082      | -            | -                | -                | -         |     0.42 | apEX, flameZ, mezii, Spinx, ZywOo |
|            1 |     4164 | 2024-02-19 | GamerLegion  | W   | 0.079      | -            | -                | -                | -         |     0.01 | apEX, flameZ, mezii, Spinx, ZywOo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($208,805.00)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.65) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.867 | $40,000.00     | $34,677.78      |
| 2024-06-02 |      0.775 | $42,000.00     | $32,538.33      |
| 2024-05-12 |      0.634 | $80,000.00     | $50,711.11      |
| 2024-03-31 |      0.355 | $80,000.00     | $28,377.78      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
