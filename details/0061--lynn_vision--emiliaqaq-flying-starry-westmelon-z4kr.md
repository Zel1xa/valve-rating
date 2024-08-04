### Roster Details<br />
Team Name: Lynn Vision<br />
Roster: EmiliaQAQ, flying, Starry, Westmelon, z4kr<br />
Global Rank: [61](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [3]( ../standings_asia.md)<br />
<br />
Final Rank Value:  992.8<br />
<br />
Final Rank Value (992.8) = Starting Rank Value (980.5) + Head To Head Adjustments (12.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.475[<sup>1</sup>](#table2)
- Bounty Collected: 0.309[<sup>2</sup>](#table1)
- Opponent Network: 0.053[<sup>2</sup>](#table1)
- LAN Wins: 0.300[<sup>2</sup>](#table1)

The average of these factors is 0.284<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 980.5
- 400 + ( ( 0.284 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 980.5


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
|           27 |     1215 | 2024-06-09 | ATOX              | W   | 0.827      | 0.416        | 0.020 (0.007)    | 0.220 (0.075)    | 0 (0.000) |     9.69 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           26 |     1273 | 2024-06-08 | TYLOO             | W   | 0.821      | 0.416        | 0.013 (0.004)    | 0.252 (0.086)    | 0 (0.000) |     5.24 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           25 |     1395 | 2024-06-06 | ATOX              | L   | 0.807      | -            | -                | -                | -         |   -16.17 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           24 |     1450 | 2024-06-05 | TYLOO             | W   | 0.801      | 0.416        | 0.013 (0.004)    | 0.252 (0.084)    | 0 (0.000) |     4.49 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           23 |     1572 | 2024-06-01 | Aurora            | L   | 0.774      | -            | -                | -                | -         |    -1.08 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           22 |     1582 | 2024-05-31 | ATOX              | W   | 0.771      | 0.500        | 0.020 (0.008)    | 0.220 (0.085)    | 1 (0.771) |     8.52 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           21 |     1634 | 2024-05-30 | Gaimin Gladiators | W   | 0.759      | 0.500        | 0.038 (0.014)    | 0.351 (0.133)    | 1 (0.759) |    12.42 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           20 |     1679 | 2024-05-28 | Aurora            | L   | 0.746      | -            | -                | -                | -         |    -0.92 | EmiliaQAQ, flying, Starry, Westmelon, z4kr |
|           19 |     2738 | 2024-04-18 | Rare Atom         | L   | 0.481      | -            | -                | -                | -         |   -12.55 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           18 |     2749 | 2024-04-18 | TYLOO             | L   | 0.480      | -            | -                | -                | -         |   -11.86 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           17 |     3006 | 2024-04-09 | G2                | L   | 0.420      | -            | -                | -                | -         |    -0.06 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           16 |     3034 | 2024-04-08 | TYLOO             | W   | 0.414      | 0.624        | 0.019 (0.005)    | 0.092 (0.024)    | 1 (0.414) |     2.74 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           15 |     3045 | 2024-04-07 | FURIA             | L   | 0.412      | -            | -                | -                | -         |    -0.26 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           14 |     3177 | 2024-04-03 | The MongolZ       | L   | 0.381      | -            | -                | -                | -         |    -0.07 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           13 |     3215 | 2024-04-02 | LYG               | W   | 0.374      | 0.143        | -                | 0.034 (0.002)    | -         |     2.13 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           12 |     3221 | 2024-04-02 | ATOX              | W   | 0.373      | 0.143        | 0.020 (0.001)    | 0.220 (0.012)    | -         |     3.94 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           11 |     3436 | 2024-03-19 | The MongolZ       | L   | 0.281      | -            | -                | -                | -         |    -0.04 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|           10 |     3445 | 2024-03-18 | Gaimin Gladiators | L   | 0.274      | -            | -                | -                | -         |    -4.43 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            9 |     3452 | 2024-03-17 | FURIA             | W   | 0.270      | 0.143        | 0.284 (0.011)    | 0.491 (0.019)    | 1 (0.270) |     8.36 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            8 |     3471 | 2024-03-17 | HEROIC            | L   | 0.268      | -            | -                | -                | -         |    -0.32 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            7 |     3909 | 2024-02-27 | FlyQuest          | W   | 0.146      | 0.143        | 0.104 (0.002)    | 0.290 (0.006)    | 1 (0.146) |     3.37 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            6 |     3911 | 2024-02-27 | The MongolZ       | L   | 0.144      | -            | -                | -                | -         |    -0.02 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            5 |     3946 | 2024-02-25 | TYLOO             | W   | 0.133      | 0.143        | 0.019 (0.000)    | -                | 1 (0.133) |     0.96 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            4 |     3949 | 2024-02-25 | Twisted Minds     | W   | 0.132      | -            | -                | -                | 1 (0.132) |     0.16 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            3 |     4158 | 2024-02-17 | Newhappy          | L   | 0.074      | -            | -                | -                | -         |    -2.18 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            2 |     4187 | 2024-02-16 | Newhappy          | W   | 0.067      | -            | -                | -                | -         |     0.14 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |
|            1 |     4193 | 2024-02-16 | MAG               | W   | 0.066      | -            | -                | -                | -         |     0.12 | EmiliaQAQ, Jee, Starry, Westmelon, z4kr    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($25,356.13)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.827 | $15,000.00     | $12,400.00      |
| 2024-06-02 |      0.780 | $10,000.00     | $7,801.16       |
| 2024-04-14 |      0.453 | $5,000.00      | $2,267.48       |
| 2024-03-20 |      0.289 | $10,000.00     | $2,887.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
