### Roster Details<br />
Team Name: Lynn Vision<br />
Roster: afufu, EmiliaQAQ, flying, Westmelon, z4kr<br />
Global Rank: [53](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [3]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1034.5<br />
<br />
Final Rank Value (1034.5) = Starting Rank Value (1049.2) + Head To Head Adjustments (-14.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.484[<sup>1</sup>](#table2)
- Bounty Collected: 0.311[<sup>2</sup>](#table1)
- Opponent Network: 0.060[<sup>2</sup>](#table1)
- LAN Wins: 0.407[<sup>2</sup>](#table1)

The average of these factors is 0.316<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1049.2
- 400 + ( ( 0.316 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1049.2


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
|           29 |       28 | 2024-08-05 | Chinggis Warriors  | L   | 1.000      | -            | -                | -                | -         |   -24.84 | afufu, EmiliaQAQ, flying, Westmelon, z4kr  |
|           28 |       55 | 2024-08-04 | Bad News Kangaroos | W   | 1.000      | 0.380        | 0.016 (0.006)    | 0.217 (0.083)    | 1 (1.000) |     5.41 | afufu, EmiliaQAQ, flying, Westmelon, z4kr  |
|           27 |     1283 | 2024-06-09 | ATOX               | W   | 0.813      | 0.416        | 0.020 (0.007)    | 0.210 (0.071)    | 0 (0.000) |     7.71 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           26 |     1341 | 2024-06-08 | TYLOO              | W   | 0.807      | 0.416        | 0.013 (0.004)    | 0.283 (0.095)    | 0 (0.000) |     7.18 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           25 |     1463 | 2024-06-06 | ATOX               | L   | 0.794      | -            | -                | -                | -         |   -17.71 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           24 |     1518 | 2024-06-05 | TYLOO              | W   | 0.787      | 0.416        | 0.013 (0.004)    | 0.283 (0.093)    | -         |     6.54 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           23 |     1640 | 2024-06-01 | Aurora             | L   | 0.760      | -            | -                | -                | -         |    -1.37 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           22 |     1650 | 2024-05-31 | ATOX               | W   | 0.758      | 0.500        | 0.020 (0.008)    | 0.210 (0.079)    | 1 (0.758) |     6.64 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           21 |     1702 | 2024-05-30 | Gaimin Gladiators  | W   | 0.746      | 0.500        | 0.037 (0.014)    | 0.331 (0.124)    | 1 (0.746) |    10.08 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           20 |     1747 | 2024-05-28 | Aurora             | L   | 0.732      | -            | -                | -                | -         |    -1.21 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           19 |     2806 | 2024-04-18 | Rare Atom          | L   | 0.467      | -            | -                | -                | -         |   -10.79 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           18 |     2817 | 2024-04-18 | TYLOO              | L   | 0.466      | -            | -                | -                | -         |   -12.30 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           17 |     3074 | 2024-04-09 | G2                 | L   | 0.407      | -            | -                | -                | -         |    -0.07 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           16 |     3102 | 2024-04-08 | TYLOO              | W   | 0.400      | 0.624        | 0.019 (0.005)    | 0.086 (0.022)    | 1 (0.400) |     1.98 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           15 |     3113 | 2024-04-07 | FURIA              | L   | 0.399      | -            | -                | -                | -         |    -0.35 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           14 |     3245 | 2024-04-03 | The MongolZ        | L   | 0.367      | -            | -                | -                | -         |    -0.10 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           13 |     3283 | 2024-04-02 | LYG                | W   | 0.360      | -            | -                | -                | -         |     1.51 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           12 |     3289 | 2024-04-02 | ATOX               | W   | 0.359      | 0.143        | 0.020 (0.001)    | 0.210 (0.011)    | -         |     2.93 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           11 |     3504 | 2024-03-19 | The MongolZ        | L   | 0.267      | -            | -                | -                | -         |    -0.06 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           10 |     3513 | 2024-03-18 | Gaimin Gladiators  | L   | 0.261      | -            | -                | -                | -         |    -5.04 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            9 |     3520 | 2024-03-17 | FURIA              | W   | 0.256      | 0.143        | 0.284 (0.010)    | 0.469 (0.017)    | 1 (0.256) |     7.88 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            8 |     3539 | 2024-03-17 | HEROIC             | L   | 0.254      | -            | -                | -                | -         |    -0.45 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            7 |     3977 | 2024-02-27 | FlyQuest           | W   | 0.132      | 0.143        | 0.104 (0.002)    | 0.278 (0.005)    | 1 (0.132) |     2.68 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            6 |     3979 | 2024-02-27 | The MongolZ        | L   | 0.131      | -            | -                | -                | -         |    -0.03 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            5 |     4014 | 2024-02-25 | TYLOO              | W   | 0.119      | -            | -                | -                | 1 (0.119) |     0.63 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            4 |     4017 | 2024-02-25 | Twisted Minds      | W   | 0.118      | -            | -                | -                | 1 (0.118) |     0.10 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            3 |     4226 | 2024-02-17 | Newhappy           | L   | 0.060      | -            | -                | -                | -         |    -1.82 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            2 |     4255 | 2024-02-16 | Newhappy           | W   | 0.054      | -            | -                | -                | -         |     0.08 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            1 |     4261 | 2024-02-16 | MAG                | W   | 0.053      | -            | -                | -                | -         |     0.07 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($27,567.69)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-05 |      1.000 | $2,756.00      | $2,756.00       |
| 2024-06-09 |      0.813 | $15,000.00     | $12,195.83      |
| 2024-06-02 |      0.767 | $10,000.00     | $7,665.05       |
| 2024-04-14 |      0.440 | $5,000.00      | $2,199.42       |
| 2024-03-20 |      0.275 | $10,000.00     | $2,751.39       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
