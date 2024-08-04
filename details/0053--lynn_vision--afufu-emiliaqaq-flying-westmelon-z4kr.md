### Roster Details<br />
Team Name: Lynn Vision<br />
Roster: afufu, EmiliaQAQ, flying, Westmelon, z4kr<br />
Global Rank: [53](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [3]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1052.3<br />
<br />
Final Rank Value (1052.3) = Starting Rank Value (1046.2) + Head To Head Adjustments (6.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.474[<sup>1</sup>](#table2)
- Bounty Collected: 0.313[<sup>2</sup>](#table1)
- Opponent Network: 0.063[<sup>2</sup>](#table1)
- LAN Wins: 0.414[<sup>2</sup>](#table1)

The average of these factors is 0.316<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1046.2
- 400 + ( ( 0.316 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1046.2


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
|           28 |       19 | 2024-08-04 | Bad News Kangaroos | W   | 1.000      | 0.380        | 0.017 (0.006)    | 0.226 (0.086)    | 1 (1.000) |     5.62 | afufu, EmiliaQAQ, flying, Westmelon, z4kr  |
|           27 |     1247 | 2024-06-09 | ATOX               | W   | 0.825      | 0.416        | 0.020 (0.007)    | 0.219 (0.075)    | 0 (0.000) |     8.05 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           26 |     1305 | 2024-06-08 | TYLOO              | W   | 0.819      | 0.416        | 0.013 (0.004)    | 0.292 (0.099)    | 0 (0.000) |     5.70 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           25 |     1427 | 2024-06-06 | ATOX               | L   | 0.805      | -            | -                | -                | -         |   -17.79 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           24 |     1482 | 2024-06-05 | TYLOO              | W   | 0.799      | 0.416        | 0.013 (0.004)    | 0.292 (0.097)    | -         |     5.01 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           23 |     1604 | 2024-06-01 | Aurora             | L   | 0.772      | -            | -                | -                | -         |    -1.43 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           22 |     1614 | 2024-05-31 | ATOX               | W   | 0.770      | 0.500        | 0.020 (0.008)    | 0.219 (0.084)    | 1 (0.770) |     6.87 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           21 |     1666 | 2024-05-30 | Gaimin Gladiators  | W   | 0.758      | 0.500        | 0.038 (0.014)    | 0.350 (0.133)    | 1 (0.758) |    10.54 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           20 |     1711 | 2024-05-28 | Aurora             | L   | 0.744      | -            | -                | -                | -         |    -1.25 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           19 |     2770 | 2024-04-18 | Rare Atom          | L   | 0.479      | -            | -                | -                | -         |   -13.14 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           18 |     2781 | 2024-04-18 | TYLOO              | L   | 0.478      | -            | -                | -                | -         |   -12.59 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           17 |     3038 | 2024-04-09 | G2                 | L   | 0.419      | -            | -                | -                | -         |    -0.08 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           16 |     3066 | 2024-04-08 | TYLOO              | W   | 0.412      | 0.624        | 0.019 (0.005)    | 0.092 (0.024)    | 1 (0.412) |     2.05 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           15 |     3077 | 2024-04-07 | FURIA              | L   | 0.410      | -            | -                | -                | -         |    -0.35 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           14 |     3209 | 2024-04-03 | The MongolZ        | L   | 0.379      | -            | -                | -                | -         |    -0.10 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           13 |     3247 | 2024-04-02 | LYG                | W   | 0.372      | -            | -                | -                | -         |     1.58 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           12 |     3253 | 2024-04-02 | ATOX               | W   | 0.371      | 0.143        | 0.020 (0.001)    | 0.219 (0.012)    | -         |     3.06 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           11 |     3468 | 2024-03-19 | The MongolZ        | L   | 0.279      | -            | -                | -                | -         |    -0.06 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           10 |     3477 | 2024-03-18 | Gaimin Gladiators  | L   | 0.272      | -            | -                | -                | -         |    -5.16 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            9 |     3484 | 2024-03-17 | FURIA              | W   | 0.268      | 0.143        | 0.284 (0.011)    | 0.490 (0.019)    | 1 (0.268) |     8.25 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            8 |     3503 | 2024-03-17 | HEROIC             | L   | 0.266      | -            | -                | -                | -         |    -0.45 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            7 |     3941 | 2024-02-27 | FlyQuest           | W   | 0.144      | 0.143        | 0.104 (0.002)    | 0.294 (0.006)    | 1 (0.144) |     2.98 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            6 |     3943 | 2024-02-27 | The MongolZ        | L   | 0.143      | -            | -                | -                | -         |    -0.03 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            5 |     3978 | 2024-02-25 | TYLOO              | W   | 0.131      | -            | -                | -                | 1 (0.131) |     0.70 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            4 |     3981 | 2024-02-25 | Twisted Minds      | W   | 0.130      | -            | -                | -                | 1 (0.130) |     0.11 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            3 |     4190 | 2024-02-17 | Newhappy           | L   | 0.072      | -            | -                | -                | -         |    -2.17 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            2 |     4219 | 2024-02-16 | Newhappy           | W   | 0.066      | -            | -                | -                | -         |     0.09 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            1 |     4225 | 2024-02-16 | MAG                | W   | 0.064      | -            | -                | -                | -         |     0.08 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($25,284.84)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.825 | $15,000.00     | $12,373.26      |
| 2024-06-02 |      0.778 | $10,000.00     | $7,783.33       |
| 2024-04-14 |      0.452 | $5,000.00      | $2,258.56       |
| 2024-03-20 |      0.287 | $10,000.00     | $2,869.68       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
