### Roster Details<br />
Team Name: Lynn Vision<br />
Roster: EmiliaQAQ, flying, Starry, Westmelon, z4kr<br />
Global Rank: [58](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [3]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1004.0<br />
<br />
Final Rank Value (1004.0) = Starting Rank Value (993.3) + Head To Head Adjustments (10.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.477[<sup>1</sup>](#table2)
- Bounty Collected: 0.311[<sup>2</sup>](#table1)
- Opponent Network: 0.049[<sup>2</sup>](#table1)
- LAN Wins: 0.317[<sup>2</sup>](#table1)

The average of these factors is 0.288<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 993.3
- 400 + ( ( 0.288 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 993.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           27 |     1142 | 2024-06-09 | ATOX              | W   | 0.844      | 0.416        | 0.021 (0.007)    | 0.183 (0.064)    | 0 (0.000) |     9.80 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           26 |     1202 | 2024-06-08 | TYLOO             | W   | 0.838      | 0.416        | 0.013 (0.004)    | 0.211 (0.074)    | 0 (0.000) |     5.09 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           25 |     1333 | 2024-06-06 | ATOX              | L   | 0.825      | -            | -                | -                | -         |   -16.62 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           24 |     1390 | 2024-06-05 | TYLOO             | W   | 0.818      | 0.416        | 0.013 (0.004)    | 0.211 (0.072)    | 0 (0.000) |     4.34 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           23 |     1513 | 2024-06-01 | Aurora            | L   | 0.792      | -            | -                | -                | -         |    -1.14 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           22 |     1523 | 2024-05-31 | ATOX              | W   | 0.789      | 0.500        | 0.021 (0.008)    | 0.183 (0.072)    | 1 (0.789) |     8.60 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           21 |     1575 | 2024-05-30 | Gaimin Gladiators | W   | 0.777      | 0.500        | 0.040 (0.015)    | 0.360 (0.140)    | 1 (0.777) |    12.79 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           20 |     1620 | 2024-05-28 | Aurora            | L   | 0.764      | -            | -                | -                | -         |    -0.98 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           19 |     2729 | 2024-04-18 | Rare Atom         | L   | 0.499      | -            | -                | -                | -         |   -13.77 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           18 |     2740 | 2024-04-18 | TYLOO             | L   | 0.498      | -            | -                | -                | -         |   -12.39 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           17 |     3000 | 2024-04-09 | G2                | L   | 0.438      | -            | -                | -                | -         |    -0.06 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           16 |     3028 | 2024-04-08 | TYLOO             | W   | 0.432      | 0.624        | 0.020 (0.005)    | 0.094 (0.025)    | 1 (0.432) |     2.77 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           15 |     3039 | 2024-04-07 | FURIA             | L   | 0.430      | -            | -                | -                | -         |    -0.26 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           14 |     3177 | 2024-04-03 | The MongolZ       | L   | 0.398      | -            | -                | -                | -         |    -0.08 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           13 |     3217 | 2024-04-02 | LYG               | W   | 0.392      | -            | -                | -                | -         |     2.14 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           12 |     3223 | 2024-04-02 | ATOX              | W   | 0.391      | 0.143        | 0.021 (0.001)    | 0.183 (0.010)    | -         |     4.05 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           11 |     3443 | 2024-03-19 | The MongolZ       | L   | 0.298      | -            | -                | -                | -         |    -0.05 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           10 |     3452 | 2024-03-18 | Gaimin Gladiators | L   | 0.292      | -            | -                | -                | -         |    -4.65 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            9 |     3459 | 2024-03-17 | FURIA             | W   | 0.288      | 0.143        | 0.286 (0.012)    | 0.494 (0.020)    | 1 (0.288) |     8.91 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            8 |     3478 | 2024-03-17 | HEROIC            | L   | 0.286      | -            | -                | -                | -         |    -0.34 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            7 |     3929 | 2024-02-27 | FlyQuest          | W   | 0.164      | 0.143        | 0.106 (0.002)    | 0.322 (0.008)    | 1 (0.164) |     3.81 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            6 |     3931 | 2024-02-27 | The MongolZ       | L   | 0.162      | -            | -                | -                | -         |    -0.02 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            5 |     3967 | 2024-02-25 | TYLOO             | W   | 0.150      | 0.143        | 0.020 (0.000)    | 0.094 (0.002)    | 1 (0.150) |     1.06 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            4 |     3970 | 2024-02-25 | Twisted Minds     | W   | 0.149      | -            | -                | -                | 1 (0.149) |     0.17 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            3 |     4185 | 2024-02-17 | Newhappy          | L   | 0.092      | -            | -                | -                | -         |    -2.71 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            2 |     4215 | 2024-02-16 | Newhappy          | W   | 0.085      | -            | -                | -                | -         |     0.16 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            1 |     4221 | 2024-02-16 | MAG               | W   | 0.084      | -            | -                | -                | -         |     0.15 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($26,067.25)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.844 | $15,000.00     | $12,666.67      |
| 2024-06-02 |      0.798 | $10,000.00     | $7,978.94       |
| 2024-04-14 |      0.471 | $5,000.00      | $2,356.37       |
| 2024-03-20 |      0.307 | $10,000.00     | $3,065.28       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
