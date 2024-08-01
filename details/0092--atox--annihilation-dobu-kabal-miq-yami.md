### Roster Details<br />
Team Name: ATOX<br />
Roster: Annihilation, dobu, kabal, MiQ, yAmi<br />
Global Rank: [92](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [4]( ../standings_asia.md)<br />
<br />
Final Rank Value:  876.2<br />
<br />
Final Rank Value (876.2) = Starting Rank Value (872.4) + Head To Head Adjustments (3.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.372[<sup>1</sup>](#table2)
- Bounty Collected: 0.327[<sup>2</sup>](#table1)
- Opponent Network: 0.015[<sup>2</sup>](#table1)
- LAN Wins: 0.205[<sup>2</sup>](#table1)

The average of these factors is 0.230<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 872.4
- 400 + ( ( 0.230 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 872.4


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
|           18 |       12 | 2024-08-01 | Rare Atom   | L   | 1.000      | -            | -                | -                | -         |   -20.48 | Annihilation, dobu, kabal, MiQ, yAmi  |
|           17 |     1140 | 2024-06-09 | Lynn Vision | L   | 0.845      | -            | -                | -                | -         |    -9.81 | Annihilation, dobu, kabal, MiQ, Zesta |
|           16 |     1331 | 2024-06-06 | Lynn Vision | W   | 0.825      | 0.416        | 0.080 (0.027)    | 0.156 (0.054)    | 0 (0.000) |    16.63 | Annihilation, dobu, kabal, MiQ, Zesta |
|           15 |     1392 | 2024-06-05 | GR          | W   | 0.819      | 0.416        | 0.008 (0.003)    | 0.076 (0.026)    | 0 (0.000) |     5.90 | Annihilation, dobu, kabal, MiQ, Zesta |
|           14 |     1431 | 2024-06-04 | -72c        | W   | 0.812      | 0.416        | 0.003 (0.001)    | 0.039 (0.013)    | 0 (0.000) |     5.44 | Annihilation, dobu, kabal, MiQ, Zesta |
|           13 |     1521 | 2024-05-31 | Lynn Vision | L   | 0.789      | -            | -                | -                | -         |    -8.60 | Annihilation, dobu, kabal, MiQ, Zesta |
|           12 |     1574 | 2024-05-29 | BLEED       | L   | 0.776      | -            | -                | -                | -         |    -1.52 | Annihilation, dobu, kabal, MiQ, Zesta |
|           11 |     1597 | 2024-05-29 | OG          | W   | 0.771      | 0.500        | 0.143 (0.055)    | 0.132 (0.051)    | 1 (0.771) |    17.26 | Annihilation, dobu, kabal, MiQ, Zesta |
|           10 |     1918 | 2024-05-18 | The MongolZ | L   | 0.698      | -            | -                | -                | -         |    -0.07 | Annihilation, dobu, kabal, MiQ, Zesta |
|            9 |     1949 | 2024-05-17 | The Huns    | W   | 0.691      | 0.143        | 0.000 (0.000)    | 0.003 (0.000)    | 1 (0.691) |     1.37 | Annihilation, dobu, kabal, MiQ, Zesta |
|            8 |     3216 | 2024-04-02 | The MongolZ | L   | 0.392      | -            | -                | -                | -         |    -0.04 | Annihilation, dobu, kabal, MiQ, Zesta |
|            7 |     3221 | 2024-04-02 | Lynn Vision | L   | 0.391      | -            | -                | -                | -         |    -4.05 | Annihilation, dobu, kabal, MiQ, Zesta |
|            6 |     3588 | 2024-03-13 | -72c        | W   | 0.258      | 0.143        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     0.54 | dobu, FlyNN, kabal, MiQ, Zesta        |
|            5 |     3598 | 2024-03-13 | ROUX        | W   | 0.258      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.54 | dobu, FlyNN, kabal, MiQ, Zesta        |
|            4 |     3928 | 2024-02-27 | FlyQuest    | L   | 0.163      | -            | -                | -                | -         |    -0.80 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            3 |     3952 | 2024-02-26 | TYLOO       | W   | 0.157      | 0.143        | 0.020 (0.000)    | 0.094 (0.002)    | 1 (0.157) |     1.77 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            2 |     3955 | 2024-02-26 | MAG         | W   | 0.156      | 0.143        | 0.000 (0.000)    | 0.009 (0.000)    | 1 (0.156) |     0.51 | AccuracyTG, dobu, kabal, MiQ, Zesta   |
|            1 |     3969 | 2024-02-25 | FlyQuest    | L   | 0.149      | -            | -                | -                | -         |    -0.73 | AccuracyTG, dobu, kabal, MiQ, Zesta   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,757.78)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
