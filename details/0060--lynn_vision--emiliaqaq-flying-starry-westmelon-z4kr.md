### Roster Details<br />
Team Name: Lynn Vision<br />
Roster: EmiliaQAQ, flying, Starry, Westmelon, z4kr<br />
Global Rank: [60](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [3]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1007.2<br />
<br />
Final Rank Value (1007.2) = Starting Rank Value (996.7) + Head To Head Adjustments (10.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.476[<sup>1</sup>](#table2)
- Bounty Collected: 0.311[<sup>2</sup>](#table1)
- Opponent Network: 0.049[<sup>2</sup>](#table1)
- LAN Wins: 0.321[<sup>2</sup>](#table1)

The average of these factors is 0.289<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 996.7
- 400 + ( ( 0.289 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 996.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           27 |     1098 | 2024-06-09 | ATOX              | W   | 0.850      | 0.416        | 0.021 (0.007)    | 0.184 (0.065)    | 0 (0.000) |     9.86 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           26 |     1156 | 2024-06-08 | TYLOO             | W   | 0.844      | 0.416        | 0.013 (0.004)    | 0.210 (0.074)    | 0 (0.000) |     5.04 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           25 |     1278 | 2024-06-06 | ATOX              | L   | 0.831      | -            | -                | -                | -         |   -16.75 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           24 |     1333 | 2024-06-05 | TYLOO             | W   | 0.824      | 0.416        | 0.013 (0.004)    | 0.210 (0.072)    | 0 (0.000) |     4.28 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           23 |     1455 | 2024-06-01 | Aurora            | L   | 0.798      | -            | -                | -                | -         |    -1.13 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           22 |     1465 | 2024-05-31 | ATOX              | W   | 0.795      | 0.500        | 0.021 (0.008)    | 0.184 (0.073)    | 1 (0.795) |     8.64 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           21 |     1517 | 2024-05-30 | Gaimin Gladiators | W   | 0.783      | 0.500        | 0.040 (0.015)    | 0.363 (0.142)    | 1 (0.783) |    12.88 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           20 |     1562 | 2024-05-28 | Aurora            | L   | 0.770      | -            | -                | -                | -         |    -0.97 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           19 |     2621 | 2024-04-18 | Rare Atom         | L   | 0.505      | -            | -                | -                | -         |   -13.98 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           18 |     2632 | 2024-04-18 | TYLOO             | L   | 0.504      | -            | -                | -                | -         |   -12.58 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           17 |     2889 | 2024-04-09 | G2                | L   | 0.444      | -            | -                | -                | -         |    -0.06 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           16 |     2917 | 2024-04-08 | TYLOO             | W   | 0.438      | 0.624        | 0.020 (0.005)    | 0.095 (0.026)    | 1 (0.438) |     2.77 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           15 |     2928 | 2024-04-07 | FURIA             | L   | 0.436      | -            | -                | -                | -         |    -0.26 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           14 |     3060 | 2024-04-03 | The MongolZ       | L   | 0.404      | -            | -                | -                | -         |    -0.08 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           13 |     3098 | 2024-04-02 | LYG               | W   | 0.398      | -            | -                | -                | -         |     2.15 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           12 |     3104 | 2024-04-02 | ATOX              | W   | 0.397      | 0.143        | 0.021 (0.001)    | 0.184 (0.010)    | -         |     4.09 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           11 |     3319 | 2024-03-19 | The MongolZ       | L   | 0.304      | -            | -                | -                | -         |    -0.05 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           10 |     3328 | 2024-03-18 | Gaimin Gladiators | L   | 0.298      | -            | -                | -                | -         |    -4.74 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            9 |     3335 | 2024-03-17 | FURIA             | W   | 0.294      | 0.143        | 0.284 (0.012)    | 0.495 (0.021)    | 1 (0.294) |     9.10 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            8 |     3354 | 2024-03-17 | HEROIC            | L   | 0.292      | -            | -                | -                | -         |    -0.33 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            7 |     3792 | 2024-02-27 | FlyQuest          | W   | 0.170      | 0.143        | 0.105 (0.003)    | 0.298 (0.007)    | 1 (0.170) |     3.98 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            6 |     3794 | 2024-02-27 | The MongolZ       | L   | 0.168      | -            | -                | -                | -         |    -0.02 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            5 |     3829 | 2024-02-25 | TYLOO             | W   | 0.156      | 0.143        | 0.020 (0.000)    | 0.095 (0.002)    | 1 (0.156) |     1.09 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            4 |     3832 | 2024-02-25 | Twisted Minds     | W   | 0.155      | -            | -                | -                | 1 (0.155) |     0.17 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            3 |     4041 | 2024-02-17 | Newhappy          | L   | 0.098      | -            | -                | -                | -         |    -2.89 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            2 |     4070 | 2024-02-16 | Newhappy          | W   | 0.091      | -            | -                | -                | -         |     0.17 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            1 |     4076 | 2024-02-16 | MAG               | W   | 0.090      | -            | -                | -                | -         |     0.16 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($26,307.43)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.850 | $15,000.00     | $12,756.74      |
| 2024-06-02 |      0.804 | $10,000.00     | $8,038.98       |
| 2024-04-14 |      0.477 | $5,000.00      | $2,386.39       |
| 2024-03-20 |      0.313 | $10,000.00     | $3,125.32       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
