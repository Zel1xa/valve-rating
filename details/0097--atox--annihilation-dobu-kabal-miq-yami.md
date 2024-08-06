### Roster Details<br />
Team Name: ATOX<br />
Roster: Annihilation, dobu, kabal, MiQ, yAmi<br />
Global Rank: [97](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [6]( ../standings_asia.md)<br />
<br />
Final Rank Value:  872.5<br />
<br />
Final Rank Value (872.5) = Starting Rank Value (864.6) + Head To Head Adjustments (7.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.371[<sup>1</sup>](#table2)
- Bounty Collected: 0.324[<sup>2</sup>](#table1)
- Opponent Network: 0.018[<sup>2</sup>](#table1)
- LAN Wins: 0.190[<sup>2</sup>](#table1)

The average of these factors is 0.226<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 864.6
- 400 + ( ( 0.226 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 864.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |      127 | 2024-08-02 | Rare Atom   | L   | 1.000      | -            | -                | -                | -         |   -14.08 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           19 |      158 | 2024-08-01 | CatEvil     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.230 (0.033)    | 0 (0.000) |     6.58 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           18 |      168 | 2024-08-01 | Rare Atom   | L   | 1.000      | -            | -                | -                | -         |   -14.29 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           17 |     1286 | 2024-06-09 | Lynn Vision | L   | 0.813      | -            | -                | -                | -         |    -7.70 | Annihilation, dobu, kabal, MiQ, Zesta |
|           16 |     1466 | 2024-06-06 | Lynn Vision | W   | 0.793      | 0.416        | 0.086 (0.028)    | 0.182 (0.060)    | 0 (0.000) |    17.70 | Annihilation, dobu, kabal, MiQ, Zesta |
|           15 |     1525 | 2024-06-05 | GR          | W   | 0.787      | 0.416        | 0.008 (0.003)    | 0.072 (0.024)    | 0 (0.000) |     5.81 | Annihilation, dobu, kabal, MiQ, Zesta |
|           14 |     1564 | 2024-06-04 | -72c        | W   | 0.780      | 0.416        | 0.003 (0.001)    | 0.038 (0.012)    | 0 (0.000) |     5.34 | Annihilation, dobu, kabal, MiQ, Zesta |
|           13 |     1653 | 2024-05-31 | Lynn Vision | L   | 0.757      | -            | -                | -                | -         |    -6.64 | Annihilation, dobu, kabal, MiQ, Zesta |
|           12 |     1706 | 2024-05-29 | BLEED       | L   | 0.744      | -            | -                | -                | -         |    -1.43 | Annihilation, dobu, kabal, MiQ, Zesta |
|           11 |     1729 | 2024-05-29 | OG          | W   | 0.739      | 0.500        | 0.137 (0.051)    | 0.120 (0.044)    | 1 (0.739) |    16.72 | Annihilation, dobu, kabal, MiQ, Zesta |
|           10 |     2022 | 2024-05-18 | The MongolZ | L   | 0.665      | -            | -                | -                | -         |    -0.07 | Annihilation, dobu, kabal, MiQ, Zesta |
|            9 |     2053 | 2024-05-17 | The Huns    | W   | 0.659      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | 1 (0.659) |     1.36 | Annihilation, dobu, kabal, MiQ, Zesta |
|            8 |     3287 | 2024-04-02 | The MongolZ | L   | 0.360      | -            | -                | -                | -         |    -0.03 | Annihilation, dobu, kabal, MiQ, Zesta |
|            7 |     3292 | 2024-04-02 | Lynn Vision | L   | 0.359      | -            | -                | -                | -         |    -2.92 | Annihilation, dobu, kabal, MiQ, Zesta |
|            6 |     3650 | 2024-03-13 | -72c        | W   | 0.226      | 0.143        | 0.000 (0.000)    | 0.009 (0.000)    | 0 (0.000) |     0.50 | dobu, FlyNN, kabal, MiQ, Zesta        |
|            5 |     3660 | 2024-03-13 | ROUX        | W   | 0.226      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.49 | dobu, FlyNN, kabal, MiQ, Zesta        |
|            4 |     3981 | 2024-02-27 | FlyQuest    | L   | 0.131      | -            | -                | -                | -         |    -0.69 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            3 |     4005 | 2024-02-26 | TYLOO       | W   | 0.125      | 0.143        | 0.019 (0.000)    | 0.086 (0.002)    | 1 (0.125) |     1.42 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            2 |     4008 | 2024-02-26 | MAG         | W   | 0.124      | 0.143        | 0.000 (0.000)    | 0.005 (0.000)    | 1 (0.124) |     0.41 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            1 |     4021 | 2024-02-25 | FlyQuest    | L   | 0.117      | -            | -                | -                | -         |    -0.62 | AccuracyTG, dobu, kabal, MiQ, Zesta   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,501.48)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
