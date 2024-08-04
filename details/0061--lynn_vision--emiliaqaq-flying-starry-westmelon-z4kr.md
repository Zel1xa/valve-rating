### Roster Details<br />
Team Name: Lynn Vision<br />
Roster: EmiliaQAQ, flying, Starry, Westmelon, z4kr<br />
Global Rank: [61](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [3]( ../standings_asia.md)<br />
<br />
Final Rank Value:  993.8<br />
<br />
Final Rank Value (993.8) = Starting Rank Value (981.6) + Head To Head Adjustments (12.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.475[<sup>1</sup>](#table2)
- Bounty Collected: 0.309[<sup>2</sup>](#table1)
- Opponent Network: 0.053[<sup>2</sup>](#table1)
- LAN Wins: 0.302[<sup>2</sup>](#table1)

The average of these factors is 0.285<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 981.6
- 400 + ( ( 0.285 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 981.6


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
|           27 |     1211 | 2024-06-09 | ATOX              | W   | 0.830      | 0.416        | 0.020 (0.007)    | 0.220 (0.076)    | 0 (0.000) |     9.71 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           26 |     1269 | 2024-06-08 | TYLOO             | W   | 0.824      | 0.416        | 0.013 (0.004)    | 0.252 (0.086)    | 0 (0.000) |     5.24 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           25 |     1391 | 2024-06-06 | ATOX              | L   | 0.810      | -            | -                | -                | -         |   -16.24 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           24 |     1446 | 2024-06-05 | TYLOO             | W   | 0.804      | 0.416        | 0.013 (0.004)    | 0.252 (0.084)    | 0 (0.000) |     4.49 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           23 |     1568 | 2024-06-01 | Aurora            | L   | 0.777      | -            | -                | -                | -         |    -1.09 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           22 |     1578 | 2024-05-31 | ATOX              | W   | 0.774      | 0.500        | 0.020 (0.008)    | 0.220 (0.085)    | 1 (0.774) |     8.54 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           21 |     1630 | 2024-05-30 | Gaimin Gladiators | W   | 0.762      | 0.500        | 0.038 (0.015)    | 0.353 (0.134)    | 1 (0.762) |    12.50 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           20 |     1675 | 2024-05-28 | Aurora            | L   | 0.749      | -            | -                | -                | -         |    -0.94 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           19 |     2733 | 2024-04-18 | Rare Atom         | L   | 0.484      | -            | -                | -                | -         |   -12.64 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           18 |     2744 | 2024-04-18 | TYLOO             | L   | 0.483      | -            | -                | -                | -         |   -11.95 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           17 |     3001 | 2024-04-09 | G2                | L   | 0.423      | -            | -                | -                | -         |    -0.06 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           16 |     3029 | 2024-04-08 | TYLOO             | W   | 0.417      | 0.624        | 0.019 (0.005)    | 0.092 (0.024)    | 1 (0.417) |     2.75 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           15 |     3040 | 2024-04-07 | FURIA             | L   | 0.415      | -            | -                | -                | -         |    -0.26 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           14 |     3172 | 2024-04-03 | The MongolZ       | L   | 0.384      | -            | -                | -                | -         |    -0.07 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           13 |     3210 | 2024-04-02 | LYG               | W   | 0.377      | 0.143        | -                | 0.034 (0.002)    | -         |     2.14 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           12 |     3216 | 2024-04-02 | ATOX              | W   | 0.376      | 0.143        | 0.020 (0.001)    | 0.220 (0.012)    | -         |     3.96 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           11 |     3431 | 2024-03-19 | The MongolZ       | L   | 0.284      | -            | -                | -                | -         |    -0.04 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           10 |     3440 | 2024-03-18 | Gaimin Gladiators | L   | 0.277      | -            | -                | -                | -         |    -4.47 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            9 |     3447 | 2024-03-17 | FURIA             | W   | 0.273      | 0.143        | 0.284 (0.011)    | 0.491 (0.019)    | 1 (0.273) |     8.45 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            8 |     3466 | 2024-03-17 | HEROIC            | L   | 0.271      | -            | -                | -                | -         |    -0.33 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            7 |     3903 | 2024-02-27 | FlyQuest          | W   | 0.149      | 0.143        | 0.104 (0.002)    | 0.291 (0.006)    | 1 (0.149) |     3.44 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            6 |     3905 | 2024-02-27 | The MongolZ       | L   | 0.147      | -            | -                | -                | -         |    -0.02 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            5 |     3940 | 2024-02-25 | TYLOO             | W   | 0.136      | 0.143        | 0.019 (0.000)    | -                | 1 (0.136) |     0.98 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            4 |     3943 | 2024-02-25 | Twisted Minds     | W   | 0.135      | -            | -                | -                | 1 (0.135) |     0.16 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            3 |     4151 | 2024-02-17 | Newhappy          | L   | 0.077      | -            | -                | -                | -         |    -2.27 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            2 |     4180 | 2024-02-16 | Newhappy          | W   | 0.070      | -            | -                | -                | -         |     0.14 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            1 |     4186 | 2024-02-16 | MAG               | W   | 0.069      | -            | -                | -                | -         |     0.13 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($25,478.36)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.830 | $15,000.00     | $12,445.83      |
| 2024-06-02 |      0.783 | $10,000.00     | $7,831.71       |
| 2024-04-14 |      0.457 | $5,000.00      | $2,282.75       |
| 2024-03-20 |      0.292 | $10,000.00     | $2,918.06       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
