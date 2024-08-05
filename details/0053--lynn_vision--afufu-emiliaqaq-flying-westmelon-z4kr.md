### Roster Details<br />
Team Name: Lynn Vision<br />
Roster: afufu, EmiliaQAQ, flying, Westmelon, z4kr<br />
Global Rank: [53](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [3]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1035.0<br />
<br />
Final Rank Value (1035.0) = Starting Rank Value (1050.0) + Head To Head Adjustments (-14.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.484[<sup>1</sup>](#table2)
- Bounty Collected: 0.312[<sup>2</sup>](#table1)
- Opponent Network: 0.062[<sup>2</sup>](#table1)
- LAN Wins: 0.410[<sup>2</sup>](#table1)

The average of these factors is 0.317<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1050.0
- 400 + ( ( 0.317 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1050.0


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
|           29 |       17 | 2024-08-05 | Chinggis Warriors  | L   | 1.000      | -            | -                | -                | -         |   -24.87 | afufu, EmiliaQAQ, flying, Westmelon, z4kr  |
|           28 |       44 | 2024-08-04 | Bad News Kangaroos | W   | 1.000      | 0.380        | 0.017 (0.006)    | 0.222 (0.085)    | 1 (1.000) |     5.41 | afufu, EmiliaQAQ, flying, Westmelon, z4kr  |
|           27 |     1272 | 2024-06-09 | ATOX               | W   | 0.818      | 0.416        | 0.020 (0.007)    | 0.215 (0.073)    | 0 (0.000) |     7.75 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           26 |     1330 | 2024-06-08 | TYLOO              | W   | 0.812      | 0.416        | 0.013 (0.004)    | 0.289 (0.097)    | 0 (0.000) |     7.19 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           25 |     1452 | 2024-06-06 | ATOX               | L   | 0.799      | -            | -                | -                | -         |   -17.83 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           24 |     1507 | 2024-06-05 | TYLOO              | W   | 0.792      | 0.416        | 0.013 (0.004)    | 0.289 (0.095)    | -         |     6.54 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           23 |     1629 | 2024-06-01 | Aurora             | L   | 0.765      | -            | -                | -                | -         |    -1.41 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           22 |     1639 | 2024-05-31 | ATOX               | W   | 0.763      | 0.500        | 0.020 (0.008)    | 0.215 (0.082)    | 1 (0.763) |     6.67 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           21 |     1691 | 2024-05-30 | Gaimin Gladiators  | W   | 0.751      | 0.500        | 0.037 (0.014)    | 0.342 (0.128)    | 1 (0.751) |    10.18 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           20 |     1736 | 2024-05-28 | Aurora             | L   | 0.737      | -            | -                | -                | -         |    -1.25 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           19 |     2795 | 2024-04-18 | Rare Atom          | L   | 0.472      | -            | -                | -                | -         |   -10.93 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           18 |     2806 | 2024-04-18 | TYLOO              | L   | 0.471      | -            | -                | -                | -         |   -12.45 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           17 |     3063 | 2024-04-09 | G2                 | L   | 0.412      | -            | -                | -                | -         |    -0.08 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           16 |     3091 | 2024-04-08 | TYLOO              | W   | 0.405      | 0.624        | 0.019 (0.005)    | 0.089 (0.023)    | 1 (0.405) |     1.99 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           15 |     3102 | 2024-04-07 | FURIA              | L   | 0.404      | -            | -                | -                | -         |    -0.35 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           14 |     3234 | 2024-04-03 | The MongolZ        | L   | 0.372      | -            | -                | -                | -         |    -0.10 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           13 |     3272 | 2024-04-02 | LYG                | W   | 0.365      | -            | -                | -                | -         |     1.52 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           12 |     3278 | 2024-04-02 | ATOX               | W   | 0.364      | 0.143        | 0.020 (0.001)    | 0.215 (0.011)    | -         |     2.96 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           11 |     3493 | 2024-03-19 | The MongolZ        | L   | 0.272      | -            | -                | -                | -         |    -0.06 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           10 |     3502 | 2024-03-18 | Gaimin Gladiators  | L   | 0.266      | -            | -                | -                | -         |    -5.11 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            9 |     3509 | 2024-03-17 | FURIA              | W   | 0.261      | 0.143        | 0.284 (0.011)    | 0.481 (0.018)    | 1 (0.261) |     8.03 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            8 |     3528 | 2024-03-17 | HEROIC             | L   | 0.259      | -            | -                | -                | -         |    -0.45 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            7 |     3966 | 2024-02-27 | FlyQuest           | W   | 0.137      | 0.143        | 0.104 (0.002)    | 0.286 (0.006)    | 1 (0.137) |     2.79 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            6 |     3968 | 2024-02-27 | The MongolZ        | L   | 0.136      | -            | -                | -                | -         |    -0.03 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            5 |     4003 | 2024-02-25 | TYLOO              | W   | 0.124      | -            | -                | -                | 1 (0.124) |     0.66 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            4 |     4006 | 2024-02-25 | Twisted Minds      | W   | 0.123      | -            | -                | -                | 1 (0.123) |     0.10 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            3 |     4215 | 2024-02-17 | Newhappy           | L   | 0.065      | -            | -                | -                | -         |    -1.97 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            2 |     4244 | 2024-02-16 | Newhappy           | W   | 0.059      | -            | -                | -                | -         |     0.08 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            1 |     4250 | 2024-02-16 | MAG                | W   | 0.058      | -            | -                | -                | -         |     0.07 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($27,767.69)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-05 |      1.000 | $2,756.00      | $2,756.00       |
| 2024-06-09 |      0.818 | $15,000.00     | $12,270.83      |
| 2024-06-02 |      0.772 | $10,000.00     | $7,715.05       |
| 2024-04-14 |      0.445 | $5,000.00      | $2,224.42       |
| 2024-03-20 |      0.280 | $10,000.00     | $2,801.39       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
