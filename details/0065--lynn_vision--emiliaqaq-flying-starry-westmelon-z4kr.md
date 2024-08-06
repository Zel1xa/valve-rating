### Roster Details<br />
Team Name: Lynn Vision<br />
Roster: EmiliaQAQ, flying, Starry, Westmelon, z4kr<br />
Global Rank: [65](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [3]( ../standings_asia.md)<br />
<br />
Final Rank Value:  989.0<br />
<br />
Final Rank Value (989.0) = Starting Rank Value (976.6) + Head To Head Adjustments (12.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.474[<sup>1</sup>](#table2)
- Bounty Collected: 0.307[<sup>2</sup>](#table1)
- Opponent Network: 0.049[<sup>2</sup>](#table1)
- LAN Wins: 0.292[<sup>2</sup>](#table1)

The average of these factors is 0.280<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 976.6
- 400 + ( ( 0.280 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 976.6


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
|           27 |     1281 | 2024-06-09 | ATOX              | W   | 0.812      | 0.416        | 0.020 (0.007)    | 0.210 (0.071)    | 0 (0.000) |     9.60 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           26 |     1339 | 2024-06-08 | TYLOO             | W   | 0.806      | 0.416        | 0.013 (0.004)    | 0.245 (0.082)    | 0 (0.000) |     5.24 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           25 |     1461 | 2024-06-06 | ATOX              | L   | 0.793      | -            | -                | -                | -         |   -15.81 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           24 |     1516 | 2024-06-05 | TYLOO             | W   | 0.786      | 0.416        | 0.013 (0.004)    | 0.245 (0.080)    | 0 (0.000) |     4.51 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           23 |     1638 | 2024-06-01 | Aurora            | L   | 0.760      | -            | -                | -                | -         |    -0.97 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           22 |     1648 | 2024-05-31 | ATOX              | W   | 0.757      | 0.500        | 0.020 (0.008)    | 0.210 (0.079)    | 1 (0.757) |     8.46 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           21 |     1700 | 2024-05-30 | Gaimin Gladiators | W   | 0.745      | 0.500        | 0.037 (0.014)    | 0.331 (0.123)    | 1 (0.745) |    12.25 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           20 |     1745 | 2024-05-28 | Aurora            | L   | 0.732      | -            | -                | -                | -         |    -0.83 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           19 |     2804 | 2024-04-18 | Rare Atom         | L   | 0.467      | -            | -                | -                | -         |   -12.73 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           18 |     2815 | 2024-04-18 | TYLOO             | L   | 0.466      | -            | -                | -                | -         |   -11.45 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           17 |     3072 | 2024-04-09 | G2                | L   | 0.406      | -            | -                | -                | -         |    -0.05 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           16 |     3100 | 2024-04-08 | TYLOO             | W   | 0.400      | 0.624        | 0.019 (0.005)    | 0.086 (0.022)    | 1 (0.400) |     2.70 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           15 |     3111 | 2024-04-07 | FURIA             | L   | 0.398      | -            | -                | -                | -         |    -0.24 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           14 |     3243 | 2024-04-03 | The MongolZ       | L   | 0.366      | -            | -                | -                | -         |    -0.07 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           13 |     3281 | 2024-04-02 | LYG               | W   | 0.360      | 0.143        | -                | 0.031 (0.002)    | -         |     2.10 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           12 |     3287 | 2024-04-02 | ATOX              | W   | 0.359      | 0.143        | 0.020 (0.001)    | 0.210 (0.011)    | -         |     3.83 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           11 |     3502 | 2024-03-19 | The MongolZ       | L   | 0.266      | -            | -                | -                | -         |    -0.04 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           10 |     3511 | 2024-03-18 | Gaimin Gladiators | L   | 0.260      | -            | -                | -                | -         |    -4.22 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            9 |     3518 | 2024-03-17 | FURIA             | W   | 0.256      | 0.143        | 0.284 (0.010)    | 0.469 (0.017)    | 1 (0.256) |     7.92 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            8 |     3537 | 2024-03-17 | HEROIC            | L   | 0.254      | -            | -                | -                | -         |    -0.30 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            7 |     3975 | 2024-02-27 | FlyQuest          | W   | 0.132      | 0.143        | 0.104 (0.002)    | 0.274 (0.005)    | 1 (0.132) |     3.03 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            6 |     3977 | 2024-02-27 | The MongolZ       | L   | 0.130      | -            | -                | -                | -         |    -0.02 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            5 |     4012 | 2024-02-25 | TYLOO             | W   | 0.118      | 0.143        | 0.019 (0.000)    | -                | 1 (0.118) |     0.87 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            4 |     4015 | 2024-02-25 | Twisted Minds     | W   | 0.117      | -            | -                | -                | 1 (0.117) |     0.14 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            3 |     4224 | 2024-02-17 | Newhappy          | L   | 0.060      | -            | -                | -                | -         |    -1.76 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            2 |     4253 | 2024-02-16 | Newhappy          | W   | 0.053      | -            | -                | -                | -         |     0.11 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            1 |     4259 | 2024-02-16 | MAG               | W   | 0.052      | -            | -                | -                | -         |     0.10 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($24,785.76)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.812 | $15,000.00     | $12,186.11      |
| 2024-06-02 |      0.766 | $10,000.00     | $7,658.56       |
| 2024-04-14 |      0.439 | $5,000.00      | $2,196.18       |
| 2024-03-20 |      0.274 | $10,000.00     | $2,744.91       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
