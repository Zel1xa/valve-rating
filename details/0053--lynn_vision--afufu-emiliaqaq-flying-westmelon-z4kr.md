### Roster Details<br />
Team Name: Lynn Vision<br />
Roster: afufu, EmiliaQAQ, flying, Westmelon, z4kr<br />
Global Rank: [53](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [3]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1033.9<br />
<br />
Final Rank Value (1033.9) = Starting Rank Value (1048.6) + Head To Head Adjustments (-14.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.484[<sup>1</sup>](#table2)
- Bounty Collected: 0.311[<sup>2</sup>](#table1)
- Opponent Network: 0.061[<sup>2</sup>](#table1)
- LAN Wins: 0.407[<sup>2</sup>](#table1)

The average of these factors is 0.316<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1048.6
- 400 + ( ( 0.316 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1048.6


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
|           29 |       24 | 2024-08-05 | Chinggis Warriors  | L   | 1.000      | -            | -                | -                | -         |   -24.84 | afufu, EmiliaQAQ, flying, Westmelon, z4kr  |
|           28 |       51 | 2024-08-04 | Bad News Kangaroos | W   | 1.000      | 0.380        | 0.016 (0.006)    | 0.222 (0.084)    | 1 (1.000) |     5.42 | afufu, EmiliaQAQ, flying, Westmelon, z4kr  |
|           27 |     1279 | 2024-06-09 | ATOX               | W   | 0.813      | 0.416        | 0.020 (0.007)    | 0.214 (0.072)    | 0 (0.000) |     7.71 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           26 |     1337 | 2024-06-08 | TYLOO              | W   | 0.807      | 0.416        | 0.013 (0.004)    | 0.289 (0.097)    | 0 (0.000) |     7.19 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           25 |     1459 | 2024-06-06 | ATOX               | L   | 0.794      | -            | -                | -                | -         |   -17.72 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           24 |     1514 | 2024-06-05 | TYLOO              | W   | 0.787      | 0.416        | 0.013 (0.004)    | 0.289 (0.095)    | -         |     6.55 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           23 |     1636 | 2024-06-01 | Aurora             | L   | 0.761      | -            | -                | -                | -         |    -1.38 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           22 |     1646 | 2024-05-31 | ATOX               | W   | 0.758      | 0.500        | 0.020 (0.008)    | 0.214 (0.081)    | 1 (0.758) |     6.64 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           21 |     1698 | 2024-05-30 | Gaimin Gladiators  | W   | 0.746      | 0.500        | 0.037 (0.014)    | 0.339 (0.126)    | 1 (0.746) |    10.11 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           20 |     1743 | 2024-05-28 | Aurora             | L   | 0.733      | -            | -                | -                | -         |    -1.22 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           19 |     2802 | 2024-04-18 | Rare Atom          | L   | 0.468      | -            | -                | -                | -         |   -10.79 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           18 |     2813 | 2024-04-18 | TYLOO              | L   | 0.467      | -            | -                | -                | -         |   -12.31 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           17 |     3070 | 2024-04-09 | G2                 | L   | 0.407      | -            | -                | -                | -         |    -0.07 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           16 |     3098 | 2024-04-08 | TYLOO              | W   | 0.401      | 0.624        | 0.019 (0.005)    | 0.088 (0.022)    | 1 (0.401) |     1.98 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           15 |     3109 | 2024-04-07 | FURIA              | L   | 0.399      | -            | -                | -                | -         |    -0.34 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           14 |     3241 | 2024-04-03 | The MongolZ        | L   | 0.367      | -            | -                | -                | -         |    -0.10 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           13 |     3279 | 2024-04-02 | LYG                | W   | 0.361      | -            | -                | -                | -         |     1.51 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           12 |     3285 | 2024-04-02 | ATOX               | W   | 0.360      | 0.143        | 0.020 (0.001)    | 0.214 (0.011)    | -         |     2.93 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           11 |     3500 | 2024-03-19 | The MongolZ        | L   | 0.267      | -            | -                | -                | -         |    -0.06 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           10 |     3509 | 2024-03-18 | Gaimin Gladiators  | L   | 0.261      | -            | -                | -                | -         |    -5.03 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            9 |     3516 | 2024-03-17 | FURIA              | W   | 0.257      | 0.143        | 0.284 (0.010)    | 0.479 (0.018)    | 1 (0.257) |     7.89 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            8 |     3535 | 2024-03-17 | HEROIC             | L   | 0.254      | -            | -                | -                | -         |    -0.45 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            7 |     3973 | 2024-02-27 | FlyQuest           | W   | 0.133      | 0.143        | 0.104 (0.002)    | 0.284 (0.005)    | 1 (0.133) |     2.69 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            6 |     3975 | 2024-02-27 | The MongolZ        | L   | 0.131      | -            | -                | -                | -         |    -0.03 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            5 |     4010 | 2024-02-25 | TYLOO              | W   | 0.119      | -            | -                | -                | 1 (0.119) |     0.64 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            4 |     4013 | 2024-02-25 | Twisted Minds      | W   | 0.118      | -            | -                | -                | 1 (0.118) |     0.10 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            3 |     4222 | 2024-02-17 | Newhappy           | L   | 0.061      | -            | -                | -                | -         |    -1.83 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            2 |     4251 | 2024-02-16 | Newhappy           | W   | 0.054      | -            | -                | -                | -         |     0.08 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            1 |     4257 | 2024-02-16 | MAG                | W   | 0.053      | -            | -                | -                | -         |     0.07 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($27,578.80)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-05 |      1.000 | $2,756.00      | $2,756.00       |
| 2024-06-09 |      0.813 | $15,000.00     | $12,200.00      |
| 2024-06-02 |      0.767 | $10,000.00     | $7,667.82       |
| 2024-04-14 |      0.440 | $5,000.00      | $2,200.81       |
| 2024-03-20 |      0.275 | $10,000.00     | $2,754.17       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
