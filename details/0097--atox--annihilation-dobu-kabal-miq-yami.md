### Roster Details<br />
Team Name: ATOX<br />
Roster: Annihilation, dobu, kabal, MiQ, yAmi<br />
Global Rank: [97](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [6]( ../standings_asia.md)<br />
<br />
Final Rank Value:  872.3<br />
<br />
Final Rank Value (872.3) = Starting Rank Value (864.6) + Head To Head Adjustments (7.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.371[<sup>1</sup>](#table2)
- Bounty Collected: 0.325[<sup>2</sup>](#table1)
- Opponent Network: 0.018[<sup>2</sup>](#table1)
- LAN Wins: 0.192[<sup>2</sup>](#table1)

The average of these factors is 0.227<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 864.6
- 400 + ( ( 0.227 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 864.6


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
|           20 |      114 | 2024-08-02 | Rare Atom   | L   | 1.000      | -            | -                | -                | -         |   -14.23 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           19 |      145 | 2024-08-01 | CatEvil     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.235 (0.034)    | 0 (0.000) |     6.56 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           18 |      155 | 2024-08-01 | Rare Atom   | L   | 1.000      | -            | -                | -                | -         |   -14.47 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           17 |     1273 | 2024-06-09 | Lynn Vision | L   | 0.818      | -            | -                | -                | -         |    -7.74 | Annihilation, dobu, kabal, MiQ, Zesta |
|           16 |     1453 | 2024-06-06 | Lynn Vision | W   | 0.798      | 0.416        | 0.086 (0.029)    | 0.187 (0.062)    | 0 (0.000) |    17.82 | Annihilation, dobu, kabal, MiQ, Zesta |
|           15 |     1512 | 2024-06-05 | GR          | W   | 0.792      | 0.416        | 0.008 (0.003)    | 0.074 (0.024)    | 0 (0.000) |     5.82 | Annihilation, dobu, kabal, MiQ, Zesta |
|           14 |     1551 | 2024-06-04 | -72c        | W   | 0.785      | 0.416        | 0.003 (0.001)    | 0.039 (0.013)    | 0 (0.000) |     5.35 | Annihilation, dobu, kabal, MiQ, Zesta |
|           13 |     1640 | 2024-05-31 | Lynn Vision | L   | 0.762      | -            | -                | -                | -         |    -6.67 | Annihilation, dobu, kabal, MiQ, Zesta |
|           12 |     1693 | 2024-05-29 | BLEED       | L   | 0.749      | -            | -                | -                | -         |    -1.44 | Annihilation, dobu, kabal, MiQ, Zesta |
|           11 |     1716 | 2024-05-29 | OG          | W   | 0.743      | 0.500        | 0.138 (0.051)    | 0.124 (0.046)    | 1 (0.743) |    16.88 | Annihilation, dobu, kabal, MiQ, Zesta |
|           10 |     2009 | 2024-05-18 | The MongolZ | L   | 0.670      | -            | -                | -                | -         |    -0.07 | Annihilation, dobu, kabal, MiQ, Zesta |
|            9 |     2040 | 2024-05-17 | The Huns    | W   | 0.664      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | 1 (0.664) |     1.37 | Annihilation, dobu, kabal, MiQ, Zesta |
|            8 |     3274 | 2024-04-02 | The MongolZ | L   | 0.365      | -            | -                | -                | -         |    -0.03 | Annihilation, dobu, kabal, MiQ, Zesta |
|            7 |     3279 | 2024-04-02 | Lynn Vision | L   | 0.364      | -            | -                | -                | -         |    -2.95 | Annihilation, dobu, kabal, MiQ, Zesta |
|            6 |     3637 | 2024-03-13 | -72c        | W   | 0.231      | 0.143        | 0.000 (0.000)    | 0.009 (0.000)    | 0 (0.000) |     0.51 | dobu, FlyNN, kabal, MiQ, Zesta        |
|            5 |     3647 | 2024-03-13 | ROUX        | W   | 0.231      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.50 | dobu, FlyNN, kabal, MiQ, Zesta        |
|            4 |     3968 | 2024-02-27 | FlyQuest    | L   | 0.136      | -            | -                | -                | -         |    -0.71 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            3 |     3992 | 2024-02-26 | TYLOO       | W   | 0.130      | 0.143        | 0.019 (0.000)    | 0.089 (0.002)    | 1 (0.130) |     1.48 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            2 |     3995 | 2024-02-26 | MAG         | W   | 0.129      | 0.143        | 0.000 (0.000)    | 0.006 (0.000)    | 1 (0.129) |     0.43 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            1 |     4008 | 2024-02-25 | FlyQuest    | L   | 0.122      | -            | -                | -                | -         |    -0.64 | AccuracyTG, dobu, kabal, MiQ, Zesta   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,541.11)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
