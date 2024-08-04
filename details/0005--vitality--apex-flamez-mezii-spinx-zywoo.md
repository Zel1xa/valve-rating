### Roster Details<br />
Team Name: Vitality<br />
Roster: apEX, flameZ, mezii, Spinx, ZywOo<br />
Global Rank: [5](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [5]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1854.8<br />
<br />
Final Rank Value (1854.8) = Starting Rank Value (1854.1) + Head To Head Adjustments (0.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.842[<sup>1</sup>](#table2)
- Bounty Collected: 0.703[<sup>2</sup>](#table1)
- Opponent Network: 0.300[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.711<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1854.1
- 400 + ( ( 0.711 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1854.1


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
|           31 |       21 | 2024-08-03 | Astralis     | W   | 1.000      | 0.581        | 0.391 (0.227)    | 0.421 (0.245)    | 1 (1.000) |     9.49 | apEX, flameZ, mezii, Spinx, ZywOo |
|           30 |      183 | 2024-07-30 | Astralis     | W   | 1.000      | 0.581        | 0.391 (0.227)    | 0.421 (0.245)    | 1 (1.000) |    10.01 | apEX, flameZ, mezii, Spinx, ZywOo |
|           29 |      216 | 2024-07-29 | GamerLegion  | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.67 | apEX, flameZ, mezii, Spinx, ZywOo |
|           28 |      543 | 2024-07-19 | Virtus.pro   | L   | 1.000      | -            | -                | -                | -         |   -22.20 | apEX, flameZ, mezii, Spinx, ZywOo |
|           27 |      659 | 2024-07-17 | M80          | W   | 1.000      | 1.000        | -                | 0.587 (0.587)    | 1 (1.000) |     0.99 | apEX, flameZ, mezii, Spinx, ZywOo |
|           26 |     1007 | 2024-06-15 | Spirit       | L   | 0.867      | -            | -                | -                | -         |   -11.71 | apEX, flameZ, mezii, Spinx, ZywOo |
|           25 |     1047 | 2024-06-14 | FaZe         | W   | 0.861      | 0.729        | 0.639 (0.401)    | 0.402 (0.252)    | 1 (0.861) |     8.54 | apEX, flameZ, mezii, Spinx, ZywOo |
|           24 |     1080 | 2024-06-13 | G2           | W   | 0.854      | 0.729        | 1.000 (0.623)    | 0.498 (0.310)    | 1 (0.854) |    17.05 | apEX, flameZ, mezii, Spinx, ZywOo |
|           23 |     1111 | 2024-06-12 | Virtus.pro   | L   | 0.848      | -            | -                | -                | -         |   -20.22 | apEX, flameZ, mezii, Spinx, ZywOo |
|           22 |     1536 | 2024-06-02 | G2           | L   | 0.782      | -            | -                | -                | -         |    -9.59 | apEX, flameZ, mezii, Spinx, ZywOo |
|           21 |     1565 | 2024-06-01 | Spirit       | W   | 0.775      | 0.624        | 1.000 (0.484)    | -                | 1 (0.775) |    13.85 | apEX, flameZ, mezii, Spinx, ZywOo |
|           20 |     1600 | 2024-05-31 | HEROIC       | W   | 0.768      | -            | -                | -                | 1 (0.768) |     4.21 | apEX, flameZ, mezii, Spinx, ZywOo |
|           19 |     1648 | 2024-05-29 | 9z           | L   | 0.755      | -            | -                | -                | -         |   -21.51 | apEX, flameZ, mezii, Spinx, ZywOo |
|           18 |     1692 | 2024-05-27 | G2           | W   | 0.743      | 0.624        | 1.000 (0.464)    | 0.498 (0.231)    | 1 (0.743) |    13.82 | apEX, flameZ, mezii, Spinx, ZywOo |
|           17 |     1702 | 2024-05-27 | Monte        | W   | 0.741      | 0.624        | -                | 0.619 (0.286)    | 1 (0.741) |     0.22 | apEX, flameZ, mezii, Spinx, ZywOo |
|           16 |     2172 | 2024-05-12 | MOUZ         | L   | 0.641      | -            | -                | -                | -         |    -9.83 | apEX, flameZ, mezii, Spinx, ZywOo |
|           15 |     2204 | 2024-05-11 | Astralis     | W   | 0.634      | 0.889        | 0.391 (0.220)    | 0.421 (0.237)    | -         |     6.89 | apEX, flameZ, mezii, Spinx, ZywOo |
|           14 |     2221 | 2024-05-10 | FaZe         | W   | 0.628      | 0.889        | 0.639 (0.357)    | -                | -         |     6.70 | apEX, flameZ, mezii, Spinx, ZywOo |
|           13 |     2473 | 2024-04-28 | The MongolZ  | W   | 0.546      | 0.889        | 1.000 (0.486)    | 0.721 (0.350)    | -         |    10.10 | apEX, flameZ, mezii, Spinx, ZywOo |
|           12 |     2546 | 2024-04-25 | BetBoom      | W   | 0.527      | 0.889        | -                | 0.541 (0.254)    | -         |     1.26 | apEX, flameZ, mezii, Spinx, ZywOo |
|           11 |     2583 | 2024-04-23 | Sharks       | W   | 0.514      | -            | -                | -                | -         |     0.04 | apEX, flameZ, mezii, Spinx, ZywOo |
|           10 |     3247 | 2024-03-30 | FaZe         | L   | 0.354      | -            | -                | -                | -         |    -7.89 | apEX, flameZ, mezii, Spinx, ZywOo |
|            9 |     3274 | 2024-03-28 | Cloud9       | W   | 0.341      | -            | -                | -                | -         |     0.13 | apEX, flameZ, mezii, Spinx, ZywOo |
|            8 |     3361 | 2024-03-23 | Complexity   | W   | 0.307      | -            | -                | -                | -         |     2.27 | apEX, flameZ, mezii, Spinx, ZywOo |
|            7 |     3378 | 2024-03-22 | Imperial     | W   | 0.300      | -            | -                | -                | -         |     0.36 | apEX, flameZ, mezii, Spinx, ZywOo |
|            6 |     3397 | 2024-03-21 | The MongolZ  | W   | 0.295      | 1.000        | 1.000 (0.295)    | -                | -         |     5.71 | apEX, flameZ, mezii, Spinx, ZywOo |
|            5 |     3404 | 2024-03-21 | Eternal Fire | L   | 0.294      | -            | -                | -                | -         |    -6.47 | apEX, flameZ, mezii, Spinx, ZywOo |
|            4 |     4060 | 2024-02-21 | ENCE         | W   | 0.101      | -            | -                | -                | -         |     0.33 | apEX, flameZ, mezii, Spinx, ZywOo |
|            3 |     4090 | 2024-02-20 | Cloud9       | L   | 0.094      | -            | -                | -                | -         |    -2.92 | apEX, flameZ, mezii, Spinx, ZywOo |
|            2 |     4107 | 2024-02-19 | HEROIC       | W   | 0.089      | -            | -                | -                | -         |     0.46 | apEX, flameZ, mezii, Spinx, ZywOo |
|            1 |     4123 | 2024-02-19 | GamerLegion  | W   | 0.086      | -            | -                | -                | -         |     0.01 | apEX, flameZ, mezii, Spinx, ZywOo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($210,446.34)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.65) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.874 | $40,000.00     | $34,949.07      |
| 2024-06-02 |      0.782 | $42,000.00     | $32,823.19      |
| 2024-05-12 |      0.641 | $80,000.00     | $51,253.70      |
| 2024-03-31 |      0.362 | $80,000.00     | $28,920.37      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
