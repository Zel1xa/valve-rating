### Roster Details<br />
Team Name: ATOX<br />
Roster: Annihilation, dobu, kabal, MiQ, yAmi<br />
Global Rank: [95](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [4]( ../standings_asia.md)<br />
<br />
Final Rank Value:  863.4<br />
<br />
Final Rank Value (863.4) = Starting Rank Value (864.5) + Head To Head Adjustments (-1.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.372[<sup>1</sup>](#table2)
- Bounty Collected: 0.324[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.194[<sup>2</sup>](#table1)

The average of these factors is 0.227<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 864.5
- 400 + ( ( 0.227 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 864.5


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
|           20 |       87 | 2024-08-02 | Rare Atom   | L   | 1.000      | -            | -                | -                | -         |   -18.24 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           19 |      118 | 2024-08-01 | CatEvil     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.236 (0.034)    | 0 (0.000) |     6.42 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           18 |      128 | 2024-08-01 | Rare Atom   | L   | 1.000      | -            | -                | -                | -         |   -18.92 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           17 |     1246 | 2024-06-09 | Lynn Vision | L   | 0.825      | -            | -                | -                | -         |    -8.05 | Annihilation, dobu, kabal, MiQ, Zesta |
|           16 |     1426 | 2024-06-06 | Lynn Vision | W   | 0.806      | 0.416        | 0.078 (0.026)    | 0.192 (0.064)    | 0 (0.000) |    17.80 | Annihilation, dobu, kabal, MiQ, Zesta |
|           15 |     1485 | 2024-06-05 | GR          | W   | 0.799      | 0.416        | 0.008 (0.003)    | 0.076 (0.025)    | 0 (0.000) |     5.86 | Annihilation, dobu, kabal, MiQ, Zesta |
|           14 |     1524 | 2024-06-04 | -72c        | W   | 0.792      | 0.416        | 0.003 (0.001)    | 0.039 (0.013)    | 0 (0.000) |     5.39 | Annihilation, dobu, kabal, MiQ, Zesta |
|           13 |     1613 | 2024-05-31 | Lynn Vision | L   | 0.770      | -            | -                | -                | -         |    -6.87 | Annihilation, dobu, kabal, MiQ, Zesta |
|           12 |     1666 | 2024-05-29 | BLEED       | L   | 0.757      | -            | -                | -                | -         |    -1.49 | Annihilation, dobu, kabal, MiQ, Zesta |
|           11 |     1689 | 2024-05-29 | OG          | W   | 0.751      | 0.500        | 0.139 (0.052)    | 0.128 (0.048)    | 1 (0.751) |    17.11 | Annihilation, dobu, kabal, MiQ, Zesta |
|           10 |     1982 | 2024-05-18 | The MongolZ | L   | 0.678      | -            | -                | -                | -         |    -0.07 | Annihilation, dobu, kabal, MiQ, Zesta |
|            9 |     2013 | 2024-05-17 | The Huns    | W   | 0.672      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | 1 (0.672) |     1.39 | Annihilation, dobu, kabal, MiQ, Zesta |
|            8 |     3247 | 2024-04-02 | The MongolZ | L   | 0.373      | -            | -                | -                | -         |    -0.03 | Annihilation, dobu, kabal, MiQ, Zesta |
|            7 |     3252 | 2024-04-02 | Lynn Vision | L   | 0.371      | -            | -                | -                | -         |    -3.06 | Annihilation, dobu, kabal, MiQ, Zesta |
|            6 |     3610 | 2024-03-13 | -72c        | W   | 0.239      | 0.143        | 0.000 (0.000)    | 0.009 (0.000)    | 0 (0.000) |     0.53 | dobu, FlyNN, kabal, MiQ, Zesta        |
|            5 |     3620 | 2024-03-13 | ROUX        | W   | 0.239      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.52 | dobu, FlyNN, kabal, MiQ, Zesta        |
|            4 |     3941 | 2024-02-27 | FlyQuest    | L   | 0.144      | -            | -                | -                | -         |    -0.73 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            3 |     3965 | 2024-02-26 | TYLOO       | W   | 0.138      | 0.143        | 0.019 (0.000)    | 0.092 (0.002)    | 1 (0.138) |     1.56 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            2 |     3968 | 2024-02-26 | MAG         | W   | 0.136      | 0.143        | 0.000 (0.000)    | 0.007 (0.000)    | 1 (0.136) |     0.46 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            1 |     3981 | 2024-02-25 | FlyQuest    | L   | 0.130      | -            | -                | -                | -         |    -0.66 | AccuracyTG, dobu, kabal, MiQ, Zesta   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,601.48)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
