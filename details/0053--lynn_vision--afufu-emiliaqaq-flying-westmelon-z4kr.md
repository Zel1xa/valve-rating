### Roster Details<br />
Team Name: Lynn Vision<br />
Roster: afufu, EmiliaQAQ, flying, Westmelon, z4kr<br />
Global Rank: [53](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [3]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1034.9<br />
<br />
Final Rank Value (1034.9) = Starting Rank Value (1049.8) + Head To Head Adjustments (-14.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.484[<sup>1</sup>](#table2)
- Bounty Collected: 0.312[<sup>2</sup>](#table1)
- Opponent Network: 0.062[<sup>2</sup>](#table1)
- LAN Wins: 0.410[<sup>2</sup>](#table1)

The average of these factors is 0.317<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1049.8
- 400 + ( ( 0.317 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1049.8


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
|           29 |       18 | 2024-08-05 | Chinggis Warriors  | L   | 1.000      | -            | -                | -                | -         |   -24.87 | afufu, EmiliaQAQ, flying, Westmelon, z4kr  |
|           28 |       45 | 2024-08-04 | Bad News Kangaroos | W   | 1.000      | 0.380        | 0.017 (0.006)    | 0.222 (0.085)    | 1 (1.000) |     5.41 | afufu, EmiliaQAQ, flying, Westmelon, z4kr  |
|           27 |     1273 | 2024-06-09 | ATOX               | W   | 0.818      | 0.416        | 0.020 (0.007)    | 0.215 (0.073)    | 0 (0.000) |     7.74 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           26 |     1331 | 2024-06-08 | TYLOO              | W   | 0.812      | 0.416        | 0.013 (0.004)    | 0.289 (0.097)    | 0 (0.000) |     7.19 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           25 |     1453 | 2024-06-06 | ATOX               | L   | 0.798      | -            | -                | -                | -         |   -17.82 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           24 |     1508 | 2024-06-05 | TYLOO              | W   | 0.792      | 0.416        | 0.013 (0.004)    | 0.289 (0.095)    | -         |     6.54 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           23 |     1630 | 2024-06-01 | Aurora             | L   | 0.765      | -            | -                | -                | -         |    -1.41 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           22 |     1640 | 2024-05-31 | ATOX               | W   | 0.762      | 0.500        | 0.020 (0.008)    | 0.215 (0.082)    | 1 (0.762) |     6.67 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           21 |     1692 | 2024-05-30 | Gaimin Gladiators  | W   | 0.750      | 0.500        | 0.037 (0.014)    | 0.342 (0.128)    | 1 (0.750) |    10.18 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           20 |     1737 | 2024-05-28 | Aurora             | L   | 0.737      | -            | -                | -                | -         |    -1.25 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           19 |     2796 | 2024-04-18 | Rare Atom          | L   | 0.472      | -            | -                | -                | -         |   -10.92 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           18 |     2807 | 2024-04-18 | TYLOO              | L   | 0.471      | -            | -                | -                | -         |   -12.44 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           17 |     3064 | 2024-04-09 | G2                 | L   | 0.411      | -            | -                | -                | -         |    -0.08 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           16 |     3092 | 2024-04-08 | TYLOO              | W   | 0.405      | 0.624        | 0.019 (0.005)    | 0.089 (0.023)    | 1 (0.405) |     1.99 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           15 |     3103 | 2024-04-07 | FURIA              | L   | 0.403      | -            | -                | -                | -         |    -0.35 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           14 |     3235 | 2024-04-03 | The MongolZ        | L   | 0.372      | -            | -                | -                | -         |    -0.10 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           13 |     3273 | 2024-04-02 | LYG                | W   | 0.365      | -            | -                | -                | -         |     1.52 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           12 |     3279 | 2024-04-02 | ATOX               | W   | 0.364      | 0.143        | 0.020 (0.001)    | 0.215 (0.011)    | -         |     2.95 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           11 |     3494 | 2024-03-19 | The MongolZ        | L   | 0.272      | -            | -                | -                | -         |    -0.06 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           10 |     3503 | 2024-03-18 | Gaimin Gladiators  | L   | 0.265      | -            | -                | -                | -         |    -5.10 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            9 |     3510 | 2024-03-17 | FURIA              | W   | 0.261      | 0.143        | 0.284 (0.011)    | 0.481 (0.018)    | 1 (0.261) |     8.02 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            8 |     3529 | 2024-03-17 | HEROIC             | L   | 0.259      | -            | -                | -                | -         |    -0.45 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            7 |     3967 | 2024-02-27 | FlyQuest           | W   | 0.137      | 0.143        | 0.104 (0.002)    | 0.286 (0.006)    | 1 (0.137) |     2.79 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            6 |     3969 | 2024-02-27 | The MongolZ        | L   | 0.135      | -            | -                | -                | -         |    -0.03 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            5 |     4004 | 2024-02-25 | TYLOO              | W   | 0.123      | -            | -                | -                | 1 (0.123) |     0.66 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            4 |     4007 | 2024-02-25 | Twisted Minds      | W   | 0.123      | -            | -                | -                | 1 (0.123) |     0.10 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            3 |     4216 | 2024-02-17 | Newhappy           | L   | 0.065      | -            | -                | -                | -         |    -1.96 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            2 |     4245 | 2024-02-16 | Newhappy           | W   | 0.058      | -            | -                | -                | -         |     0.08 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            1 |     4251 | 2024-02-16 | MAG                | W   | 0.057      | -            | -                | -                | -         |     0.07 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($27,751.02)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-05 |      1.000 | $2,756.00      | $2,756.00       |
| 2024-06-09 |      0.818 | $15,000.00     | $12,264.58      |
| 2024-06-02 |      0.771 | $10,000.00     | $7,710.88       |
| 2024-04-14 |      0.444 | $5,000.00      | $2,222.34       |
| 2024-03-20 |      0.280 | $10,000.00     | $2,797.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
