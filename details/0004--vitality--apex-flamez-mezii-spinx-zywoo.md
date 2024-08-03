### Roster Details<br />
Team Name: Vitality<br />
Roster: apEX, flameZ, mezii, Spinx, ZywOo<br />
Global Rank: [4](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [4]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1852.1<br />
<br />
Final Rank Value (1852.1) = Starting Rank Value (1857.7) + Head To Head Adjustments (-5.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.842[<sup>1</sup>](#table2)
- Bounty Collected: 0.701[<sup>2</sup>](#table1)
- Opponent Network: 0.306[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.712<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1857.7
- 400 + ( ( 0.712 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1857.7


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
|           31 |        8 | 2024-08-03 | Astralis     | W   | 1.000      | 0.581        | 0.353 (0.205)    | 0.396 (0.230)    | 1 (1.000) |     8.68 | apEX, flameZ, mezii, Spinx, ZywOo |
|           30 |      149 | 2024-07-30 | Astralis     | W   | 1.000      | 0.581        | 0.353 (0.205)    | -                | 1 (1.000) |     9.08 | apEX, flameZ, mezii, Spinx, ZywOo |
|           29 |      182 | 2024-07-29 | GamerLegion  | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.67 | apEX, flameZ, mezii, Spinx, ZywOo |
|           28 |      509 | 2024-07-19 | Virtus.pro   | L   | 1.000      | -            | -                | -                | -         |   -22.35 | apEX, flameZ, mezii, Spinx, ZywOo |
|           27 |      624 | 2024-07-17 | M80          | W   | 1.000      | 1.000        | -                | 0.608 (0.608)    | 1 (1.000) |     0.99 | apEX, flameZ, mezii, Spinx, ZywOo |
|           26 |      956 | 2024-06-15 | Spirit       | L   | 0.873      | -            | -                | -                | -         |   -11.58 | apEX, flameZ, mezii, Spinx, ZywOo |
|           25 |      987 | 2024-06-14 | FaZe         | W   | 0.866      | 0.729        | 0.644 (0.407)    | 0.418 (0.264)    | 1 (0.866) |     8.72 | apEX, flameZ, mezii, Spinx, ZywOo |
|           24 |     1018 | 2024-06-13 | G2           | W   | 0.860      | 0.729        | 1.000 (0.627)    | 0.516 (0.323)    | 1 (0.860) |    16.94 | apEX, flameZ, mezii, Spinx, ZywOo |
|           23 |     1048 | 2024-06-12 | Virtus.pro   | L   | 0.853      | -            | -                | -                | -         |   -20.45 | apEX, flameZ, mezii, Spinx, ZywOo |
|           22 |     1463 | 2024-06-02 | G2           | L   | 0.787      | -            | -                | -                | -         |    -9.88 | apEX, flameZ, mezii, Spinx, ZywOo |
|           21 |     1491 | 2024-06-01 | Spirit       | W   | 0.780      | 0.624        | 1.000 (0.487)    | 0.477 (0.232)    | 1 (0.780) |    14.13 | apEX, flameZ, mezii, Spinx, ZywOo |
|           20 |     1525 | 2024-05-31 | HEROIC       | W   | 0.774      | -            | -                | -                | 1 (0.774) |     4.15 | apEX, flameZ, mezii, Spinx, ZywOo |
|           19 |     1573 | 2024-05-29 | 9z           | L   | 0.761      | -            | -                | -                | -         |   -23.29 | apEX, flameZ, mezii, Spinx, ZywOo |
|           18 |     1617 | 2024-05-27 | G2           | W   | 0.748      | 0.624        | 1.000 (0.467)    | 0.516 (0.241)    | 1 (0.748) |    13.74 | apEX, flameZ, mezii, Spinx, ZywOo |
|           17 |     1627 | 2024-05-27 | Monte        | W   | 0.747      | 0.624        | -                | 0.639 (0.298)    | 1 (0.747) |     0.21 | apEX, flameZ, mezii, Spinx, ZywOo |
|           16 |     2096 | 2024-05-12 | MOUZ         | L   | 0.646      | -            | -                | -                | -         |   -11.40 | apEX, flameZ, mezii, Spinx, ZywOo |
|           15 |     2127 | 2024-05-11 | Astralis     | W   | 0.639      | 0.889        | 0.353 (0.201)    | -                | -         |     6.04 | apEX, flameZ, mezii, Spinx, ZywOo |
|           14 |     2144 | 2024-05-10 | FaZe         | W   | 0.634      | 0.889        | 0.644 (0.363)    | 0.418 (0.235)    | -         |     6.75 | apEX, flameZ, mezii, Spinx, ZywOo |
|           13 |     2395 | 2024-04-28 | The MongolZ  | W   | 0.552      | 0.889        | 1.000 (0.491)    | 0.745 (0.365)    | -         |    10.14 | apEX, flameZ, mezii, Spinx, ZywOo |
|           12 |     2467 | 2024-04-25 | BetBoom      | W   | 0.533      | 0.889        | -                | 0.563 (0.267)    | -         |     1.24 | apEX, flameZ, mezii, Spinx, ZywOo |
|           11 |     2504 | 2024-04-23 | Sharks       | W   | 0.519      | -            | -                | -                | -         |     0.04 | apEX, flameZ, mezii, Spinx, ZywOo |
|           10 |     3168 | 2024-03-30 | FaZe         | L   | 0.360      | -            | -                | -                | -         |    -7.94 | apEX, flameZ, mezii, Spinx, ZywOo |
|            9 |     3195 | 2024-03-28 | Cloud9       | W   | 0.346      | -            | -                | -                | -         |     0.14 | apEX, flameZ, mezii, Spinx, ZywOo |
|            8 |     3278 | 2024-03-23 | Complexity   | W   | 0.313      | -            | -                | -                | -         |     2.34 | apEX, flameZ, mezii, Spinx, ZywOo |
|            7 |     3294 | 2024-03-22 | Imperial     | W   | 0.306      | -            | -                | -                | -         |     0.31 | apEX, flameZ, mezii, Spinx, ZywOo |
|            6 |     3313 | 2024-03-21 | The MongolZ  | W   | 0.300      | 1.000        | 1.000 (0.300)    | -                | -         |     5.79 | apEX, flameZ, mezii, Spinx, ZywOo |
|            5 |     3320 | 2024-03-21 | Eternal Fire | L   | 0.299      | -            | -                | -                | -         |    -6.60 | apEX, flameZ, mezii, Spinx, ZywOo |
|            4 |     3973 | 2024-02-21 | ENCE         | W   | 0.106      | -            | -                | -                | -         |     0.34 | apEX, flameZ, mezii, Spinx, ZywOo |
|            3 |     4003 | 2024-02-20 | Cloud9       | L   | 0.099      | -            | -                | -                | -         |    -3.09 | apEX, flameZ, mezii, Spinx, ZywOo |
|            2 |     4020 | 2024-02-19 | HEROIC       | W   | 0.094      | -            | -                | -                | -         |     0.49 | apEX, flameZ, mezii, Spinx, ZywOo |
|            1 |     4036 | 2024-02-19 | GamerLegion  | W   | 0.092      | -            | -                | -                | -         |     0.01 | apEX, flameZ, mezii, Spinx, ZywOo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($211,773.98)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.65) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.879 | $40,000.00     | $35,168.52      |
| 2024-06-02 |      0.787 | $42,000.00     | $33,053.61      |
| 2024-05-12 |      0.646 | $80,000.00     | $51,692.59      |
| 2024-03-31 |      0.367 | $80,000.00     | $29,359.26      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
