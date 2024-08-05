### Roster Details<br />
Team Name: ATOX<br />
Roster: Annihilation, dobu, kabal, MiQ, yAmi<br />
Global Rank: [95](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [4]( ../standings_asia.md)<br />
<br />
Final Rank Value:  862.9<br />
<br />
Final Rank Value (862.9) = Starting Rank Value (864.0) + Head To Head Adjustments (-1.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.372[<sup>1</sup>](#table2)
- Bounty Collected: 0.324[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.193[<sup>2</sup>](#table1)

The average of these factors is 0.227<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 864.0
- 400 + ( ( 0.227 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 864.0


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
|           20 |       92 | 2024-08-02 | Rare Atom   | L   | 1.000      | -            | -                | -                | -         |   -18.22 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           19 |      123 | 2024-08-01 | CatEvil     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.237 (0.034)    | 0 (0.000) |     6.44 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           18 |      133 | 2024-08-01 | Rare Atom   | L   | 1.000      | -            | -                | -                | -         |   -18.89 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           17 |     1251 | 2024-06-09 | Lynn Vision | L   | 0.823      | -            | -                | -                | -         |    -8.03 | Annihilation, dobu, kabal, MiQ, Zesta |
|           16 |     1431 | 2024-06-06 | Lynn Vision | W   | 0.803      | 0.416        | 0.078 (0.026)    | 0.191 (0.064)    | 0 (0.000) |    17.73 | Annihilation, dobu, kabal, MiQ, Zesta |
|           15 |     1490 | 2024-06-05 | GR          | W   | 0.796      | 0.416        | 0.008 (0.003)    | 0.075 (0.025)    | 0 (0.000) |     5.85 | Annihilation, dobu, kabal, MiQ, Zesta |
|           14 |     1529 | 2024-06-04 | -72c        | W   | 0.790      | 0.416        | 0.003 (0.001)    | 0.040 (0.013)    | 0 (0.000) |     5.38 | Annihilation, dobu, kabal, MiQ, Zesta |
|           13 |     1618 | 2024-05-31 | Lynn Vision | L   | 0.767      | -            | -                | -                | -         |    -6.86 | Annihilation, dobu, kabal, MiQ, Zesta |
|           12 |     1671 | 2024-05-29 | BLEED       | L   | 0.754      | -            | -                | -                | -         |    -1.48 | Annihilation, dobu, kabal, MiQ, Zesta |
|           11 |     1694 | 2024-05-29 | OG          | W   | 0.748      | 0.500        | 0.138 (0.052)    | 0.127 (0.047)    | 1 (0.748) |    17.04 | Annihilation, dobu, kabal, MiQ, Zesta |
|           10 |     1987 | 2024-05-18 | The MongolZ | L   | 0.675      | -            | -                | -                | -         |    -0.07 | Annihilation, dobu, kabal, MiQ, Zesta |
|            9 |     2018 | 2024-05-17 | The Huns    | W   | 0.669      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | 1 (0.669) |     1.39 | Annihilation, dobu, kabal, MiQ, Zesta |
|            8 |     3252 | 2024-04-02 | The MongolZ | L   | 0.370      | -            | -                | -                | -         |    -0.03 | Annihilation, dobu, kabal, MiQ, Zesta |
|            7 |     3257 | 2024-04-02 | Lynn Vision | L   | 0.369      | -            | -                | -                | -         |    -3.04 | Annihilation, dobu, kabal, MiQ, Zesta |
|            6 |     3615 | 2024-03-13 | -72c        | W   | 0.236      | 0.143        | 0.000 (0.000)    | 0.009 (0.000)    | 0 (0.000) |     0.52 | dobu, FlyNN, kabal, MiQ, Zesta        |
|            5 |     3625 | 2024-03-13 | ROUX        | W   | 0.236      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.51 | dobu, FlyNN, kabal, MiQ, Zesta        |
|            4 |     3946 | 2024-02-27 | FlyQuest    | L   | 0.141      | -            | -                | -                | -         |    -0.72 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            3 |     3970 | 2024-02-26 | TYLOO       | W   | 0.135      | 0.143        | 0.019 (0.000)    | 0.091 (0.002)    | 1 (0.135) |     1.53 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            2 |     3973 | 2024-02-26 | MAG         | W   | 0.134      | 0.143        | 0.000 (0.000)    | 0.007 (0.000)    | 1 (0.134) |     0.45 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            1 |     3986 | 2024-02-25 | FlyQuest    | L   | 0.127      | -            | -                | -                | -         |    -0.65 | AccuracyTG, dobu, kabal, MiQ, Zesta   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,580.00)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
