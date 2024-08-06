### Roster Details<br />
Team Name: Vitality<br />
Roster: apEX, flameZ, mezii, Spinx, ZywOo<br />
Global Rank: [5](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [5]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1853.1<br />
<br />
Final Rank Value (1853.1) = Starting Rank Value (1851.7) + Head To Head Adjustments (1.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.841[<sup>1</sup>](#table2)
- Bounty Collected: 0.698[<sup>2</sup>](#table1)
- Opponent Network: 0.290[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.707<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1851.7
- 400 + ( ( 0.707 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1851.7


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
|           31 |       75 | 2024-08-03 | Astralis     | W   | 1.000      | 0.581        | 0.389 (0.226)    | 0.412 (0.239)    | 1 (1.000) |     9.50 | apEX, flameZ, mezii, Spinx, ZywOo |
|           30 |      239 | 2024-07-30 | Astralis     | W   | 1.000      | 0.581        | 0.389 (0.226)    | 0.412 (0.239)    | 1 (1.000) |    10.03 | apEX, flameZ, mezii, Spinx, ZywOo |
|           29 |      272 | 2024-07-29 | GamerLegion  | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.68 | apEX, flameZ, mezii, Spinx, ZywOo |
|           28 |      599 | 2024-07-19 | Virtus.pro   | L   | 1.000      | -            | -                | -                | -         |   -22.19 | apEX, flameZ, mezii, Spinx, ZywOo |
|           27 |      715 | 2024-07-17 | M80          | W   | 1.000      | 1.000        | -                | 0.576 (0.576)    | 1 (1.000) |     0.97 | apEX, flameZ, mezii, Spinx, ZywOo |
|           26 |     1063 | 2024-06-15 | Spirit       | L   | 0.855      | -            | -                | -                | -         |   -11.47 | apEX, flameZ, mezii, Spinx, ZywOo |
|           25 |     1103 | 2024-06-14 | FaZe         | W   | 0.848      | 0.729        | 0.626 (0.387)    | 0.391 (0.242)    | 1 (0.848) |     8.29 | apEX, flameZ, mezii, Spinx, ZywOo |
|           24 |     1136 | 2024-06-13 | G2           | W   | 0.842      | 0.729        | 1.000 (0.614)    | 0.489 (0.300)    | 1 (0.842) |    16.90 | apEX, flameZ, mezii, Spinx, ZywOo |
|           23 |     1167 | 2024-06-12 | Virtus.pro   | L   | 0.835      | -            | -                | -                | -         |   -19.93 | apEX, flameZ, mezii, Spinx, ZywOo |
|           22 |     1592 | 2024-06-02 | G2           | L   | 0.769      | -            | -                | -                | -         |    -9.34 | apEX, flameZ, mezii, Spinx, ZywOo |
|           21 |     1621 | 2024-06-01 | Spirit       | W   | 0.762      | 0.624        | 1.000 (0.476)    | -                | 1 (0.762) |    13.70 | apEX, flameZ, mezii, Spinx, ZywOo |
|           20 |     1656 | 2024-05-31 | HEROIC       | W   | 0.756      | -            | -                | -                | 1 (0.756) |     4.13 | apEX, flameZ, mezii, Spinx, ZywOo |
|           19 |     1704 | 2024-05-29 | 9z           | L   | 0.743      | -            | -                | -                | -         |   -21.15 | apEX, flameZ, mezii, Spinx, ZywOo |
|           18 |     1748 | 2024-05-27 | G2           | W   | 0.730      | 0.624        | 1.000 (0.456)    | 0.489 (0.223)    | 1 (0.730) |    13.72 | apEX, flameZ, mezii, Spinx, ZywOo |
|           17 |     1758 | 2024-05-27 | Monte        | W   | 0.729      | 0.624        | -                | 0.611 (0.278)    | 1 (0.729) |     0.22 | apEX, flameZ, mezii, Spinx, ZywOo |
|           16 |     2228 | 2024-05-12 | MOUZ         | L   | 0.628      | -            | -                | -                | -         |    -9.63 | apEX, flameZ, mezii, Spinx, ZywOo |
|           15 |     2260 | 2024-05-11 | Astralis     | W   | 0.621      | 0.889        | 0.389 (0.215)    | 0.412 (0.228)    | -         |     6.74 | apEX, flameZ, mezii, Spinx, ZywOo |
|           14 |     2277 | 2024-05-10 | FaZe         | W   | 0.615      | 0.889        | 0.626 (0.343)    | -                | -         |     6.45 | apEX, flameZ, mezii, Spinx, ZywOo |
|           13 |     2529 | 2024-04-28 | The MongolZ  | W   | 0.534      | 0.889        | 1.000 (0.474)    | 0.709 (0.337)    | -         |     9.98 | apEX, flameZ, mezii, Spinx, ZywOo |
|           12 |     2602 | 2024-04-25 | BetBoom      | W   | 0.515      | 0.889        | -                | 0.526 (0.240)    | -         |     1.22 | apEX, flameZ, mezii, Spinx, ZywOo |
|           11 |     2639 | 2024-04-23 | Sharks       | W   | 0.501      | -            | -                | -                | -         |     0.04 | apEX, flameZ, mezii, Spinx, ZywOo |
|           10 |     3303 | 2024-03-30 | FaZe         | L   | 0.342      | -            | -                | -                | -         |    -7.67 | apEX, flameZ, mezii, Spinx, ZywOo |
|            9 |     3330 | 2024-03-28 | Cloud9       | W   | 0.328      | -            | -                | -                | -         |     0.13 | apEX, flameZ, mezii, Spinx, ZywOo |
|            8 |     3417 | 2024-03-23 | Complexity   | W   | 0.295      | -            | -                | -                | -         |     2.27 | apEX, flameZ, mezii, Spinx, ZywOo |
|            7 |     3434 | 2024-03-22 | Imperial     | W   | 0.288      | -            | -                | -                | -         |     0.33 | apEX, flameZ, mezii, Spinx, ZywOo |
|            6 |     3453 | 2024-03-21 | The MongolZ  | W   | 0.282      | 1.000        | 1.000 (0.282)    | -                | -         |     5.52 | apEX, flameZ, mezii, Spinx, ZywOo |
|            5 |     3460 | 2024-03-21 | Eternal Fire | L   | 0.281      | -            | -                | -                | -         |    -6.20 | apEX, flameZ, mezii, Spinx, ZywOo |
|            4 |     4116 | 2024-02-21 | ENCE         | W   | 0.088      | -            | -                | -                | -         |     0.31 | apEX, flameZ, mezii, Spinx, ZywOo |
|            3 |     4146 | 2024-02-20 | Cloud9       | L   | 0.081      | -            | -                | -                | -         |    -2.52 | apEX, flameZ, mezii, Spinx, ZywOo |
|            2 |     4163 | 2024-02-19 | HEROIC       | W   | 0.076      | -            | -                | -                | -         |     0.39 | apEX, flameZ, mezii, Spinx, ZywOo |
|            1 |     4179 | 2024-02-19 | GamerLegion  | W   | 0.074      | -            | -                | -                | -         |     0.01 | apEX, flameZ, mezii, Spinx, ZywOo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($207,393.33)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.65) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.861 | $40,000.00     | $34,444.44      |
| 2024-06-02 |      0.769 | $42,000.00     | $32,293.33      |
| 2024-05-12 |      0.628 | $80,000.00     | $50,244.44      |
| 2024-03-31 |      0.349 | $80,000.00     | $27,911.11      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
