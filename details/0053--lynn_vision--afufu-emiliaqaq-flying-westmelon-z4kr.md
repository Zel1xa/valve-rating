### Roster Details<br />
Team Name: Lynn Vision<br />
Roster: afufu, EmiliaQAQ, flying, Westmelon, z4kr<br />
Global Rank: [53](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [3]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1034.4<br />
<br />
Final Rank Value (1034.4) = Starting Rank Value (1049.1) + Head To Head Adjustments (-14.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.484[<sup>1</sup>](#table2)
- Bounty Collected: 0.311[<sup>2</sup>](#table1)
- Opponent Network: 0.060[<sup>2</sup>](#table1)
- LAN Wins: 0.407[<sup>2</sup>](#table1)

The average of these factors is 0.316<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1049.1
- 400 + ( ( 0.316 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1049.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           29 |       30 | 2024-08-05 | Chinggis Warriors  | L   | 1.000      | -            | -                | -                | -         |   -24.84 | afufu, EmiliaQAQ, flying, Westmelon, z4kr  |
|           28 |       57 | 2024-08-04 | Bad News Kangaroos | W   | 1.000      | 0.380        | 0.016 (0.006)    | 0.217 (0.083)    | 1 (1.000) |     5.41 | afufu, EmiliaQAQ, flying, Westmelon, z4kr  |
|           27 |     1285 | 2024-06-09 | ATOX               | W   | 0.813      | 0.416        | 0.020 (0.007)    | 0.210 (0.071)    | 0 (0.000) |     7.70 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           26 |     1343 | 2024-06-08 | TYLOO              | W   | 0.807      | 0.416        | 0.013 (0.004)    | 0.283 (0.095)    | 0 (0.000) |     7.18 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           25 |     1465 | 2024-06-06 | ATOX               | L   | 0.793      | -            | -                | -                | -         |   -17.70 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           24 |     1520 | 2024-06-05 | TYLOO              | W   | 0.787      | 0.416        | 0.013 (0.004)    | 0.283 (0.093)    | -         |     6.55 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           23 |     1642 | 2024-06-01 | Aurora             | L   | 0.760      | -            | -                | -                | -         |    -1.37 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           22 |     1652 | 2024-05-31 | ATOX               | W   | 0.757      | 0.500        | 0.020 (0.008)    | 0.210 (0.079)    | 1 (0.757) |     6.64 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           21 |     1704 | 2024-05-30 | Gaimin Gladiators  | W   | 0.745      | 0.500        | 0.037 (0.014)    | 0.331 (0.123)    | 1 (0.745) |    10.07 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           20 |     1749 | 2024-05-28 | Aurora             | L   | 0.732      | -            | -                | -                | -         |    -1.21 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           19 |     2808 | 2024-04-18 | Rare Atom          | L   | 0.467      | -            | -                | -                | -         |   -10.78 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           18 |     2819 | 2024-04-18 | TYLOO              | L   | 0.466      | -            | -                | -                | -         |   -12.29 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           17 |     3076 | 2024-04-09 | G2                 | L   | 0.406      | -            | -                | -                | -         |    -0.07 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           16 |     3104 | 2024-04-08 | TYLOO              | W   | 0.400      | 0.624        | 0.019 (0.005)    | 0.086 (0.022)    | 1 (0.400) |     1.98 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           15 |     3115 | 2024-04-07 | FURIA              | L   | 0.398      | -            | -                | -                | -         |    -0.35 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           14 |     3247 | 2024-04-03 | The MongolZ        | L   | 0.367      | -            | -                | -                | -         |    -0.10 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           13 |     3285 | 2024-04-02 | LYG                | W   | 0.360      | -            | -                | -                | -         |     1.51 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           12 |     3291 | 2024-04-02 | ATOX               | W   | 0.359      | 0.143        | 0.020 (0.001)    | 0.210 (0.011)    | -         |     2.92 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           11 |     3506 | 2024-03-19 | The MongolZ        | L   | 0.267      | -            | -                | -                | -         |    -0.06 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           10 |     3515 | 2024-03-18 | Gaimin Gladiators  | L   | 0.260      | -            | -                | -                | -         |    -5.03 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            9 |     3522 | 2024-03-17 | FURIA              | W   | 0.256      | 0.143        | 0.284 (0.010)    | 0.469 (0.017)    | 1 (0.256) |     7.87 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            8 |     3541 | 2024-03-17 | HEROIC             | L   | 0.254      | -            | -                | -                | -         |    -0.45 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            7 |     3979 | 2024-02-27 | FlyQuest           | W   | 0.132      | 0.143        | 0.104 (0.002)    | 0.278 (0.005)    | 1 (0.132) |     2.67 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            6 |     3981 | 2024-02-27 | The MongolZ        | L   | 0.130      | -            | -                | -                | -         |    -0.03 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            5 |     4016 | 2024-02-25 | TYLOO              | W   | 0.119      | -            | -                | -                | 1 (0.119) |     0.63 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            4 |     4019 | 2024-02-25 | Twisted Minds      | W   | 0.118      | -            | -                | -                | 1 (0.118) |     0.10 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            3 |     4228 | 2024-02-17 | Newhappy           | L   | 0.060      | -            | -                | -                | -         |    -1.81 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            2 |     4257 | 2024-02-16 | Newhappy           | W   | 0.053      | -            | -                | -                | -         |     0.07 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            1 |     4263 | 2024-02-16 | MAG                | W   | 0.052      | -            | -                | -                | -         |     0.07 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($27,552.88)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-05 |      1.000 | $2,756.00      | $2,756.00       |
| 2024-06-09 |      0.813 | $15,000.00     | $12,190.28      |
| 2024-06-02 |      0.766 | $10,000.00     | $7,661.34       |
| 2024-04-14 |      0.440 | $5,000.00      | $2,197.57       |
| 2024-03-20 |      0.275 | $10,000.00     | $2,747.69       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
