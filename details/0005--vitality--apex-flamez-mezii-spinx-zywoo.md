### Roster Details<br />
Team Name: Vitality<br />
Roster: apEX, flameZ, mezii, Spinx, ZywOo<br />
Global Rank: [5](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [5]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1853.5<br />
<br />
Final Rank Value (1853.5) = Starting Rank Value (1852.1) + Head To Head Adjustments (1.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.841[<sup>1</sup>](#table2)
- Bounty Collected: 0.699[<sup>2</sup>](#table1)
- Opponent Network: 0.291[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.708<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1852.1
- 400 + ( ( 0.708 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1852.1


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
|           31 |       71 | 2024-08-03 | Astralis     | W   | 1.000      | 0.581        | 0.389 (0.226)    | 0.413 (0.240)    | 1 (1.000) |     9.51 | apEX, flameZ, mezii, Spinx, ZywOo |
|           30 |      235 | 2024-07-30 | Astralis     | W   | 1.000      | 0.581        | 0.389 (0.226)    | 0.413 (0.240)    | 1 (1.000) |    10.03 | apEX, flameZ, mezii, Spinx, ZywOo |
|           29 |      268 | 2024-07-29 | GamerLegion  | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.68 | apEX, flameZ, mezii, Spinx, ZywOo |
|           28 |      595 | 2024-07-19 | Virtus.pro   | L   | 1.000      | -            | -                | -                | -         |   -22.18 | apEX, flameZ, mezii, Spinx, ZywOo |
|           27 |      711 | 2024-07-17 | M80          | W   | 1.000      | 1.000        | -                | 0.576 (0.576)    | 1 (1.000) |     0.97 | apEX, flameZ, mezii, Spinx, ZywOo |
|           26 |     1059 | 2024-06-15 | Spirit       | L   | 0.857      | -            | -                | -                | -         |   -11.51 | apEX, flameZ, mezii, Spinx, ZywOo |
|           25 |     1099 | 2024-06-14 | FaZe         | W   | 0.851      | 0.729        | 0.629 (0.390)    | 0.393 (0.243)    | 1 (0.851) |     8.35 | apEX, flameZ, mezii, Spinx, ZywOo |
|           24 |     1132 | 2024-06-13 | G2           | W   | 0.844      | 0.729        | 1.000 (0.615)    | 0.489 (0.301)    | 1 (0.844) |    16.93 | apEX, flameZ, mezii, Spinx, ZywOo |
|           23 |     1163 | 2024-06-12 | Virtus.pro   | L   | 0.837      | -            | -                | -                | -         |   -19.98 | apEX, flameZ, mezii, Spinx, ZywOo |
|           22 |     1588 | 2024-06-02 | G2           | L   | 0.771      | -            | -                | -                | -         |    -9.38 | apEX, flameZ, mezii, Spinx, ZywOo |
|           21 |     1617 | 2024-06-01 | Spirit       | W   | 0.765      | 0.624        | 1.000 (0.477)    | -                | 1 (0.765) |    13.74 | apEX, flameZ, mezii, Spinx, ZywOo |
|           20 |     1652 | 2024-05-31 | HEROIC       | W   | 0.758      | -            | -                | -                | 1 (0.758) |     4.16 | apEX, flameZ, mezii, Spinx, ZywOo |
|           19 |     1700 | 2024-05-29 | 9z           | L   | 0.745      | -            | -                | -                | -         |   -21.22 | apEX, flameZ, mezii, Spinx, ZywOo |
|           18 |     1744 | 2024-05-27 | G2           | W   | 0.732      | 0.624        | 1.000 (0.457)    | 0.489 (0.224)    | 1 (0.732) |    13.74 | apEX, flameZ, mezii, Spinx, ZywOo |
|           17 |     1754 | 2024-05-27 | Monte        | W   | 0.731      | 0.624        | -                | 0.611 (0.279)    | 1 (0.731) |     0.22 | apEX, flameZ, mezii, Spinx, ZywOo |
|           16 |     2224 | 2024-05-12 | MOUZ         | L   | 0.631      | -            | -                | -                | -         |    -9.66 | apEX, flameZ, mezii, Spinx, ZywOo |
|           15 |     2256 | 2024-05-11 | Astralis     | W   | 0.624      | 0.889        | 0.389 (0.216)    | 0.413 (0.229)    | -         |     6.77 | apEX, flameZ, mezii, Spinx, ZywOo |
|           14 |     2273 | 2024-05-10 | FaZe         | W   | 0.618      | 0.889        | 0.629 (0.345)    | -                | -         |     6.50 | apEX, flameZ, mezii, Spinx, ZywOo |
|           13 |     2525 | 2024-04-28 | The MongolZ  | W   | 0.536      | 0.889        | 1.000 (0.477)    | 0.710 (0.338)    | -         |    10.01 | apEX, flameZ, mezii, Spinx, ZywOo |
|           12 |     2598 | 2024-04-25 | BetBoom      | W   | 0.517      | 0.889        | -                | 0.527 (0.242)    | -         |     1.23 | apEX, flameZ, mezii, Spinx, ZywOo |
|           11 |     2635 | 2024-04-23 | Sharks       | W   | 0.504      | -            | -                | -                | -         |     0.04 | apEX, flameZ, mezii, Spinx, ZywOo |
|           10 |     3299 | 2024-03-30 | FaZe         | L   | 0.344      | -            | -                | -                | -         |    -7.71 | apEX, flameZ, mezii, Spinx, ZywOo |
|            9 |     3326 | 2024-03-28 | Cloud9       | W   | 0.331      | -            | -                | -                | -         |     0.13 | apEX, flameZ, mezii, Spinx, ZywOo |
|            8 |     3413 | 2024-03-23 | Complexity   | W   | 0.297      | -            | -                | -                | -         |     2.29 | apEX, flameZ, mezii, Spinx, ZywOo |
|            7 |     3430 | 2024-03-22 | Imperial     | W   | 0.290      | -            | -                | -                | -         |     0.34 | apEX, flameZ, mezii, Spinx, ZywOo |
|            6 |     3449 | 2024-03-21 | The MongolZ  | W   | 0.285      | 1.000        | 1.000 (0.285)    | -                | -         |     5.56 | apEX, flameZ, mezii, Spinx, ZywOo |
|            5 |     3456 | 2024-03-21 | Eternal Fire | L   | 0.283      | -            | -                | -                | -         |    -6.25 | apEX, flameZ, mezii, Spinx, ZywOo |
|            4 |     4112 | 2024-02-21 | ENCE         | W   | 0.090      | -            | -                | -                | -         |     0.31 | apEX, flameZ, mezii, Spinx, ZywOo |
|            3 |     4142 | 2024-02-20 | Cloud9       | L   | 0.083      | -            | -                | -                | -         |    -2.60 | apEX, flameZ, mezii, Spinx, ZywOo |
|            2 |     4159 | 2024-02-19 | HEROIC       | W   | 0.079      | -            | -                | -                | -         |     0.41 | apEX, flameZ, mezii, Spinx, ZywOo |
|            1 |     4175 | 2024-02-19 | GamerLegion  | W   | 0.076      | -            | -                | -                | -         |     0.01 | apEX, flameZ, mezii, Spinx, ZywOo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($207,998.33)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.65) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.864 | $40,000.00     | $34,544.44      |
| 2024-06-02 |      0.771 | $42,000.00     | $32,398.33      |
| 2024-05-12 |      0.631 | $80,000.00     | $50,444.44      |
| 2024-03-31 |      0.351 | $80,000.00     | $28,111.11      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
