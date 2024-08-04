### Roster Details<br />
Team Name: Vitality<br />
Roster: apEX, flameZ, mezii, Spinx, ZywOo<br />
Global Rank: [5](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [5]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1855.1<br />
<br />
Final Rank Value (1855.1) = Starting Rank Value (1853.9) + Head To Head Adjustments (1.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.842[<sup>1</sup>](#table2)
- Bounty Collected: 0.703[<sup>2</sup>](#table1)
- Opponent Network: 0.299[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.711<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1853.9
- 400 + ( ( 0.711 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1853.9


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
|           31 |       42 | 2024-08-03 | Astralis     | W   | 1.000      | 0.581        | 0.391 (0.227)    | 0.421 (0.245)    | 1 (1.000) |     9.49 | apEX, flameZ, mezii, Spinx, ZywOo |
|           30 |      206 | 2024-07-30 | Astralis     | W   | 1.000      | 0.581        | 0.391 (0.227)    | 0.421 (0.245)    | 1 (1.000) |    10.00 | apEX, flameZ, mezii, Spinx, ZywOo |
|           29 |      239 | 2024-07-29 | GamerLegion  | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.67 | apEX, flameZ, mezii, Spinx, ZywOo |
|           28 |      566 | 2024-07-19 | Virtus.pro   | L   | 1.000      | -            | -                | -                | -         |   -22.16 | apEX, flameZ, mezii, Spinx, ZywOo |
|           27 |      682 | 2024-07-17 | M80          | W   | 1.000      | 1.000        | -                | 0.587 (0.587)    | 1 (1.000) |     0.97 | apEX, flameZ, mezii, Spinx, ZywOo |
|           26 |     1030 | 2024-06-15 | Spirit       | L   | 0.867      | -            | -                | -                | -         |   -11.65 | apEX, flameZ, mezii, Spinx, ZywOo |
|           25 |     1070 | 2024-06-14 | FaZe         | W   | 0.860      | 0.729        | 0.638 (0.400)    | 0.402 (0.252)    | 1 (0.860) |     8.57 | apEX, flameZ, mezii, Spinx, ZywOo |
|           24 |     1103 | 2024-06-13 | G2           | W   | 0.854      | 0.729        | 1.000 (0.622)    | 0.498 (0.310)    | 1 (0.854) |    17.04 | apEX, flameZ, mezii, Spinx, ZywOo |
|           23 |     1134 | 2024-06-12 | Virtus.pro   | L   | 0.847      | -            | -                | -                | -         |   -20.18 | apEX, flameZ, mezii, Spinx, ZywOo |
|           22 |     1559 | 2024-06-02 | G2           | L   | 0.781      | -            | -                | -                | -         |    -9.57 | apEX, flameZ, mezii, Spinx, ZywOo |
|           21 |     1588 | 2024-06-01 | Spirit       | W   | 0.774      | 0.624        | 1.000 (0.483)    | -                | 1 (0.774) |    13.88 | apEX, flameZ, mezii, Spinx, ZywOo |
|           20 |     1623 | 2024-05-31 | HEROIC       | W   | 0.767      | -            | -                | -                | 1 (0.767) |     4.23 | apEX, flameZ, mezii, Spinx, ZywOo |
|           19 |     1671 | 2024-05-29 | 9z           | L   | 0.755      | -            | -                | -                | -         |   -21.49 | apEX, flameZ, mezii, Spinx, ZywOo |
|           18 |     1715 | 2024-05-27 | G2           | W   | 0.742      | 0.624        | 1.000 (0.463)    | 0.498 (0.231)    | 1 (0.742) |    13.81 | apEX, flameZ, mezii, Spinx, ZywOo |
|           17 |     1725 | 2024-05-27 | Monte        | W   | 0.741      | 0.624        | -                | 0.619 (0.286)    | 1 (0.741) |     0.22 | apEX, flameZ, mezii, Spinx, ZywOo |
|           16 |     2195 | 2024-05-12 | MOUZ         | L   | 0.640      | -            | -                | -                | -         |    -9.80 | apEX, flameZ, mezii, Spinx, ZywOo |
|           15 |     2227 | 2024-05-11 | Astralis     | W   | 0.633      | 0.889        | 0.391 (0.220)    | 0.421 (0.237)    | -         |     6.88 | apEX, flameZ, mezii, Spinx, ZywOo |
|           14 |     2244 | 2024-05-10 | FaZe         | W   | 0.627      | 0.889        | 0.638 (0.356)    | -                | -         |     6.72 | apEX, flameZ, mezii, Spinx, ZywOo |
|           13 |     2496 | 2024-04-28 | The MongolZ  | W   | 0.546      | 0.889        | 1.000 (0.485)    | 0.721 (0.350)    | -         |    10.09 | apEX, flameZ, mezii, Spinx, ZywOo |
|           12 |     2569 | 2024-04-25 | BetBoom      | W   | 0.526      | 0.889        | -                | 0.541 (0.253)    | -         |     1.26 | apEX, flameZ, mezii, Spinx, ZywOo |
|           11 |     2606 | 2024-04-23 | Sharks       | W   | 0.513      | -            | -                | -                | -         |     0.04 | apEX, flameZ, mezii, Spinx, ZywOo |
|           10 |     3270 | 2024-03-30 | FaZe         | L   | 0.354      | -            | -                | -                | -         |    -7.86 | apEX, flameZ, mezii, Spinx, ZywOo |
|            9 |     3297 | 2024-03-28 | Cloud9       | W   | 0.340      | -            | -                | -                | -         |     0.14 | apEX, flameZ, mezii, Spinx, ZywOo |
|            8 |     3384 | 2024-03-23 | Complexity   | W   | 0.307      | -            | -                | -                | -         |     2.37 | apEX, flameZ, mezii, Spinx, ZywOo |
|            7 |     3401 | 2024-03-22 | Imperial     | W   | 0.299      | -            | -                | -                | -         |     0.35 | apEX, flameZ, mezii, Spinx, ZywOo |
|            6 |     3420 | 2024-03-21 | The MongolZ  | W   | 0.294      | 1.000        | 1.000 (0.294)    | -                | -         |     5.70 | apEX, flameZ, mezii, Spinx, ZywOo |
|            5 |     3427 | 2024-03-21 | Eternal Fire | L   | 0.293      | -            | -                | -                | -         |    -6.45 | apEX, flameZ, mezii, Spinx, ZywOo |
|            4 |     4083 | 2024-02-21 | ENCE         | W   | 0.100      | -            | -                | -                | -         |     0.33 | apEX, flameZ, mezii, Spinx, ZywOo |
|            3 |     4113 | 2024-02-20 | Cloud9       | L   | 0.093      | -            | -                | -                | -         |    -2.89 | apEX, flameZ, mezii, Spinx, ZywOo |
|            2 |     4130 | 2024-02-19 | HEROIC       | W   | 0.088      | -            | -                | -                | -         |     0.46 | apEX, flameZ, mezii, Spinx, ZywOo |
|            1 |     4146 | 2024-02-19 | GamerLegion  | W   | 0.085      | -            | -                | -                | -         |     0.01 | apEX, flameZ, mezii, Spinx, ZywOo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($210,261.48)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.65) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.873 | $40,000.00     | $34,918.52      |
| 2024-06-02 |      0.781 | $42,000.00     | $32,791.11      |
| 2024-05-12 |      0.640 | $80,000.00     | $51,192.59      |
| 2024-03-31 |      0.361 | $80,000.00     | $28,859.26      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
