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
Final Rank Value (1034.9) = Starting Rank Value (1049.9) + Head To Head Adjustments (-15.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.484[<sup>1</sup>](#table2)
- Bounty Collected: 0.312[<sup>2</sup>](#table1)
- Opponent Network: 0.063[<sup>2</sup>](#table1)
- LAN Wins: 0.411[<sup>2</sup>](#table1)

The average of these factors is 0.317<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1049.9
- 400 + ( ( 0.317 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1049.9


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
|           29 |        9 | 2024-08-05 | Chinggis Warriors  | L   | 1.000      | -            | -                | -                | -         |   -24.88 | afufu, EmiliaQAQ, flying, Westmelon, z4kr  |
|           28 |       35 | 2024-08-04 | Bad News Kangaroos | W   | 1.000      | 0.380        | 0.017 (0.006)    | 0.225 (0.086)    | 1 (1.000) |     5.41 | afufu, EmiliaQAQ, flying, Westmelon, z4kr  |
|           27 |     1264 | 2024-06-09 | ATOX               | W   | 0.819      | 0.416        | 0.020 (0.007)    | 0.218 (0.074)    | 0 (0.000) |     7.75 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           26 |     1322 | 2024-06-08 | TYLOO              | W   | 0.813      | 0.416        | 0.013 (0.004)    | 0.292 (0.099)    | 0 (0.000) |     7.19 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           25 |     1444 | 2024-06-06 | ATOX               | L   | 0.800      | -            | -                | -                | -         |   -17.86 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           24 |     1499 | 2024-06-05 | TYLOO              | W   | 0.793      | 0.416        | 0.013 (0.004)    | 0.292 (0.096)    | -         |     6.54 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           23 |     1621 | 2024-06-01 | Aurora             | L   | 0.767      | -            | -                | -                | -         |    -1.44 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           22 |     1631 | 2024-05-31 | ATOX               | W   | 0.764      | 0.500        | 0.020 (0.008)    | 0.218 (0.083)    | 1 (0.764) |     6.68 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           21 |     1683 | 2024-05-30 | Gaimin Gladiators  | W   | 0.752      | 0.500        | 0.037 (0.014)    | 0.346 (0.130)    | 1 (0.752) |    10.20 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           20 |     1728 | 2024-05-28 | Aurora             | L   | 0.738      | -            | -                | -                | -         |    -1.26 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           19 |     2787 | 2024-04-18 | Rare Atom          | L   | 0.473      | -            | -                | -                | -         |   -10.96 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           18 |     2798 | 2024-04-18 | TYLOO              | L   | 0.472      | -            | -                | -                | -         |   -12.48 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           17 |     3055 | 2024-04-09 | G2                 | L   | 0.413      | -            | -                | -                | -         |    -0.08 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           16 |     3083 | 2024-04-08 | TYLOO              | W   | 0.407      | 0.624        | 0.019 (0.005)    | 0.090 (0.023)    | 1 (0.407) |     2.00 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           15 |     3094 | 2024-04-07 | FURIA              | L   | 0.405      | -            | -                | -                | -         |    -0.35 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           14 |     3226 | 2024-04-03 | The MongolZ        | L   | 0.373      | -            | -                | -                | -         |    -0.10 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           13 |     3264 | 2024-04-02 | LYG                | W   | 0.367      | -            | -                | -                | -         |     1.53 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           12 |     3270 | 2024-04-02 | ATOX               | W   | 0.365      | 0.143        | 0.020 (0.001)    | 0.218 (0.011)    | -         |     2.96 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           11 |     3485 | 2024-03-19 | The MongolZ        | L   | 0.273      | -            | -                | -                | -         |    -0.06 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           10 |     3494 | 2024-03-18 | Gaimin Gladiators  | L   | 0.267      | -            | -                | -                | -         |    -5.13 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            9 |     3501 | 2024-03-17 | FURIA              | W   | 0.262      | 0.143        | 0.284 (0.011)    | 0.487 (0.018)    | 1 (0.262) |     8.07 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            8 |     3520 | 2024-03-17 | HEROIC             | L   | 0.260      | -            | -                | -                | -         |    -0.45 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            7 |     3958 | 2024-02-27 | FlyQuest           | W   | 0.139      | 0.143        | 0.104 (0.002)    | 0.290 (0.006)    | 1 (0.139) |     2.82 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            6 |     3960 | 2024-02-27 | The MongolZ        | L   | 0.137      | -            | -                | -                | -         |    -0.03 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            5 |     3995 | 2024-02-25 | TYLOO              | W   | 0.125      | -            | -                | -                | 1 (0.125) |     0.66 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            4 |     3998 | 2024-02-25 | Twisted Minds      | W   | 0.124      | -            | -                | -                | 1 (0.124) |     0.10 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            3 |     4207 | 2024-02-17 | Newhappy           | L   | 0.067      | -            | -                | -                | -         |    -2.00 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            2 |     4236 | 2024-02-16 | Newhappy           | W   | 0.060      | -            | -                | -                | -         |     0.08 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            1 |     4242 | 2024-02-16 | MAG                | W   | 0.059      | -            | -                | -                | -         |     0.07 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($27,812.13)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-05 |      1.000 | $2,756.00      | $2,756.00       |
| 2024-06-09 |      0.819 | $15,000.00     | $12,287.50      |
| 2024-06-02 |      0.773 | $10,000.00     | $7,726.16       |
| 2024-04-14 |      0.446 | $5,000.00      | $2,229.98       |
| 2024-03-20 |      0.281 | $10,000.00     | $2,812.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
