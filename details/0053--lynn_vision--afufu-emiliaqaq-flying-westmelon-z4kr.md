### Roster Details<br />
Team Name: Lynn Vision<br />
Roster: afufu, EmiliaQAQ, flying, Westmelon, z4kr<br />
Global Rank: [53](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [3]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1052.4<br />
<br />
Final Rank Value (1052.4) = Starting Rank Value (1046.5) + Head To Head Adjustments (5.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.475[<sup>1</sup>](#table2)
- Bounty Collected: 0.313[<sup>2</sup>](#table1)
- Opponent Network: 0.064[<sup>2</sup>](#table1)
- LAN Wins: 0.414[<sup>2</sup>](#table1)

The average of these factors is 0.316<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1046.5
- 400 + ( ( 0.316 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1046.5


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
|           28 |        7 | 2024-08-04 | Bad News Kangaroos | W   | 1.000      | 0.380        | 0.017 (0.006)    | 0.226 (0.086)    | 1 (1.000) |     5.62 | afufu, EmiliaQAQ, flying, Westmelon, z4kr  |
|           27 |     1223 | 2024-06-09 | ATOX               | W   | 0.826      | 0.416        | 0.020 (0.007)    | 0.220 (0.075)    | 0 (0.000) |     8.06 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           26 |     1281 | 2024-06-08 | TYLOO              | W   | 0.820      | 0.416        | 0.013 (0.004)    | 0.292 (0.099)    | 0 (0.000) |     5.71 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           25 |     1403 | 2024-06-06 | ATOX               | L   | 0.807      | -            | -                | -                | -         |   -17.81 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           24 |     1458 | 2024-06-05 | TYLOO              | W   | 0.800      | 0.416        | 0.013 (0.004)    | 0.292 (0.097)    | -         |     5.01 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           23 |     1580 | 2024-06-01 | Aurora             | L   | 0.773      | -            | -                | -                | -         |    -1.44 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           22 |     1590 | 2024-05-31 | ATOX               | W   | 0.771      | 0.500        | 0.020 (0.008)    | 0.220 (0.085)    | 1 (0.771) |     6.88 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           21 |     1642 | 2024-05-30 | Gaimin Gladiators  | W   | 0.759      | 0.500        | 0.038 (0.014)    | 0.351 (0.133)    | 1 (0.759) |    10.46 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           20 |     1687 | 2024-05-28 | Aurora             | L   | 0.745      | -            | -                | -                | -         |    -1.26 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           19 |     2746 | 2024-04-18 | Rare Atom          | L   | 0.480      | -            | -                | -                | -         |   -13.18 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           18 |     2757 | 2024-04-18 | TYLOO              | L   | 0.479      | -            | -                | -                | -         |   -12.63 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           17 |     3014 | 2024-04-09 | G2                 | L   | 0.420      | -            | -                | -                | -         |    -0.08 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           16 |     3042 | 2024-04-08 | TYLOO              | W   | 0.413      | 0.624        | 0.019 (0.005)    | 0.092 (0.024)    | 1 (0.413) |     2.06 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           15 |     3053 | 2024-04-07 | FURIA              | L   | 0.411      | -            | -                | -                | -         |    -0.36 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           14 |     3185 | 2024-04-03 | The MongolZ        | L   | 0.380      | -            | -                | -                | -         |    -0.10 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           13 |     3223 | 2024-04-02 | LYG                | W   | 0.373      | -            | -                | -                | -         |     1.58 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           12 |     3229 | 2024-04-02 | ATOX               | W   | 0.372      | 0.143        | 0.020 (0.001)    | 0.220 (0.012)    | -         |     3.06 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           11 |     3444 | 2024-03-19 | The MongolZ        | L   | 0.280      | -            | -                | -                | -         |    -0.06 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           10 |     3453 | 2024-03-18 | Gaimin Gladiators  | L   | 0.273      | -            | -                | -                | -         |    -5.20 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            9 |     3460 | 2024-03-17 | FURIA              | W   | 0.269      | 0.143        | 0.284 (0.011)    | 0.490 (0.019)    | 1 (0.269) |     8.28 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            8 |     3479 | 2024-03-17 | HEROIC             | L   | 0.267      | -            | -                | -                | -         |    -0.46 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            7 |     3917 | 2024-02-27 | FlyQuest           | W   | 0.145      | 0.143        | 0.104 (0.002)    | 0.294 (0.006)    | 1 (0.145) |     3.00 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            6 |     3919 | 2024-02-27 | The MongolZ        | L   | 0.144      | -            | -                | -                | -         |    -0.03 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            5 |     3954 | 2024-02-25 | TYLOO              | W   | 0.132      | -            | -                | -                | 1 (0.132) |     0.71 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            4 |     3957 | 2024-02-25 | Twisted Minds      | W   | 0.131      | -            | -                | -                | 1 (0.131) |     0.11 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            3 |     4166 | 2024-02-17 | Newhappy           | L   | 0.073      | -            | -                | -                | -         |    -2.20 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            2 |     4195 | 2024-02-16 | Newhappy           | W   | 0.067      | -            | -                | -                | -         |     0.10 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            1 |     4201 | 2024-02-16 | MAG                | W   | 0.066      | -            | -                | -                | -         |     0.09 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($25,327.43)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.826 | $15,000.00     | $12,389.24      |
| 2024-06-02 |      0.779 | $10,000.00     | $7,793.98       |
| 2024-04-14 |      0.453 | $5,000.00      | $2,263.89       |
| 2024-03-20 |      0.288 | $10,000.00     | $2,880.32       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
