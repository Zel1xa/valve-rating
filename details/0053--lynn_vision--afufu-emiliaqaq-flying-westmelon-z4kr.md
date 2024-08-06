### Roster Details<br />
Team Name: Lynn Vision<br />
Roster: afufu, EmiliaQAQ, flying, Westmelon, z4kr<br />
Global Rank: [53](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [3]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1051.8<br />
<br />
Final Rank Value (1051.8) = Starting Rank Value (1057.5) + Head To Head Adjustments (-5.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.484[<sup>1</sup>](#table2)
- Bounty Collected: 0.328[<sup>2</sup>](#table1)
- Opponent Network: 0.060[<sup>2</sup>](#table1)
- LAN Wins: 0.407[<sup>2</sup>](#table1)

The average of these factors is 0.320<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1057.5
- 400 + ( ( 0.320 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1057.5


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
|           29 |       43 | 2024-08-05 | Chinggis Warriors  | L   | 1.000      | -            | -                | -                | -         |   -19.89 | afufu, EmiliaQAQ, flying, Westmelon, z4kr  |
|           28 |       69 | 2024-08-04 | Bad News Kangaroos | W   | 1.000      | 0.380        | 0.016 (0.006)    | 0.217 (0.082)    | 1 (1.000) |     5.10 | afufu, EmiliaQAQ, flying, Westmelon, z4kr  |
|           27 |     1297 | 2024-06-09 | ATOX               | W   | 0.812      | 0.416        | 0.020 (0.007)    | 0.209 (0.071)    | 0 (0.000) |     7.32 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           26 |     1355 | 2024-06-08 | TYLOO              | W   | 0.805      | 0.416        | 0.056 (0.019)    | 0.283 (0.095)    | 0 (0.000) |    10.16 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           25 |     1477 | 2024-06-06 | ATOX               | L   | 0.792      | -            | -                | -                | -         |   -17.97 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           24 |     1532 | 2024-06-05 | TYLOO              | W   | 0.785      | 0.416        | 0.056 (0.018)    | 0.283 (0.092)    | -         |     9.72 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           23 |     1654 | 2024-06-01 | Aurora             | L   | 0.759      | -            | -                | -                | -         |    -1.41 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           22 |     1664 | 2024-05-31 | ATOX               | W   | 0.756      | 0.500        | 0.020 (0.008)    | 0.209 (0.079)    | 1 (0.756) |     6.43 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           21 |     1716 | 2024-05-30 | Gaimin Gladiators  | W   | 0.744      | 0.500        | 0.037 (0.014)    | 0.331 (0.123)    | 1 (0.744) |     9.83 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           20 |     1761 | 2024-05-28 | Aurora             | L   | 0.731      | -            | -                | -                | -         |    -1.25 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           19 |     2820 | 2024-04-18 | Rare Atom          | L   | 0.466      | -            | -                | -                | -         |   -10.85 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           18 |     2831 | 2024-04-18 | TYLOO              | L   | 0.465      | -            | -                | -                | -         |   -12.35 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           17 |     3088 | 2024-04-09 | G2                 | L   | 0.405      | -            | -                | -                | -         |    -0.08 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           16 |     3116 | 2024-04-08 | TYLOO              | W   | 0.399      | 0.624        | 0.019 (0.005)    | 0.086 (0.021)    | 1 (0.399) |     1.90 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           15 |     3127 | 2024-04-07 | FURIA              | L   | 0.397      | -            | -                | -                | -         |    -0.36 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           14 |     3259 | 2024-04-03 | The MongolZ        | L   | 0.366      | -            | -                | -                | -         |    -0.10 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           13 |     3297 | 2024-04-02 | LYG                | W   | 0.359      | -            | -                | -                | -         |     1.45 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           12 |     3303 | 2024-04-02 | ATOX               | W   | 0.358      | 0.143        | 0.020 (0.001)    | 0.209 (0.011)    | -         |     2.81 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           11 |     3518 | 2024-03-19 | The MongolZ        | L   | 0.265      | -            | -                | -                | -         |    -0.06 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           10 |     3527 | 2024-03-18 | Gaimin Gladiators  | L   | 0.259      | -            | -                | -                | -         |    -5.10 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            9 |     3534 | 2024-03-17 | FURIA              | W   | 0.255      | 0.143        | 0.284 (0.010)    | 0.468 (0.017)    | 1 (0.255) |     7.82 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            8 |     3553 | 2024-03-17 | HEROIC             | L   | 0.253      | -            | -                | -                | -         |    -0.47 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            7 |     3991 | 2024-02-27 | FlyQuest           | W   | 0.131      | 0.143        | 0.104 (0.002)    | 0.277 (0.005)    | 1 (0.131) |     2.60 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            6 |     3993 | 2024-02-27 | The MongolZ        | L   | 0.129      | -            | -                | -                | -         |    -0.03 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            5 |     4028 | 2024-02-25 | TYLOO              | W   | 0.117      | -            | -                | -                | 1 (0.117) |     0.60 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            4 |     4031 | 2024-02-25 | Twisted Minds      | W   | 0.116      | -            | -                | -                | 1 (0.116) |     0.09 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            3 |     4240 | 2024-02-17 | Newhappy           | L   | 0.059      | -            | -                | -                | -         |    -1.78 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            2 |     4269 | 2024-02-16 | Newhappy           | W   | 0.052      | -            | -                | -                | -         |     0.07 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            1 |     4275 | 2024-02-16 | MAG                | W   | 0.051      | -            | -                | -                | -         |     0.06 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($27,506.58)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-06 |      1.000 | $2,756.00      | $2,756.00       |
| 2024-06-09 |      0.812 | $15,000.00     | $12,172.92      |
| 2024-06-02 |      0.765 | $10,000.00     | $7,649.77       |
| 2024-04-14 |      0.438 | $5,000.00      | $2,191.78       |
| 2024-03-20 |      0.274 | $10,000.00     | $2,736.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
