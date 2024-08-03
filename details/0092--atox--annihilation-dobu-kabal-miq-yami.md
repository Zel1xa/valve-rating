### Roster Details<br />
Team Name: ATOX<br />
Roster: Annihilation, dobu, kabal, MiQ, yAmi<br />
Global Rank: [92](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [4]( ../standings_asia.md)<br />
<br />
Final Rank Value:  869.5<br />
<br />
Final Rank Value (869.5) = Starting Rank Value (864.1) + Head To Head Adjustments (5.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.372[<sup>1</sup>](#table2)
- Bounty Collected: 0.325[<sup>2</sup>](#table1)
- Opponent Network: 0.015[<sup>2</sup>](#table1)
- LAN Wins: 0.196[<sup>2</sup>](#table1)

The average of these factors is 0.227<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 864.1
- 400 + ( ( 0.227 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 864.1


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
|           18 |       72 | 2024-08-01 | Rare Atom   | L   | 1.000      | -            | -                | -                | -         |   -18.77 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           17 |     1156 | 2024-06-09 | Lynn Vision | L   | 0.831      | -            | -                | -                | -         |    -9.73 | Annihilation, dobu, kabal, MiQ, Zesta |
|           16 |     1331 | 2024-06-06 | Lynn Vision | W   | 0.812      | 0.416        | 0.078 (0.026)    | 0.159 (0.054)    | 0 (0.000) |    16.28 | Annihilation, dobu, kabal, MiQ, Zesta |
|           15 |     1390 | 2024-06-05 | GR          | W   | 0.805      | 0.416        | 0.008 (0.003)    | 0.078 (0.026)    | 0 (0.000) |     5.97 | Annihilation, dobu, kabal, MiQ, Zesta |
|           14 |     1428 | 2024-06-04 | -72c        | W   | 0.799      | 0.416        | 0.003 (0.001)    | 0.040 (0.013)    | 0 (0.000) |     5.50 | Annihilation, dobu, kabal, MiQ, Zesta |
|           13 |     1515 | 2024-05-31 | Lynn Vision | L   | 0.776      | -            | -                | -                | -         |    -8.55 | Annihilation, dobu, kabal, MiQ, Zesta |
|           12 |     1568 | 2024-05-29 | BLEED       | L   | 0.763      | -            | -                | -                | -         |    -1.47 | Annihilation, dobu, kabal, MiQ, Zesta |
|           11 |     1591 | 2024-05-29 | OG          | W   | 0.757      | 0.500        | 0.140 (0.053)    | 0.133 (0.050)    | 1 (0.757) |    17.02 | Annihilation, dobu, kabal, MiQ, Zesta |
|           10 |     1882 | 2024-05-18 | The MongolZ | L   | 0.684      | -            | -                | -                | -         |    -0.07 | Annihilation, dobu, kabal, MiQ, Zesta |
|            9 |     1913 | 2024-05-17 | The Huns    | W   | 0.678      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | 1 (0.678) |     1.41 | Annihilation, dobu, kabal, MiQ, Zesta |
|            8 |     3145 | 2024-04-02 | The MongolZ | L   | 0.379      | -            | -                | -                | -         |    -0.03 | Annihilation, dobu, kabal, MiQ, Zesta |
|            7 |     3150 | 2024-04-02 | Lynn Vision | L   | 0.378      | -            | -                | -                | -         |    -3.98 | Annihilation, dobu, kabal, MiQ, Zesta |
|            6 |     3501 | 2024-03-13 | -72c        | W   | 0.245      | 0.143        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     0.54 | dobu, FlyNN, kabal, MiQ, Zesta        |
|            5 |     3511 | 2024-03-13 | ROUX        | W   | 0.245      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.53 | dobu, FlyNN, kabal, MiQ, Zesta        |
|            4 |     3831 | 2024-02-27 | FlyQuest    | L   | 0.150      | -            | -                | -                | -         |    -0.76 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            3 |     3855 | 2024-02-26 | TYLOO       | W   | 0.144      | 0.143        | 0.019 (0.000)    | 0.096 (0.002)    | 1 (0.144) |     1.64 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            2 |     3858 | 2024-02-26 | MAG         | W   | 0.143      | 0.143        | 0.000 (0.000)    | 0.008 (0.000)    | 1 (0.143) |     0.48 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            1 |     3871 | 2024-02-25 | FlyQuest    | L   | 0.136      | -            | -                | -                | -         |    -0.69 | AccuracyTG, dobu, kabal, MiQ, Zesta   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,651.48)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
