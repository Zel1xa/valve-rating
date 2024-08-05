### Roster Details<br />
Team Name: Vitality<br />
Roster: apEX, flameZ, mezii, Spinx, ZywOo<br />
Global Rank: [5](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [5]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1854.7<br />
<br />
Final Rank Value (1854.7) = Starting Rank Value (1853.4) + Head To Head Adjustments (1.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.842[<sup>1</sup>](#table2)
- Bounty Collected: 0.702[<sup>2</sup>](#table1)
- Opponent Network: 0.298[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.710<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1853.4
- 400 + ( ( 0.710 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1853.4


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
|           31 |       47 | 2024-08-03 | Astralis     | W   | 1.000      | 0.581        | 0.390 (0.227)    | 0.421 (0.244)    | 1 (1.000) |     9.51 | apEX, flameZ, mezii, Spinx, ZywOo |
|           30 |      211 | 2024-07-30 | Astralis     | W   | 1.000      | 0.581        | 0.390 (0.227)    | 0.421 (0.244)    | 1 (1.000) |    10.03 | apEX, flameZ, mezii, Spinx, ZywOo |
|           29 |      244 | 2024-07-29 | GamerLegion  | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.68 | apEX, flameZ, mezii, Spinx, ZywOo |
|           28 |      571 | 2024-07-19 | Virtus.pro   | L   | 1.000      | -            | -                | -                | -         |   -22.17 | apEX, flameZ, mezii, Spinx, ZywOo |
|           27 |      687 | 2024-07-17 | M80          | W   | 1.000      | 1.000        | -                | 0.587 (0.587)    | 1 (1.000) |     0.97 | apEX, flameZ, mezii, Spinx, ZywOo |
|           26 |     1035 | 2024-06-15 | Spirit       | L   | 0.864      | -            | -                | -                | -         |   -11.62 | apEX, flameZ, mezii, Spinx, ZywOo |
|           25 |     1075 | 2024-06-14 | FaZe         | W   | 0.857      | 0.729        | 0.635 (0.397)    | 0.401 (0.251)    | 1 (0.857) |     8.50 | apEX, flameZ, mezii, Spinx, ZywOo |
|           24 |     1108 | 2024-06-13 | G2           | W   | 0.851      | 0.729        | 1.000 (0.620)    | 0.498 (0.309)    | 1 (0.851) |    17.00 | apEX, flameZ, mezii, Spinx, ZywOo |
|           23 |     1139 | 2024-06-12 | Virtus.pro   | L   | 0.844      | -            | -                | -                | -         |   -20.12 | apEX, flameZ, mezii, Spinx, ZywOo |
|           22 |     1564 | 2024-06-02 | G2           | L   | 0.778      | -            | -                | -                | -         |    -9.52 | apEX, flameZ, mezii, Spinx, ZywOo |
|           21 |     1593 | 2024-06-01 | Spirit       | W   | 0.771      | 0.624        | 1.000 (0.481)    | -                | 1 (0.771) |    13.84 | apEX, flameZ, mezii, Spinx, ZywOo |
|           20 |     1628 | 2024-05-31 | HEROIC       | W   | 0.765      | -            | -                | -                | 1 (0.765) |     4.21 | apEX, flameZ, mezii, Spinx, ZywOo |
|           19 |     1676 | 2024-05-29 | 9z           | L   | 0.752      | -            | -                | -                | -         |   -21.41 | apEX, flameZ, mezii, Spinx, ZywOo |
|           18 |     1720 | 2024-05-27 | G2           | W   | 0.739      | 0.624        | 1.000 (0.461)    | 0.498 (0.230)    | 1 (0.739) |    13.79 | apEX, flameZ, mezii, Spinx, ZywOo |
|           17 |     1730 | 2024-05-27 | Monte        | W   | 0.738      | 0.624        | -                | 0.619 (0.285)    | 1 (0.738) |     0.22 | apEX, flameZ, mezii, Spinx, ZywOo |
|           16 |     2200 | 2024-05-12 | MOUZ         | L   | 0.637      | -            | -                | -                | -         |    -9.77 | apEX, flameZ, mezii, Spinx, ZywOo |
|           15 |     2232 | 2024-05-11 | Astralis     | W   | 0.630      | 0.889        | 0.390 (0.219)    | 0.421 (0.236)    | -         |     6.86 | apEX, flameZ, mezii, Spinx, ZywOo |
|           14 |     2249 | 2024-05-10 | FaZe         | W   | 0.625      | 0.889        | 0.635 (0.353)    | -                | -         |     6.65 | apEX, flameZ, mezii, Spinx, ZywOo |
|           13 |     2501 | 2024-04-28 | The MongolZ  | W   | 0.543      | 0.889        | 1.000 (0.483)    | 0.721 (0.348)    | -         |    10.09 | apEX, flameZ, mezii, Spinx, ZywOo |
|           12 |     2574 | 2024-04-25 | BetBoom      | W   | 0.524      | 0.889        | -                | 0.540 (0.251)    | -         |     1.25 | apEX, flameZ, mezii, Spinx, ZywOo |
|           11 |     2611 | 2024-04-23 | Sharks       | W   | 0.510      | -            | -                | -                | -         |     0.04 | apEX, flameZ, mezii, Spinx, ZywOo |
|           10 |     3275 | 2024-03-30 | FaZe         | L   | 0.351      | -            | -                | -                | -         |    -7.82 | apEX, flameZ, mezii, Spinx, ZywOo |
|            9 |     3302 | 2024-03-28 | Cloud9       | W   | 0.338      | -            | -                | -                | -         |     0.13 | apEX, flameZ, mezii, Spinx, ZywOo |
|            8 |     3389 | 2024-03-23 | Complexity   | W   | 0.304      | -            | -                | -                | -         |     2.35 | apEX, flameZ, mezii, Spinx, ZywOo |
|            7 |     3406 | 2024-03-22 | Imperial     | W   | 0.297      | -            | -                | -                | -         |     0.35 | apEX, flameZ, mezii, Spinx, ZywOo |
|            6 |     3425 | 2024-03-21 | The MongolZ  | W   | 0.291      | 1.000        | 1.000 (0.291)    | -                | -         |     5.67 | apEX, flameZ, mezii, Spinx, ZywOo |
|            5 |     3432 | 2024-03-21 | Eternal Fire | L   | 0.290      | -            | -                | -                | -         |    -6.40 | apEX, flameZ, mezii, Spinx, ZywOo |
|            4 |     4088 | 2024-02-21 | ENCE         | W   | 0.097      | -            | -                | -                | -         |     0.33 | apEX, flameZ, mezii, Spinx, ZywOo |
|            3 |     4118 | 2024-02-20 | Cloud9       | L   | 0.090      | -            | -                | -                | -         |    -2.81 | apEX, flameZ, mezii, Spinx, ZywOo |
|            2 |     4135 | 2024-02-19 | HEROIC       | W   | 0.085      | -            | -                | -                | -         |     0.44 | apEX, flameZ, mezii, Spinx, ZywOo |
|            1 |     4151 | 2024-02-19 | GamerLegion  | W   | 0.083      | -            | -                | -                | -         |     0.01 | apEX, flameZ, mezii, Spinx, ZywOo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($209,611.67)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.65) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.870 | $40,000.00     | $34,811.11      |
| 2024-06-02 |      0.778 | $42,000.00     | $32,678.33      |
| 2024-05-12 |      0.637 | $80,000.00     | $50,977.78      |
| 2024-03-31 |      0.358 | $80,000.00     | $28,644.44      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
