### Roster Details<br />
Team Name: Vitality<br />
Roster: apEX, flameZ, mezii, Spinx, ZywOo<br />
Global Rank: [5](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [5]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1848.6<br />
<br />
Final Rank Value (1848.6) = Starting Rank Value (1849.3) + Head To Head Adjustments (-0.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.842[<sup>1</sup>](#table2)
- Bounty Collected: 0.700[<sup>2</sup>](#table1)
- Opponent Network: 0.294[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.709<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1849.3
- 400 + ( ( 0.709 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1849.3


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
|           31 |       13 | 2024-08-03 | Astralis     | W   | 1.000      | 0.581        | 0.352 (0.205)    | 0.382 (0.222)    | 1 (1.000) |     8.63 | apEX, flameZ, mezii, Spinx, ZywOo |
|           30 |      175 | 2024-07-30 | Astralis     | W   | 1.000      | 0.581        | 0.352 (0.205)    | -                | 1 (1.000) |     9.03 | apEX, flameZ, mezii, Spinx, ZywOo |
|           29 |      208 | 2024-07-29 | GamerLegion  | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.69 | apEX, flameZ, mezii, Spinx, ZywOo |
|           28 |      535 | 2024-07-19 | Virtus.pro   | L   | 1.000      | -            | -                | -                | -         |   -22.17 | apEX, flameZ, mezii, Spinx, ZywOo |
|           27 |      651 | 2024-07-17 | M80          | W   | 1.000      | 1.000        | -                | 0.587 (0.587)    | 1 (1.000) |     1.01 | apEX, flameZ, mezii, Spinx, ZywOo |
|           26 |      999 | 2024-06-15 | Spirit       | L   | 0.868      | -            | -                | -                | -         |   -11.58 | apEX, flameZ, mezii, Spinx, ZywOo |
|           25 |     1039 | 2024-06-14 | FaZe         | W   | 0.861      | 0.729        | 0.640 (0.402)    | 0.402 (0.253)    | 1 (0.861) |     8.58 | apEX, flameZ, mezii, Spinx, ZywOo |
|           24 |     1072 | 2024-06-13 | G2           | W   | 0.855      | 0.729        | 1.000 (0.623)    | 0.498 (0.310)    | 1 (0.855) |    17.16 | apEX, flameZ, mezii, Spinx, ZywOo |
|           23 |     1103 | 2024-06-12 | Virtus.pro   | L   | 0.848      | -            | -                | -                | -         |   -20.18 | apEX, flameZ, mezii, Spinx, ZywOo |
|           22 |     1528 | 2024-06-02 | G2           | L   | 0.782      | -            | -                | -                | -         |    -9.50 | apEX, flameZ, mezii, Spinx, ZywOo |
|           21 |     1557 | 2024-06-01 | Spirit       | W   | 0.776      | 0.624        | 1.000 (0.484)    | 0.460 (0.223)    | 1 (0.776) |    14.01 | apEX, flameZ, mezii, Spinx, ZywOo |
|           20 |     1592 | 2024-05-31 | HEROIC       | W   | 0.769      | -            | -                | -                | 1 (0.769) |     4.27 | apEX, flameZ, mezii, Spinx, ZywOo |
|           19 |     1640 | 2024-05-29 | 9z           | L   | 0.756      | -            | -                | -                | -         |   -21.51 | apEX, flameZ, mezii, Spinx, ZywOo |
|           18 |     1684 | 2024-05-27 | G2           | W   | 0.743      | 0.624        | 1.000 (0.464)    | 0.498 (0.231)    | 1 (0.743) |    13.97 | apEX, flameZ, mezii, Spinx, ZywOo |
|           17 |     1694 | 2024-05-27 | Monte        | W   | 0.742      | 0.624        | -                | 0.618 (0.286)    | 1 (0.742) |     0.23 | apEX, flameZ, mezii, Spinx, ZywOo |
|           16 |     2164 | 2024-05-12 | MOUZ         | L   | 0.641      | -            | -                | -                | -         |    -9.77 | apEX, flameZ, mezii, Spinx, ZywOo |
|           15 |     2196 | 2024-05-11 | Astralis     | W   | 0.635      | 0.889        | 0.352 (0.199)    | -                | -         |     6.00 | apEX, flameZ, mezii, Spinx, ZywOo |
|           14 |     2213 | 2024-05-10 | FaZe         | W   | 0.629      | 0.889        | 0.640 (0.357)    | 0.402 (0.225)    | -         |     6.72 | apEX, flameZ, mezii, Spinx, ZywOo |
|           13 |     2465 | 2024-04-28 | The MongolZ  | W   | 0.547      | 0.889        | 1.000 (0.486)    | 0.721 (0.350)    | -         |    10.17 | apEX, flameZ, mezii, Spinx, ZywOo |
|           12 |     2538 | 2024-04-25 | BetBoom      | W   | 0.528      | 0.889        | -                | 0.542 (0.254)    | -         |     1.29 | apEX, flameZ, mezii, Spinx, ZywOo |
|           11 |     2575 | 2024-04-23 | Sharks       | W   | 0.515      | -            | -                | -                | -         |     0.04 | apEX, flameZ, mezii, Spinx, ZywOo |
|           10 |     3239 | 2024-03-30 | FaZe         | L   | 0.355      | -            | -                | -                | -         |    -7.85 | apEX, flameZ, mezii, Spinx, ZywOo |
|            9 |     3266 | 2024-03-28 | Cloud9       | W   | 0.342      | -            | -                | -                | -         |     0.14 | apEX, flameZ, mezii, Spinx, ZywOo |
|            8 |     3353 | 2024-03-23 | Complexity   | W   | 0.308      | -            | -                | -                | -         |     2.32 | apEX, flameZ, mezii, Spinx, ZywOo |
|            7 |     3370 | 2024-03-22 | Imperial     | W   | 0.301      | -            | -                | -                | -         |     0.37 | apEX, flameZ, mezii, Spinx, ZywOo |
|            6 |     3389 | 2024-03-21 | The MongolZ  | W   | 0.295      | 1.000        | 1.000 (0.295)    | -                | -         |     5.76 | apEX, flameZ, mezii, Spinx, ZywOo |
|            5 |     3396 | 2024-03-21 | Eternal Fire | L   | 0.294      | -            | -                | -                | -         |    -6.45 | apEX, flameZ, mezii, Spinx, ZywOo |
|            4 |     4052 | 2024-02-21 | ENCE         | W   | 0.101      | -            | -                | -                | -         |     0.34 | apEX, flameZ, mezii, Spinx, ZywOo |
|            3 |     4082 | 2024-02-20 | Cloud9       | L   | 0.094      | -            | -                | -                | -         |    -2.94 | apEX, flameZ, mezii, Spinx, ZywOo |
|            2 |     4099 | 2024-02-19 | HEROIC       | W   | 0.089      | -            | -                | -                | -         |     0.47 | apEX, flameZ, mezii, Spinx, ZywOo |
|            1 |     4115 | 2024-02-19 | GamerLegion  | W   | 0.087      | -            | -                | -                | -         |     0.01 | apEX, flameZ, mezii, Spinx, ZywOo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($210,620.00)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.65) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.874 | $40,000.00     | $34,977.78      |
| 2024-06-02 |      0.782 | $42,000.00     | $32,853.33      |
| 2024-05-12 |      0.641 | $80,000.00     | $51,311.11      |
| 2024-03-31 |      0.362 | $80,000.00     | $28,977.78      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
