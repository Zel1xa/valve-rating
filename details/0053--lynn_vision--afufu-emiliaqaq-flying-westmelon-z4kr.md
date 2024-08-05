### Roster Details<br />
Team Name: Lynn Vision<br />
Roster: afufu, EmiliaQAQ, flying, Westmelon, z4kr<br />
Global Rank: [53](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [3]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1051.7<br />
<br />
Final Rank Value (1051.7) = Starting Rank Value (1045.5) + Head To Head Adjustments (6.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.474[<sup>1</sup>](#table2)
- Bounty Collected: 0.312[<sup>2</sup>](#table1)
- Opponent Network: 0.063[<sup>2</sup>](#table1)
- LAN Wins: 0.412[<sup>2</sup>](#table1)

The average of these factors is 0.316<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1045.5
- 400 + ( ( 0.316 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1045.5


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
|           28 |       23 | 2024-08-04 | Bad News Kangaroos | W   | 1.000      | 0.380        | 0.017 (0.006)    | 0.226 (0.086)    | 1 (1.000) |     5.63 | afufu, EmiliaQAQ, flying, Westmelon, z4kr  |
|           27 |     1251 | 2024-06-09 | ATOX               | W   | 0.823      | 0.416        | 0.020 (0.007)    | 0.219 (0.075)    | 0 (0.000) |     8.03 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           26 |     1309 | 2024-06-08 | TYLOO              | W   | 0.816      | 0.416        | 0.013 (0.004)    | 0.292 (0.099)    | 0 (0.000) |     5.70 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           25 |     1431 | 2024-06-06 | ATOX               | L   | 0.803      | -            | -                | -                | -         |   -17.73 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           24 |     1486 | 2024-06-05 | TYLOO              | W   | 0.796      | 0.416        | 0.013 (0.004)    | 0.292 (0.097)    | -         |     5.01 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           23 |     1608 | 2024-06-01 | Aurora             | L   | 0.770      | -            | -                | -                | -         |    -1.41 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           22 |     1618 | 2024-05-31 | ATOX               | W   | 0.767      | 0.500        | 0.020 (0.008)    | 0.219 (0.084)    | 1 (0.767) |     6.86 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           21 |     1670 | 2024-05-30 | Gaimin Gladiators  | W   | 0.755      | 0.500        | 0.038 (0.014)    | 0.349 (0.132)    | 1 (0.755) |    10.49 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           20 |     1715 | 2024-05-28 | Aurora             | L   | 0.742      | -            | -                | -                | -         |    -1.24 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           19 |     2774 | 2024-04-18 | Rare Atom          | L   | 0.477      | -            | -                | -                | -         |   -13.07 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           18 |     2785 | 2024-04-18 | TYLOO              | L   | 0.476      | -            | -                | -                | -         |   -12.53 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           17 |     3042 | 2024-04-09 | G2                 | L   | 0.416      | -            | -                | -                | -         |    -0.07 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           16 |     3070 | 2024-04-08 | TYLOO              | W   | 0.410      | 0.624        | 0.019 (0.005)    | 0.091 (0.023)    | 1 (0.410) |     2.05 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           15 |     3081 | 2024-04-07 | FURIA              | L   | 0.408      | -            | -                | -                | -         |    -0.35 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           14 |     3213 | 2024-04-03 | The MongolZ        | L   | 0.377      | -            | -                | -                | -         |    -0.10 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           13 |     3251 | 2024-04-02 | LYG                | W   | 0.370      | -            | -                | -                | -         |     1.57 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           12 |     3257 | 2024-04-02 | ATOX               | W   | 0.369      | 0.143        | 0.020 (0.001)    | 0.219 (0.012)    | -         |     3.04 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           11 |     3472 | 2024-03-19 | The MongolZ        | L   | 0.276      | -            | -                | -                | -         |    -0.06 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           10 |     3481 | 2024-03-18 | Gaimin Gladiators  | L   | 0.270      | -            | -                | -                | -         |    -5.12 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            9 |     3488 | 2024-03-17 | FURIA              | W   | 0.266      | 0.143        | 0.284 (0.011)    | 0.490 (0.019)    | 1 (0.266) |     8.17 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            8 |     3507 | 2024-03-17 | HEROIC             | L   | 0.264      | -            | -                | -                | -         |    -0.45 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            7 |     3945 | 2024-02-27 | FlyQuest           | W   | 0.142      | 0.143        | 0.104 (0.002)    | 0.293 (0.006)    | 1 (0.142) |     2.92 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            6 |     3947 | 2024-02-27 | The MongolZ        | L   | 0.140      | -            | -                | -                | -         |    -0.03 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            5 |     3982 | 2024-02-25 | TYLOO              | W   | 0.128      | -            | -                | -                | 1 (0.128) |     0.69 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            4 |     3985 | 2024-02-25 | Twisted Minds      | W   | 0.127      | -            | -                | -                | 1 (0.127) |     0.11 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            3 |     4194 | 2024-02-17 | Newhappy           | L   | 0.070      | -            | -                | -                | -         |    -2.10 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            2 |     4223 | 2024-02-16 | Newhappy           | W   | 0.063      | -            | -                | -                | -         |     0.09 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            1 |     4229 | 2024-02-16 | MAG                | W   | 0.062      | -            | -                | -                | -         |     0.08 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($25,189.47)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.823 | $15,000.00     | $12,337.50      |
| 2024-06-02 |      0.776 | $10,000.00     | $7,759.49       |
| 2024-04-14 |      0.449 | $5,000.00      | $2,246.64       |
| 2024-03-20 |      0.285 | $10,000.00     | $2,845.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
