### Roster Details<br />
Team Name: Vitality<br />
Roster: apEX, flameZ, mezii, Spinx, ZywOo<br />
Global Rank: [5](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [5]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1854.4<br />
<br />
Final Rank Value (1854.4) = Starting Rank Value (1861.9) + Head To Head Adjustments (-7.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.844[<sup>1</sup>](#table2)
- Bounty Collected: 0.710[<sup>2</sup>](#table1)
- Opponent Network: 0.299[<sup>2</sup>](#table1)
- LAN Wins: 0.982[<sup>2</sup>](#table1)

The average of these factors is 0.709<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1861.9
- 400 + ( ( 0.709 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1861.9


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
|           32 |       58 | 2024-07-30 | Astralis     | W   | 1.000      | 0.581        | 0.394 (0.229)    | -                | 1 (1.000) |     9.14 | apEX, flameZ, mezii, Spinx, ZywOo |
|           31 |       91 | 2024-07-29 | GamerLegion  | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.68 | apEX, flameZ, mezii, Spinx, ZywOo |
|           30 |      418 | 2024-07-19 | Virtus.pro   | L   | 1.000      | -            | -                | -                | -         |   -21.77 | apEX, flameZ, mezii, Spinx, ZywOo |
|           29 |      534 | 2024-07-17 | M80          | W   | 1.000      | 1.000        | 0.189 (0.189)    | 0.551 (0.551)    | 1 (1.000) |     1.00 | apEX, flameZ, mezii, Spinx, ZywOo |
|           28 |      882 | 2024-06-15 | Spirit       | L   | 0.892      | -            | -                | -                | -         |   -11.77 | apEX, flameZ, mezii, Spinx, ZywOo |
|           27 |      922 | 2024-06-14 | FaZe         | W   | 0.885      | 0.729        | 0.663 (0.428)    | 0.410 (0.264)    | 1 (0.885) |     9.52 | apEX, flameZ, mezii, Spinx, ZywOo |
|           26 |      955 | 2024-06-13 | G2           | W   | 0.879      | 0.729        | 1.000 (0.641)    | 0.492 (0.315)    | 1 (0.879) |    17.26 | apEX, flameZ, mezii, Spinx, ZywOo |
|           25 |      986 | 2024-06-12 | Virtus.pro   | L   | 0.872      | -            | -                | -                | -         |   -20.35 | apEX, flameZ, mezii, Spinx, ZywOo |
|           24 |     1411 | 2024-06-02 | G2           | L   | 0.806      | -            | -                | -                | -         |   -10.14 | apEX, flameZ, mezii, Spinx, ZywOo |
|           23 |     1440 | 2024-06-01 | Spirit       | W   | 0.799      | 0.624        | 1.000 (0.499)    | -                | 1 (0.799) |    14.55 | apEX, flameZ, mezii, Spinx, ZywOo |
|           22 |     1475 | 2024-05-31 | HEROIC       | W   | 0.793      | -            | -                | -                | 1 (0.793) |     4.62 | apEX, flameZ, mezii, Spinx, ZywOo |
|           21 |     1523 | 2024-05-29 | 9z           | L   | 0.780      | -            | -                | -                | -         |   -22.16 | apEX, flameZ, mezii, Spinx, ZywOo |
|           20 |     1567 | 2024-05-27 | G2           | W   | 0.767      | 0.624        | 1.000 (0.479)    | 0.492 (0.236)    | 1 (0.767) |    13.96 | apEX, flameZ, mezii, Spinx, ZywOo |
|           19 |     1577 | 2024-05-27 | Monte        | W   | 0.766      | 0.624        | -                | 0.613 (0.293)    | 1 (0.766) |     0.23 | apEX, flameZ, mezii, Spinx, ZywOo |
|           18 |     2047 | 2024-05-12 | MOUZ         | L   | 0.665      | -            | -                | -                | -         |    -9.61 | apEX, flameZ, mezii, Spinx, ZywOo |
|           17 |     2079 | 2024-05-11 | Astralis     | W   | 0.658      | 0.889        | 0.394 (0.231)    | 0.386 (0.226)    | 1 (0.658) |     6.43 | apEX, flameZ, mezii, Spinx, ZywOo |
|           16 |     2096 | 2024-05-10 | FaZe         | W   | 0.653      | 0.889        | 0.663 (0.384)    | 0.410 (0.238)    | -         |     7.64 | apEX, flameZ, mezii, Spinx, ZywOo |
|           15 |     2348 | 2024-04-28 | The MongolZ  | W   | 0.571      | 0.889        | 1.000 (0.507)    | 0.719 (0.365)    | -         |    10.56 | apEX, flameZ, mezii, Spinx, ZywOo |
|           14 |     2421 | 2024-04-25 | BetBoom      | W   | 0.552      | 0.889        | -                | 0.554 (0.271)    | -         |     1.39 | apEX, flameZ, mezii, Spinx, ZywOo |
|           13 |     2458 | 2024-04-23 | Sharks       | W   | 0.538      | -            | -                | -                | -         |     0.04 | apEX, flameZ, mezii, Spinx, ZywOo |
|           12 |     3122 | 2024-03-30 | FaZe         | L   | 0.379      | -            | -                | -                | -         |    -7.96 | apEX, flameZ, mezii, Spinx, ZywOo |
|           11 |     3149 | 2024-03-28 | Cloud9       | W   | 0.365      | -            | -                | -                | -         |     0.16 | apEX, flameZ, mezii, Spinx, ZywOo |
|           10 |     3236 | 2024-03-23 | Complexity   | W   | 0.332      | -            | -                | -                | -         |     2.49 | apEX, flameZ, mezii, Spinx, ZywOo |
|            9 |     3253 | 2024-03-22 | Imperial     | W   | 0.325      | -            | -                | -                | -         |     0.43 | apEX, flameZ, mezii, Spinx, ZywOo |
|            8 |     3272 | 2024-03-21 | The MongolZ  | W   | 0.319      | 1.000        | 1.000 (0.319)    | 0.719 (0.229)    | -         |     6.23 | apEX, flameZ, mezii, Spinx, ZywOo |
|            7 |     3279 | 2024-03-21 | Eternal Fire | L   | 0.318      | -            | -                | -                | -         |    -6.76 | apEX, flameZ, mezii, Spinx, ZywOo |
|            6 |     3935 | 2024-02-21 | ENCE         | W   | 0.125      | -            | -                | -                | -         |     0.44 | apEX, flameZ, mezii, Spinx, ZywOo |
|            5 |     3965 | 2024-02-20 | Cloud9       | L   | 0.118      | -            | -                | -                | -         |    -3.68 | apEX, flameZ, mezii, Spinx, ZywOo |
|            4 |     3982 | 2024-02-19 | HEROIC       | W   | 0.113      | -            | -                | -                | -         |     0.65 | apEX, flameZ, mezii, Spinx, ZywOo |
|            3 |     3998 | 2024-02-19 | GamerLegion  | W   | 0.111      | -            | -                | -                | -         |     0.01 | apEX, flameZ, mezii, Spinx, ZywOo |
|            2 |     4249 | 2024-02-05 | HEROIC       | L   | 0.018      | -            | -                | -                | -         |    -0.46 | apEX, flameZ, mezii, Spinx, ZywOo |
|            1 |     4282 | 2024-02-03 | ENCE         | L   | 0.007      | -            | -                | -                | -         |    -0.18 | apEX, flameZ, mezii, Spinx, ZywOo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($216,963.17)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.65) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-31 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.898 | $40,000.00     | $35,929.07      |
| 2024-06-02 |      0.806 | $42,000.00     | $33,852.19      |
| 2024-05-12 |      0.665 | $80,000.00     | $53,213.70      |
| 2024-03-31 |      0.386 | $80,000.00     | $30,880.37      |
| 2024-02-11 |      0.059 | $10,000.00     | $587.82         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
