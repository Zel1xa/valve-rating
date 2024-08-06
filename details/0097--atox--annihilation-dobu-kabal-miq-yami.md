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
Final Rank Value (872.5) = Starting Rank Value (864.7) + Head To Head Adjustments (7.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.371[<sup>1</sup>](#table2)
- Bounty Collected: 0.325[<sup>2</sup>](#table1)
- Opponent Network: 0.018[<sup>2</sup>](#table1)
- LAN Wins: 0.190[<sup>2</sup>](#table1)

The average of these factors is 0.226<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 864.7
- 400 + ( ( 0.226 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 864.7


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
|           20 |      124 | 2024-08-02 | Rare Atom   | L   | 1.000      | -            | -                | -                | -         |   -14.08 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           19 |      155 | 2024-08-01 | CatEvil     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.230 (0.033)    | 0 (0.000) |     6.57 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           18 |      165 | 2024-08-01 | Rare Atom   | L   | 1.000      | -            | -                | -                | -         |   -14.30 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           17 |     1283 | 2024-06-09 | Lynn Vision | L   | 0.813      | -            | -                | -                | -         |    -7.71 | Annihilation, dobu, kabal, MiQ, Zesta |
|           16 |     1463 | 2024-06-06 | Lynn Vision | W   | 0.794      | 0.416        | 0.086 (0.028)    | 0.182 (0.060)    | 0 (0.000) |    17.71 | Annihilation, dobu, kabal, MiQ, Zesta |
|           15 |     1522 | 2024-06-05 | GR          | W   | 0.787      | 0.416        | 0.008 (0.003)    | 0.072 (0.024)    | 0 (0.000) |     5.81 | Annihilation, dobu, kabal, MiQ, Zesta |
|           14 |     1561 | 2024-06-04 | -72c        | W   | 0.780      | 0.416        | 0.003 (0.001)    | 0.038 (0.012)    | 0 (0.000) |     5.34 | Annihilation, dobu, kabal, MiQ, Zesta |
|           13 |     1650 | 2024-05-31 | Lynn Vision | L   | 0.758      | -            | -                | -                | -         |    -6.64 | Annihilation, dobu, kabal, MiQ, Zesta |
|           12 |     1703 | 2024-05-29 | BLEED       | L   | 0.745      | -            | -                | -                | -         |    -1.43 | Annihilation, dobu, kabal, MiQ, Zesta |
|           11 |     1726 | 2024-05-29 | OG          | W   | 0.739      | 0.500        | 0.137 (0.051)    | 0.120 (0.044)    | 1 (0.739) |    16.73 | Annihilation, dobu, kabal, MiQ, Zesta |
|           10 |     2019 | 2024-05-18 | The MongolZ | L   | 0.666      | -            | -                | -                | -         |    -0.07 | Annihilation, dobu, kabal, MiQ, Zesta |
|            9 |     2050 | 2024-05-17 | The Huns    | W   | 0.659      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | 1 (0.659) |     1.36 | Annihilation, dobu, kabal, MiQ, Zesta |
|            8 |     3284 | 2024-04-02 | The MongolZ | L   | 0.360      | -            | -                | -                | -         |    -0.03 | Annihilation, dobu, kabal, MiQ, Zesta |
|            7 |     3289 | 2024-04-02 | Lynn Vision | L   | 0.359      | -            | -                | -                | -         |    -2.93 | Annihilation, dobu, kabal, MiQ, Zesta |
|            6 |     3647 | 2024-03-13 | -72c        | W   | 0.227      | 0.143        | 0.000 (0.000)    | 0.009 (0.000)    | 0 (0.000) |     0.50 | dobu, FlyNN, kabal, MiQ, Zesta        |
|            5 |     3657 | 2024-03-13 | ROUX        | W   | 0.226      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.49 | dobu, FlyNN, kabal, MiQ, Zesta        |
|            4 |     3978 | 2024-02-27 | FlyQuest    | L   | 0.131      | -            | -                | -                | -         |    -0.69 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            3 |     4002 | 2024-02-26 | TYLOO       | W   | 0.125      | 0.143        | 0.019 (0.000)    | 0.086 (0.002)    | 1 (0.125) |     1.43 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            2 |     4005 | 2024-02-26 | MAG         | W   | 0.124      | 0.143        | 0.000 (0.000)    | 0.005 (0.000)    | 1 (0.124) |     0.42 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            1 |     4018 | 2024-02-25 | FlyQuest    | L   | 0.118      | -            | -                | -                | -         |    -0.62 | AccuracyTG, dobu, kabal, MiQ, Zesta   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,504.44)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
