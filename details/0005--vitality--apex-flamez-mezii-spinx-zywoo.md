### Roster Details<br />
Team Name: Vitality<br />
Roster: apEX, flameZ, mezii, Spinx, ZywOo<br />
Global Rank: [5](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [5]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1849.2<br />
<br />
Final Rank Value (1849.2) = Starting Rank Value (1850.0) + Head To Head Adjustments (-0.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.842[<sup>1</sup>](#table2)
- Bounty Collected: 0.701[<sup>2</sup>](#table1)
- Opponent Network: 0.295[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.710<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1850.0
- 400 + ( ( 0.710 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1850.0


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
|           31 |       10 | 2024-08-03 | Astralis     | W   | 1.000      | 0.581        | 0.353 (0.205)    | 0.382 (0.222)    | 1 (1.000) |     8.65 | apEX, flameZ, mezii, Spinx, ZywOo |
|           30 |      172 | 2024-07-30 | Astralis     | W   | 1.000      | 0.581        | 0.353 (0.205)    | -                | 1 (1.000) |     9.04 | apEX, flameZ, mezii, Spinx, ZywOo |
|           29 |      205 | 2024-07-29 | GamerLegion  | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.69 | apEX, flameZ, mezii, Spinx, ZywOo |
|           28 |      532 | 2024-07-19 | Virtus.pro   | L   | 1.000      | -            | -                | -                | -         |   -22.16 | apEX, flameZ, mezii, Spinx, ZywOo |
|           27 |      648 | 2024-07-17 | M80          | W   | 1.000      | 1.000        | -                | 0.587 (0.587)    | 1 (1.000) |     1.01 | apEX, flameZ, mezii, Spinx, ZywOo |
|           26 |      995 | 2024-06-15 | Spirit       | L   | 0.871      | -            | -                | -                | -         |   -11.62 | apEX, flameZ, mezii, Spinx, ZywOo |
|           25 |     1035 | 2024-06-14 | FaZe         | W   | 0.864      | 0.729        | 0.643 (0.405)    | 0.403 (0.254)    | 1 (0.864) |     8.65 | apEX, flameZ, mezii, Spinx, ZywOo |
|           24 |     1068 | 2024-06-13 | G2           | W   | 0.858      | 0.729        | 1.000 (0.626)    | 0.498 (0.312)    | 1 (0.858) |    17.19 | apEX, flameZ, mezii, Spinx, ZywOo |
|           23 |     1099 | 2024-06-12 | Virtus.pro   | L   | 0.851      | -            | -                | -                | -         |   -20.24 | apEX, flameZ, mezii, Spinx, ZywOo |
|           22 |     1524 | 2024-06-02 | G2           | L   | 0.785      | -            | -                | -                | -         |    -9.56 | apEX, flameZ, mezii, Spinx, ZywOo |
|           21 |     1553 | 2024-06-01 | Spirit       | W   | 0.779      | 0.624        | 1.000 (0.486)    | 0.461 (0.224)    | 1 (0.779) |    14.06 | apEX, flameZ, mezii, Spinx, ZywOo |
|           20 |     1588 | 2024-05-31 | HEROIC       | W   | 0.772      | -            | -                | -                | 1 (0.772) |     4.30 | apEX, flameZ, mezii, Spinx, ZywOo |
|           19 |     1636 | 2024-05-29 | 9z           | L   | 0.759      | -            | -                | -                | -         |   -21.60 | apEX, flameZ, mezii, Spinx, ZywOo |
|           18 |     1680 | 2024-05-27 | G2           | W   | 0.746      | 0.624        | 1.000 (0.466)    | 0.498 (0.232)    | 1 (0.746) |    13.99 | apEX, flameZ, mezii, Spinx, ZywOo |
|           17 |     1690 | 2024-05-27 | Monte        | W   | 0.745      | 0.624        | -                | 0.618 (0.287)    | 1 (0.745) |     0.23 | apEX, flameZ, mezii, Spinx, ZywOo |
|           16 |     2160 | 2024-05-12 | MOUZ         | L   | 0.644      | -            | -                | -                | -         |    -9.80 | apEX, flameZ, mezii, Spinx, ZywOo |
|           15 |     2192 | 2024-05-11 | Astralis     | W   | 0.638      | 0.889        | 0.353 (0.200)    | -                | -         |     6.05 | apEX, flameZ, mezii, Spinx, ZywOo |
|           14 |     2209 | 2024-05-10 | FaZe         | W   | 0.632      | 0.889        | 0.643 (0.361)    | 0.403 (0.227)    | -         |     6.79 | apEX, flameZ, mezii, Spinx, ZywOo |
|           13 |     2461 | 2024-04-28 | The MongolZ  | W   | 0.550      | 0.889        | 1.000 (0.489)    | 0.720 (0.352)    | -         |    10.20 | apEX, flameZ, mezii, Spinx, ZywOo |
|           12 |     2533 | 2024-04-25 | BetBoom      | W   | 0.531      | 0.889        | -                | 0.543 (0.256)    | -         |     1.30 | apEX, flameZ, mezii, Spinx, ZywOo |
|           11 |     2570 | 2024-04-23 | Sharks       | W   | 0.518      | -            | -                | -                | -         |     0.04 | apEX, flameZ, mezii, Spinx, ZywOo |
|           10 |     3234 | 2024-03-30 | FaZe         | L   | 0.358      | -            | -                | -                | -         |    -7.90 | apEX, flameZ, mezii, Spinx, ZywOo |
|            9 |     3261 | 2024-03-28 | Cloud9       | W   | 0.345      | -            | -                | -                | -         |     0.14 | apEX, flameZ, mezii, Spinx, ZywOo |
|            8 |     3348 | 2024-03-23 | Complexity   | W   | 0.311      | -            | -                | -                | -         |     2.35 | apEX, flameZ, mezii, Spinx, ZywOo |
|            7 |     3365 | 2024-03-22 | Imperial     | W   | 0.304      | -            | -                | -                | -         |     0.37 | apEX, flameZ, mezii, Spinx, ZywOo |
|            6 |     3384 | 2024-03-21 | The MongolZ  | W   | 0.298      | 1.000        | 1.000 (0.298)    | -                | -         |     5.81 | apEX, flameZ, mezii, Spinx, ZywOo |
|            5 |     3391 | 2024-03-21 | Eternal Fire | L   | 0.297      | -            | -                | -                | -         |    -6.51 | apEX, flameZ, mezii, Spinx, ZywOo |
|            4 |     4046 | 2024-02-21 | ENCE         | W   | 0.104      | -            | -                | -                | -         |     0.35 | apEX, flameZ, mezii, Spinx, ZywOo |
|            3 |     4076 | 2024-02-20 | Cloud9       | L   | 0.097      | -            | -                | -                | -         |    -3.03 | apEX, flameZ, mezii, Spinx, ZywOo |
|            2 |     4093 | 2024-02-19 | HEROIC       | W   | 0.092      | -            | -                | -                | -         |     0.49 | apEX, flameZ, mezii, Spinx, ZywOo |
|            1 |     4109 | 2024-02-19 | GamerLegion  | W   | 0.090      | -            | -                | -                | -         |     0.01 | apEX, flameZ, mezii, Spinx, ZywOo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($211,359.44)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.65) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.877 | $40,000.00     | $35,100.00      |
| 2024-06-02 |      0.785 | $42,000.00     | $32,981.67      |
| 2024-05-12 |      0.644 | $80,000.00     | $51,555.56      |
| 2024-03-31 |      0.365 | $80,000.00     | $29,222.22      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
