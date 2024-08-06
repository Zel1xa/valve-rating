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
Final Rank Value (1034.5) = Starting Rank Value (1049.3) + Head To Head Adjustments (-14.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.484[<sup>1</sup>](#table2)
- Bounty Collected: 0.312[<sup>2</sup>](#table1)
- Opponent Network: 0.062[<sup>2</sup>](#table1)
- LAN Wins: 0.409[<sup>2</sup>](#table1)

The average of these factors is 0.317<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1049.3
- 400 + ( ( 0.317 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1049.3


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
|           29 |       20 | 2024-08-05 | Chinggis Warriors  | L   | 1.000      | -            | -                | -                | -         |   -24.86 | afufu, EmiliaQAQ, flying, Westmelon, z4kr  |
|           28 |       47 | 2024-08-04 | Bad News Kangaroos | W   | 1.000      | 0.380        | 0.016 (0.006)    | 0.222 (0.084)    | 1 (1.000) |     5.41 | afufu, EmiliaQAQ, flying, Westmelon, z4kr  |
|           27 |     1275 | 2024-06-09 | ATOX               | W   | 0.816      | 0.416        | 0.020 (0.007)    | 0.215 (0.073)    | 0 (0.000) |     7.73 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           26 |     1333 | 2024-06-08 | TYLOO              | W   | 0.810      | 0.416        | 0.013 (0.004)    | 0.289 (0.097)    | 0 (0.000) |     7.19 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           25 |     1455 | 2024-06-06 | ATOX               | L   | 0.796      | -            | -                | -                | -         |   -17.78 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           24 |     1510 | 2024-06-05 | TYLOO              | W   | 0.790      | 0.416        | 0.013 (0.004)    | 0.289 (0.095)    | -         |     6.55 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           23 |     1632 | 2024-06-01 | Aurora             | L   | 0.763      | -            | -                | -                | -         |    -1.40 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           22 |     1642 | 2024-05-31 | ATOX               | W   | 0.760      | 0.500        | 0.020 (0.008)    | 0.215 (0.082)    | 1 (0.760) |     6.66 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           21 |     1694 | 2024-05-30 | Gaimin Gladiators  | W   | 0.749      | 0.500        | 0.037 (0.014)    | 0.340 (0.127)    | 1 (0.749) |    10.14 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           20 |     1739 | 2024-05-28 | Aurora             | L   | 0.735      | -            | -                | -                | -         |    -1.24 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           19 |     2798 | 2024-04-18 | Rare Atom          | L   | 0.470      | -            | -                | -                | -         |   -10.86 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           18 |     2809 | 2024-04-18 | TYLOO              | L   | 0.469      | -            | -                | -                | -         |   -12.38 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           17 |     3066 | 2024-04-09 | G2                 | L   | 0.410      | -            | -                | -                | -         |    -0.07 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           16 |     3094 | 2024-04-08 | TYLOO              | W   | 0.403      | 0.624        | 0.019 (0.005)    | 0.089 (0.022)    | 1 (0.403) |     1.99 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           15 |     3105 | 2024-04-07 | FURIA              | L   | 0.401      | -            | -                | -                | -         |    -0.35 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           14 |     3237 | 2024-04-03 | The MongolZ        | L   | 0.370      | -            | -                | -                | -         |    -0.10 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           13 |     3275 | 2024-04-02 | LYG                | W   | 0.363      | -            | -                | -                | -         |     1.52 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           12 |     3281 | 2024-04-02 | ATOX               | W   | 0.362      | 0.143        | 0.020 (0.001)    | 0.215 (0.011)    | -         |     2.94 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           11 |     3496 | 2024-03-19 | The MongolZ        | L   | 0.270      | -            | -                | -                | -         |    -0.06 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           10 |     3505 | 2024-03-18 | Gaimin Gladiators  | L   | 0.263      | -            | -                | -                | -         |    -5.08 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            9 |     3512 | 2024-03-17 | FURIA              | W   | 0.259      | 0.143        | 0.284 (0.011)    | 0.480 (0.018)    | 1 (0.259) |     7.97 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            8 |     3531 | 2024-03-17 | HEROIC             | L   | 0.257      | -            | -                | -                | -         |    -0.45 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            7 |     3969 | 2024-02-27 | FlyQuest           | W   | 0.135      | 0.143        | 0.104 (0.002)    | 0.285 (0.006)    | 1 (0.135) |     2.75 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            6 |     3971 | 2024-02-27 | The MongolZ        | L   | 0.134      | -            | -                | -                | -         |    -0.03 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            5 |     4006 | 2024-02-25 | TYLOO              | W   | 0.122      | -            | -                | -                | 1 (0.122) |     0.65 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            4 |     4009 | 2024-02-25 | Twisted Minds      | W   | 0.121      | -            | -                | -                | 1 (0.121) |     0.10 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            3 |     4218 | 2024-02-17 | Newhappy           | L   | 0.063      | -            | -                | -                | -         |    -1.90 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            2 |     4247 | 2024-02-16 | Newhappy           | W   | 0.057      | -            | -                | -                | -         |     0.08 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            1 |     4253 | 2024-02-16 | MAG                | W   | 0.055      | -            | -                | -                | -         |     0.07 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($27,678.80)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-05 |      1.000 | $2,756.00      | $2,756.00       |
| 2024-06-09 |      0.816 | $15,000.00     | $12,237.50      |
| 2024-06-02 |      0.769 | $10,000.00     | $7,692.82       |
| 2024-04-14 |      0.443 | $5,000.00      | $2,213.31       |
| 2024-03-20 |      0.278 | $10,000.00     | $2,779.17       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
