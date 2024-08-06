### Roster Details<br />
Team Name: Falcons<br />
Roster: dupreeh, Maden, Magisk, Snappi, SunPayus<br />
Global Rank: [18](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [14]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1428.9<br />
<br />
Final Rank Value (1428.9) = Starting Rank Value (1416.9) + Head To Head Adjustments (12.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.603[<sup>1</sup>](#table2)
- Bounty Collected: 0.505[<sup>2</sup>](#table1)
- Opponent Network: 0.158[<sup>2</sup>](#table1)
- LAN Wins: 0.712[<sup>2</sup>](#table1)

The average of these factors is 0.494<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1416.9
- 400 + ( ( 0.494 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1416.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |      121 | 2024-08-02 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -5.73 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           25 |      241 | 2024-07-30 | GamerLegion      | W   | 1.000      | 0.581        | 0.173 (0.100)    | 0.259 (0.151)    | 1 (1.000) |     5.32 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           24 |      274 | 2024-07-29 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -5.62 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           23 |     1040 | 2024-06-16 | Complexity       | L   | 0.860      | -            | -                | -                | -         |    -7.45 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           22 |     1045 | 2024-06-16 | ENCE             | W   | 0.860      | 0.500        | 0.173 (0.074)    | 0.422 (0.181)    | 1 (0.860) |    11.36 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           21 |     1074 | 2024-06-15 | The MongolZ      | W   | 0.854      | 0.500        | 1.000 (0.427)    | 0.694 (0.296)    | 1 (0.854) |    24.89 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           20 |     1084 | 2024-06-15 | Party Astronauts | W   | 0.852      | 0.500        | 0.041 (0.017)    | 0.510 (0.217)    | 1 (0.852) |     2.16 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           19 |     1125 | 2024-06-14 | Aurora           | L   | 0.846      | -            | -                | -                | -         |   -13.20 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           18 |     1733 | 2024-05-28 | Liquid           | L   | 0.736      | -            | -                | -                | -         |    -6.24 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           17 |     1754 | 2024-05-27 | Monte            | W   | 0.729      | 0.624        | 0.080 (0.036)    | 0.598 (0.272)    | 1 (0.729) |     2.28 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           16 |     1766 | 2024-05-27 | G2               | L   | 0.728      | -            | -                | -                | -         |    -1.21 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           15 |     2016 | 2024-05-18 | Spirit           | L   | 0.667      | -            | -                | -                | -         |    -1.30 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           14 |     2048 | 2024-05-17 | Virtus.pro       | W   | 0.660      | 0.769        | 0.498 (0.253)    | 0.309 (0.157)    | 1 (0.660) |    16.88 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           13 |     2127 | 2024-05-15 | BetBoom          | W   | 0.648      | 0.769        | 0.248 (0.123)    | 0.514 (0.256)    | 1 (0.648) |     9.17 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           12 |     2186 | 2024-05-14 | Virtus.pro       | L   | 0.641      | -            | -                | -                | -         |    -3.46 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           11 |     2561 | 2024-04-27 | G2               | L   | 0.526      | -            | -                | -                | -         |    -0.75 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           10 |     2586 | 2024-04-26 | BetBoom          | L   | 0.520      | -            | -                | -                | -         |    -8.44 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            9 |     2612 | 2024-04-25 | TYLOO            | W   | 0.513      | 0.889        | 0.019 (0.009)    | 0.086 (0.039)    | 1 (0.513) |     0.43 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            8 |     2632 | 2024-04-24 | The MongolZ      | L   | 0.506      | -            | -                | -                | -         |    -0.93 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            7 |     3807 | 2024-03-06 | Metizport        | L   | 0.182      | -            | -                | -                | -         |    -5.42 | Maden, Magisk, s1mple, Snappi, SunPayus  |
|            6 |     4260 | 2024-02-16 | AMKAL            | L   | 0.053      | -            | -                | -                | -         |    -1.37 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            5 |     4286 | 2024-02-15 | Eternal Fire     | L   | 0.046      | -            | -                | -                | -         |    -0.25 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            4 |     4315 | 2024-02-14 | FaZe             | L   | 0.041      | -            | -                | -                | -         |    -0.25 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            3 |     4320 | 2024-02-14 | 3DMAX            | W   | 0.041      | 0.143        | 0.510 (0.003)    | 1.000 (0.006)    | 1 (0.041) |     1.05 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            2 |     4376 | 2024-02-10 | Spirit           | L   | 0.015      | -            | -                | -                | -         |    -0.03 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            1 |     4389 | 2024-02-09 | ENCE             | W   | 0.008      | 1.000        | 0.173 (0.001)    | 0.422 (0.004)    | 1 (0.008) |     0.15 | BOROS, Maden, Magisk, Snappi, SunPayus   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($70,342.66)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-06-16 |      0.860 | $20,000.00     | $17,209.26      |
| 2024-06-02 |      0.768 | $5,000.00      | $3,841.20       |
| 2024-05-19 |      0.674 | $50,000.00     | $33,675.93      |
| 2024-05-12 |      0.627 | $7,000.00      | $4,391.85       |
| 2024-03-10 |      0.209 | $5,000.00      | $1,042.94       |
| 2024-02-11 |      0.021 | $80,000.00     | $1,681.48       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
