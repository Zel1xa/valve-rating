### Roster Details<br />
Team Name: ATOX<br />
Roster: Annihilation, dobu, kabal, MiQ, yAmi<br />
Global Rank: [95](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [4]( ../standings_asia.md)<br />
<br />
Final Rank Value:  857.7<br />
<br />
Final Rank Value (857.7) = Starting Rank Value (864.1) + Head To Head Adjustments (-6.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.372[<sup>1</sup>](#table2)
- Bounty Collected: 0.324[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.195[<sup>2</sup>](#table1)

The average of these factors is 0.227<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 864.1
- 400 + ( ( 0.227 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 864.1


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
|           20 |       58 | 2024-08-02 | Rare Atom   | L   | 1.000      | -            | -                | -                | -         |   -18.18 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           19 |       88 | 2024-08-01 | CatEvil     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.236 (0.034)    | 0 (0.000) |     6.47 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           18 |       97 | 2024-08-01 | Rare Atom   | L   | 1.000      | -            | -                | -                | -         |   -18.74 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           17 |     1215 | 2024-06-09 | Lynn Vision | L   | 0.827      | -            | -                | -                | -         |    -9.69 | Annihilation, dobu, kabal, MiQ, Zesta |
|           16 |     1395 | 2024-06-06 | Lynn Vision | W   | 0.807      | 0.416        | 0.078 (0.026)    | 0.152 (0.051)    | 0 (0.000) |    16.17 | Annihilation, dobu, kabal, MiQ, Zesta |
|           15 |     1454 | 2024-06-05 | GR          | W   | 0.801      | 0.416        | 0.008 (0.003)    | 0.076 (0.025)    | 0 (0.000) |     5.93 | Annihilation, dobu, kabal, MiQ, Zesta |
|           14 |     1493 | 2024-06-04 | -72c        | W   | 0.794      | 0.416        | 0.003 (0.001)    | 0.039 (0.013)    | 0 (0.000) |     5.47 | Annihilation, dobu, kabal, MiQ, Zesta |
|           13 |     1582 | 2024-05-31 | Lynn Vision | L   | 0.771      | -            | -                | -                | -         |    -8.52 | Annihilation, dobu, kabal, MiQ, Zesta |
|           12 |     1635 | 2024-05-29 | BLEED       | L   | 0.758      | -            | -                | -                | -         |    -1.50 | Annihilation, dobu, kabal, MiQ, Zesta |
|           11 |     1658 | 2024-05-29 | OG          | W   | 0.752      | 0.500        | 0.139 (0.052)    | 0.128 (0.048)    | 1 (0.752) |    17.15 | Annihilation, dobu, kabal, MiQ, Zesta |
|           10 |     1951 | 2024-05-18 | The MongolZ | L   | 0.679      | -            | -                | -                | -         |    -0.07 | Annihilation, dobu, kabal, MiQ, Zesta |
|            9 |     1982 | 2024-05-17 | The Huns    | W   | 0.673      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | 1 (0.673) |     1.40 | Annihilation, dobu, kabal, MiQ, Zesta |
|            8 |     3216 | 2024-04-02 | The MongolZ | L   | 0.374      | -            | -                | -                | -         |    -0.04 | Annihilation, dobu, kabal, MiQ, Zesta |
|            7 |     3221 | 2024-04-02 | Lynn Vision | L   | 0.373      | -            | -                | -                | -         |    -3.94 | Annihilation, dobu, kabal, MiQ, Zesta |
|            6 |     3579 | 2024-03-13 | -72c        | W   | 0.240      | 0.143        | 0.000 (0.000)    | 0.009 (0.000)    | 0 (0.000) |     0.53 | dobu, FlyNN, kabal, MiQ, Zesta        |
|            5 |     3589 | 2024-03-13 | ROUX        | W   | 0.240      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.52 | dobu, FlyNN, kabal, MiQ, Zesta        |
|            4 |     3910 | 2024-02-27 | FlyQuest    | L   | 0.145      | -            | -                | -                | -         |    -0.74 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            3 |     3934 | 2024-02-26 | TYLOO       | W   | 0.139      | 0.143        | 0.019 (0.000)    | 0.092 (0.002)    | 1 (0.139) |     1.58 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            2 |     3937 | 2024-02-26 | MAG         | W   | 0.138      | 0.143        | 0.000 (0.000)    | 0.007 (0.000)    | 1 (0.138) |     0.47 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            1 |     3950 | 2024-02-25 | FlyQuest    | L   | 0.131      | -            | -                | -                | -         |    -0.67 | AccuracyTG, dobu, kabal, MiQ, Zesta   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,613.33)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
