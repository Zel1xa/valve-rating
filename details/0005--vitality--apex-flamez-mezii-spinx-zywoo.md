### Roster Details<br />
Team Name: Vitality<br />
Roster: apEX, flameZ, mezii, Spinx, ZywOo<br />
Global Rank: [5](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [5]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1854.0<br />
<br />
Final Rank Value (1854.0) = Starting Rank Value (1852.5) + Head To Head Adjustments (1.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.841[<sup>1</sup>](#table2)
- Bounty Collected: 0.700[<sup>2</sup>](#table1)
- Opponent Network: 0.292[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.708<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1852.5
- 400 + ( ( 0.708 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1852.5


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
|           31 |       68 | 2024-08-03 | Astralis     | W   | 1.000      | 0.581        | 0.389 (0.226)    | 0.413 (0.240)    | 1 (1.000) |     9.51 | apEX, flameZ, mezii, Spinx, ZywOo |
|           30 |      232 | 2024-07-30 | Astralis     | W   | 1.000      | 0.581        | 0.389 (0.226)    | 0.413 (0.240)    | 1 (1.000) |    10.03 | apEX, flameZ, mezii, Spinx, ZywOo |
|           29 |      265 | 2024-07-29 | GamerLegion  | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.68 | apEX, flameZ, mezii, Spinx, ZywOo |
|           28 |      592 | 2024-07-19 | Virtus.pro   | L   | 1.000      | -            | -                | -                | -         |   -22.18 | apEX, flameZ, mezii, Spinx, ZywOo |
|           27 |      708 | 2024-07-17 | M80          | W   | 1.000      | 1.000        | -                | 0.577 (0.577)    | 1 (1.000) |     0.97 | apEX, flameZ, mezii, Spinx, ZywOo |
|           26 |     1056 | 2024-06-15 | Spirit       | L   | 0.859      | -            | -                | -                | -         |   -11.54 | apEX, flameZ, mezii, Spinx, ZywOo |
|           25 |     1096 | 2024-06-14 | FaZe         | W   | 0.853      | 0.729        | 0.631 (0.392)    | 0.394 (0.245)    | 1 (0.853) |     8.40 | apEX, flameZ, mezii, Spinx, ZywOo |
|           24 |     1129 | 2024-06-13 | G2           | W   | 0.846      | 0.729        | 1.000 (0.617)    | 0.490 (0.302)    | 1 (0.846) |    16.95 | apEX, flameZ, mezii, Spinx, ZywOo |
|           23 |     1160 | 2024-06-12 | Virtus.pro   | L   | 0.840      | -            | -                | -                | -         |   -20.03 | apEX, flameZ, mezii, Spinx, ZywOo |
|           22 |     1585 | 2024-06-02 | G2           | L   | 0.774      | -            | -                | -                | -         |    -9.43 | apEX, flameZ, mezii, Spinx, ZywOo |
|           21 |     1614 | 2024-06-01 | Spirit       | W   | 0.767      | 0.624        | 1.000 (0.479)    | -                | 1 (0.767) |    13.78 | apEX, flameZ, mezii, Spinx, ZywOo |
|           20 |     1649 | 2024-05-31 | HEROIC       | W   | 0.760      | -            | -                | -                | 1 (0.760) |     4.18 | apEX, flameZ, mezii, Spinx, ZywOo |
|           19 |     1697 | 2024-05-29 | 9z           | L   | 0.748      | -            | -                | -                | -         |   -21.29 | apEX, flameZ, mezii, Spinx, ZywOo |
|           18 |     1741 | 2024-05-27 | G2           | W   | 0.735      | 0.624        | 1.000 (0.459)    | 0.490 (0.225)    | 1 (0.735) |    13.76 | apEX, flameZ, mezii, Spinx, ZywOo |
|           17 |     1751 | 2024-05-27 | Monte        | W   | 0.733      | 0.624        | -                | 0.611 (0.280)    | 1 (0.733) |     0.22 | apEX, flameZ, mezii, Spinx, ZywOo |
|           16 |     2221 | 2024-05-12 | MOUZ         | L   | 0.633      | -            | -                | -                | -         |    -9.68 | apEX, flameZ, mezii, Spinx, ZywOo |
|           15 |     2253 | 2024-05-11 | Astralis     | W   | 0.626      | 0.889        | 0.389 (0.217)    | 0.413 (0.230)    | -         |     6.80 | apEX, flameZ, mezii, Spinx, ZywOo |
|           14 |     2270 | 2024-05-10 | FaZe         | W   | 0.620      | 0.889        | 0.631 (0.348)    | -                | -         |     6.55 | apEX, flameZ, mezii, Spinx, ZywOo |
|           13 |     2522 | 2024-04-28 | The MongolZ  | W   | 0.538      | 0.889        | 1.000 (0.479)    | 0.710 (0.340)    | -         |    10.04 | apEX, flameZ, mezii, Spinx, ZywOo |
|           12 |     2595 | 2024-04-25 | BetBoom      | W   | 0.519      | 0.889        | -                | 0.529 (0.244)    | -         |     1.24 | apEX, flameZ, mezii, Spinx, ZywOo |
|           11 |     2632 | 2024-04-23 | Sharks       | W   | 0.506      | -            | -                | -                | -         |     0.04 | apEX, flameZ, mezii, Spinx, ZywOo |
|           10 |     3296 | 2024-03-30 | FaZe         | L   | 0.346      | -            | -                | -                | -         |    -7.75 | apEX, flameZ, mezii, Spinx, ZywOo |
|            9 |     3323 | 2024-03-28 | Cloud9       | W   | 0.333      | -            | -                | -                | -         |     0.13 | apEX, flameZ, mezii, Spinx, ZywOo |
|            8 |     3410 | 2024-03-23 | Complexity   | W   | 0.300      | -            | -                | -                | -         |     2.31 | apEX, flameZ, mezii, Spinx, ZywOo |
|            7 |     3427 | 2024-03-22 | Imperial     | W   | 0.292      | -            | -                | -                | -         |     0.34 | apEX, flameZ, mezii, Spinx, ZywOo |
|            6 |     3446 | 2024-03-21 | The MongolZ  | W   | 0.287      | 1.000        | 1.000 (0.287)    | -                | -         |     5.60 | apEX, flameZ, mezii, Spinx, ZywOo |
|            5 |     3453 | 2024-03-21 | Eternal Fire | L   | 0.286      | -            | -                | -                | -         |    -6.29 | apEX, flameZ, mezii, Spinx, ZywOo |
|            4 |     4109 | 2024-02-21 | ENCE         | W   | 0.093      | -            | -                | -                | -         |     0.32 | apEX, flameZ, mezii, Spinx, ZywOo |
|            3 |     4139 | 2024-02-20 | Cloud9       | L   | 0.086      | -            | -                | -                | -         |    -2.67 | apEX, flameZ, mezii, Spinx, ZywOo |
|            2 |     4156 | 2024-02-19 | HEROIC       | W   | 0.081      | -            | -                | -                | -         |     0.42 | apEX, flameZ, mezii, Spinx, ZywOo |
|            1 |     4172 | 2024-02-19 | GamerLegion  | W   | 0.078      | -            | -                | -                | -         |     0.01 | apEX, flameZ, mezii, Spinx, ZywOo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($208,536.11)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.65) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.866 | $40,000.00     | $34,633.33      |
| 2024-06-02 |      0.774 | $42,000.00     | $32,491.67      |
| 2024-05-12 |      0.633 | $80,000.00     | $50,622.22      |
| 2024-03-31 |      0.354 | $80,000.00     | $28,288.89      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
