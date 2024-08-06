### Roster Details<br />
Team Name: ATOX<br />
Roster: Annihilation, dobu, kabal, MiQ, yAmi<br />
Global Rank: [99](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [7]( ../standings_asia.md)<br />
<br />
Final Rank Value:  873.9<br />
<br />
Final Rank Value (873.9) = Starting Rank Value (864.5) + Head To Head Adjustments (9.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.371[<sup>1</sup>](#table2)
- Bounty Collected: 0.324[<sup>2</sup>](#table1)
- Opponent Network: 0.018[<sup>2</sup>](#table1)
- LAN Wins: 0.190[<sup>2</sup>](#table1)

The average of these factors is 0.226<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 864.5
- 400 + ( ( 0.226 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 864.5


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
|           20 |      132 | 2024-08-02 | Rare Atom   | L   | 1.000      | -            | -                | -                | -         |   -13.73 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           19 |      163 | 2024-08-01 | CatEvil     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.231 (0.033)    | 0 (0.000) |     6.67 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           18 |      173 | 2024-08-01 | Rare Atom   | L   | 1.000      | -            | -                | -                | -         |   -14.08 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           17 |     1291 | 2024-06-09 | Lynn Vision | L   | 0.812      | -            | -                | -                | -         |    -7.33 | Annihilation, dobu, kabal, MiQ, Zesta |
|           16 |     1471 | 2024-06-06 | Lynn Vision | W   | 0.793      | 0.416        | 0.086 (0.028)    | 0.182 (0.060)    | 0 (0.000) |    17.98 | Annihilation, dobu, kabal, MiQ, Zesta |
|           15 |     1530 | 2024-06-05 | GR          | W   | 0.786      | 0.416        | 0.008 (0.003)    | 0.072 (0.024)    | 0 (0.000) |     5.80 | Annihilation, dobu, kabal, MiQ, Zesta |
|           14 |     1569 | 2024-06-04 | -72c        | W   | 0.779      | 0.416        | 0.003 (0.001)    | 0.038 (0.012)    | 0 (0.000) |     5.33 | Annihilation, dobu, kabal, MiQ, Zesta |
|           13 |     1658 | 2024-05-31 | Lynn Vision | L   | 0.757      | -            | -                | -                | -         |    -6.44 | Annihilation, dobu, kabal, MiQ, Zesta |
|           12 |     1711 | 2024-05-29 | BLEED       | L   | 0.744      | -            | -                | -                | -         |    -1.42 | Annihilation, dobu, kabal, MiQ, Zesta |
|           11 |     1734 | 2024-05-29 | OG          | W   | 0.738      | 0.500        | 0.137 (0.050)    | 0.120 (0.044)    | 1 (0.738) |    16.70 | Annihilation, dobu, kabal, MiQ, Zesta |
|           10 |     2027 | 2024-05-18 | The MongolZ | L   | 0.665      | -            | -                | -                | -         |    -0.07 | Annihilation, dobu, kabal, MiQ, Zesta |
|            9 |     2058 | 2024-05-17 | The Huns    | W   | 0.659      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | 1 (0.659) |     1.36 | Annihilation, dobu, kabal, MiQ, Zesta |
|            8 |     3292 | 2024-04-02 | The MongolZ | L   | 0.359      | -            | -                | -                | -         |    -0.03 | Annihilation, dobu, kabal, MiQ, Zesta |
|            7 |     3297 | 2024-04-02 | Lynn Vision | L   | 0.358      | -            | -                | -                | -         |    -2.82 | Annihilation, dobu, kabal, MiQ, Zesta |
|            6 |     3655 | 2024-03-13 | -72c        | W   | 0.226      | 0.143        | 0.000 (0.000)    | 0.009 (0.000)    | 0 (0.000) |     0.50 | dobu, FlyNN, kabal, MiQ, Zesta        |
|            5 |     3665 | 2024-03-13 | ROUX        | W   | 0.225      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.49 | dobu, FlyNN, kabal, MiQ, Zesta        |
|            4 |     3986 | 2024-02-27 | FlyQuest    | L   | 0.130      | -            | -                | -                | -         |    -0.69 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            3 |     4010 | 2024-02-26 | TYLOO       | W   | 0.124      | 0.143        | 0.019 (0.000)    | 0.086 (0.002)    | 1 (0.124) |     1.42 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            2 |     4013 | 2024-02-26 | MAG         | W   | 0.123      | 0.143        | 0.000 (0.000)    | 0.005 (0.000)    | 1 (0.123) |     0.41 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            1 |     4026 | 2024-02-25 | FlyQuest    | L   | 0.117      | -            | -                | -                | -         |    -0.61 | AccuracyTG, dobu, kabal, MiQ, Zesta   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,497.04)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
