### Roster Details<br />
Team Name: Lynn Vision<br />
Roster: EmiliaQAQ, flying, Starry, Westmelon, z4kr<br />
Global Rank: [58](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [3]( ../standings_asia.md)<br />
<br />
Final Rank Value:  993.4<br />
<br />
Final Rank Value (993.4) = Starting Rank Value (981.0) + Head To Head Adjustments (12.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.475[<sup>1</sup>](#table2)
- Bounty Collected: 0.309[<sup>2</sup>](#table1)
- Opponent Network: 0.049[<sup>2</sup>](#table1)
- LAN Wins: 0.303[<sup>2</sup>](#table1)

The average of these factors is 0.284<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 981.0
- 400 + ( ( 0.284 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 981.0


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
|           27 |     1156 | 2024-06-09 | ATOX              | W   | 0.831      | 0.416        | 0.020 (0.007)    | 0.187 (0.065)    | 0 (0.000) |     9.73 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           26 |     1209 | 2024-06-08 | TYLOO             | W   | 0.825      | 0.416        | 0.013 (0.004)    | 0.220 (0.075)    | 0 (0.000) |     5.20 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           25 |     1331 | 2024-06-06 | ATOX              | L   | 0.812      | -            | -                | -                | -         |   -16.28 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           24 |     1386 | 2024-06-05 | TYLOO             | W   | 0.805      | 0.416        | 0.013 (0.004)    | 0.220 (0.074)    | 0 (0.000) |     4.45 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           23 |     1505 | 2024-06-01 | Aurora            | L   | 0.779      | -            | -                | -                | -         |    -1.07 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           22 |     1515 | 2024-05-31 | ATOX              | W   | 0.776      | 0.500        | 0.020 (0.008)    | 0.187 (0.073)    | 1 (0.776) |     8.55 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           21 |     1567 | 2024-05-30 | Gaimin Gladiators | W   | 0.764      | 0.500        | 0.038 (0.015)    | 0.366 (0.140)    | 1 (0.764) |    12.62 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           20 |     1612 | 2024-05-28 | Aurora            | L   | 0.751      | -            | -                | -                | -         |    -0.92 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           19 |     2667 | 2024-04-18 | Rare Atom         | L   | 0.486      | -            | -                | -                | -         |   -12.71 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           18 |     2678 | 2024-04-18 | TYLOO             | L   | 0.485      | -            | -                | -                | -         |   -11.97 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           17 |     2935 | 2024-04-09 | G2                | L   | 0.425      | -            | -                | -                | -         |    -0.06 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           16 |     2963 | 2024-04-08 | TYLOO             | W   | 0.419      | 0.624        | 0.019 (0.005)    | 0.096 (0.025)    | 1 (0.419) |     2.77 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           15 |     2974 | 2024-04-07 | FURIA             | L   | 0.417      | -            | -                | -                | -         |    -0.26 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           14 |     3106 | 2024-04-03 | The MongolZ       | L   | 0.385      | -            | -                | -                | -         |    -0.07 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           13 |     3144 | 2024-04-02 | LYG               | W   | 0.379      | 0.143        | -                | 0.035 (0.002)    | -         |     2.16 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           12 |     3150 | 2024-04-02 | ATOX              | W   | 0.378      | 0.143        | 0.020 (0.001)    | 0.187 (0.010)    | -         |     3.98 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           11 |     3360 | 2024-03-19 | The MongolZ       | L   | 0.285      | -            | -                | -                | -         |    -0.04 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           10 |     3369 | 2024-03-18 | Gaimin Gladiators | L   | 0.279      | -            | -                | -                | -         |    -4.45 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            9 |     3376 | 2024-03-17 | FURIA             | W   | 0.275      | 0.143        | 0.284 (0.011)    | 0.508 (0.020)    | 1 (0.275) |     8.51 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            8 |     3395 | 2024-03-17 | HEROIC            | L   | 0.273      | -            | -                | -                | -         |    -0.32 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            7 |     3830 | 2024-02-27 | FlyQuest          | W   | 0.151      | 0.143        | 0.104 (0.002)    | 0.302 (0.007)    | 1 (0.151) |     3.49 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            6 |     3832 | 2024-02-27 | The MongolZ       | L   | 0.149      | -            | -                | -                | -         |    -0.02 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            5 |     3867 | 2024-02-25 | TYLOO             | W   | 0.137      | 0.143        | 0.019 (0.000)    | -                | 1 (0.137) |     1.00 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            4 |     3870 | 2024-02-25 | Twisted Minds     | W   | 0.136      | -            | -                | -                | 1 (0.136) |     0.16 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            3 |     4078 | 2024-02-17 | Newhappy          | L   | 0.079      | -            | -                | -                | -         |    -2.32 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            2 |     4107 | 2024-02-16 | Newhappy          | W   | 0.072      | -            | -                | -                | -         |     0.15 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            1 |     4113 | 2024-02-16 | MAG               | W   | 0.071      | -            | -                | -                | -         |     0.13 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($25,546.88)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.831 | $15,000.00     | $12,471.53      |
| 2024-06-02 |      0.785 | $10,000.00     | $7,848.84       |
| 2024-04-14 |      0.458 | $5,000.00      | $2,291.32       |
| 2024-03-20 |      0.294 | $10,000.00     | $2,935.19       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
